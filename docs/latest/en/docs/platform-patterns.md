---
id: platform-patterns
title: Patterns
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

Kalıplar, Pyronome teknolojisinin önemli bir elemanıdır. Proje modelinin belirlenmesini sağlayan şemalar, kaynak kod üretiminde kullanılacak statik dosyalar ve şablonlar bir araya getirilerek kalıplar oluşturulmaktadır. Kalıplar da, projelerde olduğu gibi başka kalıplara bağlı olabilmektedir.

## My Patterns Page
Oluşturduğunuz ya da üyesi olduğunuz kalıpların listelendiği sayfadır. Bu sayfa üzerinden yeni kalıp ekleyebilir ya da mevcut kalıplarınızı görüntüleyebilirsiniz.

| Table Field | Description |
| ------ | ------ |
| Ad | Kalıbın başlığı, kalıbın bulunduğu dizin ve kalıp adının gösterildiği alandır. |
| Etkin Sürüm | Pyronome üzerinde kalıpların farklı sürümleri oluşturulabilir. Bu alan, üzerinde değişiklik yapılmakta olan etkin sürümü ifade etmektedir. Kalıbın **"Sürümler"** sayfası üzerinden etkin sürüm değiştirilebilir. |
| Enabled | Kalıbın etkin olup olmadığını belirten alandır. Etkin olmayan kalıplar, diğer üyeler tarafından görüntülenemez. |
| <i class="fas fa-users"></i> Members Button | Kalıbın sahibi tarafından belirlenen, kalıbın üzerinde işlem yapma yetkisine sahip diğer üyelerin görüntülendiği **"Üyeler"** sayfasını gösterir. |
| <i class="fas fa-trash-alt"></i> Delete Button | Kalıbın silinmesi için kullanılan düğmedir. |

## Installed Pattern Page
Proje ya da kalıp oluştururken, **"Kalıp Ekle/Kur"** penceresi üzerinden proje ya da kalıbınıza dahil ettiğiniz kalıplar bu bölümde listelenmektedir.

## New Pattern Page
Yeni kalıp ekleme formunun bulunduğu sayfadır.

