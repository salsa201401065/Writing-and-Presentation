# Writing-and-Presentation Week1
## **Unix Command Line**
### **Shell**
•	Salah satu aplikasi dari command line adalah shell yang berfungsi untuk menginstruksikan OS
### **Command Line Interface**
•	Dari segi tampilan, aplikasi terbagi atas dua, yaitu CLI (Command Line Interface) dan GUI (Grafical User Interface)

•	CLI hanya dapat menampilkan aplikasi dalam bentuk teks

•	GUI dapat menampilkan aplikasi dalam bentuk grafis (tampilan) berupa teks, media seperti foto dan video, serta suara seperti wa, youtube, dll
### **Mengakses CLI dan menggunakan terminal**
•	Mengakses CLI dapat dilakukan dengan berbagai shell sh, bash, zsh, dan cmd 

•	Cmd merupakan shell yang biasa digunakan di windows

•	Sh merupakan shell yang digunakan pada linux yang banyak digunakan oleh para development
### **File System Structure**
•	Strukturnya berbentuk pohon (tree)

•	Menjelaskan bagaimana suatu data disimpan pada sistem

### **Command untuk melihat current working directory**
•	Menggunakan perintah ‘pwd’ untuk melihat status kita sekarang lagi di file dan folder mana.

![image](https://user-images.githubusercontent.com/85721113/192131450-6c464f0c-2aa9-45c4-94b1-9199a51ca3c5.png)

### **Command untuk melihat isi sebuah directory**
•	Untuk melihat isi dari folder yang kita buka, kita dapat menggunakan perintah ‘ls’

![image](https://user-images.githubusercontent.com/85721113/192131615-d35ef8c3-e623-4316-aa05-0bf6f64c6b29.png)

### **Command untuk berpindah directory**
•	Untuk berpindah directory, kita dapat menggunakan perintah ‘cd’. Caranya dengan : cd(spasi)(directory yang dituju)

![image](https://user-images.githubusercontent.com/85721113/192131625-96d4bffe-7fdb-49f3-b993-f7a155c6ffb5.png)

•	Selain itu cd juga dapat kita gunakan untuk keluar dari suatu atau beberapa directory

![image](https://user-images.githubusercontent.com/85721113/192131634-2f65ce12-8119-48ed-a3a8-a52c60e2bd9a.png)

### **Command untuk melihat isi file**

•	Untuk melihat keseluruhan isi file, kita dapat menggunakan perintah ‘cat’, misal kita ingin melihat keseluruhan isi dari sebuah file txt (karena CLI hanya bisa menamapilkan dalam bentuk text, tidak dalam bentuk media). Caranya : cat(spasi)(‘namaFile’)

![image](https://user-images.githubusercontent.com/85721113/192131650-0497cfd3-7172-459a-aba2-916c1905c203.png)

•	Untuk melihat beberapa baris atas dari isi file, kita dapat menggunakan perintah ‘head’. Caranya : head(spasi)(‘namaFile’)

![image](https://user-images.githubusercontent.com/85721113/192131657-a7ae89ad-388d-4ccf-a9e9-e19d8deebd50.png)

•	Untuk melihat beberapa baris bawah dari isi file, kita dapat menggunakan perintah ‘tail’. Caranya : tail(spasi)(‘namaFile’)

![image](https://user-images.githubusercontent.com/85721113/192131667-1fbd1e53-c396-4b3d-8f0d-62ac4ac6a79d.png)

### **Command untuk membuat file & direktori**
•	Untuk membuat direktori kita dapat menggunakan perintah ‘mkdir’. Cara menggunakannya : mkdir(spasi)(‘namaFolder’)

![image](https://user-images.githubusercontent.com/85721113/192131744-05e83619-41e3-4b5a-b53f-578ad28ef135.png)

•	Untuk membuat file baru, misalnya file txt kita dapat menggunakan perintah ‘touch’. Caranya dengan menggunakan : touch(spasi)(namaFile)

![image](https://user-images.githubusercontent.com/85721113/192131753-8bf730cd-77d3-411d-b4db-d25a71e0fdf9.png)

### **Command untuk menyalin file & direktori**
•	Untuk menyalin file kita dapat menggunakan perintah ‘cp’. Caranya : cp(spasi)(namaFile yang akan disalin)(spasi)(namaFilebaru yang disalin)

![image](https://user-images.githubusercontent.com/85721113/192131762-71904975-e10f-4760-bd40-551bf09edd5c.png)

•	Untuk menyalin folder kita dapat menggunakan perintah ‘cp’. Caranya : cp(spasi)(-r)(spasi)(namaFolder yang akan disalin)(spasi)(namaFolderbaru yang disalin)

![image](https://user-images.githubusercontent.com/85721113/192131766-4e0d8d2b-3d13-47b2-be40-bcc6b0c39d79.png)

### **Command untuk memindahkan atau me-rename file dan direktori**
•	Untuk memindahkan suatu file ke dalam suatu folder, kita dapat menggunakan perintah ‘mv’. Caranya : mv(spasi)(namaFile yang akan dpindahkan)(spasi)(alamat folder tujuan)

![image](https://user-images.githubusercontent.com/85721113/192131779-18ea3363-ab8f-458a-80cf-04af9d71b2b7.png)

•	Untuk memindahkan suatu folder ke dalam suatu folder, kita dapat menggunakan perintah ‘mv’. Caranya : mv(spasi)(namaFolder yang akan dpindahkan)(spasi)(alamat folder tujuan)

![image](https://user-images.githubusercontent.com/85721113/192131791-f240d585-9769-4704-a729-f62d3a47f293.png)

•	Untuk merename suatu folder, kita dapat menggunakan perintah ‘mv’. Caranya : mv(spasi)(namaFolder yang lama)(spasi)(namaFolder yang baru)

![image](https://user-images.githubusercontent.com/85721113/192131801-83848143-d123-4b6a-953a-1ff4c24b4175.png)

•	Untuk merename suatu folder, kita dapat menggunakan perintah ‘mv’. Caranya : mv(spasi)(namaFile yang lama)(spasi)(namaFile yang baru)

![image](https://user-images.githubusercontent.com/85721113/192131809-3ba69913-2acd-4b36-a3d5-d42a04354ca8.png)

### **Command untuk menghapus file & direktori**
•	Jika ingin menghapus suatu folder, kita dapat menggunakan perintah ‘rm’. Caranya : rm(spasi)-r(spasi)(Alamat folder yang akan dihapus)

![image](https://user-images.githubusercontent.com/85721113/192131827-1163ec96-9adf-44cd-98ca-61197ba870ea.png)

•	Jika ingin menghapus suatu file, kita dapat menggunakan perintah ‘rm’. Caranya : rm(spasi)(namaFile yang akan dihapus)

![image](https://user-images.githubusercontent.com/85721113/192131834-8b99ee83-62db-4b1e-a7d5-06d7b75eb19c.png)

## **Git and GitHub**
### **Kegunaan Git dan GitHub**
Git dan GitHub merupakan sesuatu yang wajib digunakan oleh seorang developer dalam mengerjakan projek yang dibuat. Kegunaan dari Git dan GitHub sendiri Jika terjadi perubahan atau penambahan pada projek yang kita kerjakan bersama dengan para developer lainnya, kita dapat mengetahui informasi tersebut. Hal ini juga memudahkan para developer yang berkolaborasi dalam mengerjakan suatu projek yang kemudian projek tersebut akan di simpan di repository github.
### **Perbedaann antara Git dan GitHub**
•	Git adalah software yang digunakan untuk mengelola source code dari projek yang sedang dikerjakan. 

•	GitHub adalah layanan hosting berbasis web yang berguna sebagai wadah untuk menampung atau menyimpan git.
### **Alur kerja dari Git dan GitHub**

![image](https://user-images.githubusercontent.com/85721113/192149552-e0b09517-5326-4440-83ea-554a2525e5c3.png)

•	Melakukan setup

•	Membuat repository

•	Menandakan file yang akan dilacak perubahannya

•	Melakukan commit dan membuat keterangan terhadap setiap perubahan

•	Mempublish repository projek  ke GitHub


### **Membuat repository Git**

•	Untuk langkah awal, jangan lupa melakukan setup dengan menggunakan git config --global user.name “<nama user>”, config –global user.email <email user>

•	Lakukan pengecekan apakah setup berhasil melalui git config --list

•	Untuk membuat repository baru, kita dapat menggunakan perintah git init 

![image](https://user-images.githubusercontent.com/85721113/192149585-26b51330-8441-47d0-bf3d-c8a341f246c4.png)

### **Melakukan commit pada Git**

•	Untuk melihat status dari file, kita dapat menggunakan perintah git status 

![image](https://user-images.githubusercontent.com/85721113/192149637-2b71b23e-b71d-47de-98e2-8bc8195ede6d.png)

•	Untuk melacak perubahan, kita harus menandakan file yang akan dilacak menggunakan perintah git add . 

![image](https://user-images.githubusercontent.com/85721113/192149643-1998a537-8696-4634-bb37-a86260fef58f.png)

•	Setelah ditandain, perubahan tersebut dapat disimpan dan diberi keterangan terhadap file yang berubah dengan cara git commit -m “<komentar>”

![image](https://user-images.githubusercontent.com/85721113/192149650-fcb5204e-90e6-4d7c-88bd-56f013f70328.png)

•	Mengecek hasil penyimpanan yang telah di commit dalam baris singkat dapat menggunakan perintah git log –oneline

![image](https://user-images.githubusercontent.com/85721113/192149662-1d695dc0-0612-400f-89f8-ce91a1971456.png)

•	Untuk pindah ke spesifik file yang mau kita tuju, kita dapat menggunakan perintah git checkout <kode commit file>

![image](https://user-images.githubusercontent.com/85721113/192149666-c88c097d-08ab-40f1-a981-f486feb4a875.png)

### **Mempublish aplikasi ke GitHub**

•	Untuk melakukan publish, langkah yang harus kita lakukan pertama kali adalah membuat repository di akun github kita

![image](https://user-images.githubusercontent.com/85721113/192149692-fcfc6997-abd5-423f-9e70-cd9a5bddbfca.png)

•	Langkah berikutnya adalah melakukan perintah git remote untuk menghubungkan repository dengan github

 ![image](https://user-images.githubusercontent.com/85721113/192149705-a4202275-1c4b-4ff7-b202-54798ba0d65b.png)

•	Selanjutnya gunkan perintah git push untuk mengupload repository di github

![image](https://user-images.githubusercontent.com/85721113/192149709-2dddde26-7824-4a31-ada0-47d81e78fc98.png)

### **Melakukan cloning Git dan GitHub**

•	Untuk melakukan cloning kita dapat menggunakan perintah git remote 

![image](https://user-images.githubusercontent.com/85721113/192149718-76f1f326-a1c0-4897-a8bc-ee1263604029.png)

## **HTML**
### **Peran HTML pada web development**
•	HTML dijadikan kerangka dalam sebuah website, analoginya jika manusia, HTML merupakan kerangka manusia

•	Tidak membuat halaman website menarik dan interaktif

•	Bukan merupakan bahasa pemerograman karena tidak bisa mengolah data

### **Tools pendukung dalam menggunakan HTML**
•	Code editor, contoh : Visual Studio Code, Notepad++, Sublime Text

•	Web browser, untuk mempresentasikan hasil codingan, contoh : chrome, mircosoft edge

### **HTML sederhana**
•	HTML dapat dituliskan tanpa struktur, tapi lebih baik menggunakan struktur. Struktur dasar HTML :

<!DOCTYPE html>
<html lang="en">
  <head>
     <meta charset="UTF-8" />
     <meta http-equiv="X-UA-Compatible" content="IE=edge" />
     <meta name="viewport" content="width=device-width, initial-scale=1.0" />
     <title>Belajar HTML</title>
  </head>
 <body>
 </body>
</html>

### **Kegunaan Git dan GitHub**
### **Kegunaan Git dan GitHub**
### **Kegunaan Git dan GitHub**







