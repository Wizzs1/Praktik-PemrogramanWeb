
Nama : Wisnu Ikhwansyah Saputra
  
NIM : 312210305

Kelas : TI 22.A3

  ---
# Praktikum 1 : Tag HTML Dasar

## Membuat Paragraf

    <!--ini adalah paragraf pertama-->
    <p>
        Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di
        Prodi Teknik Informatika Universitas Pelita Bangsa
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
        dalam mengenal tag-tag dasar HTML.
    </p>
    <!--ini adalah paragraf kedua-->
    <p>
        Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
        mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
        tag dasar HTML.
    </p>

   
<img width="631" alt="gambar1" src="https://github.com/Wizzs1/Praktik-PemrogramanWeb/assets/110619093/0b5dc16c-4673-483c-b106-15b40a58a60e">

### mengatur atribut paragraf

    <!--ini adalah paragraf kedua-->
    <p align="right">
        Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
        mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
        tag dasar HTML.
    </p>

<img width="630" alt="Screenshot 2023-09-29 185234" src="https://github.com/Wizzs1/Praktik-PemrogramanWeb/assets/110619093/69ea774f-63fa-4cf6-b5ed-a070f5089d77">

### menambahkan judul

    <!--judul paragraf pertama-->
    <h1>Belajar Dasar HTML</h1>
    <!-- judul paragraf kedua-->
    <h2>Paragraf Pada HTML</h2>

<img width="630" alt="Screenshot 2023-09-29 185830" src="https://github.com/Wizzs1/Praktik-PemrogramanWeb/assets/110619093/0e937db1-a6bc-43df-b5d4-366277dd7134">

### memformat teks

    <!--ini adalah paragraf pertama-->
    <p>
        Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah Pemrograman Web di
        Prodi <b>Teknik Informatika</b> <i>Universitas Pelita Bangsa</i>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
        dalam mengenal tag-tag dasar HTML.
    <h2>Paragraf Pada HTML</h2>
    <!--ini adalah paragraf kedua-->
    <p align="right">
        Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
        mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
        tag dasar HTML.
    </p>

<img width="633" alt="image" src="https://github.com/Wizzs1/Praktik-PemrogramanWeb/assets/110619093/237d0e00-5745-4563-a4bb-323d5910618b">

### menyisipkan gambar

    <h3>Menyisipkan Gambar</h3>
    <!--menambahkan gambar-->
    <img src="liltotto.jpg" width="200">

<img width="631" alt="Screenshot 2023-09-29 195809" src="https://github.com/Wizzs1/Praktik-PemrogramanWeb/assets/110619093/61761680-4f20-4c10-9083-357e3fdaf9f8">

### menambahkan hyperlink

    <!--menambahkan hyperlink-->
    <nav>
        <a href="lab1_halaman2.html">Halaman 2</a>
    </nav>

<img width="632" alt="image" src="https://github.com/Wizzs1/Praktik-PemrogramanWeb/assets/110619093/4a463831-ee38-4120-8f76-e41df294af98">

### Pertanyaan

<b>1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?</b>

Tidak error dan HTML akan berjalan seperti biasa

<b>2. Apa perbedaan dari tag ```< p >``` dengan tag ```< br >``` , berikan penjelasannya!</b>

tag ```<p>``` digunakan untuk membuat paragraf baru, sedangkan tag ```<br>``` bisa digunakan untuk menggerakan teks ke barisan baru.

<b>3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!</b>

```alt``` adalah untuk menyediakan tag alt gambar untuk menggambarkan gambar ke crawler mesin pencari dan pembaca layar untuk aksesibilitas web yang lebih baik. ```title``` adalah untuk memberikan penjelasan tentang tag alt gambar dan URL gambar dalam atribut ```src```.

<b>4. Untuk mengatur ukuran gambar, digunakan atribut ```width``` dan ```height```. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya</b>

Hanya dengan menggunakan ```width``` foto akan menjadi lebih presisi tetapi ```height``` bisa mengatur foto semaunya

<b>5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( ```_blank```, ```_self```, ```_top```, ```_parent``` ), apa yang terjadi pada masing-masing nilai antribut tersebut?</b>

- ```_blank``` : Membuka dokumen yang dituju di tab baru.
- ```_self``` : Membuka dokumen yang dituju di jendela atau frame yang sama dengan elemen yang diklik. Ini adalah nilai default jika atribut target tidak ditentukan.
- ```_top``` : Membuka dokumen yang dituju di jendela penuh, menggantikan semua frame, termasuk frame luar. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti ```_self```.
- ```_parent``` : Membuka dokumen yang dituju di frame parent dari elemen yang diklik. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti ```_self```.
