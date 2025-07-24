Aplikasi kasir sederhana ini digunakan untuk mencatat transaksi pembelian barang. Pengguna dapat menambahkan barang, melihat daftar belanja, menghitung total, dan menghapus seluruh data transaksi. Cocok digunakan oleh pelaku usaha kecil, siswa, atau siapa pun yang ingin belajar dasar pencatatan transaksi.

Cara Membuka Aplikasi
Buka Google Colab di https://colab.research.google.com

Buat file Notebook baru (+ New Notebook)

Salin seluruh kode aplikasi ke dalam satu sel

Klik tombol ▶️ Run

Aplikasi akan berjalan di terminal bawah sel (interaktif)

Panduan Menu Utama
Setelah aplikasi berjalan, Anda akan melihat tampilan seperti ini:

markdown
Salin
Edit
=== APLIKASI KASIR SEDERHANA ===
1. Tambah Barang
2. Lihat Keranjang
3. Reset Keranjang
4. Keluar
Pilih menu (1-4):
✳️ Menu 1: Tambah Barang
Masukkan nama barang, harga, dan jumlah saat diminta

Contoh:

Nama: Teh Botol

Harga: 5000

Jumlah: 2

Barang akan langsung masuk ke keranjang

🛍️ Menu 2: Lihat Keranjang
Menampilkan daftar barang yang sudah dimasukkan

Tersedia juga subtotal per barang dan total keseluruhan

🧹 Menu 3: Reset Keranjang
Menghapus semua barang yang ada di keranjang

Cocok digunakan jika ingin memulai transaksi baru

❌ Menu 4: Keluar
Menutup aplikasi

Catatan Penggunaan
Harga barang harus berupa angka (tanpa titik atau koma ribuan)

Jumlah barang harus bilangan bulat (integer)

Tidak bisa menyimpan data permanen (transaksi hilang setelah keluar)

Contoh Transaksi
yaml
Salin
Edit
Pilih menu (1-4): 1
Masukkan nama barang: Indomie
Masukkan harga barang: 3500
Masukkan jumlah barang: 3
✅ Barang 'Indomie' ditambahkan ke keranjang.

Pilih menu (1-4): 2

📋 Daftar Belanja:
Nama                 Harga      Jumlah     Subtotal
Indomie              3500       3          10500

💰 Total Belanja: Rp 10,500
