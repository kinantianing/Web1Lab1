# Web1Lab1

## Belajar Tag Dasar HTML

### 1. Membuat Paragraf
Kode tag untuk paragraf adalah `<p>`. <br>
contoh codingnya seperti :
 ```
        <!-- ini paragraf pertama -->
        <p>Kami sedang belajar HTML dasar, pada matakuliah pemrograman web
            di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
            yang kami dapat adalah membuat tampilan sederhana dalam rangka mengenal tag-tag dasar HTML</p>
  
        <!-- ini paragraf kedua -->
        <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
            mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
            tag dasar HTML</p>
```
<br>

ini adalah tampilannya :
![Gambar 1.1](screenshot/latihan1.1.PNG) <br>
 
 Kemudian atur atribut paragraf, contohnya align. <br>
 nilai untuk atribut align seperti justify, center, left, right.

 Kode tag untuk mengatur atribut paragraf adalah `<p align=" ">` <br>
 tambahkan atribut seperti contoh dibawah ini :
 ```
        <!-- ini paragraf pertama -->
        <p align="justify">Kami sedang belajar HTML dasar, pada matakuliah pemrograman web
            di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
            yang kami dapat adalah membuat tampilan sederhana dalam rangka mengenal tag-tag dasar HTML</p>
  
        <!-- ini paragraf kedua -->
        <p align="justify">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
            mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
            tag dasar HTML</p>
 ```
<br>

ini adalah tampilannya :
![Gambar 1.2](screenshot/latihan1.2.PNG) <br>

### 2. Menambahkan Judul
Judul memiliki 6 level, mulai dari h1 sampai dengan h6. <br>
Tambahkan judul dengan `<h1>` sebelum paragraf pertama, dan `<h2>` sebelum paragraf kedua. <br>
Contoh codingnya seperti :
 ```
    <!-- judul paragraf pertama -->
      <h1>Belajar Dasar HTML</h1>
        <!-- ini paragraf pertama -->
        <p align="justify">Kami sedang belajar HTML dasar, pada matakuliah pemrograman web
            di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
            yang kami dapat adalah membuat tampilan sederhana dalam rangka mengenal tag-tag dasar HTML</p>
  
    <!-- judul paragraf pertama -->
      <h2>Paragraf Pada HTML</h2>
        <!-- ini paragraf kedua -->
        <p align="justify">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
            mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
            tag dasar HTML</p>
```
<br>

ini adalah tampilannya :
![Gambar 2](screenshot/latihan2.PNG) <br>

### 3. Memformat Teks
Ada beberapa tag yang bisa digunakan untuk memformat teks pada paragraf. <br>
Diantaranya seperti : `<i>, <u>, <b>, <mark>, <small>`. <br>
contoh codingnya seperti :
 ```
    <!-- judul paragraf pertama -->
      <h1>Belajar Dasar HTML</h1>
        <!-- ini paragraf pertama -->
        <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>pemrograman web</b>
            di Prodi <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama
            yang kami dapat adalah membuat tampilan sederhana dalam rangka mengenal tag-tag dasar HTML</p>
  
    <!-- judul paragraf pertama -->
      <h2>Paragraf Pada HTML</h2>
        <!-- ini paragraf kedua -->
        <p align="justify">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
            mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
            tag dasar HTML</p>
```
<br>

ini adalah tampilannya :
![Gambar 3](screenshot/latihan3.PNG) <br>

### 4. Menyisipkan Gambar
Siapkan gambar yang akan disisipkan pda halaman web, simpan gambar satu folder dengan file html. <br>
kode untuk menyisipkan gambar adalah : `<img src=" ">`. <br>
contoh codingnya seperti :
 ```
    <!-- sub judul paragraf -->
      <h3>Menambahkan Gambar</h3>
        <!-- menambah gambar -->
        <img src="Logo_UPB.PNG" width="200" title="Logo Universitas Pelita Bangsa">
```
<br>

ini adalah tampilannya :
![Gambar 4](screenshot/latihan3.PNG) <br>



