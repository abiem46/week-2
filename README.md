#
A. Pengenalan Javascript
1. Pengertian Javascript 
    Javascript adalah bahasa yang berbentuk kumpulan skrip yang pada fungsinya
berjalan pada suatu dokumen HTML, sepanjang sejarah internet bahasa ini adalah
bahasa skrip pertama untuk web. Bahasa ini adalah bahasa pemrograman untuk
memberikan kemampuan tambahan terhadap bahasa HTML dengan mengijinkan
pengeksekusian perintah perintah di sisi user, yang artinya di sisi browser bukan di
sisi server web. Javascript bergantung kepada browser(navigator) yang memanggil halaman web yang berisi skrip skrip dari Javascript dan tentu saja terselip di dalam dokumen HTML. Javascript juga tidak memerlukan kompilator atau penterjemah khusus untuk menjalankannya (pada kenyataannya kompilator Javascript sendiri sudah termasuk di dalam browser tersebut). Lain halnya dengan bahasa “Java” (dengan mana JavaScript selalu di banding bandingkan) yang memerlukan kompilator khusus untuk menterjemahkannya di sisi user/klien. 

1.2.  Keperluan Java Script

Untuk mempelajari pemrograman JavaScript, ada dua piranti yang diperlukan, yaitu :

• Teks Editor
 
 Digunakan untuk menuliskan kode-kode Java Script, teks editor yang dapat
digunakan antara lain notepad dan ultra edit.

• Web Browser

Digunakan untuk menampilkan halaman web yang mengandung kode-kode
Java Script. Web browser yang digunakan harus mendukung Java Srcipt.
Browser yang dapat digunakan adalah internet explorer dan Netscape
Navigator. 

1.3. Penulisan Java Script

Kode Java Script dituliskan pada file HTML.Terdapat dua cara untuk menuliskan
kode-kode Java Script agar dapat ditampilkan pada halaman HTML, yaitu : 

    a) Java script ditulis pada file yang sama.

Contoh Penulisan :

    <HTML>
    <HEAD><TITLE>……….</TITLE>
    </HEAD>
    <BODY>
    kode javascript disini
    </SCRIPT>
    kode HTML disini
    </BODY>
    </HTML>

    b) Javascript ditulis pada file terpisah
    Kode Javascript bisa juga kita buat dalam file terpisah dengan tujuan agar dokumen HTML isinya tidak terlalu panjang.
#
2. Variabel JavaScript

Variabel adalah tempat dimana kita menyimpan nilai-nilai atau informasi-informasi 
pada JavaScript. Variabel yang dideklarasikan dapat di isi dengan nilai apa saja.  Dalam JavaScript pendeklarasian sebuah variabel sifatnya opsional, artinya kita boleh mendeklarasikan atau tidak hal tersebut tidak menjadi masalah. Jika kita
memberi nilai pada variabel, maka dalam JavaScript dianggap bahwa anda telah 
mendeklarasikan variabel tersebut. 
Aturan penamaan variabel : 

    • Harus di awali dengan karakter (huruf atau baris bawah)
    • Tidak boleh menggunakan spasi
    • Huruf Kapital dan kecil memiliki arti yang berbeda
    • Tidak boleh menggunakan kata-kata yang merupakan perintah dalam JavaScript.

Deklarasi Variabel:
    
    Var nama_variabel = nilai 
    Atau 
    Nama_variabel = nilai 
Contoh :

    var nama; 
    var nama = ” Febby Limas Sendelvant” 
    var X = 1998; 
    var Y; 
    Nama = ”Fahmi” 
    X = 1990; 
    Y = 08170223513

2.1 Tipe Data 

Tidak seperti bahasa pemrograman lainnya, JavaScript tidak memiliki tipe data secara 
explisit. Hal ini dapat dilihat dari beberapa contoh variabel diatas. Anda 
mendeklarasikan variabel tapi tidak menentukan tipenya. 
Meskipun JavaScript tidak memiliki tipe data secara explisit. JavaScript mempunyai 
tipe data implisit. Terdapat empat macam tipe data implisit yang dimiliki oleh
JavaScript yaitu :

    • Numerik, seperti : 0222532531, 1000, 45, 3.146789 dsb 
    • String, seperti : “Hallo”, “April”, “Jl. Setiabudi No 17A”, “Cece Kirani” dsb.
    • Boolean, bernilai true atau false 
    • Null, variabel yang tidak di inisilisasi.

2.2 Tipe Numerik 

