#  XML / JSON Formatlarında Spor Veri Hizmetleri [[zporsdata.com](https://www.zporsdata.com "zporsdata.com")]
### Real-Time Sports Data Feed API Services JSON / XML

> Zporsdata.com olarak birden fazla kaynağa ait verileri bir API yapısı ile sizlere sunmayı amaçladık ve başardık. Bu hizmetleri kolayca kullanabileceğiniz sorgu yapıları mevcut ve bu yapıların kullanımını daha da kolaylaştırmak için detaylı açıklamaların yer aldığı bir "API Doküman" sayfası da yer almaktadır.

> Zporsdata.com API yapısında yer alan veriler sadece bahis yapıları için değil kişisel projeleriniz için de kullanabilirsiniz. Birden fazla özelliştirme ile paketler oluşturduk ve belli başlı özellikleri kategorilendirdik. Böylece ihtiyacınıza ve bütçenize uygun hizmeti tercih edebilmeniz sağlandı. 

> Birden fazla kaynağa ait veri hizmetinin dahil olduğunu belirtmiştik. Birden fazla kaynağın yer almasının sebebi, çeşitliliğin yer almasını istediğimiz içindir. Bir dönem X kaynağını tercih edebilir ve daha sonraki dönemlerde bu kaynağı değiştirebilirsiniz. Veri şablonları standart hale getirildi ve bu şekilde hizmete açıldı. Sadece kaynaklara göre değişiklik gösteren ek veriler ya da çıkarılan veriler (- ya da +) yer alabilir. Bu tip durumlar kaynakların benzersiz yanlarından dolayıdır. 

> Şu an için kaynaklar arasındaki isimler; "[Iddaa](https://www.zporsdata.com/urun-hizmetler/etiket/iddaa "Iddaa")", "[Bwin](https://www.zporsdata.com/urun-hizmetler/etiket/bwin "Bwin")", "[Bet3000](https://www.zporsdata.com/urun-hizmetler/etiket/bet3000 "Bet3000")", "[Hititbet](https://www.zporsdata.com/urun-hizmetler/etiket/hititbet "Hititbet")" ve "[Betradar](https://www.zporsdata.com/urun-hizmetler/etiket/betradar "Betradar")" şeklindedir. Zaman içerisinde bu kaynaklar artış gösterecektir. Tabii sizlerin de geri bildirimlerinizi de değerlendirmekteyiz. 

------------


**API Hizmetlerinde yer alan özellikler / hizmetler**

- 25+ Spor Dalı (Kaynağa göre değişmektedir)
- Gelecek Karşılaşmalar (Pre-Match / Bülten )
- Canlı Karşılaşmalar (Live / Canlı Bülten )
- Karşılaşma Oranları (Kaynağa göre değişen +100 market seçeneği)
- Karşılaşma Sonuçları 
- Karşılaşma Tahmin Sonuçlandırma (Kupon sonuçlandırma ile karıştırılmaması gerekiyor. Karşılaşma sonuçlandırma market bahsine göre seçim durumunu kontrol eder ve seçimin gerçekleşme cevabını verir)
- Karşılaşma Detayları (Karşılaşmanın bir çok detayını listeler. "Olaylar, Korner, Kart, Değişiklik vb. karşılaşma detayları")
-  +100 Spor dalların genel listesi
- Fikstür listesi
- Sezona ait takım listesi
- Ülkeler
- Ligler
- Sezonlar
- Oyuncular 
- Stadyumlar
- Hakemler
- Arşivler
- Aralarındaki karşılaşmalar


------------


## API Demo Yapısı 

> API yapılarını, kaynakları detaylı şekilde incelemeniz için bir demo yapımızda mevcuttur. Tek yapmanız gereken "Ürün / Hizmetler" sayfasından "Demo" sekmesine geçiş yaparak incelemek istediğiniz kaynağa ait paketi sepetinize eklemeli ve sipariş vermeniz yeterli olacaktır. Yetkililerimiz gerekli kullanıcı bilgilerini kontrol ederek uygunluğunuzu onayladıktan sonra siparişinizi onaylar ve hizmetiniz aktif hale getirilir. 

> Hizmetiniz aktif edildikten sonra panelinizde yer alan "ürün/hizmetlerim" sayfasından ilgili ürününüzün detaylarını inceleyebilir ve API yapısına erişim sağlamanız için gerekli olan "api_key" yani erişim anahtarı bilgisine ulaşabilirsiniz.

> Satın almış olduğunuz hizmetlerde paketlere göre değişiklik gösteren sorgu limitleri mevcuttur. Bu sorgu limitleri aylık olarak kullanım hakkınızı belirler. API yapısına erişim sağladığınız her sorguda -1 şeklinde geri sayım gerçekleşir. Limite eriştiğinizde hizmetiniz pasif duruma geçer ve bir sonraki ödeme periyoduna kadar erişim sağlayamazsınız.





