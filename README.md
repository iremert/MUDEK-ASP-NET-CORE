# MHRS-ASP-NET-CORE


## Projemin Amacı ve Tanıtımı
- Müdek (Mühendislik Eğitim Programları Değerlendirme ve Akreditasyon Derneği) web sitemin amacı ,tüm paydaşların etkin bir şekilde etkileşimde bulunabileceği bir platform sunmaktır. 
- Bu site, mühendislik fakültelerinin eğitim programlarının ulusal ve uluslararası standartlara uygunluğunu değerlendirmek, sürekli iyileştirme süreçlerini desteklemek ve akreditasyon süreçlerini yönetmek üzere tasarlanmıştır. Müdek’in misyonu , mühendislik eğitiminin kalitesini arttırmak, öğrencilerin, mezunların ve toplumun beklentilerini karşılamaktır.
- Web sitemde dört ana panel vardır; Kullanıcı paneli, Bölüm koordinatörü, Öğretim Görevlisi, Müdek Denetçisi.
- Bu panellerin her biri , kullanıcıların rolleri ve ihtiyaçlarına göre özelleştirilmiş işlevler sunarak, değerlendirme ve akreditasyon süreçlerini daha verimli hale getirir.






## Projemde Kullanılan Teknolojiler
- Projemi geliştirirken  C# dilini , web tarafında çatı olarak Asp Net Core 6.0 kullandım.
- Proje boyunca SOLİD prensiplerine sadık kalmaya çalıştım ve  çok katmanlı mimariyi benimseyerek, katmanları sorumluluklarına göre ayrıştırdım. Bu sayede daha temiz ve düzenli olmasını sağladı.
- Veritabanı yönetimi için Microsoft Sql Server (MSSQL) kullandım. Veritabanı işlemlerini yönetmek için Entity Framework’ün Code First yaklaşımını benimsedim.
- Güvenlik , projedeki en önemli şeylerden biridir. Kullanıcı kimlik doğrulama , yetkilendirme ve rolleme işlemlerini Asp Net Core İdentity ile sağladım.
- Tasarım da HTML, CSS, JavaScript kullandım. Ayrıca etkisiz ve hatalı sayfalarda 403,404 gibi durum kodlarına karşılık gelen sayfalar oluşturdum.
- Formlar ve girdiler üzerindeki doğrulama işlemleri için Data Annotations kullandım.
- Projemin iletişim bölümünden gelen mesajlara cevap vermek için mail gönderme işlevi ekledim.
- Üç panelimize de Dashboard alanı ekledim bu sayede istatistikleri görebiliyoruz.





### Kullanıcı Paneli: Kullanıcı Paneli 5 bölümden oluşmaktadır; Anasayfa, hakkımızda, bölüm koordinatörlerimiz, iletişim, giriş. Panelden birkaç fotoğrafa bakalım.




