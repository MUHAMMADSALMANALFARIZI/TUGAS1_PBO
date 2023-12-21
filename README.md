# TUGAS1_PBO
Tugas pertama, mata kuliah Pemrograman Berorientasi Objek semester 3

- Nama     : Muhammad Salman Alfarizi
- NIM/NPM  : G1F022047
- Prodi    : Sistem Infromasi (A)

## SOAL
1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:
 (https://github.com/randiijulian/randiijulian/assets/81604461/e32b6d92-7e3a-4323-a0e3-711009112c8e)
2. Buatlah program bebas, dengan menerapkan if else pada:
   a. For Loops
   b. While Loops
3. Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for

## PEMBAHASAN DAN PENJELASAN
#### Jawaban Nomor 1

   <img width="594" alt="TUGAS-1-NOMOR-1" src="https://github.com/SalmanAlfarizi28/TUGAS1_PBO/assets/150643024/01219cad-7c38-410d-a494-34ee391d2c09">
   
###### Penjelasan Kode

a)	nama = "Muhammad Salman Alfarizi": Mendefinisikan variabel nama dan memberikannya nilai "Muhammad Salman Alfarizi".

b)	for angka in range(1, 101):: Memulai loop for yang akan mengiterasi melalui rentang angka dari 1 hingga 100.

c)	if angka % 10 == 0:: Memeriksa apakah angka adalah kelipatan 10 dengan menggunakan operasi modulo (%). Jika benar, masuk ke dalam blok if.

d)	for kelipatan10 in range(3):: Memulai loop for dalam blok if yang akan mencetak nama sebanyak tiga kali jika angka adalah kelipatan 10.

e)	print(nama): Mencetak nilai dari variabel nama (Muhammad Salman Alfarizi) sebanyak tiga kali karena ini berada di dalam loop for kelipatan 10.

f)	else:: Jika angka bukan kelipatan 10, masuk ke blok else.

g)	print(angka): Mencetak nilai angka jika angka tidak merupakan kelipatan 10.

###### Penjelasan Luaran(Output)

Dengan demikian, program ini akan mencetak angka dari 1 hingga 100, dan setiap kali mencapai kelipatan 10, akan mencetak nama ("Muhammad Salman Alfarizi") sebanyak tiga kali.

#### Jawaban Nomor 2

   #A)FOR LOOPS
   
   <img width="456" alt="TUGAS-1-NOMOR-2a" src="https://github.com/SalmanAlfarizi28/TUGAS1_PBO/assets/150643024/a0af4e9d-5e5f-43d4-af90-96345b5d210b">
   
###### Penjelasan Kode

a)	batas_bawah = 18: Mendefinisikan batas bawah rentang suhu dalam derajat Celsius.

b)	batas_atas = 32: Mendefinisikan batas atas rentang suhu dalam derajat Celsius.

c)	for suhu in range(batas_bawah, batas_atas + 1):: Memulai loop for yang akan mengiterasi melalui rentang suhu dari batas_bawah hingga batas_atas (inklusif).

d)	if suhu >= 30:: Memeriksa apakah suhu lebih besar atau sama dengan 30. Jika benar, masuk ke dalam blok if.

e)	status = "panas": Menginisialisasi variabel status dengan nilai "panas" jika suhu lebih besar atau sama dengan 30.

f)	elif 20 <= suhu < 30:: Jika kondisi pada baris 4 salah, maka memeriksa apakah suhu di antara 20 hingga 30 (tidak termasuk 30). Jika benar, masuk ke dalam blok elif (else if).

g)	status = "nyaman": Mengubah nilai variabel status menjadi "nyaman" jika kondisi pada baris 6 benar.

h)	else:: Jika kedua kondisi sebelumnya salah, masuk ke dalam blok else.

i)	status = "dingin": Mengubah nilai variabel status menjadi "dingin" jika tidak memenuhi kondisi pada blok if atau elif.

j)	print(f"Suhu {suhu} derajat Celsius diklasifikasikan sebagai suhu {status}."): Mencetak hasil klasifikasi suhu berdasarkan nilai status untuk setiap iterasi dalam loop for.

###### Penjelasan Luaran(Output)

Pada akhirnya, program ini mencetak klasifikasi suhu untuk setiap nilai suhu dalam rentang yang ditentukan. Dimana program ini telah menerapkan if else pada perulangan For

  #B)WHILE LOOPS
  
  <img width="542" alt="TUGAS-1-NOMOR-2b" src="https://github.com/SalmanAlfarizi28/TUGAS1_PBO/assets/150643024/f9afe452-1439-40f7-a566-c67f1d1b0c66">

###### Penjelasan Kode

a)	suhu = 18: Mendefinisikan nilai awal untuk variabel suhu.

