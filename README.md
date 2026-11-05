# 3D İnteraktif Stadyum Projesi (Cloudflare Pages)

## 📁 Dosya Yapısı
- `index.html`: Three.js tabanlı 3D Stadyum web arayüzü.
- `takipciler.json`: Stadyumda oturan taraftarların isim listesi.
- `veri/guncelle.py`: Koltuklardaki isimleri güncelleyen Python otomasyon betiği.

## 🚀 Cloudflare Pages Yayınlama Adımları
1. Bu klasördeki tüm dosyaları GitHub hesabınızda yeni bir depoya (Repository) yükleyin (Push edin).
2. [Cloudflare Dashboard](https://dash.cloudflare.com/) hesabınıza girin.
3. **Workers & Pages** -> **Create Application** -> **Pages** sekmesini seçin.
4. **Connect to Git** butonuna basarak GitHub deponuzu seçin.
5. Derleme Ayarları (Build settings):
   - **Framework preset:** `None`
   - **Build command:** (Boş bırakın)
   - **Build output directory:** `/`
6. **Save and Deploy** butonuna tıklayın.

Artık siteniz canlı ortamda `takipciler.json` verisi ile çalışacaktır!
