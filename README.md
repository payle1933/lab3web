~~~
Nama  :Maulana Hasanudin
kelas :TI.20.D.1
nim   : 312010106
~~~
# Membuat dokumen HTML dengan nama file lab3_list.html. Setelah itu buat struktur dasar HTML
~~~
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat List</h1>
 </header>
</body>
</html>
~~~

<img width="1070" alt="aa" src="https://user-images.githubusercontent.com/101716660/161121712-7da3a6c0-f342-441e-ac5e-b1ef9eec3acc.png">


## LANGKAH 2
### Membuat Daftar Pesanan
~~~
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
    </ol>
</section>
~~~

<img width="1070" alt="bb" src="https://user-images.githubusercontent.com/101716660/161121760-ffc37488-7caa-43ec-b206-74d8876f36d7.png">


## LANGKAH 3
### Membuat Daftar Unordered
~~~
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
    </ul>
   </section>
   ~~~
<img width="1070" alt="cc" src="https://user-images.githubusercontent.com/101716660/161121796-31b93350-129f-47e5-9860-01278e1fd9c9.png">


## LANGKAH 4
### Membuat Daftar Deskripsi
~~~
<section id="unorder-list">
    <h2>Description List</h2>
    <dl>
    <dt>Fakultas Teknik</dt>
    <dd>Teknik Industri</dd>
    <dd>Teknik Informatika</dd>
    <dd>Teknik Lingkungan</dd>
    <dt>Fakultas Ekonomi dan Bisnis</dt>
    <dd>Akuntansi</dd>
    <dd>Manajemen</dd>
    <dd>Bisnis Digital</dd>
    </dl>
</section>
~~~
<img width="1070" alt="dd" src="https://user-images.githubusercontent.com/101716660/161121835-bb5ce44c-c9f6-4ce3-826e-5432b2b32e43.png">


## LANGKAH 5
### Membuat dokumen HTML baru dengan nama file lab3_tabel.html. Setelah itu buat struktur dasar HTML
~~~
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat Table</h1>
 </header>
</body>
</html>
~~~

<img width="1070" alt="ff" src="https://user-images.githubusercontent.com/101716660/161123501-f4bb853c-2418-4f4a-a008-ee43dd8a8822.png">


## LANGKAH 6
### Membuat tabel dan mengatur margin tabel
~~~
<table border="1" cellpadding="4" cellspacing="0">
  <thead>
      <tr>
        <th>No.</th>
        <th>Fakultas</th>
        <th>Program Studi</th>
      </tr>
 </thead>
 <tbody>
    <tr>
       <td>1.</td>
       <td>Teknik</td>
       <td>Teknik Informatika</td>
    </tr>
    <tr>
       <td>2.</td>
       <td>Teknik</td>
       <td>Teknik Industri</td>
    </tr>
    <tr>
       <td>3.</td>
       <td>Teknik</td>
       <td>Teknik Lingkungan</td>
    </tr>
 </tbody>
</table>
~~~
<img width="1070" alt="ff" src="https://user-images.githubusercontent.com/101716660/161122952-c8ae0e38-3dd7-4096-80e9-b654464cc057.png">



## LANGKAH 7
### Menggabungkan Sel Data
~~~
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>No.</th>
        <th>Fakultas</th>
        <th>Program Studi</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>1.</td>
        <td rowspan="3">Teknik</td>
        <td>Teknik Informatika</td>
      </tr>
      <tr>
        <td>2.</td>
        <td>Teknik Industri</td>
      </tr>
      <tr>
        <td>3.</td>
        <td>Teknik Lingkungan</td>
      </tr>
    </tbody>
   </table>
~~~
<img width="1070" alt="ff" src="https://user-images.githubusercontent.com/101716660/161123135-cb2635ae-191b-48dc-9f9a-38eb936b5b73.png">



