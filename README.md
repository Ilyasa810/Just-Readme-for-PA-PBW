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
> Universitas Mulawarman · Fakultas Teknik · Program Studi Sistem Informasi

<br/>

[📖 Deskripsi](#-deskripsi-aplikasi) · [✨ Fitur](#-fitur-website) · [⚙️ Instalasi](#%EF%B8%8F-instalasi) · [👥 Tim](#-tim-pengembang)

</div>

<br/>

---

## 📖 Deskripsi Aplikasi

**Wonderland Samarinda** adalah aplikasi web manajemen taman hiburan yang dikembangkan sebagai solusi digitalisasi objek wisata nyata di Samarinda. Dibangun menggunakan **PHP Native** dengan pola arsitektur **MVC (Model-View-Controller)**, aplikasi ini menghadirkan pengalaman lengkap — mulai dari informasi publik taman, sistem reservasi online, hingga panel admin untuk pengelolaan konten secara menyeluruh.

Website ini bertujuan untuk memudahkan masyarakat dalam memperoleh informasi terkait wahana, fasilitas, harga tiket, serta ulasan pengunjung secara cepat dan mudah diakses. Dari sisi admin, sistem ini mendukung pengelolaan data secara efisien melalui fitur CRUD yang terintegrasi dengan database MySQL.

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
<summary><b>🌐 Halaman Publik (Tanpa Login)</b></summary>
<br/>

- 🏠 **Beranda** — Landing page dengan info taman, statistik, galeri, dan ulasan terbaru
- 🎢 **Aktivitas/Wahana** — Daftar wahana beserta deskripsi, harga, keterangan, rating, dan fasilitas
- 💰 **Harga & Promo** — Informasi harga tiket serta promo yang sedang berlaku
- 🏗️ **Fasilitas** — Daftar fasilitas yang tersedia di area wisata
- 🖼️ **Galeri** — Foto-foto kunjungan yang telah disetujui oleh admin
- ⭐ **Ulasan** — Ulasan dan rating dari pengunjung
- 🔑 **Login & Register** — Masuk atau membuat akun user

</details>

<details open>
<summary><b>👤 Fitur User (Setelah Login)</b></summary>
<br/>

- 📊 **Dashboard** — Halaman utama user setelah login yang menampilkan ringkasan informasi akun
- ⭐ **Kirim Ulasan** — Mengisi dan mengirim ulasan serta rating terhadap pengalaman kunjungan
- 📷 **Upload Foto** — Mengunggah foto kunjungan ke dalam sistem
- 🚪 **Logout** — Keluar dari sistem

</details>

<details open>
<summary><b>🔐 Panel Admin</b></summary>
<br/>

- 📈 **Dashboard** — Ringkasan data dan aktivitas dalam sistem secara real-time
- 🎠 **Kelola Aktivitas/Wahana** — CRUD data wahana (nama, foto, keterangan, kapasitas, deskripsi, harga)
- 🏗️ **Kelola Fasilitas** — CRUD data fasilitas (nama, ikon, deskripsi, keterangan tambahan, status)
- 🏷️ **Kelola Harga Tiket** — Mengelola data harga tiket (nama paket, harga, deskripsi, ketentuan)
- 🎁 **Kelola Promo** — Mengelola informasi promo aktif
- 📋 **Kelola Reservasi** — Menginput dan mengelola data reservasi pengguna
- 💬 **Kelola Ulasan** — Menyetujui atau menolak ulasan dari pengunjung sebelum ditampilkan ke publik
- 🖼️ **Kelola Foto User** — Menyetujui atau menolak foto yang diunggah pengunjung
- 🚪 **Logout** — Keluar dari halaman admin

</details>

<details open>
<summary><b>🛡️ Keamanan</b></summary>
<br/>

- 🔑 **CSRF Token** — Perlindungan pada setiap form autentikasi
- 🔒 **Session Auth** — Login & logout berbasis session PHP
- 🚫 **Profanity Filter** — Filter otomatis kata tidak pantas pada ulasan
- ✅ **Server-side Validation** — Validasi input di sisi server
- 🛡️ **Prepared Statement** — Pencegahan SQL Injection menggunakan `$db->prepare()` dan `bind_param()`

</details>

<br/>

---

## 📸 Tampilan Website

<details open>
<summary><b>🌐 Halaman Publik</b></summary>
<br/>

**Landing Page**
<div align="center">
  <img src="screenshots/landing-page.png" alt="Landing Page" width="80%"/>
</div>
<br/>

**Halaman Wahana / Atraksi**
<div align="center">
  <img src="screenshots/halaman-wahana.png" alt="Halaman Wahana" width="80%"/>
</div>
<br/>

**Detail Wahana**
<div align="center">
  <img src="screenshots/detail-wahana.png" alt="Detail Wahana" width="80%"/>
</div>
<br/>

**Galeri Foto**
<div align="center">
  <img src="screenshots/galeri.png" alt="Galeri Foto" width="80%"/>
</div>
<br/>

**Ulasan Pengunjung**
<div align="center">
  <img src="screenshots/ulasan.png" alt="Ulasan Pengunjung" width="80%"/>
</div>
<br/>

**Harga Tiket & Promo**
<div align="center">
  <img src="screenshots/harga-tiket.png" alt="Harga Tiket dan Promo" width="80%"/>
</div>
<br/>

**Lokasi & Informasi**
<div align="center">
  <img src="screenshots/lokasi-info.png" alt="Lokasi dan Informasi" width="80%"/>
</div>

</details>

<details open>
<summary><b>🔑 Autentikasi</b></summary>
<br/>

**Halaman Login**
<div align="center">
  <img src="screenshots/login.png" alt="Halaman Login" width="80%"/>
</div>
<br/>

**Halaman Register**
<div align="center">
  <img src="screenshots/register.png" alt="Halaman Register" width="80%"/>
</div>

</details>

<details open>
<summary><b>👤 Dashboard User</b></summary>
<br/>

**Dashboard Pengunjung**
<div align="center">
  <img src="screenshots/dashboard-user.png" alt="Dashboard User" width="80%"/>
</div>
<br/>

**Kirim Ulasan**
<div align="center">
  <img src="screenshots/kirim-ulasan.png" alt="Kirim Ulasan" width="80%"/>
</div>
<br/>

**Upload Foto Kunjungan**
<div align="center">
  <img src="screenshots/upload-foto.png" alt="Upload Foto" width="80%"/>
</div>
<br/>

**Reservasi Saya**
<div align="center">
  <img src="screenshots/reservasi-user.png" alt="Reservasi User" width="80%"/>
</div>

</details>

<details open>
<summary><b>🔐 Panel Admin</b></summary>
<br/>

**Dashboard Admin**
<div align="center">
  <img src="screenshots/dashboard-admin.png" alt="Dashboard Admin" width="80%"/>
</div>
<br/>

**Kelola Wahana**
<div align="center">
  <img src="screenshots/admin-wahana.png" alt="Kelola Wahana" width="80%"/>
</div>
<br/>

**Kelola Reservasi**
<div align="center">
  <img src="screenshots/admin-reservasi.png" alt="Kelola Reservasi" width="80%"/>
</div>
<br/>

**Kelola Ulasan**
<div align="center">
  <img src="screenshots/admin-ulasan.png" alt="Kelola Ulasan" width="80%"/>
</div>
<br/>

**Kelola Foto User**
<div align="center">
  <img src="screenshots/admin-foto-user.png" alt="Kelola Foto User" width="80%"/>
</div>
<br/>

**Kelola Fasilitas**
<div align="center">
  <img src="screenshots/admin-fasilitas.png" alt="Kelola Fasilitas" width="80%"/>
</div>
<br/>

**Kelola Harga & Promo**
<div align="center">
  <img src="screenshots/admin-harga-promo.png" alt="Kelola Harga dan Promo" width="80%"/>
</div>

</details>

> 💡 **Cara menambahkan screenshot:** Buat folder `screenshots/` di root project, lalu simpan gambar sesuai nama file di atas. Atau ganti path `screenshots/nama-file.png` dengan URL gambar langsung jika di-host online.

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
│   │   │   └── partials/       # Komponen sidebar.php & topbar.php
│   │   ├── auth/               # Login & Register
│   │   ├── public/             # Halaman publik
│   │   └── user/               # Dashboard user
│   │
│   └── 📁 helpers/             # Fungsi pembantu
│       ├── image_helper.php
│       └── profanity_filter.php
│
├── 📁 assets/                  # CSS, JS, gambar statis
│   ├── css/                    # File stylesheet tampilan
│   ├── gallery/                # Foto galeri
│   └── wahana/                 # Foto masing-masing wahana
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

Semua request diarahkan melalui `index.php` menggunakan parameter `?page=` di URL (Front Controller Pattern). Contoh: `?page=admin_reservasi` akan memanggil `AdminController->reservasi()`.

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

> 🎓 Dikerjakan sebagai **Proyek Akhir PRAKTISI 2026 Genap** — Mata Kuliah Pemrograman Berbasis Web, bermitra dengan objek wisata **Wonderland Samarinda**.
> 
> Dosen Pengampu: **Ir. M. Ibadurrahman Arrasyid, S.Kom., M.Kom**

<div align="center">

| Nama | NIM | Peran |
|:---|:---:|:---|
| Nayla Camelia Indraswari | 2409116009 | Koordinasi Tim, Flowchart & Laporan |
| Nabila Imtiyaz Agustin | 2409116011 | Database Design & Laporan |
| Muhammad Ilyasa' 'Izzuddin | 2409116033 | Backend & Integrasi Database |
| Muhammad Reffi Fadillah | 2409116034 | UI/UX Design (Figma), Frontend (HTML/CSS/Vue.js) & Backend (PHP) |

</div>

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />

**🎡 Wonderland Samarinda**

*Dibuat dengan ❤️ oleh Tim Proyek Akhir PRAKTISI 2026 Genap*

*Program Studi Sistem Informasi — Fakultas Teknik — Universitas Mulawarman, Samarinda, Kalimantan Timur*

</div>
