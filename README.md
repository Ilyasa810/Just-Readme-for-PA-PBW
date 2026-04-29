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

[📖 Deskripsi](#-deskripsi-aplikasi) &nbsp;·&nbsp; [🎯 Tujuan & Manfaat](#-tujuan--manfaat) &nbsp;·&nbsp; [✨ Fitur](#-fitur-website) &nbsp;·&nbsp; [📸 Screenshots](#-tampilan-website) &nbsp;·&nbsp; [🗂️ Struktur](#️-struktur-direktori) &nbsp;·&nbsp; [⚙️ Instalasi](#️-instalasi) &nbsp;·&nbsp; [👥 Tim](#-tim-pengembang)

</div>

<br/>

---

## 📖 Deskripsi Aplikasi

**Wonderland Samarinda** adalah sistem informasi wisata berbasis web yang dikembangkan sebagai solusi digitalisasi destinasi wisata nyata di Kota Samarinda. Dibangun menggunakan **PHP Native** dengan arsitektur **MVC (Model-View-Controller)**, aplikasi ini hadir sebagai platform terpadu untuk pengunjung dan pengelola taman hiburan.

Perkembangan teknologi informasi di era digital telah memberikan dampak signifikan dalam penyebaran informasi dan promosi sektor pariwisata. Website ini hadir untuk menjawab kebutuhan Wonderland Samarinda yang sebelumnya belum memiliki platform digital resmi — informasi mengenai wahana, fasilitas, harga tiket, dan ulasan pengunjung masih terbatas dan tidak terpusat.

<br/>

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                    WONDERLAND SAMARINDA                         │
│           Platform Wisata Digital Terpadu Samarinda             │
├─────────────────┬───────────────────┬───────────────────────────┤
│    🌐 Publik    │   👤 User Login   │        🔐 Admin          │
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

## 🎯 Tujuan & Manfaat

### Tujuan Proyek

1. Membangun website yang mampu menyajikan informasi mengenai Wonderland Samarinda secara terpusat dan mudah diakses oleh masyarakat.
2. Menyediakan media digital yang informatif untuk menampilkan data wahana, fasilitas, tiket, dan ulasan pengunjung secara terstruktur.
3. Mempermudah admin dalam mengelola informasi wisata melalui fitur pengelolaan data berbasis website yang efisien dan terorganisir.

### Manfaat Proyek

1. **Meningkatkan efektivitas pengelolaan informasi** — Website membantu mitra dalam mengelola dan memperbarui informasi terkait Wonderland Samarinda.
2. **Mendukung media promosi digital** — Website dapat digunakan sebagai sarana promosi resmi yang mampu menjangkau lebih banyak calon pengunjung.
3. **Mempermudah penyampaian informasi** — Mitra dapat menyampaikan informasi secara cepat, akurat, dan terpusat tanpa bergantung pada media lain yang terbatas.
4. **Meningkatkan profesionalitas pengelolaan wisata** — Keberadaan website resmi memberikan kesan lebih profesional dan terpercaya.

### ⚠️ Keterbatasan Proyek

- Website berfungsi sebagai **media informasi dan pengelolaan data**, belum mendukung fitur transaksi secara penuh.
- Sistem belum menyediakan fitur **pembelian tiket secara online**; pembelian tiket masih dilakukan secara langsung di lokasi wisata.
- Website belum mendukung **sistem pembayaran digital**.

<br/>

---

## ✨ Fitur Website

<details open>
<summary><b>🌐 &nbsp;Halaman Publik — Tanpa Login</b></summary>
<br/>

| Menu | Fungsi |
|:---|:---|
| 🏠 **Beranda** | Landing page dengan gambaran umum wisata, highlight aktivitas, dan promo terbaru |
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
| 🎟️ **Reservasi** | Pemesanan kunjungan; memilih tanggal dan mengisi data, disimpan dengan status menunggu konfirmasi admin |
| ⭐ **Kirim Ulasan** | Tulis ulasan dan beri rating berdasarkan pengalaman kunjungan |
| 📷 **Upload Foto** | Unggah foto kunjungan untuk ditampilkan di galeri (perlu persetujuan admin) |
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
  <img src="https://github.com/user-attachments/assets/c46b3a2b-8b46-443b-85ea-55a359a52428" alt="Landing Page" width="85%"/>
  <br/><sub><i>Halaman utama dengan hero section, statistik, dan navigasi</i></sub>
</div>

<br/>

**🎢 Halaman Wahana / Atraksi**
<div align="center">
  <img src="https://github.com/user-attachments/assets/565d69c2-54eb-4b2a-9900-2ef2d9403b70" alt="Halaman Wahana" width="85%"/>
  <br/><sub><i>Daftar wahana dengan kategori, harga, dan tombol detail</i></sub>
</div>

<br/>

**🎯 Detail Wahana**
<div align="center">
  <img src="https://github.com/user-attachments/assets/6a3899ee-c346-44c4-860f-d124918a2a95" alt="Detail Wahana" width="85%"/>
  <br/><sub><i>Info lengkap wahana, ulasan pengunjung, dan form tulis ulasan</i></sub>
</div>

<br/>

**🖼️ Galeri Foto**
<div align="center">
  <img src= "https://github.com/user-attachments/assets/154da513-5484-4c66-9ca1-3f55be7d57df" alt="Galeri Foto" width="85%"/>
  <br/><sub><i>Kumpulan foto resmi dan kiriman pengunjung yang telah disetujui</i></sub>
</div>

<br/>

**⭐ Ulasan Pengunjung**
<div align="center">
  <img src="https://github.com/user-attachments/assets/dda462b3-e544-4f7b-a03c-473ac935a457" alt="Ulasan Pengunjung" width="85%"/>
  <br/><sub><i>Rating keseluruhan dan daftar ulasan dari pengunjung</i></sub>
</div>

<br/>

**💰 Harga Tiket & Promo**
<div align="center">
  <img src= "https://github.com/user-attachments/assets/6e04c311-c1fd-4491-a174-13c7c77fb61c" alt="Harga Tiket dan Promo" width="85%"/>
  <br/><sub><i>Paket tiket masuk dan promo yang sedang berlaku</i></sub>
</div>

<br/>

**📍 Lokasi & Informasi**
<div align="center">
  <img src= "https://github.com/user-attachments/assets/d4b11bbe-925a-44d7-8976-26eb716bd252" alt="Lokasi dan Informasi" width="85%"/>
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
| <img src= "https://github.com/user-attachments/assets/85c25c6d-01e9-47aa-b1ca-5a1077cb1900" alt="Login" width="100%"/> | <img src= "https://github.com/user-attachments/assets/1575e605-4423-4dac-9997-972e88f1705a" alt="Register" width="100%"/> |
| *Form masuk akun* | *Form daftar akun baru* |

</div>

</details>

<br/>

<details open>
<summary><b>👤 &nbsp;Dashboard User</b></summary>
<br/>

**📊 Dashboard Pengunjung**
<div align="center">
  <img src="https://github.com/user-attachments/assets/698b0edb-8800-4b22-8d61-6a189e2bec86" alt="Dashboard User" width="85%"/>
  <br/><sub><i>Ringkasan aktivitas: ulasan, foto, dan reservasi milik user</i></sub>
</div>

<br/>

**⭐ Kirim Ulasan**
<div align="center">
  <img src="https://github.com/user-attachments/assets/bba4beab-5eb8-41ea-bbad-c2e2b2028b5a" alt="Kirim Ulasan" width="85%"/>
  <br/><sub><i>Form pengisian ulasan dan bintang rating</i></sub>
</div>

<br/>

**📷 Upload Foto Kunjungan**
<div align="center">
  <img src="https://github.com/user-attachments/assets/abc87741-3e37-4054-82ee-091494718c22" alt="Upload Foto" width="85%"/>
  <br/><sub><i>Unggah foto kenangan untuk ditampilkan di galeri</i></sub>
</div>

<br/>

**🎟️ Reservasi Saya**
<div align="center">
  <img src= "https://github.com/user-attachments/assets/1ade2e14-03f5-479a-ab38-0d6ce9439698" alt="Reservasi User" width="85%"/>
  <br/><sub><i>Daftar dan status reservasi pengunjung</i></sub>
</div>

</details>

<br/>

<details open>
<summary><b>🔐 &nbsp;Panel Admin</b></summary>
<br/>

**📈 Dashboard Admin**
<div align="center">
  <img src="https://github.com/user-attachments/assets/b8682d3e-8805-45d0-ba93-04c062e6452b" alt="Dashboard Admin" width="85%"/>
  <br/><sub><i>Statistik sistem, reservasi terbaru, dan wahana terpopuler</i></sub>
</div>

<br/>

**🎠 Kelola Wahana**
<div align="center">
  <img src="https://github.com/user-attachments/assets/1bee1b48-7690-47e4-ac3d-6d506d49471e" alt="Kelola Wahana" width="85%"/>
  <br/><sub><i>CRUD data wahana dengan foto dan informasi lengkap</i></sub>
</div>

<br/>

**📋 Kelola Reservasi**
<div align="center">
  <img src= "https://github.com/user-attachments/assets/72b66aec-320b-4a74-936b-6924b45e6442" alt="Kelola Reservasi" width="85%"/>
  <br/><sub><i>Input dan manajemen data reservasi pengunjung</i></sub>
</div>

<br/>

**💬 Moderasi Ulasan**
<div align="center">
  <img src="https://github.com/user-attachments/assets/5f6dfab3-6502-4931-a185-28d27f83ca06" alt="Kelola Ulasan" width="85%"/>
  <br/><sub><i>Persetujuan dan penolakan ulasan sebelum tayang ke publik</i></sub>
</div>

<br/>

**🖼️ Moderasi Foto User**
<div align="center">
  <img src= "https://github.com/user-attachments/assets/93002d17-1293-41dc-9930-c1ec10dace3c" alt="Kelola Foto User" width="85%"/>
  <br/><sub><i>Kurasi foto unggahan pengunjung untuk galeri</i></sub>
</div>

<br/>

**🏗️ Kelola Fasilitas**
<div align="center">
  <img src="https://github.com/user-attachments/assets/03d49ef1-7e1a-4747-8f1d-0c1d9c15a433" alt="Kelola Fasilitas" width="85%"/>
  <br/><sub><i>Manajemen data fasilitas yang tersedia di area wisata</i></sub>
</div>

<br/>

**🏷️ Kelola Harga & Promo**
<div align="center">
  <img src="https://github.com/user-attachments/assets/2811ed56-eb8f-4a2a-8387-9ff41c467971" alt="Kelola Harga dan Promo" width="85%"/>
  <br/><sub><i>Pengaturan paket tiket dan promo aktif</i></sub>
</div>

</details>

<br/>

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

**Penjelasan tiap layer:**

- **`UserModel.php`** — Menangani data pengguna: pencarian user by email saat login, pembuatan akun baru, pengelolaan foto unggahan pengunjung.
- **`WahanaModel.php`** — Mengambil data wahana untuk halaman daftar maupun detail berdasarkan ID.
- **`GaleriModel.php`** — Mengambil data foto galeri yang ditampilkan di halaman publik.
- **`ReservasiModel.php`** — Menangani data reservasi: ambil semua data, ubah status (terjadwal/selesai/dibatalkan), hapus data.
- **`UlasanModel.php`** — Mengelola ulasan: simpan ulasan baru, ubah status (pending/approved), hapus ulasan.
- Semua Model menggunakan **Prepared Statement** (`$db->prepare()` & `bind_param()`) untuk mencegah SQL Injection.

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

> 🎓 **Proyek Akhir Praktikum** — Mata Kuliah Pemrograman Berbasis Web
>
> Dosen Pengampu: **Ir. M. Ibadurrahman Arrasyid, S.Kom., M.Kom**
>
> Mitra: **Wonderland Samarinda** — Destinasi Wisata Kota Samarinda

</div>

<br/>

<div align="center">

| Avatar | Nama | NIM | Kontribusi |
|:---:|:---|:---:|:---|
| 👩‍💼 | **Nayla Camelia Indraswari** | 2409116009 | Koordinasi Tim · Pembuatan Flowchart Sistem · Penyusunan Laporan |
| 👩‍💻 | **Nabila Imtiyaz Agustin** | 2409116011 | Perancangan & Pengelolaan Database · Penyusunan Laporan |
| 👨‍💻 | **Muhammad Ilyasa' 'Izzuddin** | 2409116033 | Backend Development · Integrasi Website & Database · Penyusunan Laporan |
| 👨‍🎨 | **Muhammad Reffi Fadillah** | 2409116034 | UI/UX Design (Figma) · Frontend (HTML/CSS/Vue.js) · Backend (PHP) · Penyusunan Laporan |

</div>

<br/>

---

## 📝 Kesimpulan

Pembangunan website Wonderland Samarinda dirancang sebagai solusi untuk menyediakan media informasi wisata yang terpusat, terstruktur, dan mudah diakses oleh masyarakat. Website ini menampilkan berbagai informasi penting seperti wahana, fasilitas, harga tiket, serta ulasan pengunjung secara sistematis.

Penerapan arsitektur MVC membantu pengelolaan sistem yang lebih terorganisir, memudahkan proses pengembangan dan pemeliharaan secara tim. Dari sisi pengguna, website memberikan kemudahan dalam memperoleh informasi; dari sisi admin, sistem ini mendukung pengelolaan data secara efisien melalui fitur CRUD.

Website ini memiliki potensi untuk dikembangkan lebih lanjut, terutama dalam penambahan fitur transaksi online dan sistem pembayaran digital di masa mendatang.

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
