---
id: platform-organizations
title: Organizations
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

Geliştirilen kalıplar için [https://pyronome.com](https://pyronome.com) üzerinde genel ad uzayları oluşturmak amacıyla alanlar bölümü kullanılmaktadır. Alanlar bölümü yardımıyla,[https://pyronome.com](https://pyronome.com) alan adı üzerinden erişilebilen farklı kalıp dizinleri oluşturulabilmektedir.

Bununla birlikte alanlar platform üzerinde oluşturulan proje ve kalıpları sınıflandırmak için de kullanıbilir. **"Ana Sayfa"**, **"Projeler"** ve **"Kalıplarım"** sayfalarının sağ üst tarafında alan seçim menüleri yer almaktadır. Alan seçimi yapıldığında sadece seçilen alan içindeki kayıtlar gösterilir.

## Organizations Page
Oluşturduğunuz ya da üyesi olduğunuz alanların listelendiği sayfadır. Bu sayfa üzerinden yeni alan ekleyebilir ya da mevcut alanlarınızı görüntüleyebilirsiniz.

| Table Field | Description |
| ------ | ------ |
| Name | Alanın adını belirtir. |
| Enabled | Using this field, you can specify whether the organization is enabled or not. |
| Görünüm | Alanlar **"Genel"** ya da **"Özel"** olabilir. **"Genel"** alanlar Marketplace üzerinde görüntülenebilir. **"Özel"** alanlar sadece yetkisi olan kullanıcılar tarafından görüntülenebilir. |
| <i class="fas fa-users"></i> Members Button | Alanın sahibi tarafından belirlenen, alanın üzerinde işlem yapma yetkisine sahip diğer üyelerin görüntülendiği **"Üyeler"** sayfasını gösterir. |
| <i class="fas fa-trash-alt"></i> Delete Button | Alanın silinmesi için kullanılan düğmedir. |

## New Organization Page
Yeni alan ekleme formunun bulunduğu sayfadır.

| Form Field | Description |
| ------ | ------ |
| Enabled | Using this field, you can specify whether the organization is enabled or not. |
| Name | Alanın adını belirtmektedir.<br><i class="fas fa-exclamation-triangle"></i> Alan adı ile ilgili olarak lütfen aşağıda belirtilen ölçütlere dikkat ediniz.<br><br>`Required` |
| Description | Alan ile ilgili Descriptionların girilebileceği Form Fielddır. |
| Görünüm | Alanın görüntülenme biçimini belirtir. Alanlar **"Genel"** ya da **"Özel"** olabilir. **"Genel"** alanlar Marketplace üzerinde görüntülenebilir. **"Özel"** alanlar sadece yetkisi olan kullanıcılar tarafından görüntülenebilir. |
| Alan Logosu | Alana ait simgenin yüklenebileceği Form Fielddır. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Please consider the followings regarding your organization name:
    <ul>
        <li>It must contain only English characters.</li>
        <li>It cannot contain spaces and tab characters.</li>
        <li>It must be longer than two characters.</li>
        <li>You can enter only the "-" and underscore "_" characters as punctuation.</li>
        <li>It cannot begin with number, the middle line "-" and the underscore "_".</li>
    </ul></p>
</div>

## Organization Page
Daha önceden eklenmiş bir alana ait özelliklerde değişiklik yapmak için kullanabileceğiniz sayfadır. Bu sayfa üzerindeki form alanları ile ilgili detaylı bilgi için [Yeni Alan Sayfası](#yeni-alan-sayfası) bölümüne bakabilirsiniz.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>
        Alan adını değiştirdikten sonra, eski alan adınız <strong>HEMEN UYGUN DURUMA</strong> geçecek ve başka bir kullanıcı tarafından kayıt edilebilecektir.
    </p>
</div>

## Organization Members Page
Alanı görüntüleme, düzenleme ve yönetme faaliyetlerini gerçekleştirecek kullanıcıların belirlendiği bölümdür.

Alana 3 (üç) farklı türde üye eklebilirsiniz:
- Owner: Alan üzerinde tam yetkiye sahiptir. Başka yönetici kullanıcılar ekleyebilir.
- Developer: Alan özelliklerini güncelleme yetkisine sahiptir. Alan içinde yeni bir proje ve kalıp oluşturabilir.
- Viewer: Alan özelliklerini görüntüleyebilir ancak güncelleme yapamaz.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>Alana ekleyeceğiniz üyelerin platforma üye olmaları gerekmektedir. Daha önceden üye kaydı yapmamış üyelerin e-posta adresini belirterek; davet gönderebilirsiniz.</p>
</div>