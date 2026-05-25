# ESP32-CAM Foto Kapan Projesi

Bu proje, **ESP32-CAM** modülü kullanılarak geliştirilmiş, hareket algıladığında otomatik olarak fotoğraf çeken ve bu fotoğrafları [SD Kart/Sunucu] üzerine kaydeden bir "Foto Kapan" (Trail Camera) uygulamasıdır. Doğada yaban hayatını gözlemlemek veya güvenlik amaçlı izleme yapmak için oldukça ekonomik ve işlevsel bir çözümdür.

## 📸 Proje Hakkında
ESP32-CAM’in dahili kamera yeteneklerini ve [örneğin: PIR hareket sensörü] kullanarak, sensör bir hareket algıladığında ESP32-CAM uyanır, yüksek çözünürlüklü bir fotoğraf çeker ve belirlenen hedefe kayıt yapar. 

## 🚀 Özellikler
- **Düşük Güç Tüketimi:** [Derin uyku (Deep Sleep) modu kullanımıyla ilgili bilgi ekleyin].
- **Hızlı Tetikleme:** Hareket algılandığı anda milisaniyeler içerisinde kamera aktivasyonu.
- **Depolama:** Çekilen fotoğrafların SD kart üzerine kaydedilmesi.
- **Kompakt Tasarım:** Küçük boyutları sayesinde her yere kolayca gizlenebilir.

## 🛠 Donanım Gereksinimleri
Projenin çalışması için ihtiyaç duyulan temel bileşenler:
- ESP32-CAM Geliştirme Kartı
- FTDI Programlayıcı (Kod yüklemek için)
- [Örn: HC-SR501 PIR Hareket Sensörü]
- SD Kart Modülü (veya dahili yuvası)
- Güç Kaynağı (Li-po batarya veya Powerbank)
- Jumper kablolar ve breadboard

## 💻 Yazılım Kurulumu
1. **Arduino IDE Hazırlığı:** ESP32 kart kütüphanelerini Arduino IDE'ye eklediğinizden emin olun.
2. **Kütüphaneler:** Kod içerisinde kullanılan gerekli kütüphaneleri (örneğin `esp_camera.h`) kurun.
3. **Yapılandırma:** `Kodlar` klasöründeki dosyalarda yer alan pin tanımlamalarını ve [varsa Wi-Fi/SD kart] ayarlarınızı kendi donanımınıza göre düzenleyin.
4. **Yükleme:** ESP32-CAM kartını FTDI ile bilgisayara bağlayın, doğru kartı ve portu seçerek kodu yükleyin.

## 📂 Dosya Yapısı
- `/Kodlar`: Projenin kaynak kodlarını içerir.
- `Rapor.docx`: Projenin tasarım süreci, devre şemaları ve test sonuçlarını içeren teknik rapor.

## 📝 Teknik Rapor
Projenin detaylı analizini, devre şemalarını ve çalışma prensibini `Rapor.docx` dosyasından inceleyebilirsiniz.

---
