## Membuat CRUD dengan PHP Mysql

Pastikan anda sudah mendownload tools yang dibutuhkan

1. xampp
2. visual studio code
3. web browser (google chrome)
   
Selanjutnya buka jalankan mysql dan apache pada xampp control panel Selanjutnya buka phpmyadmin lalu import data_barang.sql

Buat folder di dalam htdocs lalu buat kan beberapa file

- koneksi.php
- tambah.php
- index.php
- ubah.php
- hapus.php
- gambar

Buka file koneksi.php masukan kode berikut :

<?php

$host = "localhost";

$host = "localhost";
$user = "root";
$pass = "";
$db = "latihan1";

$conn = mysqli_connect($host, $user, $pass, $db);
if ($conn == false) {
  echo "Koneksi ke server gagal";
  die();
}




  


