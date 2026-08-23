# 🚀 TaskFlow - Modern React & Tailwind Görev ve Proje Yönetim Uygulaması

Bu proje, modern web geliştirme standartlarına uygun olarak **React.js**, **Tailwind CSS** ve **LocalStorage** kullanılarak geliştirilmiş kapsamlı bir frontend uygulamasıdır.

---

## 📌 Proje Özellikleri ve Yönerge Uyumluluğu

* ✅ **Modern Kütüphane:** React (Vite altyapısı ile ultra hızlı çalışma)
* ✅ **Modern CSS Mimarisi:** Tailwind CSS ile responsive, modern koyu tema tasarımı
* ✅ **Klasör Yapısı:** `src/components`, `src/pages`, `src/interfaces`, `src/context` şeklinde modüler dizilim
* ✅ **Tam CRUD Desteği:**
  * **Ekle (Create):** Modal penceresi üzerinden başlık, açıklama, sorumlu, kategori ve öncelik ile görev oluşturma
  * **Listele (Read):** Dinamik filtreleme, arama ve durum gruplama ile listeleme
  * **Güncelle (Update):** Görev detaylarını düzenleme ve anlık durum değiştirme (Beklemede / Devam Ediyor / Tamamlandı)
  * **Sil (Delete):** Güvenlik onay mekanizmalı silme işlemi
* ✅ **Kalıcı Veri (LocalStorage):** Sayfa yenilense bile tüm veriler tarayıcı hafızasında saklanır.
* ✅ **Netlify / Vercel Deploy Desteği:** `netlify.toml` ve `public/_redirects` dosyaları hazır olarak yapılandırılmıştır.

---

## 🛠️ Kurulum ve Yerel Çalıştırma

Projeyi bilgisayarınızda çalıştırmak için aşağıdaki adımları uygulayın:

1. **Bağımlılıkları Yükleyin:**
   ```bash
   npm install
   ```

2. **Geliştirme Sunucusunu Başlatın:**
   ```bash
   npm run dev
   ```

3. Tarayıcınızda açın:
   `http://localhost:5173`

---

## 🌐 Netlify Üzerinde Yayına Alma (Deploy) Rehberi

1. Projeyi bir GitHub deposuna (Public Repository) push edin.
2. [Netlify](https://www.netlify.com)'ye giriş yapıp **"Add new site" > "Import an existing project"** seçeneğine tıklayın.
3. GitHub deponuzu seçin:
   - **Build Command:** `npm run build`
   - **Publish Directory:** `dist`
4. **Deploy Site** butonuna tıklayın. Birkaç saniye içinde canlı URL adresiniz hazır olacaktır!

---

## 📂 Dosya ve Dizin Ağacı

```text
react-taskflow-app/
├── index.html
├── netlify.toml
├── package.json
├── tailwind.config.js
├── vite.config.js
├── public/
│   └── _redirects
└── src/
    ├── App.jsx
    ├── index.css
    ├── main.jsx
    ├── components/
    │   ├── FilterBar.jsx
    │   ├── Navbar.jsx
    │   ├── StatsOverview.jsx
    │   ├── TaskCard.jsx
    │   └── TaskModal.jsx
    ├── context/
    │   └── TaskContext.jsx
    ├── interfaces/
    │   └── taskInterface.js
    └── pages/
        └── Dashboard.jsx
```
