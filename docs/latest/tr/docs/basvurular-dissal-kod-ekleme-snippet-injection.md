---
id: basvurular-dissal-kod-ekleme-snippet-injection
title: Dışsal Kod Ekleme (Snippet Injection)
sidebar_label: Dışsal Kod Ekleme
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

Kaynak kod üreteçleri tarafından üretilen kod içine bazı durumlarda özel kodlar eklemek isteyebilirsiniz. Ya da üreteçler tarafından üretilen bir kod bloğunu etkisiz hale getirerek kendi kod bloğunuzu kaynak koda eklemek isteyebilirsiniz. Bu gibi durumlarda, Dışsal Kod Ekleme (Snippet Injection) yöntemi pratik bir çözüm sunmaktadır.

Pyronome kaynak kod üreteçleri tarafından kaynak kod üretim sürecinin hemen ardından otomatik olarak Dışsal Kod Ekleme (Snippet Injection) işlemi çalıştırılmakta; gerekli yerlere dışsal kodlar eklenmektedir.

Dışsal kod ekleme sistemi iki bölümden oluşur:
1. Dışsal Kod Belirteci
2. `snippets` Dizin Yapısı

Dışsal Kod Belirteci, kalıp şablonları ya da statik dosyalar içine yerleştirilen `{{@snippet:` ile başlayan belirteçlerdir. Bu belirteçlerin bulunduğu alanlara, dizin yapısı göz önünde bulundurularak, kod ekleme işlemi yapılmaktadır. `snippets` Dizin Yapısı, Dışsal Kod Belirteci ile belirtilen bölümlere kaynak kodun nasıl ekleneceğini belirleyen özel isimlendirmeye ve içeriğe sahip dosya ve dizinlerdir.

## Dışsal Kod Belirteci

Dışsal kodun, kaynak kod dosyası içinde tam olarak nereye ekleneceğini dışsal kod belirteçleri belirlemektedir. Üretilen dosyalar ya da statik dosyalar içerisine bu dosyayı oluşturan kullanıcılar tarafından dışsal kod eklenebilecek bölümler belirlenir ve bu bölümlere `{{@snippet:` ile başlayan belirteçler eklenir. Böylelikle kaynak kod üretim işlemi sonrasında çalıştırılan dışsal kod ekleme işlemi hangi kodun nereye ekleneceğini bulup; kod ekleme işlemini gerçekleştirir.

**Örneğin;**

```php
<?php

namespace App\Providers;

use Illuminate\Foundation\Support\Providers\RouteServiceProvider as ServiceProvider;
use Illuminate\Support\Facades\Route;
use App\Http\Middleware\HTMLDBMiddleware;
use App\Http\Middleware\AdminLTEMiddleware;

class RouteServiceProvider extends ServiceProvider
{

    /* {{@snippet:begin_methods}} */

    /**
     * This namespace is applied to your controller routes.
     *
     * In addition, it is set as the URL generator's root namespace.
     *
     * @var string
     */
    protected $namespace = 'App\Http\Controllers';
```

Yukarıdaki kaynak kod içinde, dışsal kod belirteci, `{{@snippet:begin_methods}}` şeklinde kullanılmıştır. Burada `begin_methods` dışsal kod bloğunun adını belirtmektedir.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Not:</strong>
    </p>
    <p>Kaynak kod dosyasının türüne göre, dışsal kod belirtecinin başına ve/veya sonuna yorum bloğu açma/kapama karakterleri eklenebilir. Dışsal kaynak kod ekleme sürecinde, dışsal kod belirteci geçen satır TAMAMEN SİLİNİR, dışsal kod bloğu bu satıra yazılır.</p>
</div>

## `snippets` Dizin Yapısı

Pyronome kaynak kod üreteçleri tarafından üretilen kaynak kodun aşağıdakine benzer bir dizin yapısı bulunmaktadır:

<pre>
├── pyronome
├── snippets <span class="red-text">*</span>
└── source
</pre>

Oluşturulan kaynak kod içindeki `snippets` dizininin içinde de `system` ve `user` isimli iki dizin daha bulunmaktadır:

<pre>
├── pyronome
├── snippets
│   ├── system <span class="red-text">*</span>
│   └── user <span class="red-text">*</span>
└── source
</pre>

`snippets` dizininin içinde bulunan `system` dizini bir proje için kullanılacak kalıplar tarafından kullanılmak üzere oluşturulmuştur. `user` dizini de proje kullanıcısı tarafından eklenecek dışsal kodlar için oluşturulmuştur. `snippets` dizini içinde öncelikle `system` dizini içindeki kaynak kodlar; daha sonra da `user` dizini içindeki kaynak kodlar eklenir.

**Örneğin;** Aşağıdaki kaynak kod dosyasının `RouteServiceProvider.php` dosya adıyla `source/app/Providers/` dizini içinde yer aldığını varsayalım.

