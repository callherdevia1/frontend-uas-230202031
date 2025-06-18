# PBF - UJIAN AKHIR SEMESTER(UAS) 

| Name  | Devia Herena Kippuw |
|-------|---------------------|
| NIM   | 230202031           |
| Class | TI - 2B             |

Repository ini dibuat untuk Dokumentasi Ujian Akhir Semester Mata Kuliah PBF.

## 🗒️ Persiapan Awal
- PHP >= 8.1
- Composer
- MySQL/MariaDB
- Git Bash

## 💻BackEnd
1. Buat Proyek CodeIgniter 4 Baru
2. Buka Command Prompt
   ```bash
   composer create-project codeigniter4/appstarter backend_rumahsakit
3. Buat File Env
   ```bash
   copy env .env
4. Edit Konfigurasi Di .env
    ```bash
    database.default.hostname = localhost
    database.default.database = db_rumahsakit_230202031
    database.default.username = root
    database.default.password =
## 💻Databases
1. Masuk ke MYSQL
2. Buat Database Dengan Memasukan Query
   ```bash
   CREATE DATABASE db_rumahsakit_230202031;
3. Buat Tabel Dengan Memasukan Query
   ```bash
   CREATE TABLE pasien (
      id INT AUTO_INCREMENT PRIMARY KEY,
      nama VARCHAR(100),
      alamat TEXT,
      tanggal_lahir DATE,
      jenis_kelamin ENUM('L', 'P')
    );
    
    CREATE TABLE obat (
      id INT AUTO_INCREMENT PRIMARY KEY,
      nama_obat VARCHAR(100),
      kategori VARCHAR(50),
      stok INT,
      harga DECIMAL(10,2)
    );
   
## 💻Frontend Laravel
1. Buka Terminal Pada Laragon
2. Ketikkan
   ```bash
   composer create-project laravel/laravel frontend-uas-230202031 "10.0"
## 📧 

