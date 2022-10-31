# Writing-and-Presentation

## **Konsep Form in ReactJS**
- Form atau formulir dimana user bisa menginput data yang disimpan pada server atau ditampilkan pada tampilan website sama halnya seperti pada html
- React JS menggunakan form agar user bisa berinteraksi dengan halaman web, seperti mengisi biodata, login, register, mencari data, dan lainnya
- Form terbagi menjadi2, yaitu controlled component dan uncontrolled component

### **Controlled Component**
- Elemen masukan form yang nilainya dikontrol oleh React 
- state yang dapat berubah seperti ini biasanya disimpan pada properti dari komponen, dan hanya akan diubah menggunakan setState()
- data form ditangani oleh komponen React

```html
class NameForm extends React.Component {
  constructor(props) {
    super(props);
    this.state = {value: ''};

    this.handleChange = this.handleChange.bind(this);
    this.handleSubmit = this.handleSubmit.bind(this);
  }

  handleChange(event) {
    this.setState({value: event.target.value});
  }

  handleSubmit(event) {
    alert('A name was submitted: ' + this.state.value);
    event.preventDefault();
  }

  render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <label>
          Name:
          <input type="text" value={this.state.value} onChange={this.handleChange} />
        </label>
        <input type="submit" value="Submit" />
      </form>
    );
  }
}
```


### **Uncontrolled Component**
- uncontrolled component menyimpan sumber kebenaran dalam DOM
- lebih mudah untuk mengintegrasikan kode React dan non-React
- data form akan ditangani oleh DOM-nya sendiri

```html
class NameForm extends React.Component {
  constructor(props) {
    super(props);
    this.handleSubmit = this.handleSubmit.bind(this);
    this.input = React.createRef();
  }

  handleSubmit(event) {
    alert('Sebuah nama telah dikirim: ' + this.input.current.value);
    event.preventDefault();
  }

  render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <label>
          Nama:
          <input type="text" ref={this.input} />
        </label>
        <input type="submit" value="Kirim" />
      </form>
    );
  }
}
```


