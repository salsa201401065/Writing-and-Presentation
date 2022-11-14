# Writing-and-Presentation Week8
## **React Testing**
- Melakukan pengecekan apakah kode berhasil dijalankan sesuai dengan yang diharapkan
- Testing terbagi ke dalam 3 kategori, yaitu unit testing, integration testing, dan UI testing

### **React Testing Installations**
- Instalasi jest :
```html
npm i jest --save-dev
```
-Tambahkan kode pada package.JSON:
```html
"scripts": {
    "test": "jest"
  },
```

### **Making React Testing**
- Tambahkan kode berikut pada filterByTerm.spec.js :
```html
describe("Filter function", () => {
  // test stuff
});
```
- Menggunakan react context secara complete
```html
describe("Filter function", () => {
  test("it should filter by a search term (link)", () => {
    const input = [
      { id: 1, url: "https://www.url1.dev" },
      { id: 2, url: "https://www.url2.dev" },
      { id: 3, url: "https://www.link3.dev" }
    ];

    const output = [{ id: 3, url: "https://www.link3.dev" }];

    expect(filterByTerm(input, "link")).toEqual(output);

    expect(filterByTerm(input, "LINK")).toEqual(output);
  });
});

function filterByTerm(inputArr, searchTerm) {
  const regex = new RegExp(searchTerm, "i");
  return inputArr.filter(function(arrayElement) {
    return arrayElement.url.match(regex);
  });
}
```

### **Coverage in React Testing**
- Import filterbyterm
```html
const filterByTerm = require("../src/filterByTerm");
// ...
```
- run dan test di terminal
```html
npm test -- --coverage
```

Output :

![Screenshot (251)](https://user-images.githubusercontent.com/85721113/201680226-73412e86-c92d-4654-bcbd-1ba6103c719e.png)



