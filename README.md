# yararli-dosyalar

# ögrenci olarak kartımın sifresini değiştirebilmeliyim

* Ögrenci sifre değiştirme ekranına gelir. Bu ekranda kullanici adi, eski sifre, yeni sifre, yeni sifreyi onaylabildiğim alanlar bulunmaktadır. Kullanici adi alanı giriş yaptığı için degeri otomatik girilmiştir. Bu alanlara göre sifre değişir.

* Kabul Kriterlerim
	* Kullanici adi alanı değişemez.
	* Geçerli bir kullanici adi olmalıdır.
	* son kullandığım 2 şifre yeni şifre olamaz.
	* En az 8 harfden oluşmalıdır. En az 1 adet sayı, özel -karakter ve harf olmalıdır.
	* Eski parola doğru girilmelidir.
	* Yeni şifre ile onayladığım yeni şifre alanların değerleri eşleşmelidir.
  
# ögrenci olarak satın aldıklarımı görüntüleyebilmeliyim

* Ögrenci daha önce aldıklarını ögrenmek veya merak etmek isteyebilir. Bundan dolayı ögrenci kendi sayfasında bunları listeli bir şekilde görüntüleyebilir. Bunun için ögrenci o ekrana gelir. Bu ekranda satın aldıkların listesi sayfalama şeklinde gelmektedir.

* Kabul Kriterlerim
  * maksimum 1 yıl geçmiş satın alınanları görüntüleyebilsin.
  * her sayfa 5lerli elemanlar şeklinde gösterilsin.
  * En son satın aldığı ilk sıraya gelecek şekilde gösterilsin.
  
# ögrenci olarak yemek alabilmeliyim

* Yemekhanenin ögrenci kartını okuyabildiği bir makinesi bulunmaktadır. Ögrenci yemekhaneye gelerek sisteme kartını okutur. Bu cihaz ögrenci karttan kullanıcı adini alabiliyor. Ve buna göre satın alma işlemi gerçekleşiyor. 

* Kabul Kriterlerim
  * Geçerli bir kullanıcı adi olmalı
  * Ögrenci kartı aktif olmalı
  * burslu ögrenci 1 defaya mahsus bakiyesini azalmamalı
  * ilk alışta yemek fiyatı kadar bakiye azalmalı
  * ikinci veya daha fazla alımda yemek fiyatın 2 katı kadar bakiye azalmalı
  * maksimum günlük 3 yemek alabilir.
  * satın alınanlara eklenmeli
  
# Sistem yöneticisi olarak ögrencinin aldığı yemeği iptal edebilmeliyim

* Ögrenci olarak bir yemek satın alınır. Ve daha sonra yanlışlıkla bir tane daha satın alır ve bunu iptal edilmesini istiyor. Sistem yöneticisi ögrencinin bu satın aldığı yemeği yemediğinden emin ise silme süreci başlar. Bunun için sistem yöneticisi yemeği iptal edeceği ekrana gelir. Burada kullanıcı kullanici adi alanını girerek(bir cihaza kartı okutarakta girebilir) satın aldığı yemeği siler.

* Kabul Kriterlerim
  * Geçerli kullanıcı adı girer
  * Ögrenci bakiyesi aldığı fiyat kadar artmalı
  * Ögrenci satın aldıklarından silinmeli
  * Satın aldığı gün ile iptal talebi edilen gün aynı olmalıdır.
  * Sadece öğrencinin aldığı son yemek iptal edilebilir.
  * Sistem yöneticisi aynı kullanıcı adına sahip aynı gün sadece 1 kez iptal işlemi gerçekleştirebilir.
  
# Sistem yöneticisi olarak ögrenci kart geçerlilik süresini güncelleyebilmeliyim

* Kartların geçerlilik süresi 1 dönem kadardır. 1 dönem geçen kartlar bloke olmaktadır. Bu nedenle sistem yönetici bu kartı aktif hale getirmesi gerekir. O yüzden ögrenci kartı geçerlilik süresini otomatik 1 dönem daha aktif halde güncelleyebilmelidir. Bunun için sistem yöneticisi kart günceleme sayfasına gelir. Burada 1 öğrenci kullanıcı adi, kimlik numarası ve ad soyad girebileceği alanlar ve ögrenci belgesini yükleyebileceği alan bulunur.

* Kabul Testleri
  * Kullanıcı adi geçerli olmalı ve o hesaba ait kimlik numarası ad soyad bilgisi eşleşmeli
  * Kartın geçerlilik tarihi bitmiş olmalı
  * Okuldan alınan islak imzalı ögrenci belgesi veya edevleten alınan ögrenci belgesi sisteme eklenmeli
 
# sistem yöneticisi olarak ögrencilere burs verebilmeliyim

* Ögrenciler bursa başvururlar. Bu bursdan gerekli belgeleri teslim ederek sistem yöneticisine başvurur. Sistem yöneticisi her dönem bir dönem geçerli olmak süretiyle bursa başvuran bazı ögrencileri şeçer. Bu kişilere 1 gün 1 yemek hakkı kazandırır.

* Kabul Teslerim
  * Bir dönem içerisinde yanlızca 1 defa gerçekleşir.
  * Maksimum 100 ögrenciye burs verebilir.
  * Bunların 80 tanesi maddi durumu az olandan oluşmalı
  * 20 tanesi ise farklı bölümlerden birer tane ve en iyi çalışkan(1. sınıf için bir önceki ögrenim diploma notu, 2 ve sonrası için şuana kadarki ortalaması ) ögrencilerden oluşmalıdır
  * 100 kişi farklı kişiler olmalıdır.
  
# ögrenci olarak burs başvurusu yapabilmeliyim

* Burs butonu burs ekranına geçmek içindir. Bu burs butonu her dönem başında aktif olmaktadır. Ögrenciler bu burs butonu aktif olduğunda burs ekranına gelir. Burada ailede aylık kaç lira maaş geldigi, kaç kardeş, başarı notu ve bunu ispat eden belge ve aylık maaşları ispatladığı belge alanları girilerek burs başvurusu gerçekleştirilir.

* Kabul Testlerim
  * Ögrenci verilen bütün alanları girmelidir.
  * 1 dönemde 1 kez başvurulabilir.
