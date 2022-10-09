# Writing-and-Presentation
## ** JS MODULES**
- Cara untuk memisahkan code ke beberapa file yang berbeda untuk memmudahkan maintain terhadap code dimana file-file tsb saling terhubung
- Keuntungan : mudah untuk mengelola code, code tidak menumpuk di suatu file
- Export dapat dilakukan pada variabel, function, dan class
- Syarat awal untuk menggunakan js modules adalah saat menyambukan file html dengan file js, wajib menambakan property type="module"

![image](https://user-images.githubusercontent.com/85721113/194764457-990e0746-b9fa-4206-99c3-2bde80368450.png)

-  2 komponen utama dalam js modules adalah export(keluar) dan import(kedalam)

![image](https://user-images.githubusercontent.com/85721113/194764576-a53b4fb9-86ba-48f5-8a39-a7ebaa36beb6.png)

![image](https://user-images.githubusercontent.com/85721113/194764586-2ef100c9-bf34-41a9-9891-22024abfe029.png)

![image](https://user-images.githubusercontent.com/85721113/194764597-7acce11b-69e6-48b7-b5c3-4f6465d9c0a5.png)


## **RECURSIVE**
- Function yang memanggil diri sendiri
- Kebanyakan digunakan untuk case yang berhubungan dengan matematika dan calculate
- Struktur rekursif
```html
function recursive() {
recursive();
}
```
- Rekursif akan berhenti memanggil dirinya sendiri jika kondisi sudah terpenuhi
```html
function recursive(){
  if(condition){
  
  } else{
  
  }
}
```
- Ciri dari rekursif : selalu memiliki kondisi dimana akan stop, selalu memanggil diri sendiri sambil memecahkan data masukan setiap panggilannya

Contoh rekursif case

![image](https://user-images.githubusercontent.com/85721113/194765161-4f79f61a-1a45-4a25-b08f-2c23180e7e74.png)

![image](https://user-images.githubusercontent.com/85721113/194765275-b55c35aa-364a-4f69-8429-9e9425bf260e.png)


