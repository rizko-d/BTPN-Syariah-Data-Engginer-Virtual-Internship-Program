## Clause Pada TSQL 

<table>
	<caption>Clause adalah fungsi bawaan yang tedapat pada TSQL. Dengan bantuan clause, kita 
dapat menangani data yang disimpan dalam tabel dengan mudah.
Clause membantu untuk memfilter dan menganalisis data dengan cepat. Ketika kita 
memiliki sejumlah besar data yang disimpan dalam database, kita menggunakan 
clause untuk melakukan kueri dan mendapatkan data yang dibutuhkan oleh 
pengguna. Berikut merupakan contoh beberapa kalusa, yaitu :</caption>
	<thead>
	<tr>
		<th>Klausa</th>
		<th>Deskripsi</th>
		<th>Contoh</th>
    <th>Command</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>Where Clause</td>
		<td>Klausa WHERE berfungsi untuk memilih baris berdasarkan ekspresi boolean. 
Hanya baris yang ekspresinya dievaluasi menjadi TRUE yang dikembalikan 
dalam hasil.</td>
		<td>Ambil kolom ID, NAME, dan SALALRY dari tabel CUSTOMERS dimana 
SALARY lebih besar dari 2000</td>
    <td>SELECT ID, NAME, SALARY 
FROM CUSTOMERS
WHERE SALARY > 2000;
</td>
	</tr>
	<tr>
		<td>Limit Clause</td>
		<td>Klausa LIMIT digunakan ketika kita memiliki sejumlah besar data dalam tabel. 
Dengan bantuan klausa LIMIT, kita dapat membatasi jumlah baris yang 
dikembalikan oleh kueri kita.</td>
		<td>Ambil 5 data dari semua kolom yang berasal dari tabel employee</td>
    <td>SELECT *
FROM employee 
LIMIT 5;</td>
	</tr>
	<tr>
		<td>Order By Clause</td>
		<td>Klausa ORDER BY digunakan untuk mengurutkan data dalam urutan ascending 
atau descending sesuai kebutuhan pengguna. Secara default, data diurutkan 
dalam urutan ascending
</td>
		<td>Mari kita lihat detail dari data employee yang diurutkan berdasarkan 
descending dari kolom salary
</td>
    <td>SELECT *
FROM employee 
ORDER BY salary DESC ;</td>
	</tr>
	<tr>
		<td>Delete Clause</td>
		<td>Klausa DELETE berfungsi untuk menghapus catatan yang ada dari tabel.</td>
		<td>Hapuslah data yang memiliki kolom emp_id = ‘B83’</td>
    <td>DELETE FROM employee
WHERE emp_id = ‘B83’ ;
SELECT * FROM employee
</td>
	</tr>
	<tr>
		<td>Update Clause</td>
		<td>Klausa UPDATE berfungsi untuk memperbarui catatan yang ada di database.</td>
		<td>Update data experience James menjadi 15 tahun</td>
    <td>UPDATE employee
SET experience = 15
WHERE name = ‘James’ ;
SELECT * FROM employee
</td>
	</tr>
	<tbody>
</table>


## Resource 
* https://docs.oracle.com/
* https://www.tutorialspoint.com/sql/sql-where-clause
* https://data-flair.training/blogs/clause-in-sql/