Pada dasarnya JavaScript hanya mengenal dua macam tipe numerik, yaitu bilangan 
bulat (integer) dan bilangan pecahan(real/float).  Untuk bilangan bulat, kita dapat merepresentasikan dengan basis desimal, oktal atau heksadesimal.

2.3 Tipe String 

Untuk mendeklarasikan tipe string dapat dilakukan dengan cara menuliskan string 
diantara tanda petik tunggal (’) atau tanda petik ganda (”) 

Contoh : 
 
    var str =’Contoh deklarasi string’; 
    var str1 = ”cara ini juga bisa untuk menulis string”;

2.4 Tipe Boolean 

Tipe boolean hanya mempunyai nilai True atau False. Tipe ini biasanya digunakan 
untuk mengecek suatu kondisi atau keadaan. 

Contoh : 

     var X = (Y > 90); 

contoh diatas menunjukkan bahwa jika Y lebih besar dari 90 maka X akan bernilai 
True. 

2.5 Tipe Null 

Tipe Null digunakan untuk merepresentasikan variabel yang tidak diberi nilai awal 
(inisialisasi). 

2.6 Operator 
Operator pada JavaScript terbagi menjadi enam, yaitu : 

    • Aritmatika 
    • Pemberian nilai (Assign) 
    • Pemanipulasian bit (bitwise) 
    • Pembanding 
    • Logika 
    • String


a. Operator Aritmatika 

Digunakan untuk operan beripe numerik. Ada dua macam operator aritmatik, yaitu 
operator numerik tunggal dan operator aritmatik biner. Perbedaan kedua operator 
terletak pada jumlah operan yang harus dioperasikan.

b. Operator Pemberian Nilai 

Digunakan untuk memberikan nilai ke suatu operan atau mengubah nilai suatu 
operan.

c. Operator manipulasi bit

Operasi ini berhubungan dengan 
pemanipulasian bit pada operan bertipe bilangan 
bulat.

Contoh : 

    var A = 12; // A = 1100b 
    var B = 10; // B = 1010b 
    var C = A & B 
    maka akan dihasilkan bilangan seperti berikut : 
    1100b 
    1010b AND
    1000b 
    var A = 12; 
    var C = A<< 2 
    var D = A >> 1 
    
maka variabel C akan bernilai 48(0011 0000b) 
variabel D akan bernilai 6 (0110b).

d. Operator Pembanding 

Digunakan untuk membandingkan dua buah operan. Operan yang dikenal operator ini 
dapat bertipe string, numerik, maupun ekspresi lain.

e. Operator Logika 

Digunakan untuk mengoperasikan operan yang bertipe boolean. 

Contoh : 

    var A = true; 
    var B = false; 
    var C = A && B; //menghasilkan false 
    var D = A || B ; // false 
    var E = !A; //false

 f. Operator String 

Selain operator pembanding, operator string pada JavaScript juga mengenal satu 
operator lagi yang bernama PENGGABUNGAN. Operator ini digunakan untuk 
menggabungkan beberapa string menjadi sebuah string yang lebih panjang. 

Contoh : 

    nama = ”Java” + ”Script”; 
    akan menghasilkan ”JavaScript” pada variabel nama

Contoh Program Javascript
    
    nama = ”Java” + ”Script”; 
    akan menghasilkan ”JavaScript” pada variabel nama

    Contoh Program JavaScript 
    <HTML> 
    <HEAD><TITLE>Operasi Aritmatika</TITLE></HEAD> 
    <BODY> 
    <P><SCRIPT language="JavaScript"> 
    <!-- 
    document.writeln("<PRE>"); 
    document.writeln("<H1>Operasi Aritmatik</H1>"); 
    var A = "100"; 
    var B = "200"; 
    var C = 300; 
    var D = 400; 
    var E = A + B; 
    document.writeln('"100" + "200" = ' +   E); 
    E = B + C; 
    document.writeln('"200" + 300 = ' + E); 
    E = C + D; 
    document.writeln('300 + 400 = ' + E); 
    document.writeln("<PRE>"); 
    //--> 
    </SCRIPT></P> 
    </BODY>     
    </HTML

Output yang di tampikan :
#
![alt text](string.png)
#
2.7 Memasukkan Data

Untuk memasukkan data dari keyboard dapat dilakukan dengan menggunakan 
perintah input.

