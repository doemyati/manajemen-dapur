# Manajemen Dapur SMP IT Baitul Muslim

Frontend statis untuk aplikasi manajemen operasional dapur sekolah.

## Status
Ini adalah tahap awal publikasi antarmuka. Integrasi database Google Spreadsheet dan autentikasi server belum dikonfigurasi.

## Keamanan
- Jangan menyimpan password, token, API key, atau ID rahasia di file frontend atau repository publik.
- Login pada versi awal ini sengaja belum mengizinkan akses sampai backend Google Apps Script dikonfigurasi.
- Spreadsheet database harus tetap Private.
- Pemeriksaan peran dan hak akses wajib dilakukan di backend, bukan hanya di browser.

## Deployment GitHub Pages
1. Buka **Settings → Pages**.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu simpan.
4. Setelah deployment selesai, alamat situs biasanya `https://doemyati.github.io/manajemen-dapur/`.

## Rencana integrasi
- Google Spreadsheet sebagai database.
- Google Apps Script sebagai API dan pengelola autentikasi.
- Peran pengguna: Kepala Sekolah, Bendahara, dan PJ Dapur.
- Perencanaan menu rotasi 10 hari (pagi, siang, malam).
- Prediksi biaya berbasis harga pembelian terakhir.
- Laporan 10 harian, bulanan, semester, dan tahunan dalam PDF/Excel.

Jangan gunakan aplikasi untuk pencatatan operasional nyata sebelum backend, otorisasi, dan penyimpanan data diuji.
