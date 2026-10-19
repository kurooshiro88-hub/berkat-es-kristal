CV BERKAT ES KRISTAL — Invoice App Prototype

ISI PAKET
- index.html: aplikasi prototipe
- manifest.webmanifest: metadata PWA
- sw.js: service worker untuk cache offline

FITUR PROTOTIPE
- Dashboard ringkasan omzet/piutang
- Form invoice UDANG/LOKAL
- Produk dan harga dapat ditambah, diedit, dinonaktifkan
- Pelanggan tersimpan dari invoice dan dapat diedit
- Jasa kirim per balok untuk LOKAL, tampil sebagai baris invoice
- Biaya tambahan bebas nama dan nominal
- Riwayat invoice, edit, duplikasi, hapus
- Status pembayaran dan saldo piutang
- Cetak/simpan sebagai PDF melalui dialog print browser
- Backup/restore JSON dan ekspor CSV
- Pengingat backup mingguan saat aplikasi dibuka pada hari Senin

PENTING
1. Ini prototipe untuk uji alur, bukan versi produksi.
2. Untuk PWA yang benar-benar dapat dipasang dan menggunakan service worker offline, host folder ini di situs HTTPS. Membuka file HTML langsung dari Files tidak mengaktifkan service worker.
3. PDF dibuat melalui dialog cetak browser. Pada iPhone, pilih Share/Save to Files dari tampilan cetak sesuai opsi yang tersedia di iOS.
4. Face ID belum diimplementasikan. PIN dalam prototipe hanya simulasi dan disimpan tidak terenkripsi; jangan mengandalkannya untuk keamanan data sungguhan.
5. Data tersimpan pada localStorage browser. Menghapus data situs/browser dapat menghapus data aplikasi. Ekspor backup secara berkala dan uji pemulihan.
6. Jangan gunakan untuk transaksi penting sebelum menguji perhitungan, format PDF, ekspor/impor, dan pemulihan backup.
