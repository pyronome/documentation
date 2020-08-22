---
id: platform-surum-gecmisi
title: Platform Sürüm Geçmişi
sidebar_label: Sürüm Geçmişi
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

## Sürüm 3.1.3

1. Kalıpların "Ayarlar" bölümü altındaki "Pazaryeri" bölümüne "Etiketler" bölümü eklendi.
2. Proje sayfasına kalıp sayfalarında olduğu gibi "Değişkenler" bölümü eklendi. Böylelikle veritabanı şifresi, SSH anahtarı, erişim anahtarı, ortam değişkenleri vb. bilgiler proje içinden de tanımlanabilecek.
3. Kalıp şablonları için `skip_whitespace` özelliği eklendi. Böylelikle bir şablonun içeriğinde sadece boşluk karakterleri varsa; ilgili şablon için hiçbir işlem yapılmaması sağlanabilecek.
4. Arabirimde kullanım kolaylığı sağlayan güncellemeler yapıldı.
5. Arabirimde stil güncellemeleri yapıldı.
6. Doğru çalışmayan bazı bölüm ve özelliklerin, doğru çalışmasını sağlayacak yamalar yapıldı.

## Sürüm 3.1.2

1. Dışsal Kod Ekleme (Snippet Injection) için daha etkin bir dizin yapısı oluşturuldu.
2. Dışsal Kod Ekleme (Snippet Injection) için `__glue__`, `__header__`, `__footer__` ve `__default__` yardımcı dosyaları eklendi. (Bkz. [`snippets` Dizin Yapısı](/latest/tr/docs/basvurular-dissal-kod-ekleme-snippet-injection/#snippets-dizin-yapısı))
3. Kullanıcı profil ayarlarına zaman dilimi özelliği eklendi.
4. Kalıp şablon dosyaları için toplu indirme özelliği eklendi.
5. Kalıp şablonları için `skip_empty` ve `remove_whitespace` özellikleri eklendi. Böylelikle kaynak kod üretimi yapılırken, boş şablonlar geçilebilecek, ya da içinde sadece boşluk karakterleri olan şablonlardaki boşluklar kaldırılabilecek.
6. Kalıpların "Ayarlar" bölümü altındaki "Pazaryeri" bölümüne, detaylı fiyatlandırma seçenekleri eklendi.
7. Arabirimde kullanım kolaylığı sağlayan güncellemeler yapıldı.
8. Arabirimde stil güncellemeleri yapıldı.
9. Doğru çalışmayan bazı bölüm ve özelliklerin, doğru çalışmasını sağlayacak yamalar yapıldı.

## Sürüm 3.1.1

1. Üretilen kaynak kodun içine, model dosyalarının eklenmesi sağlandı.
2. Kalıp şablon yardımcılarına `{{! ... }}` kaçış simgesi eklendi. (Bkz. [Kaçış Simgesi](/latest/tr/docs/basvurular-kalip-sablonu-kaynak-kod-yardimcilari/#kaçış-simgesi))
3. Kalıp şablon yardımcılarına `{{@if ... }}` şeklinde denetim yapıları eklenmesi sağlandı. (Bkz. [Denetim Yapıları](/latest/tr/docs/basvurular-kalip-sablonu-kaynak-kod-yardimcilari/#denetim-yapıları))
4. Kalıp şablonları için Git kod deposu ekleme özelliği eklendi. Böylelikle şablonlar dosya olarak güncellenebilecek. Güncellenen dosyalar Git kod deposuna yüklenebilecek, Git kod deposuna yüklenen dosyalar tek tuşla kalıp şablonlar bölümüne çekilebilecek.
5. Şema, şablon ve model editörlerine kullanım kolaylığı sağlayan özellikler eklendi.
6. Arabirimde kullanım kolaylığı sağlayan güncellemeler yapıldı.
7. Arabirimde stil güncellemeleri yapıldı.
8. Doğru çalışmayan bazı bölüm ve özelliklerin, doğru çalışmasını sağlayacak yamalar yapıldı.

## Sürüm 3.1.0

1. Proje bölümü Files sayfası eklendi. Böylelikle projeler için statik dosyalar eklenebilecek.
2. Proje ve kalıplar için kalıp olarak Git kod deposu kurulum özelliği eklendi. Kaynak kod üretim aşamasında eğer Git kod deposu belirtilmişse; sırası geldiğinde Git kod deposundan belirlenen kaynak kodlar çekilecek ve belirlenen dizinlere kopyalanacak, daha kaynak kod üretim işlemi kaldığı yerden devam edecek.
3. Arabirimde kullanım kolaylığı sağlayan güncellemeler yapıldı.
4. Arabirimde stil güncellemeleri yapıldı.

## Sürüm 3.0.0

1. Kalıplar bölümü eklendi. Kullanıcılar bu bölümü kullanarak kendi kalıplarını ekleyebilecek.
2. Kaynak kod editörü eklendi. Böylelikle kullanıcılar kaynak kod üretim işleminden sonra üretilen kaynak kodu görüntüleyebilecek ve üzerinde değişiklik yapabilecek.
3. Çoklu dil arabirim desteği eklendi.
4. Şema, şablon ve modellerin JSON olarak indirilmesi ve yüklenmesi özelliği eklendi.
5. "Güncelleme Geçmişi" özelliği eklendi. Bu özellik Şema, şablon ve model üzerinde yapılan tüm güncelleme işlemlerini tarayıcının yerel hafızasında `indexedDB` veritabanını kullanarak kaydediyor. Bu özellik sayesinde daha önce yapılmış güncellemelere geri dönülebiliyor.
6. Kalıplar ve projeler için sürüm özelliği eklendi.
7. Projeler ve kalıplar için çoklu-kalıp ekleme özelliği eklendi. Böylelikle kullanıcılar projelerine birden fazla kalıp ekleyebilecek. Eklenen kalıpların kaynak kodu tek seferde üretilebilecek.