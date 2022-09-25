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



