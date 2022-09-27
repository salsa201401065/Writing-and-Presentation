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
 
 ```html
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
 
 ```
 
•	Anatomi dari HTML

![image](https://user-images.githubusercontent.com/85721113/192193510-73c36530-e211-404f-a508-32fd8b1228e5.png)

•	Hal yang disebut sebagai elemen pada HTML jika dimulai dari tag awal hingga tag penutup

![image](https://user-images.githubusercontent.com/85721113/192193541-4c3a4f88-aed0-4d14-b3df-269c3857065f.png)

•	Terdapat banyak atribut pada HTML, bahkan terdapat beberapa elemen yang harus diikuti oleh atribut di HTML. Contohnya : <img src = “ ”  /> , <a href “ ” />, dan lainnya

### **HTML secara manual dan menggunakan live server dari VS Code**
•	Pertama-tama jika menggunakan text editor VSCode, harus menginstall dulu ekstensi yang bernama “live server”

![image](https://user-images.githubusercontent.com/85721113/192193679-1e0cd04b-a7ad-44fb-bc8c-11962be3aba3.png)

•	Jika itu cara manual, setiap ngesave developer harus merefresh halaman web terlebih dahulu agar perubahan terbaru tampak di halaman web browser

### **Pengimplementasikan tag HTML yang populer**
Beberapa tag HTML yang sering digunakan :
 
•	Tag untuk membuat paragraph

```html
<p>Climate change refers to long-term shifts in temperatures and weather patterns. These shifts may be natural, such as through variations in the solar cycle. But since the 1800s, human activities have been the main driver of climate change, primarily due to burning fossil fuels like coal, oil and gas.</p>
```

•	Tag untuk membuat baris baru

```html
<br>
```

•	Tag untuk menebalkan huruf atau kalimat

```html
<b>ini adalah huruf cetak tebal</b>
```

•	Tag membuat huruf cetak miring

```html
<i>ini adalah huruf cetak miring</i>
```

•	Tag untuk memasukkan gambar
```html
<img src = “” />
 ```
 
•	Tag untuk membuat link

```html
<a href  = “” />
```

•	Tag untuk list
 
 Untuk unordered list (list tidak berurutan)
```html
<ul>
        <li>Javascript</li>
        <li>PHP</li>
        <li>Java</li>
        <li>Python</li>
        <li>Kotlin</li>
</ul>
```

Untuk ordered list (list berurutan)
```html
<ol>
        <li>Javascript</li>
        <li>PHP</li>
        <li>Java</li>
        <li>Python</li>
        <li>Kotlin</li>
 </ol>
 ```
      
•	Tag Heading

```html
<h1>ini heading 1</h1>
<h2>ini heading 2</h2>
<h3>ini heading 3</h3>
<h4>ini heading 4</h4>
<h5>ini heading 5</h5>
<h6>ini heading 6</h6>	
```

Semakin ke atas angkanya ukuran huruf akan semakin kecil

### **Pengimplementasian semantic HTML**
•	Semantic HTML berfungsi agar dokumen HTML kita akan mudah dibaca, baik itu oleh manusia maupun mesin. 

Jika menggunakan <div> terllu banyak untuk membuat class, maka terkadang akan ada kesulitan dalam membaca dokumen.

```html
<div id="header"></div>
<div class="section">
	<div class="article">
		<div class="figure">
			<img>
			<div class="figcaption"></div>
		</div>
	</div>
</div>
<div id="footer"></div>
```
Dokumen akan lebih mudah dibaca jika menggunakan semantic HTML :

```html
<header></header>
<section>
	<article>
		<figure>
			<img>
			<figcaption></figcaption>
		</figure>
	</article>
</section>
<footer></footer>
```

•	Terdapat beberapa macam tag semantic HTML yang bisa digunakan

![Screenshot (92)](https://user-images.githubusercontent.com/85721113/192198458-5a4d59d2-f585-4089-ac32-2a290fd47b9c.png)


### **Publish website sampai ke tahap deployment**
•	Untuk mempublish aplikasi website yang dibuat, kita dapat menggunakan app yang bernama netlify dengan cara login terlebih dahulu melalui akun github yang telah kita miliki
	
## **CSS**

### **CSS pada web development**
•	CSS membuat tampilan website tampak lebih menarik

•	Jika dianalogikan pada manusia, CSS merupakan kulit serta outfit yang digunakan oleh manusia agar tampil menarik


### **Styling CSS : Cara menyisipkan CSS ke dalam HTML**
•	Inline CSS
Disisipkan langsung di dalam tag HTML


```html
<h2 style="color:red;font-family:sans">Ini judul artikel</h2>
```

•	Internal CSS
Code CSS disisipkan di dalam tag <style></style>.  Tag <style> bisa ditulis di dalam tag <head>, bisa juga ditulis di dalam tag <body>. Namun kebanyakan orang menulisnya di dalam <head>
```html
<head>
  <title>Contoh Internal CSS</title>
  <!-- penulisan internal css dalam tag head -->
  <style type="text/css">
    p{
      font-family: serif;
      line-height: 1.75em;
      font-size: 18px;
    }
    i { 
      font-family: sans;
      color: orange;
    }
  </style>
</head>
```
•	File CSS dibuat terpisah, maksudnya tidak berada di file yang sama dengan HTML. Ekstensi filenya .css dan alamat file diletakkan di dalam tag <head></head> pada file HTML
```html	
<head>
	<link rel="stylesheet" href="style2.css">
</head> 
```
### **Penggunaan sintaks dasar dari CSS**
•	CSS Selector elements 
```html	
	<style>
            h1 { color: red; }
            p { color: blue; }
		</style>
```

•	CSS Selector by Id
```html	
Selector yang bersifat unik, hanya dapat dipanggil sekali saja.

```html	
#putih {
            color: pink;
        } 
```

•	CSS Selector by Class
Selector yang bisa di panggil berulang-ulang.
```html	
 .content{
            background-color: bisque;
            display: flex;
            justify-content: center;
        }
```
•	Properti yang sering digunakan

Background-color

![image](https://user-images.githubusercontent.com/85721113/192550667-ec6f70ee-7a39-4ea8-a3e4-7ac1f4b888d1.png)

Font-size

![image](https://user-images.githubusercontent.com/85721113/192550696-f4a323e0-7cc3-40a9-ba27-b8d256486143.png)

Color 
![image](https://user-images.githubusercontent.com/85721113/192550764-fc9b8c75-a475-45e1-ab95-e2683a6de059.png)


Dan banyak lainya


### **Metode responsive web design menggunakan CSS **
•	View port
 viewport adalah daerah pada layar yang menampilkan suatu konten. Dalam konteks kita kali ini, tentu viewport adalah daerah yang menampilkan halaman web yang sedang kita akses
```html	
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

•	Position : relative
diposisikan relatif dari posisi normalnya

•	Position : static
Merupakan posisi default, elemen ini tidak terpengaruh oleh top right, left, ataupun bottom.

•	Position : absolute
diposisikan relative dengan posisi ancestor terdekat yang posisinya bukan static

•	Position : fixed
diposisikan relatif terhadap viewport browser, di mana akan selalu berada di tempat yang sama jika walaupun halaman website di-scroll

•	Position : sticky
diposisikan berdasarkan scroll halaman dari user
•	Box Model

![image](https://user-images.githubusercontent.com/85721113/192554522-bc7a7e3f-2c6e-4b37-8af6-3acaec8696b9.png)

![image](https://user-images.githubusercontent.com/85721113/192554578-87ff7b98-2bfd-4e51-91bf-2b2c1c87977c.png)

### **Penggunaan flexbox**
•	Justift-content

Flex-start - semua item akan ditempatkan di depan seperti pada gambar di atas

Flex-end   semua item akan ditempatkan di belakang

center akan memampatkan semua item ke tengah

space-between akan memberi ruang pada setiap dua item yang bersebelahan

space-around akan memberi ruang pada sekitar tiap item















