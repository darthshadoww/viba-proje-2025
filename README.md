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
  - `viba-20242-proje-GRUPNO.zip`  
  - `viba-20242-rapor-GRUPNO.pdf`  
  - `viba-20242-GRUPNO.txt` (`.exe` uzantılı dosyanın adı değiştirilerek)

---


## 💡 Katkıda Bulunacaklar İçin Notlar

- 🔀 **Branch kullanımı zorunlu:** Herkes kendi görevine özel bir branch’te çalışmalı. `main` doğrudan değiştirilmemeli.
- 📥 **Pull Request kullanın:** İşiniz bittiğinde doğrudan main’e atmak yerine PR açarak kodu birleştirin.
- 📝 **Açıklayıcı commit mesajları yazın:** Örn: `Add CRC calculation`, `Fix GUI layout bug`
- 🔄 **Push yapmadan önce güncelleyin:** `git pull origin main` ile en güncel hali alın.
- 💡 **Kod okunabilirliğine dikkat edin:** Girintiler, boşluklar ve yorum satırları düzenli olmalı.
- 🚫 **Derlenmiş dosyaları commit etmeyin:** `.exe`, `.obj`, `cmake-build-debug/` gibi klasörler `.gitignore` ile dışlanmalı.
- 📌 **Her dosyaya kısa bir açıklama ekleyin:** Ne yaptığını anlatan 1-2 satırlık yorum.
- 🧾 **Rapor için kendi kısmınızın kısa özetini hazır tutun.**

Bu kurallar sayesinde ekip olarak daha düzenli ve sorunsuz bir geliştirme süreci geçirebiliriz.
