# Keuangan Saya (aplikasi web / PWA)

Isi paket:
- index.html — aplikasinya (satu file)
- manifest.webmanifest, sw.js — agar bisa dipasang dan jalan offline
- icon-*.png, apple-touch-icon.png — ikon aplikasi

## Cara memasang online (gratis, pilih salah satu)
**Netlify (paling mudah):** buka app.netlify.com/drop, lalu seret folder hasil ekstrak zip ini ke halaman itu. Kamu langsung mendapat alamat web.
**GitHub Pages:** buat repositori baru, unggah semua file di folder ini, lalu aktifkan Pages di Settings > Pages.
**Vercel / Cloudflare Pages:** unggah folder yang sama.

Alamatnya harus HTTPS (semua layanan di atas sudah HTTPS). File tidak bisa dipasang kalau hanya dibuka dari penyimpanan ponsel.

## Memasang di ponsel
- Android (Chrome): buka alamatnya, ketuk menu titik tiga, lalu "Pasang aplikasi".
- iPhone (Safari): ketuk tombol Bagikan, lalu "Tambah ke Layar Utama".

## Data dan cadangan
Data tersimpan di perangkat. Tidak ada sinkronisasi otomatis di versi ini. Untuk memindahkan data antar perangkat: ikon ⚙ > Cadangan data > Simpan (mengunduh file .json), lalu di perangkat lain ⚙ > Muat dan pilih file itu. Buat cadangan berkala, karena menghapus data browser juga menghapus data aplikasi.

## Menjadikan APK Android (opsional)
Setelah aplikasi online, buka pwabuilder.com, masukkan alamat webnya, lalu pilih Android untuk mengunduh paket APK.
