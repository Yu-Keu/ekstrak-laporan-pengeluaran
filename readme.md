# 🌊 Sistem Ekstraksi Jurnal & Arus Kas Keuangan Mahad

Aplikasi web _Single Page Application_ (SPA) berbasis client-side murni untuk membantu tim administrasi keuangan Mahad mengekstrak data Laporan Pertanggungjawaban (LPJ) dari file Excel (.xlsx) ke format jurnal Buku Besar & Buku Pembantu, serta merekap arus kas harian secara otomatis.

---

## ✨ Fitur Utama

- **Fitur 1: Ekstraktor LPJ Excel ke Jurnal**
  - Parsing file Excel langsung di browser (tanpa upload ke server/cloud).
  - Pilihan cepat Kode Bidang & Chart of Accounts (COA).
  - Output Buku Besar (ringkasan akun) dan Buku Pembantu (rincian item).
  - Ekspor/salin instan dalam format TSV (siap paste langsung ke spreadsheet).

- **Fitur 2: Rekap Arus Kas Harian**
  - Paste data transaksi dari spreadsheet secara langsung.
  - Mendukung input angka bertanda minus `(100.000)` atau `-100.000` (pelunasan hutang).
  - Perhitungan otomatis Kas Tunai Netto (Kode 1), Kas Bank Netto (Kode 2), dan Grand Total.
  - Normalisasi otomatis untuk sel teks yang memiliki baris baru/enter.

- **Desain & Performa**
  - Antarmuka modern **Bright Coastal / Aqua Glassmorphism**.
  - Tipografi rapi menggunakan **Plus Jakarta Sans** & **JetBrains Mono**.
  - 100% Client-Side (privasi data aman, bisa berjalan offline).
