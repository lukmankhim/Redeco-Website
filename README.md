# Redeco Website (demo)

Demo toko online Redeco Bamboo Charcoal Wall Panel. Satu halaman statis (`index.html`) dengan katalog 20 motif, detail produk, kalkulator kebutuhan panel, keranjang, checkout, dan simulasi pembayaran Midtrans Snap.

Buka `index.html` langsung di browser, atau jalankan `python3 -m http.server` lalu buka `http://localhost:8000`.

## Yang masih placeholder

- **Harga**: `SERIES` di `index.html` (Wood Grain Rp385.000, Pure Color Rp365.000, Marble Rp425.000, tambahan 8 mm Rp90.000, packing kayu Rp75.000) adalah harga demo.
- **Ongkir**: rumus estimasi di `totals()`; nanti diganti API kurir (RajaOngkir/Biteship).
- **Palet warna**: token di `:root` diambil dari logo Redeco. Ganti dengan palet termic.id.
- **Font**: Plus Jakarta Sans; Poppins Bold hanya untuk wordmark.
- **Kontak & bukti**: nomor WhatsApp, sertifikat uji, dan halaman legal masih placeholder (`[...]` di halaman).
- **Nama motif**: Marble (MB-01 s.d. MB-08) dan WG-06/WG-07 masih nama sementara (dilabeli di halaman).
- **Pembayaran**: simulasi. Untuk produksi, backend (mis. Medusa + payment provider Midtrans) membuat token Snap dan status order diambil dari notifikasi HTTP Midtrans.
