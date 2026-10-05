Laporan Praktikum 3: CSS Dasar
Nama :  Rafli Putra Sudrajat

Nim : 312510326

Kelas : I251B

Mata Kuliah: Pemrograman Web

Universitas: Universitas Pelita Bangsa

Tujuan Praktikum

Mahasiswa mampu memahami konsep dasar CSS.

Mahasiswa mampu memahami aturan penulisan pada CSS (Internal, Eksternal, dan Inline).

Mahasiswa mampu memahami selector sebagai pengontrol CSS (Elemen, ID, dan Class).

Mahasiswa mampu membuat pengaturan CSS pada HTML.

Langkah-langkah Praktikum

1. Membuat Dokumen HTML Dasar

Langkah pertama adalah membuat dokumen HTML dasar dengan nama lab2_css_dasar.html. Dokumen ini menggunakan struktur HTML5 yang berisi elemen-elemen seperti header, <nav>, dan <div> untuk menyusun kerangka halaman web.

2. Mendeklarasikan CSS Internal

CSS Internal ditulis di dalam tag <style> yang diletakkan pada bagian <head> dokumen HTML. Pada langkah ini, gaya ditambahkan untuk memodifikasi elemen body, header, dan teks h1.

3. Menambahkan Inline CSS

Inline CSS ditulis langsung di dalam baris tag HTML sebagai atribut style. Pada praktikum ini, inline CSS diterapkan pada tag <p> untuk mengubah perataan teks menjadi ke tengah (center) dan mengubah warna tulisan. Gaya ini hanya berdampak pada satu baris elemen tersebut.

4. Membuat CSS Eksternal

CSS Eksternal dipisahkan ke dalam file khusus bernama style_eksternal.css. File ini kemudian dihubungkan ke dokumen HTML menggunakan tag <link rel="stylesheet" href="style_eksternal.css">. Metode ini sangat efisien untuk mengatur gaya di banyak halaman sekaligus.

5. Menambahkan CSS Selector (ID dan Class)

Selector digunakan untuk memilih secara spesifik elemen mana yang akan diubah gayanya:

ID Selector (#): Diterapkan pada elemen spesifik (contoh: #intro). ID bersifat unik dan hanya boleh digunakan satu kali pada satu halaman.

Class Selector (.): Digunakan untuk mengelompokkan beberapa elemen (contoh: .button). Class bisa digunakan berulang kali pada elemen-elemen yang berbeda.

6. Validasi Dokumen CSS (W3C Validator)

Melakukan pengujian kode pada style_eksternal.css menggunakan layanan W3C CSS Validator. Hasil pengecekan menunjukkan pesan "Tidak ditemukan kesalahan", yang berarti kode yang ditulis sudah valid dan sesuai dengan standar web internasional.