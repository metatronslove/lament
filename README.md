# 🔷 Lament Configuration - Hellraiser Puzzle Box 3D Viewer

![Hellraiser Puzzle Box](docs/social-preview.jpg)

Bu proje, **Hellraiser** film serisindeki ikonik **Lament Configuration** (Lemarş Konfigürasyonu) kutusunun interaktif 3D görüntüleyicisini sunar. 
[metatronslove](https://github.com/metatronslove/lament) tarafından oluşturulan orijinal 3D baskı modellerini temel alır ve [ViewSTL Javascript Plugin](https://www.viewstl.com/plugin/) ile web üzerinde çalışacak şekilde uyarlanmıştır.

## ✨ Özellikler

- **6 Farklı Model**: Pozitif/Negatif kabartmalı çeşitli versiyonlar
- **Tam İnteraktif Kontrol**: Döndürme, yakınlaştırma, sürükleme
- **Çoklu Görünüm Modu**: Düz, yumuşak gölgeli, tel kafes
- **Renk Değiştirme**: İstediğiniz renkte inceleyin
- **Otomatik Döndürme**: Her açıdan görmek için
- **Izgara Gösterimi**: Referans için
- **Mobil Uyumlu**: Dokunmatik ekranlarda sorunsuz çalışır

## 🚀 Canlı Demo

Projeyi hemen inceleyin:  
[https://kullaniciadi.github.io/lament/docs/](https://kullaniciadi.github.io/lament/docs/)

*(Yukarıdaki bağlantıyı kendi GitHub kullanıcı adınızla değiştirin)*

## 📁 Dosya Yapısı

```
lament/
├── docs/                      # GitHub Pages ana klasörü
│   ├── index.html             # Ana 3D görüntüleyici
│   ├── social-preview.jpg     # Open Graph paylaşım resmi
│   ├── models/                # STL dosyaları
│   │   ├── Lament_Configuration_Cube-3x3x3P.stl
│   │   ├── Lament_Configuration_Cube-3x3x3N.stl
│   │   ├── Lament_Configuration_3x3x3_Positive.stl
│   │   ├── Lament_Configuration_3x3x3_Negative.stl
│   │   ├── Lament_Configuration_3x3x3_Positive_A.stl
│   │   └── Lament_Configuration_3x3x3_Positive_B.stl
│   └── js/                     # ViewSTL ve Three.js kütüphaneleri
│       ├── three.min.js
│       ├── stl_viewer.min.js
│       ├── OrbitControls.js
│       ├── TrackballControls.js
│       ├── Projector.js
│       ├── CanvasRenderer.js
│       └── webgl_detector.js
└── README.md                   # Bu dosya
```

## 🛠️ Kullanım

1. **Depoyu klonlayın:**
   ```bash
   git clone https://github.com/kullaniciadi/lament.git
   cd lament
   ```

2. **Kendi resminizi ekleyin:**  
   `docs/social-preview.jpg` dosyasını kendi görselinizle değiştirin (1200x630 piksel önerilir).

3. **GitHub Pages'i etkinleştirin:**  
   Repo ayarlarından `docs/` klasörünü GitHub Pages kaynağı olarak seçin.

4. **Canlı yayına alın:**  
   Artık `https://kullaniciadi.github.io/lament/docs/` adresinde yayında!

## 🙏 Teşekkür ve Kaynaklar

Bu proje aşağıdaki harika açık kaynak çalışmalar olmasaydı mümkün olmazdı:

- **[metatronslove/lament](https://github.com/metatronslove/lament)** - Orijinal Lament Configuration 3D baskı modelleri (Simon Sayce'ın orijinal film tasarımına dayanır)
- **[ViewSTL Javascript Plugin](https://www.viewstl.com/plugin/)** - Three.js tabanlı mükemmel STL görüntüleyici
- **[Three.js](https://threejs.org/)** - 3D kütüphane

### Orijinal Tasarım
The Lament Configuration'ın orijinal tasarımı, ilk Hellraiser filmi için **Simon Sayce** tarafından yapılmıştır. Bu proje, sinema tarihinin bu ikonik objesini dijital ortamda yaşatmayı amaçlar.

## ☕ Destek Olun

Eğer bu projeyi beğendiyseniz ve **metatronslove**'ın orijinal 3D modelleme çalışmalarını desteklemek isterseniz:

[![Buy Me A Coffee](https://img.buymeacoffee.com/button-api/?text=Model%20Yaratıcısına%20Kahve%20Ismarla&emoji=☕&slug=metatronslove&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff)](https://buymeacoffee.com/metatronslove)

Ayrıca ViewSTL gibi harika araçlar geliştiren ekiplere de destek olmayı unutmayın!

## 📜 Lisans

- Kod (HTML/JS) kısmı: MIT License
- 3D Modeller: Orijinal repo sahibinin ([metatronslove](https://github.com/metatronslove/lament)) belirttiği lisans geçerlidir
- ViewSTL Plugin: MIT License

---

*"We have such sights to show you."*  
🔷 *Hellraiser hayranları için hazırlanmıştır, kar amacı gütmez.*
