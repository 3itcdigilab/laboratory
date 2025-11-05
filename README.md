ProjectHub - UI demo

Deskripsi
---------
Halaman statis sederhana yang meniru tampilan antarmuka pada lampiran: sidebar kiri, topbar, statistik ringkas, dan kartu pengguna.

Files (flat, siap dimasukkan ke GitHub root)
- index.html  — markup utama, termasuk inline SVG logo (tidak perlu assets)
- styles.css  — semua styling
- script.js   — sedikit JS (placeholder)
- README.md   — file ini

Menjalankan (Windows)
----------------------
Cukup buka `index.html` dengan browser. Contoh dari PowerShell:

Start-Process index.html

Atau buka file langsung dari file explorer.

Catatan untuk GitHub
---------------------
- File sudah disimpan lurus di root (tidak ada subfolder).
- Jika ingin deploy ke GitHub Pages: commit ke branch `gh-pages` atau aktifkan GitHub Pages di repo Anda.

Penyesuaian lebih lanjut
-----------------------
- Tambah data dinamis (JSON) dan render lebih banyak kartu pengguna lewat `script.js`.
- Tambah icon set atau gunakan font-icon bila perlu.

Jika mau, saya bisa:
- menambahkan responsive drawer (untuk layar kecil),
- mengubah palet warna supaya lebih cocok dengan brand Anda, atau
- mengekspor desain ke template React/Vue.
