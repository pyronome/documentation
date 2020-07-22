---
id: platform-hakkinda
title: Hakkında
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

**Dünyada 2016 yılında yazılım projeleri için 300 milyar dolardan fazla para harcandı. Ancak bu projelerin yalnız %33'u başarıyla tamamlandı. %48'si süre ve bütçe aşımına uğradı. %19'u ise hiç tamamlanamadı. Yani yaklaşık $60 milyar dolar çöpe gitti.**

**Biz bu büyük kaybın önüne geçilebileceğine inanıyoruz.**

2012 yılında, yazılım geliştirmenin daha kolay ve hızlı bir yolunu bulduk. Bulduğumuz çözümü birçok ticari projede başarıyla uyguladık. Sonrasında bu çözümü tüm dünya ile paylaşmaya karar verdik. Böylece Pyronome doğmuş oldu.

Pyronome, hızlı, sürdürebilir ve ölçeklenebilir yazılımlar geliştirilmesini sağlayan çevrimiçi bir platformdur.

Yazılım geliştirme işi, gerçek-hayat problemlerini bilgisayar sistemleri yardımıyla çözmek olarak özetlenebilir. Bilgisayar sistemleri, gerçek hayat sistemlerine -sosyal sistemler- göre kapsamı ve sınırları belli bir yapıya sahiptir. Öte yandan gerçek hayat sistemleri -sosyal sistemler-, daha karmaşık ve sınırları kimi zaman kolay belirlenemeyen bir yapıya sahiptir. Bir sosyal sistemin bilgisayar sistemleri ile desteklenebilmesi için sosyal sistemin bilgisayarın anlayabileceği bir dile dönüştürülmesi gerekmektedir. Bu dönüştürme aşamasında, sosyal sistem belli bir yaklaşımla bölümlere ayrılmalı, belirlenen bölümler içindeki işlemler, bu işlemleri yapacak kullanıcılar, bu işlemlerin etkilediği diğer işlemler ve bu etkileşimin girdileri ve çıktıları tam ve kesin olarak belirlenmelidir.

2005 yılında, [Aykut Aydınlı](https://github.com/aykutaydinli) tarafından Sanpark projelerinde kullanılmak üzere bir kavram geliştirilmiştir. Ortaya konan bu kavram, gerçek hayat sistemlerini, bilgisayar sistemlerinin sınırlarına hiç odaklanmadan -başka bir deyişle gerçek hayat sistemlerini, bilgisayar sistemlerinden izole ederek- bir tanım dili yardımıyla anlamsal olarak modelleme esasına dayanmaktadır. Eğer modelleme aşamasında belirlenen dil doğrudan bilgisayar dillerine dönüştürülebilirse, anlamsal olarak modellenebilen her sosyal sistem doğrudan bilgisayar sistemlerine dönüştürülebilir. Öte yandan bilgisayar sistemleri tarafından modellenemeyecek her sosyal sistem zaten belirlenen dil ile de modellenemeyeceği için bu analiz aşamasının en başında farkedilebilecektir.

Başlangıçta bu modelleme aşamasında anlamsal modelleme dili olarak XML kullanılmaktaydı. Geliştirilen otomatik dönüştürme araçları ile XML ile modellenen sistemler başarılı bir biçimde çalışan bilgisayar sistemlerine dönüştürülmüştür. Bununla birlikte sosyal sistemler dinamik bir yapıya sahiptir ve zaman içinde değişiklik gösterebilmektedir. Değişen sosyal sistem tekrar XML dili ile modellenmiş ve otomatik dönüştürme ve kaynak kod üretim araçları ile yeni sosyal sisteme uygun bilgisayar sistemi üretilebilmiştir.

2007 yılının sonlarına kadar modelleme dili olarak XML dili kullanılmıştır. XML dili yerine kullanılabilecek diğer diller belirlenmiş; ancak belirlenen dillerin de ihtiyaçları karşılamakta yetersiz olduğu anlaşılınca yeni bir modelleme dili geliştirilmiştir. Böylelikle [Modo](http://modolanguage.org) dili doğmuştur. [Modo](http://modolanguage.org) dili basit sözdizimi ile bilgisayar teknolojilerine hakim olmayan kişiler tarafından da rahatlıkla okunup yazılabilmektedir. 2 yıl boyunca [Modo](http://modolanguage.org) dili birçok gerçek hayat sisteminin modellenmesinde test edilmiş; 2009 yılı Haziran ayında [Modo](http://modolanguage.org) diline son şekli verilmiş ve dil tanımı [Aykut Aydınlı](https://github.com/aykutaydinli) ve [Doruk Eker](https://github.com/dorukeker) tarafından tamamlanmıştır.

[Modo](http://modolanguage.org) dilinden diğer bilgisayar dillerine dönüşüm yapabilen kaynak kod üreteçleri için evrensel bir altyapı geliştirilmiş ve bu evrensel altyapı ile 2012 yılında Pyronome platformu doğmuştur. Başlarda kaynak kod üreteçleri doğrudan [Modo](http://modolanguage.org) dilindeki tanımları okumakta ve ilgili dildeki tanımlara dönüştürmekteydi. Her dil için ayrı ayrı üreteçler yazılmakta ve bu üreteçlere yeni özellikler eklemek zaman almaktaydı. 2012 yılında geliştirilen ilkörnekle, genel tanımlar, farklı bilgisayar dillerine kolaylıkla dönüştürülmüştür. 2012 yılında geliştirilen bu genel tanımlara "Kalıp" ismi verilmiştir.

2014 yılında kalıpların oluşturulması için web tabanlı arayüzler geliştirilmiş; kalıpların hiç kodlama yapmadan oluşturulması sağlanmıştır. 2017 yılından sonra edinilen bu birikimin dünya üzerindeki tüm geliştiricilerle paylaşılmasına karar verilmiştir.