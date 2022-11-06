# Writing-and-Presentation

## **Router**
- Digunakan untuk berpindah halaman
- Mirip tag anchor pada html yang akan membantu perpindahan halaman

### **Instalasi dan configure Router**
- Menginstalasi router menggunakan perintah :
```html
npm install react-router-dom@5.2.0
```
- Configurate router 
```html
import React from "react"
import ReactDOM from "react-dom/client"
import App from "./App"
import { BrowserRouter } from "react-router-dom"

const root = ReactDOM.createRoot(document.getElementById("root"))
root.render(
  <React.StrictMode>
    <BrowserRouter>
      <App />
    </BrowserRouter>
  </React.StrictMode>
)
```
### **Routing Dasar**
- Routes membungkungkus beberapa routes yang akan kita gunakan
```html
import { Route, Routes } from "react-router-dom"
import { Home } from "./Home"
import { BookList } from "./BookList"

export function App() {
  return (
    <Routes>
      <Route path="/" element={<Home />} />
      <Route path="/books" element={<BookList />} />
    </Routes>
  )
}
```
- React Router akan melihat rute yang ditentukan dalam komponen Routes dan mereder prop dari Route yang memiliki URL yang pas

### **Routing Dasar Navigation Handling**

- Pengganti dari tag anchor pada html 
- Menggunakan tag <link>
```html
<ul>
          <li><Link to="/">Home</Link></li>
          <li><Link to="/books">Books</Link></li>
        </ul>
```

### **Dynamic Routing**
- Digunakan untuk route pada data yang bersifat dinamis (sering berubah-ubah)
- Menggunakan parameter :id
```html
<Routes>
  <Route path="/" element={<Home />} />
  <Route path="/books" element={<BookList />} />
  <Route path="/books/:id" element={<Book />} />
</Routes>
```
- Pengaksesan dapat menggunakan key useParams
```html
import { useParams } from "react-router-dom"

export function Book() {
  const { id } = useParams()

  return (
    <h1>Book {id}</h1>
  )
}
```
### **Nested Routing**
- Digunakan bila terdapat banyak rute yang menggunakan parent route yang sama
- Langkah yang dapat dilakukan adalah membuat parent route digunakan untuk semua child route. Kemudian di dalam parent route letakkan semua komponen child route
``html
<Routes>
  <Route path="/" element={<Home />} />
  <Route path="/books">
    <Route index element={<BookList />} />
    <Route path=":id" element={<Book />} />
    <Route path="new" element={<NewBook />} />
  </Route>
  <Route path="*" element={<NotFound />} />
</Routes>
```
