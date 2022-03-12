# Lab1Web
Tugas Praktikum Pertemuan 2

Nama    : Faza Ardan Kusuma <br>
NIM     : 312010001<br>
Kelas   : TI 20 B1

Pertama kita buat tag HTML terlebih dahulu dengan nama <b>lab1_tag_dasar.html</b> dan tambahkan tag dasar dokumen HTML.<br>

```<!DOCTYPE html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>
    
</body>
</html>
```


Maka tampilannya akan menjadi seperti berikut pada browser.<br>
![Gambar Title HTML Dasar](Pic/lab1tagdasar.png)

<br>

## 1. Membuat Paragraf <br>

Pada poin ini saya akan membuat paragraf pada file HTML.<br>
Pada sintax p bertujuan untuk membuat paragraf baru. Berikut source codenya : <br>
```
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html. </p>
```

Berikut adalah tampilannya : <br>
![Gambar Membuat Paragraf 1](Pic/membuatparagraf1.png)<br>

<b>Merubah Paragraf</b><br>
Untuk membuat paragraf menjadi ditengah dan misalnya rata kanan, maka source code dirubah menjadi seperti berikut : <br>
``` <!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
```

Berikut tampilannya :<br>
![Merubah Paragraf](Pic/merubahparagraf.png)<br>
Dalam tampilan tersebut terlihat perbedaan antara yang belum dirubah paragrafnya dan yang sudah.<br>

## 2. Menambahkan Judul (Heading) <br>

Judul memiliki 6 level, yaitu <i>h1 sampai dengan h6</i>. <br>
Disini saya akan menambahkan judul h1 pada oaragraf pertama dan judul h2 pada paragraf kedua.<br>
Maka dari itu, source code saya rubah menjadi : <br>
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html. </p>
```

Berikut untuk tampilannya : <br>
![Menambahkan Judul](Pic/menambahkanheading.png)<br>

## 3. Memformat Text

Setelah selesai memberi Judul, disini saya akan mencoba untuk merubah format text seperti membuat text with background, bold text, italic text, underlined text, smaller text, subscript text dan superscript.<br>

Disini selain saya rubah format text, saya juga rubah alignment pada kedua paragraf, yaitu rata kanan-kiri pada paragraf pertama dan rata kiri pada paragraf kedua, berikut adalah source codenya: <br>

```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- Ini adalah paragraf pertama -->
<p align="justify">Kami sedang belajar <mark style="background-color:yellow">HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat adalah <mark style="background-color:aqua">membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML</mark>.</p>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
<!-- Ini adalah paragraf kedua -->
<p >Ini <small>merupakan sebuah paragraf</small> yang <del>terdiri dari</del>beberapa kalimat<sub> yang </sub>saling <sup>mendukung</sup>sehingga <i>menjadi satu kesatuan</i>. <mark style="background-color: grey">Paragraf dibuat dengan menggunakan tag dasar html.</mark> </p>
```

Maka, tampilannya akan berubah menjadi seperti berikut : <br>
![Memformat Teks](Pic/merubahformatteks.png)<br>

## 4. Menyisipkan Gambar <br>

Disini saya akan menyisipkan gambar logo UPB. File gambar logo UPB diletakkan satu folder dengan file html.<br>

Berikut source codenya :<br>

```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo UPB.png" title="Logo Univeritas Pelita Bangsa">
```

Berikut tampilannya : <br>
![Menyisipkan Gambar 1](Pic/menyisipkangambar1.png)<br>

Disini bisa dilihat bahwa gambar sudah berhasil disisipkan, namun ukuran atau gambarnya terlalu besar. Maka dari itu gambar logo UPB tersebut akan saya perkecil, maka source code berubah menjadi : <br>

```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo UPB.png" width="320" height="240px" title="Logo Univeritas Pelita Bangsa">
```

Tampilan seteleah dirubah ukuran gambar :<br>
![Menyisipkan Gambar 2](Pic/menyisipkangambar2.png)<br>

## 5. Menambahkan Hyperlink
Pada poin terakhir disini saya akan meambahkan hyperlink halaman 1, halaman 2 dan halaman web Google. <br>
Pada halaman 2 isinya adalah jawaban dari soal praktikum

Berikut untuk source codenya :<br>
```
<nav>
    <div align="center">
    <a href="lab1_tag_dasar.html" style="background-color:lightcoral">Dasar HTML</a>
    <a href="lab1_halaman2.html" style="background-color: thistle;">Halaman 2</a>
    <a href="http://www.google.com" style="background-color: lime
    ;">Halaman Web Eksternal Google</a>
    </nav>
    </div>
    <hr>
```

Dan inilah tampilannya : <br>
![Menambahkan Hyperlink](Pic/menambahkanhyperlink.png)<br>
