## Statemen Pada TSQL 

<table>
	<caption>Statement pada TSQL merupakan sebuah perintah yang terdapat pada TSQL. Terdapat 
macam-macam statement yang terdapat pada TSQL, beberapa diantaranya yaitu :</caption>
	<thead>
	<tr>
		<th>Statemen</th>
		<th>Deskripsi</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>Select</td>
		<td>Select digunakan untuk memanipulasi data dengan tujuan menampilkan 
maupun mengambil sebuah data pada tabel. Berikut contoh statement jika kita 
ingin mengambil semua kolom pada tabel Customers.
SELECT * FROM Customers;</td>
	</tr>
	<tr>
		<td>Where</td>
		<td>WHERE merupakan perintah dasar yang digunakan untuk memfilter hasil 
SELECT dengan mengekstrak record yang memenuhi persyaratan tertentu.
SELECT kolom1, kolom2, … FROM nama_tabel WHERE kondisi;
</td>
	</tr>
	<tr>
		<td>Order By</td>
		<td>Perintah ORDER BY merupakan perintah yang digunakan untuk mengurutkan 
result-set dalam pengurutan ‘ascending’ atau ‘descending’. Secara default 
perintah ORDER BY menampilkan record dalam pengurutan ‘ascending’ (‘ASC’). 
Untuk mengurutkan ‘descending’, gunakan kata kunci ‘DESC’.
SELECT kolom1, kolom2, … FROM nama_tabel ORDER BY column DESC;
SELECT nis, nama FROM siswa ORDER BY tahun_lahir DESC;;</td>
	</tr>
	<tr>
		<td>Insert INTO</td>
		<td>Perintah INSERT INTO dapat di gunakan untuk menambahkan record baru ke 
dalam tabel.
INSERT INTO nama_tabel VALUES (nilai1, nilai2, nilai3, …);
INSERT INTO nama_tabel (kolom1, kolom2) VALUES (nilai1, nilai2);</td>
	</tr>
	<tr>
		<td>Update</td>
		<td>Perintah UPDATE merupakan perintah yang digunakan untuk memperbarui 
atau mengubah nilai suatu record berdasarkan kriteria tertentu.
UPDATE nama_tabel SET kolom1 = nilai1, kolom2 = nilai2, … WHERE kondisi;</td>
	</tr>
	<tr>
		<td>Create</td>
		<td>Perintah CREATE merupakan perintah yang digunakan untuk membuat 
database atau tabel.
CREATE DATABASE namadatabase;</td>
	</tr>
	<tr>
		<td>Delete</td>
		<td>Perintah DELETE merupakan perintah yang di gunakan untuk menghapus nilai 
suatu record berdasarkan kriteria tertentu.
DELETE FROM table_name WHERE condition;</td>
	</tr>
	<tr>
		<td>Min</td>
		<td>MIN merupakan perintah yang di gunakan untuk mendapatkan nilai terkecil dari 
suatu kolom. MIN hanya menampilkan satu record saja yang memenuhi kriteria 
yang ditentukan.
SELECT MIN(nama_kolom) FROM nama_tabel WHERE kondisi;</td>
	</tr>
	<tr>
		<td>Max</td>
		<td>MAX merupakan perintah yang di gunakan untuk mendapatkan nilai terbesar 
dari suatu kolom.
SELECT MAX(nama_kolom) FROM nama_tabel WHERE kondisi</td>
	</tr>
	<tr>
		<td>Count</td>
		<td>MAX merupakan perintah yang di gunakan untuk mendapatkan nilai terbesar 
dari suatu kolom.
SELECT MAX(nama_kolom) FROM nama_tabel WHERE kondisi</td>
	</tr>
	<tbody>
</table>
