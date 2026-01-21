# Sistem CRUD Data Warga RT

Project ini merupakan aplikasi web sederhana berbasis **PHP dan MySQL** yang digunakan untuk mengelola data warga tingkat RT menggunakan konsep **CRUD (Create, Read, Update, Delete)**. Sistem ini memungkinkan pengurus RT untuk melakukan pendataan warga secara terstruktur dan terkomputerisasi.

Aplikasi ini dikembangkan sebagai latihan dan implementasi konsep **Web Programming dan Basis Data**, serta dibuat untuk memenuhi **Tugas Besar mata kuliah E-Commerce dan Pengembangan Web**.

---

## Deskripsi Proyek

Sistem CRUD Data Warga RT dirancang untuk membantu proses administrasi kependudukan di lingkungan RT, seperti pencatatan identitas warga, pengelolaan data, serta pembaruan informasi secara cepat dan terpusat melalui aplikasi web.

Fitur utama meliputi:
- Menampilkan daftar warga
- Menambahkan data warga baru
- Mengedit data warga
- Menghapus data warga
- Penyimpanan data ke dalam database MySQL

---

## Fitur Utama

1. Tambah Data Warga  
2. Lihat Data Warga  
3. Edit Data Warga  
4. Hapus Data Warga  
5. Integrasi Database MySQL  

---

## Teknologi yang Digunakan

- PHP  
- MySQL  
- HTML  
- CSS  
- XAMPP / Laragon  

---

## Struktur Folder

```
CRUD-Data-Warga-RT-main/
│
├── index.php      # Menampilkan data warga
├── tambah.php     # Form tambah data
├── edit.php       # Form edit data
├── hapus.php      # Proses hapus data
├── config.php     # Koneksi database
├── warga.sql      # Struktur dan data awal database
└── README.md
```

---

## Cara Menjalankan

1. Pindahkan folder project ke direktori server (htdocs / www).
2. Import file `warga.sql` ke MySQL melalui phpMyAdmin.
3. Atur koneksi database pada file `config.php`.
4. Jalankan melalui browser:
   ```
   http://localhost/CRUD-Data-Warga-RT-main
   ```

---

## Alur Kerja Sistem

1. User membuka halaman utama.
2. Sistem menampilkan data warga dari database.
3. User dapat menambah, mengedit, atau menghapus data.
4. Perubahan langsung tersimpan di database MySQL.

---

## Tujuan Pembelajaran

Project ini bertujuan untuk memahami:
- Konsep CRUD
- Koneksi PHP dengan MySQL
- Operasi dasar SQL
- Pengembangan aplikasi web sederhana
- Pengelolaan data berbasis database

---

## Author

Fachri Reyhan  
Mahasiswa – Teknologi Informasi / Informatika  
Tahun: 2026  

---

## Lisensi

Project ini dibuat untuk keperluan akademik dan pembelajaran.  
Bebas digunakan sebagai referensi dengan mencantumkan sumber.
