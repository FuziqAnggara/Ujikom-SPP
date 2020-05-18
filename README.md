<p align="center"><img src="https://github.com/FuziqAnggara/Ujikom-SPP/blob/master/public/img/dashboard.PNG" width="1000"></p>

<p align="center">
    <h1>Aplikasi Pembayaran SPP</h1>
</p>

## Tentang Aplikasi Pembayaran SPP

Level Admin

-   Login
-   Logout
-   CRUD data siswa
-   CRUD data petugas
-   CRUD data Kelas
-   CRUD data SPP
-   Entri Transaksi Pembayaran
-   Lihat Histori Pembayaran
-   Generate Laporan

Level Petugas

-   Login
-   Logout
-   Entri Transaksi Pembayaran
-   Lihat Histori Pembayaran

Level Siswa

-   Login
-   Logout
-   Lihat Histori Pembayaran

## Akun Untuk Login

Level Admin

-   email : admin@spp.com
-   password : admin

Level Petugas

-   email : petugas@spp.com
-   password : petugas

Level Siswa

-   NISN : 123456789876
-   Nama : siswa

## Cara Install Project Aplikasi Pembayaran SPP

$ cd Ujikom - SPP <br>
$ composer update <br>
$ php artisan migrate --seed <br>
$ php artisan serve <br>

Catatan :
lakukan terlebih dahulu pembuatan database dengan nama db_spp sebelum melakukan migrate.
