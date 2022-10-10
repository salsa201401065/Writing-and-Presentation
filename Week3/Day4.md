# Writing-and-Presentation
## **Asyncronous**
- Asyncronous : keadaan dimana suatu code bisa dieksesusi tidak secara berurutan dan tanpa menunggu code lain/diatas nya dieksekusi terlebih daulu, sehingga user tetap bisa berpindah ke halaman lain pada saat ada halaman yang ditunggu
- Syncronous : keadaan dimana suatu code di eksekusi secara berurutan dan tidak dapat saling menyela
- Single thread blocking : harus menunggu setiap antrian selesai.
- Single thread non-blocking : mengizinkan adanya pemotongan antrian.
- Multi thread : banyak antrian.
### **Callback**
- Function yang dijadikan argumen
- Dapat digunakan pada asyncronous maupun syncronous

![image](https://user-images.githubusercontent.com/85721113/194793968-5b80060f-e855-4c4e-9f85-ae4dc4acdf52.png)

### **Promises**
- Digunakan untuk melihat apakah suatu kondisi terjadi atau gagal terjadi
- Promise hanya dapat berjalan di asynchronous
- Mmebuat code lebuh mudah dibaca
- Promise memiliki error handling. Jadi, ketika ada kesalahan maka dapat ditindak lanjuti

![image](https://user-images.githubusercontent.com/85721113/194793799-e0e8b4ed-e7dc-4322-8971-a983c4b56201.png)

- Promise dengan argumen 

![image](https://user-images.githubusercontent.com/85721113/194796381-26483cb3-755a-409b-8220-77d60998540e.png)


### **Await**
- Hadir sejak fitur ES2017
- Mempermudah  dalam menangani proses asynchronous
- Dapat dikatakan sebagai syntax yang menangani promise agar penulisan code lebih efisien 
- Setiap baris yang menggunakan await, akan ditunggu sampai Asynchronous Promise tersebut di resolve
- Pengimplementasian Async/Await dengan menggunakan kata kunci async sebelum fungsi

```html
const getAllUser = async ()=> {
	const data = await getUser()
	console.log(data)
}
```
-Error handling async/await dapat menggunakan try and catch
```html
const getAllUser = async ()=> {
	try {
		const result = await getUser()
		console.log(result)
	} catch (error) {
		console.log(error)
	}
}
```

### **Fetch**
- Fetch adalah sebuah teknik untuk melakukan request dan response jaringan. 
- Merupakan fitur yang ada sejak ES6
- Fetch mengembalikan sebuah Promise sehingga request fetch akan selalu berjalan async
- Cara penggunaan fetch()
```html
fetch('http://example.com/movies.json')
  .then(response => response.json())
  .then(data => console.log(data));
```
- Pengaksesan fetch() untuk mendapatkan data
```html
var base_url = "http://api.football-data.org/v2/";
fetch(base_url + "competitions/2021/standings",{
   headers: {
        'X-Auth-Token': '***************'
      }
    })
    .then(response => {
      return response.json();
    })
    .then(function(data) {
       console.log(data)
     }.catch(error => {
        console.log(error);
 });
```






