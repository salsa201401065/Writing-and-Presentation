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
## **Mengatasi error serta bug**


