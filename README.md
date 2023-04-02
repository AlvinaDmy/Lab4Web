## Praktikum 4: PHP Modular

Nama: Alvina Damayanti

Nim: 312110125

Kelas: TI.21.A.3

## 1. Membuat file baru dengan nama header.php

![img 1](img/1.png)

## 2. Membuat file baru dengan nama footer.php

![img 2](img/2.png)

## 3. Membuat file baru dengan nama home.php

![img 3](img/3.png)

## 4. Membuat file baru dengan nama about.php

![img 4](img/4.png)

## MEMBUAT ROUTING

Langkah awal adalah menyiapkan file utama (index.php) yang berisi routing untuk mengakses banyak 
halaman. 

Contohnya:
• Halaman Home ( http://localhost/lab4_php_modular/index.php?mod=home )
• Halaman About ( http://localhost/lab4_php_modular/index.php?mod=about )

## 5. Membuat file baru dengan nama index.php

![img 5](img/5.png)

Dengan hasil Output seperti:

•home:

![img 6](img/6.png)

•about:

![img 7](img/7.png)

## Aktivasi mod_rewrite (.htaccess)

Langkah awal yang harus disiapkan adalah aktivasi mod_rewrite pada webserver Apache2 pada configurasi httpd.conf.

![img 8](img/8.png)

Aktifkan LoadModule mod_rewrite dengan cara melakukan un-comment pada baris tersebut.

## 7. Membuat file baru dengan nama .htaccess

![img 9](img/9.png)

Cara aksesnya menjadi:
• Halaman Home ( http://localhost/lab4_php_modular/home )
• Halaman About ( http://localhost/lab4_php_modular/about )

Dan Hasil Outputnya yaitu:

•home:

![img 10](img/10.png)

•about:

![img 11](img/11.png)

## Mengimplementasikan konsep modularisasi pada kode program praktikum 3 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama

## 1. tampilan .htaccsess

![img 12](img/12.png)

## Tampilan output lab3_php_database

## 2. Tampilan home.php:

![img 13](img/13.png)

## 3. Tampilan about.php:

![img 14](img/14.png)

## 4. Tampilan contact.php:

![img 15](img/15.png)

## 5. Tampilan tambah.php:

![img 16](img/16.png)

## 6. Tampilan ubah.php:

![img 17](img/17.png)