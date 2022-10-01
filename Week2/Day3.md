# Writing-and-Presentation
## **Introducing DOM**
o DOM(Document Object Model)

o	Bukan merupakan bagian dari javascript

Dengan DOM, Javascript dapat melakukan :

o Javascript dapat merubah setiap elemen HTML pada halaman web.

o Javascript dapat merubah setiap atribut HTML pada halaman web.

o Javascript dapat merubah setiap style CSS pada halaman web.

o Javascript dapat menghilangkan elemen dan atribut HTML yang ada.

o Javascript dapat menambahkan elemen dan atribut HTML baru.

o Javascript dapat bereaksi pada setiap event yang ada pada halaman web.

o Javascript dapat membuat event baru pada halaman web.


## **Traversing Elements DOM ke bawah**
Dapat dilakukan dengan cara : 

### **Get Element by ID**
o Digunakan untuk menyeleksi elemen berdasarkan ID.
```html
document.getElementById('nama Id')
```
nb : element id harus unik dalam satu halaman web saja.

![image](https://user-images.githubusercontent.com/85721113/193370926-dd294669-0920-40c2-8f00-42ed0459102c.png)

Output :
![image](https://user-images.githubusercontent.com/85721113/193371087-6712df9b-69ee-4d16-9bd8-2ca4b25e35f1.png)

### **Get Element By Class Attribute**
o  digunakan untuk menyeleksi elemen dengan menggunakan Class pada suatu elemen.
```html
document.getElementsByClassName('namaKelas')
```

![image](https://user-images.githubusercontent.com/85721113/193376290-41655d5b-cfd4-4fa3-8d91-e8653133af4d.png)

Output :

![image](https://user-images.githubusercontent.com/85721113/193376303-60aafc58-2c0a-42b8-a711-b1c4dd55bb43.png)


### **Get Element By Tag**

```html
getElementsByTagName(“Tag”).
```

![image](https://user-images.githubusercontent.com/85721113/193376444-3afc38af-8d54-409a-8bc1-f6d6102fcec4.png)

### **Query Selector**
```html
document.QuerySelector("")
```
![image](https://user-images.githubusercontent.com/85721113/193378049-8cced75c-f97c-4ec6-8d2c-9c720de5eef9.png)

### **Query Selector All**
```html
document.QuerySelectorAll("")
```
![image](https://user-images.githubusercontent.com/85721113/193378163-0ed27c54-1594-49c6-8759-4403d496d828.png)

## **Traversing Elements DOM ke atas**
Dapat dilakukan dengan cara : 
### **ParentElement**
![image](https://user-images.githubusercontent.com/85721113/193378408-25ba3590-d047-4345-a183-54f0c9a967e3.png)
### **closest()**
![image](https://user-images.githubusercontent.com/85721113/193378468-63de04a4-339a-46cc-9555-bde9cc823d22.png)

### **Traversing Elements DOM ke samping**
### **nextElementSibling**
![image](https://user-images.githubusercontent.com/85721113/193378578-de1bc1af-c693-48a8-be57-4183d8d77dcb.png)

### **previousElementSibling**
![image](https://user-images.githubusercontent.com/85721113/193378581-8ef07f59-85e9-4bde-adfb-be51f5c73a62.png)



