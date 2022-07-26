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
