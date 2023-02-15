# LATIHAN2DPBO2023
### Saya Mochamad Khaairi NIM 2106416 mengerjakan Latihan 1 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Deskripsi Tugas
Buatlah program berbasis OOP menggunakan bahasa pemrograman C++, Java, Python, dan PHP yang mengimplementasikan konsep Multi-level Inheritance  pada kelas - kelas tersebut:
* Mahasiswa: NIM, nama, jenis_kelamin, fakultas, prodi
* Human: NIK, nama, jenis_kelamin
* SivitasAkademik: asal_universitas, email_edu

## Desain Program
Program didesain menjadi empat class
* **Human**
* **Sivitas**
* **Mahasiswa**
* **Pilih**

Class `Human` akan menjadi parent utama dan memiliki child yaitu class `Sivitas`, serta class `Sivitas` memiliki child yaitu class `Mahasiswa` yang artinya class `Mahasiswa` menjadi cucu dari class `Human`.

Pada class `Human` terdapat tiga atribut:
* **nik** -> berisi NIK mahasiswa, `string`
* **name** -> berisi nama mahasiswa, `string`
* **gender** -> berisi jenis kelamin mahasiswa, `string`

tiap atribut memiliki setter dan getternya masing-masing.

Pada class `Sivitas` yang merupakan child dari class `Human` (mengapa child karena Sivitas merupakan Human / manusia) maka class `Sivitas` mewarisi atribut dan method dari class parentnya yaitu class `Human`, lalu class `Sivitas` sendiri memiliki atributnya sendiri yang membuatnya "lebih baik" ketimbang class parentnya. Atribut tambahannya yaitu:
* **univ** -> berisi asal universitas, `string`
* **email** -> berisi email univeritas, `string`

Pada class `Mahasiswa` yang merupakan child dari class `Sivitas` (mengapa child karena Mahasiswa merupakan Sivitas sekaligus juga Human) memiliki atribut tambahan selain dari parentnya yaitu:
* **nim** -> berisi NIM mahasiswa, `string`
* **faculty** -> berisi fakultas mahasiswa, `string`
* **major** -> berisi program studi, `string`

## Alur Program
Pertama program akan menampilkan menu pilihan dan user diminta untuk menginput salah satu dari ketiga pilihan dan jika program sudah selesai menjalankan perintah maka proses (inputan untuk pemilihan menu) akan dijalankan berulang sampai user menginput perintah untuk mengakhiiri program.
* masukkan (1) untuk menjalankan perintah `add`
* masukkan (2) untuk menjalankan perintah `show`
* masukkan (3) untuk mengakhiri program

## Dokumentasi
Pada program Java

![Screenshot - Java](https://user-images.githubusercontent.com/100757455/218931751-ed49b146-d9c6-414e-abc8-c3a08ab49cac.png)