Contoh Program JavaScript

    <HTML> 
    <HEAD><TITLE>Memasukkan Bilangan</TITLE></HEAD> 
    <BODY> 
    <P><SCRIPT language="JavaScript"> 
    <!-- 
    function jumlah() 
    { 
    var bil1 = parseFloat(document.fform.bilangan1.value); 
    if (isNaN (bil1)) 
    bil1=0.0; 
    var bil2 = parseFloat(document.fform.bilangan2.value); 
    if (isNaN (bil2)) 
    bil2=0.0; 
    var hasil = bil1 + bil2; 
    alert ("Hasil Penjumlahan = " + hasil); 
    } 
    //--></SCRIPT></P> 
    <FORM NAME ="fform"> 
    <H1><BR>Memasukkan Data Lewat Keyboard</H1> 
    <PRE> 
    Bilangan Pertama :<input type="text" size="11" name="bilangan1"> 
    Bilangan Kedua :<input type="text" size="11" name="bilangan2"> 
    </PRE> 
    <P> 
    <INPUT TYPE="button" value="Jumlahkan" onclick="jumlah()"> 
    <INPUT TYPE="reset" value="Ulang"> 
    </FORM> 
    </BODY> 
    </HTML>

Output yang di tampilkan :
#
![alt text](memasukkan_data.png)
#
*B. Objek Javascript*

Objek Untuk memasukkan Data 
Terdapat beberapa objek yang dapat digunakan untuk memeasukkan data.Objek-objek tersebut biasanya terdapat dalam suatu form. Adapun objek-objek tersebut meliputi Objek Text, Objek Radio, Objek Checkbox, Objek Textarea, dan Objek 
Select. 

1. Objek Text,Untuk menginputkan data kita dapat menggunakan komponen/objek text. 

2.Objek Radio, Objek Radio 
Objek radio adalah komponen yang digunakan untuk melakukan suatu pemilihan data. 
Karena selalu berupa Array , untuk mengakses satu tombol radio digunakan 
radio[indeks]. Disamping itu objek radio juga mempunyai nili True jika dipilih dan 
False jika tidak. Untuk memilih suatu objek radio menggunakan properti Checked.

3.Objek Checkbox, Objek checkbox menyimpan informasi tentang elemen form yang berupa kotak cek. 
Penggunaannya hampir sama seperti objek radio.

4.Objek TextArea, Objek textarea menyimpan informasi tentang elemen form yang berupa kotak teks dengan banyak baris.

5.Objek Select, Objek Select menyimpan informasi tentang elemen form yang berupa kotak daftar. Objek select berguna apabila di dalam form terdapat banyak pilihan yang telas  mempunyai nilai tertentu.

6. Objek String, String adalah suatu objek yang merupakan kumpulan dari elemen karakter-karakter. Dalam Javascript string atau karakter harus diapit dengan tanda petik ganda(“) atau tanda petik tunggal(‘). 

Contoh pendeklarasian Objek String : 

    Nama = “Shafana Vevica” 
    Panjang = Nama,length; // Panjang akan berisi 14 

Length adalah property yang sering digunakan dalam objek string yang digunakan 
Untuk mengetahui banyaknya karakter dalam suatu string.  Objek String juga memiliki method yang dapat digunakan untuk memanipulasi string tersebut. Adapun Method yang dapat digunakan meliputi : 

![alt text](string2.png)

7. Objek Document, objek ini digunakan untuk mengakses informasi mengenai dokumen HTML, tampilan output dan memanipulasinya. 
Property dari objek document meliputi :

![alt text](objekdocument.png)

Method dari objek document meliputi : 

![alt text](objekdocument2.png)

*C. Percabangan*

Untuk membuat suatu halaman yang dinamis dan interaktif, perancang halaman Web 
membutuhkan perintah-perintah yang dapat mengatur aliran dari informasi. 
Berdasarkan hasil komputasi yang telah dilakukan, JavaScript akan membuat 
keputusan jalur mana yang akan dieksekusi. 
Pada dasarnya dalam JavaScript terdapat dua macam pernyataan percabangan yaitu 
if..else dan switch.

1.If else, Pernyataan ini digunakan untuk menguji sebuah kondisi dan kemudian mengeksekusi pernyataan tertentu bila kondisi tersebut terpenuhi, dan mengeksekusi pernyataan lain 
bila kondisi tersebut tidak terpenuhi. 

    if (kondisi) 
    { 
    //pernyataan1 dieksekusi 
    //bila kondisi terpenuhi 
    } 
    else 
    { 
    //pernyataan2 dieksekusi 
    //bila kodisi tidak terpenuhi 
    } 
