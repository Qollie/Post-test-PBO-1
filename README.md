# Dokumentasi MinPro PBO Tema Studio Musik Sederhana

**Nama**: Muhammad Pidha Iqbal Fadillah  
**NIM**: 2309116033  
**Program Studi**: Sistem Informasi A 2023

## Deskripsi Program
Studio Musik Sederhana adalah sebuah program simulasi studio musik yang memungkinkan pengguna untuk melihat daftar lagu, menambahkan lagu baru, menghapus lagu yang ada, serta memperbarui informasi lagu seperti judul, artis, genre, dan durasi. Program ini ditulis dalam bahasa pemrograman Java dengan konsep CRUD (Create, Read, Update, Delete) yang diimplementasikan melalui dua kelas utama dan menggunakan struktur **ArrayList** untuk menyimpan data lagu.

## Fitur
- **Tampilkan Daftar Lagu (Read)**: Menampilkan semua lagu yang tersedia di studio beserta artis, genre, dan durasinya.
- **Tambah Lagu (Create)**: Menambahkan lagu baru ke dalam studio dengan memasukkan judul, artis, genre, dan durasi.
- **Hapus Lagu (Delete)**: Menghapus lagu dari daftar berdasarkan judul lagu yang dimasukkan oleh pengguna.
- **Update Lagu (Update)**: Memperbarui informasi lagu seperti judul, artis, genre, dan durasi berdasarkan judul lagu.
- **Validasi Input**: Menangani kesalahan input seperti judul lagu yang tidak valid atau pilihan menu yang salah.

## Class
Program ini memiliki dua class utama:

1. **Lagu**
   - **Deskripsi**: Kelas ini merepresentasikan entitas lagu dalam studio musik. Setiap lagu memiliki atribut judul, artis, genre, dan durasi.
   - **Properties**:
     - judul: Judul lagu.
     - artis: Nama artis dari lagu tersebut.
     - genre: Genre lagu.
     - durasi: Durasi lagu (dalam menit).
   - **Method**:
     - toString(): Mengembalikan informasi lengkap tentang lagu dalam format teks.
   - **Constructor**: Menginisialisasi objek Lagu dengan judul, artis, genre, dan durasi yang diberikan.

2. **StudioMusik**
   - **Deskripsi**: Kelas ini mengelola operasi CRUD terhadap daftar lagu. Menggunakan struktur data **ArrayList** untuk menyimpan objek **Lagu**.
   - **Properties**:
     - daftarLagu: ArrayList yang menyimpan objek **Lagu**.
   - **Method**:
     - tambahLagu(): Menambahkan lagu baru ke dalam daftar.
     - hapusLagu(): Menghapus lagu dari daftar berdasarkan judul lagu.
     - perbaruiLagu(): Memperbarui informasi lagu pada posisi tertentu.
     - tampilkanLagu(): Menampilkan semua lagu yang ada di studio musik.
   - **Constructor**: Menambahkan beberapa lagu default ketika studio musik dibuat.

## Package
Program ini menggunakan minimal dua package:
1. **musik**: Berisi class yang merepresentasikan entitas lagu dalam program.
2. **mainProgram**: Berisi class yang mengelola logika CRUD untuk studio musik.

## Alur Program
![image](https://github.com/user-attachments/assets/077f1745-2d01-4434-8982-46c41e0ae9c8)  
Pertama-tama user bisa memilih studio musik mana yang mau dilihat atau diakses, semisalkan user
salah memilih studio user bisa mengganti nya dengan opsi "ganti studio"


**Create**

![image](https://github.com/user-attachments/assets/e17cd7b7-40a2-474a-8515-0d75d4254b46)  
Setelah memilih studio, user dapat memilih beberapa opsi dari menu yang telah ditampilkan.
Jika user memilih untuk menambah lagu maka akan diminta inputan untuk judul, nama artis, genre, dan durasi


**Read**

![image](https://github.com/user-attachments/assets/b54427fe-3699-49c4-bcd3-f9ca70668b62)  
Setelah menambahkan lagu, user juga dapat memilih untuk melihat daftar lagu yang sudah ada di studio musik yang sedang diakses. Pada pilihan Lihat Daftar Lagu, sistem akan menampilkan daftar lagu beserta detail seperti judul, artis, genre, dan durasi.


**Update**

![image](https://github.com/user-attachments/assets/55dad8ee-996d-4efd-ab8d-cef92ed9fd8f)  
Fitur berikutnya adalah Edit Lagu, di mana user dapat mengubah informasi dari sebuah lagu yang sudah ada. User akan memilih lagu berdasarkan nomor urut dari daftar lagu yang ditampilkan, dan dapat mengganti judul, artis, genre, dan durasi lagu tersebut.


**Delete**

![image](https://github.com/user-attachments/assets/b0fd5fb0-dad3-43a8-a395-317ac9668e87)  
Fitur Hapus Lagu memungkinkan user untuk menghapus lagu dari daftar. Sama seperti fitur Edit Lagu, user akan memilih nomor lagu yang ingin dihapus dari daftar. Setelah konfirmasi, lagu tersebut akan dihapus dari daftar studio musik.


**Ganti Studio**

![image](https://github.com/user-attachments/assets/16c63f32-1e66-47cb-b2ef-a1914dfc3d26)  
Jika user ingin berpindah ke studio musik lain, mereka dapat menggunakan opsi Ganti Studio. Opsi ini akan membawa user kembali ke menu pemilihan studio, dan user dapat memilih studio lain untuk dikelola tanpa keluar dari aplikasi.


**Exit**

![image](https://github.com/user-attachments/assets/db56cf33-699f-46fb-9ab3-a10fc2f7c347)

Setelah selesai menggunakan sistem, user dapat memilih opsi Keluar untuk mengakhiri program. Program akan ditutup dan semua perubahan akan tersimpan.

