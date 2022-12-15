## A. Tahap Melakukan Data Modeling
Pada materi reading sebelumnya, kita telah mempelajari tahap tahap dan 
bentuk dari Data Modeling, untuk merangkumnya berikut hal hal yang harus 
dipersiapkan saat melakukan Data Modeling :
* 1. Memilih teknik / model Data Modeling yang ingin digunakan, dapat berupa 
Entity Relationship Diagram, Hierarchical Data Model, Relational Data 
Model, Network Data Model atau Object Oriented Data Model.
* 2. Selanjutnya adalah mengidentifikasi entitas dan elemen yang ada pada 
transaksi bisnis, berikan keterangan pada setiap data atau elemen yang 
ada pada entitas bisnis.
* 3. Memberikan relasi dan hubungan antara elemen dan entitas, dapat 
berupa one to many, many to many, atau many to one.
* 4. Selanjutnya adalah memberikan keterangan atribut, tipe data, atau 
spesifikasi data lainnya
* 5. Terakhir adalah memberikan keterangan primary, atau secondary, key 
pada elemen di dalam entitas
Setelah kita memahami tahap untuk melakukan Data Modeling, kita akan 
menerapkannya pada studi kasus 

##. B Studi Kasus
Untuk mempermudah kalian memahami konsep dari aktivitas Data Modeling, 
kalian akan diberikan sebuah contoh kasus.
Bayangkan kalian memiliki sebuah perusahaan pulpen. Dan pada perusahaan 
ini, ada tiga unit yang bekerja yaitu : vendor tempat membeli bahan pulpen, produksi 
yaitu perusahaan kalian, dan pelanggan yaitu retail.
Berdasarkan materi yang telah kita pelajari sebelumnya, dalam melakukan data 
modeling ada tiga tahap : Yaitu Conceptual Model, Logical Model, dan Physical Model. 
Lalu bagaimana kita membuat data model menggunakan ERD? Berikut tahap 
tahapannya :

### 1. Conceptual Model
Pada tahap ini, data diidentifikasi sesuai dengan data yang dibutuhkan 
atau transaksi bisnis yang terjadi pada perusahaan. Telah kita ketahui bahwa 
pada perusahaan pulpen ini, terjadi dua transaksi bisnis, yaitu Vendor ke 
Produksi, dan Produksi ke Pelanggan. Sehingga dapat kita definisikan Model 
Conceptual sebagai berikut : 

<img src ="https://github.com/rizko-d/BTPN-Syariah-Data-Engginer-Virtual-Internship-Program/blob/main/minggu-ke-2/Data%20Modeling%20Case%20Study/a1.jpg">
Perlu diketahui bahwa saat kita merancang model Conceptual, model 
tersebut harus sesederhana mungkin, namun tidak menghilangkan transaksi 
bisnis sama sekali.

### 2. Logical Model
Selanjutnya adalah Logical Model. Dalam tahap ini entitas yang telah kita 
rancang sebelumnya, perlu diberikan keterangan tambahan. Yaitu menambah 
elemen atau data di dalam entitas dan memberikan hubungan antar entitas 
yang jelas. Perhatikan Logical Model dibawah :

<img src="https://github.com/rizko-d/BTPN-Syariah-Data-Engginer-Virtual-Internship-Program/blob/main/minggu-ke-2/Data%20Modeling%20Case%20Study/a2.jpg"> 
Figur diatas adalah salah satu bentuk dari Logical Model dari perusahaan 
pulpen yang kita analisis. Berbeda dari Conceptual model sebelumnya, tiap 
entitas ditambahkan elemen dan data didalamnya. Contohnya pada entitas 
vendor memiliki data “Avg. Sale” dan “Number of item Purchase”. Perlu diingat 
bahwa tiap elemen tersebut belum merupakan nama elemen akhir, dan hanya 
penjelasan dari isi elemen tersebut. 
ID entitas juga dituliskan walau belum dijelaskan secara eksplisit, nantinya 
ID entitas akan diubah menjadi elemen primary key pada entitas tersebut. 
Terakhir, hubungan antar entitas dijelaskan menggunakan garis yang 
disebut sebagai “Crow’s Foot Notation” dan menjelaskan hubungan antar 
entitas, seperti entitas produksi pada entitas customer yang berhubungan 
secara One to Many.

### 3.  Physical Model
Tahap ini merupakan tahap akhir dari Data Modeling, premis dari model 
ini adalah melengkapi Logical Model yang kita bentuk sebelumnya sehingga 
data model memiliki keterangan data type, kolom, index, constraints, dan 
elemen DBMS lainnya. Perhatikan figur dibawah ini 

<img src ="https://github.com/rizko-d/BTPN-Syariah-Data-Engginer-Virtual-Internship-Program/blob/main/minggu-ke-2/Data%20Modeling%20Case%20Study/a3.jpg">

Pada figur diatas, kita dapat melihat perbedaan antara Logical Model dan 
Physical Model, perbedaan yang paling jelas adalah menambahkan data type 
dari tiap elemen di entitas. 
Mungkin contoh kasus diatas masih terlalu general, namun penerapannya 
di dunia professional lebih rumit. Bayangkan perusahaan pulpen kalian memiliki 
4 vendor yang berbeda atau pulpen yang akan dijual ke retail membutuhkan 3 
kali produksi dari 3 produsen yang berbeda. Yang penting kalian telah 
mempelajari bentuk dan perbedaan dari tiap tahap dan cara 
mengaplikasikannya

## Referensi 
* https://www.dewaweb.com/blog/entity-relationship-diagram/
