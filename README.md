# 🚀 Python OOP & GUI Projeleri Portfolyoma Bakış

## 🚗 RentACar - Premium Araç Paylaşım ve Filo Yönetim Sistemi

![1.RentACar Logo](Araç_Kiralama_Sistemi/rentacar.jpg)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green.svg)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey.svg)
![AI](https://img.shields.io/badge/AI-HuggingFace-orange.svg)

Modern, minimalist ve "Apple Store" tasarım estetiğinden ilham alan çizgileriyle geliştirilmiş; yapay zeka destekli güvenlik protokolleri, dinamik harita entegrasyonu ve gelişmiş raporlama modülleri barındıran masaüstü araç paylaşım platformu.


## 📌 Proje Hakkında
RentACar; kurumsal ve bireysel müşterilerin hızlı, güvenli ve esnek bir şekilde araç kiralamasını sağlayan, yöneticilerin ise tüm filoyu, kazanç bilançolarını ve üye veritabanını tek bir merkezden kontrol etmesine imkan tanıyan kapsamlı bir yönetim yazılımıdır. 

Proje, arayüz mimarisinde **PyQt5**, veritabanı yönetiminde **SQLite3** ve iş mantığında **Nesneye Yönelik Programlama (OOP)** prensipleri kullanılarak kararlı bir katmanlı mimari (Layered Architecture) üzerine inşa edilmiştir.

---

## ✨ Öne Çıkan Gelişmiş Özellikler

* **🛡️ Yapay Zeka Destekli 4-Nokta Ehliyet DNA Testi (KYC):** Sisteme sahte, fotokopi veya yabancı ehliyet yüklenmesini engellemek için; sol üst (Mavi TR amblemi), sağ üst (Kırmızı/Pembe şerit), sağ alt (Turkuaz dalgalar) ve merkez piksel yoğunluklarını anlık tarayan patentli görüntü işleme algoritması. HuggingFace CLIP modeli ile desteklenmiştir.
* **🗺️ Dinamik Harita ve Canlı Konum Entegrasyonu:** Leaflet API ve QWebEngineView kullanılarak hazırlanan entegre harita modülü sayesinde araçların harita üzerindeki canlı konumlarını görebilme ve haritadan kiralama yapabilme.
* **📊 Gelişmiş Veri Doğrulama (RegEx) Katmanı:** Form girişlerinde kullanıcı manipülasyonunu sıfıra indirmek adına; isimlerde sayı yasağı, e-postalarda otomatik küçük harfe dönüştürme ve format kontrolü, telefon numaralarında tam 10 hane kısıtlaması, marka/model girişlerinde özel karakter yasağı.
* **📑 Kurumsal Fatura ve PDF Raporlama:** `ReportLab` kütüphanesi kullanılarak her kiralama sonunda kurumsal gider faturası standartlarına uygun, indirilebilir şık PDF faturalar üretme.
* **📉 İstatistiksel Grafik Panelleri:** Yöneticiler için `QtChart` ve `matplotlib` altyapısı kullanılarak hazırlanan dinamik kazanç, popüler araç ve aktif kiralama grafik analitiği.

---

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

Projenin tam performansla çalışabilmesi için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

```bash
# 1. Temel Arayüz ve Grafik Bileşenleri
pip install PyQt5 PyQtWebEngine PyQtChart

# 2. Görüntü İşleme, Renk Profilleme ve Yapay Zeka Altyapısı
pip install Pillow transformers torch

# 3. PDF Fatura ve Coğrafi Konum Kütüphaneleri
pip install reportlab geocoder matplotlib
```

### 1. [🚗 RentACar - Ekran Görüntüleri](./README2.md)


# 💪 FitTrack Pro - Premium Fitness ve Sağlık Takip Sistemi

![2.Fit Logo](Fitness_Takip_Sistemi/logo.png)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green.svg)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Analytics-blueviolet.svg)

