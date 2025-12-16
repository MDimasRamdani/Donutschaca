🍩 Donutschaca – Web-Based Donut Ordering System
<p align="center"> <img src="donut.png" width="120" alt="Donutschaca Logo"> </p> <p align="center"> <b>Web Application for UMKM Donut Ordering</b><br> Built with PHP Native, MySQL & Bootstrap </p> <p align="center"> <img src="https://img.shields.io/badge/PHP-Native-blue?logo=php"> <img src="https://img.shields.io/badge/MySQL-Database-orange?logo=mysql"> <img src="https://img.shields.io/badge/Bootstrap-Frontend-purple?logo=bootstrap"> <img src="https://img.shields.io/badge/Status-Active-success"> </p>

🚀 About The Project

Donutschaca adalah aplikasi pemesanan kue berbasis web yang dikembangkan untuk membantu UMKM Donutschaca dalam mengelola proses bisnis secara digital, mulai dari manajemen produk, pemesanan, pembayaran, hingga laporan penjualan.

Aplikasi ini dibangun menggunakan PHP Native tanpa framework backend untuk memperkuat pemahaman logika pemrograman dan struktur sistem informasi berbasis web.

👥 User Roles & Features
Aplikasi ini memiliki 3 aktor utama dengan hak akses yang berbeda:
👨‍💼 Admin
<p align="center"> <img src="img/gambarweb/Admin/DashboardAdmin.png" width="600"> </p>
Fungsi Admin:
- Mengelola data produk
- Mengelola pemesanan pelanggan
- Mengelola pembayaran
- Melihat bukti pembayaran
- Melihat riwayat pemesanan

👑 Owner
<p align="center"> <img src="img/gambarweb/Owner/Dashboard.png" width="600"> </p>
Fungsi Owner:
- Melihat laporan produk
- Melihat laporan pemesanan
- Melihat laporan pembayaran
- Melihat pendapatan penjualan
- Mengelola akun admin

🧑‍💻 Pelanggan
<p align="center"> <img src="img/gambarweb/Pelanggan/Dashboard.png" width="600"> </p>
Fungsi Pelanggan:
- Melihat daftar produk
- Melakukan pemesanan produk
- Melakukan Transaksi Pembayaran

🛠️ Tech Stack
<p align="center"> <img src="https://skillicons.dev/icons?i=php,html,css,js,bootstrap,mysql,git,github,vscode" /> </p>
Detail:
- Backend : PHP Native
- Frontend : HTML, CSS, JavaScript
- UI Framework : Bootstrap
- Database : MySQL
- Server : Apache (XAMPP)

📁 Project Structure
htdocs/
├── admin/        # Halaman & fitur Admin
├── owner/        # Halaman & laporan Owner
├── pelanggan/    # Halaman pelanggan
├── koneksi/      # Konfigurasi database
├── bukti/        # Bukti pembayaran
├── img/          # Asset & screenshot sistem
├── donut.png     # Logo aplikasi
└── index.php     # Entry point aplikasi

⚙️ Installation Guide

1️⃣ Clone repository

git clone https://github.com/username/donutschaca.git


2️⃣ Pindahkan ke htdocs

C:/xampp/htdocs/donutschaca


3️⃣ Buat database MySQL

Nama database: donutschaca

Import file .sql (jika tersedia)

4️⃣ Konfigurasi database
File:

/koneksi/koneksi.php

$host = "localhost";
$user = "root";
$pass = "";
$db   = "donutschaca";


5️⃣ Jalankan aplikasi

http://localhost/donutschaca

🔐 Access Control
Role	Permissions
Admin	Produk, Pesanan, Pembayaran
Owner	Laporan & Manajemen Admin
Pelanggan	Produk & Pemesanan

📌 Notes
Folder bukti/ harus memiliki permission read & write
Direkomendasikan PHP versi 7.4+

🎓 Academic Context
Project ini dikembangkan sebagai bagian dari:
- Tugas akhir / Skripsi
- Implementasi Sistem Informasi UMKM
- Studi kasus aplikasi pemesanan berbasis web

👨‍🎓 Developer
Muhamad Dimas Ramdani Fitrian Syaputra
Informatics Engineering Student
Focused on Networking, Web Development & PHP Native

“Building systems is not just about code, but about solving real problems.”

⭐ If you find this project useful, don’t forget to give it a star!
