<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=🎡%20Wonderland%20Samarinda&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Website%20Manajemen%20Taman%20Hiburan%20Berbasis%20PHP%20MVC&descAlignY=58&descSize=16" />

<br/>

[![PHP](https://img.shields.io/badge/PHP-8.1-%23777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-%234479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-%2342B883?style=for-the-badge&logo=vuedotjs&logoColor=white)](https://vuejs.org)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5-%237952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![Laragon](https://img.shields.io/badge/Laragon-Compatible-%2345A3E5?style=for-the-badge&logo=laragon&logoColor=white)](https://laragon.org)

<br/>

> 🎓 **Proyek Akhir PRAKTISI 2026 Genap** — Pemrograman Web
> Universitas Mulawarman · Fakultas Ilmu Komputer dan Teknologi Informasi

<br/>

[📖 Deskripsi](#-deskripsi-aplikasi) · [✨ Fitur](#-fitur-website) · [⚙️ Instalasi](#%EF%B8%8F-instalasi) · [👥 Tim](#-tim-pengembang)

</div>

<br/>

---

## 📖 Deskripsi Aplikasi

**Wonderland Samarinda** adalah aplikasi web manajemen taman hiburan yang dikembangkan sebagai solusi digitalisasi objek wisata nyata di Samarinda. Dibangun menggunakan **PHP Native** dengan pola arsitektur **MVC (Model-View-Controller)**, aplikasi ini menghadirkan pengalaman lengkap — mulai dari informasi publik taman, sistem reservasi online, hingga panel admin untuk pengelolaan konten secara menyeluruh.

<br/>

<div align="center">

| 🌐 Pengunjung Umum | 👤 User Login | 🔐 Admin |
|:---:|:---:|:---:|
| Lihat info taman & wahana | Reservasi tiket online | Kelola semua data |
| Cek pricelist & galeri | Upload foto kunjungan | Moderasi ulasan |
| Baca ulasan pengunjung | Tulis ulasan & rating | Statistik dashboard |

</div>

<br/>

---

## ✨ Fitur Website

<details open>
<summary><b>🌐 Halaman Publik</b></summary>
<br/>

- 🏠 **Beranda** — Landing page dengan info taman, statistik, galeri, dan ulasan terbaru
- 🎢 **Detail Wahana** — Deskripsi lengkap, foto, dan informasi tiap wahana
- 💰 **Pricelist** — Daftar harga tiket dan paket kunjungan

</details>

<details open>
<summary><b>👤 Fitur User (Setelah Login)</b></summary>
<br/>

- 📊 **Dashboard** — Ringkasan aktivitas dan riwayat kunjungan
- 🎟️ **Reservasi** — Pemesanan tiket secara online
- 📷 **Upload Foto** — Unggah foto kenangan kunjungan
- ⭐ **Ulasan & Rating** — Tulis review untuk setiap wahana

</details>

<details open>
<summary><b>🔐 Panel Admin</b></summary>
<br/>

- 📈 **Dashboard** — Statistik kunjungan dan ringkasan data real-time
- 🎠 **Manajemen Wahana** — CRUD data wahana (nama, foto, deskripsi)
- 📋 **Manajemen Reservasi** — Kelola dan konfirmasi pemesanan tiket
- 💬 **Manajemen Ulasan** — Moderasi ulasan dari pengunjung
- 🏷️ **Pricelist & Promo** — Kelola harga dan promo aktif
- 🏗️ **Fasilitas** — Kelola informasi fasilitas taman
- 🖼️ **Galeri & Foto User** — Kelola foto resmi dan kiriman pengunjung

</details>

<details open>
<summary><b>🛡️ Keamanan</b></summary>
<br/>

- 🔑 **CSRF Token** — Perlindungan pada setiap form autentikasi
- 🔒 **Session Auth** — Login & logout berbasis session PHP
- 🚫 **Profanity Filter** — Filter otomatis kata tidak pantas pada ulasan
- ✅ **Server-side Validation** — Validasi input di sisi server

</details>

<br/>

---

## 🗂️ Struktur Direktori

```
wonderland-samarinda/
│
├── 📁 app/
│   ├── 📁 controllers/         # Logika bisnis aplikasi
│   │   ├── AdminController.php
│   │   ├── AuthController.php
│   │   ├── GaleriController.php
│   │   ├── UlasanController.php
│   │   ├── UserController.php
│   │   └── WahanaController.php
│   │
│   ├── 📁 models/              # Interaksi dengan database
│   │   ├── GaleriModel.php
│   │   ├── ReservasiModel.php
│   │   ├── UlasanModel.php
│   │   ├── UserModel.php
│   │   └── WahanaModel.php
│   │
│   ├── 📁 views/               # Tampilan halaman
│   │   ├── admin/              # View panel admin
│   │   ├── auth/               # Login & Register
│   │   ├── public/             # Halaman publik
│   │   └── user/               # Dashboard user
│   │
│   └── 📁 helpers/             # Fungsi pembantu
│       ├── image_helper.php
│       └── profanity_filter.php
│
├── 📁 assets/                  # CSS, JS, gambar statis
├── 📁 config/
│   └── koneksi.php             # Konfigurasi database
├── 📁 uploads/                 # Foto yang diupload user
├── 📄 index.php                # Entry point (Front Controller)
└── 🗄️ wonderlands.sql          # Dump database lengkap
```

<br/>

---

## 🗄️ Skema Database

Database `wonderlands` terdiri dari **12 tabel**:

<div align="center">

| # | Tabel | Keterangan |
|:---:|:---|:---|
| 1 | `users` | Data akun pengunjung terdaftar |
| 2 | `admin` | Data akun pengelola / admin |
| 3 | `wahana` | Data wahana & atraksi taman |
| 4 | `reservasi` | Data pemesanan tiket masuk |
| 5 | `tiket` | Detail tiket per reservasi |
| 6 | `ulasan` | Review & rating dari pengunjung |
| 7 | `galeri` | Galeri foto resmi taman |
| 8 | `foto_pengunjung` | Foto kiriman pengunjung |
| 9 | `pricelist` | Daftar harga tiket |
| 10 | `promo` | Data promo & diskon aktif |
| 11 | `fasilitas` | Informasi fasilitas taman |
| 12 | `kontak_pesan` | Pesan dari form kontak |

</div>

<br/>

---

## ⚙️ Instalasi

### Prasyarat

- ✅ [Laragon](https://laragon.org/) (PHP 8.1+ & MySQL 8.0+)
- ✅ Browser modern (Chrome, Firefox, Edge)
- ✅ Git (opsional, untuk clone)

<br/>

### Langkah-langkah

**① Clone Repository**
```bash
git clone https://github.com/username/wonderland-samarinda.git
```

**② Pindahkan ke folder www**
```
C:/laragon/www/wonderland-samarinda/
```

**③ Import Database**
```
1. Buka http://localhost/phpmyadmin
2. Buat database baru → nama: wonderlands
3. Pilih tab Import → upload file wonderlands.sql → klik Go
```

**④ Konfigurasi Koneksi**

Edit file `config/koneksi.php`:
```php
$host = "localhost";
$user = "root";
$pass = "";           // Laragon default: password kosong
$db   = "wonderlands";
```

**⑤ Jalankan Aplikasi**
```
🌐 http://localhost/wonderland-samarinda/
```

<br/>

### 🚪 Akses Login

| Role | URL | Keterangan |
|:---:|:---|:---|
| 👥 Publik | `/` | Tanpa login |
| 👤 User | `/?page=login` | Daftar akun baru via Register |
| 🔐 Admin | `/?page=login` | Cek kredensial di tabel `admin` (phpMyAdmin) |

<br/>

---

## 🧱 Arsitektur MVC

```
                    ┌─────────────────────┐
    HTTP Request ──▶│     index.php        │
                    │  (Front Controller)  │
                    └────────┬────────────┘
                             │ routing via ?page=
                             ▼
                    ┌─────────────────────┐
                    │     Controller       │
                    │  (Wahana/User/Admin) │
                    └──────┬──────┬───────┘
                           │      │
               ┌───────────▼──┐  ┌▼───────────────┐
               │    Model     │  │      View        │
               │  (query DB)  │  │ (render HTML/PHP)│
               └──────┬───────┘  └────────┬─────────┘
                      │                   │
               ┌──────▼──────┐            ▼
               │   Database   │     Response ke Browser
               │   (MySQL)    │
               └─────────────┘
```

<br/>

---

## 🛠️ Teknologi

<div align="center">

| Teknologi | Versi | Fungsi |
|:---:|:---:|:---|
| ![PHP](https://img.shields.io/badge/-PHP-777BB4?logo=php&logoColor=white) | 8.1 | Backend & routing |
| ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white) | 8.0 | Database utama |
| ![Vue.js](https://img.shields.io/badge/-Vue.js-42B883?logo=vuedotjs&logoColor=white) | 3.x | Reaktivitas UI frontend |
| ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white) | 5.x | Komponen UI & responsivitas |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) | ES6+ | Interaktivitas halaman |
| ![Laragon](https://img.shields.io/badge/-Laragon-777BB4?logo=laragon&logoColor=white) | — | Local server development |

</div>

<br/>

---

## 👥 Tim Pengembang

> 🎓 Dikerjakan sebagai **Proyek Akhir PRAKTISI 2026 Genap** — Mata Kuliah Pemrograman Web, bermitra dengan objek wisata **Wonderland Samarinda**.

<div align="center">

| Nama | NIM | Peran |
|:---|:---:|:---:|
| *(nama anggota 1)* | *(NIM)* | Backend & Database |
| *(nama anggota 2)* | *(NIM)* | Frontend & UI |
| *(nama anggota 3)* | *(NIM)* | Admin Panel |
| *(nama anggota 4)* | *(NIM)* | Dokumentasi & Testing |

</div>

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />

**🎡 Wonderland Samarinda**

*Dibuat dengan ❤️ oleh Tim Proyek Akhir PRAKTISI 2026 Genap*

*Universitas Mulawarman — Samarinda, Kalimantan Timur*

</div>
