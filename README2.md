<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B35,50:F7C59F,100:FF6B35&height=220&section=header&text=🎡%20Wonderland%20Samarinda&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Platform%20Digital%20Taman%20Hiburan%20Kota%20Samarinda&descAlignY=58&descSize=17&descColor=ffe8d6" />

</div>

<div align="center">

<br/>

[![PHP](https://img.shields.io/badge/PHP-8.1-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-42B883?style=for-the-badge&logo=vuedotjs&logoColor=white)](https://vuejs.org)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![Laragon](https://img.shields.io/badge/Laragon-Ready-45A3E5?style=for-the-badge&logo=laragon&logoColor=white)](https://laragon.org)
[![MVC](https://img.shields.io/badge/Pattern-MVC-E34F26?style=for-the-badge)](/)

<br/><br/>

[![Proyek Akhir](https://img.shields.io/badge/🎓%20Proyek%20Akhir-PRAKTISI%202026%20Genap-FF6B35?style=flat-square)](/)
[![Universitas](https://img.shields.io/badge/🏛️%20Universitas-Mulawarman-2C5F8A?style=flat-square)](/)
[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=flat-square)](/)

<br/>

---

### 🌐 [Live Demo](#) &nbsp;·&nbsp; 📖 [Dokumentasi](#-deskripsi-aplikasi) &nbsp;·&nbsp; 🐛 [Report Bug](#) &nbsp;·&nbsp; ✨ [Request Feature](#)

---

</div>

<br/>

## 📖 Deskripsi Aplikasi

<img align="right" width="380" src="https://capsule-render.vercel.app/api?type=rect&color=0:FF6B35,100:F7C59F&height=180&text=Wonderland%0ASamarinda&fontSize=28&fontColor=fff&fontAlignY=45&desc=Digital%20Theme%20Park%20Platform&descSize=13&descColor=ffe8d6&descAlignY=72" />

**Wonderland Samarinda** adalah platform digital manajemen taman hiburan yang dikembangkan sebagai solusi nyata digitalisasi sektor pariwisata di Kota Samarinda.

Dibangun menggunakan **PHP Native** dengan arsitektur **MVC (Model-View-Controller)**, platform ini mengintegrasikan pengalaman pengunjung, sistem reservasi online, dan panel administrasi terpadu — semuanya dalam satu aplikasi web yang responsif dan interaktif.

> *Dikembangkan sebagai Proyek Akhir PRAKTISI 2026 Genap, bermitra langsung dengan objek wisata Wonderland Samarinda.*

<br clear="right"/>

<br/>

<div align="center">

```
╔══════════════════╦══════════════════╦══════════════════╗
║  🌐 Pengunjung   ║   👤 User Login  ║    🔐 Admin      ║
╠══════════════════╬══════════════════╬══════════════════╣
║ Info taman &     ║ Reservasi tiket  ║ Kelola semua     ║
║ wahana           ║ online           ║ data taman       ║
║                  ║                  ║                  ║
║ Galeri & ulasan  ║ Upload foto      ║ Moderasi konten  ║
║ pengunjung       ║ kunjungan        ║ & ulasan         ║
║                  ║                  ║                  ║
║ Cek pricelist    ║ Tulis review &   ║ Dashboard &      ║
║ & promo          ║ rating wahana    ║ statistik        ║
╚══════════════════╩══════════════════╩══════════════════╝
```

</div>

<br/>

---

## ✨ Fitur Website

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Halaman Publik
- 🏠 **Beranda** — Hero section, statistik taman, galeri & ulasan terbaru
- 🎢 **Detail Wahana** — Foto, deskripsi lengkap & info tiap wahana
- 💰 **Pricelist** — Harga tiket dan paket kunjungan

### 👤 Fitur User
- 📊 **Dashboard** — Ringkasan aktivitas & riwayat kunjungan
- 🎟️ **Reservasi** — Pemesanan tiket masuk secara online
- 📷 **Upload Foto** — Unggah foto kenangan kunjungan
- ⭐ **Ulasan & Rating** — Review untuk setiap wahana

</td>
<td width="50%" valign="top">

### 🔐 Panel Admin
- 📈 **Dashboard** — Statistik & ringkasan data real-time
- 🎠 **Manajemen Wahana** — CRUD wahana & atraksi
- 📋 **Manajemen Reservasi** — Konfirmasi pemesanan tiket
- 💬 **Moderasi Ulasan** — Review & filter ulasan pengunjung
- 🏷️ **Pricelist & Promo** — Kelola harga dan promo aktif
- 🏗️ **Fasilitas** — Info fasilitas taman
- 🖼️ **Galeri** — Foto resmi & kiriman pengunjung

### 🛡️ Keamanan
- 🔑 CSRF Token · 🔒 Session Auth
- 🚫 Profanity Filter · ✅ Server Validation

</td>
</tr>
</table>

<br/>

---

## 🗂️ Struktur Direktori

```
📦 wonderland-samarinda
 ┃
 ┣ 📂 app
 ┃ ┣ 📂 controllers
 ┃ ┃ ┣ 📄 AdminController.php        ← Logika panel admin
 ┃ ┃ ┣ 📄 AuthController.php         ← Login, register, logout
 ┃ ┃ ┣ 📄 GaleriController.php       ← Manajemen galeri foto
 ┃ ┃ ┣ 📄 UlasanController.php       ← Sistem review & rating
 ┃ ┃ ┣ 📄 UserController.php         ← Dashboard & aksi user
 ┃ ┃ ┗ 📄 WahanaController.php       ← Data wahana & atraksi
 ┃ ┃
 ┃ ┣ 📂 models
 ┃ ┃ ┣ 📄 GaleriModel.php
 ┃ ┃ ┣ 📄 ReservasiModel.php
 ┃ ┃ ┣ 📄 UlasanModel.php
 ┃ ┃ ┣ 📄 UserModel.php
 ┃ ┃ ┗ 📄 WahanaModel.php
 ┃ ┃
 ┃ ┣ 📂 views
 ┃ ┃ ┣ 📂 admin                      ← View panel admin
 ┃ ┃ ┣ 📂 auth                       ← Login & Register
 ┃ ┃ ┣ 📂 public                     ← Halaman publik
 ┃ ┃ ┗ 📂 user                       ← Dashboard user
 ┃ ┃
 ┃ ┗ 📂 helpers
 ┃   ┣ 📄 image_helper.php
 ┃   ┗ 📄 profanity_filter.php
 ┃
 ┣ 📂 assets                         ← CSS, JS, gambar statis
 ┣ 📂 config
 ┃ ┗ 📄 koneksi.php                  ← Konfigurasi database
 ┣ 📂 uploads                        ← Foto upload dari user
 ┣ 📄 index.php                      ← Entry point (Front Controller)
 ┗ 🗄️ wonderlands.sql                ← Dump database lengkap
```

<br/>

---

## 🗄️ Skema Database

<div align="center">

Database **`wonderlands`** — 12 Tabel

| # | Tabel | Keterangan |
|:---:|:---|:---|
| 01 | `users` | Akun & data pengunjung terdaftar |
| 02 | `admin` | Akun pengelola / administrator |
| 03 | `wahana` | Data wahana & atraksi taman |
| 04 | `reservasi` | Pemesanan tiket masuk |
| 05 | `tiket` | Detail tiket per transaksi reservasi |
| 06 | `ulasan` | Review & rating dari pengunjung |
| 07 | `galeri` | Galeri foto resmi taman |
| 08 | `foto_pengunjung` | Foto kiriman pengunjung |
| 09 | `pricelist` | Daftar harga tiket & paket |
| 10 | `promo` | Promo & diskon aktif |
| 11 | `fasilitas` | Informasi fasilitas taman |
| 12 | `kontak_pesan` | Pesan masuk dari form kontak |

</div>

<br/>

---

## ⚙️ Instalasi

### Prasyarat

| Tools | Keterangan |
|:---|:---|
| [Laragon](https://laragon.org/) | Local server (PHP 8.1+ & MySQL 8.0+) |
| Browser Modern | Chrome / Firefox / Edge |
| [Git](https://git-scm.com/) | Untuk clone repository |

<br/>

### Langkah Instalasi

**① Clone Repository**
```bash
git clone https://github.com/username/wonderland-samarinda.git
```

**② Pindahkan ke folder www Laragon**
```bash
C:/laragon/www/wonderland-samarinda/
```

**③ Import Database**
```
1. Buka       →  http://localhost/phpmyadmin
2. Buat DB    →  nama: wonderlands
3. Import     →  upload wonderlands.sql → klik Go
```

**④ Konfigurasi Koneksi**

Edit `config/koneksi.php`:
```php
$host = "localhost";
$user = "root";
$pass = "";            // Laragon default: kosong
$db   = "wonderlands";
```

**⑤ Akses Aplikasi**
```
🌐  http://localhost/wonderland-samarinda/
```

<br/>

### 🚪 Role & Akses

<div align="center">

| Role | URL | Cara Masuk |
|:---:|:---|:---|
| 👥 **Publik** | `http://localhost/wonderland-samarinda/` | Langsung akses, tanpa login |
| 👤 **User** | `/?page=register` → `/?page=login` | Daftar akun baru |
| 🔐 **Admin** | `/?page=login` | Cek tabel `admin` di phpMyAdmin |

</div>

<br/>

---

## 🧱 Arsitektur MVC

```
  Browser / Client
       │
       │  HTTP Request (?page=xxx)
       ▼
  ┌────────────────────────────────────┐
  │           index.php                │
  │        (Front Controller)          │
  │     routing via switch($page)      │
  └──────────────┬─────────────────────┘
                 │
                 ▼
  ┌────────────────────────────────────┐
  │            Controller              │
  │   AdminController / AuthController │
  │   UserController / WahanaController│
  └──────────┬──────────┬─────────────┘
             │          │
     ┌───────▼───┐  ┌───▼────────────┐
     │   Model   │  │      View      │
     │ Query DB  │  │  Render HTML   │
     └───────┬───┘  └───────┬────────┘
             │              │
     ┌───────▼───┐          │
     │  Database │          ▼
     │  (MySQL)  │    Response HTML
     └───────────┘   ke Browser
```

<br/>

---

## 🛠️ Tech Stack

<div align="center">

<br/>

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-42B883?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Laragon](https://img.shields.io/badge/Laragon-45A3E5?style=for-the-badge&logo=laragon&logoColor=white)

<br/><br/>

| Teknologi | Versi | Fungsi |
|:---:|:---:|:---|
| PHP | 8.1 | Backend, routing, logika bisnis |
| MySQL | 8.0 | Penyimpanan data utama |
| MySQLi | — | Driver koneksi PHP ↔ MySQL |
| Vue.js | 3.x | Reaktivitas & interaktivitas UI |
| Bootstrap | 5.x | Komponen UI & layout responsif |
| JavaScript | ES6+ | Logika frontend & DOM manipulation |
| Laragon | Latest | Local development server |

</div>

<br/>

---

## 👥 Tim Pengembang

<div align="center">

> 🎓 **Proyek Akhir PRAKTISI 2026 Genap** — Mata Kuliah Pemrograman Web
> Bermitra dengan objek wisata **Wonderland Samarinda**, Kalimantan Timur

<br/>

| Avatar | Nama | NIM | Peran |
|:---:|:---|:---:|:---:|
| <img src="https://ui-avatars.com/api/?name=A1&background=FF6B35&color=fff&size=40&rounded=true" width="40"/> | *(nama anggota 1)* | *(NIM)* | Backend & Database |
| <img src="https://ui-avatars.com/api/?name=A2&background=42B883&color=fff&size=40&rounded=true" width="40"/> | *(nama anggota 2)* | *(NIM)* | Frontend & UI/UX |
| <img src="https://ui-avatars.com/api/?name=A3&background=7952B3&color=fff&size=40&rounded=true" width="40"/> | *(nama anggota 3)* | *(NIM)* | Admin Panel |
| <img src="https://ui-avatars.com/api/?name=A4&background=4479A1&color=fff&size=40&rounded=true" width="40"/> | *(nama anggota 4)* | *(NIM)* | Dokumentasi & Testing |

</div>

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B35,50:F7C59F,100:FF6B35&height=120&section=footer&fontColor=ffffff&fontSize=16" />

**🎡 Wonderland Samarinda**

*Dibuat dengan ❤️ oleh Tim Proyek Akhir PRAKTISI 2026 Genap*
*Universitas Mulawarman — Samarinda, Kalimantan Timur 🌴*

<br/>

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-FF6B35?style=flat-square)
![Universitas Mulawarman](https://img.shields.io/badge/Unmul-2026-2C5F8A?style=flat-square)
![Academic Project](https://img.shields.io/badge/Academic-Project-42B883?style=flat-square)

</div>