kondisi adalah ekspresi JavaScript yang mana hasil evaluasinya memiliki nilai 
Boolean true atau false 
Untuk kasus yang melibatkan lebih banyak kondisi, maka kita dapat meletakkan 
pernyataan if lain setelah else 
   
    if (kondisi1) 
    { 
    //pernyataan1 dieksekusi 
    //bila kondisi1 terpenuhi 
    } 
    else if (kondisi2) 
    { 
    //pernyataan2 dieksekusi 
    //bila kodisi1 tidak terpenuhi 
    } 
    else 
    { 
    //pernyataan3 dieksekusi 
    //bila kodisi2 tidak terpenuhi 
    } 

2. Percabangan Majemuk, Percabangan majemuk adalah suatu percabangan yang dapat melibatkan lebih dari 1 kondisi di dalam percabangannya. Biasanya percabangan sepert ini menggunakan 
operator tambahan seperti AND, OR dan sebagainya.

3.  Switch, Selain menggunakan if..else, percabangan juga dapat ditangani dengan perintah 
switch. Dengn kata lain pernyataan switch digunakan untuk menyederhanakan 
pernyataan if..else yang terlalu banyak.

*D. Perulangan*

 1. Perulangan 

Untuk mengulang kejadian beberapa kali maka kita membutuhkan proses perulangan. 
Pada JavaScript dikenal beberapa metode/cara perulangan. 

2. Perulangan For 

Digunakan untuk mengeksekusi pernyataan-pernyataan beberapa kali. Perulangan For paling sering dipakai, jika anda sudah tahu akhir dari perulangan tersebut. . Perintah for mengulang suatu loop sampai kondisi menghasilkan evaluasi true atau loop keluar dengan perintah break .

Contoh : 

    for (nilai awal;kondisi;penambahan) 
    { 
    ulang pernyataan ini; 
    } 

