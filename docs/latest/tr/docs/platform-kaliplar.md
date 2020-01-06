---
id: platform-kaliplar
title: Platform Kalıplar Bölümü
sidebar_label: Kalıplar
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

Kalıplar, Pyronome teknolojisinin önemli bir elemanıdır. Proje modelinin belirlenmesini sağlayan şemalar, kaynak kod üretiminde kullanılacak statik dosyalar ve şablonlar bir araya getirilerek kalıplar oluşturulmaktadır. Kalıplar da, projelerde olduğu gibi başka kalıplara bağlı olabilmektedir.

## Kalıplarım Sayfası
Oluşturduğunuz ya da üyesi olduğunuz kalıpların listelendiği sayfadır. Bu sayfa üzerinden yeni kalıp ekleyebilir ya da mevcut kalıplarınızı görüntüleyebilirsiniz.

| Tablo Alanı | Açıklama |
| ------ | ------ |
| Ad | Kalıbın başlığı, kalıbın bulunduğu dizin ve kalıp adının gösterildiği alandır. |
| Etkin Sürüm | Pyronome üzerinde kalıpların farklı sürümleri oluşturulabilir. Bu alan, üzerinde değişiklik yapılmakta olan etkin sürümü ifade etmektedir. Kalıbın **"Sürümler"** sayfası üzerinden etkin sürüm değiştirilebilir. |
| Etkin | Kalıbın etkin olup olmadığını belirten alandır. Etkin olmayan kalıplar, diğer üyeler tarafından görüntülenemez. |
| <i class="fas fa-users"></i> Üyeler Düğmesi | Kalıbın sahibi tarafından belirlenen, projenin üzerinde işlem yapma yetkisine sahip diğer üyelerin görüntülendiği **"Üyeler"** sayfasını gösterir. |
| <i class="fas fa-trash-alt"></i> Silme Düğmesi | Kalıbın silinmesi için kullanılan düğmedir. |

## Kurulan Kalıplar Sayfası
Proje ya da kalıp oluştururken, **"Kalıp Ekle/Kur"** penceresi üzerinden proje ya da kalıbınıza dahil ettiğiniz kalıplar bu bölümde listelenmektedir.

## Yeni Kalıp Sayfası
Yeni kalıp ekleme formunun bulunduğu sayfadır.

