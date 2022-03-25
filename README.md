<h1 align="center">Praktikum 2 Pemrograman Web</h2>
<h3>Langkah Praktikum</h3>
<h4>1. Membuat dokumen HTML</h4>
<img width="556" alt="coding1" src="https://user-images.githubusercontent.com/76044697/160047791-e6517318-8315-4f3e-998b-c2c6ddca5666.PNG">
<p>Sintaks di atas merupakan struktur dasar dari HTML.<br/>
Apabila ditampilkan di browser akan menghasilkan tampilan :</p>
<img width="960" alt="hasil1" src="https://user-images.githubusercontent.com/76044697/160048369-b68c1189-ad6c-45ff-8481-11b562ab05f5.PNG">
<h4>2. Mendeklarasikan CSS internal</h4>
<img width="470" alt="coding2" src="https://user-images.githubusercontent.com/76044697/160049089-cd7e7e6a-cfd3-42d7-a3c1-603e3cdf1710.PNG">
<p>Sintaks CSS internal diletakan pada head dokumen html.<br/>
  Apabila ditampilkan akan menghasilkan :</p>
  <img width="960" alt="hasil2" src="https://user-images.githubusercontent.com/76044697/160049193-a41179df-57ed-4fe1-be0d-a3282de3eaee.PNG">
<h4>3. Menambahkan inline CSS</h4>
<img width="608" alt="coding3" src="https://user-images.githubusercontent.com/76044697/160049531-ca6f35c2-b1f9-43a5-8b85-84af9cfd93a0.PNG">
<p>Menambahkan inline CSS cukup dengan memberikan deklarasi dalam tag p seperti gambar di atas.<br/>
  Kemudian dari sintaks di atas akan menghasilkan tampilan : </p>
  <img width="960" alt="hasil3" src="https://user-images.githubusercontent.com/76044697/160049761-5fdeb2fd-a795-4ef5-98ec-74b7bab9533f.PNG">
<h4>4. Membuat CSS eksternal</h4>
Sebelumnya, Anda perlu membuat file baru dengan format css dengan sintaks sebagai berikut :
<img width="351" alt="coding4" src="https://user-images.githubusercontent.com/76044697/160049971-0e380df5-e9c1-4a15-b490-e19567953267.PNG">
Kemudian, untuk memanggil file css tadi, tambahkan tag link di dalam tag head pada file html seperti sintaks di bawah :
<img width="503" alt="coding4 1" src="https://user-images.githubusercontent.com/76044697/160050257-ee244c08-ecec-409b-9fd7-887b7dd49205.PNG">
<p>style_eksternal.css merupakan nama dari file css eksternal yang akan dipanggil<br/>
Apabila dibuka di browser akan memberikan tampilan :</p>
<img width="960" alt="hasil4" src="https://user-images.githubusercontent.com/76044697/160050312-f5f2f3ac-bbe6-46fb-aeff-382b62f0b23f.PNG">
<h4>5. Menambahkan CSS Selector</h4>
<img width="381" alt="coding5" src="https://user-images.githubusercontent.com/76044697/160050568-1835a7cc-ccd5-4bef-9bba-5f89adec1d8a.PNG">
<p>CSS selector ditambahkan pada file css eksternal<br/>
  Setelah disimpan maka halaman web akan menampilkan :</p>
  <img width="960" alt="hasil5" src="https://user-images.githubusercontent.com/76044697/160050713-28a76853-90de-46b6-b27a-d039df268544.PNG">
<h1>Jawaban Soal</h1>
<h3>1. Bereksperimen pada kode CSS </h3>
Saya bereksperimen menambahkan paragraf baru serta css untuk mengubah warna dari isi paragraph tersebut.
<img width="646" alt="coding eksperimen" src="https://user-images.githubusercontent.com/76044697/160119997-90829c82-5ede-4709-85c3-759d2aa65c69.PNG">
Halaman web akan menampilkan :
<img width="960" alt="hasil eksperimen" src="https://user-images.githubusercontent.com/76044697/160120084-fe1f86fb-f1dc-4130-bd97-b552d1b645fb.PNG">
<h3>2. Perbedaan elemen h1 {...} dengan #intro h1 {...}</h3>
<p>Pada sintaks CSS, h1{..} berfungsi untuk memberikan visual css kepada seluruh tag h1 di html, sedangkan #intro h1{..} berfungsi untuk memberikan visual css kepada seluruh tag h1 yang memiliki id dengan nama "intro".</p>
  <h3>3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?</h3>
<p>Apabila 3 deklarasi css diberikan pada elemen yang sama maka yang jadi prioritas untuk ditampilkan pada browser adalah deklarasi inline css. Berikut contohnya yang digaris bawahi merah: </p>
Eksternal
<img width="406" alt="eksternal" src="https://user-images.githubusercontent.com/76044697/160115144-9fbabac5-6440-469a-8f2c-c0ef5c11be26.PNG">
Internal
<img width="296" alt="internal" src="https://user-images.githubusercontent.com/76044697/160115483-e4961f90-c7b0-49ae-b918-32736f9deb3a.PNG">
Inline
<img width="647" alt="inline" src="https://user-images.githubusercontent.com/76044697/160115516-7a1dd2c4-8e19-4e8e-af87-981dc83b0540.PNG">
Halaman web akan menghasilkan warna text merah mengikuti sintaks pada inline css :
<img width="1012" alt="hasil inline" src="https://user-images.githubusercontent.com/76044697/160115831-a591e7b9-644a-46e8-a522-653f0aed2270.PNG">
<h3>Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?</h3>
Deklarasi yang akan ditampilkan antara id dan class adalah id, karena id merupakan entitas unik dan merupakan prioritas. Dapat dilihat pada contoh berikut yang dilingkari merah :
<img width="640" alt="coding id" src="https://user-images.githubusercontent.com/76044697/160117793-f026e37c-1687-4a46-b743-c9e59b11f4fa.PNG">
Halaman web akan menampilkan :
<img width="960" alt="hasil id" src="https://user-images.githubusercontent.com/76044697/160118056-aedfc8a6-fddd-465f-8752-0fa6fbb17537.PNG">
