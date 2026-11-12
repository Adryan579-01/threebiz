# ThreeBiz (Mthree Business Suite)

Request Form, Cash Advance, Reimbursement, Expense Accounts, Saldo Rincian, Catatan Nilai Saldo
&mdash; aplikasi kas kecil PT. MAHIRA MITRA MANDIRI (PT. M THREE), Windows.

Repo ini memuat **rilis & pembaruan** ThreeBiz. Kode sumber aplikasi tidak tersedia di repo ini;
aplikasi terkemas dalam `ThreeBiz.exe` (installer / portable) dengan modul terenkripsi
di `_internal/appcore.bin`.

## Unduh terbaru

Buka [halaman rilis](https://github.com/Adryan579-01/threebiz/releases) dan ambil salah satu:

- **`ThreeBiz-Setup-<versi>-clean.exe`** &mdash; installer (disarankan). Memasang aplikasi per
  pengguna di `%LOCALAPPDATA%\Programs\ThreeBiz`, tanpa hak Administrator, dan membuat shortcut
  Start Menu. Data tersimpan terpisah di `%LOCALAPPDATA%\ThreeBiz\data` sehingga pembaruan
  **tidak pernah menghapus data** Anda.
- **`ThreeBiz-Portable-<versi>.zip`** &mdash; ekstrak seluruh isi ZIP ke folder mana saja,
  jalankan `ThreeBiz.exe` di dalamnya (jangan memindahkan `.exe` sendirian).

Setiap berkas dilengkapi `.sha256` untuk memverifikasi integritas unduhan.

## Yang baru di 0.1.88

- **Sidebar terbuka seketika** begitu pointer diarahkan ke menu slide bar kiri
  (jeda turun dari ±0,7 detik menjadi ±0,1&ndash;0,2 detik).
- **Pemuatan latar**: pembacaan database, rekap/grafik, dan pembuatan PDF/CSV berjalan di
  thread latar; jendela tetap mulus saat data besar dimuat.
- **Logo baru M THREE / MAHIRA MITRA MANDIRI** pada menu slide bar; banner, ikon jendela,
  ikon taskbar, dan ikon `.exe` tetap memakai logo ThreeBiz lama.
- **Tombol Pratinjau Form** di halaman Reimbursement dan perbaikan pratinjau foto.

Aplikasi **tanpa login** sejak 0.1.78: semua menu terbuka dan data tersimpan lokal di
folder data aplikasi.

## Update otomatis

ThreeBiz memeriksa rilis terbaru di repo ini saat dibuka. Bila ada versi baru, aplikasi
menawarkan pembaruan dan memasangnya senyap tanpa menyentuh data. Versi terinstal tertera di
kaki menu slide bar (`V. <versi> by Chameleon`).

## Rilis lama

Riwayat rilis dari v0.1.65 hingga v0.1.84 (per 12 November 2026) dirilis di repositori
sebelumnya dan **tidak lagi tersedia**. Unduh selalu dari [rilis terbaru](https://github.com/Adryan579-01/threebiz/releases/latest).

---
&copy; 2026 PT. MAHIRA MITRA MANDIRI. All rights reserved.
