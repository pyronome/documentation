---
id: basvurular-kalip-sablonu-kaynak-kod-yardimcilari
title: Kalıp Şablonu Kaynak Kod Yardımcıları
sidebar_label: Şablon Yardımcıları
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

## Değişkenler

### Küresel Değişkenler

##### `{{$__globals__/PYRONOME_SHORT_VERSION}}`

Pyronome sürümünün kısa halini tutan küresel değişkendir. `3.1.2` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_VERSION}}`

Pyronome sürümünün kısa halini tutan küresel değişkendir. `3.1.2` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_LONG_VERSION}}`

Pyronome sürümünün tam halini tutan küresel değişkendir. `3.1.2+20200430.assets/605a822a/cache` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_NAME}}`

Mevcut proje adını tutan küresel değişkendir. `testproject` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_TITLE}}`

Mevcut proje başlığını tutan küresel değişkendir. `Test Project` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_VERSION}}`

Mevcut proje sürümünü tutan küresel değişkendir. `0.0.0-dev` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_DATETIME}}`

Kaynak kod üretim işleminin yapıldığı tarih ve zamanı herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `20200802125448` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_DATETIME_FORMATTED}}`

Kaynak kod üretim işleminin yapıldığı tarih ve zamanı biçimlendirilmiş bir şekilde gösteren küresel değişkendir. `2020-08-02 12:54:48` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_DATE}}`

Kaynak kod üretim işleminin yapıldığı tarihi herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `20200802` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_TIME}}`

Kaynak kod üretim işleminin yapıldığı zamanı herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `125448` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_YEAR}}`

Kaynak kod üretim işleminin yapıldığı yılı herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `2020` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_MONTH}}`

Kaynak kod üretim işleminin yapıldığı ayı herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `08` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_DAY}}`

Kaynak kod üretim işleminin yapıldığı günü herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `02` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_HOUR}}`

Kaynak kod üretim işleminin yapıldığı saati herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `12` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_CURRENT_MINUTE}}`

Kaynak kod üretim işleminin yapıldığı dakikayı herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `54` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PATTERN_NAME}}`

Kaynak kod üretim işleminin yapıldığı kalıbın adını tutan küresel değişkendir. `testpattern` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PATTERN_TITLE}}`

Kaynak kod üretim işleminin yapıldığı kalıbın başlığını tutan küresel değişkendir. `Test Pattern` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PATTERN_VERSION}}`

Kaynak kod üretim işleminin yapıldığı kalıbın sürümünü tutan küresel değişkendir. `0.0.0-dev` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_USER_NAME}}`

Kaynak kod üretimi yapan kullanıcının adını tutan küresel değişkendir.

##### `{{$__globals__/PYRONOME_PROJECT_USER_EMAIL}}`

Kaynak kod üretimi yapan kullanıcının e-posta adresini tutan küresel değişkendir.

##### `{{$__globals__/PYRONOME_PROJECT_USER_FULL_NAME}}`

Kaynak kod üretimi yapan kullanıcının tam adını (örn. ad soyad) tutan küresel değişkendir.

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_DATETIME}}`

Kaynak kod üretim işlemi yapılan projenin oluşturulma tarih ve zamanını herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `20200726080645` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_DATETIME_FORMATTED}}`

Kaynak kod üretim işlemi yapılan projenin oluşturulma tarih ve zamanını biçimlendirilmiş bir şekilde gösteren küresel değişkendir. `2020-07-26 08:06:45` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_DATE}}`

Kaynak kod üretim işlemi yapılan projenin oluşturulma tarihini herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `20200726` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_TIME}}`

Kaynak kod üretim işlemi yapılan projenin oluşturulma zamanını herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `080645` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATETIME}}`

Kaynak kod üretim işlemi yapılan projenin son güncelleme tarih ve zamanını herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `20200726080645` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATETIME_FORMATTED}}`

Kaynak kod üretim işlemi yapılan projenin son güncelleme tarih ve zamanını biçimlendirilmiş bir şekilde gösteren küresel değişkendir. `2020-07-26 08:06:45` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATE}}`

Kaynak kod üretim işlemi yapılan projenin son güncelleme tarihini herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `20200726` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_TIME}}`

