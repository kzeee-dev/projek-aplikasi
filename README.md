# WARUNG BUMDes — Beta v1.Agustus.26

Aplikasi Android kasir dan manajemen BUMDes berbasis WebView.

## Fitur
- Login Admin / Kasir
- Kasir dan keranjang penjualan
- Pencarian produk pintar (nama, barcode, typo ringan)
- Produk & stok
- Pembelian / barang masuk
- Pelanggan & piutang
- Supplier
- Keuangan
- Laporan dan export CSV
- Riwayat penjualan dan cetak struk
- Retur penjualan
- Stock opname
- Buku kas
- Riwayat aktivitas
- Pengguna dan pengaturan
- Backup / restore JSON
- Penyimpanan lokal perangkat

## Akun demo
- Admin: `admin` / `1234`
- Kasir: `kasir` / `1234`

## Build APK di GitHub Actions
1. Upload **isi ZIP ini** ke root repository GitHub (jangan membuat folder proyek bersarang).
2. Commit ke branch `main` atau `master`.
3. Buka **Actions** → workflow **Build Beta v1.Agustus.26 APK**.
4. Jalankan workflow.
5. Setelah selesai, buka **Artifacts** → `Beta-v1.Agustus.26-APK`.
6. Di dalam artifact ada `app-debug.apk`.

Konfigurasi:
- JDK 17
- Gradle 8.7
- Android Gradle Plugin 8.5.2
- compileSdk 35
- minSdk 23

## Catatan
Data aplikasi disimpan di localStorage WebView, belum memakai server/cloud. Backup JSON secara berkala untuk mencegah kehilangan data.