## LANGKAH 8
### Membuat dokumen HTML baru dengan nama file lab3_form.html dan Buat Tabel
~~~
<form action="proses.php" method="post">
         <fieldset>
         <legend>Data Pelanggan</legend>
         <p>
         <label for="nama">Nama</label>
         <input type="text" id="nama" name="nama">
         </p>
         <p>
         <label for="alamat">Alamat</label>
        <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
         </p>
        <p>
        <label>Jenis Kelamin</label>
        <input id="jk_l" type="radio" name="kelamin" value="L" /><label
        for="jk_l">Laki-laki</label>
         <input id="jk_p" type="radio" name="kelamin" value="P" /><label
         for="jk_p">Perempuan</label>
        </p>
        <p><input type="submit" value="Login"></p>
        </fieldset>
    </form>
~~~
<img width="1070" alt="gg" src="https://user-images.githubusercontent.com/101716660/161123244-83321253-a0ff-450b-927b-c290d163ea15.png">



## LANGKAH 9
### menambahkan style pada form agar tampilan lebih menarik menggunakan CSS
~~~    
    <style>
        form p > label {
        display: inline-block;
        width: 100px;
        }
        form input[type="text"], form textarea {
        border: 1px solid #197a43;
        }
        form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
        }
        </style>
~~~
<img width="1070" alt="hh" src="https://user-images.githubusercontent.com/101716660/161123297-ed59a2ae-444d-4312-8ea3-e5a2b3814507.png">



# TUGAS
## Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
### Membuat Dropdown Menu
~~~
#CSS
	<style type="text/css">
	html,body{
		padding: 0;
		margin:0;
		font-family: sans-serif;
	}
 
	.menu{
		background-color: #ff7b00;
	}
 
	.menu ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		overflow: hidden;
	}
 
	.menu > ul > li {
		float: left;
	}
 
	
	.menu li a {
		display: inline-block;
		color: white;
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
	}
 
	.menu li a:hover{
		background-color: #ff7b00;
	}
 
	li.dropdown {
		display: inline-block;
	}
 
	.dropdown:hover .isi-dropdown {
		display: block;
	}
 
	.isi-dropdown a:hover {
		color: #fff !important;
	}
 
	.isi-dropdown {
		position: absolute;
		display: none;
		box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
		z-index: 1;
		background-color: #f9f9f9;
	}
 
	.isi-dropdown a {
		color: #3c3c3c !important;
	}
 
	.isi-dropdown a:hover {
		color: #232323 !important;
		background: #f3f3f3 !important;
	}
</style>
 
#Dropdown Menu 
<header class="header">
	<div class="menu">
 
		<ul>
			<li><a href="lab3_tugas.html">Home</a></li>
			<li class="dropdown"><a href="#">DROPDOWN MENU LAB 3 WEB</a>
				<ul class="isi-dropdown">
					<li><a href="lab3_list.html">LAB 3 LIST</a></li>
					<li><a href="lab3_tabel.html">LAB 3 TABEL</a></li>
					<li><a href="lab3_form.html">LAB 3 FORM</a></li>
				</ul>
			</li>
		</ul>
 
	</div>
</header>
~~~
<img width="1070" alt="ii1" src="https://user-images.githubusercontent.com/101716660/161123346-d698abb8-3ae3-44c8-b05f-8f4df536198e.png">


## Membuat Listbox dengan banyak pilihan
~~~
<h4>CONTOH LISTBOX</h4>
<form action="proses.php" method="get">
    <p>Agama
    <select name='agama' multiple='multiple'>
      <option value='islam'>Islam</option>
      <option value='kristen' selected='selected'>Kristen</option>
      <option value='katholik'>Katholik</option>
      <option value='hindu'>Hindu</option>
      <option value='kristen'>Budha</option>
    </select>
    </p>
    <input type='submit' name='tombol' value='kirim' />
 ~~~
 <img width="1070" alt="ii2" src="https://user-images.githubusercontent.com/101716660/161123376-df5c5ca2-7529-40c6-a717-ac1bf26b8326.png">
