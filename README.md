# Browser Extension UI

Bu proje, tarayıcı eklentileri için modern ve kullanıcı dostu bir arayüz sunmayı amaçlayan bir React tabanlı uygulamadır.

<img width="1901" height="908" alt="image" src="https://github.com/user-attachments/assets/c1706098-91a2-48a3-8f68-fc905a956d46" />

<img width="1890" height="899" alt="image" src="https://github.com/user-attachments/assets/92c0408d-2aae-437f-90f2-60e5a437831a" />


## Özellikler

- Eklenti kartları ile görsel ve sezgisel yönetim
- Aktif/pasif filtreleme
- Karanlık ve aydınlık tema desteği
- Modern ve responsive tasarım
- Kolayca özelleştirilebilir yapı

## Kurulum

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

1. **Depoyu klonlayın:**
   ```bash
   git clone https://github.com/kullanici-adiniz/browser-extension-ui.git
   cd browser-extension-ui
   ```

2. **Bağımlılıkları yükleyin:**
   ```bash
   npm install
   ```

3. **Projeyi başlatın:**
   ```bash
   npm run dev
   ```

4. Tarayıcınızda `http://localhost:5173` adresini ziyaret edin.

## Proje Yapısı

- `src/` : Uygulama kaynak kodları
  - `components/` : React bileşenleri
  - `contexts/` : Context API ile global durum yönetimi
  - `lib/` : Veri ve tip tanımlamaları
  - `assets/` : Görseller ve fontlar
- `public/` : Statik dosyalar
- `index.html` : Giriş noktası
- `vite.config.ts` : Vite yapılandırması