1) Hakkımızda
![image](https://github.com/user-attachments/assets/c4a28d27-a832-4998-a004-c44dbe25d4f3)

2) Bölüm koordinatörlerimiz
![image](https://github.com/user-attachments/assets/d3f31902-4ed2-4bcc-a2c9-eac12f2c2de6)

3) İletişim
![image](https://github.com/user-attachments/assets/a9def14a-5110-4903-a424-2bbc966c70d9)

4) Giriş Yap
![image](https://github.com/user-attachments/assets/4d2ae5bc-a2e1-4b55-827c-dcfb77a1d80f)





### Bölüm Koordinatörleri Paneli:

1) Dashboard
![image](https://github.com/user-attachments/assets/5869c9b1-dca3-4128-9beb-c24a27841526)

2) Bildirim: iletişim kısmından atılan mesajlar buraya gelir.
![image](https://github.com/user-attachments/assets/2e012999-16eb-407f-88ce-77df18181cde)

3) Kullanıcı İşlemleri
![image](https://github.com/user-attachments/assets/5ac6561d-6d6d-4b08-9fc5-d4961ba7cd45)
![image](https://github.com/user-attachments/assets/86bd967c-5a0b-4df1-af37-563d8dcd8a07)


4) Rol İşlemleri

![image](https://github.com/user-attachments/assets/7af724f6-271e-4fb1-b408-a2707e3341ad)


![image](https://github.com/user-attachments/assets/4884ea8a-7015-4378-8e03-39aba1cee0db)


![image](https://github.com/user-attachments/assets/d8435e45-bbf7-444f-8e8c-9c621340b344)

5) Ders İşlemleri

![image](https://github.com/user-attachments/assets/4fd74db9-d9cd-4e06-b8bd-c6700ff15a89)

![image](https://github.com/user-attachments/assets/1291e95e-286c-4810-9e26-8f9a63b3c360)

![image](https://github.com/user-attachments/assets/887e7d29-d620-4586-b71c-9e16a7800b03)


6) İletişim İşlemleri

![image](https://github.com/user-attachments/assets/bfbdc495-19e5-4b7b-b444-8046e7bcbbd3)

![image](https://github.com/user-attachments/assets/7fc6e843-5d86-4db3-ad5c-0dbb275fd8f5)

![image](https://github.com/user-attachments/assets/02b43ea0-6760-4967-94f6-e3bcb8d3051e)


7) Ayarlar İşlemleri

![image](https://github.com/user-attachments/assets/28f5f43e-0b91-4f5a-9238-3fef8a6a93f6)

![image](https://github.com/user-attachments/assets/b8b2836d-93b1-4483-be8c-34581a39350d)


8) Çıkış İşlemleri: Bu her panelde vardır
![image](https://github.com/user-attachments/assets/e2455f6e-5041-4460-b022-8ea83ecb2292)






### Öğretim Görevlisi Paneli

1) Dashboard:

![image](https://github.com/user-attachments/assets/29f746c5-7ae8-434e-88c4-458964429d4d)

2) Kullanıcı adı ve görseli:
![image](https://github.com/user-attachments/assets/7aee21ff-e843-48ba-b630-e530080dd031)

3) Döküman İşlemleri:
![image](https://github.com/user-attachments/assets/e4c028d9-6c61-4bba-a6b5-82ca2c3e6e37)

![image](https://github.com/user-attachments/assets/ea865717-7e08-4f15-b5ab-8cc289660098)

4) Tablo İşlemleri

![image](https://github.com/user-attachments/assets/ad59a85b-8e2c-4a9e-917c-76ef531f0de6)

![image](https://github.com/user-attachments/assets/112ba3aa-edc9-49ad-8dbe-ba6def2f3010)

![image](https://github.com/user-attachments/assets/2df7bbdb-069d-446e-83bd-3c7ee375cbc8)

![image](https://github.com/user-attachments/assets/d4273724-5276-47c2-98d5-0e5a23f923d6)

5) Değerlendirme Ölçütleri İşlemleri

![image](https://github.com/user-attachments/assets/eb304772-9aa1-49f5-b882-cd8d430ce032)

![image](https://github.com/user-attachments/assets/9aaeab69-c068-4c30-a961-d5f995bebe53)

![image](https://github.com/user-attachments/assets/c1761860-3f51-4db5-8d76-af49fcc29a72)

6) Öğrenci İşlemleri

   ![image](https://github.com/user-attachments/assets/5e024994-eb6b-4bef-ba20-da04d7bc228c)

   ![image](https://github.com/user-attachments/assets/29dc7cef-8258-4d8f-b90b-ba3ad645cbaa)

7) Öğrenci Not Hesaplama

![image](https://github.com/user-attachments/assets/15478ad5-4b87-4e0a-aad6-3c969945dec2)

![image](https://github.com/user-attachments/assets/e12ef865-d9a1-4a93-9d2d-9171e0343bac)

8) Ayarlar İşlemleri

   ![image](https://github.com/user-attachments/assets/50dcacbc-eb98-4135-91c2-5d3feed65ca3)

   ![image](https://github.com/user-attachments/assets/f912aa20-93a8-4850-9df9-c0296663fc62)


### Müdek Denetçisi Paneli

1) Dashboard
   ![image](https://github.com/user-attachments/assets/0ef7a3bb-07f0-4d24-ab7b-beb4e04e5d50)

2) Sidebar
   ![image](https://github.com/user-attachments/assets/e70a56d1-5943-4103-9880-1420071f8a5f)

3) Öğretim Görevlisi İşlemleri

   ![image](https://github.com/user-attachments/assets/25758dd8-5e9a-43de-8862-baa80c5926af)

4) Ders Listesi

  ![image](https://github.com/user-attachments/assets/ea8bbf7d-1404-49ab-9948-8dc9d594fc2f)

5) Öğretim Görevlisi İşlemleri

   ![image](https://github.com/user-attachments/assets/5fd003c7-2cc7-4a0a-8f20-e232fb277dd4)

   ![image](https://github.com/user-attachments/assets/a55c451a-3afc-4302-81bc-96a666b998a1)

   ![image](https://github.com/user-attachments/assets/2841036e-69b1-4fcd-8f7c-f2d838f0d4c5)

6) Değerlendirme Ölçütleri Listesi

     ![image](https://github.com/user-attachments/assets/1f5e157c-e371-4de8-8363-2abcd93d7dd0)

7) Ayarlar İşlemleri

   ![image](https://github.com/user-attachments/assets/57ffefe9-30cf-48f4-ac30-509bde488c6e)


#### Error sayfası

![image](https://github.com/user-attachments/assets/ec23e019-f77f-4267-897d-d83355642751)
