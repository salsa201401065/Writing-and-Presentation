# Writing-and-Presentation

## **Asycn action Middleware and Thunk**
- Redux Thunk adalah konsep dimana memungkinkan pengiriman action secara asycn melalui suatu fungsi objek 
- Memanfaatkan penyimpanan Redux dan mengandalkan API eksternal
- Fungsi menerima pengiriman yang kemudian digunakan untuk mengirim asycn objek di dalam isi fungsi setelah operasi async selesai

## **Create Middleware**
- Immport key applyMiddleware function dari Redux 
```html
import { applyMiddleware } from "redux";
```
- Defenisikan middleware menggunakan function
```html
const loggerMiddleware = (store) => (next) => (action) => {
  // your code
};
```
- Create suatu store
```html
const store = createStore(reducer, middleware);
```
- Middleware menggunakan fungsi bersarang (nested)
```html
const loggerMiddleware = (store) => (next) => (action) => {
  console.log("action", action);
  next(action);
};
```

Output

![Screenshot (238)](https://user-images.githubusercontent.com/85721113/200238310-77e5b3ea-97ce-4719-aba6-c1a26628373f.png)


