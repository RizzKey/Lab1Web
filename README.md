# praktikum 1 - pemrograman web
#### Fitrah Rizki Ardiansyah - 311910465
#### TI.19.A.2
# LANGKAH 1
### Membuka VS Code dan membuat file baru serta membuat struktur HTML Dasar
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
![image](https://user-images.githubusercontent.com/56240954/112934019-1d97e280-914b-11eb-9455-f4d1fe458a26.png)

# LANGKAH 2
### Membuat 2 buah paragraf dan atur atribut paragraf (Rata Kiri / Rata Kanan / Rata Tengah / Sama Rata)

```
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
 ```
 ![image](https://user-images.githubusercontent.com/56240954/112966834-ce66a780-9174-11eb-9491-ad3588682533.png)

# LANGKAH 3
### Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![image](https://user-images.githubusercontent.com/56240954/112967391-6d8b9f00-9175-11eb-9ea2-a49854b69854.png)

# LANGKAH 4
### Memformat Teks menggunakan format-format teks yang ada seperti ``` <b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>, dan <sup>. ```
    
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```    
![image](https://user-images.githubusercontent.com/56240954/112968583-a37d5300-9176-11eb-9552-b86bc14895e2.png)

# LANGKAH 5
### Menyisipkan Gambar dan mengatur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu bersama dengan gambar yg akan disisipkan.
![image](https://user-images.githubusercontent.com/56240954/112969160-31f1d480-9177-11eb-98a7-4533aadb9ea1.png)
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="LOGO_UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
![image](https://user-images.githubusercontent.com/56240954/112969410-6c5b7180-9177-11eb-9886-370021ca528c.png)

# LANGKAH 6
### Menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
![image](https://user-images.githubusercontent.com/56240954/112969851-d5db8000-9177-11eb-9e52-41bb04ac1242.png)

# LANGKAH 7
### Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakana Hyperlink.
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<p align="justify">Ini adalah halaman kedua.</p>

</body>
</html>
````
![image](https://user-images.githubusercontent.com/56240954/112970254-32d73600-9178-11eb-8cbc-a7f85bfd6208.png)

# Jawab Pertanyaan Berikut
### 1.Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
```Ada error ketika saya salah penulisan Heading <h1> tidak ditutup dengan </h1> jadi tidak terjadi perubahan.```

### 2.Apa perbedaan dari tag ```<p>``` dengan tag ```<br>``` berikan penjelasannya!
```Dari hasil praktek saya sendiri, perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan
dengan tag <p> yg jarak enter nya tidak terlalu jauh.```



