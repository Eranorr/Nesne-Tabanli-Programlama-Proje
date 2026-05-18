# 🚀 RentACar Araç Paylaşım Sistemi Genel Bakış

1. Giriş ve Hesap Oluşturma Ekranları
Kullanıcıların güvenli giriş yaptığı ve RegEx kısıtlamalı (E-posta doğrulama, otomatik küçük harfe çevirme, telefon hane kontrolü) kayıt modülü.

![1. Giriş Yap Ekranı](ekran_goruntuleri/01_login_screen.png)
![2. Kayıt Ol Modülü ve Veri Doğrulama](ekran_goruntuleri/02_register_screen.png)

2. Müşteri Ana Sayfası ve Araç Seçim Ekranı
"Apple Store" sadeliğinde tasarlanmış, mevcut müsait araçların listelendiği şık Dashboard.

![3. Müşteri Ana Sayfası (Dashboard)](ekran_goruntuleri/03_customer_dashboard.png)

3. Canlı Harita Modülü
Araçların gerçek konumlarının Leaflet API ve OpenStreetMap yardımıyla QWebEngineView üzerinde gösterildiği ve haritadan doğrudan kiralama tetiklenen ekran.

![4. Canlı Harita ve Konum Seçimi](ekran_goruntuleri/04_live_map.png)

4. Ehliyet Yükleme ve Yapay Zeka Doğrulama Ekranı (KYC)
4-Nokta DNA renk taraması algoritmasının sahte ve yabancı belgeleri yakaladığı, kriz kontrol ekranı.

![5. Yapay Zeka / Simülasyon Ehliyet Doğrulama Ekranı](ekran_goruntuleri/05_kyc_verification.png)

5. Aktif Kiralama, Ödeme ve Geçmiş İşlemler Ekranı
Sanal kart arayüzü barındıran ödeme ekranı ve tamamlanan işlemler sonrası PDF fatura üretim modülü.

![6. Sanal Kart Ödeme ve Kiralama Onay Ekranı](ekran_goruntuleri/06_payment_screen.png)
![7. Geçmiş Kiralamalar](ekran_goruntuleri/07_rental_history.png)
![7-2. PDF FaturaSekmesi](ekran_goruntuleri/07-2_fatura.png)

6. Admin Paneli - Müşteri Yönetimi ve Kullanıcı Silme Ekranı
Sistem yöneticisinin üyeleri izlediği ve yüksek güvenlikli yönetim sekmesi.

![8. Admin Paneli - Müşteri Yönetimi ve Güvenli Silme](ekran_goruntuleri/08_admin_customers.png)

7. Admin Paneli - Araç Filosu Yönetimi
Marka ve model hanelerine özel karakter girilmesini engelleyen RegEx mimarili araç ekleme, çıkarma ve fiyat güncelleme ekranı.

![9. Admin Paneli - Araç Ekleme ve Düzenleme Ekranı](ekran_goruntuleri/09_admin_fleet.png)

8. Admin Paneli - Finansal Analitik ve Grafikler
Şirketin toplam kazanç, popüler araç ve kiralama istatistiklerini grafiksel olarak gösteren analiz paneli.

![10. Admin Paneli - Grafik Raporlama ve Analitik](ekran_goruntuleri/10_admin_analytics.png)
