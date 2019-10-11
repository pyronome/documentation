---
id: temel-kavramlar
title: Temel Kavramlar
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

## Sıfır Hatalı Yazılım Kavramı

Genel bir bakış açısıyla, her ne şekilde olursa olsun kullanıcı ihtiyaçlarını karşılamayan yazılım hatalı olarak değerlendirilebilir. Bu durum aşağıdaki sebeplerin biri ya da hepsinin bir araya gelmesiyle oluşabilir:

1.  Yazılım içinde kodlama hataları bulunmaktadır ve yazılım yapması gereken işlemleri yaparken hata vermekte ya da hatalı çıktılar üretmektedir.
2.  Yazılımın bir parçası olduğu gerçek hayat sistemi -sosyal sistem- doğru bir biçimde analiz edilmediği için geliştirilen yazılım bu sosyal sistemdeki işlemleri desteklemek yerine bu işlemlerin yapılmasını zorlaştırmakta ya da engellemektedir.

Sıfır Hatalı Yazılım kavramı bir ideal durumu simgelemektedir. Sıfır Hatalı Yazılım ideal durumuna yaklaşmak isteyen bir kişi yukarıda belirtilen iki farklı hata grubunda oluşabilecek hataların önüne geçebilmelidir.

Birinci grup hatalar, çalışma zamanı hataları, başka bir deyişle "bug"lardır. Yazılımlar bilgisayar komut satırlarının belli bir düzen ve belli bir sıra ile ard arda dizilmesi ile oluşurlar. Her bir komut satırında belli bir hata olasılığı olduğu varsayılırsa, komut satır sayısı arttıkça hata olasılığı da artacaktır. Tam tersine, hata oluşabilecek komut satırlarının sayısını düşürmek de hata olasılığını düşürecektir. Yeniden kullanılabilir kaynak kod kütüphaneleri, kaynak kod üreteçleri, bulutta hizmet veren ve yazılımın yapacağı faaliyetlerin bir bölümünü üstlenen çevrimiçi hizmetler, geliştirilmekte olan yazılımın kaynak kod satır sayısını düşürebileceği için birinci tip hataların oluşma olasılığını düşürebilecektir.

İkinci tip hatalar ise tasarım zamanı hataları olarak ifade edilebilir. Yazılımın bir parçası olacağı gerçek hayat sistemininin -sosyal sistem- süreçlerinin, paydaşlarının ve gereklerinin analizi aşamasında oluşan hatalardır. Gerçek hayat sistemlerinin analizi aşamasında analizi yapan kişinin tecrübesi ve bilgi birikimi ikinci tip hataların önlenmesi açısından büyük bir önem taşımaktadır. Ancak deneyim ve bilgi birikimi sınırlı kişiler tarafından da deneme-yanılma ile bu hataların giderilmesi zaman içerisinde sağlanabilmektedir. Deneme-yanılma metodu her durum için uygun değildir. Bununla birlikte deneme-yanılma metodu yanılma maliyetinin/süresinin düşük olması durumunda anlamlı bir seçenek niteliğine kavuşabilmektedir. Bu noktada, kaynak kod üreteçleri bu deneme-yanılma sürecinde yanılma maliyetinin/süresinin düşürülmesinde kullanılabilir.

Özetle, Sıfır Hatalı Yazılım kavramı bir ideal durumu simgelemektedir. Bu ideal duruma yaklaşmak için yazılım tasarım ve çalışma zamanı hatalarının önüne geçilmesi gerekmektedir. Kaynak kod üreteçleri, yeniden kullanılabilir kütüphaneler, bulutta hizmet veren çevrimiçi hizmetler hem tasarım hem de çalışma zamanı hatalarının önüne geçilmesini sağlayabilir.

## Çevik Yazılım Geliştirme

