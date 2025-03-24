# VİBA 2024-2025 Bahar Dönemi Proje Ödevi

**Ders Kodu:** BLM3051  
**Ders Adı:** Veri İletişimi ve Bilgisayar Ağları  
**Proje Konusu:** Data Link Layer Simülasyonu (CRC, Checksum, Stop&Wait)  
**Programlama Dili:** C++  
**Arayüz:** GUI (framework serbest)

---

## 🔍 Proje Hakkında

Bu projede OSI modelinin 2. katmanı olan **Veri Bağlantı Katmanı (Data Link Layer)** baz alınarak, bir .dat dosyasının frame'lere bölünmesi, CRC kodlarının hesaplanması ve Stop&Wait protokolü ile simüle edilmiş veri iletimi gerçekleştirilmiştir.

---

## ⚙️ Uygulama Özellikleri

- .dat uzantılı dosya seçimi ve dizin gezme  
- Verilerin 100-bit’lik frame’lere bölünmesi  
- 16. dereceden CRC polinomu ile hata kontrolü  
- CRC kodlarının GUI üzerinde gösterimi  
- Checksum hesaplama ve hexadecimal formatta sunumu  
- Stop&Wait protokolü ile veri iletimi  
  - %10 veri kaybı  
  - %20 veri bozulması  
  - %15 ACK kaybı  
  - %5 checksum hatası  
- Tüm sürecin kullanıcı arayüzüyle görselleştirilmesi

---

## 🧩 Klasör Yapısı

```
viba-20242-proje/
├── src/              # C++ kaynak dosyaları
├── gui/              # GUI ile ilgili dosyalar
├── data/             # .dat örnek dosyalar
├── docs/             # Rapor, teslim dökümanları
├── README.md
└── .gitignore
```

---

## 👥 Proje Ekibi (İş Bölümü - 3 Kategori)

| Görev Kategorisi                     | Açıklama                                                                 |
|--------------------------------------|--------------------------------------------------------------------------|
| Veri İşleme & İletim                 | Dosya seçimi, frame bölme, CRC, checksum, Stop&Wait simülasyonu          |
| GUI Tasarımı & Entegrasyon          | Arayüz tasarımı ve veri iletim sürecinin görselleştirilmesi               |
| Raporlama & Teslim Dosyaları        | Proje raporu, teslim dosyalarının hazırlanması ve format kontrolü         |

---

## 🚀 Derleme & Çalıştırma

Gerekli C++ derleyicisi ve GUI framework kurulumu sonrası:

```bash
g++ src/main.cpp -o viba_app
./viba_app
```

> Kullandığınız GUI kütüphanesini belirtmeyi unutmayın.

---

## 📅 Teslim Bilgisi

- **Son Teslim Tarihi:** 20 Nisan 2025, 23:59 (TSİ)  
- **Teslim Formatı:**  
  - `viba-2025-proje-GRUPNO.zip`  
  - `viba-2025-rapor-GRUPNO.pdf`  
  - `viba-2025-GRUPNO.txt` (`.exe` uzantılı dosyanın adı değiştirilerek)

---
