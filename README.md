# Lab2Web.
# Praktikum 2 - HTML Lanjutan

Langkah-Langkah Praktikum
1. Membuat Tabel Data Mahasiswa

Pada latihan pertama, dibuat tabel untuk menampilkan data mahasiswa. Tabel terdiri dari kolom NIM, Nama, dan Program Studi.

Elemen HTML yang digunakan adalah:

<table> untuk membuat tabel.
<tr> untuk membuat baris.
<th> untuk membuat judul kolom.
<td> untuk mengisi data tabel.

Hasil:




2. Membuat Tabel Nilai Praktikum

Pada latihan kedua, dibuat tabel nilai praktikum menggunakan struktur tabel yang lebih lengkap.

Elemen yang digunakan:

<caption> sebagai judul tabel.
<thead> sebagai bagian kepala tabel.
<tbody> sebagai isi tabel.
<tfoot> sebagai bagian akhir tabel.

Pada bagian <tfoot> ditampilkan nilai rata-rata mahasiswa.

Hasil:




3. Membuat Form Registrasi Mahasiswa

Pada latihan ketiga, dibuat form registrasi mahasiswa.

Form menggunakan beberapa jenis input, yaitu:

Nama
Email
Password
Tanggal lahir
Jenis kelamin
Keahlian
Program studi
Alamat

Selain itu digunakan tombol Daftar untuk mengirim data dan tombol Reset untuk menghapus isian form.

Hasil:




4. Membuat Validasi Form

Pada latihan berikutnya diterapkan validasi form dasar menggunakan atribut HTML.

Validasi yang digunakan:

required untuk memastikan data wajib diisi.
minlength untuk menentukan jumlah karakter minimum.
min untuk menentukan nilai minimum.
max untuk menentukan nilai maksimum.
type="email" untuk validasi format email.

Contoh:

<input type="text" required minlength="3">
<input type="email" required>
<input type="number" min="17" max="60" required>

Validasi dilakukan oleh browser ketika pengguna mencoba mengirim form dengan data yang belum sesuai.

Hasil:




5. Menggunakan Semantic HTML

Pada latihan semantic HTML, digunakan beberapa elemen untuk membentuk struktur halaman.

Elemen yang digunakan:

<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>

Penggunaan semantic HTML membuat struktur halaman menjadi lebih terorganisir dan mudah dipahami.

Hasil:




6. Menambahkan Multimedia

Pada latihan multimedia ditambahkan audio dan video ke dalam halaman HTML.

Elemen yang digunakan adalah:

<audio controls>
    <source src="media/audio.mp3" type="audio/mpeg">
</audio>

dan:

<video controls width="480">
    <source src="media/video.mp4" type="video/mp4">
</video>

File audio dan video disimpan di dalam folder media.

Hasil:




7. Proyek Mini - Biodata Mahasiswa

Setelah menyelesaikan latihan, dibuat proyek mini berupa halaman Biodata Mahasiswa.

Halaman ini menggabungkan materi yang telah dipelajari sebelumnya, yaitu:

Semantic HTML
Tabel
Form
Validasi form
Data Mahasiswa

Data mahasiswa ditampilkan menggunakan tabel yang berisi:

NIM
Nama
Program Studi
Form Biodata

Form biodata terdiri dari:

Nama
Email
Program Studi
Alamat
Tombol Simpan
Tombol Reset

Beberapa input menggunakan atribut required sebagai validasi form dasar.

Hasil Proyek Mini:




8. Pengujian

Setiap halaman yang telah dibuat dibuka menggunakan browser untuk memastikan kode HTML dapat berjalan dengan baik.

Pengujian meliputi:

Tampilan tabel.
Tampilan dan fungsi form.
Validasi form.
Struktur semantic HTML.
Pemutaran audio.
Pemutaran video.
Tampilan halaman Biodata Mahasiswa.

Screenshot hasil pengujian digunakan sebagai dokumentasi praktikum.
