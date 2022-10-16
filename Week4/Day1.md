# Writing-and-Presentation

![Screenshot (60)](https://user-images.githubusercontent.com/85721113/196063527-742715ba-72be-47cd-94f7-89a295e702d7.png)

- API merupakan perantara yang menjembatani antara backend dan frontend
- Frontend terfokus pada sisi client
- Backend terfokus pada server dan database
- Backend menjadi penyedia data untuk frontend
- Frontend merupakan media untuk mempresentasikan data-data tsb

## **Promise()**
- Digunakan untuk melihat apakah suatu kondisi terjadi atau gagal terjadi
- Promise hanya dapat berjalan di asynchronous
- Memmbuat code lebuh mudah dibaca
- Promise memiliki error handling. Jadi, ketika ada kesalahan maka dapat ditindak lanjuti

![Screenshot (95)](https://user-images.githubusercontent.com/85721113/196064102-851ac32b-d95b-41ff-9ff6-2b9613dfee69.png)

![Screenshot (96)](https://user-images.githubusercontent.com/85721113/196064137-da92f03c-c689-4cd1-8a24-09d471241840.png)

## **Async Await**
-  Fitur yang mempermudah dalam menangani proses asynchronous
-  Async/Await merupakan sebuah syntax khusus yang digunakan untuk menangani Promise agar penulisan code lebih efisien dan rapih

```html
const getAllUser = async ()=> {
	const data = await getUser()
	console.log(data)
}
```
### **Error handling Async Await**
- Dengan cara menggunakan try catch di dalam function

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




