# 🍳 Web Resep Interaktif (HTML + JS)

[![Demo](https://img.shields.io/badge/Demo-Online-brightgreen)](https://resep.nguprus.my.id)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)
![License](https://img.shields.io/badge/License-Free-success)

🌐 **Live Demo:**  
👉 https://resep.nguprus.my.id

---

## ✨ Tentang Project

Website resep masakan berbasis **HTML + CSS + JavaScript murni (tanpa framework)**.  
Dirancang seperti **aplikasi mobile fullscreen** dengan tema **Merah – Kuning**.

Cocok untuk:
- Buku resep pribadi
- Usaha kuliner / UMKM
- Dapur produksi
- Konversi APK (WebView / PWA)

---

## 📸 Screenshot

![Home](assets/home.png)
![Resep](assets/resep.png)

---

## 🚀 Fitur Utama

- ✅ Fullscreen mobile UI (app style)
- ✅ Sidebar menu (☰)
- ✅ Tombol Home
- ✅ Edit bahan proporsional otomatis
- ✅ Reset resep
- ✅ Cetak resep
- ✅ Search + kategori
- ✅ Pagination
- ✅ Tema merah–kuning konsisten
- ✅ Font custom **More Sugar**
- ✅ Tanpa database / backend
- ✅ Siap GitHub Pages

---

## 📂 Struktur Folder

```
/
│
├── index.html                  # halaman utama (menu resep)
├── resep-*.html                # halaman tiap resep
│
├── /data
│   ├── menu-data.js            # data sidebar menu
│   └── resep-data.js           # daftar resep halaman depan
│
├── /fonts
│   └── MoreSugar.ttf
│
├── /assets                    # screenshot (opsional)
│
└── README.md
```

---

## 🧭 Penjelasan File

### index.html
Halaman utama:
- daftar semua resep
- pencarian
- kategori
- pagination
- sidebar

Data diambil dari:

```
/data/resep-data.js
```

---

### /data/menu-data.js
Mengatur isi sidebar (☰)

Contoh:

```javascript
const menuItems = [
  { label:"Tentang", icon:"fa-circle-info", link:"#"},
  { label:"WhatsApp", icon:"fa-brands fa-whatsapp", link:"https://wa.me/628xxxx" }
];
```

Tambah menu cukup edit file ini saja.

---

### /data/resep-data.js
Mengatur daftar resep di halaman utama

Format:

```javascript
"Nama Resep": "file.html | kategori1,kategori2"
```

Contoh:

```javascript
"Creamy Mushroom": "resep-creamy-mushroom.html | creamy,saus"
```

---

## ✏️ Cara Menambah Resep Baru

### 1. Buat file HTML baru
Contoh:

```
resep-sambal.html
```

### 2. Tambahkan di `/data/resep-data.js`

```javascript
"Sambal Pedas": "resep-sambal.html | sambal,pedas"
```

Selesai 🎉  
Resep otomatis muncul di halaman utama.

---

## ✏️ Cara Edit Sidebar Menu

Edit:

```
/data/menu-data.js
```

Tambah:

```javascript
{
  label:"Instagram",
  icon:"fa-brands fa-instagram",
  link:"https://instagram.com/akunmu"
}
```

Tidak perlu ubah halaman lain.

---

## ⚙️ Teknologi

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome

Semua file **statis (HTML + JS saja)**  
Tidak perlu backend.

---

## ▶️ Menjalankan Project

Langsung buka:

```
index.html
```

atau upload ke:

- GitHub Pages
- Netlify
- Vercel
- Hosting statis lainnya

---

## 🎨 Warna Tema

```
Merah  : #d62828
Kuning : #ffd60a
```

---

## 👨‍🍳 Catatan

- Klik **Edit** → ubah takaran → semua bahan otomatis proporsional  
- **Reset** → kembali ke awal  
- **Cetak** → mode print bersih  

---

⭐ Jika project ini membantu, jangan lupa beri **Star** di GitHub!
