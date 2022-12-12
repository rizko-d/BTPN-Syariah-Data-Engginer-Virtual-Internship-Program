## T-SQL Filter, Aggregate, and Duplicate

<table>
	<caption>Filter</caption>
  <caption>Filter digunakan untuk melakukan subset item data dari database Beberapa 
  filter yang sering digunakan :</caption>
	<thead>
	<tr>
		<th>Operator</th>
		<th>Syntax</th>
		<th>Fungsi</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>Where</td>
		<td>SELECT kolom1, kolom2, … FROM nama_tabel WHERE kondisi</td>
		<td>WHERE merupakan perintah yang di gunakan untuk mem-filter hasil 
    SELECT dengan mengekstrak record yang memenuhi persyaratan 
    tertentu.</td>
	</tr>
	<tr>
		<td>AND, OR, NOT</td>
		<td>SELECT kolom1, kolom2, … FROM nama_tabel WHERE kondisi1 AND 
    kondisi2 AND kondisi3; <br>
    SELECT kolom1, kolom2, … FROM nama_tabel WHERE kondisi1 OR 
    kondisi2 OR kondisi3 …;</td>
		<td>Operator AND, OR dan NOT merupakan perintah yang biasanya di 
    kombinasikan dengan perintah WHERE. Ketiganya di gunakan untuk 
    mem-filter record berdasarkan suatu kondisi, operator AND akan 
    menampilkan record apabila semua kondisi bernilai TRUE, operator OR 
    akan menampilkan record apabila salah satu kondisi bernilai TRUE, 
    sedangkan operator NOT akan menampilkan record apabila semua 
    kondisi bernilai FALSE</td>
	</tr>
	<tr>
		<td>Between;</td>
		<td>SELECT column_name(s)
    FROM table_name
    WHERE column_name BETWEEN value1 AND value2;;</td>
		<td>Operator BETWEEN memilih nilai dalam rentang tertentu. Nilai dapat 
    berupa angka, teks, atau tanggal. Operator BETWEEN bersifat inklusif, 
    nilai awal dan akhir disertakan</td>
	</tr>
	</tbody>
</table>

<br>

<table>
	<caption>Aggregate</caption>
  <caption>Agregat dalam TSQL melakukan perhitungan pada sekelompok nilai dan kemudian 
  mengembalikan satu nilai. Berikut ini adalah beberapa fungsi agregat yang paling 
  umum digunakan</caption>
	<thead>
	<tr>
		<th>Operator</th>
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
    FROM TableName;</td>
		<td>Fungsi AVG digunakan untuk mengembalikan nilai rata-rata</td>
	</tr>
	<tr>
		<td>Count</td>
		<td>SELECT COUNT(ColumnName)
    FROM TableName;</td>
		<td>Fungsi COUNT digunakan untuk menghitung jumlah baris yang 
    dikembalikan dalam pernyataan SELECT</td>
	</tr>
	<tr>
		<td>MIN</td>
		<td>SELECT MIN(ColumnName)
    FROM TableName;
    </td>
		<td>Fungsi MIN digunakan untuk mengembalikan nilai minimum kolom.</td>
	</tr>
	<tr>
		<td>MAX</td>
		<td>SELECT MAX(ColumnName)
    FROM TableName;</td>
		<td>Fungsi MAX digunakan untuk mengembalikan nilai maksimum kolom.</td>
	</tr>
	<tbody>
</table>

<br>

<table>
	<caption>Duplicat</caption>
  <caption>Duplicate dalam TSQL merupakan terdapat dua atau lebih data yang sama. Kita dapat 
  menghapus duplicate dengan menggunakan beberapa perintah berikut :</caption>
	<thead>
	<tr>
		<th>Operator</th>
		<th>Syntak</th>
		<th>Fungsi</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>SELECT DISTINCT</td>
		<td>SELECT DISTINCT column1, column2, ...
    FROM table_name</td>
		<td>Pernyataan SELECT DISTINCT digunakan untuk mengembalikan hanya 
    nilai yang berbeda (berbeda).;</td>
	</tr>
	<tr>
		<td>COUNT</td>
		<td>SELECT COUNT(column_name)
    FROM table_name;
    </td>
		<td>Fungsi COUNT mengembalikan jumlah baris yang cocok dengan kriteria 
    yang ditentukan.
    </td>
	</tr>
	<tr>
		<td>GROUP BY</td>
		<td>SELECT column_name(s) <br>
    FROM table_name <br>
    WHERE condition <br>
    GROUP BY column_name(s) <br>
    ORDER BY column_name(s);
</td>
		<td>Pernyataan GROUP BY mengelompokkan baris yang memiliki nilai yang 
    sama ke dalam baris ringkasan, seperti "temukan jumlah pelanggan di 
    setiap negara". Pernyataan GROUP BY sering digunakan dengan fungsi 
    agregat (COUNT(), MAX(), MIN(), SUM(), AVG()) untuk mengelompokkan 
    kumpulan hasil menurut satu atau beberapa kolom.</td>
	</tr>
	</tbody>
</table>
