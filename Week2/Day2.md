# Writing-and-Presentation
## **Data-Type Built in - Prototype and Method**

o	Method : suatu keahlian yang dapat dilakukan oleh suatu tipe data

o	Properti : ciri dari suatu string

Contoh properti adalah, String length  yang digunakan untuk mengetahui panjang karakter dari suatu string.
```html
let hewan = "kancil";
console.log(hewan.length)
```

Output :
```html
6 						//Panjang karaker dari string kancil
```

### **Data type**
o	Primitive
-	String : karaker kosong atau beberapa karakter yang ditulis di dalam tanda petik.
```html
let carName1 = "Volvo XC60";  // Double quotes
let carName2 = 'Volvo XC60';  // Single quotes
```
-	Number : berupa angka bilangan bulat maupun desimal
```html
let x1 = 34.00;     // Written with decimals
let x2 = 34;        // Written without decimals
```

-	Boolean : hanya memiliki nilai true atau false
```html
let x = 5;
let y = 5;
let z = 6;
(x == y)       // Returns true
(x == z)       // Returns false
```
o	Non-primitive
-	Array : ditulis dalam tanda [], array juga dapat menampung data dengan beragam tipe data.
```html
const cars = ["Saab", "Volvo", "BMW"];
```
array dimulai dari index ke-0, dengan begitu Saaab berarti index ke-0, Volvo inedex ke-2, dan BMW index ke-3.

-	Object : objek di tulis di dalam tanda {}
```html
const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```
o	Typeof : untuk mengecek tipe data dari variabel yang kita deklarasikan
```html
typeof "John Doe"     // Returns "string"
typeof 314            // Returns "number"
```
o	Undifined : variabel yang tidak memiliki nilai
```html
let car;    // Value is undefined, type is undefined
car = undefined;    // Value is undefined, type is undefined
```
o	Empty Values : tidak ada yang dapat dilakukan karena undifined tetapi rtipe datanya dikenali
```html
let car = "";    // The value is "", the typeof is "string
```
### **Method**

String
o	UpperCase : mengubah kata atau kalimat ke dalam huruf kapital
```html
const kalimat = 'V BTS Suamiku';
console.log(kalimat.toUpperCase());  // Output : V BTS SUAMIKU
```
o	LowerCase : mengubah kata atau kalimat ke dalam huruf kecil
```html
const kalimat = 'V BTS Suamiku';
console.log(kalimat.toLowerCase());  // Output : v bts suamiku
```

o	CharAt(n) : mengembalikan karakter berdasarkan nilai index

![image](https://user-images.githubusercontent.com/85721113/193323777-ddda3f47-2b51-4e37-ab75-8084b3b2f47c.png)

o	Includes() : melakukan pencarian string

 ![image](https://user-images.githubusercontent.com/85721113/193323876-19f8d609-8e34-4b41-a01d-90f5bed82dd7.png)

o	Split() : memisahkan string menjadi data array

![image](https://user-images.githubusercontent.com/85721113/193323902-d5876208-03d3-4fed-a262-ae8c43a46afd.png)

Ket : 

[0] : halo
[1] : aku
[2] : jennie
[3] : blekping

Number

o	ToString() : merubah angka menajadi string
```html
let angka = 30;
console.log(angka.toString()); // output: “30”
```
o	Isnan(): memberitahu yang bukan angka
```html
Console.log(isNaN(“ini bukan angka”)); // output : true
```

Math

o	Math Const
```html
Math.E        // returns Euler's number
Math.PI       // returns PI
Math.SQRT2    // returns the square root of 2
Math.SQRT1_2  // returns the square root of 1/2
Math.LN2      // returns the natural logarithm of 2
Math.LN10     // returns the natural logarithm of 10
Math.LOG2E    // returns base 2 logarithm of E
Math.LOG10E   // returns base 10 logarithm of E
		```
o	Math Methods

 ![image](https://user-images.githubusercontent.com/85721113/193324244-ec33b3ab-dca9-4cde-b3d5-b0ea6edb9f10.png)



o	Math.round() : mengembalikan nilai integer
```html
Math.round(4.4); // outout : 4
```

o	Date
getFullYear()