```php
<?php

namespace App\Providers;

use Illuminate\Foundation\Support\Providers\RouteServiceProvider as ServiceProvider;
use Illuminate\Support\Facades\Route;
use App\Http\Middleware\HTMLDBMiddleware;
use App\Http\Middleware\AdminLTEMiddleware;

class RouteServiceProvider extends ServiceProvider
{

    /* {{@snippet:begin_methods}} */

    /**
     * This namespace is applied to your controller routes.
     *
     * In addition, it is set as the URL generator's root namespace.
     *
     * @var string
     */
    protected $namespace = 'App\Http\Controllers';
```

Yukarıdaki `RouteServiceProvider.php` dosyasının içinde bulunan `/* {{@snippet:begin_methods}} */` kod satırı yerine aşağıdaki yorum satırını eklemek istersek:

```php
    /* THIS COMMENT ADDED USING SNIPPET INJECTION */
```

Aşağıdaki `user` dizini içine ilk olarak `source/app/Providers/` dizinini daha sonra da bu dizin içine `RouteServiceProvider.php` DİZİNİNİ oluşturmamız gerekmektedir.

<pre>
├── pyronome
├── snippets
│   ├── system
│   └── user <span class="red-text">*</span>
└── source
</pre>

Dizinler oluşturulduktan sonra aşağıdaki gibi bir görüntüye sahip olur.

<pre>
├── pyronome
├── snippets
│   ├── system
│   └── user
│       └── source
│           └── app
│               └── Providers
│                   └── RouteServiceProvider.php
└── source
</pre>

Oluşturulan `RouteServiceProvider.php` dizini içine dışsal kod belirtecinin adı olan `begin_methods` isimli bir dizin oluşturulmalıdır. Bu dizin içine de örneğin `0000.php` isimli bir dosya oluşturulmalı ve yukarıda belirtilen yorum satırları oluşturulan dosyaya eklenmelidir.

<pre>
├── pyronome
├── snippets
│   ├── system
│   └── user
│       └── source
│           └── app
│               └── Providers
│                   └── RouteServiceProvider.php
│                       └── begin_methods
│                           └── 0000.php
└── source
</pre>

Yukarıda oluşturulan `0000.php` isimli dosyanın içine aşağıdaki yorum satırları eklenmelidir.

```php
    /* THIS COMMENT ADDED USING SNIPPET INJECTION */
```

Kaynak kod üretim işlemi sonrasında çalıştırılan dışsal kod ekleme işlemi sonucunda `source/app/Providers/RouteServiceProvider.php` dosya içeriği aşağıdaki şekilde güncellenecektir.

```php
<?php

namespace App\Providers;

use Illuminate\Foundation\Support\Providers\RouteServiceProvider as ServiceProvider;
use Illuminate\Support\Facades\Route;
use App\Http\Middleware\HTMLDBMiddleware;
use App\Http\Middleware\AdminLTEMiddleware;

class RouteServiceProvider extends ServiceProvider
{

    /* THIS COMMENT ADDED USING SNIPPET INJECTION */

    /**
     * This namespace is applied to your controller routes.
     *
     * In addition, it is set as the URL generator's root namespace.
     *
     * @var string
     */
    protected $namespace = 'App\Http\Controllers';
```

Burada `snippets/user/source/app/Providers/RouteServiceProvider.php/begin_methods` dizini içinde istediğimiz isimle dosya oluşturabiliriz. Oluşturulan dosya isimleri doğal sıralamaya göre artan sırada sıralanarak işlenecektir.

`snippets` dizinleri içine birçok farklı kaynaktan dosya eklenebileceği için, eklenen dosyaların düzenlenmesi için bazı yardımcı dosyalar eklenebilmektedir.

| Yardımcı Dosya | Açıklama |
| --- | ------- |
| `__glue__` | İlgili `snippets` dizini içinde bulunan farklı dosyaları birleştirmek için kullanılan örneğin `,` ya da `;` vb. birleştirme karakterlerini içeren dosyadır. Bu dosya içeriğinin herhangi bir uzunluk ya da karakter sayısı sınırı bulunmamaktadır. `snippets` dizini içinde hiçbir dosya bulunmazsa; bu dosya görmezden gelinir. |
| `__header__` | İlgili `snippets` dizini içinde bulunan farklı dosyaları birleştirirken en başa yazılacak içeriği içeren dosyadır. Bütün dosyalar birleştirildikten sonra en başa `__header__` dosya içeriği eklenmektedir. `snippets` dizini içinde hiçbir dosya bulunmazsa; bu dosya görmezden gelinir. |
| `__footer__` | İlgili `snippets` dizini içinde bulunan farklı dosyaları birleştirirken en sona yazılacak içeriği içeren dosyadır. Bütün dosyalar birleştirildikten sonra en sona `__footer__` dosya içeriği eklenmektedir. `snippets` dizini içinde hiçbir dosya bulunmazsa; bu dosya görmezden gelinir. |
| `__default__` | İlgili `snippets` dizini içinde hiçbir dosya bulunmazsa varsayılan olarak eklenecek içeriği içeren dosyadır. `snippets` dizini içinde dosya bulunuyorsa; bu dosya görmezden gelinir. |