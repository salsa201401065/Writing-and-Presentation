# Writing-and-Presentation

## **Responsive Web**
- Mmebuat website yang responsif
- Tampilan tidak berantakan dibuka di device manapun
- Website akan disesuaikan dengan ukuran device

### **Add Viewport**
- Ditambahkan di dalam tag <head>
  
![image](https://user-images.githubusercontent.com/85721113/196214093-1c45a7c7-54ec-4edd-aac5-1ea1e2e17294.png)
  
### **Max-width**
- Biasa digunakan untuk image
- Agar image mengikuti ukuran device dan tidak berantakan
  
 ![image](https://user-images.githubusercontent.com/85721113/196215253-d3ed013b-64ac-4a6d-afe5-49afe6241a7e.png)
 
  ### **Media Query**
  - Umumnya terbagi menjadi 2, yaitu min width dan max width
  - Terdapat 2 cara untuk menggunakannya, yang pertama membaut file css tersendiri untuk masing-masing device, cara kedua dengan cara menggabungkannya dalam satu styling css untuk berbagai device
  
  ![image](https://user-images.githubusercontent.com/85721113/196217605-c900caaf-fd7f-4719-b1c7-19221dbbd400.png)
  
  Hasilnya :
  
  ![image](https://user-images.githubusercontent.com/85721113/196217762-4b43fa19-aef1-407c-b345-88ca8ae66ca6.png)
  
  ![image](https://user-images.githubusercontent.com/85721113/196217958-84fbbed7-ac05-4553-baed-2b5ab1da69af.png)

## **Bootstrap**
- Suatu framework yang mempermudah developer dalam pembuatan website
- Terdapat 2 cara menggunakan bootstrap, yang satu dengan cara menginstall komponennya atau menggunakan link url bootstrp secara online
- Link diletakkan di dalam tag <head>
  
```html
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
```
  
 - Untuk mengatur pewarnaan dan sebagainya, bootstrap mempunyai aturan tersendiri dengan tambahan code di bagian class nya
  
```html
<p class="text-primary">.text-primary</p>
<p class="text-secondary">.text-secondary</p>
<p class="text-success">.text-success</p>
<p class="text-danger">.text-danger</p>
<p class="text-warning bg-dark">.text-warning</p>
<p class="text-info bg-dark">.text-info</p>
<p class="text-light bg-dark">.text-light</p>
<p class="text-dark">.text-dark</p>
<p class="text-body">.text-body</p>
<p class="text-muted">.text-muted</p>
<p class="text-white bg-dark">.text-white</p>
<p class="text-black-50">.text-black-50</p>
<p class="text-white-50 bg-dark">.text-white-50</p>
```
  
- Untuk mengatur grid juga terdapat code yang harus ditambahkan pada class 
```html
  <div class="d-grid gap-3">
  <div class="p-2 bg-light border">Grid item 1</div>
  <div class="p-2 bg-light border">Grid item 2</div>
  <div class="p-2 bg-light border">Grid item 3</div>
</div
```
    
    Untuk keterangan lebih lanjut dapat di cek di web bootstap : https://getbootstrap.com/docs/5.2/getting-started/introduction/
