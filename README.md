# MBSTORE

Aplikasi pembukuan konter pulsa berbasis PWA, dapat dipasang di Android dan digunakan offline setelah dibuka pertama kali melalui HTTPS.

## Isi folder
- `index.html` — aplikasi utama.
- `manifest.webmanifest` — identitas aplikasi untuk instalasi.
- `sw.js` — cache offline.
- `README.md` — panduan.

## Cara memasang di HP Android
1. Upload ke repository GitHub dengan keempat file berada di root repository.
2. Buka **Settings → Pages**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
3. Tunggu GitHub Pages menerbitkan alamat HTTPS.
4. Buka alamat tersebut di Chrome Android, pilih menu ⋮ → **Tambahkan ke layar utama** / **Install app**.
5. Buka aplikasi sekali saat internet tersedia. Setelah cache terbentuk, aplikasi dapat digunakan offline.

## Fitur
- Modal awal terpisah: Cash, GoPay, DANA, SeaBank, Pulsa DataKu.
- Penjualan dengan harga jual dan modal produk; laba dihitung otomatis.
- Pengeluaran, tambah modal, dan transfer antar akun.
- Saldo akun dan total saldo dihitung otomatis.
- Laporan per tanggal, closing harian, riwayat transaksi.
- Backup/restore JSON dan ekspor CSV.
- Data tidak dihapus saat berganti tanggal.

## Catatan penting
Data disimpan di penyimpanan browser pada perangkat (localStorage). Backup JSON perlu dilakukan rutin dan disimpan di tempat aman. Fitur sinkronisasi cloud otomatis belum tersedia. Jangan menghapus data browser/aplikasi sebelum membuat backup. Versi ini adalah PWA yang dapat dipasang dari Chrome, bukan APK native yang ditandatangani.
