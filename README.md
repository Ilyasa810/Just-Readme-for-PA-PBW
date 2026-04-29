<div align="center">

<img src="https://img.shields.io/badge/PHP-8.1-777BB4?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/MVC-Architecture-E34F26?style=for-the-badge" />
<img src="https://img.shields.io/badge/XAMPP-Compatible-FB7A24?style=for-the-badge&logo=apache&logoColor=white" />

# 🎡 Wonderland Samarinda

**Website manajemen taman hiburan berbasis PHP Native dengan arsitektur MVC**

*Tugas UTS — Mata Kuliah Pemrograman Web | Universitas Mulawarman*

</div>

---

## 📋 Deskripsi

Wonderland Samarinda adalah aplikasi web manajemen taman hiburan yang dibangun menggunakan PHP Native dengan pola arsitektur **MVC (Model-View-Controller)**. Website ini menyediakan antarmuka untuk pengunjung dan panel administrasi untuk pengelola taman.

---

## ✨ Fitur Utama

### 🌐 Halaman Publik
- **Home** — Landing page dengan informasi taman, galeri, dan ulasan pengunjung
- **Detail Wahana** — Halaman detail tiap wahana beserta foto dan deskripsi
- **Pricelist** — Daftar harga tiket dan paket kunjungan

### 👤 Fitur User (Setelah Login)
- **Dashboard User** — Ringkasan aktivitas dan data pribadi
- **Reservasi** — Pemesanan tiket secara online
- **Upload Foto** — Pengunjung dapat mengunggah foto kunjungan mereka
- **Ulasan** — Sistem review dan rating wahana

### 🔐 Panel Admin
- **Dashboard Admin** — Statistik kunjungan dan ringkasan data
- **Manajemen Wahana** — CRUD data wahana (nama, foto, deskripsi)
- **Manajemen Reservasi** — Kelola pemesanan tiket masuk
- **Manajemen Ulasan** — Moderasi ulasan pengunjung
- **Pricelist** — Kelola daftar harga
- **Fasilitas** — Kelola informasi fasilitas taman
- **Foto Pengunjung** — Kelola galeri foto dari pengunjung

### 🛡️ Keamanan
- CSRF Token pada setiap form autentikasi
- Session-based login & logout
- Filter kata tidak pantas pada ulasan (Profanity Filter)
- Validasi input sisi server

---

## 🗂️ Struktur Direktori

```
wonderland_fixed/
├── app/
│   ├── controllers/
│   │   ├── AdminController.php
│   │   ├── AuthController.php
│   │   ├── GaleriController.php
│   │   ├── UlasanController.php
│   │   ├── UserController.php
│   │   └── WahanaController.php
│   ├── models/
│   │   ├── GaleriModel.php
│   │   ├── ReservasiModel.php
│   │   ├── UlasanModel.php
│   │   ├── UserModel.php
│   │   └── WahanaModel.php
│   ├── views/
│   │   ├── admin/          # View panel admin
│   │   ├── auth/           # Login & Register
│   │   ├── public/         # Halaman publik
│   │   └── user/           # Dashboard user
│   └── helpers/
│       ├── image_helper.php
│       └── profanity_filter.php
├── assets/
│   ├── css/
│   └── wahana/
├── config/
│   └── koneksi.php
├── uploads/                # Foto yang diupload user
├── index.php               # Entry point (Front Controller)
└── wonderlands.sql         # File database
```

---

## 🗄️ Skema Database

Database `wonderlands` terdiri dari **12 tabel**:

| Tabel | Keterangan |
|---|---|
| `users` | Data akun pengunjung |
| `admin` | Data akun admin |
| `wahana` | Data wahana / atraksi |
| `reservasi` | Data pemesanan tiket |
| `tiket` | Detail tiket reservasi |
| `ulasan` | Review dan rating dari pengunjung |
| `galeri` | Galeri foto resmi taman |
| `foto_pengunjung` | Foto yang diunggah pengunjung |
| `pricelist` | Daftar harga tiket |
| `promo` | Data promo aktif |
| `fasilitas` | Informasi fasilitas taman |
| `kontak_pesan` | Pesan dari form kontak |

---

## ⚙️ Instalasi & Konfigurasi

### Prasyarat
- XAMPP (PHP 8.1+, MySQL 8.0+)
- Browser modern

### Langkah Instalasi

**1. Clone / Ekstrak Project**
```bash
# Clone repo
git clone https://github.com/username/wonderland-samarinda.git

# Atau ekstrak zip langsung ke folder htdocs XAMPP
```

**2. Pindahkan ke htdocs**
```
C:/xampp/htdocs/wonderland_fixed/
```

**3. Import Database**
- Buka `http://localhost/phpmyadmin`
- Buat database baru bernama `wonderlands`
- Klik **Import** → pilih file `wonderlands.sql` → klik **Go**

**4. Konfigurasi Koneksi Database**

Edit file `config/koneksi.php`:
```php
$host = "localhost";
$user = "root";
$pass = "";          // Sesuaikan password MySQL kamu
$db   = "wonderlands";
```

**5. Jalankan Website**
```
http://localhost/wonderland_fixed/
```

---

## 🚀 Cara Akses

| Role | URL | Akses |
|---|---|---|
| Publik | `http://localhost/wonderland_fixed/` | Tanpa login |
| User | `?page=login` | Daftar akun baru |
| Admin | `?page=login` | Gunakan akun admin dari database |

> **Catatan:** Akun admin sudah tersedia di file SQL. Cek tabel `admin` di phpMyAdmin setelah import.

---

## 🧱 Arsitektur MVC

```
Request (URL ?page=xxx)
        │
        ▼
   index.php (Front Controller)
        │
        ├── Routing via switch($page)
        │
        ▼
   Controller (misal: WahanaController)
        │
        ├── Memanggil Model untuk data
        │         │
        │         ▼
        │      Model ←→ Database (MySQLi)
        │
        └── Memanggil View untuk tampilan
                  │
                  ▼
              Response HTML
```

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Versi | Kegunaan |
|---|---|---|
| PHP | 8.1 | Backend & logika bisnis |
| MySQL | 8.0 | Database utama |
| MySQLi | — | Koneksi database |
| HTML/CSS | 5/3 | Struktur & tampilan |
| JavaScript | ES6 | Interaktivitas frontend |
| Bootstrap | 5.x | Komponen UI |
| XAMPP | — | Local development server |

---

## 👥 Tim Pengembang

> Proyek ini dikerjakan sebagai tugas kelompok Ujian Tengah Semester (UTS) mata kuliah Pemrograman Web.

| Nama | NIM | Peran |
|---|---|---|
| *(nama anggota)* | *(NIM)* | *(peran, misal: Backend/DB)* |
| *(nama anggota)* | *(NIM)* | *(peran, misal: Frontend)* |
| *(nama anggota)* | *(NIM)* | *(peran, misal: Admin Panel)* |

---

## 📝 Lisensi

Proyek ini dibuat untuk keperluan akademik. Tidak untuk digunakan secara komersial.

---

<div align="center">

Made with ❤️ for **Wonderland Samarinda**

*Universitas Mulawarman — Pemrograman Web*

</div>
