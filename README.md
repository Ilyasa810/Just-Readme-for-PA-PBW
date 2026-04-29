<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0000,50:FF8C00,100:FFD700&height=220&section=header&text=🎡%20Wonderland%20Samarinda&fontSize=48&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Website%20Informasi%20and%20Manajemen%20Taman%20Hiburan%20Wonderland%20Samarinda&descAlignY=60&descSize=17" />

</div>

<div align="center">

[![PHP](https://img.shields.io/badge/PHP-8.1-%23777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-%234479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-%2342B883?style=for-the-badge&logo=vuedotjs&logoColor=white)](https://vuejs.org)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5-%237952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![Laragon](https://img.shields.io/badge/Laragon-Ready-%2345A3E5?style=for-the-badge&logo=laragon&logoColor=white)](https://laragon.org)

</div>

<div align="center">

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![License](https://img.shields.io/badge/License-Academic-orange?style=flat-square)
![University](https://img.shields.io/badge/Universitas-Mulawarman-blue?style=flat-square)
![Year](https://img.shields.io/badge/Tahun-2026%2F2027-purple?style=flat-square)

</div>

<br/>

<div align="center">

> 🎓 **Proyek Akhir Praktikum** — Mata Kuliah Pemrograman Berbasis Web
>
> Fakultas Teknik &nbsp;·&nbsp; Program Studi Sistem Informasi &nbsp;·&nbsp; Universitas Mulawarman

</div>

<br/>

<div align="center">

[📖 Deskripsi](#-deskripsi-aplikasi) &nbsp;·&nbsp; [✨ Fitur](#-fitur-website) &nbsp;·&nbsp; [📸 Screenshots](#-tampilan-website) &nbsp;·&nbsp; [🗂️ Struktur](#️-struktur-direktori) &nbsp;·&nbsp; [⚙️ Instalasi](#️-instalasi) &nbsp;·&nbsp; [👥 Tim](#-tim-pengembang)

</div>

<br/>

---

## 📖 Deskripsi Aplikasi

**Wonderland Samarinda** adalah sistem informasi wisata berbasis web yang dikembangkan sebagai solusi digitalisasi destinasi wisata nyata di Kota Samarinda. Dibangun menggunakan **PHP Native** dengan arsitektur **MVC (Model-View-Controller)**, aplikasi ini hadir sebagai platform terpadu untuk pengunjung dan pengelola taman hiburan.

<br/>

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                    WONDERLAND SAMARINDA                         │
│           Platform Wisata Digital Terpadu Samarinda             │
├─────────────────┬───────────────────┬───────────────────────────┤
│  🌐 Publik      │   👤 User Login   │       🔐 Admin            │
├─────────────────┼───────────────────┼───────────────────────────┤
│ Info taman &    │ Kirim ulasan &    │ Kelola seluruh data       │
│ wahana          │ rating            │ website                   │
│ Harga & promo   │ Upload foto       │ Moderasi ulasan & foto    │
│ Galeri & ulasan │ Lihat reservasi   │ Statistik real-time       │
│ Kontak & lokasi │ Dashboard pribadi │ Manajemen reservasi       │
└─────────────────┴───────────────────┴───────────────────────────┘
```

</div>

<br/>

---

## ✨ Fitur Website

<details open>
<summary><b>🌐 &nbsp;Halaman Publik — Tanpa Login</b></summary>
<br/>

| Menu | Fungsi |
|:---|:---|
| 🏠 **Beranda** | Landing page dengan highlight wahana, statistik, galeri, dan promo terkini |
| 🎢 **Aktivitas / Wahana** | Daftar wahana lengkap: deskripsi, harga, rating, kapasitas, dan fasilitas |
| 💰 **Harga & Promo** | Informasi paket tiket dan promo yang sedang aktif |
| 🏗️ **Fasilitas** | Daftar fasilitas tersedia di area wisata |
| 🖼️ **Galeri** | Foto-foto kunjungan yang telah dikurasi admin |
| ⭐ **Ulasan** | Ulasan dan rating dari pengunjung terdaftar |
| 📍 **Lokasi & Info** | Peta lokasi, jam operasional, dan informasi kunjungan |
| 🔑 **Login / Register** | Masuk atau buat akun pengunjung |

</details>

<br/>

<details open>
<summary><b>👤 &nbsp;Fitur User — Setelah Login</b></summary>
<br/>

| Menu | Fungsi |
|:---|:---|
| 📊 **Dashboard** | Ringkasan aktivitas dan informasi akun pribadi |
| ⭐ **Kirim Ulasan** | Tulis ulasan dan beri rating berdasarkan pengalaman kunjungan |
| 📷 **Upload Foto** | Unggah foto kunjungan untuk ditampilkan di galeri (perlu persetujuan admin) |
| 🎟️ **Reservasi Saya** | Lihat riwayat dan status reservasi |
| 🚪 **Logout** | Keluar dari sistem |

</details>

<br/>

<details open>
<summary><b>🔐 &nbsp;Panel Admin — Full Access</b></summary>
<br/>

| Menu | Fungsi |
|:---|:---|
| 📈 **Dashboard** | Statistik kunjungan, reservasi terbaru, dan wahana terpopuler |
| 🎠 **Kelola Wahana** | CRUD: nama, foto, keterangan, kapasitas, deskripsi, harga |
| 🏗️ **Kelola Fasilitas** | CRUD: nama, ikon, deskripsi, keterangan, status |
| 🏷️ **Kelola Harga Tiket** | CRUD: nama paket, harga, deskripsi, ketentuan |
| 🎁 **Kelola Promo** | Tambah dan kelola promo aktif |
| 📋 **Kelola Reservasi** | Input dan kelola data reservasi pengunjung |
| 💬 **Moderasi Ulasan** | Setujui atau tolak ulasan sebelum ditampilkan ke publik |
| 🖼️ **Moderasi Foto** | Setujui atau tolak foto unggahan pengunjung |
| 🚪 **Logout** | Keluar dari panel admin |

</details>

<br/>

<details>
<summary><b>🛡️ &nbsp;Keamanan Sistem</b></summary>
<br/>

| Fitur | Keterangan |
|:---|:---|
| 🔑 **CSRF Token** | Proteksi pada setiap form autentikasi |
| 🔒 **Session Auth** | Login & logout berbasis PHP session |
| 🚫 **Profanity Filter** | Filter otomatis konten tidak pantas pada ulasan |
| ✅ **Server-side Validation** | Validasi input ketat di sisi server |
| 🛡️ **Prepared Statement** | Pencegahan SQL Injection via `$db->prepare()` & `bind_param()` |

</details>

<br/>

---

## 📸 Tampilan Website

<details open>
<summary><b>🌐 &nbsp;Halaman Publik</b></summary>
<br/>

**🏠 Landing Page**
<div align="center">
  <img src="screenshots/landing-page.png" alt="Landing Page" width="85%"/>
  <br/><sub><i>Halaman utama dengan hero section, statistik, dan navigasi</i></sub>
</div>

<br/>

**🎢 Halaman Wahana / Atraksi**
<div align="center">
  <img src="screenshots/halaman-wahana.png" alt="Halaman Wahana" width="85%"/>
  <br/><sub><i>Daftar wahana dengan kategori, harga, dan tombol detail</i></sub>
</div>

<br/>

**🎯 Detail Wahana**
<div align="center">
  <img src="screenshots/detail-wahana.png" alt="Detail Wahana" width="85%"/>
  <br/><sub><i>Info lengkap wahana, ulasan pengunjung, dan form tulis ulasan</i></sub>
</div>

<br/>

**🖼️ Galeri Foto**
<div align="center">
  <img src="screenshots/galeri.png" alt="Galeri Foto" width="85%"/>
  <br/><sub><i>Kumpulan foto resmi dan kiriman pengunjung yang telah disetujui</i></sub>
</div>

<br/>

**⭐ Ulasan Pengunjung**
<div align="center">
  <img src="screenshots/ulasan.png" alt="Ulasan Pengunjung" width="85%"/>
  <br/><sub><i>Rating keseluruhan dan daftar ulasan dari pengunjung</i></sub>
</div>

<br/>

**💰 Harga Tiket & Promo**
<div align="center">
  <img src="screenshots/harga-tiket.png" alt="Harga Tiket dan Promo" width="85%"/>
  <br/><sub><i>Paket tiket masuk dan promo yang sedang berlaku</i></sub>
</div>

<br/>

**📍 Lokasi & Informasi**
<div align="center">
  <img src="screenshots/lokasi-info.png" alt="Lokasi dan Informasi" width="85%"/>
  <br/><sub><i>Peta lokasi, jam operasional, fasilitas, dan kontak</i></sub>
</div>

</details>

<br/>

<details open>
<summary><b>🔑 &nbsp;Autentikasi</b></summary>
<br/>

<div align="center">

| Login | Register |
|:---:|:---:|
| <img src="screenshots/login.png" alt="Login" width="100%"/> | <img src="screenshots/register.png" alt="Register" width="100%"/> |
| *Form masuk akun* | *Form daftar akun baru* |

</div>

</details>

<br/>

<details open>
<summary><b>👤 &nbsp;Dashboard User</b></summary>
<br/>

**📊 Dashboard Pengunjung**
<div align="center">
  <img src="screenshots/dashboard-user.png" alt="Dashboard User" width="85%"/>
  <br/><sub><i>Ringkasan aktivitas: ulasan, foto, dan reservasi milik user</i></sub>
</div>

<br/>

**⭐ Kirim Ulasan**
<div align="center">
  <img src="screenshots/kirim-ulasan.png" alt="Kirim Ulasan" width="85%"/>
  <br/><sub><i>Form pengisian ulasan dan bintang rating</i></sub>
</div>

<br/>

**📷 Upload Foto Kunjungan**
<div align="center">
  <img src="screenshots/upload-foto.png" alt="Upload Foto" width="85%"/>
  <br/><sub><i>Unggah foto kenangan untuk ditampilkan di galeri</i></sub>
</div>

<br/>

**🎟️ Reservasi Saya**
<div align="center">
  <img src="screenshots/reservasi-user.png" alt="Reservasi User" width="85%"/>
  <br/><sub><i>Daftar dan status reservasi pengunjung</i></sub>
</div>

</details>

<br/>

<details open>
<summary><b>🔐 &nbsp;Panel Admin</b></summary>
<br/>

**📈 Dashboard Admin**
<div align="center">
  <img src="screenshots/dashboard-admin.png" alt="Dashboard Admin" width="85%"/>
  <br/><sub><i>Statistik sistem, reservasi terbaru, dan wahana terpopuler</i></sub>
</div>

<br/>

**🎠 Kelola Wahana**
<div align="center">
  <img src="screenshots/admin-wahana.png" alt="Kelola Wahana" width="85%"/>
  <br/><sub><i>CRUD data wahana dengan foto dan informasi lengkap</i></sub>
</div>

<br/>

**📋 Kelola Reservasi**
<div align="center">
  <img src="screenshots/admin-reservasi.png" alt="Kelola Reservasi" width="85%"/>
  <br/><sub><i>Input dan manajemen data reservasi pengunjung</i></sub>
</div>

<br/>

**💬 Moderasi Ulasan**
<div align="center">
  <img src="screenshots/admin-ulasan.png" alt="Kelola Ulasan" width="85%"/>
  <br/><sub><i>Persetujuan dan penolakan ulasan sebelum tayang ke publik</i></sub>
</div>

<br/>

**🖼️ Moderasi Foto User**
<div align="center">
  <img src="screenshots/admin-foto-user.png" alt="Kelola Foto User" width="85%"/>
  <br/><sub><i>Kurasi foto unggahan pengunjung untuk galeri</i></sub>
</div>

<br/>

**🏗️ Kelola Fasilitas**
<div align="center">
  <img src="screenshots/admin-fasilitas.png" alt="Kelola Fasilitas" width="85%"/>
  <br/><sub><i>Manajemen data fasilitas yang tersedia di area wisata</i></sub>
</div>

<br/>

**🏷️ Kelola Harga & Promo**
<div align="center">
  <img src="screenshots/admin-harga-promo.png" alt="Kelola Harga dan Promo" width="85%"/>
  <br/><sub><i>Pengaturan paket tiket dan promo aktif</i></sub>
</div>


---

## 🗂️ Struktur Direktori

```
wonderland-samarinda/
│
├── 📁 app/
│   ├── 📁 controllers/              # Logika bisnis aplikasi
│   │   ├── AdminController.php      # Seluruh fitur panel admin
│   │   ├── AuthController.php       # Login, register, logout
│   │   ├── GaleriController.php     # Galeri foto
│   │   ├── UlasanController.php     # Ulasan & rating
│   │   ├── UserController.php       # Dashboard & fitur user
│   │   └── WahanaController.php     # Halaman publik & detail wahana
│   │
│   ├── 📁 models/                   # Interaksi dengan database
│   │   ├── GaleriModel.php
│   │   ├── ReservasiModel.php
│   │   ├── UlasanModel.php
│   │   ├── UserModel.php
│   │   └── WahanaModel.php
│   │
│   ├── 📁 views/                    # Tampilan halaman (HTML + PHP)
│   │   ├── 📁 admin/                # Seluruh view panel admin
│   │   │   └── 📁 partials/         # sidebar.php & topbar.php
│   │   ├── 📁 auth/                 # login.php & register.php
│   │   ├── 📁 public/               # home.php & detail_wahana.php
│   │   └── 📁 user/                 # dashboard.php user
│   │
│   └── 📁 helpers/                  # Fungsi pembantu global
│       ├── image_helper.php         # Pengelolaan upload gambar
│       └── profanity_filter.php     # Filter kata tidak pantas
│
├── 📁 assets/                       # File statis (tidak diproses server)
│   ├── 📁 css/                      # Stylesheet tampilan
│   ├── 📁 gallery/                  # Foto galeri resmi
│   └── 📁 wahana/                   # Foto masing-masing wahana
│
├── 📁 config/
│   └── koneksi.php                  # Konfigurasi koneksi MySQL
│
├── 📁 uploads/                      # Foto yang diunggah pengunjung
├── 📁 screenshots/                  # Screenshot untuk README
├── 📄 index.php                     # Entry point — Front Controller
└── 🗄️  wonderlands.sql              # Dump database lengkap
```

<br/>

---

## 🗄️ Skema Database

Database **`wonderlands`** terdiri dari **12 tabel** yang saling terintegrasi:

<div align="center">

| # | Tabel | Deskripsi |
|:---:|:---|:---|
| 1 | `users` | Data akun pengunjung terdaftar |
| 2 | `admin` | Data akun pengelola sistem |
| 3 | `wahana` | Data wahana & atraksi taman |
| 4 | `reservasi` | Data pemesanan kunjungan |
| 5 | `tiket` | Detail tiket per reservasi |
| 6 | `ulasan` | Review & rating dari pengunjung |
| 7 | `galeri` | Foto galeri resmi taman |
| 8 | `foto_pengunjung` | Foto kiriman pengunjung |
| 9 | `pricelist` | Daftar harga tiket & paket |
| 10 | `promo` | Promo & diskon aktif |
| 11 | `fasilitas` | Informasi fasilitas area wisata |
| 12 | `kontak_pesan` | Pesan masuk dari form kontak |

</div>

<br/>

---

## 🧱 Arsitektur MVC

<pre>
                    +---------------------------+
    HTTP Request -->|         index.php         |
                    |     (Front Controller)    |
                    +-------------+-------------+
                                  |
                          routing via ?page=
                                  |
                                  v
                    +---------------------------+
                    |        Controller         |
                    |  Auth / Wahana / User /   |
                    |  Admin / Ulasan / Galeri  |
                    +------------+--------------+
                                 |
                   +-------------+-------------+
                   |                           |
                   v                           v
        +----------+----------+   +-----------+-----------+
        |        Model        |   |          View         |
        |   (Query Database)  |   |   (Render HTML/PHP)   |
        +----------+----------+   +-----------+-----------+
                   |                           |
                   v                           v
        +----------+----------+   +-----------+-----------+
        |       Database      |   |   Response ke Browser |
        |   MySQL (12 tabel)  |   |                       |
        +---------------------+   +-----------------------+
</pre>


> **Cara kerja routing:** Semua request masuk ke `index.php` via parameter `?page=` (Front Controller Pattern).
> Contoh: URL `?page=admin_reservasi` → memanggil `AdminController->reservasi()`

<br/>

---

## ⚙️ Instalasi

### Prasyarat

| Tools | Versi | Keterangan |
|:---|:---:|:---|
| Laragon | Latest | [laragon.org](https://laragon.org/) — sudah include PHP & MySQL |
| PHP | 8.1+ | Sudah include di Laragon |
| MySQL | 8.0+ | Sudah include di Laragon |
| Browser | Modern | Chrome / Firefox / Edge |

<br/>

### Langkah Instalasi

**① Clone Repository**
```bash
git clone https://github.com/username/wonderland-samarinda.git
```

**② Pindahkan ke folder Laragon**
```
C:/laragon/www/wonderland-samarinda/
```

**③ Import Database**
```
1. Buka  →  http://localhost/phpmyadmin
2. Buat database baru  →  nama: wonderlands
3. Tab Import  →  upload wonderlands.sql  →  klik Go
```

**④ Konfigurasi Koneksi Database**

Edit file `config/koneksi.php`:
```php
<?php
$host = "localhost";
$user = "root";
$pass = "";            // Laragon default: kosong
$db   = "wonderlands";

$koneksi = mysqli_connect($host, $user, $pass, $db);
mysqli_set_charset($koneksi, "utf8mb4");
?>
```

**⑤ Jalankan Aplikasi**

Buka browser dan akses:
```
http://localhost/wonderland-samarinda/
```

<br/>

### 🚪 Akses Login

<div align="center">

| Role | URL | Cara Akses |
|:---:|:---|:---|
| 👥 **Publik** | `http://localhost/wonderland-samarinda/` | Langsung akses, tanpa login |
| 👤 **User** | `/?page=login` | Daftar akun baru via halaman Register |
| 🔐 **Admin** | `/?page=login` | Cek kredensial di tabel `admin` via phpMyAdmin |

</div>

<br/>

---

## 🛠️ Teknologi yang Digunakan

<div align="center">

| Teknologi | Versi | Peran dalam Proyek |
|:---:|:---:|:---|
| ![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white&style=flat-square) **PHP** | 8.1 | Backend utama, routing, dan logika bisnis |
| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square) **MySQL** | 8.0 | Database penyimpanan seluruh data |
| ![Vue.js](https://img.shields.io/badge/Vue.js-42B883?logo=vuedotjs&logoColor=white&style=flat-square) **Vue.js** | 3.x | Reaktivitas & interaktivitas UI frontend |
| ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white&style=flat-square) **Bootstrap** | 5.x | Komponen UI, grid, dan responsivitas |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square) **JavaScript** | ES6+ | Interaktivitas & validasi sisi klien |
| ![Laragon](https://img.shields.io/badge/Laragon-45A3E5?logo=laragon&logoColor=white&style=flat-square) **Laragon** | — | Local development server |

</div>

<br/>

---

## 👥 Tim Pengembang

<div align="center">

> 🎓 **Proyek Akhir PRAKTISI 2026 Genap** — Pemrograman Berbasis Web
>
> Dosen Pengampu: **Ir. M. Ibadurrahman Arrasyid, S.Kom., M.Kom**
>
> Mitra: **Wonderland Samarinda** — Destinasi Wisata Kota Samarinda

</div>

<br/>

<div align="center">

| Avatar | Nama | NIM | Kontribusi |
|:---:|:---|:---:|:---|
| 👩‍💼 | **Nayla Camelia Indraswari** | 2409116009 | Koordinasi Tim · Flowchart Sistem · Penyusunan Laporan |
| 👩‍💻 | **Nabila Imtiyaz Agustin** | 2409116011 | Perancangan & Pengelolaan Database · Penyusunan Laporan |
| 👨‍💻 | **Muhammad Ilyasa' 'Izzuddin** | 2409116033 | Backend Development · Integrasi Website & Database |
| 👨‍🎨 | **Muhammad Reffi Fadillah** | 2409116034 | UI/UX Design (Figma) · Frontend (HTML/CSS/Vue.js) · Backend (PHP) |

</div>

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" />

<br/>

**🎡 Wonderland Samarinda**

*Dibuat dengan ❤️ oleh Wondercode Team*

*Program Studi Sistem Informasi · Fakultas Teknik · Universitas Mulawarman*

*Samarinda, Kalimantan Timur · 2026/2027*

<br/>

![Made with PHP](https://img.shields.io/badge/Made%20with-PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Database MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Universitas Mulawarman](https://img.shields.io/badge/Universitas-Mulawarman-gold?style=flat-square)

</div>
