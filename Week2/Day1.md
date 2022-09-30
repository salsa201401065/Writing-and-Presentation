# Writing-and-Presentation
## **Scope**
### **Global Scope**
o	Variabel yang diletakkan di luar dari {}

o	Variabel ini dapat diakses dimana saja

![image](https://user-images.githubusercontent.com/85721113/193292982-69dd153d-25dd-412f-8ad8-cf05b552ba2b.png)

Contoh Program :

```html
//Contoh Local dan Global scope
var juara = true;
let hadiah = "sirup";
if(juara) {  
    let hadiah = "Bakso";
    console.log(`yeay,hadiahku ${hadiah}.`)
  }

  console.log(`yah,hadiahku ${hadiah}.`);;

```

Output :

```html
yeay,hadiahku Bakso.  		//mengambil dari variabel yang berada di dalam scope
yah,hadiahku sirup. 		//mengambil dari variabel yang berada di luar scope	
```
Contoh perbedaan local dan global scope lainnya : 
```html
//Contoh Local dan Global scope
var juara = true;
let hadiah = "sirup";
if(juara) {  
    let hadiah = "Bakso";
    console.log(`yeay,hadiahku ${hadiah}.`)
  }
  console.log(`yah,hadiahku ${hadiah}.`);;
```
Output :
```html
yeay,hadiahku sirup.  		//mengambil dari variabel global  yang berada diluar scope scope
yah,hadiahku sirup. 		//mengambil dari variabel yang berada di luar scope	
```
### **Local Scope**
o	Mendeklarasikan variabel di dalam {}, seperti : conditional, function, dan looping

![image](https://user-images.githubusercontent.com/85721113/193293386-4822dda3-e9ac-47f9-bfd7-5c10e097c02e.png)

o	Variabel hanya dapat diakses didalam blocks saja

## **Function**
o	satu blok (kumpulan) perintah coding (statemens) yang mempunyai tujuan atau fungsi tertentu. Fungsi diproses atau dieksekusi apabila dipanggil oleh coding yang lain.

o	Cara mendeklarasikan fungsi 
```html
function namaFungsi(parameter1, parameter2, parameter3) {
  // code to be executed
}
```

![image](https://user-images.githubusercontent.com/85721113/193294629-87f44b91-f641-4878-9c4b-5a1ab67275c4.png)

o	Cara memanggil fungsi
```html
namaFungsi();
```
![image](https://user-images.githubusercontent.com/85721113/193294720-23fbb0fe-925b-408b-a89b-4e1804c12e63.png)

### **Parameter dan Argumen**
Parameter adalah variabel yang menyimpan nilai untuk diproses di dalam fungsi. 

Argument adalah nilai yang ditampung dari seluruh argumen yang dikirimkan kepada sebuah fungsi.

Contoh : 

![image](https://user-images.githubusercontent.com/85721113/193295241-dc7a136f-87ca-4b52-abbd-662efcad1e1d.png)

Ouput : 
```html
6
```
### **Arrow Function**

o	Cara ES6 atau cara yang digunakan untuk menuliskan suatu fungsi

o	Arrow Function memungkinkan kita untuk menulis sintaks fungsi dengan cara lebih pendek.
o	Cara membuat arrow function

![image](https://user-images.githubusercontent.com/85721113/193295521-3bc8deb2-d004-404b-84e6-5594ec09e3e2.png)

Contoh program arrow function 0 parameter :

![image](https://user-images.githubusercontent.com/85721113/193295594-8fcfb1cd-a556-4172-9b36-25f870197bf7.png)

Contoh program arrow function 2 parameter :

![image](https://user-images.githubusercontent.com/85721113/193295633-ded8bd01-8954-411e-ace2-e15475a6da82.png)

## **Mengatasi error serta bug**
Macam-macam error :

o	References Error : Menggunakan variabel yang belum di deklarasikan

o	Syntax Error : syntax yang tidak terbaca, biasanya karena typo

o	Range Error : memanipulasi range data dengan panjang yang tidak sesuai

o	Types Error : menggunakan tipe data yang undfined yang tidak sesuai dengan kebutuhan

Solusi dengan menggunakan try-catch 





