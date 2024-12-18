# Daftar Nilai Mahasiswa

## Berikut program nya

![Gambar1](https://github.com/Raihanardiansyah/Praktikum_8/blob/main/ss/1.png?raw=true)  
Program tersebut adalah implementasi sederhana dari sebuah kelas Python bernama DaftarNilaiMahasiswa. Berikut adalah penjelasan singkat mengenai fungsi dari kode:  
### 1. Konstruktor (__init__):  
- Inisialisasi objek kelas dengan atribut self.data_mahasiswa, berupa sebuah list kosong yang akan digunakan untuk menyimpan data mahasiswa berupa nama dan nilai mereka.  
### 2.Metode tambah:  
- Metode ini digunakan untuk menambahkan data mahasiswa baru ke dalam atribut data_mahasiswa.  
- Input: nama (nama mahasiswa) dan nilai (nilai mahasiswa).  
- Data akan disimpan dalam bentuk dictionary dengan kunci "nama" dan "nilai".  
- Setelah data ditambahkan, akan dicetak pesan konfirmasi bahwa data berhasil ditambahkan.  
### 3.Metode tampilkan:  
- Metode ini digunakan untuk menampilkan seluruh data mahasiswa yang tersimpan.  
- Jika tidak ada data mahasiswa dalam data_mahasiswa, maka akan dicetak pesan "Belum ada data mahasiswa."  
- Jika ada data, maka akan ditampilkan daftar mahasiswa beserta nilai mereka dalam format yang terurut berdasarkan indeks.

![Gambar2](https://github.com/Raihanardiansyah/Praktikum_8/blob/main/ss/2.png?raw=true)  
### 1.Metode hapus:  
- Digunakan untuk menghapus data mahasiswa berdasarkan nama.  
- Input: nama (nama mahasiswa yang ingin dihapus).  
- Algoritma:  
- Melakukan iterasi pada daftar data_mahasiswa.  
- Jika ditemukan mahasiswa dengan nama yang sesuai, data mahasiswa tersebut akan dihapus dari daftar menggunakan metode .remove().
- Jika data berhasil dihapus, akan mencetak pesan konfirmasi.
- Jika nama tidak ditemukan dalam daftar, akan mencetak pesan bahwa data tidak ditemukan.

### 2. Metode ubah:  
- Digunakan untuk mengubah nilai mahasiswa berdasarkan nama.  
- Input: nama (nama mahasiswa yang ingin diubah) dan nilai_baru (nilai baru untuk mahasiswa tersebut).  
- Algoritma:  
- Melakukan iterasi pada daftar data_mahasiswa.  
- Jika ditemukan mahasiswa dengan nama yang sesuai, nilai mahasiswa tersebut akan diperbarui.  
- Jika data berhasil diubah, akan mencetak pesan konfirmasi.  
- Jika nama tidak ditemukan dalam daftar, akan mencetak pesan bahwa data tidak ditemukan.  

![Gambar3](https://github.com/Raihanardiansyah/Praktikum_8/blob/main/ss/3.png?raw=true)  
Kode yang ditampilkan adalah bagian utama (main) dari program berbasis kelas DaftarNilaiMahasiswa. Berikut adalah penjelasan singkat dari kode tersebut:  
### 1. Inisialisasi Objek:
- Membuat sebuah objek bernama daftar_nilai dari kelas DaftarNilaiMahasiswa. Objek ini akan digunakan untuk menyimpan, menampilkan, mengubah, dan menghapus data mahasiswa.  
### 2. Menambahkan Data Mahasiswa:  
- daftar_nilai.tambah("Ujang", 70): Menambahkan mahasiswa bernama "Ujang" dengan nilai 70.  
- daftar_nilai.tambah("Ikan", 100): Menambahkan mahasiswa bernama "Ikan" dengan nilai 100.  
### 3. Menampilkan Data Mahasiswa:  
- daftar_nilai.tampilkan(): Menampilkan daftar mahasiswa yang telah ditambahkan.  
### 4. Mengubah Nilai Mahasiswa:  
- daftar_nilai.ubah("Ujang", 95): Mengubah nilai mahasiswa bernama "Ujang" dari 70 menjadi 95.  
- daftar_nilai.tampilkan(): Menampilkan data setelah perubahan.  
### 5. Menghapus Data Mahasiswa:  
- daftar_nilai.hapus("Ikan"): Menghapus data mahasiswa bernama "Ikan".  
- daftar_nilai.tampilkan(): Menampilkan data setelah penghapusan.  

### Alur Eksekusi Program:
### 1. Awal: Menambahkan dua data mahasiswa:
- "Ujang" dengan nilai 70.
- "Ikan" dengan nilai 100.
- Data ini kemudian ditampilkan.
### 2. Perubahan:   
- Nilai "Ujang" diubah menjadi 95, dan daftar data mahasiswa ditampilkan kembali untuk memverifikasi perubahan.
### 3. Penghapusan:  
- Data mahasiswa bernama "Ikan" dihapus, kemudian daftar data mahasiswa ditampilkan lagi untuk memastikan penghapusan.

### Berikut Flowchartnya  
![Gambar4](https://github.com/Raihanardiansyah/Praktikum_8/blob/main/ss/flowchart.jpg?raw=true)  
Flowchart tersebut menjelaskan alur proses pengolahan data mahasiswa dengan beberapa fitur utama yang disediakan dalam menu pilihan. Berikut adalah penjelasan singkatnya:  
### 1. Tampilkan Menu Pilihan:  
Pengguna diberikan beberapa opsi:  
- Tambah data mahasiswa  
- Tampilkan data mahasiswa  
- Ubah data mahasiswa  
- Hapus data mahasiswa  
- Keluar dari program
### 2. Input Pilihan:  
Pengguna diminta untuk memilih salah satu opsi dari menu.  
- Jika pilihan valid, proses berlanjut sesuai dengan opsi yang dipilih.  
- Jika tidak, proses berakhir.  
### 3. Proses Berdasarkan Pilihan:  
- Tambah Data Mahasiswa: Pengguna dapat memasukkan nama dan nilai mahasiswa untuk menambahkannya ke data.  
- Tampilkan Data Mahasiswa: Menampilkan data mahasiswa yang telah ditambahkan.  
- Ubah Data Mahasiswa: Mengedit data mahasiswa yang sudah ada.  
- Hapus Data Mahasiswa: Menghapus data mahasiswa yang dipilih.  

![Gambar5](https://github.com/Raihanardiansyah/Praktikum_8/blob/main/ss/diagram.png?raw=true)  
Diagram tersebut adalah diagram kelas (class diagram) yang menggambarkan struktur dari kelas DaftarNilaiMahasiswa. Berikut adalah penjelasan singkatnya:  
### 1. Kelas DaftarNilaiMahasiswa:  
### Atribut:  
-  data_mahasiswa: list  
Sebuah atribut yang berupa daftar (list) untuk menyimpan data mahasiswa.  
### Metode:  
- __init__()  
Konstruktor yang digunakan untuk menginisialisasi atribut data_mahasiswa sebagai list kosong.  
- tambah(nama: str, nim: int, gender: str, nilai: int)  
Metode untuk menambahkan data mahasiswa ke dalam daftar data_mahasiswa. Data yang disimpan meliputi nama, NIM, jenis kelamin, dan nilai.  
- tampilkan()  
Metode untuk menampilkan seluruh data mahasiswa yang telah tersimpan.  
- hapus(nama: str)  
Metode untuk menghapus data mahasiswa berdasarkan nama.  
- ubah(nama: str, nim: int, gender: str, nilai: int)  
Metode untuk mengubah data mahasiswa berdasarkan nama. Data yang dapat diubah meliputi nama, NIM, jenis kelamin, dan nilai.  
- menu_interaktif()  
Metode untuk menjalankan menu interaktif yang memungkinkan pengguna untuk memilih fungsi seperti menambah, menampilkan, mengubah, atau menghapus data mahasiswa.  

### 2. Relasi Antar Metode:  
- Diagram menunjukkan hubungan antar metode dan fungsi-fungsi yang diimplementasikan dalam kelas. Setiap metode memiliki peran spesifik untuk memanipulasi data mahasiswa.
### 3. Fungsionalitas:  
- Diagram ini menggambarkan bahwa kelas DaftarNilaiMahasiswa dirancang untuk mengelola data mahasiswa secara terstruktur, mulai dari penambahan, penghapusan, pengubahan, hingga menampilkan data.

Diagram ini memberikan gambaran bahwa kelas DaftarNilaiMahasiswa adalah solusi lengkap untuk manajemen data mahasiswa dalam bentuk OOP (Object-Oriented Programming)  
