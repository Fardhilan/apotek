1. Entitas & Hubungannya:
- KARYAWAN: Petugas apotek yang melayani pelanggan
- PELANGGAN: Pembeli obat di apotek
- OBAT: Produk yang dijual di apotek
- SUPPLIER: Pemasok obat ke apotek
- TRANSAKSI: Pencatatan pembelian obat
- DETAIL_TRANSAKSI: Rincian obat yang dibeli
- KATEGORI_OBAT: Pengelompokan jenis obat
2. Alur Bisnis Utama:
- Pelanggan datang ke apotek
- Karyawan melayani pelanggan
- Pelanggan memilih obat
- Karyawan mencatat transaksi
- Detail obat yang dibeli masuk ke detail transaksi
- Stok obat berkurang otomatis
- Supplier memasok obat ketika stok menipis
3. Kardinalitas (Hubungan antar Entitas):
- 1 Karyawan bisa melayani banyak Transaksi
- 1 Pelanggan bisa melakukan banyak Transaksi
- 1 Transaksi bisa memiliki banyak Detail Transaksi
- 1 Obat bisa masuk ke banyak Detail Transaksi
- 1 Supplier bisa memasok banyak Obat
- 1 Kategori bisa memiliki banyak Obat