| Form Alanı | Açıklama |
| ------ | ------ |
| Etkin | Kalıbın etkin olup olmadığını belirleyebileceğiniz alandır. |
| Boş Kalıp Oluştur | Bu alan seçildiğinde boş bir kalıp oluşturulmaktadır. |
| Varolan Kalıbı Klonla | Daha önce oluşturduğunuz ya da üzerinde düzenleme yetkiniz olan bir kalıbı klonlayarak yeni bir kalıp oluşturabilirsiniz. Bu alan seçildiğinde açılan alan içerisinden bir kalıp seçilmelidir. |
| Kalıplar | Bu alan sadece **"Varolan Kalıbı Klonla"** alanı seçildiğinde gösterilmektedir. Yeni oluşturulacak kalıbın hangi kalıptan klonlanacağını belirten alandır. Bu alanda önceden eklemiş olduğunuz ya da düzenleme yetkisine sahip olduğunuz projeler listelenmektedir. |
| Alan | Kalıbın hangi isim uzayı içinde tanımlanacağını belirten alandır. Bu alanda kullanıcı adınız ve eklemiş olduğunuz alanlar listelenmektedir.<br><br>`Gerekli` |
| Varolan Dizine Ekle | Kalıbın önceden oluşturulan dizinlerin içine ekleneceğini belirten alandır. |
| Yeni Dizin Oluştur | Bu alan seçildiğinde kalıp yeni oluşturulacak dizine kaydedilir. |
| Ana Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Kalıbın kaydedileceği ana dizini belirtmektedir. |
| Alt Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Kalıbın kaydedileceği alt dizini belirtmektedir. |
| Ad | Kalıbın adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Kalıp adı ile ilgili olarak lütfen [Genel Ayarlar Sayfası](#genel-ayarlar-sayfası) bölümünde belirtilen ölçütlere dikkat ediniz.<br><br>`Gerekli` ve `Benzersiz` |
| Başlık | Kalıbın başlığını belirtmektedir.<br><br>`Gerekli` |
| Görünüm | Kalıbın görüntülenme biçimini belirtir. Kalıplar **"Genel"** ya da **"Özel"** olabilir. **"Genel"** kalıplar Pazaryeri üzerinde görüntülenebilir. **"Özel"** kalıplar sadece yetkisi olan kullanıcılar tarafından görüntülenebilir. |
| Kalıp Logosu | Kalıba ait simgenin yüklenebileceği form alanıdır. |

## Kalıp Sayfası
Kalıbınızın tüm detaylarının bulunduğu sayfadır. Bu sayfa üzerinden kalıp şemasını, şablonlarını, modelini ve dosyalarını yönetebilirsiniz.

### Genel Bakış Sayfası
Kalıp sayfasına girildiğinde ilk gösterilen bölümdür. Bu bölüm tüm kalıp özelliklerinin özeti niteliğindedir.

| Bölüm | Açıklama |
| ------ | ------ |
| Temel Özellikler | Kalıbın belli başlı özelliklerinin gösterildiği tablodur. Detaylı bilgi için [**"Genel Ayarlar Sayfası"**](#genel-ayarlar-sayfası) bölümüne bakınız. |
| Kalıplar | Kalıbın bağımlı olduğu kalıpların listelendiği bölümdür. Detaylı bilgi için [**"Kalıplar Sayfası"**](#kalıplar-sayfası) bölümüne bakınız. |
| Dosyalar | Kalıbın statik dosyalarının gösterildiği bölümdür. Detaylı bilgi için [**"Dosyalar Sayfası"**](#dosyalar-sayfası) bölümüne bakınız. |
| Sürümler | Kalıp sürümlerinin listelendiği bölümdür. Detaylı bilgi için [**"Sürümler Sayfası"**](#surumler-sayfası) bölümüne bakınız. |
| Üyeler | Kalıbın üyelerinin listelendiği bölümdür. Detaylı bilgi için [**"Üyeler Sayfası"**](#uyeler-sayfası) bölümüne bakınız. |
| İşlem Geçmişi | Kalıp üzerinde düzenleme yetkisine sahip kullanıcıların, kalıp üzerinde yapmış olduğu güncellemelerin listelendiği bölümdür. |

### Şema Sayfası
Kalıplar kaynak kod üretimi yaparken belli özelliklere ve kullanıcı tarafından eklenecek belli parametrelere ihtiyaç duymaktadır. Bu bölümde kullanıcı tarafından eklenecek parametrelerin ne olduğu ve kullanıcıdan nasıl alıncağı belirlenir. Böylelikle kullanıcı kalıbı kendi projesine eklediğinde projenin model sayfası bu bölümde belirlenen şemaya göre oluşturulur.

| Bölüm | Açıklama |
| ------ | ------ |
| <i class="fas fa-history"></i> Güncelleme Geçmişi | Şema güncelleme işlemi yapıldığında şemanın bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Doğrulama Sonucu | Şema güncelleme işlemi sırasında şemanın belirlenen ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Doğrulama Sonucu"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Şema içeriğinde belirtilen değerlerin ve şema alanlarının aranabildiği bölümdür. Bu bölümde **Kurallı İfadeler (Regular Expression)** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Hepsini Daralt | Şema içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Hepsini Genişlet | Şema içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> JSON Olarak Düzenle | Şemayı JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Doğrulama Sayfası
Kalıbın şeması belirlendikten sonra, bu şemanın hangi koşullara göre doğrulanacağının belirtilmesi gerekmektedir. Böylelikle kalıbınızı kullanan kullanıcıları yönlendirip; kaynak kod üretim aşamasından önce gerekli kontrollerin yapılmasını sağlayabilirsiniz. Uyumsuz bölümlerin kullanıcılara gösterilip; bu uyumsuzlukların düzeltilmesini sağlayabilirsiniz. Bu bölümde doğrulamanın yapılması için koşullar oluşturulmaktadır.

| Bölüm | Açıklama |
| ------ | ------ |
| <i class="fas fa-history"></i> Güncelleme Geçmişi | Doğrulama modelinin güncelleme işlemi yapıldığında modelin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Doğrulama Sonucu | Doğrulama modellerinin de ön tanımlı kuralları bulunmaktadır. Doğrulama modelinin belirlenen ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Doğrulama Sonucu"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Doğrulama model içeriğinde belirtilen değerlerin ve model alanlarının aranabildiği bölümdür. Bu bölümde **Kurallı İfadeler (Regular Expression)** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Hepsini Daralt | Doğrulama model içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Hepsini Genişlet | Doğrulama modeli içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> JSON Olarak Düzenle | Doğrulama modelini JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Dosyalar Sayfası
Kaynak kod üretim aşamasında, bazı dosyalar doğrudan -üzerinde hiçbir işlem yapılmadan- kaynak kod eklenmesi gerekmektedir. Bu dosyalar statik dosyalar olarak adlandırılmaktadır. Bu bölümde, bu statik dosyalar eklenebilmektedir.

Bu bölümde eklenebilecek dosyalar, resim, ikili dosya (Binary File) ve metin tabanlı dosyalar olabilir. Metin tabanlı dosyalar bütünleşik editör yardımıyla düzenlenebilmektedir. Bununla birlikte bütün statik dosyaların .zip uzantılı sıkıştırılmış bir dosya olarak atılması ve sıkıştırılmış dosyanın açılmasını sağlayabilirsiniz.

### Şablonlar Sayfası
Kalıpların en önemli bileşenlerinden bir tanesi şablonlardır. Şablonlar model ağacına göre kod parçalarının bir araya getirilerek üreteçlerin oluşturulmasını sağlamaktadır.

| Bölüm | Açıklama |
| ------ | ------ |
| <i class="fas fa-history"></i> Güncelleme Geçmişi | Şablon modelinin güncelleme işlemi yapıldığında modelin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Doğrulama Sonucu | Şablon model güncelleme işlemi sırasında modelin ön-tanımlı ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Doğrulama Sonucu"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Şablon model içeriğinde belirtilen değerlerin ve model alanlarının aranabildiği bölümdür. Bu bölümde **Kurallı İfadeler (Regular Expression)** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Hepsini Daralt | Şablon modeli içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Hepsini Genişlet | Şablon modeli içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> JSON Olarak Düzenle | Şablon modeli JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Değişkenler Sayfası
Bir projenin kaynak kod üretim aşamasında birden fazla kalıp eklenebilir. Bu kalıplar için kaynak kod üretim işlemi birbirinden ayrı işletilmektedir. Bununla birlikte kaynak kod üretimi paralel işleme ile de gerçekleştirilebilir. Bu gibi durumlarda genel değişken tanımları yapılıp bu değişken tanımlarının bütün kaynak kod üretim sürecinde tanımlı kalmasını bu bölümü kullanarak sağlayabilirsiniz.

| Bölüm | Açıklama |
| ------ | ------ |
| <i class="fas fa-history"></i> Güncelleme Geçmişi | Değişkenlerin güncelleme işlemi yapıldığında değişkenlerin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Doğrulama Sonucu | Değişken güncelleme işlemi sırasında değişkenlerin ön-tanımlı ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Doğrulama Sonucu"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Değişkenlerin içeriğinde belirtilen değerlerin aranabildiği bölümdür. Bu bölümde **Kurallı İfadeler (Regular Expression)** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Hepsini Daralt | Değişkenlerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Hepsini Genişlet | Daraltılmış değişkenlerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> JSON Olarak Düzenle | Değişkenleri JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Model Sayfası
Kalıbın seçilen kalıplara göre modelinin oluşturulduğu bölümdür. Seçilen kalıpların şemasında belirlenen ve bu kalıbın şema bölümünde belirlenen ölçütlere göres bu bölümde model içeriği oluşturulur.

| Bölüm | Açıklama |
| ------ | ------ |
| <i class="fas fa-history"></i> Güncelleme Geçmişi | Model güncelleme işlemi yapıldığında modelin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Doğrulama Sonucu | Model güncelleme işlemi sırasında modelin seçilen kalıpların ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Doğrulama Sonucu"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Model içeriğinde belirtilen değerlerin ve model alanlarının aranabildiği bölümdür. Bu bölümde **Kurallı İfadeler (Regular Expression)** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Hepsini Daralt | Model içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Hepsini Genişlet | Model içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> JSON Olarak Düzenle | Modeli JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Kalıplar Sayfası
Aynen projelerde olduğu gibi kalıplara da başka kalıplar kurulabilir. Böylelikle bazı alt seviye kalıpların tekrar tekrar seçilmesi zorunluğu ortadan kalkar.

**"Kalıp Ekle/Kur"** düğmesine basıldığında kalıba kurulabilecek kalıpların listesini gösteren pencere açılır. Bu bölüm yardımıyla kalıplar belli ölçütlere göre arayabilir ve kalıp kurma ve satın alma işlemlerini gerçekleştirebilirsiniz.

Kalıba kurulu kalıpların listesi sayfanın orta bölümünde yer almaktadır. Bu bölümdeki kalıplar her satırın sol tarafında bulunan özel sıralama tutucuları ile sıralanabilir. Listedeki her satırın sol tarafında bulunan sürüm seçicisi ile kurulan kalıbın hangi sürümüne göre kaynak kod üretim işlemi yapılabileceği seçilebilir.

### Genel Ayarlar Sayfası
Projeye ait genel bilgilerin güncellendiği bölümdür.

| Form Alanı | Açıklama |
| ------ | ------ |
| Etkin | Projenin etkin olup olmadığını belirleyebileceğiniz alandır. |
| Alan | Projenin hangi isim uzayı içinde tanımlanacağını belirten alandır. Bu alanda kullanıcı adınız ve eklemiş olduğunuz alanlar listelenmektedir.<br><br>`Gerekli` |
| Varolan Dizine Ekle | Projenin önceden oluşturulan dizinlerin içine ekleneceğini belirten alandır. |
| Yeni Dizin Oluştur | Bu alan seçildiğinde proje yeni oluşturulacak dizine kaydedilir. |
| Ana Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği ana dizini belirtmektedir. |
| Alt Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği alt dizini belirtmektedir. |
| Ad | Projenin adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Proje adı ile ilgili olarak lütfen aşağıda belirtilen ölçütlere dikkat ediniz.<br><br>`Gerekli` |
| Başlık | Projenin başlığını belirtmektedir.<br><br>`Gerekli` ve `Benzersiz` |
| Açıklama | Proje ile ilgili açıklamaların girilebileceği form alanıdır. |
| Proje Logosu | Projeye ait simgenin yüklenebileceği form alanıdır. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Uyarı:</strong>
    </p>
    <p><strong>"Ad"</strong> alanı ile ilgili olarak aşağıdaki ölçütlere dikkat edilmelidir:
    <ul>
        <li>Sadece İngilizce karakterler içermelidir.</li>
        <li>Boşluk ve sekme karakterlerini içeremez.</li>
        <li>İki karakterden daha uzun olmalıdır.</li>
        <li>Noktalama işareti olarak sadece orta çizgi "-" ve alt tire "_" karakterleri kabul edilmektedir.</li>
        <li>Sayı, orta çizgi "-" ve alt tire "_" ile başlayamaz.</li>
    </ul></p>
</div>

### Üyeler Sayfası
Projeyi görüntüleme, düzenleme ve yönetme faaliyetlerini gerçekleştirecek kullanıcıların belirlendiği bölümdür.

Projeye 3 (üç) farklı türde üye eklebilirsiniz:
- Yönetici: Proje üzerinde tam yetkiye sahiptir. Başka yönetici kullanıcılar ekleyebilir.
- Geliştirici: Proje özelliklerini, modelini ve kalıplarını güncelleme yetkisine sahiptir.
- İzleyici: Proje özelliklerini, modelini ve kalıplarını görüntüleyebilir ancak güncelleme yapamaz.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Not:</strong>
    </p>
    <p>Projeye ekleyeceğiniz üyelerin platforma üye olmaları gerekmektedir. Daha önceden üye kaydı yapmamış üyelerin e-posta adresini belirterek; davet gönderebilirsiniz.</p>
</div>

### Sürümler Sayfası
Proje modelinin farklı sürümlere sahip kopyalarını oluşturmak için bu bölümü kullanabilirsiniz. Proje sürümlerini belirlerken,

1. Majör
2. Minor
3. Yama

ana sürüm numaraları belirtilmelidir.

Bunun yanında,

- `dev`
- `alpha`
- `beta`

soneklerini ekleyerek ara sürümler de oluşturabilirsiniz.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Not:</strong>
    </p>
    <p>Pyronome sürümlerin belirlenmesinde <strong>Anlamsal Sürümleme</strong> yaklaşımını önermektedir. Anlamsal Sürümleme ile ilgili daha detaylı bilgi için <a href="https://semver.org/lang/tr/">https://semver.org/</a> adresini ziyaret edebilirsiniz.</p>
</div>

### Pazaryeri Sayfası
Projeye ait genel bilgilerin güncellendiği bölümdür.

| Form Alanı | Açıklama |
| ------ | ------ |
| Etkin | Projenin etkin olup olmadığını belirleyebileceğiniz alandır. |
| Alan | Projenin hangi isim uzayı içinde tanımlanacağını belirten alandır. Bu alanda kullanıcı adınız ve eklemiş olduğunuz alanlar listelenmektedir.<br><br>`Gerekli` |
| Varolan Dizine Ekle | Projenin önceden oluşturulan dizinlerin içine ekleneceğini belirten alandır. |
| Yeni Dizin Oluştur | Bu alan seçildiğinde proje yeni oluşturulacak dizine kaydedilir. |
| Ana Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği ana dizini belirtmektedir. |
| Alt Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği alt dizini belirtmektedir. |
| Ad | Projenin adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Proje adı ile ilgili olarak lütfen aşağıda belirtilen ölçütlere dikkat ediniz.<br><br>`Gerekli` |
| Başlık | Projenin başlığını belirtmektedir.<br><br>`Gerekli` ve `Benzersiz` |
| Açıklama | Proje ile ilgili açıklamaların girilebileceği form alanıdır. |
| Proje Logosu | Projeye ait simgenin yüklenebileceği form alanıdır. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Uyarı:</strong>
    </p>
    <p><strong>"Ad"</strong> alanı ile ilgili olarak aşağıdaki ölçütlere dikkat edilmelidir:
    <ul>
        <li>Sadece İngilizce karakterler içermelidir.</li>
        <li>Boşluk ve sekme karakterlerini içeremez.</li>
        <li>İki karakterden daha uzun olmalıdır.</li>
        <li>Noktalama işareti olarak sadece orta çizgi "-" ve alt tire "_" karakterleri kabul edilmektedir.</li>
        <li>Sayı, orta çizgi "-" ve alt tire "_" ile başlayamaz.</li>
    </ul></p>
</div>