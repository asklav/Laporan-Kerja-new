M&R CHECKLIST - PAKET PWA

Agar benar-benar bisa diinstal sebagai aplikasi Chrome (bukan hanya pintasan):
1. Unggah SEMUA isi folder ini ke root repository GitHub Pages yang sama.
2. Pastikan URL utama membuka index.html, dan file berikut tersedia pada URL yang sama:
   /manifest.webmanifest
   /sw.js
   /icons/icon.svg
   /icons/icon-192.png
   /icons/icon-512.png
3. Aktifkan GitHub Pages (Settings > Pages) dan gunakan URL HTTPS.
4. Buka situs di Chrome Android, refresh, tunggu sebentar, lalu menu ⋮ > Instal aplikasi.
   Jika browser menampilkan tombol "Instal Aplikasi" di header, tombol itu juga bisa digunakan.

PENTING: jangan hanya unggah index.html. Manifest dan service worker wajib ikut di-host.
Aplikasi memakai localStorage; data checklist tersimpan di perangkat/browser masing-masing. Backup JSON tetap disarankan.
