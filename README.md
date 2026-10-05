# Praktikum 3: CSS Dasar - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 3 Pemrograman Web.

## Identitas Mahasiswa

| Keterangan      | Data                 |
| --------------- | ---------------      |
| **Nama**        | Rafli Putra Sudrajat |
| **Kelas**       | I251B                |
| **NIM**         | 312510326		|
| **Mata Kuliah** | Pemrograman Web      |

### Tujuan Praktikum

Mahasiswa mampu memahami konsep dasar CSS.

Mahasiswa mampu memahami aturan penulisan pada CSS (Internal, Eksternal, dan Inline).

Mahasiswa mampu memahami selector sebagai pengontrol CSS (Elemen, ID, dan Class).

Mahasiswa mampu membuat pengaturan CSS pada HTML.

---

## Struktur Folder Proyek

```
Lab3Web/
├── Lab3_css_dasar.html
├── style_eksternal.css
└── README.md

```
## 1. Struktur File

Struktur file pada praktikum ini adalah sebagai berikut:

<img width="435" height="177" alt="image" src="https://github.com/user-attachments/assets/8a265090-e79d-4f52-a2c9-1bcf6979c358" />

## Langkah-langkah Praktikum

### 1. Membuat Dokumen HTML Dasar

Langkah pertama adalah membuat dokumen HTML dasar dengan nama lab2_css_dasar.html. Dokumen ini menggunakan struktur HTML5 yang berisi elemen-elemen seperti header, <nav>, dan <div> untuk menyusun kerangka halaman web.

<img width="975" height="246" alt="image" src="https://github.com/user-attachments/assets/a743ed0a-0a44-4dcb-969b-08c7d6c03312" />

Selanjutnya buka pada brwoser untuk melihat hasilnya.

<img width="796" height="508" alt="image" src="https://github.com/user-attachments/assets/58a34680-65bf-4c56-a035-81cfbaaa5981" />

### 2. Mendeklarasikan CSS Internal

CSS Internal ditulis di dalam tag <style> yang diletakkan pada bagian <head> dokumen HTML. Pada langkah ini, gaya ditambahkan untuk memodifikasi elemen body, header, dan teks h1.

<img width="437" height="399" alt="image" src="https://github.com/user-attachments/assets/84c361be-2a6b-4d79-b71f-3e1b6d6eeb12" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="847" height="320" alt="image" src="https://github.com/user-attachments/assets/0e80b207-36dc-438f-8878-52a9a0239598" />

### 3. Menambahkan Inline CSS

Inline CSS ditulis langsung di dalam baris tag HTML sebagai atribut style. Pada praktikum ini, inline CSS diterapkan pada tag <p> untuk mengubah perataan teks menjadi ke tengah (center) dan mengubah warna tulisan. Gaya ini hanya berdampak pada satu baris elemen tersebut.

<img width="861" height="35" alt="image" src="https://github.com/user-attachments/assets/be14323c-e35e-4b56-94ce-fb659748e887" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="769" height="224" alt="image" src="https://github.com/user-attachments/assets/84cfc496-21df-43f1-854f-ffeaabe964e6" />


### 4. Membuat CSS Eksternal

CSS Eksternal dipisahkan ke dalam file khusus bernama style_eksternal.css. File ini kemudian dihubungkan ke dokumen HTML menggunakan tag <link rel="stylesheet" href="style_eksternal.css">. Metode ini sangat efisien untuk mengatur gaya di banyak halaman sekaligus.

<img width="393" height="333" alt="image" src="https://github.com/user-attachments/assets/4548197d-64b6-4970-a75a-25faec1e4a49" />

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian
<head>

<img width="975" height="126" alt="image" src="https://github.com/user-attachments/assets/c5968971-2259-4394-a8a9-ce7969f84d80" />


Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="975" height="288" alt="image" src="https://github.com/user-attachments/assets/4431d308-e272-446b-8f49-59adb62cf8cb" />


### 5. Menambahkan CSS Selector (ID dan Class)

Selector digunakan untuk memilih secara spesifik elemen mana yang akan diubah gayanya:

ID Selector (#): Diterapkan pada elemen spesifik (contoh: #intro). ID bersifat unik dan hanya boleh digunakan satu kali pada satu halaman.

Class Selector (.): Digunakan untuk mengelompokkan beberapa elemen (contoh: .button). Class bisa digunakan berulang kali pada elemen-elemen yang berbeda.

<img width="354" height="471" alt="image" src="https://github.com/user-attachments/assets/7f10d93c-004d-4dc5-a402-1688265a7996" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="975" height="339" alt="image" src="https://github.com/user-attachments/assets/308c5d77-7787-46af-a7eb-7e1f16b39943" />


### 6. Validasi Dokumen CSS (W3C Validator)

Melakukan pengujian kode pada style_eksternal.css menggunakan layanan W3C CSS Validator. Hasil pengecekan menunjukkan pesan "Tidak ditemukan kesalahan", yang berarti kode yang ditulis sudah valid dan sesuai dengan standar web internasional.

<img width="1055" height="549" alt="image" src="https://github.com/user-attachments/assets/12f2c224-8aa3-499d-810d-46bbbd8b9993" />
