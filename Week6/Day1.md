# Writing-and-Presentation

## **Introduction to ReactJS**
- Library JavaScript yang biasa digunakan saat membangun UI suatu website atau aplikasi web
- Bersifat open source
- Diperkenalkan oleh facebook

## **Instalasi ReactJS**
- Menginstall node.js terlebih dahulu. Node.js adalah aplikasi yang memungkinkan javascript di luar dari web browser
- Membuat library 
```html
npx create-react-app <nama-folder>
```
![Screenshot (136)](https://user-images.githubusercontent.com/85721113/198840912-f3a24cdb-9661-4104-b5a1-c479fce2b8c1.png)
- Tunggu hingga keluar bacaan "happy hacking"
![Screenshot (137)](https://user-images.githubusercontent.com/85721113/198840940-27609e7a-9723-4375-a565-7578cc7fcf2c.png)

## **Penggunaan ReactJS**

![Screenshot (151)](https://user-images.githubusercontent.com/85721113/198841174-38429006-30dc-4d2d-ad83-588fae8cf128.png)

- Playground utama adalah file app.jsx dimana semua function akan diimport ke file tersebut
- JSX adalah extension syntax JavaScript yang digunakan untuk memodifikasi Document Object Model (DOM) dengan kode bergaya HTML
- Harus menggunakan tag kosong sebelum memasukkan component

```html
<>
</> 

atau 

<div>
</div>
```
![Screenshot (152)](https://user-images.githubusercontent.com/85721113/198842110-c2fab380-65d2-4b67-adda-642aed06ce13.png)

- Penulisan fungsi di awal huruf harus menggunakan huruf kapital
- Nama file = nama fungsi

## **Component pada ReactJS**
- Component dapat dibuat di luar main file (app.jsx)
- Caranya dengan membuat folder baru di dalam src yang berisi nama componen yang akan diguanan

![Screenshot (153)](https://user-images.githubusercontent.com/85721113/198842184-edb4182c-28e5-4a94-bbcc-44e3a36ba5ab.png)

![Screenshot (154)](https://user-images.githubusercontent.com/85721113/198842207-14be6194-e999-4850-9185-9c39bad742fc.png)

jangan lupa untuk mengeksport componenentnya

- Kemudian jika ingin menggunakan component, silakan panggil component tersebut di main file (app.jsx)
- Pemanggilan component harus menggunakan import 
- 
![Screenshot (155)](https://user-images.githubusercontent.com/85721113/198842356-c22b5828-52f8-45db-aaba-08b2c5bee707.png)

- Cara memanggil component yang diimport 

![Screenshot (156)](https://user-images.githubusercontent.com/85721113/198842442-8796efac-2f28-4eb6-88a3-7cdf62695cc3.png)

- Menampilkannya di web browser, menggunakan perintah nmp start di terminal
```html
npm start
```
![Screenshot (157)](https://user-images.githubusercontent.com/85721113/198842611-f432085f-4fc9-4f98-9f04-df60310d682f.png)

![Screenshot (158)](https://user-images.githubusercontent.com/85721113/198842705-5abce462-a031-4ae1-99d4-a95d4eb2cf80.png)


 



