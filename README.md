<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

rability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

# 🏫 CRUD Laravel + Filament — SMP Mentari

Modul praktikum **Pemrograman Berbasis Web (PBW)** ini membimbing mahasiswa dalam membangun aplikasi **CRUD Laravel + Filament v4** bertema *SMP Mentari*.  
Hasil akhir berupa **panel admin** (Filament) dan **halaman publik sederhana** untuk menampilkan kegiatan sekolah.

---

## 🎯 Tujuan Praktikum
Mahasiswa mampu:
- Membuat proyek Laravel dari nol.
- Menginstal dan mengonfigurasi Filament v4.
- Mendesain model dan migrasi data (Kegiatan & Siswa).
- Menghasilkan CRUD otomatis menggunakan Filament Resource.
- Membuat halaman depan (public page) untuk menampilkan data kegiatan.

---

## 🧰 Prasyarat & Peralatan
| Software | Versi Minimal | Keterangan |
|-----------|----------------|-------------|
| PHP | 8.2+ | Wajib |
| Composer | 2.x | Dependency Manager |
| Node.js | 18+ | Untuk build front-end |
| MySQL / MariaDB | — | Database |
| Git | (opsional) | Version Control |

> **Catatan:** Gunakan **Filament v4** (mendukung Laravel 11+) untuk kompatibilitas dengan Tailwind v4.

---

## ⚙️ Langkah Instalasi

### 1️⃣ Buat Proyek Laravel Baru
```bash
composer create-project laravel/laravel smpmentari_filament
cd smpmentari_filament
php artisan serve
