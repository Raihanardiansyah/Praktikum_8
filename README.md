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
