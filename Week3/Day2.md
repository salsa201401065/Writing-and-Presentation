# Writing-and-Presentation
## **Object**
- Objek : suatu variabel yang menyimpan nilai (properti) dan fungsi (method)
- Properti : data lengkap dari sebuah objek
- Method : apa saja yang bisa dilakukan dari suatu objek

```html
Object : 
human

Properti : 
name : 'Lisa'
age : '24'
height : '162'
weight : '55'

Method :
run()
jump()
eat()
dance()
study()
```

### **Membuat Object**
- Objek dideklarasikan di dalam variabel
```html
let human = {}; // manusia adalah objek kosong
```
- Objek juga bisa menampung properti data yang bertipe apapun seperti array

### **Pengaksesan properti dan method suatu object**

![image](https://user-images.githubusercontent.com/85721113/194734305-8f8491df-b698-47be-abae-6bc1d730ab7d.png)

![image](https://user-images.githubusercontent.com/85721113/194734308-b7fa79e8-5dbb-462e-85c3-7cead6ad5a20.png)

### **Pengaksesan properti suatu object menggunakan barcked notion {}**

![image](https://user-images.githubusercontent.com/85721113/194734431-a7b01328-4337-4373-9c97-1af006cb813f.png)

![image](https://user-images.githubusercontent.com/85721113/194734442-cdbe9480-7c24-4635-a251-a8922d48c13b.png)

### **Update Object**
- Pengupdate-an pada variabel dengan tipe data objek dapat dilakukan
- Object dapat mengupdate nilai dari properti yang telah tersedia
- Objek dapat menambah properti dan nilai baru

![image](https://user-images.githubusercontent.com/85721113/194735577-3a341089-2dc9-434c-a0a4-ca1262c58343.png)

![image](https://user-images.githubusercontent.com/85721113/194735586-4b6d8f12-efa3-417a-848d-17b0a5b3b000.png)

- Penggentian seluruh data object tidak dapat dilakukan jika menggunakan const, jika memang membutuhkan update dari seluruh data object maka gunakan let

![image](https://user-images.githubusercontent.com/85721113/194735820-22f5f686-d851-4be9-bdf9-d9b6fa68ac98.png)

![image](https://user-images.githubusercontent.com/85721113/194735816-ccfbaa0d-009b-4960-b090-8f05a52c5b2d.png)

![image](https://user-images.githubusercontent.com/85721113/194735852-dbb3c9b7-8539-4215-9584-3645aabd4588.png)

![image](https://user-images.githubusercontent.com/85721113/194735904-054b343f-2409-4d15-9142-8c930f2b7010.png)

### **Delete Object Properti**
- Dapat menggunakan operator delete

![image](https://user-images.githubusercontent.com/85721113/194735941-7703671b-c6b8-4b43-b750-fe454cf7f1c8.png)

![image](https://user-images.githubusercontent.com/85721113/194735946-7dbf4ebb-6cae-4e7f-aa7d-d30c387727dc.png)

### **Method**
- Memasukkan value pada property berupa function
- Console : global javascript objek
- log() : property yang berupa function dari object console
- Method dapat di custom

![image](https://user-images.githubusercontent.com/85721113/194738708-f75fd32e-3e27-4326-9058-4aac8ca5cfab.png)

### **Nested Object**
- Kasus dimana suatu objek berasal dari turunan objek lainnya

![image](https://user-images.githubusercontent.com/85721113/194739003-d9e45a84-2805-4e75-85c4-db4838ff761b.png)

### **Pass by Reference**
- Mengubah data yang ada pada objek melalui sebuah function dan memasukkan objek sebagai parameter function

![image](https://user-images.githubusercontent.com/85721113/194739187-a2264a6e-b0c0-432b-809f-c2e10c42b334.png)

### **Looping Object**
- Jika ingin menmapilkan seluruh object properti yang jumlahnya banyak

```html
for(let key in object){
 // ...
}
```

![image](https://user-images.githubusercontent.com/85721113/194739324-923932df-7109-404f-9224-3cfdf0259c80.png)


### **Array of Object**
- Untuk menyimpan banyak data dari onjek yang jumlahnya banyak

![image](https://user-images.githubusercontent.com/85721113/194739467-893a6a25-5278-4f91-bf1a-364e97462101.png)


















