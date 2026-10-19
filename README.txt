SUARA — Website Prototype

CARA MENJALANKAN
1. Ekstrak file ZIP.
2. Buka folder suara-website.
3. Klik dua kali index.html untuk membukanya di browser (Chrome/Edge).

CARA EDIT MANUAL
- Teks, nama campaign, angka demo, dan struktur: buka index.html dengan VS Code atau Notepad.
- Desain/warna: cari bagian <style> di bagian atas file.
- Konten campaign dan Impact Tracker: cari bagian HTML dengan id campaign / impact.
- Data status tracker: cari const data di bagian <script>.
- Level dan ambang badge: cari const levels di bagian <script>.
- Perhitungan alokasi: fungsi calcSplit dan bagian Siklus Dana SUARA.
- Logo saat ini berupa huruf S sebagai placeholder; dapat diganti logo final kelompok.

CATATAN
Ini adalah prototipe front-end. Tombol donasi hanya mensimulasikan transaksi dan progres level tersimpan di browser lokal (localStorage). Tidak ada payment gateway, database, akun login, atau penyaluran dana sungguhan. Nama, nominal, status, dan tanggal campaign adalah data ilustratif. Sebelum digunakan publik, perlu backend, kebijakan privasi, verifikasi penerima, sistem admin, dan integrasi pembayaran resmi.