b)	batas_atas = 32: Mendefinisikan batas atas rentang suhu dalam derajat Celsius.

c)	while suhu <= batas_atas:: Memulai loop while yang akan terus berjalan selama nilai suhu kurang dari atau sama dengan batas_atas.

d)	if suhu >= 30:: Memeriksa apakah nilai suhu lebih besar atau sama dengan 30. Jika benar, masuk ke dalam blok if.

e)	status = "panas": Menginisialisasi variabel status dengan nilai "panas" jika suhu lebih besar atau sama dengan 30.

f)	elif 20 <= suhu < 30:: Jika kondisi pada baris 4 salah, maka memeriksa apakah suhu di antara 20 hingga 30 (tidak termasuk 30). Jika benar, masuk ke dalam blok elif (else 
if).

g)	status = "nyaman": Mengubah nilai variabel status menjadi "nyaman" jika kondisi pada baris 6 benar.

h)	else:: Jika kedua kondisi sebelumnya salah, masuk ke dalam blok else.

i)	status = "dingin": Mengubah nilai variabel status menjadi "dingin" jika tidak memenuhi kondisi pada blok if atau elif.

j)	print(f"Suhu {suhu} derajat Celsius diklasifikasikan sebagai suhu {status}."): Mencetak hasil klasifikasi suhu berdasarkan nilai status untuk setiap iterasi dalam loop while.

k)	suhu += 1: Menambahkan nilai suhu sebesar 1 pada setiap iterasi untuk mencegah perulangan tanpa batas.

###### Penjelasan Luaran(Output)

Dengan demikian, program ini mencetak klasifikasi suhu untuk setiap nilai suhu dalam rentang yang ditentukan menggunakan loop while. Sama seperti perulangan di atas program ini telah menerapkan if else tetapi pada pada perulangan While.

#### Jawaban Nomor 3

   <img width="569" alt="TUGAS-1-NOMOR-3" src="https://github.com/SalmanAlfarizi28/TUGAS1_PBO/assets/150643024/7a96e852-2e1a-421e-82be-f354e68fa882">

###### Penjelasan Kode

a)	penyanyi_favorit = ["Adele", "Ed Sheeran", "Taylor Swift", "Beyonce", "Bruno Mars"]: Mendefinisikan list penyanyi_favorit yang berisi nama-nama penyanyi favorit (ARRAY).

b)	for penyanyi in penyanyi_favorit:: Memulai loop for yang akan mengiterasi melalui setiap elemen dalam list penyanyi_favorit. Pada setiap iterasi, nilai dari elemen tersebut disimpan dalam variabel penyanyi.

c)	if penyanyi == "0":: Memeriksa apakah nilai penyanyi adalah string "0". Jika benar, masuk ke dalam blok if.

d)	aksi = "menyanyikan lagu-lagu penuh emosi.": Jika kondisi pada baris 3 benar, variabel aksi diinisialisasi dengan string yang menyatakan aksi yang sesuai dengan penyanyi tersebut.

e)	elif penyanyi == "1":: Melanjutkan untuk memeriksa kondisi berikutnya. Jika nilai penyanyi adalah string "1", masuk ke dalam blok elif.

f)	aksi = "menulis dan menyanyikan lagu-lagu romantis.": Jika kondisi pada baris 5 benar, variabel aksi diinisialisasi dengan string yang sesuai.

g)	Langkah-langkah serupa diulangi untuk setiap penyanyi dan aksi yang sesuai.

h)	else:: Jika tidak ada kondisi sebelumnya yang benar, masuk ke dalam blok else.

i)	aksi = "membuat karya musik yang unik dan menginspirasi.": Jika kondisi pada baris 7, 5, 3, atau 1 tidak benar, variabel aksi diinisialisasi dengan string yang sesuai dengan kondisi terakhir.

j)	print(f"{penyanyi} dikenal karena {aksi}"): Mencetak hasil klasifikasi untuk setiap penyanyi, termasuk nama penyanyi dan aksi yang sesuai dengan kondisi yang dipenuhi.

###### Penjelasan Luaran(Output)

Luaran yang dihasilkan dari program ini adalah perulangan yang dilakukan yang mengambil data penyanyi dari variabel array dengan nama penyanyi_favorit, dan menyesuaikan aksinya dengan kondisi percabangan if else if. Saya menggunakan kondisi pada percabangannya menggunakan nomor index dari array dimana dimulai dari 0. dari kode dapat kita ketahui bahwa data dalam array dengan index 0 adalah Adele dan seterusnya. Sehingga luaran yang dihasilkan akan menyesuaikan dengan kondisi yang memenuhi untuk menyesuaikan nama penyanyi dan aksinya.
