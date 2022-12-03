## Tipe Numerik

<table>
	<caption>Tipe data numerik digunakan untuk menyimpan data numerik (angka). Karakteristik 
  utama dari tipe data numerik adalah suatu data yang memungkinkan untuk dikenai 
  operasi aritmatika seperti pertambahan, pengurangan, perkalian dan pembagian.</caption>
	<thead>
	<tr>
		<th>Tipe Data</th>
		<th>Deskripsi</th>
		<th>Kapasitas Penyimpanan</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>bit</td>
		<td>Bilangan integer yang bisa 0, 1, atau NULL</td>
		<td></td>
	</tr>
	<tr>
		<td>tinyint</td>
		<td>Memungkinkan seluruh angka dari 0 hingga 255</td>
		<td>1 byte</td>
	</tr>
	<tr>
		<td>smallint</td>
		<td>Memungkinkan seluruh angka antara -32.768 dan 32.767</td>
		<td>2 bytes</td>
	</tr>
	<tr>
		<td>Int</td>
		<td>Memungkinkan seluruh angka antara -9.223.372.036.854.775.808 dan 9.223.372.854.775.807</td>
		<td>4 bytes</td>
	</tr>
	<tr>
		<td>Real</td>
		<td>Data presisi angka floating dari -3.40E + 38 hingga 3.40E + 38</td>
		<td>4 bytes</td>
	</tr>
	<tbody>
</table>

## Tipe Date and Time

<table>
	<caption>Tipe data date dan time digunakan khusus untuk menyimpan data tanggal dan waktu.</caption>
	<thead>
	<tr>
		<th>Tipe Data</th>
		<th>Deskripsi</th>
		<th>Kapasitas Penyimpanan</th>
	</tr>
	</thead>
	<tbody>
  <tr>
		<td>datetime</td>
		<td>Dari January 1, 1753, ke December 31, 9999 dengan tingkat akurasi sekitar 3.33 milliseconds</td>
		<td>8 bytes</td>
	</tr>
  <tr>
		<td>datetime2</td>
		<td>Dari January 1, 0001 ke December 31, 9999 dengan tingkat akurasi sekitar 100 nanoseconds</td>
		<td>6-8 bytes</td>
	</tr>
  <tr>
		<td>date</td>
		<td>Menyimpan tipe data date. Dari January 1, 0001 ke December 31, 9999</td>
		<td>3 bytes</td>
	</tr>
  <tr>
	  <td>time</td>
		<td>Menyimpan tipe data time dengan tingkat akurasi sekitar 100 nanoseconds</td>
		<td>3-5 bytes</td>
	</tr>
  <tr>
	  <td>timestamp</td>
		<td>Menyimpan nomor unik yang diperbarui setiap kali baris dibuat atau diubah. Proses ini berdasarkan nilai waktu pada jam internal dan tidak sesuai dengan real-time.
  </td>
		<td></td>
	</tr>
  <tbody>
</table>

## Tipe String
<table>
	<caption>Tipe data string digunakan untuk menyimpan data string (text)..</caption>
	<thead>
	<tr>
		<th>Tipe Data</th>
		<th>Deskripsi</th>
		<th>Ukuran Maksimum</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>char(n)</td>
		<td>Panjang fix karakter non-Unicode </td>
		<td>8100 Karakter</td>
	</tr>
  <tr>
		<td>varchar(n)</td>
		<td>Lebar variable karakter string </td>
		<td>8000 Karakter</td>
	</tr>
  <tr>
		<td>varchar(max)</td>
		<td>Lebar variable karakter string </td>
		<td>1,073,741,824 karakter</td>
	</tr>
  <tr>
		<td>text</td>
		<td>Lebar variable karakter string </td>
		<td>2GB dari text data</td>
	</tr>
  <tr>
		<td>nchar</td>
		<td>Lebar Fix Unicode String </td>
		<td>4000 Characters</td>
	</tr>
  <tbody>
</table
