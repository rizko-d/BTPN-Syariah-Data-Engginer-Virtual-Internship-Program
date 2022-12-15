## Date, String, Numeric pada T-SQL 

<table>
	<caption>Date</caption>
	<thead>
	<tr>
		<th>Operator</th>
		<th>Fungsi</th>
		<th>Syntax</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>DATEADD</td>
		<td>Fungsi DATEADD menambahkan interval waktu/tanggal ke tanggal dan 
    kemudian mengembalikan tanggal.</td>
		<td>DATEADD(interval, number, date)</td>
	</tr>
	<tr>
		<td>DATEDIFF</td>
		<td>Fungsi DATEDIFF mengembalikan perbedaan antara dua tanggal.</td>
		<td>DATEDIFF(interval, date1, date2)</td>
	</tr>
	<tr>
		<td>GETDATE</td>
		<td>Fungsi GETDATE mengembalikan tanggal dan waktu sistem database 
    saat ini, dalam format 'YYYY-MM-DD hh:mm:ss.mmm'.</td>
		<td>GETDATE()</td>
	</tr>
	<tr>
		<td>DATENAME</td>
		<td>Fungsi DATENAME mengembalikan bagian tertentu dari tanggal. Fungsi 
    ini mengembalikan hasil sebagai nilai string.</td>
		<td>DATENAME(interval, date)</td>
	</tr>
	<tr>
		<td>DATEPART</td>
		<td>Fungsi DATEPART mengembalikan bagian tertentu dari tanggal.Fungsi 
    ini mengembalikan hasil sebagai nilai integer.</td>
		<td>DATEPART(interval, date)
    </td>
	</tr>
	<tbody>
</table>

<table>
	<caption>String</caption>
	<thead>
	<tr>
		<th>Operator</th>
		<th>Fungsi</th>
		<th>Syntax</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>ASCII</td>
		<td>Fungsi ASCII mengembalikan nilai ASCII untuk karakter tertentu.</td>
		<td>ASCII(character)</td>
	</tr>
	<tr>
		<td>CHAR</td>
		<td>Fungsi CHAR mengembalikan karakter berdasarkan kode ASCII</td>
		<td>CHAR(code)</td>
	</tr>
	<tr>
		<td>CONCAT</td>
		<td>Fungsi CONCAT menambahkan dua atau lebih string bersama-sama.
    </td>
		<td>CONCAT(string1, string2, ...., string_n)
    </td>
	</tr>
	<tr>
		<td>LOWER</td>
		<td>Fungsi LOWER mengonversi string menjadi huruf kecil.</td>
		<td>LOWER(text)</td>
	</tr>
	<tr>
		<td>SUBSTRING</td>
		<td>Fungsi SUBSTRING mengekstrak beberapa karakter dari sebuah 
    string</td>
		<td>SUBSTRING(string, start, length)</td>
	</tr>
	<tbody>
</table>

<table>
	<caption>Numeric</caption>
	<thead>
	<tr>
		<th>Operator</th>
		<th>Fungsi</th>
		<th>Syntax</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>AVG</td>
		<td>Fungsi AVG digunakan untuk mengembalikan nilai rata-rata
    </td>
		<td>SELECT AVG(ColumnName)
    FROM TableName;</td>
	</tr>
	<tr>
		<td>MIN</td>
		<td>Fungsi MIN digunakan untuk mengembalikan nilai minimum kolom.</td>
		<td>SELECT MIN(ColumnName)
    FROM TableName;
  </td>
	</tr>
	<tr>
		<td>MAX</td>
		<td>Fungsi MAX digunakan untuk mengembalikan nilai maksimum kolom.</td>
		<td>SELECT MAX(ColumnName)
    FROM TableName;
  </td>
	</tr>
	<tr>
		<td>ABS</td>
		<td>Fungsi ABS mengembalikan nilai absolut dari suatu angka</td>
		<td>ABS(number)</td>
	</tr>
	<tr>
		<td>ROUND</td>
		<td>Fungsi ROUND digunakan untuk membulatkan angka ke sejumlah 
    tempat desimal yang ditentukan.</td>
		<td>ROUND(number, decimals, operation)</td>
	</tr>
	<tbody>
</table>
