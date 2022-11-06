# Writing-and-Presentation

## **State Management React-Redux**
- Redux adalah library javascript yang membantu dalam mengelola state yang digunakan
- State management adalah konsep yang membantu agar parent state bisa langsung diberikan kepada child state tanpa harus melakukan props drilling (mengoper state ke component lain terlebih dahulu untuk sampai pada state child)

![Screenshot (211)](https://user-images.githubusercontent.com/85721113/200200741-07bac25d-94fb-42c9-b1f5-1e475504c281.png)

### **Instalasi React-Redux**
- Untuk penggunaan redux, instalasi terlebih dahulu react-redux menggunakan perintah
```html
npm install react-redux
```
- Gunakan tag <provider> pada main.jsx agar redux dapat digunakan dan gunakanalah import
```html
import ReactDOM from 'react-dom/client'
import { Provider } from 'react-redux'
  import { Provider } from 'react-redux'
import store from './store'

import App from './App'


const root = ReactDOM.createRoot(document.getElementById('root'))
root.render(
  <Provider store={store}>
    <App />
  </Provider>
)
```
  
### **Store di React-Redux**
- Store adalah tempat untuk menyimpan state yang ada pada aplikasi
- Mengupdate state
- Menyediakan izin untuk pengaksesan state
- Menotice atau memberitahukan komponen lain jika terjadi perubahan pada state
  
### **Action di React-Redux**
- Bentuk fungsi sederhana yang mereturn objek seperti halnya yang biasa digunakan pada javascript yang berguna untuk mengirim informasi kepada store
```html
const increment = () => {
    return {
        type: 'INCREMENT'
    }
}
```

  
  
  
 

