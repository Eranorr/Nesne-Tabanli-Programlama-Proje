# 🚀 Python OOP & GUI Projeleri Portfolyom

## 🚗 RentACar - Premium Araç Paylaşım ve Filo Yönetim Sistemi

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

### 1. [🚗 RentACar - Araç Paylaşım Sistemi](./README2.md)
