# 🚀 GalaxiRide — Transportasi Masa Depan

> Aplikasi transportasi online bertema galaksi neon untuk warga Aceh.  
> Dibangun dengan HTML, CSS, dan JavaScript murni — tanpa framework.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white)

---

## 📋 Deskripsi

**GalaxiRide** adalah aplikasi ojek online berbasis web dengan tampilan dark space dan efek neon. Dibuat sebagai single-page application (SPA) menggunakan HTML, CSS, dan vanilla JavaScript. Proyek ini merupakan pengembangan dari *Laju-Nanggroe* dengan desain ulang total dan penambahan beberapa fitur baru.

---

## ✨ Fitur

### Fitur Utama (dari versi sebelumnya)
- **Pemesanan Ride** — input tujuan, estimasi tarif otomatis, dan pilih driver
- **Peta Interaktif** — tracking real-time menggunakan Leaflet.js + OpenStreetMap
- **Chat Driver via WhatsApp** — tombol langsung ke WhatsApp driver
- **Top Up Saldo** — modal top up dengan 4 nominal pilihan
- **Riwayat Perjalanan** — tampilan tabel (desktop) dan kartu (mobile)
- **Halaman Profil** — edit nama, nomor WhatsApp, dan informasi akun
- **Navigasi Responsif** — sidebar di desktop, bottom nav di mobile

### Fitur Baru
- 🚗 **Multi Tipe Kendaraan** — Motor, Mobil, dan Premium (masing-masing dengan tarif berbeda)
- 🏷️ **Kode Promo** — input kode diskon (contoh: `GALAX10` untuk diskon 10%)
- ⭐ **Rating Driver** — modal rating bintang + komentar muncul setelah perjalanan selesai
- 🏆 **GalaxiPoint (XP)** — poin reward otomatis dari setiap perjalanan
- 🎖️ **Achievement Badges** — lencana pencapaian yang bisa di-unlock di halaman profil
- 🌤️ **Widget Cuaca** — informasi cuaca acak di beranda sebagai panduan berkendara
- 🔍 **Filter Riwayat** — filter perjalanan berdasarkan tipe kendaraan
- ⏱️ **Estimasi Waktu (ETA)** — perkiraan waktu tiba berdasarkan tujuan

---

## 🎨 Desain

| Elemen | Detail |
|---|---|
| Tema | Dark Space / Galaksi Neon |
| Warna utama | Neon Blue `#00d4ff`, Neon Purple `#b44fff`, Neon Cyan `#00ffea` |
| Background | `#04050f` dengan animasi bintang berkedip (canvas) |
| Font | Orbitron (heading), Rajdhani (body) via Google Fonts |
| Animasi | Nebula blob, starfield canvas, glow effects |
| Komponen | Sidebar, topbar, bottom nav, modal, toast notification, map overlay |

---

## 🗂️ Struktur Proyek

```
galaxiride/
├── GalaxiRide.html       # File utama (single file app)
└── README.md             # Dokumentasi ini
```

Seluruh CSS, JavaScript, dan HTML berada dalam satu file (`GalaxiRide.html`).

---

## 🚀 Cara Menjalankan

Tidak perlu instalasi atau build tool apapun.

1. Download atau clone repositori ini
2. Buka file `GalaxiRide.html` langsung di browser

```bash
# Atau jalankan dengan live server (VS Code extension)
# Klik kanan GalaxiRide.html → Open with Live Server
```

> **Catatan:** Peta Leaflet membutuhkan koneksi internet untuk memuat tile OpenStreetMap.

---

## 📦 Dependensi Eksternal (CDN)

Semua dependensi dimuat via CDN, tidak ada instalasi npm yang diperlukan.

| Library | Versi | Kegunaan |
|---|---|---|
| [Font Awesome](https://fontawesome.com) | 6.5.0 | Ikon |
| [Google Fonts](https://fonts.google.com) | — | Font Orbitron & Rajdhani |
| [Leaflet.js](https://leafletjs.com) | 1.9.4 | Peta interaktif |
| [OpenStreetMap](https://www.openstreetmap.org) | — | Tile layer peta |

---

## 🧩 Halaman & Navigasi

| Halaman | Deskripsi |
|---|---|
| **Beranda** | Form pesan ride, pilih driver, widget cuaca, promo banner |
| **Riwayat** | Daftar semua perjalanan dengan filter tipe kendaraan |
| **Tentang Kami** | Informasi layanan dan fitur unggulan GalaxiRide |
| **Profil** | Edit akun, lihat saldo, XP, dan achievement badges |

---

## 💡 Kode Promo

| Kode | Diskon | Keterangan |
|---|---|---|
| `GALAX10` | 10% | Diskon untuk semua tipe kendaraan |

---

## 📱 Responsivitas

| Breakpoint | Layout |
|---|---|
| ≥ 769px | Sidebar kiri + konten utama |
| ≤ 768px | Sidebar tersembunyi (hamburger) + bottom navigation |
| ≥ 1400px | Padding konten lebih luas |

---

## 🔧 Pengembangan Lanjutan

Beberapa ide untuk pengembangan ke depan:

- Integrasi backend (Node.js / Laravel) untuk data persisten
- Autentikasi pengguna (login/register)
- Notifikasi push untuk status driver
- Integrasi payment gateway (GoPay, OVO, Dana)
- Riwayat perjalanan tersimpan di localStorage / database
- Mode gelap / terang yang bisa di-toggle

---

## 👤 Kredit

Dikembangkan berdasarkan proyek **Laju-Nanggroe** dengan desain ulang total bertema galaksi neon.

- Peta: [OpenStreetMap](https://www.openstreetmap.org) contributors
- Ikon: [Font Awesome](https://fontawesome.com)
- Font: [Google Fonts](https://fonts.google.com)

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan belajar dan pengembangan portofolio.  
Bebas digunakan dan dimodifikasi dengan mencantumkan kredit.
