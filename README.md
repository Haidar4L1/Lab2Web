1. membuat dokumen
    - Tag <!DOCTYPE html>,
Setiap dokumen HTML harus dimulai dengan deklarasi DOCTYPE.

    - Tag <html lang="en">,
Tag pembuka <html> menandakan awal dari dokumen HTML.
Atribut lang="en" menunjukkan bahwa bahasa yang digunakan dalam halaman ini adalah bahasa Inggris.

    - Tag <head>,
head addalah bagian yang berisi informasi meta tentang dokumen,  seperti pengaturan karakter (charset), dan judul halaman (<title>).

    - Meta Charset (<meta charset="UTF-8">)
Menetapkan pengkodean karakter dokumen menjadi UTF-8, yang memungkinkan hampir semua karakter digunakan, termasuk huruf, simbol, dan karakter dari berbagai bahasa.

    - Meta Viewport <meta name="viewport" content="width=device-width, initial-scale=1.0">
    Atribut ini mengatur agar tampilan web sesuai dengan lebar layar perangkat pengguna, penting untuk desain responsif.
    
    - Tag <title>
    Memberikan judul halaman yang akan tampil pada tab browser.
    
    - Tag <body>
    Bagian yang memuat seluruh konten visual yang akan tampil di halaman web.
    
    - Tag <header>
    Bagian ini biasanya digunakan untuk menampilkan judul atau informasi pembuka.
    
    - Tag <nav>
    Bagian ini digunakan untuk membuat navigasi. 
    
    - Div Tag dengan ID intro (<div id="intro">)
    Tag <div> ini menggunakan atribut id dengan nilai "intro." ID digunakan dalam CSS untuk mengidentifikasi elemen ini secara unik.
    
        Di dalam <div> ini terdapat <h1> berisi teks "Hello World" dan sebuah paragraf <p> yang menjelaskan bahwa halaman ini adalah untuk belajar HTML dan CSS dasar.
    
    - Paragraph <p>
    untuk membuat seatu teks pada halaman web, Terdapat juga tag <b> untuk menebalkan teks dan <i> untuk membuat teks miring
    di bawah merupakan kodingnya
![ss1 kodenya](https://github.com/user-attachments/assets/dc925651-dffa-46b1-bd96-8a6c8b7da66d)
maka hasilnya
![ss1](https://github.com/user-attachments/assets/e514d162-45b7-4bdd-a294-83c4e6581b51)

2. Mendeklarasikan CSS Internal
    -Tag <head>:

Tag <head> adalah bagian dari dokumen HTML yang berisi informasi metadata, yang tidak ditampilkan langsung di halaman web.

    - Tag <style>:

Tag <style> digunakan untuk menambahkan CSS (Cascading Style Sheets) langsung di dalam dokumen HTML.

    - Tag <body>:

Tag <body> adalah bagian dari dokumen HTML yang berisi semua konten visual yang akan ditampilkan kepada pengguna. Tag <body> berfungsi untuk menampilkan konten nyata.

    - Tag <header>:
Tag <header> digunakan untuk membuat bagian pengantar di sebuah halaman atau bagian dari halaman, seperti judul, logo, atau navigasi. Biasanya, elemen ini berada di bagian atas halaman.

    - Tag <h1>:

Tag <h1> adalah elemen heading yang paling besar dan paling penting dalam sebuah halaman HTML. 
di bawah merupakan kodinganya
![ss2  kodenya](https://github.com/user-attachments/assets/9021d2c5-caf4-4d07-a580-573f7fab4634)
maka hasilnya
![ss2](https://github.com/user-attachments/assets/aedbc3b0-1984-4aad-acf2-362affb7fa57)

3. Menambahkan Inline CSS
pada tag <p di dalamnya terdapat atribut style 
dan text-align: center;:
Atribut ini digunakan untuk mengatur perataan teks dalam elemen paragraf. Nilai center berarti teks akan diratakan di tengah secara horizontal di dalam elemen <p>.

atribut color untuk warna dan untuk kode #ccd8e4; yaitu biru muda
kodingnya
![ss3 kodenya](https://github.com/user-attachments/assets/477c935e-79b7-45b9-8397-7c6b418dcbe9)
hasilnya
![ss3](https://github.com/user-attachments/assets/3c74b06b-74f3-4863-aa88-e19d795fab7b)

4. Membuat CSS Eksternal
   - pada  nav awalan
terdapat atribut 
background: #20A759;: 
Mengatur warna latar belakang elemen <nav> menjadi hijau dengan kode warna heksadesimal #20A759.

    color: #fff;
    : Mengatur warna teks di dalam elemen <nav> menjadi putih. Nilai #fff adalah kode heksadesimal untuk warna putih.

    padding: 10px;: 
    Memberikan jarak (padding) sebesar 10 piksel di dalam elemen <nav>, sehingga konten (seperti teks dan tautan) tidak terlalu dekat dengan batas elemen.
    
    - pada nav kedua, nav a {}: 
    Bagian ini mengatur gaya untuk semua tautan (<a>) yang berada di dalam elemen <nav>.
    terdapat atribut
    color: #fff;
    : Mengubah warna teks pada tautan di dalam elemen <nav> menjadi putih.
    
        text-decoration: none;
        : Menghapus garis bawah (underline) pada tautan, sehingga teks terlihat lebih bersih.

        padding: 10px 20px;
        : Memberikan jarak (padding) di dalam tautan, dengan 10 piksel di bagian atas dan bawah, serta 20 piksel di bagian kiri dan kanan. Ini membuat tautan lebih mudah diklik dan memberikan ruang yang lebih besar di sekitar teks tautan.

kodinganya
![ss4 kode csssnya](https://github.com/user-attachments/assets/9911e70d-688b-4e1e-bdf6-862da2da98e4)

- link
<link rel="stylesheet" href="style_eksternal.css" type="text/css"> 
berfungsi untuk menghubungkan halaman HTML dengan file CSS eksternal.
kodngnya

![ss4 kode link ke cssnya](https://github.com/user-attachments/assets/ac8d01bc-5975-48a8-98ad-fb090602fabe)
hasilnya
![ss4](https://github.com/user-attachments/assets/94521daf-0315-4a00-a6ca-7c1b765e6713)

5. Menambahkan CSS Selector

ID Selector (#intro) 
digunakan untuk mengatur elemen yang memiliki ID intro, mengatur warna latar belakang, border, tinggi minimum, dan padding.

Class Selector (.button) 
digunakan untuk mengatur elemen-elemen dengan class button, memberikan padding, warna latar belakang, warna teks, margin, dan mengatur tampilan inline-block.

Class Selector (.btn-primary) 
adalah modifikasi dari .button yang mengubah latar belakang elemen menjadi merah untuk elemen yang memiliki class btn-primary.

kodingnyanya
![ss5 kodenya](https://github.com/user-attachments/assets/9f428e5c-02f1-4753-b979-318234f80b18)
hasilnya
![ss5](https://github.com/user-attachments/assets/fdbe907a-377d-4653-b9f6-54c58667baa5)


6. perubahan
kodingnya
![ss6 kodenya](https://github.com/user-attachments/assets/fcedd27f-4ee1-489e-8938-ad640ef83f75)
hasilnya
![ss6 perubahanya](https://github.com/user-attachments/assets/d4a7a124-e075-40e9-be48-db42d64c94e6)

