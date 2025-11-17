<img width="1213" height="192" alt="Screenshot 2025-11-17 131033" src="https://github.com/user-attachments/assets/dc8df82c-322a-4193-84df-65f9c8cdff11" />


Database: latihan1
Tabel: data_barang
Struktur tabel memiliki kolom:
id_barang (sebagai primary key)
kategori (jenis barang)
nama (nama barang)
gambar (file gambar barang)
harga_beli (harga pembelian)
harga_jual (harga penjualan)
stok (jumlah persediaan)
Data awal yang sudah tersimpan:
3 barang elektronik (HP Samsung, HP Xiaomi, HP OPPO)
Masing-masing memiliki harga beli, harga jual, dan stok



<img width="1045" height="384" alt="Screenshot 2025-11-17 131542" src="https://github.com/user-attachments/assets/53418bbd-64bb-454c-8968-ad2c216ec22e" />




<img width="1213" height="192" alt="Screenshot 2025-11-17 131033" src="https://github.com/user-attachments/assets/d5c6d80a-07b2-4997-812e-dc0bf082db7d" />


Berhasil melakukan koneksi antara aplikasi PHP dengan database MySQL
Menggunakan file koneksi.php yang berisi konfigurasi koneksi
Fungsi mysqli_connect() digunakan untuk membuat koneksi
Pesan "Koneksi berhasil" menunjukkan koneksi database berjalan dengan baik


<img width="975" height="340" alt="Screenshot 2025-11-17 144446" src="https://github.com/user-attachments/assets/3591ea69-bfa3-49e4-9c55-11fb7871c05b" />


Menampilkan data barang dalam format tabel
Kolom yang ditampilkan: Gambar, Nama Barang, Kategori, Harga Jual, Harga Beli, Stok, Aksi
Terdapat duplikasi data "HP Samsung Android" (mungkin error input)
Tombol aksi "Ubah" dan "Hapus" tersedia untuk setiap barang
Tampilan masih sederhana tanpa gambar



<img width="594" height="528" alt="Screenshot 2025-11-17 134011" src="https://github.com/user-attachments/assets/63da9613-8c1f-4e2f-b777-fb5f98a7ff4f" />


Form untuk menambah data barang baru "Bandphone vivo"
Field yang diisi:
Nama Barang: Bandphone vivo
Kategori: Hand Phone (dropdown selection)
Harga Jual: 4,000,000
Harga Beli: 3,900,000
Stok: 15 unit
File Gambar: Tombol "Choose File" untuk upload gambar
Tombol "Simpan" untuk menyimpan data ke database



<img width="1154" height="388" alt="Screenshot 2025-11-17 134128" src="https://github.com/user-attachments/assets/103d9045-591c-4b9d-b544-c3cf3699934c" />


Berhasil menambahkan data baru "handphone vivo" ke database
Data baru muncul dalam tabel dengan spesifikasi:
Kategori: Hand Phone
Harga Beli: 3,900,000
Stok: 15 unit
Data lama tetap tersimpan:
HP Samsung Android (Elektronik)
HP Xiaomi Android (Elektronik)
HP OPPO Android (Elektronik)
Terdapat sedikit formatting issue pada tampilan data baru

