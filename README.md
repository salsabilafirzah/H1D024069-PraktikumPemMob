# Laporan Praktikum Pemrograman Mobile

---

### Identitas Mahasiswa
- **Nama** : Salsabila Firzah Amanina
- **NIM** : H1D024069
- **Shift Awal** : H
- **Shift Akhir** : D

---

## Modul 2: Pengenalan dan Desain Framework Flutter

### 1. Dasar Widget (Hello World, Column, & Row)

Penjelasan singkat:
- **Hello World**: Menampilkan widget dasar `MaterialApp`, `Scaffold`, `AppBar`, `Center`, dan `Text` sebagai awalan framework Flutter.
- **Column Widget**: Mengatur tata letak child widget secara vertikal (ke bawah).
- **Row Widget**: Mengatur tata letak child widget secara horizontal (ke samping).

| Hello World | Column Widget | Row Widget |
| :---: | :---: | :---: |
| <img src="screenshot/HelloWorld.jpeg" width="250" alt="Hello World" /> | <img src="screenshot/ColumnWidget.jpeg" width="250" alt="Column Widget" /> | <img src="screenshot/RowWidget.jpeg" width="250" alt="Row Widget" /> |

### 2. Form Input, Navigasi Halaman, & ListView

Penjelasan singkat:
- **Form Produk**: Menggunakan `TextField` untuk menginput Kode Produk, Nama Produk, dan Harga, serta tombol `Simpan` untuk mengirim data ke halaman lain.
- **Detail Produk**: Menampilkan detail data yang dikirim dan diterima dari form input sebelumnya.
- **List Data Produk**: Menampilkan daftar katalog produk menggunakan widget `ListView` bertipe `Card` secara dinamis.

| Form Produk | Detail Produk | List Data Produk |
| :---: | :---: | :---: |
| <img src="screenshot/FormProduk.jpeg" width="250" alt="Form Produk" /> | <img src="screenshot/DetailProduk.jpeg" width="250" alt="Detail Produk" /> | <img src="screenshot/ListDataProduk.jpeg" width="250" alt="List Data Produk" /> |

---

## Modul 3: Navigasi, Routing, Local Storage (SharedPreferences), & Drawer

Penjelasan singkat:
- **Login Page (`login_page.dart`)**: Form autentikasi input username dan password. Jika berhasil, username disimpan ke local storage menggunakan `SharedPreferences` dan berpindah halaman menggunakan dialog notifikasi.
- **Home Page (`home_page.dart`)**: Mengambil dan menampilkan data username yang tersimpan secara lokal di `SharedPreferences`.
- **Drawer / Side Menu (`sidemenu.dart`)**: Navigasi menu samping untuk berpindah antara halaman **Home** dan **About**.
- **About Page (`about_page.dart`)**: Halaman statis informasi yang juga terhubung dengan menu drawer navigasi.

### Hasil Demonstrasi (Screen Recording)

<p align="center">
  <img src="screenshot/Modul 3.gif" width="300" alt="Demonstrasi Modul 3" />
</p>

> *File rekaman video original: [Modul 3.mp4](screenshot/Modul%203.mp4)*

---

## Modul 4: Operasi CRUD dengan API CodeIgniter 4 & Desain UI Tokokita

Penjelasan materi:
Pada modul ini dibangun arsitektur RESTful API menggunakan framework **CodeIgniter 4** dengan database **MySQL (Laragon)**, serta pembuatan model dan antarmuka pengguna (UI) pada **Flutter (Tokokita)**:
1. **Backend RESTful API (CodeIgniter 4)**:
   - Endpoint `/registrasi` (POST) untuk pendaftaran user/member baru dengan enkripsi password `PASSWORD_DEFAULT`.
   - Endpoint `/login` (POST) untuk autentikasi user dan pembuatan access token (`auth_key`).
   - Endpoint `/produk` (CRUD: POST, GET, PUT, DELETE) untuk manajemen data katalog produk.
2. **Frontend Flutter (Tokokita)**:
   - **Model Data**: Pemodelan data `Login`, `Registrasi`, dan `Produk` dengan parsing `fromJson`.
   - **Form Registrasi & Login (`registrasi_page.dart` & `login_page.dart`)**: Dilengkapi validasi form (`TextFormField`, regex format email, minimal karakter password).
   - **CRUD UI Produk**: `ProdukPage` (katalog produk berbentuk list card dan tombol tambah), `ProdukForm` (form tambah & ubah produk), dan `ProdukDetail` (tampil detail, dialog konfirmasi hapus, dan navigasi edit).

### Hasil Dokumentasi & Screenshot Modul 4

| Registrasi Page | Login Page | List Produk |
| :---: | :---: | :---: |
| <img src="" width="250" alt="Registrasi Page" /> | <img src="" width="250" alt="Login Page" /> | <img src="" width="250" alt="List Produk" /> |

<br>

| Tambah Produk | Detail Produk | Ubah Produk |
| :---: | :---: | :---: |
| <img src="" width="250" alt="Tambah Produk" /> | <img src="" width="250" alt="Detail Produk" /> | <img src="" width="250" alt="Ubah Produk" /> |
