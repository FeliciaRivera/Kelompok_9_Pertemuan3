# Warung Pojok Mba Sofy - Website Informasi Sederhana

Studi kasus perancangan halaman web informasi sederhana untuk UMKM, dikerjakan sebagai tugas kelompok mata kuliah Pemrograman Antarmuka Pengguna.

## Informasi Tugas

- Mata Kuliah: Pemrograman Antarmuka Pengguna
- Kelompok: 9 (SI A)
- Studi Kasus: Opsi B - Katalog Produk / Daftar Harga UMKM

## Anggota Kelompok

| Nama | NIM |
|---|---|
| Deio Castello Sujati | 825250002 |
| Felicia Rivera | 825250003 |
| Muhammad Ubait Dhaifullah | 825250012 |

## Tentang Project Ini

Website ini dibuat untuk Warung Pojok Mba Sofy, sebuah usaha kuliner rumahan yang berlokasi di Gedung P, Kantin Universitas Tarumanagara. Website menampilkan profil usaha, katalog menu beserta daftar harga dalam bentuk tabel, kategori produk, jam operasional, peta lokasi, dan form kontak.

## Fitur Utama

- Struktur halaman semantik: `header`, `nav`, `main`, `article`, `aside`, `footer`.
- Layout multi-kolom menggunakan CSS Grid (`grid-template-columns: 2fr 1fr`), memisahkan konten utama (profil usaha dan tabel menu) dengan sidebar (kategori produk, jam operasional, peta lokasi, dan form kontak).
- Tabel Katalog Menu & Daftar Harga dengan struktur `thead`/`tbody`, penggunaan `colspan` untuk judul tabel dan `rowspan` untuk pengelompokan kategori menu.
- Styling tabel meliputi `border-collapse`, `padding`, `text-align`, zebra-striping (`nth-child(even)`), dan efek hover pada baris.
- Kategori produk ditampilkan dalam grid dua kolom lengkap dengan foto.
- Peta lokasi menggunakan embed Google Maps melalui `iframe`.
- Form kontak dengan kontrol input teks, dropdown (`select`), area teks (`textarea`), dan tombol submit.
- Desain responsif: layout dua kolom berubah menjadi satu kolom pada layar dengan lebar di bawah 800px.

## Teknologi yang Digunakan

- HTML5
- CSS3 (CSS Grid, custom styling tanpa framework tambahan)

## Pembagian Tugas

| Anggota | Bagian yang Dikerjakan |
|---|---|
| Deio Castello Sujati | Struktur dasar halaman: header, nav, bagian Profil Usaha pada article, dan footer. |
| Muhammad Ubait Dhaifullah | Layout multi-kolom (`main.container` dengan grid 2fr/1fr) beserta seluruh isi aside: kategori produk, jam operasional, dan peta lokasi. |
| Felicia Rivera | Tabel Katalog Menu & Daftar Harga, form Hubungi Kami, styling CSS untuk tabel dan form, serta penyesuaian responsive design. |
