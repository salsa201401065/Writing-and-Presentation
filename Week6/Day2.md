# Writing-and-Presentation

## **Component in ReactJS**
- Penulisan function harus menggunakan huruf besar di awal 
- Jangan lupa ada nilai return
- Di react harus punya pembungkus utama (parent)
- Component pada reactJS berguna untuk membuat penulisan code lebih efektif. Code cukup ditulis sekali namun bisa dipanggil berulang kali

```html
<>
</>
atau 
<div></div>
```
- Buat folder bernama components di dalam folder src untuk menampung file jsx yang berisi components
- Nama function harus sama dengan nama file

![Screenshot (162)](https://user-images.githubusercontent.com/85721113/198881874-a3149545-458e-434a-8e7c-1a2eb2507483.png)

- Penggunaan CSS masih sama seperti sebelum-sebelumnya. Bedanya penulisan class nya menggunakan ?className
- Patikan semua function dipanggil ek app.jsx yang menjadi main file (pintu masuk) yang nantinya codingan bisa ditampilkan di web browser
- Penggunaanya menggunakan export import

![Screenshot (163)](https://user-images.githubusercontent.com/85721113/198882333-cadd34cc-f3df-4f09-99c7-37bcaf624423.png)

Pemanggilan function di app.jsx

![Screenshot (164)](https://user-images.githubusercontent.com/85721113/198882366-58ed0619-71a5-4efb-a2a6-64324b174871.png)

![image](https://user-images.githubusercontent.com/85721113/198882374-ea46e7a6-aee6-48af-b4ac-5f92599e618c.png)

## **Props and State**
- Konten dari member info bersifat statis sebelum menggunakan props and state. agar bersifat dinamis maka digunakanlah props and state.
- State : suatu objek untuk menyimpan data
- Props : pengiriman data pada child dan parent
- Props dapat dikatakan sebagai parameter dari function

![Screenshot (166)](https://user-images.githubusercontent.com/85721113/198883052-2f6ecfea-7f3f-4f16-ae12-64eb7b9c5c10.png)

- Memproses JS dapat dilakukan di dalam HTML pada ReactJS menggunakan {}
- Penggunaan Inline CSS menggunakan camel case

![Screenshot (167)](https://user-images.githubusercontent.com/85721113/198884238-51919d85-9139-4418-a8a8-008f80bafbf0.png)

![Screenshot (169)](https://user-images.githubusercontent.com/85721113/198884258-6d453993-9349-476f-a70a-cb81bbf3bbfe.png)
 
 - Styling CSS inline juga dapat menggunakan props dan state

![Screenshot (170)](https://user-images.githubusercontent.com/85721113/198884690-be619c74-3d00-4bf9-9703-e5a0f110a02a.png)

![Screenshot (171)](https://user-images.githubusercontent.com/85721113/198884695-fb994e88-f34b-4875-a9b1-9982a9a551b5.png)

![image](https://user-images.githubusercontent.com/85721113/198884698-10900576-f567-4834-8ae6-c5d840964588.png)

- Sebab react bersifat imutable, maka jika ingin merubah konten dapat menggunakan konsep use state

![Screenshot (174)](https://user-images.githubusercontent.com/85721113/198886392-4dcec869-b24a-47ca-8bd7-32046cdb86af.png)

![image](https://user-images.githubusercontent.com/85721113/198886401-1c3bc222-fa88-44ae-9ded-f009be9c5c0c.png)

## **Stateless dan Statefull**
- Stateless : tidak memiliki state dan hanya memiliki props, yang bertindak sebagai stateless adalah member info.
- Statefull : memiliki state dan dapat mengirimnya ke component. Yang bertindak sebagai statefull adalah app.jsx

## **Penggunaan Bootstrap pada ReactJS**
- Memasukkan link cdn di bagian index.html

![Screenshot (176)](https://user-images.githubusercontent.com/85721113/198888353-ec9478ff-5d93-48bc-b08b-0a345c5780ba.png)

- Memasukkan code  bootstrap di folder compoenent sesuai kebutuhan
- Mengganti semua class menjadi className

![Screenshot (177)](https://user-images.githubusercontent.com/85721113/198888430-ea17e7e0-36c5-42b9-8da7-36c39a279479.png)

![image](https://user-images.githubusercontent.com/85721113/198888432-66f5a284-0491-479a-b7e4-51913a300531.png)














