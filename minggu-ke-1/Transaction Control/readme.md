## Transcation Control 

### Outline 
* Konsep Transcation Control 
* Fungsi Transaction Control 
* Kasus Transaction Control 

### Memahami konsep Transaction Control 
<img src="https://github.com/rizko-d/BTPN-Syariah-Data-Engginer-Virtual-Internship-Program/blob/main/minggu-ke-1/Transaction-Control/1.jpg">

### Implementasi Transaction Control 
* Batch Processing, dimana baris, dan isi didalam table harus berubah dalam satu kesatuan 
* Mengubah data yang ada pada dua atau lebih database
* Distributed Transaction, dimana data bersangkutan dengan database yang berbeda server

### Transaction Control ACID Properties 
* Atomicity,dimana kumpulan proses terpisah dianggap sebagai satu proses.
* Consistency, yaitu hasil transaksi tidak mengubah database, jika proses itu gagal
* Isolation, Setiap transaksi memiliki batasan dan lingkup yang berbeda dengan yang lain
* Durability, jika transaksi sukses, hasil data akan tersimpan dan terproses pada database

### Transaction Control Statements 
* Begin Transaction, Menyatakan statement transaksi dimulai
* Commit, Pernyataan untuk perubahan di Transaksi.
* Rollback, Pernyataan untuk transaksi yang gagal.
<img src="https://github.com/rizko-d/BTPN-Syariah-Data-Engginer-Virtual-Internship-Program/blob/main/minggu-ke-1/Transaction-Control/2.jpg">

