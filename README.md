# Lab8Web

**Nama: Ema Rosida**

**NIM: 312010062**

**Kelas: TI.20.D1**

**Mata Kuliah: Pemrograman Web**

**Praktikum 8: PHP dan Database MySQL**

Langkah-langkah Praktikum

# Persiapan

Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.

# Menjalankan MySQL Server

Untuk menjalankan MySQL Server dari menu XAMPP Control.
![1](https://user-images.githubusercontent.com/101863671/169685721-3fb80a46-c054-4a5c-8acf-1a3ed9280916.png)

# Mengakses MySQL Client menggunakan PHP 
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser: http://localhost/phpmyadmin/

# Membuat Database: Studi Kasus Data Barang
![image](https://user-images.githubusercontent.com/101863671/169686015-ef8660ea-a5aa-42f2-b9bc-bdd5701e6e74.png)

# Membuat Database
CREATE DATABASE latihan1;

# Membuat Tabel
![2](https://user-images.githubusercontent.com/101863671/169686121-8f532f13-769a-4e1b-97dd-f6d49f8a50f0.png)

# Menambahkan Data
![image](https://user-images.githubusercontent.com/101863671/169686305-9ced2b8a-f79a-4598-9026-fec3de709608.png)
![3](https://user-images.githubusercontent.com/101863671/169686319-002ea827-72fe-4691-a1c5-3891a5f56111.png)

![4 (2)](https://user-images.githubusercontent.com/101863671/169686474-18f8afaa-3a0c-4e8e-aa64-135b218f4096.png)

# Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (c:\xampp\htdocs)
![5](https://user-images.githubusercontent.com/101863671/169686375-570e7c88-5b06-4cc6-b650-31a225d87569.png)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:http://localhost/lab8_php_database/
![6](https://user-images.githubusercontent.com/101863671/169686541-6a0762b7-2239-4233-a34a-997a5662f4b9.png)

# Membuat file koneksi database
Buat file baru dengan nama koneksi.php
![7](https://user-images.githubusercontent.com/101863671/169686743-8f1bc872-b30e-4052-ba20-44e8168859a6.png)

Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”;
![8](https://user-images.githubusercontent.com/101863671/169686760-7706c294-89ef-417f-af9b-a7a4381d2340.png)

# Membuat file index untuk menampilkan data (Read)
Buat file baru dengan nama index.php
![9 (2)](https://user-images.githubusercontent.com/101863671/169687553-84384589-161f-45aa-b0d9-62dd2c46608f.png)
![10 (2)](https://user-images.githubusercontent.com/101863671/169687563-64b2cbed-5839-4046-8113-15dae9d55d56.png)

Agar tampilan nya terlihat rapih dan menarik tambahkan CSS di dalamnya
![style css (2)](https://user-images.githubusercontent.com/101863671/169688640-92f633ad-424a-4ca4-84e4-0a55a123b25c.png)

Hasil browser
![11 (2)](https://user-images.githubusercontent.com/101863671/169687592-4575fb3a-5ebd-4893-a11c-5246769c1fbe.png)

# Menambah Data (Create)
Buat file baru dengan nama tambah.php
![12 (2)](https://user-images.githubusercontent.com/101863671/169687714-304c0046-25c0-482c-856c-125066f66463.png)
![13 (2)](https://user-images.githubusercontent.com/101863671/169687717-ba8e8655-cf7d-44e4-b75c-e807eb2efcea.png)
![14 (2)](https://user-images.githubusercontent.com/101863671/169687727-6e220a9a-08ab-45cb-bd32-022e23f73777.png)

Hasil browser
![15 (2)](https://user-images.githubusercontent.com/101863671/169687759-7cb4e06d-4fa2-4fe6-bcc1-919bb5a8eeb3.png)

# Mengubah Data (Update)
Buat file baru dengan nama ubah.php
![16 (2)](https://user-images.githubusercontent.com/101863671/169687881-842408c6-d2f3-4860-9389-4bcd85dcd358.png)
![17 (2)](https://user-images.githubusercontent.com/101863671/169687887-ba59f736-da00-4aa7-b81a-719e2c054a5f.png)
![18 (2)](https://user-images.githubusercontent.com/101863671/169687896-825a4611-187e-4c0b-a506-0d1b6379a680.png)
![19 (2)](https://user-images.githubusercontent.com/101863671/169687904-3666a9dc-d4ff-4bf7-b5ce-b8189aca2eed.png)
![20 (2)](https://user-images.githubusercontent.com/101863671/169687996-43ff9a3f-d3fa-4d0e-b375-014a09a284b5.png)

Data sebelum diubah:
![11 (2)](https://user-images.githubusercontent.com/101863671/169688031-c8d97de3-f9b4-43c4-b3e0-99b39d8e4b39.png)

Data setelah diubah:
![21 (2)](https://user-images.githubusercontent.com/101863671/169688070-3443acb5-13d1-40f6-a259-4b45f58c8a4f.png)

# Menghapus Data (Delete)
Buat file baru dengan nama hapus.php
![22 (2)](https://user-images.githubusercontent.com/101863671/169688114-6f18c187-5e07-43ce-93f0-fd1ef503a9df.png)

Data sebelum dihapus:
![11 (2)](https://user-images.githubusercontent.com/101863671/169688186-05719f05-927d-4aa0-a191-7ba573797235.png)

Data setelah dihapus:
![23 (2)](https://user-images.githubusercontent.com/101863671/169688173-3d42a48b-4435-4e07-be23-d1294044dd7e.png)









