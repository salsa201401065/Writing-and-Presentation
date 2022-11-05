# Writing-and-Presentation

## **Proptypes**
- Memastikan tipe data yang dikirim dari parent ke child adalah tipe data yang sama
- Sebelum menggunakan prop-types, wajib instalasi terlebih dahulu. Ketikkan kode berikut di terminal
```html
npm install prop-types
```
- Mengimport prop-types yang sudah diinstall di file-file components yang digunakan
```html
import PropTypes from "prop-types";
```

### **Proptypes Memastikan tipe data harus sama persis dengan yang diminta**
- Diminta agar nama bertype data String dan Age bertype data number

![Screenshot (213)](https://user-images.githubusercontent.com/85721113/199537415-e4ce3243-f7c9-456b-8e44-2392b34604ca.png)

![Screenshot (215)](https://user-images.githubusercontent.com/85721113/199537731-8b020e6a-6509-4033-98f3-de472bb34de1.png)

![Screenshot (216)](https://user-images.githubusercontent.com/85721113/199538055-be7e18bb-a917-4a3c-861b-39fe5c760dc0.png)

- Namun, bila type data yang diinput tidak sesuai akan keluar error di console walau kode tetap berjalan. Misalkan age seharusnya number tapi yang dimasukkan type string.

![Screenshot (217)](https://user-images.githubusercontent.com/85721113/199538482-64eb0960-7570-4d38-ba13-8084a4d054d8.png)

![Screenshot (218)](https://user-images.githubusercontent.com/85721113/199538817-7702208f-b3ac-459c-ac8d-fc223f9ec931.png)

Namun age yang keluarkan menjadi "20" + 5

### **Proptypes Memastikan tipe data bersifat bebas dan harus ada**
- Menggunakan kata required

```html
StudentInfo.propTypes = {
    // type data number
  age: PropTypes.number,
  // type data bebas
  name: PropTypes.any.isRequired, 

};
```

### **Proptypes memberikan opsi pada type data**
- Menggunakan kata kunci oneOfType
- Misalkan age boleh ebrtipe string atau number

```html
    StudentInfo.propTypes = {
  name: PropTypes.any.isRequired, 
  age: PropTypes.oneOfType([PropTypes.string, PropTypes.number]),
};
```

![Screenshot (221)](https://user-images.githubusercontent.com/85721113/200120549-ed5681a2-74ea-49f8-a582-09002eea9e5b.png)

### **Proptypes untuk type data array**
- Menggunakan key  PropTypes.array
```html
    StudentInfo.propTypes = {
 
  name: PropTypes.any.isRequired, 
  age: PropTypes.oneOfType([PropTypes.string, PropTypes.number]),
  data: PropTypes.array,
};
```
![Screenshot (222)](https://user-images.githubusercontent.com/85721113/200121413-99e55043-4c45-48ac-93ca-071485afa5fe.png)

### **Proptypes untuk mengecek isi data array**
- Menggunakan key PropTypes.arrayOf
- Misalkan, Data array hanya boleh diisi dengan number
```html
 data: PropTypes.arrayOf(PropTypes.number),
```
saat ada data yang diisi bertipe string 

![Screenshot (223)](https://user-images.githubusercontent.com/85721113/200121698-c48777cc-7941-4acd-a631-54cc93ac010a.png)

![Screenshot (224)](https://user-images.githubusercontent.com/85721113/200121728-3a59b318-fa4f-4b5b-b316-3f74c44c9bc5.png)

### **Proptypes array yang dapat diisi dengan berbagai type data**
- Menggunakan key PropTypes.arrayOf(PropTypes.oneOfType([]))
```html
 data: PropTypes.arrayOf(PropTypes.oneOfType([PropTypes.number, PropTypes.string])),
```
- Data dapat diisi dengan type number atau string

![Screenshot (223)](https://user-images.githubusercontent.com/85721113/200122059-c899b60b-194f-4d5c-9995-eb788a962154.png)

![Screenshot (226)](https://user-images.githubusercontent.com/85721113/200122291-dc0db17c-e5df-4d42-aba6-b2086cebe6a7.png)

### **Proptypes type data object**
- Mengggunaka key PropTypes.object
```html
 StudentInfo.propTypes = {
 
  name: PropTypes.any.isRequired, 
  age: PropTypes.oneOfType([PropTypes.string, PropTypes.number]),
  data:PropTypes.arrayOf(PropTypes.oneOfType([PropTypes.number, PropTypes.string])),
  info: PropTypes.object,
};
```

![Screenshot (227)](https://user-images.githubusercontent.com/85721113/200122859-306487c0-ca61-4beb-bf6d-213d52a8955a.png)

### **Proptypes mengecek isi type data object**
- Menggunakan key PropTypes.shape
```html
StudentInfo.propTypes = {
 
  name: PropTypes.any.isRequired, 
  age: PropTypes.oneOfType([PropTypes.string, PropTypes.number]),
  data:PropTypes.arrayOf(PropTypes.oneOfType([PropTypes.number, PropTypes.string])),
  info: PropTypes.shape({
    hobby: PropTypes.string,
    class: PropTypes.number,
     }),

};
```
- Misalkan class diisi dengan data yang bertipe string

![Screenshot (228)](https://user-images.githubusercontent.com/85721113/200123052-a427fc31-4fbf-4143-a6fb-64edafa849b5.png)

![Screenshot (229)](https://user-images.githubusercontent.com/85721113/200123086-65342a89-3409-4a61-9900-453327650ea5.png)

### **Proptype smengecek nilai dan key dari object**
- Menggunakan key PropTypes.exact
```html
  StudentInfo.propTypes = {
 
  name: PropTypes.any.isRequired, 
  age: PropTypes.oneOfType([PropTypes.string, PropTypes.number]),
  data:PropTypes.arrayOf(PropTypes.oneOfType([PropTypes.number, PropTypes.string])),
  info: PropTypes.exact({
    hobby: PropTypes.string,
    class: PropTypes.number,
  }).isRequired,

};
```
















