# Stok Harian Kinmart

Aplikasi web mandiri untuk cek stok harian toko sayur Kinmart. Jalan tanpa server dan tanpa Muse — buka `index.html` di browser HP.

## Fitur

- 94 barang baku (awal: Ready 33, Kosong 28, Restok 33)
- Tiap barang punya 3 tombol manual: READY / KOSONG / RESTOK
- Undo sampai 20 langkah + Kembali ke Awal
- Menu Input Hari Ini: centang Kosong dan Restok, lalu Terapkan
- Kirim ke WhatsApp atasan: gabungan Ready + Restok, diurutkan abjad A-Z, dipecah tepat 3 pesan polos (satu nama barang per baris, tanpa judul/penjelasan/emoji). Barang Kosong tidak dikirim.
- Tab Cadangan: Export ke HP (JSON), Export ke Google Drive (via menu Bagikan HP), Export Laporan Hari Ini (TXT), Backup Data Stok (Export/Import JSON)
- Data tersimpan per tanggal di browser HP (localStorage)

## Cara pakai

1. Buka `index.html` di Chrome HP, atau buka lewat GitHub Pages.
2. Tambahkan ke Layar Utama supaya terasa seperti aplikasi.
3. Update status barang, lalu kirim lewat tab Kirim WA.
4. Export backup sesekali dari tab Cadangan, terutama sebelum ganti HP.
