# SiSatu (Sistem Informasi RW 01) - Frontend Demo

Website demo portofolio frontend untuk Sistem Informasi RW 01 (SiSatu).
Dibuat sebagai aplikasi statis responsif tanpa backend & database untuk kemudahan deployment di Vercel / GitHub Pages.

## Halaman Tersedia
- **`public/index.html`** : Landing Page publik & ringkasan fitur
- **`public/login.html`** : Halaman Masuk / Login Demo
- **`public/dashboard.html`** : Dashboard Admin & Statistik RW
- **`public/data-warga.html`** : Tabel Informasi Data Kependudukan RW 01
- **`public/bansos.html`** : Sistem Pendukung Keputusan (DSS) Rekomendasi Bansos
- **`public/iuran.html`** : Administrasi Buku Kas & Iuran Warga

## Cara Menjalankan Lokal
Cukup buka file `public/index.html` langsung di browser, atau gunakan Live Server / HTTP Server:
```bash
npx serve public
```

## Deployment ke Vercel
Repository ini sudah dilengkapi dengan file `vercel.json` dan siap di-deploy secara instan.
Output directory diatur ke folder `public`.
