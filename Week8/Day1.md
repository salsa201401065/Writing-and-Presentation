# Writing-and-Presentation Week8
## **Context**
- Mempermudah agar data dapat digunakan secara global tanpa harus menggunakan elemen perantara
- Dapat menggunakan perintah createContext()
```html
const ThemeContext = React.createContext('light');

class App extends React.Component {
  render() {
    return (
      <ThemeContext.Provider value="dark">
        <Toolbar />
      </ThemeContext.Provider>
    );
  }
}
function Toolbar() {
  return (
    <div>
      <ThemedButton />
    </div>
  );
}

class ThemedButton extends React.Component {
  static contextType = ThemeContext;
  render() {
    return <Button theme={this.context} />;
  }
}
```
## **Create Context pada API**
- React render komponen yang menerima objek Context ini akan membaca nilai context secara real time dengan mencocokannya ke provider
- defaultValue hanya digunakan ketika komponen tidak memiliki Provider yang cocok
```html
const MyContext = React.createContext(defaultValue);
```
### **Context Provider**
- Objek Context dilengkapi dengan komponen Provider React yang memungkinkan komponen lain untuk menerima perubahan context
- prop value untuk dioper ke komponen lain
- Kata kuncinya menggunakan Context.Provide
```html
<MyContext.Provider value={/* beberapa nilai */}>
```

### **Context Provider**
- Menerima perubahan context
- Menerima prop value untuk dioper
- Menggunakan kata kunci Context.Provider
```html
<MyContext.Provider value={/* beberapa nilai */}>
```


### **Context Type**
Diberikan objek Context yang dibuat oleh React.createContext()
```html
class MyClass extends React.Component {
  static contextType = MyContext;
  render() {
    let value = this.context;
    /* *render* sesuatu berdasarkan nilainya */
  }
}
```

### **Context Consumer**
- Komponen React yang menerima perubahan context
- Menerima context di dalam komponen fungsi
```html
<MyContext.Consumer>
  {value => /* render sesuatu berdasarkan nilai *context*-nya */}
</MyContext.Consumer>
```

### **Context Displayname**
- Objek Context menerima properti string displayName
- React DevTools menggunakan string ini untuk menentukan apa yang harus di tampilkan untuk context 
```html
const MyContext = React.createContext(/* beberapa nilai */);
MyContext.displayName = 'MyDisplayName';

<MyContext.Provider> // "MyDisplayName.Provider" in DevTools
<MyContext.Consumer> // "MyDisplayName.Consumer" in DevTools
```


### **Contoh Context Dinamis**
- Perubahan theme
```html
export const themes = {
  light: {
    foreground: '#000000',
    background: '#eeeeee',
  },
  dark: {
    foreground: '#ffffff',
    background: '#222222',
  },
};

export const ThemeContext = React.createContext(
  themes.dark // nilai *default*
);
```

### **Memperbarui Context Dari Komponen Bersarang**
- Mengoper sebuah fungsi melewati context untuk memperbarui context
- Mmperbarui theme-toggler-button
```html
import {ThemeContext} from './theme-context';

function ThemeTogglerButton() {
  // Theme Toggler Button tidak hanya menerima *theme*
  // tetapi juga fungsi toggleTheme dari *context*
  return (
    <ThemeContext.Consumer>
      {({theme, toggleTheme}) => (
        <button
          onClick={toggleTheme}
          style={{backgroundColor: theme.background}}>
          Toggle Theme
        </button>
      )}
    </ThemeContext.Consumer>
  );
}

export default ThemeTogglerButton;
```


