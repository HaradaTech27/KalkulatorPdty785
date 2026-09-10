# Kalkulator Produktiviti HD785

Aplikasi HTML5 + CSS3 + JavaScript vanilla, tanpa CDN/framework/database/server untuk kalkulasi.

## File
- `index.html` — aplikasi utama
- `hd785.jpg` — foto HD785 dari referensi yang diberikan
- `manifest.json` — konfigurasi PWA
- `service-worker.js` — cache offline PWA
- `icon-192.png` / `icon-512.png` — ikon PWA

## Menjalankan
1. Untuk kalkulator biasa: buka `index.html` langsung.
2. Untuk mengaktifkan service worker/PWA: jalankan folder ini melalui `localhost` atau HTTPS.
   Contoh sederhana: gunakan server lokal apa pun yang tersedia di komputer.
3. Setelah aplikasi dibuka sekali melalui localhost/HTTPS, asset utama akan dicache oleh service worker dan dapat digunakan kembali tanpa koneksi.

## Catatan
- Kalkulasi berjalan 100% lokal di browser.
- Tidak ada dependency CDN.
- Jarak harus cocok tepat pada tabel, maksimal 1 angka desimal. Tidak ada interpolasi.
- 0.1 km memang tidak tersedia pada tabel.
- Kapasitas vessel dikunci 42 BCM.
- Footer mengikuti instruksi terakhir: `By NRP: 521904`.
