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

https://github.com/user-attachments/assets/screenshot/Modul%203.mp4 (atau dapat dilihat langsung melalui file video di bawah):

<video src="screenshot/Modul%203.mp4" controls="controls" width="350">
  Browser Anda tidak mendukung tag video. Anda dapat mengunduh atau memutar langsung file <a href="screenshot/Modul%203.mp4">screenshot/Modul 3.mp4</a>.
</video>

> *Catatan: Jika pemutar video di atas tidak langsung tampil di aplikasi Markdown viewer tertentu, silakan buka langsung file video di [screenshot/Modul 3.mp4](screenshot/Modul%203.mp4).*
