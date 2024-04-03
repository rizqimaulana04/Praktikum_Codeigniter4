# PHP Framework (Codeigniter)

## Instruksi Praktikum

1. Persiapkan text editor misalnya `VSCode`.
2. Buat folder baru dengan nama `Artikel` pada docroot webserver (`htdocs`)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Langkah-langkah Praktikum

**Persiapan**<br>
Sebelum memulai menggunakan Framework Codeigniter, perlu dilakukan konfigurasi pada
webserver. Beberapa ekstensi PHP perlu diaktifkan untuk kebutuhan pengembangan
Codeigniter 4.<br>
<br>
Berikut beberapa ekstensi yang perlu diaktifkan:<br>
• `php-json` ekstension untuk bekerja dengan JSON;<br>
• `php-mysqlnd` native driver untuk MySQL;<br>
• `php-xml` ekstension untuk bekerja dengan XML;<br>
• `php-intl` ekstensi untuk membuat aplikasi multibahasa;<br>
• `libcurl` (opsional), jika ingin pakai Curl.<br>
<br>
Untuk mengaktifkan ekstentsi tersebut, melalu `XAMPP Control Panel`, pada bagian Apache
klik `Config`->`PHP.ini`
<br>
![img](gambar/1.png)<br>
<br>
Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan.
Kemudian simpan kembali filenya dan restart Apache web server.<br>
<br>
![img](gambar/2.png)<br>
<br>

## Instalasi Codeigniter 4

Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual
dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.<br>
• Unduh `Codeigniter` dari website https://codeigniter.com/download <br>
• Extrak file zip Codeigniter ke direktori `htdocs/Artikel`.<br>
• Ubah nama direktory `framework-4.x.xx` menjadi `ci4`.<br>
• Buka browser dengan alamat http://localhost/Artikel/ci4/public/ <br>
<br>

![img](gambar/3.png)
