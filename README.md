# Creator Studio — demo frontend

## Isi
- `index.html`: aplikasi satu halaman
- `qris.png`: opsional, gambar QRIS yang disediakan pemilik
- `vercel.json`: konfigurasi deploy sederhana

## Jalankan lokal
Buka `index.html` di browser atau gunakan extension Live Server di Visual Studio Code.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub.
2. Upload `index.html`, `vercel.json`, dan `qris.png` (jika memang QRIS tersebut benar milik Anda).
3. Buka Settings → Pages → Deploy from a branch → pilih `main` dan folder `/root`.
4. Tunggu URL Pages muncul.

## Deploy ke Vercel
1. Push file ke repository GitHub.
2. Masuk Vercel dan pilih Add New → Project.
3. Import repository, Framework Preset pilih Other, Build Command kosong, Output Directory `.`.
4. Klik Deploy.

## PENTING — sebelum produksi
Ini prototipe frontend-only. Akun, status Pro, harga, dan permintaan pembayaran disimpan di `localStorage` browser, bukan server. Password admin demo `admin / admin1245` terlihat di kode dan hanya untuk uji coba; siapa pun dapat menirunya. Jangan pakai untuk layanan publik atau menerima uang sungguhan sampai autentikasi backend (Supabase/Firebase), database, verifikasi pembayaran server-side, aturan akses admin, kebijakan privasi, dan halaman syarat layanan diterapkan. QRIS yang diberikan pada percakapan menampilkan merchant “TOKO GAME ONLINE, TGLSR”; pastikan QR itu benar milik penerima pembayaran sebelum digunakan.
