# Online Satranç Oyunu

Gerçek oyuncularla online satranç oynayabileceğiniz web uygulaması.

## Özellikler

- ⚡ Gerçek zamanlı multiplayer
- 🎯 Otomatik oyuncu eşleştirme
- 🏰 Tam satranç tahtası ve taşları
- 📱 Mobil uyumlu tasarım
- 🔄 Anlık hamle senkronizasyonu

## Kurulum

### Yerel Geliştirme

```bash
# Bağımlılıkları yükle
npm install

# Sunucuyu başlat
npm run dev
```

Tarayıcınızda `http://localhost:3001` adresine gidin.

### Vercel + Render Deployment

#### Backend (Render)

1. Bu projeyi GitHub'a yükleyin
2. Render.com'da yeni Web Service oluşturun
3. GitHub repo'nuzu bağlayın
4. Ayarlar:
   - Build Command: `npm install`
   - Start Command: `npm start`
   - Environment: `Node`

#### Frontend (Vercel)

1. Vercel'de yeni proje oluşturun
2. Environment Variables ekleyin:
   ```
   NEXT_PUBLIC_SERVER_URL=https://your-render-app.onrender.com
   ```

## Teknolojiler

- **Backend**: Node.js, Express, Socket.io
- **Frontend**: HTML5, CSS3, JavaScript
- **Deployment**: Render (backend), Vercel (frontend)

## Oyun Kuralları

- Standart satranç kuralları geçerlidir
- Beyaz taşlar ilk hamleyi yapar
- Sıra tabanlı oyun sistemi
- Rakip ayrılırsa oyun sona erer

## Geliştirme Notları

- Socket.io ile gerçek zamanlı iletişim
- Basit hamle doğrulama sistemi
- Responsive tasarım
- CORS ayarları yapılandırılmış

## Lisans

MIT