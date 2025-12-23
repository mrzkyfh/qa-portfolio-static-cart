## Test Case ID: TC-CART-001
**Judul:** Menambahkan produk ke keranjang
**Prekondisi:** Pengguna berada di halaman daftar produk  

### Langkah:
1. Buka website
2. Klik tombol (+) pada salah satu produk

### Hasil yang Diharapkan:
Sistem menampilkan pop-up notifikasi bahwa produk berhasil ditambahkan ke keranjang.



## Test Case ID: TC-CART-002
**Judul:** Menambahkan jumlah produk di keranjang
**Prekondisi:** Pengguna berada di halaman fitur keranjang  

### Langkah:
1. Buka website
2. Buka fitur keranjang
3. Klik Tombol (+) di dalam tabel Qty

### Hasil yang Diharapkan:
Jumlah produk bertambah dan total harga diperbarui sesuai jumlah terbaru.



## Test Case ID: TC-CART-003
**Judul:** Mengurangi jumlah produk di keranjang
**Prekondisi:** Pengguna berada di halaman fitur keranjang  

### Langkah:
1. Buka website
2. Buka fitur keranjang
3. Klik Tombol (-) di dalam tabel Qty

### Hasil yang Diharapkan:
Jumlah produk berkurang dan total harga diperbarui sesuai perubahan.



## Test Case ID: TC-CART-004
**Judul:** Menghapus produk di keranjang
**Prekondisi:** Pengguna berada di halaman fitur keranjang  

### Langkah:
1. Buka website
2. Buka fitur keranjang
3. Klik Tombol "Hapus" di dalam tabel aksi

### Hasil yang Diharapkan:
Produk berhasil dihapus dari keranjang dan total harga diperbarui sesuai item yang tersisa.


## Test Case ID: TC-CART-005
**Judul:** Mengurangi jumlah produk hingga kurang dari 1  
**Prekondisi:** Produk sudah ditambahkan ke keranjang  

### Langkah:
1. Buka halaman keranjang
2. Klik tombol Kurangi (-) secara berulang hingga jumlah produk mencapai 1
3. Klik tombol Kurangi (-) sekali lagi

### Hasil yang Diharapkan:
Page akan menampilkan kalimat (Keranjangmu masih kosong. Yuk pilih kue dulu di halaman utama.) 




