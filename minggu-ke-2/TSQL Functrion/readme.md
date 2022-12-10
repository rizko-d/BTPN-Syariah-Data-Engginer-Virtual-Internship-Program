## T-SQL Function
> Fungsi adalah metode yang digunakan untuk melakukan operasi data. TSQL memiliki banyak fungsi bawaan yang digunakan untuk melakukan rangkaian string, perhitungan matematis, dan lain-lain. Fungsi TSQL dikategorikan ke dalam dua kategori, yaitu fungsi agregat dan fungsi skala


<table>
	<caption>Fungsi Agregat</caption>
	<captopn>Fungsi Agregat dalam TSQL melakukan perhitungan pada sekelompok nilai dan 
kemudian mengembalikan satu nilai. Berikut ini adalah beberapa fungsi agregat yang 
paling umum digunakan:</caption
	<thead>
	<tr>
		<th>Function</th>
		<th>Syntax</th>
		<th>Fungsi</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>SUM</td>
		<td>SELECT SUM(ColumnName)
    FROM TableName;</td>
		<td>Fungsi SUM digunakan untuk menghitung jumlah dari sekumpulan nilai</td>
	</tr>
	<tr>
		<td>AVG</td>
		<td>SELECT AVG(ColumnName)
    FROM TableName;
</td>
		<td>Fungsi AVG digunakan untuk mengembalikan nilai rata-rata
</td>
	</tr>
	<tr>
		<td>COUNT</td>
		<td>SELECT COUNT(ColumnName)
    FROM TableName;</td>
		<td>Fungsi COUNT digunakan untuk menghitung jumlah baris yang dikembalikan 
dalam pernyataan SELECT</td>
	</tr>
	<tr>
		<td>MIN</td>
		<td>SELECT MIN(ColumnName)
    FROM TableName;</td>
		<td>Fungsi MIN digunakan untuk mengembalikan nilai minimum kolom.
</td>
	</tr>
	<tr>
		<td>MAX</td>
		<td>SELECT MAX(ColumnName)
    FROM TableName;
</td>
		<td>Fungsi MAX digunakan untuk mengembalikan nilai maksimum kolom.</td>
	</tr>
	<tbody>
</table>

<table>
	<caption>Fungsi Skalar</caption>
	<caption>Fungsi Skalar dalam TSQL digunakan untuk mengembalikan nilai tunggal dari nilai 
input yang diberikan. Berikut ini adalah beberapa fungsi skalar yang paling umum 
digunakan:
</caption>
	<thead>
	<tr>
		<th>Function</th>
		<th>Syntax</th>
		<th>Fungsi</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>LCASE</td>
		<td>SELECT LCASE(ColumnName)
FROM TableName;</td>
		<td>Fungsi LCASE digunakan untuk mengubah nilai kolom string menjadi karakter 
huruf kecil.</td>
	</tr>
	<tr>
		<td>UCASE</td>
		<td>SELECT UCASE(ColumnName)
FROM TableName;</td>
		<td>Fungsi UCASE digunakan untuk mengubah nilai kolom string menjadi karakter 
huruf besar</td>
	</tr>
	<tr>
		<td>LEN</td>
		<td>SELECT LENGTH(String) AS SampleColumn;</td>
		<td>Fungsi LEN digunakan untuk mengambil panjang string input</td>
	</tr>
	<tr>
		<td>MID</td>
		<td>SELECT MID(ColumnName, Start, Length)
FROM TableName;</td>
		<td>Fungsi MID digunakan untuk mengekstrak substring dari kolom yang memiliki 
tipe data string.</td>
	</tr>
	<tr>
		<td>ROUND</td>
		<td>SELECT ROUND(ColumnName, Decimals)
FROM TableName;
</td>
		<td>Fungsi ROUND digunakan untuk membulatkan nilai numerik ke bilangan bulat 
terdekat</td>
	</tr>
	<tbody>
</table>


### Resource 

* https://www.geeksforgeeks.org/sql-functions-aggregate-scalar-functions/
* https://www.edureka.co/blog/sql-functions
* https://www.w3schools.com/sql/sql_ref_sqlserver.asp
