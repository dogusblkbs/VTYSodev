#Nazif Doğuş Bölükbaş 121519055 VTYS
Marmara Üniversitesi Fen Fakültesi İstatistik Bölümü

🎯 Projenin Amacı
Bu projenin amacı, kiralanabilir powerbank hizmeti sunan bir sistemde kullanıcıların cihazları ne kadar süreyle kullandığını, bu kullanımın yaş gruplarına göre farklılık gösterip göstermediğini ve günlük elde edilen kazancı analiz edebilecek bir veritabanı yapısı oluşturmaktır.

🧱 Kullanılan Tablolar ve İlişkiler
1. Kullanici

id, KullaniciAdi, KullaniciSoyad, KullaniciYas, KullaniciCinsiyet

Uygulamaya kayıtlı kullanıcıların kişisel bilgilerini tutar.

2. Powerbank

PowerbankID, UretimYili, SonKullananID, SonKiralamaTarihi

Şirket envanterinde bulunan cihazlar ve en son kullanım bilgileri yer alır.

3. Kiralama

KiralamaID, KullaniciID, PowerbankID, KiralamaTarihi, KullanimSuresiDakika, DakikalikUcret, ToplamUcret

Kullanıcıların gerçekleştirdiği kiralama işlemleri kayıt altına alınır.

4. Lokasyon

ID, Sehir

Powerbank hizmeti verilen şehir bilgileri tutulur.

5. KiralamaLokasyon

LokasyonID, KiralamaID, KullaniciID

Her kiralamanın hangi kullanıcı tarafından, hangi lokasyonda yapıldığı belirtilir.