Kaynak kod üretim işlemi yapılan projenin son güncelleme zamanını herhangi bir biçimlendirme yapmadan gösteren küresel değişkendir. `080645` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_2BYTES_LOWERCASE}}`

2 karakter uzunluğuna sahip küçük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4a` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_4BYTES_LOWERCASE}}`

4 karakter uzunluğuna sahip küçük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4a69` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_8BYTES_LOWERCASE}}`

8 karakter uzunluğuna sahip küçük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4a692a27` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_16BYTES_LOWERCASE}}`

16 karakter uzunluğuna sahip küçük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4a692a2798b3c8fa` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_32BYTES_LOWERCASE}}`

32 karakter uzunluğuna sahip küçük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4a692a2798b3c8fa4297b7a0d535d06b` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_64BYTES_LOWERCASE}}`

64 karakter uzunluğuna sahip küçük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_2BYTES_UPPERCASE}}`

2 karakter uzunluğuna sahip büyük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4A` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_4BYTES_UPPERCASE}}`

4 karakter uzunluğuna sahip büyük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4A69` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_8BYTES_UPPERCASE}}`

8 karakter uzunluğuna sahip büyük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4A692A27` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_16BYTES_UPPERCASE}}`

16 karakter uzunluğuna sahip büyük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4A692A2798B3C8FA` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_32BYTES_UPPERCASE}}`

32 karakter uzunluğuna sahip büyük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir. `4A692A2798B3C8FA4297B7A0D535D06B` şeklinde bir değere sahiptir.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_64BYTES_UPPERCASE}}`

64 karakter uzunluğuna sahip büyük harfler ve sayılar içeren rastgele metin tutan küresel değişkendir.

### Model Değişkenleri

```yaml
- project
    - model_list
        - model
            - title
            - property_list
                - property
                    - title     # <-- Bu elemanda olduğumuzu varsayalım
                    - category