Contoh dalam program :

    For(x=1;x<=10;x++) 
    { 
    document.writeln(”Belajar JavaScript Yuuuuu..”); 

3. Perulangan While 
Perulangan lain yang dapat digunakan adalah dengan menggunakan perintah While. 
Perintah while digunakan untuk perulangan yang tidak diketahui berapa kali proses 
perulangannya. Perintah while terus mengulangi loop selama kondisi memiliki nilai true. Syntax untuk perintah while adalah sebagai berikut :

    while (kondisi) 
    
    { 
    ulang pernyataan ini; 

    }

4. Perulangan Do While

Perulangan ini hampir sama seperti while, digunakan apabila kita belum tahu berapa 
kali perulangan harus dilakukan. Bedanya pernyataan do..while pengujiannya 
dilakukan di akhir pernyataan. 

    Do 
    { 
    //pernyataan1 dieksekusi 
    } 
    while (kondisi);

*E. Kejadian (Event)*

Kejadian (Event) Even adalah sesuatu yang terjadi pada halaman HTML. Berikut ini terdapat beberapa bentuk kejadian yaitu jika pengguna memuat dokumen, pengguna memasukkan data, pengguna mengklik tombol dan sebagainya. Hal-hal tersebut diatur oleh even. Semua kejadian pada Javascript dapat anda tangani dengan menentukan kejadiannya. Biasanya kejadian(even) adalah sebuah fungsi, tetapi pada beberapa kasus, kita dapat menuliskan pernyataan-pernyataannya secara langsung. 
Berikut ini adalah daftar kejadian(even) pada JavaScript :

![alt text](event.png)

1. Event On Submit
Event on submit akan dibangkitkan apabila seorang user menekan tombol submit. 
Dengan event ini data yang diinputkan akan dikirimkan ke tempat lain (email, file 
teks atau ke dalam suatu tabel).

2.Manipulasi Gambar 
Untuk memuat suatu image, pada Javascript terdapat objek Image. Untuk membuat
objek tersebut pendeklarasiannya adalah sebagai berikut : 

    img1 = new Image () 
    img1.src = "pic1.gif" 

artinya membuat objek image dengan isinya adalah image pic1.gif.


*F. Materi DOM*

1. Pengertian Dom

Pengertian DOM
Pada tingkat paling dasar, situs web terdiri dari dokumen HTML dan CSS. Browser membuat representasi dokumen yang dikenal sebagai Document Object Model (DOM). Dokumen ini memungkinkan Javascript untuk mengakses dan memanipulasi elemen dan style situs web. Model ini dibangun dalam struktur objek dan mendefinisikan:

- Elemen HTML sebagai objek
- Properties dan event elemen HTML
- Method untuk mengakses elemen HTML

![alt text](dom.gif)

Elemen-elemen di atas disebut sebagai node. Tidak hanya elemen yang mendapatkan node tetapi atribut elemen dan teks juga mendapatkan node sendiri, yaitu attribute-node dan text-node.

*DOM Document*
DOM Document adalah keseluruhan objek yang ada di laman web Anda. Jika Anda ingin mengakses objek apa pun di halaman web Anda, Anda harus selalu mulai dengan dokumen tersebut. Karena ada banyak properties dan method penting yang bisa Anda gunakan untuk mengakses dan memodifikasi situs web Anda.

2. Cara Mendapatkan Elemen HTML Mendapatkan elemen dengan ID
Method getElementById() digunakan untuk mendapatkan elemen tunggal dengan id-nya. Mari kita lihat sebuah contoh:

    var title = document.getElementById(‘header-title’);

Di sini kita mendapatkan elemen dengan id header-title dan menyimpannya ke dalam variabel. Mendapatkan elemen dengan nama kelas Kita juga bisa mendapatkan lebih dari satu objek dengan menggunakan method getElementsByClassName().

    var items = document.getElementsByClassName(‘list-items’);

Di sini kita mendapatkan semua item dengan kelas list-items dan menyimpannya ke dalam variabel.

3. Mendapatkan elemen dengan nama tag

Kita juga bisa mendapatkan elemen kita dengan nama tag menggunakan method getElementsByTagName().

    var listItems = document.getElementsByTagName(‘li’);

Di sini kita mendapatkan semua elemen li dari dokumen HTML kita dan menyimpannya ke dalam variabel.

4.Queryselector

Method querySelector() mengembalikan elemen pertama yang cocok dengan CSS selector yang ditentukan. Itu berarti bahwa Anda bisa mendapatkan elemen dengan id, kelas, tag dan semua CSS selector yang valid. Berikut adalah daftar beberapa opsi yang paling populer.

Get by id:

    var header = document.querySelector(‘#header’)

Get by class:

    var items = document.querySelector(‘.list-items’)

Get by tag:

    var headings = document.querySelector(‘h1’);

5. Mendapatkan elemen yang lebih spesifik:

Kita juga bisa mendapatkan elemen yang lebih spesifik menggunakan CSS Selector.

    document.querySelector(“h1.heading”);

Dalam contoh ini kita mencari tag dan kelas secara bersamaan dan mengembalikan elemen pertama yang melewati CSS Selector.

6. Queryselectorall

Method querySelectorAll() sepenuhnya sama dengan method querySelector() kecuali saat ia mengembalikan semua elemen yang sesuai dengan CSS Selector.

    var heading = document.querySelectorAll(‘h1.heading’);

Dalam contoh ini, kita mendapatkan semua tag h1 yang memiliki kelas heading dan menyimpannya dalam array.

7. Mengubah Elemen HTML

HTML DOM memungkinkan kita mengubah konten dan style elemen HTML dengan mengubah propertinya.

 - Mengubah HTML
Properti innerHTML dapat digunakan untuk mengubah konten elemen HTML.

     document.getElementById(“#header”).innerHTML = “Hello World!”;

Dalam contoh ini kita mendapatkan elemen dengan id header dan mengatur konten inner menjadi “Hello World!”.

- InnerHTML juga dapat digunakan untuk menempatkan tag di tag lain.

        document.getElementsByTagName("div").innerHTML = "<h1>Hello World!</h1>"

Di sini kita meletakkan tag h1 ke semua div yang sudah ada.

8. Mengubah nilai atribut

Anda juga dapat mengubah nilai atribut menggunakan DOM.

    document.getElementsByTag(“img”).src = “test.jpg”;

Dalam contoh ini kita mengubah src dari semua tag <img/> menjadi test.jpg.

9. Mengubah style

Untuk mengubah style elemen HTML, kita perlu mengubah properti style elemen kita. Berikut ini contoh sintaks untuk mengubah style:

    document.getElementById(id).style.property = new style

Sekarang mari kita lihat contoh di mana kita mendapatkan elemen dan mengubah batas bawah menjadi garis hitam solid:

    document.getElementsByTag(“h1”).style.borderBottom = “solid 3px #000”;

Properti CSS perlu ditulis dalam camelcase bukan nama properti css normal. Dalam contoh ini kita menggunakan borderBottom.

10. Menambah dan menghapus elemen

Sekarang kita akan melihat bagaimana kita dapat menambahkan elemen baru dan menghapus yang sudah ada.

- Menambahkan elemen
Berikut ini contoh sintaks untuk menambah elemen:

    var div = document.createElement(‘div’);

Di sini kita hanya membuat elemen div menggunakan method createElement() yang mengambil tagname sebagai parameter dan menyimpannya ke dalam variabel. Setelah itu kita hanya perlu memberikan beberapa konten dan kemudian memasukkannya ke dokumen DOM kita.

    var newContent = document.createTextNode("Hello World!");
    div.appendChild(newContent);
    document.body.insertBefore(div, currentDiv);

Di sini kita membuat konten menggunakan method createTextNode() yang menggunakan sebuah String sebagai parameter dan kemudian kita memasukkan elemen div baru sebelum div yang sudah ada dalam dokumen kita.

11. Menghapus elemen

Berikut ini contoh sintaks untuk menghapus elemen:

    var elem = document.querySelector('#header');
    elem.parentNode.removeChild(elem);

Di sini kita mendapatkan elemen dan menghapusnya menggunakan method removeChild().

!2. Mengganti elemen

Berikut ini contoh sintaks untuk mengganti elemen:

    var div = document.querySelector('#div');
    var newDiv = document.createElement(‘div’);
    newDiv.innerHTML = "Hello World2"
    div.parentNode.replaceChild(newDiv, div);

Di sini kita dapat mengganti elemen menggunakan method replaceChild(). Argumen pertama adalah elemen baru dan argumen kedua adalah elemen yang ingin kita ganti.

Menulis langsung ke HTML output stream
Kita juga dapat menulis ekspresi HTML dan JavaScript langsung ke HTML output streammenggunakan method write().

    document.write(“<h1>Hello World!</h1><p>This is a paragraph!</p>”);

Kita juga dapat meneruskan ekspresi JavaScript seperti objek tanggal.

    document.write(Date());

Method write() juga dapat mengambil beberapa argumen yang akan ditambahkan ke dokumen sesuai dengan kemunculannya.

13.Event Handlers

HTML DOM juga memungkinkan Javascript untuk bereaksi terhadap HTML event. Berikut adalah daftar beberapa yang paling penting:

- mouse click
- page load
- mouse move
- input field change
- Assign Events

Anda dapat menentukan event secara langsung dalam kode HTML Anda dengan menggunakan atribut pada tag Anda. Berikut adalah contoh event onclick:

    <h1 onclick=”this.innerHTML = ‘Hello!’”>Click me!</h1>

Dalam contoh ini, teks h1 akan berubah menjadi “Halo!” Saat Anda mengklik tombol.

Anda juga dapat memanggil fungsi saat suatu event dipicu seperti yang Anda lihat pada contoh berikut.

    <h1 onclick=”changeText(this)”>Click me!</h1>

Di sini kita memanggil method changeText() ketika tombol diklik dan meneruskan elemen sebagai atribut.

Kita juga dapat menetapkan event yang sama dalam kode Javascript kita.

    document.getElementById(“btn”).onclick = changeText();

14. Assign Events Listeners

Berikut ini contoh sintaks untuk menentukan event listeners ke elemen HTML:

    document.getElementById(“btn”)addEventListener('click', runEvent);

Di sini kita hanya menetapkan clickevent yang memanggil method runEvent ketika elemen ‘btn’ Anda diklik.

Anda juga dapat menetapkan beberapa event ke satu elemen:

    document.getElementById(“btn”)addEventListener('mouseover', runEvent);

15. Node Relationships

Node dalam DOM Document memiliki hubungan hierarki satu dengan yang lain, terstruktur seperti pohon. Di sini kita menggunakan istilah parent, sibling, dan child untuk menggambarkan hubungan antar node.

Node paling atas disebut root dan merupakan satu-satunya node yang tidak memiliki parent. Root dalam dokumen HTML normal adalah tag <html /> karena tidak memiliki parent dan merupakan tag teratas di dokumen.

Menavigasi Antar Node
Kita dapat menavigasi antar node menggunakan properti berikut ini:

- parentNode
- childNodes
- firstChild
- lastChild
- nextSibling

Berikut adalah contoh bagaimana Anda bisa mendapatkan elemen parent dari h1.

    var parent = document.getElementById(“heading”).parentNode
    <SCRIPT LANGUAGE=”Javascript”>