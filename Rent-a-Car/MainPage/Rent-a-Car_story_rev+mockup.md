### Summary: Kullanıcının Girilmiş Verilere Uygun Bir Şekilde Araçları Filtreleyebilmesi 
 
 ![](https://www.hizliresim.com/7eye778.png)
 
 Accaptence Criterias:
 Varsayım 1: Kiralama işlemleri Yurtiçi için geçerli olacaktır. 
 Varsayım 2: Lokasyon isimleri veritabanında doğrulanmış bir şekilde bulunmaktadır.
 
 1. Kullanıcının aracı hangi lokasyondan alacağını seçebileceği bir seçim kutusu oluşturulmalıdır.
  1.1. Lokasyon, lokasyon adı içerisinde geçecek şekilde aranabilir. Büyük - küçük harf duyarlılığı yoktur.
  1.2. Girdi yazılırken daha önce en çok arananlar listelenerek sıralanmalıdır. 
  1.3. Kullanıcıyı yönlendirmek amaçlı girdi kutusunda gölgeli yazı(placeholder) "Nereden Alacaksınız?" yazmalıdır.
  1.4. Kullanıcıyı yönlendirmek amaçlı seçim kutusu üstüne üzerine tıklandığında "Listeden Seçim Yapabilir veya Lokasyon Adı Yazabilirsiniz" (pop-up) ibaresi belirten bir bilgi ikonu oluşturulmalıdır.
  1.5. Seçim Listesi içerisinde kullanıcının bulunduğu konumu seçebileceği bir konum ikonu olmalıdır. 
   1.5.1. Mevcut Konum ikonu tıklandığında "Mevcut Konumu Kullan" (pop-up) ibaresi belirmelidir. 
   
  ![](https://www.hizliresim.com/mlm3qnp.png)
  
 2. Aracın alış tarihinin ve saatinin seçilebileceği bir tarih - saat seçim alanı oluşturulmalıdır.
  2.1. Takvim seçildikten sonra saat seçim alanı belirmelidir.
  2.2. ilk olarak İade tarihi seçildi ise alış tarihi seçiminde seçilen tarih ve saat sonrası seçilemez ve aktif olmamalıdır.
  
  ![](https://www.hizliresim.com/lyzizzf.png)
  
 3. Aracın iade tarihinin ve saatinin seçilebileceği bir tarih - saat seçim alanı oluşturulmalıdır.
  3.1. Tarih seçildikten sonra saat seçim alanı belirmelidir. 
  3.2. ilk olarak Alış tarihi seçildi ise iade tarihi seçiminde seçilen tarih ve saat öncesi seçilemez ve aktif olmamalıdır. 
  
  ![](https://www.hizliresim.com/hlkhc9r.png)
  
 4. Sürücünün Yaşının seçilebileceği bir seçim kutusu oluşturulmalıdır.
  4.1. Kullanıcıyı yönlendirmek amaçlı seçim kutusu üstüne üzerine tıklandığında "Uygun Araçlar İçin Yaş Aralığınızı Seçiniz" (pop-up) ibaresi belirten bir bilgi ikonu oluşturulmalıdır.
  
  ![](https://www.hizliresim.com/i76e88z.png)
  
 5. Aracın kiralandığı lokasyondan farklı bir lokasyona iade edilebilmesi durumu için opsiyonel bir tik kutusu olmalıdır ve yanında "Farklı Yerde Bırakacağım" yazılmalıdır.
  5.1. Tik kutusunun tıklanmadan önce üzerine tıklandığında "Araç iadenizi farklı bir lokasyonda gerçekleştirebilirsiniz" (pop-up) ibaresi belirten bir bilgi ikonu oluşturulmalıdır.
  5.2. Tik kutusu tıklandığında, tik kutusu yanındaki yazı ortadan kalkarak "Araç Teslim Lokasyon" seçim kutusunun aynısı iade lokasyonu için belirmeli.
  5.3. Belirecek "Araç İade Lokasyonu" seçim kutusu için 1. maddedeki kabul kriterleri geçerlidir.
  5.4. Kullanıcının yanlışlıkla tıklama ihtimaline veya fikrini değiştirme ihitimaline karşın tik kutusu tıklandıktan sonra işlemin geri alınabileceği bir çarpı işareti oluşturulmalıdır. 
  5.5. Çarpıya tıklandığında lokasyon seçim kutusu gitmeli ve ilk aşamada bulunan Farklı Lokasyon tik kutusu geri gelmelidir. 
  
  ![](https://www.hizliresim.com/f9lmoeo.png)
  
 6. Kullanıcının promosyon kullanabilmesi için bir tik kutusu olmalıdır ve yanında "Promosyon Kodu Kullan" ibaresi yazmalıdır.
  6.1. Tik kutusunun tıklanmadan önce üzerine tıklandığında "Promosyon Kodu Kullanabilirsiniz" (pop-up) ibaresi belirten bir bilgi ikonu oluşturulmalıdır.
  6.2. Tik kutusu tıklandığında, tik kutusu yanındaki yazı ortadan kalkarak "Promosyon Türü" için bir seçim kutusu ve "Promosyon Kodu" için bir girdi kutusu oluşturulmalıdır.
  6.3. Seçilen "Promosyon Türü"ne göre "Promosyon Kodu" girdi kutusu ismi değişmelidir. 
  Örneğin; Anadolubank ve Denizbank harici bir banka seçimi yapıldığında, Promosyon kodu girdi kutusu "Kart No'nuzu Giriniz" olarak değişmeli.
  Zubizu seçimi yapıldığında, Promosyon kodu girdi kutusu "Tel No'nuzu Giriniz" olarak değişmeli.
  Diğer seçimlerden biri yapıldığında "Promosyon Kodunuzu Giriniz" olarak kalmalı. 
  6.4. "Promosyon Türü" ('Miles & Smiles', 'Sağlık Çalışanı', 'Türk Hava Yolları', 'Pegasus Bolbol', 'Türk Telekom Prime') seçeneklerinden biri seçildiğinde "Promosyon Kodu" Girdi kutusu ortadan kalkmalı. Başka bir seçim yapıldığında geri gelmelidir.
  6.5. Kullanıcının yanlışlıkla tıklama ihtimaline veya fikrini değiştirme ihitimaline karşın tik kutusu tıklandıktan sonra işlemin geri alınabileceği bir çarpı işareti oluşturulmalıdır. 
  6.6. Çarpıya tıklandığında Promosyon Türü seçim kutusu ve Promosyon Kodu girdi kutusu gitmeli ve ilk aşamada bulunan promosyon kullanımı tik kutusu geri gelmelidir.
  
  ![](https://www.hizliresim.com/972wdjk.png)
  
 7. Kullanıcıya uygun araçların filtrelenebilmesi için "Uygun Araçları Listele" isimli bir buton oluşturulmalıdır. 