Çevik Yazılım Geliştirme, geleneksel kalıpların dışına çıkan yaklaşımlar kullanarak, daha iyi yazılım geliştirmenin yollarını arayan değerler ve prensipler bütünüdür. Çevik Yazılım Geliştirme, belirli ve kesin kurallara dayanmaz ya da belli bir metod, araç ve/veya anaçatı önermez. Bunun yerine bir yazılım geliştirme felsefesi ortaya koymaktadır. Yazılım geliştirirken, geliştirme ekibi, birçok konuda farklı kararlar almakta ve bu kararlar geliştirilen projenin bütün süreçlerini etkilemektedir. Geliştirme sürecinin tamamında, Çevik Yazılım Geliştirme değerleri ve prensipleri göz önünde bulundurularak kararların alınması bu yazılım geliştirme felsefesinin temelini oluşturmaktadır.

[Çevik Yazılım Geliştirme Manifestosu](https://agilemanifesto.org/)'na göre:

Çevik Yazılım Geliştirme,
- Süreçler ve araçlar yerine **bireyler ve etkileşimlere**,
- Ayrıntılı belgeleme yerine **çalışan yazılıma**,
- Sözleşmeye uygunluk yerine **müşteri ile işbirliğine**,
- Planlara bağlı kalmak yerine **değişime uyum sağlamaya**,

odaklanmaktadır.

Çevik Yazılım Geliştirme yaklaşımı her ne kadar geleneksel Şelale yaklaşımına alternatif olarak ileri sürülse de, her iki yaklaşımın da kendine has avantajları ve dezavantajları vardır. Başka bir deyişle, Çevik Yazılım Geliştirme yaklaşımının, Şelale yaklaşımından daha üstün olduğu ya da tersini söylemek güçtür. Buna karşın Çevik Yazılım Geliştirme yaklaşımının, sonuç odaklı doğası ve belli kalıpların dışına çıkarak sürekli olarak yazılım geliştirmenin daha iyi yollarını araması, yazılım geliştirme yaklaşımları arasında önemini özellikle son yıllarda fazlasıyla artırmıştır.

## Yalın Yazılım Geliştirme

Yalın Yazılım Geliştirme yaklaşımını iyi anlamak için sistemler için kullanılan "Yalın" kavramını anlamamız gerekmektedir. Yalın kelimesi hızlı ve esnek bir üretim akışını ifade etmektedir. Sistemler için kullanılan "Yalın" kavramı, en yüksek verimle, ilgili sistemin paydaşlarına en yüksek değeri sağlayan sistemler olarak özetlenebilir. Yalın Yazılım Geliştirme yaklaşımı Toyota'nın Yalın Ürün Geliştirme yaklaşımına dayanmaktadır.

Yalın Yazılım Geliştirme yaklaşımı, etkili bir takım, etkin ve sürdürebilir süreçlerle hızlı ve düşük maliyetli yazılım geliştirme olarak tanımlanabilir. Yalın Yazılım Geliştirme amacıyla bir araya gelen geliştirme ekibinin, geliştirme süreçlerinde sürekli iyileştirmeye odaklanması gerekmektedir.

- Bütünsel en iyileme yaklaşımı,
- Zaman alan ve gereksiz süreçlerin ayıklanması,
- Etkin, verimli ve sürdürülebilir yaklaşımlarla kalitelin inşa edilmesi,
- Planlamaya sadık kalma,
- Sistemin paydaşlarını tanıma ve ihtiyaçlarını önemseme,
- Bilginin deneyimlenip birikime dönüşmesini sağlama,
- Hızlı sonuç üretme, Yalın Yazılım Geliştirme prensipleri olarak sayılabilir.

Yalın Yazılım Geliştirme yaklaşımın uygulanabilmesi için, geliştirme ekibi herhangi bir üretim sürecine başlamadan önce, tüm isterleri birim özelliklere dönüştürmelidir. Geliştirme ekibi sistemin kullanıcıları/paydaşları/müşterileri ile sürekli iletişimin önemini kavramalı, varsayımlarla değil sürekli iletişimle sağlanacak bir etkileşim ortamını oluşturmalıdır. Yalnızca gerekli ve yapılabilir nitelikte olan özelliklere odaklanılmalıdır. Eğer bir özellik talep edilmiş ancak uygulanması mümkün değilse, bu özelliğin geliştirilmesi için zaman harcanmamalıdır. Sürekli gözlem ve ölçümle, zaman alan süreçlerin iyileştirilmesi gerekmektedir. Ara-çıktıların mümkün mertebe nihai çıktılara dönüştürülmesi sağlanmalı, gereksiz süreçlerin önlenmesi gerekmektedir. Geliştirme ekibi, geliştirilen sisteme her ne şekilde olursa olsun bir katkı sağlayan herkesi kapsamaktadır. Yöneticiler, analizciler, kalite mühendisleri, geliştiriciler, sistem yöneticileri, kurulumu yapan kişiler ile geliştirilen sistemin desteğini veren kişiler geliştirme ekibinin bir üyesi olarak kabul edilmektedir. Süreçlerin iyileştirmesi için yapılan her türlü öneri dikkatle değerlendirilmelidir. Bununla birlikte süreçlerin iyileştirmesi için yapılan önerileri değerlendirecek ve uygun olanlarının uygulanmasını sağlayacak bir strateji geliştirilmelidir.

## Az-Kod Platformları

20 yıldan daha fazla süredir firmalar, kendi süreçlerinde verimlilik artışı sağlamak için çok büyük yazılımlar satın almaktadır. Bu yazılımlar belli bir işlevselliğe sahip olsa da değişen durumlara adaptasyon yetenekleri sınırlıdır. İnternetin hayatımıza girmesiyle sınırlar kalkmış ve firmaların yerel rekabet ortamları küresel bir boyut kazanmıştır. Başka bir deyişle, bugün bir otomobil yedek parçası üreten bir firma yalnızca kendi ilinde ya da ülkesindeki firmalarla değil, tüm dünyadaki firmalarla rekabet etmek zorundadır. Değişen rekabet ortamı, firma ölçeklerini ve iş-yapış şekillerini derinden etkilemiştir. Yeniliklere adaptasyon ve yeni iş-yapış şekillerinin hayata geçirilme zorunluluğu, firmaların kullanmakta olduğu bu büyük yazılımların yeni özelliklere sahip olmasını gerektirmiştir. Bununla birlikte küresel boyuttaki rekabet ortamı farklı farklı firma kültürlerinin oluşmasına sebep olmuştur. Alışılagelmiş yapıların dışındaki yeni firma kültürlerine standart yaklaşımlarla işleyen bu büyük yazılımlar uyum sağlamakta zorlanmış; ek maliyetlerle zaman alan güncellemeler önerilmiştir. Bu güncellemeler hem yazılım üreten hem de yazılımı kullanan firmalar için maliyetli ve yönetilmesi zor süreçler ortaya çıkarmıştır. Bu nedenle birçok firma hesap tabloları kullanmaya başlamış; hesap tablolarının esnek yapısı ile değişen koşullara uyum sağlamaya çalışmıştır.

Büyük yazılımların yeni koşullara uyum sağlama güçlüğü ile hesap tablolarının bilgi paylaşım, güncelleme yönetimi ve eş zamanlı kullanılmasında karşılaşılan güçlükler az-kod platformlarını ortaya çıkarmıştır.

Az-kod platformları kod yazmadan ya da çok az kod ile yeni özellikler eklenebilen yazılım platformlardır. Böylelikle yazılım bilgisi sınırlı kişiler tarafından aynı hesap tablolarında olduğu gibi kolaylıkla kullanılabilmekte ve yeni özellikler eklenebilmektedir. Bulut tabanlı teknolojilerin gelişmesiyle yerden ve zamandan bağımsız şekilde mobil cihazlar üzerinden erişimi de mümkün hale gelmiştir. Bu özellikleri sayesinde birçok firma tarafından kabul görmüş ve kullanılmaya başlanmıştır.