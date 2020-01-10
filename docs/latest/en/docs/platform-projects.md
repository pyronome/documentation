---
id: platform-projects
title: Projects
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

This section contains projects that you are developing on the platform.

## Projects Page
This page contains the projects you have created or are a member of. You can add new projects or view your existing projects on this page.

| Table Field | Description |
| ------ | ------ |
| Name | This field shows the project title, the folder where the project is located and the project name. |
| Active Version | Pyronome allows users to create different versions of their projects. This field refers to the version in which the user actively makes modifications to it. The active version can be changed via the **"Versions"** page of the project. |
| Enabled | This field indicates whether the project is enabled or not. Other members cannot view disabled projects. |
| <i class="fas fa-users"></i> Members Button | Displays the **"Members"** page, which lists other members authorized to take action on the project. |
| <i class="fas fa-trash-alt"></i> Delete Button | You can use this button to delete a specific project. |

## New Project Page
This page contains the form, which you can add a new project.

| Form Field | Description |
| ------ | ------ |
| Etkin | Projenin etkin olup olmadığını belirleyebileceğiniz alandır. |
| Boş Proje Oluştur | Bu alan seçildiğinde boş bir proje oluşturulmaktadır. |
| Varolan Projeyi Klonla | Daha önce oluşturduğunuz ya da üzerinde düzenleme yetkiniz olduğu bir projeyi klonlayarak yeni bir proje oluşturabilirsiniz. Bu alan seçildiğinde açılan alan içerisinden bir proje seçilmelidir. |
| Projeler | Bu alan sadece **"Varolan Projeyi Klonla"** alanı seçildiğinde gösterilmektedir. Yeni oluşturulacak projenin hangi projeden klonlanacağını belirten alandır. Bu alanda önceden eklemiş olduğunuz ya da düzenleme yetkisine sahip olduğunuz projeler listelenmektedir. |
| Alan | Projenin hangi isim uzayı içinde tanımlanacağını belirten alandır. Bu alanda kullanıcı adınız ve eklemiş olduğunuz alanlar listelenmektedir.<br><br>`Gerekli` |
| Varolan Dizine Ekle | Projenin önceden oluşturulan dizinlerin içine ekleneceğini belirten alandır. |
| Yeni Dizin Oluştur | Bu alan seçildiğinde proje yeni oluşturulacak dizine kaydedilir. |
| Ana Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği ana dizini belirtmektedir. |
| Alt Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği alt dizini belirtmektedir. |
| Ad | Projenin adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Proje adı ile ilgili olarak lütfen [Genel Ayarlar Sayfası](#genel-ayarlar-sayfası) bölümünde belirtilen ölçütlere dikkat ediniz.<br><br>`Gerekli` ve `Benzersiz` |
| Başlık | Projenin başlığını belirtmektedir.<br><br>`Gerekli` |
| Proje Logosu | Projeye ait simgenin yüklenebileceği Form Fielddır. |

## Project Page
Projenizin tüm detaylarının bulunduğu sayfadır. Bu sayfa üzerinden proje modeli, kaynak kodu ve sunucu ayarlarını yönetebilirsiniz.

### Overview Page
Proje sayfasına girildiğinde ilk gösterilen bölümdür. Bu bölüm tüm proje özelliklerinin özeti niteliğindedir.

| Section | Description |
| ------ | ------ |
| Temel Özellikler | Projenin belli başlı özelliklerinin gösterildiği tablodur. Detaylı bilgi için [**"Genel Ayarlar Sayfası"**](#genel-ayarlar-sayfası) bölümüne bakınız. |
| Kalıplar | Projenin kalıplarının listelendiği bölümdür. Detaylı bilgi için [**"Kalıplar Sayfası"**](#kalıplar-sayfası) bölümüne bakınız. |
| Kaynak Kod | Projenin üretilen kaynak kodunun gösterildiği bölümdür. Detaylı bilgi için [**"Kaynak Kod Sayfası"**](#kaynak-kod-sayfası) bölümüne bakınız. |
| Sürümler | Proje sürümlerinin listelendiği bölümdür. Detaylı bilgi için [**"Sürümler Sayfası"**](#surumler-sayfası) bölümüne bakınız. |
| Üyeler | Proje üyelerinin listelendiği bölümdür. Detaylı bilgi için [**"Üyeler Sayfası"**](#uyeler-sayfası) bölümüne bakınız. |
| İşlem Geçmişi | Proje üzerinde düzenleme yetkisine sahip kullanıcıların, proje üzerinde yapmış olduğu güncellemelerin listelendiği bölümdür. |
| Sunucular | Proje sunucularının listelendiği bölümdür. Detaylı bilgi için [**"Sunucular Sayfası"**](#sunucular-sayfası) bölümüne bakınız. |
| Kod Depoları | Projenin kod depolarının listelendiği bölümdür. Detaylı bilgi için [**"Kod Depoları Sayfası"**](#kod-depoları-sayfası) bölümüne bakınız. |
| Web İstekleri | Projenin web isteklerinin listelendiği bölümdür. Detaylı bilgi için [**"Web İstekleri Sayfası"**](#web-i-stekleri-sayfası) bölümüne bakınız. |

### Model Page
Projenin seçilen kalıplara göre modelinin oluşturulduğu bölümdür. Seçilen kalıpların şemasında belirlenen ölçütlere bu bölümde model içeriği oluşturulur.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Güncelleme Geçmişi | Model güncelleme işlemi yapıldığında modelin bir kopyası tarayıcınızın yerel hafızasına da kaydedilir. Böylelikle önceden yapmış olduğunuz bir güncellemeyi geri yükleyebilirsiniz. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Doğrulama Sonucu | Model güncelleme işlemi sırasında modelin seçilen kalıpların ölçütlerine uyup uymadığı kontrol edilir. Uyumsuz bölümler işaretlenir ve kullanıcıya gösterilir. **"Doğrulama Sonucu"** düğmesine basıldığında tüm hata, uyarı ve bilgi mesajlarının listelendiği pencere gösterilir. |
| Arama Bölümü | Model içeriğinde belirtilen değerlerin ve model alanlarının aranabildiği bölümdür. Bu bölümde **Kurallı İfadeler (Regular Expression)** sözdizimi içeren arama cümleleri de belirtebilirsiniz. |
| <i class="fas fa-minus-square"></i> Hepsini Daralt | Model içeriğinde dizilerin tümünü daraltır, böylelikle sadece düzenlenecek bölümdeki alanları genişletebilirsiniz. |
| <i class="fas fa-plus-square"></i> Hepsini Genişlet | Model içeriğinde önceden daraltılmış dizilerin hepsini genişletir. |
| <i class="fab fa-js-square"></i> JSON Olarak Düzenle | Modeli JSON sözdiziminde düzenlemek için bu bağlantıya tıklayabilirsiniz. |

### Patterns Page
Projenin kaynak kod üretimi, projeye kurulu kalıplar sayesinde gerçekleştirilir. Bir projeye birden fazla kalıp kurulabilir. Böylelikle kaynak kodu üretilecek uygulamanın farklı bölümlerinin farklı teknolojilere dönüştürülmesi ve aynı teknolojinin yeni sürümü ile güncellenmesi kolaylıkla gerçekleştirilebilir.

**"Kalıp Ekle/Kur"** düğmesine basıldığında projeye kurulabilecek kalıpların listesini gösteren pencere açılır. Bu bölüm yardımıyla kalıplar belli ölçütlere göre arayabilir ve kalıp kurma ve satın alma işlemlerini gerçekleştirebilirsiniz.

Projeye kurulu kalıpların listesi sayfanın orta bölümünde yer almaktadır. Bu bölümdeki kalıplar her satırın sol tarafında bulunan özel sıralama tutucuları ile sıralanabilir. Listedeki her satırın sol tarafında bulunan sürüm seçicisi ile kurulan kalıbın hangi sürümüne göre kaynak kod üretim işlemi yapılabileceği seçilebilir.

### Source Code Page
Projenizin kaynak kodunu bu bölümden görüntüleyebilirsiniz. Model üzerinde ya da kalıplarda herhangi bir değişiklik yapıldığında bu bölüme giriş yapıldığında otomatik olarak kaynak kod üretim işlemi gerçekleştirilir.

Kaynak kod üretim işlemini elle yeniden başlatmak için **"Şimdi Üret!"** düğmesine basabilirsiniz. Kaynak kod üretim işlemini yeniden başlattıktan sonra sayfa yeniden yüklenir ve kaynak kod üretim işlemi arkaplanda devam eder. Sayfanın sağ üst tarafında kaynak kod üretim işlemi devam ediyorken **"Üretiliyor..."** bildirimi gösterilir. Kaynak kod üretim işlemi tamamlandığında otomatik olarak dosya listesi güncellenir. Kaynak kod üretim işlemi projenin büyüklüğüne ve seçilen kalıpların içeriğine göre değişiklik gösterebilmektedir.

Üretilen kaynak kodun tamamını tek bir .zip uzantılı dosya olarak indirmek için **"İndir (.zip)"** düğmesine basabilirsiniz.

Sayfanın orta bölümünde yer alan dosya ve dizin listesinde üretilen kaynak kod gösterilmektedir. Herhangi bir dizinin üzerine tıkladığınızda o dizinin içeriğini görüntüleyebilirsiniz. Aynı şekilde herhangi bir dosyanın üzerine tıkladığınızda ilgili dosya metin içerikli bir dosya ise içeriğini görüntüleyebilirsiniz.

### General Settings Page
Projeye ait genel bilgilerin güncellendiği bölümdür.

| Form Field | Description |
| ------ | ------ |
| Etkin | Projenin etkin olup olmadığını belirleyebileceğiniz alandır. |
| Alan | Projenin hangi isim uzayı içinde tanımlanacağını belirten alandır. Bu alanda kullanıcı adınız ve eklemiş olduğunuz alanlar listelenmektedir.<br><br>`Gerekli` |
| Varolan Dizine Ekle | Projenin önceden oluşturulan dizinlerin içine ekleneceğini belirten alandır. |
| Yeni Dizin Oluştur | Bu alan seçildiğinde proje yeni oluşturulacak dizine kaydedilir. |
| Ana Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği ana dizini belirtmektedir. |
| Alt Dizin | Bu alan **"Yeni Dizin Oluştur"** alanı seçildiğinde gösterilmektedir. Projenin kaydedileceği alt dizini belirtmektedir. |
| Ad | Projenin adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Proje adı ile ilgili olarak lütfen aşağıda belirtilen ölçütlere dikkat ediniz.<br><br>`Gerekli` |
| Başlık | Projenin başlığını belirtmektedir.<br><br>`Gerekli` ve `Benzersiz` |
| Description | Proje ile ilgili Descriptionların girilebileceği Form Fielddır. |
| Proje Logosu | Projeye ait simgenin yüklenebileceği Form Fielddır. |

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
Projeyi görüntüleme, düzenleme ve yönetme faaliyetlerini gerçekleştirecek kullanıcıların belirlendiği bölümdür.

Projeye 3 (üç) farklı türde üye eklebilirsiniz:
- Yönetici: Proje üzerinde tam yetkiye sahiptir. Başka yönetici kullanıcılar ekleyebilir.
- Geliştirici: Proje özelliklerini, modelini ve kalıplarını güncelleme yetkisine sahiptir.
- İzleyici: Proje özelliklerini, modelini ve kalıplarını görüntüleyebilir ancak güncelleme yapamaz.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>Projeye ekleyeceğiniz üyelerin platforma üye olmaları gerekmektedir. Daha önceden üye kaydı yapmamış üyelerin e-posta adresini belirterek; davet gönderebilirsiniz.</p>
</div>

### Versions Page
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
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>Pyronome sürümlerin belirlenmesinde <strong>Anlamsal Sürümleme</strong> yaklaşımını önermektedir. Anlamsal Sürümleme ile ilgili daha detaylı bilgi için <a href="https://semver.org/lang/tr/">https://semver.org/</a> adresini ziyaret edebilirsiniz.</p>
</div>

### Servers Page
Projenin kaynak kod üretim işleminden sonra otomatik olarak dosyaların yükleneceği/kurulacağı sunucuaları belirtmek için bu bölümü kullanabilirsiniz.

Bu bölümde şuan için;

- FTP Sunucusu
- SFTP Sunucusu

ekleyebilirsiniz.

Oluşturulan kaynak kodu elle mevcut sunuculara yüklemek için **"Şimdi Konuşlandır!"** düğmesine basabilirsiniz. Kaynak kod belirlediğiniz sıra ile sunuculara yüklenecektir.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Sunuculara kaynak kod yükleme işlemi ardışık olarak gerçekleştirilmektedir. Başka bir deyişle, ilk sunucuya yükleme işlemi tamamlanmadan ikinci sunucuya yükleme işlemi başlatılmaz.</p>
</div>

Yükleme işleminin yapılacağı yeni bir sunucu kaydı eklemek için **"Yeni Sunucu"** düğmesine basabilirsiniz.

| Form Field | Description |
| ------ | ------ |
| Etkin | Sunucunun etkin olup olmadığını gösterir. Etkin olmayan sunuculara yükleme işlemi yapılmaz. |
| Tür | Sunucunun türünü belirtmektedir. Şuan için FTP ve SFTP sunucularına yükleme işlemi yapılabilmektedir.<br><br>`Gerekli` |
| Ad | Sunucunun adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Proje adı ile ilgili olarak lütfen aşağıda belirtilen ölçütlere dikkat ediniz.<br><br>`Gerekli` ve `Benzersiz` |
| Description | Sunucu ile ilgili Descriptionların girilebileceği Form Fielddır. |
| Sunucu Adresi | Sunucu adresinin girildiği alandır.<br><br>`Gerekli` |
| Kullanıcı | **"Sunucu Adresi"** Form Fieldnda belirtilen sunucuya erişim yetkisine sahip kullanıcının adını girebileceğiniz alandır.<br><br>`Gerekli` |
| Kullanıcı | **"Sunucu Adresi"** Form Fieldnda belirtilen sunucuya erişim yetkisine sahip kullanıcının şifresini girebileceğiniz alandır.<br><br>`Gerekli` |
| Ev Dizini | Bağlantı sağlandıktan sonra yükleme işleminin yapılacağı dizini belirtir. |
| Yuva (Port) | Bağlantının kurulacağı yuvayı belirtir.<br><br>`Gerekli` ve `Varsayılan Değer: 21` |

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

Herhangi bir sunucuya ait işlem kayıtlarını görüntülemek için, ilgili kayıt satırının sağ tarafında bulunan <strong><i class="fas fa-file-alt"></i></strong> simgesine basabilirsiniz.

Bağlantı parametrelerini eksiksiz olarak girdikten sonra bağlantıyı test etmek için **"TEST"** düğmesine basabilirsiniz.

### Repositories Page
Projenin kaynak kod üretim işleminden sonra otomatik olarak dosyaların yükleneceği kod depolarını belirtmek için bu bölümü kullanabilirsiniz.

Oluşturulan kaynak kodu elle mevcut kod depolarına yüklemek için **"Şimdi İttir!"** düğmesine basabilirsiniz. Kaynak kod belirlediğiniz sıra ile kod depolarına yüklenecektir.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Kod depolarına kaynak kod yükleme işlemi ardışık olarak gerçekleştirilmektedir. Başka bir deyişle, ilk kod deposuna yükleme işlemi tamamlanmadan ikinci kod deposuna yükleme işlemi başlatılmaz.</p>
</div>

Yükleme işleminin yapılacağı yeni bir kod deposu kaydı eklemek için **"Yeni Kod Deposu"** düğmesine basabilirsiniz.

| Form Field | Description |
| ------ | ------ |
| Etkin | Kod deposunun etkin olup olmadığını gösterir. Etkin olmayan kod depolarına yükleme işlemi yapılmaz. |
| Kod Deposu Adı | Kod depolarını listede ayırt etmek için bir isim verilmesi gerekmektedir. <br><br>`Gerekli` |
| Dal Adı (Branch) | Üretilen kodun hangi dala (branch) yükleneceğini belirten alandır. Eğer kod deposunda belirtilen dal bulunmuyorsa, dal önce üretilir daha sonra kod yükleme işlemi yapılır.<br><br>`Gerekli` |
| Ana Dizin | Üretilen kod, kod deposu içindeki belli bir dalın içinde özel bir alt dizine yüklenmesi gerekiyorsa bu alana yükleme yapılacak dizinin adının girilmesi gerekmektedir. |
| Dosyaları Eklemeden Önce Dizindeki Mevcut Dosyaları Sil | Bu seçenek işaretlendiğinde yükleme yapılmadan önce, yükleme yapılacak dizin içeriği silinir. Böylelikle model üzerinde adı değiştirilen ya da kaldırılan elemanlara ilişkin kodlar kolaylıkla temizlenebilir. |
| E-posta Adresi | Kod deposuna erişim yetkisi olan kullanıcının e-posta adresini belirtmektedir. Böylelikle kayıtlarda yükleme işleminin hangi kullanıcı tarafından yapıldığını kolaylıkla ayırt edebilirsiniz.<br><br>`Gerekli` |
| Kullanıcı Adı | Kod deposuna erişim yetkisi olan kullanıcının kullanıcı adını belirtmektedir. |
| HTTPS Kullanarak Kimlik Doğrulama | Kimlik doğrulama işleminin hangi metotla yapılacağını belirten alandır. Bu alan işaretlenirse HTTPS üzerinden kimlik doğrulaması yapılacaktır. |
| SSH Kullanarak Kimlik Doğrulama | Kimlik doğrulama işleminin hangi metotla yapılacağını belirten alandır. Bu alan işaretlenirse SSH üzerinden kimlik doğrulaması yapılacaktır. |
| HTTPS URL | **"HTTPS Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. HTTPS bağlantısı yapılacak adresi belirtir.<br><br>`Gerekli` |
| HTTPS Password | **"HTTPS Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. HTTPS bağlantısı yaparken kullanılacak şifreyi belirtir.<br><br>`Gerekli` |
| SSH Adresi | **"SSH Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. SSH bağlantısı yapılacak adresi belirtir.<br><br>`Gerekli` |
| SSH Doğrulama Anahtar Çiftini Üret | **"SSH Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. Her yeni SSH kimlik doğrulaması yapacak kod deposu kaydı eklendiğinde otomatik olarak SSH anahtar çifti oluşturulur. Mevcut bir kod deposu için anahtar çiftini tekrar üretmek isterseniz bu seçeneği işaretleyebilirsiniz. |
| İşlem Notu | Kod yükleme işleminin kod deposu kayıtlarında gösterilecek işlem notunu belirtir. İşlem notu bölümünde `{{project_name}}`, `{{project_title}}`, vb. özel tanımlayıcılar kullanabilirsiniz. Bu özel tanımların tam listesi aşağıda verilmiştir.<br><br>`Gerekli` |

Herhangi bir kod deposuna ait işlem kayıtlarını görüntülemek için, ilgili kayıt satırının sağ tarafında bulunan <strong><i class="fas fa-file-alt"></i></strong> simgesine basabilirsiniz.

#### Commit Message Mustache Templates
Kod deposuna kod yükleme işlemi yapıldığında işlem kayıtları oluşturulur. Bu işlem kayıtları için kod yükleme işlemini yapan kullanıcılar özel notlar/mesajlar belirtebilmektedir. Pyronome üzerinden yapılan kod yükleme işlemlerine de benzer şekilde özel notlar/mesajlar eklenebilir. Eklenen bu mesajların içinde proje ve kod yükleme işlemine ait özel tanımlayıcılar kullanılabilir.

Varsayılan işlem notu:

```HTML
Code generation auto-push by Pyronome
```

Özel tanımlayıcı eklenmiş işlem notu:

```HTML
Code generation auto-push by Pyronome for {{project_title}} ({{project_name}}, {{project_active_version}}).
```

Aşağıda işlem notunda kullanılabilecek özel tanımlayıcıların listesini bulabilirsiniz:

| Tanımlayıcı | Description |
| ------ | ------ |
| `{{server_host}}` | Kod deposunun bulunduğu sunucunun adresini belirtir. |
| `{{server_name}}` | Kod deposunun bulunduğu sunucunun adını belirtir. |
| `{{project_id}}` | Kod yükleme işlemi yapılan projeye ait tamsayı tekil tanımlayıcıdır. |
| `{{project_guid}}` | Kod yükleme işlemi yapılan projeye ait rakam ve harflerden oluşan tekil tanımlayıcıdır. Bu tanımlayıcı `{{project_id}}` aksine, platform içinde her eleman için benzersiz olma niteliğine sahiptir. |
| `{{project_name}}` | Projenin adını belirtir. |
| `{{project_title}}` | Projenin başlığını belirtir. |
| `{{project_short_description}}` | Projenin kısa Descriptionsını belirtir. |
| `{{project_active_version}}` | Projenin etkin sürümünü belirtir. |
| `{{project_path}}` | Projenin ad uzayını belirtir. |
| `{{project_main_directory}}` | Projenin ana dizin adını belirtir. |
| `{{project_sub_directory}}` | Projenin alt dizin adını belirtir. |
| `{{user_id}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait tamsayı tekil tanımlayıcıdır. |
| `{{user_guid}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait rakam ve harflerden oluşan benzersiz tekil tanımlayıcıdır. |
| `{{user_name}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait kullanıcı adını belirtir. |
| `{{user_full_name}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait tam adı belirtir. |

### Webhooks Page
Projenin kaynak kod üretim, sunucu konuşlandırma ve kod depolarına ittirme işlemlerinden sonra web istekleri yapılmasını sağlayarak yazılım geliştirme süreçlerinizi otomatikleştirebilirsiniz.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Web istekleri ardışık olarak gönderilmektedir. Başka bir deyişle, ilk web isteği gönderme işlemi tamamlanmadan ikinci istek gönderimi başlatılmaz.</p>
</div>

Yükleme işleminin yapılacağı yeni bir web isteği kaydı eklemek için **"Yeni Web İsteği"** düğmesine basabilirsiniz.

| Form Field | Description |
| ------ | ------ |
| Etkin | Web isteğinin etkin olup olmadığını gösterir. Etkin olmayan web isteği gönderilmez. |
| Ad | Web isteğini listede ayırt etmek için bir isim verilmesi gerekmektedir. <br><br>`Gerekli` |
| URL | Web isteğinin yapılacağı adresi belirtir.<br><br>`Gerekli` |
| Gizli Anahtar | Web isteğinin Pyronome sunucuları tarafından gönderildiğini doğrulamak amacıyla gizli anahtar belirtebilirsiniz. |
| Üretme Olayı | Web isteğinin kod üretme işleminden sonra gönderilip/gönderilmeyeceğini belirleyen alandır. |
| Konuşlandırma Olayı | Web isteğinin sunucu konuşlandırma işleminden sonra gönderilip/gönderilmeyeceğini belirleyen alandır. |
| İttirme Olayı | Web isteğinin kod deposu ittirme işleminden sonra gönderilip/gönderilmeyeceğini belirleyen alandır. |

Herhangi bir web isteğine ait işlem kayıtlarını görüntülemek için, ilgili kayıt satırının sağ tarafında bulunan <strong><i class="fas fa-file-alt"></i></strong> simgesine basabilirsiniz.

Aşağıda örnek bir web isteğini görebilirsiniz.

```JSON
{
	"event": {
		"guid": "E0X0A0M0L0E0G0U0I0D",
		"name": "Example1",
		"type": 1
	},
	"server": {
		"host":"www.pyronome.com",
		"name":"platform"
	},
	"webhook": {
		"id": 1,
		"guid": "E0X0A0M0L0E0W0B0H0O0O0K",
		"index": "1",
		"name": "ExampleWebhook1",
		"url": "https://example.com",
		"secret_token": "YOUR_SECRET_TOKEN",
        "on_generate": 1,
        "on_deploy": 0,
        "on_push": 0
	},
	"project": {
		"id": 1,
		"guid": "E0X0A0M0L0E0P0R0J0E0C0T",
		"name": "exampleproject1",
		"title": "Example Project 1",
		"short_description": "Project Short Description",
        "active_version": "1.0.0",
        "path": "exampleuser/exampleproject1",
        "main_directory": "",
        "sub_directory": ""
	},
	"user": {
		"id": 1,
		"guid": "E0X0A0M0L0E0U0S0E0R",
		"user_name": "exampleuser",
        "full_name": "Example User"
	}
}
```