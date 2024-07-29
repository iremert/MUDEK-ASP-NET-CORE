# MHRS-ASP-NET-CORE


## Projemin Amacı ve Tanıtımı
-Müdek (Mühendislik Eğitim Programları Değerlendirme ve Akreditasyon Derneği) web sitemin amacı ,tüm paydaşların etkin bir şekilde etkileşimde bulunabileceği bir platform sunmaktır. 
-Bu site, mühendislik fakültelerinin eğitim programlarının ulusal ve uluslararası standartlara uygunluğunu değerlendirmek, sürekli iyileştirme süreçlerini desteklemek ve akreditasyon süreçlerini yönetmek üzere tasarlanmıştır. Müdek’in misyonu , mühendislik eğitiminin kalitesini arttırmak, öğrencilerin, mezunların ve toplumun beklentilerini karşılamaktır.
-Web sitemde dört ana panel vardır; Kullanıcı paneli, Bölüm koordinatörü, Öğretim Görevlisi, Müdek Denetçisi.
-Bu panellerin her biri , kullanıcıların rolleri ve ihtiyaçlarına göre özelleştirilmiş işlevler sunarak, değerlendirme ve akreditasyon süreçlerini daha verimli hale getirir.






## Projemde Kullanılan Teknolojiler
-Projemi geliştirirken  C# dilini , web tarafında çatı olarak Asp Net Core 6.0 kullandım.
-Proje boyunca SOLİD prensiplerine sadık kalmaya çalıştım ve  çok katmanlı mimariyi benimseyerek, katmanları sorumluluklarına göre ayrıştırdım. Bu sayede daha temiz ve düzenli olmasını sağladı.
-Veritabanı yönetimi için Microsoft Sql Server (MSSQL) kullandım. Veritabanı işlemlerini yönetmek için Entity Framework’ün Code First yaklaşımını benimsedim.
-Güvenlik , projedeki en önemli şeylerden biridir. Kullanıcı kimlik doğrulama , yetkilendirme ve rolleme işlemlerini Asp Net Core İdentity ile sağladım.
-Tasarım da HTML, CSS, JavaScript kullandım. Ayrıca etkisiz ve hatalı sayfalarda 403,404 gibi durum kodlarına karşılık gelen sayfalar oluşturdum.
-Formlar ve girdiler üzerindeki doğrulama işlemleri için Data Annotations kullandım.
-Projemin iletişim bölümünden gelen mesajlara cevap vermek için mail gönderme işlevi ekledim.
-Üç panelimize de Dashboard alanı ekledim bu sayede istatistikleri görebiliyoruz.





## Kullanıcı Paneli: Kullanıcı Paneli 5 bölümden oluşmaktadır; Anasayfa, hakkımızda, bölüm koordinatörlerimiz, iletişim, giriş. Panelden birkaç fotoğrafa bakalım.




*Hakkımızda
![image](https://github.com/user-attachments/assets/c4a28d27-a832-4998-a004-c44dbe25d4f3)

*Bölüm koordinatörlerimiz
![image](https://github.com/user-attachments/assets/d3f31902-4ed2-4bcc-a2c9-eac12f2c2de6)

*İletişim
![image](https://github.com/user-attachments/assets/a207cb9e-230d-43db-83f1-3831faecc6d5)

*Giriş Yap
![image](https://github.com/user-attachments/assets/4d2ae5bc-a2e1-4b55-827c-dcfb77a1d80f)





## Bölüm Koordinatörleri Paneli:

*Dashboard
![image](https://github.com/user-attachments/assets/5869c9b1-dca3-4128-9beb-c24a27841526)

*Bildirim: iletişim kısmından atılan mesajlar buraya gelir.
![image](https://github.com/user-attachments/assets/2e012999-16eb-407f-88ce-77df18181cde)

*Kullanıcı İşlemleri
![image](https://github.com/user-attachments/assets/5ac6561d-6d6d-4b08-9fc5-d4961ba7cd45)
![image](https://github.com/user-attachments/assets/86bd967c-5a0b-4df1-af37-563d8dcd8a07)


*Rol İşlemleri

![image](https://github.com/user-attachments/assets/7af724f6-271e-4fb1-b408-a2707e3341ad)

![image](https://github.com/user-attachments/assets/4884ea8a-7015-4378-8e03-39aba1cee0db)

![image](https://github.com/user-attachments/assets/d8435e45-bbf7-444f-8e8c-9c621340b344)

*Ders İşlemleri

![image](https://github.com/user-attachments/assets/4fd74db9-d9cd-4e06-b8bd-c6700ff15a89)

![image](https://github.com/user-attachments/assets/1291e95e-286c-4810-9e26-8f9a63b3c360)

![image](https://github.com/user-attachments/assets/887e7d29-d620-4586-b71c-9e16a7800b03)


*İletişim İşlemleri

![image](https://github.com/user-attachments/assets/bfbdc495-19e5-4b7b-b444-8046e7bcbbd3)

![image](https://github.com/user-attachments/assets/7fc6e843-5d86-4db3-ad5c-0dbb275fd8f5)

![image](https://github.com/user-attachments/assets/02b43ea0-6760-4967-94f6-e3bcb8d3051e)


*Ayarlar İşlemleri
![image](https://github.com/user-attachments/assets/28f5f43e-0b91-4f5a-9238-3fef8a6a93f6)

![image](https://github.com/user-attachments/assets/b8b2836d-93b1-4483-be8c-34581a39350d)


*Çıkış İşlemleri: Bu her panelde vardır
![image](https://github.com/user-attachments/assets/e2455f6e-5041-4460-b022-8ea83ecb2292)







