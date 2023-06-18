# UAS-Python_V3922034_MuhammadRafiNaufalPratama

Saya mengambil data dari Bukalapak pada ......, Halaman yang saya ambil mulai dari Halaman 1 sampai Halaman 3 dengan Total produk yang ada di toko sebanyak 52 produk. Data yang saya ambil mencangkup id_seller, username, nama_toko, level_toko, premium_toko, id_produk, nama_produk, kategori, kondisi, rating, jumlah_rating, stok, jumlah_interest, jumlah_sold, jumlah_view, harga, harga_asli, diskon, dan deskripsi

Script tersebut digunakan untuk mengambil data produk dari halaman toko penjual di situs Bukalapak (https://www.bukalapak.com/u/). Berikut adalah deskripsi data yang diambil oleh script:

1. Informasi Penjual:
   - Id Penjual (idseller): ID unik penjual di Bukalapak.
   - Nama Penjual (username): Nama pengguna penjual di Bukalapak.
   - Nama Toko (nama_toko): Nama toko penjual di Bukalapak.
   - Level Toko (level_toko): Level toko penjual di Bukalapak.
   - Premium Toko (premium_toko): Status keanggotaan premium toko penjual.

2. Informasi Produk:
   - Id Produk (id_produk): ID unik produk di Bukalapak.
   - Nama Produk (nama_produk): Nama produk.
   - Kategori (kategori): Kategori produk.
   - Kondisi (kondisi): Kondisi produk (baru/bekas).
   - Rating (rating): Nilai rata-rata rating produk.
   - Jumlah Rating (jumlah_rating): Jumlah rating yang diberikan pada produk.
   - Stok (stok): Jumlah stok produk yang tersedia.
   - Jumlah Interest (jumlah_interest): Jumlah kali produk di-"interest" oleh pengguna.
   - Jumlah Sold (jumlah_sold): Jumlah produk yang terjual.
   - Jumlah View (jumlah_view): Jumlah tampilan produk.
   - Harga (harga): Harga produk.
   - Harga Asli (harga_asli): Harga asli produk sebelum diskon.
   - Diskon (diskon): Persentase diskon produk.
   - Deskripsi (deskripsi): Deskripsi lengkap produk.

Data produk diambil dari halaman-halaman produk toko penjual dengan memanfaatkan API Bukalapak. Script akan mengunduh halaman-halaman produk dalam bentuk JSON menggunakan API untuk kemudian menggabungkannya menjadi satu file JSON yang berisi semua data produk. Selanjutnya, data produk tersebut akan diubah menjadi format CSV untuk disimpan dalam file CSV dengan nama sesuai dengan id penjual.