"Apple Health" tasarım estetiğinden ve minimalist çizgilerden ilham alınarak geliştirilmiş; dinamik metabolik hesaplama motorları, interaktif gelişim grafikleri ve akıllı antrenör-sporcu entegrasyonu barındıran masaüstü sağlık ve aktivite takip platformu.

---

## 📌 Proje Hakkında
FitTrack Pro; sporcuların günlük antrenman loglarını tutmasını, vücut kitle endekslerini (BMI) anlık izlemesini ve haftalık performanslarını analiz etmesini sağlayan; antrenörlerin ise kendisini seçen öğrencilere özel takvim üzerinden dinamik programlar hazırlayabildiği kapsamlı bir sağlık yazılımıdır. 

Proje, arayüz mimarisinde **PyQt5**, veritabanı yönetiminde **SQLite3** ve veri analitiğinde **Matplotlib** kullanılarak kararlı bir mimari üzerine inşa edilmiştir.

---

## 🎓 Akademik Mimari ve OOP Prensipleri
Bu proje, iş mantığının arayüzden ayrıştırıldığı Katmanlı Mimari (Layered Architecture) kullanılarak geliştirilmiştir. Arka planda çalışan saf Python OOP sınıfları:

* **`Sporcu` Sınıfı:** Üyenin boy, kilo, hedef ve BMI (Vücut Kitle Endeksi) hesaplamalarını yöneten, ilerleme verilerini veritabanına işleyen ana model.
* **`Antrenman` Sınıfı:** Seçilen egzersizin türüne göre saatlik kalori harcama matrisini tutan ve seans özetlerini üreten model.
* **`Takip` Sınıfı:** Listeler (Lists) ve Sözlükler (Dictionaries) kullanarak kullanıcının son 7 günlük aktivite geçmişini derleyen ve UI katmanındaki grafiklere veri sağlayan analitik sınıfı.

---

## ✨ Öne Çıkan Gelişmiş Özellikler

* **🍏 Apple Health Estetiğinde Modern UI:** Tamamen bembeyaz, yuvarlak hatlı ve gölgeli (Glassmorphism) Apple kart tasarımları, animasyonlu sanal Memoji seçicisi ve `AppleMesajDialog` adında özel tasarlanmış pürüzsüz uyarı pencereleri.
* **🔥 MET Katsayılı Akıllı Kalori Motoru:** Sadece süreye dayalı basit ve yanıltıcı hesaplamalar yerine; 40'tan fazla egzersizin evrensel MET (Metabolic Equivalent of Task) değerini, sporcunun anlık güncel kilosunu ve aktivite süresini denkleme katarak bilimsel kalori tahmini yapan algoritma.
* **📈 İnaktif Canlı Gelişim Grafikleri:** `matplotlib.backends.backend_qt5agg` altyapısı kullanılarak hazırlanan, arka planı şeffaf ve cam tasarımla uyumlu entegre bar grafik paneli. Son 7 günün aktivite yoğunluğunu anlık olarak arayüze çizer.
* **🤝 Çift Katmanlı Antrenör & Sporcu Entegrasyonu:** Sporcuların sistemdeki onaylı uzmanlardan kendilerine antrenör seçebildiği, antrenörlerin ise yaka kartı formatındaki "Öğrencilerim" listesinden ilgili sporcuya tıklayarak geçmişe dönük kilitli, geleceğe dönük açık akıllı takvim programı yazabildiği ekosistem.
* **📊 Gelişmiş Veri Doğrulama (RegEx):** E-posta kutularında otomatik küçük harfe dönüştürme, isim alanlarında sayısal karakter yasağı ve Admin başvuru ekranında tam 11 haneli TC Kimlik kısıtlaması.

---

## 🛠️ Sistem Gereksinimleri ve Kütüphaneler

Projenin tam performansla (özellikle grafiklerin çizilmesi için) çalışabilmesi için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

```bash
# 1. Temel Arayüz Bileşenleri
pip install PyQt5

# 2. Veri Analitiği ve Grafik Çizim Altyapısı
pip install matplotlib
```

### 2. 💪 FitTrack Pro - Ekran Görüntüleri](./README2.md)
