## A. Definisi Entity Relationship Diagram
   Entity Relational Diagram (ERD) merupakan salah satu model yang 
digunakan untuk memahami lebih dalam sebuah database. ERD memberikan 
penjelasan yang jelas mengenai atribut, visual, dan hubungan antara entitas. 
Model ERD marak digunakan oleh perusahaan dalam merancang Data 
Modelingnya, hal ini dikarenakan ERD memberikan informasi yang jelas dan juga 
mudah untuk digunakan.

<img src ="https://github.com/rizko-d/BTPN-Syariah-Data-Engginer-Virtual-Internship-Program/blob/main/minggu-ke-2/Entity%20Relationship%20Diagram/ase.jpg">

Figur di atas merupakan contoh bentuk dari model ERD, dimana ERD 
digunakan untuk menjadi model database suatu Ski Resort. Dapat dilihat 
hubungan antar entitas, atribut data, dan visual data.

## B. Komponen Penyusun ERD
Dalam penyusunannya, ERD sendiri memiliki beberapa komponen 
tersendiri yang membedakan model ini dengan teknik data model lainnya. 
Komponen dari ERD tersebut antara lain:
* **a. Entitas** <br>
Entitas merupakan sebuah kumpulan elemen atau objek yang 
dapat diidentifikasikan secara unik atau saling berbeda. Biasanya, 
simbol dari entitas adalah persegi panjang.
* **b. Atribut** <br>
Komponen kedua adalah Atribut. Setiap entitas memiliki elemen 
yang disebut atribut yang berfungsi untuk mendeskripsikan karakteristik 
dari entitas tersebut. Atribut kunci merupakan hal pembeda atribut 
dengan entitas. Gambar atribut diwakili oleh simbol elips dan terbagi 
menjadi beberapa jenis:
   * a. Atribut kunci (key): atribut yang digunakan untuk menunjukan 
   entitas secara unik. Biasanya berupa kode yang tidak bisa dimiliki 
   oleh elemen lain.
   * b. Atribut simpel: atribut bernilai tunggal yang tidak dapat dipecah 
   lagi . contohnya adalah alamat, tanggal dan tahun terbit.
   * c. Atribut multi nilai: atribut yang memiliki sekelompok nilai untuk 
   setiap entitas instan. Contoh: nama beberapa pengarang dari 
   sebuah buku pelajaran.
   * d. Atribut gabungan: atribut yang terdiri dari beberapa atribut yang 
   lebih kecil dengan arti tertentu. Contoh: nama lengkap yang 
   terbagi menjadi nama depan, tengah, dan belakang.
   * e. Atribut derivatif: atribut yang dihasilkan dari atribut lain dan 
   tidak wajib ditulis dalam diagram ER. Contoh: usia, kelas, selisih 
   harga.
* **c. Relasi** <br>
Komponen ini merupakan hubungan antar elemen pada entitas 
yang berbeda. Komponen ini biasanya dilambangkan dengan berbentuk 
garis penghubung antara entitas. Relasi memiliki beberapa jenis yaitu : 
   * a. One to One : setiap entitas hanya bisa mempunyai relasi dengan 
       satu entitas lain. 
   * b. One to Many :hubungan antara satu entitas dengan beberapa 
       entitas dan sebaliknya. 
   * c. Many to Many : setiap entitas bisa mempunyai relasi dengan 
      entitas lain, dan sebaliknya.
      
## Referensi :
https://www.dewaweb.com/blog/entity-relationship-diagram