```

Yukarıdaki model göz önünde bulundurularak aşağıda elemanlara ait değerlerin kaynak koda aktarılması için kullanılabilecek ifadeler listelenmiştir:

##### `{{$__value__}}`

Mevcut elemanın değerini tutar. Yukarıdaki örnekte `property` elemanına ait `title` elemanının değerini verir.

Buna ek olarak;

- `{{$__value__/__uppercase_text__}}`: Yukarıdaki örnekte `property` elemanına ait `title` elemanının değerini büyük harfe çevirerek verir. 
- `{{$__value__/__lowercase_text__}}`: Yukarıdaki örnekte `property` elemanına ait `title` elemanının değerini küçük harfe çevirerek verir.
- `{{$__value__/__md5_text__}}`: Yukarıdaki örnekte `property` elemanına ait `title` elemanının değerini MD5 metin değerini verir.
- `{{$__value__/__sha1_text__}}`: Yukarıdaki örnekte `property` elemanına ait `title` elemanının değerini SHA1 metin değerini verir.
- `{{$__value__/__sha1_md5_text__}}`: Yukarıdaki örnekte `property` elemanına ait `title` elemanının değerini SHA1 metin değerinin MD5 metin değerini verir.

##### `{{$__name__}}`

Mevcut elemanın adını tutar. Yukarıdaki örnekte `property` elemanına ait `title` elemanının adını verir.

Buna ek olarak; `{{$__value__}}` ifadesinde olduğu gibi
- `{{$__name__/__uppercase_text__}}`,
- `{{$__name__/__lowercase_text__}}`,
- `{{$__name__/__md5_text__}}`,
- `{{$__name__/__sha1_text__}}` ve
- `{{$__name__/__sha1_md5_text__}}` şeklinde kullanılabilir.

##### `{{$__index__}}`

Mevcut elemanın indisini -sıfırdan başlayarak- tutar. Yukarıdaki örnekte `property` elemanına ait `title` elemanının indisini verir.

Buna ek olarak; `{{$__value__}}` ifadesinde olduğu gibi
- `{{$__index__/__md5_text__}}`,
- `{{$__index__/__sha1_text__}}` ve
- `{{$__index__/__sha1_md5_text__}}` şeklinde kullanılabilir.

##### `{{$__index1__}}`

Mevcut elemanın indisini -birden başlayarak- tutar. Yukarıdaki örnekte `property` elemanına ait `title` elemanının indisini verir.

Buna ek olarak; `{{$__value__}}` ifadesinde olduğu gibi
- `{{$__index1__/__md5_text__}}`,
- `{{$__index1__/__sha1_text__}}` ve
- `{{$__index1__/__sha1_md5_text__}}` şeklinde kullanılabilir.

##### `{{$__type__}}`

Mevcut elemanın türünü tutar. Yukarıdaki örnekte `property` elemanına ait `title` elemanının türünü verir.

Buna ek olarak; `{{$__value__}}` ifadesinde olduğu gibi
- `{{$__type__/__uppercase_text__}}`,
- `{{$__type__/__lowercase_text__}}`,
- `{{$__type__/__md5_text__}}`,
- `{{$__type__/__sha1_text__}}` ve
- `{{$__type__/__sha1_md5_text__}}` şeklinde kullanılabilir.

##### `{{$../category/__value__}}`

Mevcut eleman ile aynı seviyeye sahip `category` elemanının değerini verir.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Uyarı:</strong>
    </p>
    <p>Buradaki ifade yukarıdaki örnekte verilen modele uygun olarak belirtilmiştir. Farklı bir modelde {{$../category/__value__}} ifadesi değişkenlik gösterebilir.</p>
</div>

Aynı şekilde;
- `{{$../category/__name__}}`: Mevcut eleman ile aynı seviyeye sahip `category` elemanının adını verir.
- `{{$../category/__index__}}`: Mevcut eleman ile aynı seviyeye sahip `category` elemanının indisini -sıfırdan başlayarak- verir.
- `{{$../category/__index1__}}`: Mevcut eleman ile aynı seviyeye sahip `category` elemanının indisini -birden başlayarak- verir.
- `{{$../category/__type__}}`: Mevcut eleman ile aynı seviyeye sahip `category` elemanının türünü verir.

Buna ek olarak; `{{$__value__}}` ifadesinde olduğu gibi
- `{{$../category/__value__/__uppercase_text__}}`,
- `{{$../category/__value__/__lowercase_text__}}`,
- `{{$../category/__value__/__md5_text__}}`,
- `{{$../category/__value__/__sha1_text__}}` ve
- `{{$../category/__value__/__sha1_md5_text__}}` şeklinde kullanılabilir.

##### `{{$../../../title/__value__}}`

Mevcut elemanın içinde bulunduğu `model` elemanına ait `title` elemanının değerini verir.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Uyarı:</strong>
    </p>
    <p>Buradaki ifade yukarıdaki örnekte verilen modele uygun olarak belirtilmiştir. Farklı bir modelde {{$../../../title/__value__}} ifadesi değişkenlik gösterebilir.</p>
</div>

Aynı şekilde;
- `{{$../../../title/__name__}}`: Mevcut elemanın içinde bulunduğu `model` elemanına ait `title` elemanının adını verir.
- `{{$../../../title/__index__}}`: Mevcut elemanın içinde bulunduğu `model` elemanına ait `title` elemanının indisini -sıfırdan başlayarak- verir.
- `{{$../../../title/__index1__}}`: Mevcut elemanın içinde bulunduğu `model` elemanına ait `title` elemanının indisini -birden başlayarak- verir.
- `{{$../../../title/__type__}}`: Mevcut elemanın içinde bulunduğu `model` elemanına ait `title` elemanının türünü verir.

Buna ek olarak; `{{$__value__}}` ifadesinde olduğu gibi
- `{{$../../../title/__value__/__uppercase_text__}}`,
- `{{$../../../title/__value__/__lowercase_text__}}`,
- `{{$../../../title/__value__/__md5_text__}}`,
- `{{$../../../title/__value__/__sha1_text__}}` ve
- `{{$../../../title/__value__/__sha1_md5_text__}}` şeklinde kullanılabilir.

### Kalıp Değişkenleri

[Platform Kalıplar Değişkenler Sayfası](/latest/tr/docs/platform-kaliplar/#değişkenler-sayfası) bölümünde detayları belirtilen, kalıplar arası bilgi transferi için kullanılan değişken değerlerinin kaynak koda aktarılması gerekli olabilir. Bu değişkenleri `{{$__variables__/` ön takısı ile kaynak koda aktarabilirsiniz.

**Örneğin;**

- `MAX_CPU_COUNT` şeklinde tanımlanan değişken değeri, şablon kaynak koduna `{{$__variables__/MAX_CPU_COUNT}}` ifadesi ile aktarılabilir.
- `PUBLIC_API_KEY` şeklinde tanımlanan değişken değeri, şablon kaynak koduna `{{$__variables__/PUBLIC_API_KEY}}` ifadesi ile aktarılabilir.

## Denetim Yapıları

##### `{{@if...}}`

"EĞER" denetiminin yapılmasını sağlayan denetim yapısıdır. `...` ile belirtilen bölüme mantıksal sınama ifadesi yazılmalıdır. Mantıksal sınama ifadelerini `(` ve `)` simgeleri ile gruplayabilir; `&&` ve `||` mantıksal sınama operatörleri ile birbirine bağlayabilirsiniz.

##### `{{@else}}`

"DEĞİLSE" denetiminin yapılmasını sağlayan denetim yapısıdır.

##### `{{@elseif...}}`

"DEĞİLSE EĞER" denetiminin yapılmasını sağlayan denetim yapısıdır. `...` ile belirtilen bölüme mantıksal sınama ifadesi yazılmalıdır. Mantıksal sınama ifadelerini `(` ve `)` simgeleri ile gruplayabilir; `&&` ve `||` mantıksal sınama operatörleri ile birbirine bağlayabilirsiniz.

##### `{{@endif}}`

"EĞER" ile başlayan denetim cümlesinin bittiğini belirten denetim yapısıdır.

**Örnek 1:** `{{$__value__}}` ifadesinin değerinin "5" olduğu bir durum için aşağıdaki şablon kaynak kodu:

```php
{{@if {{$__value__}} < "5"}}
DEGER 5TEN KUCUK
{{@elseif {{$__value__}} == "5"}}
DEGER 5E ESIT
{{@else}}
DEGER 5TEN BUYUK
{{@endif}}
```

kaynak kod üreteçleri tarafından aşağıdaki koda dönüştürülecektir:

```php
DEGER 5E ESIT
```

**Örnek 2:** `{{$type/__value__}}` ifadesinin değerinin "String" olduğu bir durum için aşağıdaki şablon kaynak kodu:

```php
{{@if {{$type/__value__}} == "String"}}
$currentValue = '';
{{@else}}
$currentValue = 0;
{{@endif}}
```

kaynak kod üreteçleri tarafından aşağıdaki koda dönüştürülecektir:

```php
$currentValue = "";
```

**Örnek 3:** `{{$type/__value__}}` ifadesinin değerinin "String" olduğu ve `{{$__index__}}` ifadesinin değerinin "0" olduğu bir durum için aşağıdaki şablon kaynak kodu: 

```php
{{@if ({{$type/__value__}} == "String") && ({{$__index__}} == "0")}}
$values = [];
$values[0] = '';
{{@elseif {{$type/__value__}} == "String"}}
$values[{{$__index__}}] = '';
{{@endif}}
```

kaynak kod üreteçleri tarafından aşağıdaki koda dönüştürülecektir:

```php
$values = [];
$values[0] = '';
```

Yukarıdaki ifade aşağıdaki biçimde içe içe birleştirilmiş olarak da yazılabilir:

```php
{{@if {{$type/__value__}} == "String"}}
{{@if {{$__index__}} == "0"}}
$values = [];
{{@endif}}
$values[{{$__index__}}] = '';
{{@endif}}
```

## Kaçış Simgesi

Pyronome kalıp şablonları için özel bir anlama sahip olan `{{` ve `}}` ifadeleri, birçok başka yazılım dili, anaçatı ve kütüphane için de özel bir anlama sahip olabilir. Bu nedenle bazı durumlarda Pyronome kaynak kod üreteçlerinin `{{` ve `}}` ifadelerini görmezden gelmesini isteyebilirsiniz. Bu gibi durumlarda `{{!` ifadesi kullanılabilir. `{{!` ifadesi kaynak kod üretim aşamasında, `{{` ifadesine dönüştürülür.

**Örneğin;**

- `{{!name}}` ifadesi, `{{name}}` ifadesine dönüştürülür.
- `{{!$URL}}` ifadesi, `{{$URL}}` ifadesine dönüştürülür.
- `{{!@if}}` ifadesi, `{{@if}}` ifadesine dönüştürülür.