| Form Field | Description |
| ------ | ------ |
| Enabled | Kalıbın etkin olup olmadığını belirleyebileceğiniz alandır. |
| Boş Kalıp Oluştur | Bu alan seçildiğinde boş bir kalıp oluşturulmaktadır. |
| Varolan Kalıbı Klonla | Daha önce oluşturduğunuz ya da üzerinde düzenleme yetkiniz olan bir kalıbı klonlayarak yeni bir kalıp oluşturabilirsiniz. Bu alan seçildiğinde açılan alan içerisinden bir kalıp seçilmelidir. |
| Patterns | Bu alan sadece **"Varolan Kalıbı Klonla"** alanı seçildiğinde gösterilmektedir. Yeni oluşturulacak kalıbın hangi kalıptan klonlanacağını belirten alandır. Bu alanda önceden eklemiş olduğunuz ya da düzenleme yetkisine sahip olduğunuz kalıplar listelenmektedir. |
| Organization | Kalıbın hangi isim uzayı içinde tanımlanacağını belirten alandır. Bu alanda kullanıcı adınız ve eklemiş olduğunuz alanlar listelenmektedir.<br><br>`Required` |
| Varolan Dizine Ekle | Kalıbın önceden oluşturulan dizinlerin içine ekleneceğini belirten alandır. |
| Yeni Dizin Oluştur | Bu alan seçildiğinde kalıp yeni oluşturulacak dizine kaydedilir. |
| Main Directory | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Kalıbın kaydedileceği ana dizini belirtmektedir. |
| Sub Directory | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Kalıbın kaydedileceği alt dizini belirtmektedir. |
| Ad | Kalıbın adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Kalıp adı ile ilgili olarak lütfen [General Settings Page](#general-settings-page) bölümünde belirtilen ölçütlere dikkat ediniz.<br><br>`Required` ve `Unique` |
| Başlık | Kalıbın başlığını belirtmektedir.<br><br>`Required` |
| Görünüm | Kalıbın görüntülenme biçimini belirtir. Kalıplar **"Genel"** ya da **"Özel"** olabilir. **"Genel"** kalıplar Marketplace üzerinde görüntülenebilir. **"Özel"** kalıplar sadece yetkisi olan kullanıcılar tarafından görüntülenebilir. |
| Kalıp Logosu | Kalıba ait simgenin yüklenebileceği Form Fielddır. |

## Pattern Page
Kalıbınızın tüm detaylarının bulunduğu sayfadır. Bu sayfa üzerinden kalıp şemasını, şablonlarını, modelini ve dosyalarını yönetebilirsiniz.

### Overview Page
Kalıp sayfasına girildiğinde ilk gösterilen bölümdür. Bu bölüm tüm kalıp özelliklerinin özeti niteliğindedir.

| Section | Description |
| ------ | ------ |
| Basic Info | Kalıbın belli başlı özelliklerinin gösterildiği tablodur. Detaylı bilgi için [**"General Settings Page"**](#general-settings-page) bölümüne bakınız. |
| Patterns | Kalıbın bağımlı olduğu kalıpların listelendiği bölümdür. Detaylı bilgi için [**"Patterns Page"**](#patterns-page) bölümüne bakınız. |
| Dosyalar | Kalıbın statik dosyalarının gösterildiği bölümdür. Detaylı bilgi için [**"Dosyalar Sayfası"**](#dosyalar-sayfası) bölümüne bakınız. |
| Versions | Kalıp sürümlerinin listelendiği bölümdür. Detaylı bilgi için [**"Versions Page"**](#versions-page) bölümüne bakınız. |
| Members | Kalıbın üyelerinin listelendiği bölümdür. Detaylı bilgi için [**"Members Page"**](#members-page) bölümüne bakınız. |
| Activity Log | Kalıp üzerinde düzenleme yetkisine sahip kullanıcıların, kalıp üzerinde yapmış olduğu güncellemelerin listelendiği bölümdür. |

### Schema Page
Kalıplar kaynak kod üretimi yaparken belli özelliklere ve kullanıcı tarafından eklenecek belli parametrelere ihtiyaç duymaktadır. Bu bölümde kullanıcı tarafından eklenecek parametrelerin ne olduğu ve kullanıcıdan nasıl alıncağı belirlenir. Böylelikle kullanıcı kalıbı kendi projesine eklediğinde projenin model sayfası bu bölümde belirlenen şemaya göre oluşturulur.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | Şema güncelleme işlemi yapıldığında şemanın bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | Şema güncelleme işlemi sırasında şemanın belirlenen ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Validation Log"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Şema içeriğinde belirtilen değerlerin ve şema alanlarının aranabildiği bölümdür. Bu bölümde **Regular Expression** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Collapse All | Şema içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Expand All | Şema içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> Edit as JSON | Şemayı JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Validation Page
Kalıbın şeması belirlendikten sonra, bu şemanın hangi koşullara göre doğrulanacağının belirtilmesi gerekmektedir. Böylelikle kalıbınızı kullanan kullanıcıları yönlendirip; kaynak kod üretim aşamasından önce gerekli kontrollerin yapılmasını sağlayabilirsiniz. Uyumsuz bölümlerin kullanıcılara gösterilip; bu uyumsuzlukların düzeltilmesini sağlayabilirsiniz. Bu bölümde doğrulamanın yapılması için koşullar oluşturulmaktadır.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | Doğrulama modelinin güncelleme işlemi yapıldığında modelin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | Doğrulama modellerinin de ön tanımlı kuralları bulunmaktadır. Doğrulama modelinin belirlenen ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Validation Log"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Doğrulama model içeriğinde belirtilen değerlerin ve model alanlarının aranabildiği bölümdür. Bu bölümde **Regular Expression** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Collapse All | Doğrulama model içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Expand All | Doğrulama modeli içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> Edit as JSON | Doğrulama modelini JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Files Page
Kaynak kod üretim aşamasında, bazı dosyalar doğrudan -üzerinde hiçbir işlem yapılmadan- kaynak kod eklenmesi gerekmektedir. Bu dosyalar statik dosyalar olarak adlandırılmaktadır. Bu bölümde, bu statik dosyalar eklenebilmektedir.

Bu bölümde eklenebilecek dosyalar, resim, ikili dosya (Binary File) ve metin tabanlı dosyalar olabilir. Metin tabanlı dosyalar bütünleşik editör yardımıyla düzenlenebilmektedir. Bununla birlikte bütün statik dosyaların .zip uzantılı sıkıştırılmış bir dosya olarak atılması ve sıkıştırılmış dosyanın açılmasını sağlayabilirsiniz.

### Templates Page
Kalıpların en önemli bileşenlerinden bir tanesi şablonlardır. Şablonlar model ağacına göre kod parçalarının bir araya getirilerek üreteçlerin oluşturulmasını sağlamaktadır.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | Şablon modelinin güncelleme işlemi yapıldığında modelin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | Şablon model güncelleme işlemi sırasında modelin ön-tanımlı ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Validation Log"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Şablon model içeriğinde belirtilen değerlerin ve model alanlarının aranabildiği bölümdür. Bu bölümde **Regular Expression** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Collapse All | Şablon modeli içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Expand All | Şablon modeli içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> Edit as JSON | Şablon modeli JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Variables Page
Bir projenin kaynak kod üretim aşamasında birden fazla kalıp eklenebilir. Bu kalıplar için kaynak kod üretim işlemi birbirinden ayrı işletilmektedir. Bununla birlikte kaynak kod üretimi paralel işleme ile de gerçekleştirilebilir. Bu gibi durumlarda genel değişken tanımları yapılıp bu değişken tanımlarının bütün kaynak kod üretim sürecinde tanımlı kalmasını bu bölümü kullanarak sağlayabilirsiniz.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | Değişkenlerin güncelleme işlemi yapıldığında değişkenlerin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | Değişken güncelleme işlemi sırasında değişkenlerin ön-tanımlı ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Validation Log"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Değişkenlerin içeriğinde belirtilen değerlerin aranabildiği bölümdür. Bu bölümde **Regular Expression** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Collapse All | Değişkenlerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Expand All | Daraltılmış değişkenlerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> Edit as JSON | Değişkenleri JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Model Page
Kalıbın seçilen kalıplara göre modelinin oluşturulduğu bölümdür. Seçilen kalıpların şemasında belirlenen ve bu kalıbın şema bölümünde belirlenen ölçütlere göres bu bölümde model içeriği oluşturulur.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | Model güncelleme işlemi yapıldığında modelin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | Model güncelleme işlemi sırasında modelin seçilen kalıpların ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Validation Log"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Model içeriğinde belirtilen değerlerin ve model alanlarının aranabildiği bölümdür. Bu bölümde **Regular Expression** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Collapse All | Model içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Expand All | Model içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> Edit as JSON | Modeli JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Patterns Page
Aynen projelerde olduğu gibi kalıplara da başka kalıplar kurulabilir. Böylelikle bazı alt seviye kalıpların tekrar tekrar seçilmesi zorunluğu ortadan kalkar.

**"Kalıp Ekle/Kur"** düğmesine basıldığında kalıba kurulabilecek kalıpların listesini gösteren pencere açılır. Bu bölüm yardımıyla kalıplar belli ölçütlere göre arayabilir ve kalıp kurma ve satın alma işlemlerini gerçekleştirebilirsiniz.

Kalıba kurulu kalıpların listesi sayfanın orta bölümünde yer almaktadır. Bu bölümdeki kalıplar her satırın sol tarafında bulunan özel sıralama tutucuları ile sıralanabilir. Listedeki her satırın sol tarafında bulunan sürüm seçicisi ile kurulan kalıbın hangi sürümüne göre kaynak kod üretim işlemi yapılabileceği seçilebilir.

### General Settings Page
Kalıba ait genel bilgilerin güncellendiği bölümdür.

| Form Field | Description |
| ------ | ------ |
| Enabled | Kalıbın etkin olup olmadığını belirleyebileceğiniz alandır. |
| Organization | Kalıbın hangi isim uzayı içinde tanımlanacağını belirten alandır. Bu alanda kullanıcı adınız ve eklemiş olduğunuz alanlar listelenmektedir.<br><br>`Required` |
| Varolan Dizine Ekle | Kalıbın önceden oluşturulan dizinlerin içine ekleneceğini belirten alandır. |
| Yeni Dizin Oluştur | Bu alan seçildiğinde kalıp yeni oluşturulacak dizine kaydedilir. |
| Main Directory | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Kalıbın kaydedileceği ana dizini belirtmektedir. |
| Sub Directory | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Kalıbın kaydedileceği alt dizini belirtmektedir. |
| Ad | Kalıbın adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Kalıp adı ile ilgili olarak lütfen aşağıda belirtilen ölçütlere dikkat ediniz.<br><br>`Required` ve `Unique` |
| Başlık | Kalıbın başlığını belirtmektedir.<br><br>`Required` ve `Unique` |
| Kısa Description | Kalıbı anlatan bir cümlelik tanımıdır. |
| Description | Kalıp ile ilgili Descriptionların girilebileceği Form Fielddır. |
| Görünüm | Kalıbın görüntülenme biçimini belirtir. Kalıplar **"Genel"** ya da **"Özel"** olabilir. **"Genel"** kalıplar Marketplace üzerinde görüntülenebilir. **"Özel"** kalıplar ise sadece yetkisi olan kullanıcılar tarafından görüntülenebilir. |
| Kalıp Logosu | Kalıba ait simgenin yüklenebileceği Form Fielddır. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
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

### Members Page
Kalıbı görüntüleme, düzenleme ve yönetme faaliyetlerini gerçekleştirecek kullanıcıların belirlendiği bölümdür.

Kalıba 3 (üç) farklı türde üye eklebilirsiniz:
- Owner: Kalıp üzerinde tam yetkiye sahiptir. Başka yönetici kullanıcılar ekleyebilir.
- Developer: Kalıp özelliklerini, modelini ve kalıplarını güncelleme yetkisine sahiptir.
- Viewer: Kalıp özelliklerini, modelini ve kalıplarını görüntüleyebilir ancak güncelleme yapamaz.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>Kalıba ekleyeceğiniz üyelerin platforma üye olmaları gerekmektedir. Daha önceden üye kaydı yapmamış üyelerin e-posta adresini belirterek davet gönderebilirsiniz.</p>
</div>

### Versions Page
Kalıp modelinin farklı sürümlere sahip kopyalarını oluşturmak için bu bölümü kullanabilirsiniz. Kalıp sürümlerini belirlerken,

1. Major
2. Minor
3. Patch

ana sürüm numaraları belirtilmelidir.

Bunun yanında,

- `dev`
- `alpha`
- `beta`

soneklerini ekleyerek ara sürümler de oluşturabilirsiniz.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>Pyronome sürümlerin belirlenmesinde <strong>Anlamsal Sürümleme</strong> yaklaşımını önermektedir. Anlamsal Sürümleme ile ilgili daha detaylı bilgi için <a href="https://semver.org/lang/tr/">https://semver.org/</a> adresini ziyaret edebilirsiniz.</p>
</div>

### Marketplace Page
Kalıbın Marketplace üzerindeki sayfası ile ilgili bilgilerin güncellendiği bölümdür. Bu bölümdeki form alanların bir çoğu **"General Settings Page"** bölümündeki alanlardır.

| Form Field | Description |
| ------ | ------ |
| Başlık | Kalıbın başlığını belirtmektedir.<br><br>`Required` ve `Unique` |
| Kısa Description | Kalıbı anlatan bir cümlelik tanımıdır.<br><br>`Required` |
| Kategori | Kalıbın hangi kategori altında listeleneceğini belirtmektedir.<br><br>`Required` |
| Description | Kalıp ile ilgili Descriptionların girilebileceği Form Fielddır. |
| Anahtar Kelimeler | Marketplace üzerinde herhangi bir arama gerçekleştirildiğinde kullanılacak anahtar kelimelerdir.<br><br>`Required` |
| Web URL | Kalıbın web sitesi adresini girebileceğiniz alandır. |
| Destek URL | Kalıp kullanıcılarının yararlanabileceği destek adresini belirtmektedir. Bu bölüme GitHub, GitLab, BitBucket vb. çevrimiçi kod depolarının **"Issues"** sayfa adreslerini girebilirsiniz. |
| Kod Deposu URL | Kalıbın kod deposu adresini girebileceğiniz alandır. |
| README.md URL (DETAYLAR Sekmesi) | Marketplace üzerindeki kalıbın sayfasında **"Detaylar"** sekmesinde gösterilecek **"README.md"** dosyasının adresini belirtmektedir. |
| Lisanslama | Kalıbın kullanım lisansını belirtmektedir. |
| Fiyatlama | Kalıbın fiyatının belirlendiği bölümdür. |
| Sabit Fiyat (USD) | Kalıbın fiyatlama biçimi **"Sabit Fiyat"** olarak seçildiğinde gösterilir. Kalıbın fiyatının USD para biriminde girildiği alandır. |
| Resim Galerisi | Kalıbın ekran görüntüleri, kullanımı ile ilgili görsellerin eklendiği alandır. Bu alanda 10 (on) adet görsele yer verilebilir. Eklenen ilk görsel vitrin görseli olarak seçilir. |
| Ad | Kalıbın geliştiricisinin adını girebileceğiniz bölümdür. |
| Soyad | Kalıbın geliştiricisinin soyadını girebileceğiniz bölümdür. |
| Telefon | Kalıbın geliştiricisinin telefonunu girebileceğiniz bölümdür. |
| E-posta Adresi | Kalıbın geliştiricisinin e-posta adresini girebileceğiniz bölümdür. |
| Notlar | Kalıbın geliştiricisinin iletişim bilgileri ile ilgili belirtmek istediği notlar bu alana girilmektedir. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Bu bölümde belirtilen URL adresleri genel kullanıma açık olmalıdır.</p>
</div>