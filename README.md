# Aplikasi Catatan Pribadi Sandi

Aplikasi catatan sederhana berbasis Laravel 11 untuk tugas praktikum.

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Tentang Aplikasi

Aplikasi ini dibangun menggunakan **Laravel 11** untuk memenuhi tugas praktikum manajemen tugas dan kolaborasi kode.

## Fitur
- Catatan harian
- Manajemen tugas
- CRUD operations

## Instalasi

### Requirements
- PHP >= 8.2
- Composer
- MySQL/MariaDB
- XAMPP (untuk development)

### Langkah Instalasi
```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve