NOVA OS 0.2 — PWA package

Isi:
- index.html: desktop NOVA OS
- manifest.json: identitas dan mode aplikasi
- sw.js: cache offline dasar
- icons/: ikon aplikasi

PENTING:
PWA tidak bisa dipasang dengan mode standalone hanya dengan membuka file HTML lokal.
Upload seluruh isi folder ini ke hosting HTTPS (misalnya GitHub Pages atau Netlify).
Setelah online, buka alamat NOVA OS di Chrome Android:
1. Buka menu ⋮.
2. Pilih "Install app" atau "Tambahkan ke layar utama".
3. Jalankan NOVA OS dari ikon yang muncul di layar utama.

Saat dibuka dari ikon, address bar dan toolbar Chrome tidak tampil.
Service worker membuat file inti dapat dibuka lagi saat offline setelah kunjungan online pertama.
