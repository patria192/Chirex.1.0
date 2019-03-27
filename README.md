# Chirex.1.0
> Sistem Pakar Diagnosa Penyakit Pada Ayam Menggunakan Metode Certainty Factor Berbasis Website Responsive.

Berikut tampilan sistem yang di buat.

* Home

![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%201.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%202.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%203.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%205.png)

* Admin

![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Admin%201.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Admin%202.png)

## Configure

Use XAMPP v.3.2.2 With Php 5: Set your database name in config.php

```<?php
$server = "localhost";
$username = "root";
$password = "";
$database = "spkayam";

mysql_connect($server,$username,$password) or die("Koneksi gagal");
mysql_select_db($database) or die("Maaf, Database tidak bisa dibuka");
?>
```
## Formula yang digunakan:
```
CFc (CF1,CF2) = CF1 + CF2 (1- CF1)                        ; jika CF1 dan CF2 keduanya posistif
CFc (CF1,CF2) = CF1 + CF2 (1+ CF1)                        ; jika CF1 dan CF2 keduanya negative
CFc (CF1,CF2) = {CF1 + CF2} / (1-min{| CF1|,| CF2|})      ; jika salah satu negatif```

## Usage example

Semoga hasil karya ini dapat berguna serta bermanfaat bagi perkembangan Teknologi dan Informasi pada khususnya. Serta sebagai kajian bagi mahasiswa dalam pengambilan skripsi. .

_Di dedikasikan untuk bunga hati saya, semoga bahagia selalu dalam satu senti, semoga.. [Januriawan]._


## Release History

* 0.0.1
    * Work in progress

## Meta

Copyright – [@januriawan](https://twitter.com/januriawan) – januriawan@protonmail.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/januriawan](https://github.com/januriawan/)

## Disclaimer

* Dilarang keras di perjual-belikan, source ini saya publikasi untuk keperluan belajar saja.
    * Untuk yang mau file dokumentasi / skripsi bisa request dengan menghubungi saya.


