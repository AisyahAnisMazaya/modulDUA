*2A ( NOMOR 1 )*
Program Swap String
Program ini digunakan untuk menukar nilai dari tiga variabel string. Pertama, program akan meminta input dari pengguna untuk mengisi nilai dari variabel 'satu', 'dua', dan 'tiga'. Kemudian, program akan menampilkan nilai awal dari ketiga variabel tersebut.
Setelah itu, program akan melakukan swap nilai dari ketiga variabel tersebut menggunakan variabel 'temp' sebagai penyimpanan sementara. Nilai dari 'satu' akan disimpan di 'temp', kemudian nilai dari 'dua' akan disimpan di 'satu', nilai dari 'tiga ' akan disimpan di'dua', dan akhirnya nilai dari 'temp' akan disimpan di'tiga'.
Terakhir, program akan menampilkan nilai akhir dari ketiga variabel tersebut setelah proses swap selesai.

*2A ( NOMOR 2 )*
Program Cek Tahun Kabisat
Program ini digunakan untuk menentukan apakah suatu tahun adalah tahun kabisat atau tidak. Pertama, program akan meminta input dari pengguna untuk mengisi nilai tahun.
Kemudian, program akan melakukan pengecekan apakah tahun tersebut adalah tahun kabisat atau tidak menggunakan dua kondisi:
Jika tahun habis dibagi 400, maka tahun tersebut adalah tahun kabisat.
Jika tahun habis dibagi 4 tetapi tidak habis dibagi 100, maka tahun tersebut juga adalah tahun kabisat.
Jika salah satu kondisi di atas terpenuhi, maka variabel'kabisat' akan di-set menjadi 'true', yang berarti tahun tersebut adalah tahun kabisat. Jika tidak, maka 'kabisat' akan di-set menjadi 'false'.
Terakhir, program akan menampilkan hasil pengecekan apakah tahun tersebut adalah tahun kabisat atau tidak menggunakan perintah 'fmt.Printf'.

*2A ( NOMOR 3 )*
Program Menghitung Volume dan Luas Kulit Bola
Program ini digunakan untuk menghitung volume dan luas kulit bola berdasarkan jejari bola yang diinput oleh pengguna. Pertama, program akan meminta input dari pengguna untuk mengisi nilai jejari bola.
Kemudian, program akan menghitung volume bola menggunakan rumus '(4.0 / 3.0) * math.Pi * math.Pow(jariJari, 3)', dan menghitung luas kulit bola menggunakan rumus '4 * math.Pi * math.Pow(jariJari, 2)'.
Terakhir, program akan menampilkan hasil perhitungan volume dan luas kulit bola dengan format yang telah ditentukan, yaitu 'Bola dengan jejari %.0f memiliki volume %.4f dan luas kulit %.4f'.

*2A ( NOMOR 4 )
Program Konversi Suhu
Program ini digunakan untuk mengkonversi suhu dari derajat Celcius ke derajat Fahrenheit, Reamur, dan Kelvin. Pertama, program akan meminta input dari pengguna untuk mengisi nilai suhu dalam derajat Celcius.
Kemudian, program akan melakukan konversi suhu menggunakan rumus-rumus berikut:
Konversi ke derajat Fahrenheit: '(celsius * 9 / 5) + 32'
Konversi ke derajat Reamur: 'celsius * 4 / 5'
Konversi ke derajat Kelvin: 'celsius + 273.15'
Terakhir, program akan menampilkan hasil konversi suhu dalam format yang telah ditentukan, yaitu dengan dua angka di belakang koma.
Program ini dapat membantu pengguna untuk mengkonversi suhu dengan mudah dan akurat.

*2A ( NOMOR 5 )
Program Membaca dan Menampilkan Nilai Integer dan Karakter
Program ini digunakan untuk membaca nilai integer dan karakter dari input pengguna dan menampilkan hasilnya. Pertama, program akan meminta input dari pengguna untuk mengisi 5 nilai integer dan 3 karakter.
Kemudian, program akan membaca nilai integer dan karakter menggunakan fungsi 'fmt.Scanln'. Nilai integer akan disimpan dalam array 'numbers' dan karakter akan disimpan dalam array 'chars'.
Setelah itu, program akan menampilkan ASCII representations dari nilai integer menggunakan perulangan 'for' dan fungsi 'fmt.Printf'. Kemudian, program akan menampilkan karakter yang telah dibaca menggunakan perulangan 'for' dan fungsi 'fmt.Printf'.
Program ini dapat membantu pengguna untuk membaca dan menampilkan nilai integer dan karakter dengan mudah dan akurat.


*2B ( NOMOR 1 )
Program Menguji Kombinasi Warna
Program ini digunakan untuk menguji kombinasi warna yang diinput oleh pengguna. Pertama, program akan meminta input dari pengguna untuk mengisi jumlah percobaan yang ingin dilakukan.
Kemudian, program akan melakukan perulangan sebanyak jumlah percobaan yang diinput. Pada setiap percobaan, program akan meminta input dari pengguna untuk mengisi 4 warna (merah, kuning, hijau, dan ungu).
Program akan memeriksa apakah kombinasi warna yang diinput sesuai dengan kondisi yang telah ditentukan, yaitu "merah", "kuning", "hijau", dan "ungu" dalam urutan yang tepat. Jika kombinasi warna sesuai, program akan menampilkan "BERHASIL: true", jika tidak sesuai, program akan menampilkan "BERHASIL: false".
Program ini dapat membantu pengguna untuk menguji kombinasi warna dengan mudah dan akurat.

*2B ( NOMOR 2 )
Program Mengumpulkan Nama Bunga
Program ini digunakan untuk mengumpulkan nama bunga yang diinput oleh pengguna dan menampilkan hasilnya. Pertama, program akan meminta input dari pengguna untuk mengisi nama bunga.
Kemudian, program akan melakukan perulangan secara terus-menerus sampai pengguna menginput "SELESAI" untuk berhenti. Pada setiap iterasi, program akan meminta input dari pengguna untuk mengisi nama bunga.
Nama bunga yang diinput akan disimpan dalam variabel 'pita' dan jumlah bunga akan dihitung menggunakan variabel 'bungaCount'. Jika pengguna menginput "SELESAI", program akan berhenti dan menampilkan isi 'pita' dan jumlah 'bungaCount'.
Dengan demikian, program ini dapat membantu pengguna untuk mengumpulkan nama bunga dengan mudah dan akurat.
Program ini sangat berguna untuk mengumpulkan data nama bunga dan menampilkan hasilnya dalam format yang rapi dan akurat.

*2B ( NOMOR 3 )
Program Menguji Keseimbangan Berat Belanjaan
Program ini digunakan untuk menguji keseimbangan berat belanjaan di kedua kantong sepeda motor Pak Andi. Pertama, program akan meminta input dari pengguna untuk mengisi berat belanjaan di kedua kantong.
Kemudian, program akan melakukan perulangan secara terus-menerus sampai pengguna menginput berat belanjaan yang tidak valid (total berat lebih dari 150 atau berat salah satu kantong kurang dari 0). Jika berat belanjaan tidak valid, program akan berhenti memproses.
Jika berat belanjaan valid, program akan memeriksa apakah perbedaan berat antara kedua kantong lebih dari atau sama dengan 9. Jika perbedaan berat lebih dari atau sama dengan 9, program akan menampilkan "Sepeda motor pak Andi akan oleng: true", jika tidak, program akan menampilkan "Sepeda motor pak Andi akan oleng: false".
Dengan demikian, program ini dapat membantu pengguna untuk menguji keseimbangan berat belanjaan di sepeda motor Pak Andi dengan mudah dan akurat.
Program ini sangat berguna untuk menguji keseimbangan berat belanjaan di sepeda motor Pak Andi dan menampilkan hasilnya dalam format yang rapi dan akurat.

*2B ( NOMOR 4 )
Program Menghitung Akar 2
Program ini digunakan untuk menghitung nilai akar 2 menggunakan rumus tertentu. Pertama, program akan meminta input dari pengguna untuk mengisi nilai K.
Kemudian, program akan memanggil fungsi 'hitungAkar2' untuk menghitung nilai akar 2 berdasarkan nilai K yang diinput. Fungsi 'hitungAkar2' akan menghitung nilai akar 2 menggunakan rumus yang diketahui, yaitu:
'akar2 = sqrt((4*i + 2)^2 / ((4*i + 1) * (4*i + 3)))'
dimana 'i' adalah variabel yang bernilai dari 0 sampai K.
Setelah menghitung nilai akar 2, program akan menampilkan hasilnya dalam format yang rapi dan akurat.
Program ini sangat berguna untuk menghitung nilai akar 2 dengan mudah dan akurat.

*2C ( NOMOR 1 )
Program Menghitung Biaya Pengiriman Parsel
Program ini digunakan untuk menghitung biaya pengiriman parsel berdasarkan berat parsel yang diinput oleh pengguna. Pertama, program akan meminta input dari pengguna untuk mengisi berat parsel dalam gram.
Kemudian, program akan menghitung berat parsel dalam kilogram (kg) dan sisanya dalam gram. Berat dalam kg akan digunakan untuk menghitung biaya dasar, sedangkan sisanya akan digunakan untuk menghitung biaya tambahan.
Biaya dasar dihitung dengan mengalikan berat dalam kg dengan 10.000. Biaya tambahan dihitung dengan mengalikan sisanya dengan 5 jika sisanya lebih dari atau sama dengan 500 gram, atau dengan 15 jika sisanya kurang dari 500 gram.
Jika berat parsel lebih dari 10.000 gram, maka total biaya akan dihitung dengan menjumlahkan biaya dasar dan biaya tambahan. Jika tidak, maka total biaya akan sama dengan biaya dasar.
Akhirnya, program akan menampilkan hasil perhitungan biaya pengiriman parsel, termasuk detail berat, detail biaya, dan total biaya.
Program ini sangat berguna untuk menghitung biaya pengiriman parsel dengan mudah dan akurat.

*2C ( NOMOR 2a )
Program Mengkonversi Nilai Akhir Mata Kuliah
Program ini digunakan untuk mengkonversi nilai akhir mata kuliah menjadi nilai huruf (NMK) berdasarkan rentang nilai yang diinput oleh pengguna. Pertama, program akan meminta input dari pengguna untuk mengisi nilai akhir mata kuliah.
Kemudian, program akan melakukan pengecekan nilai akhir mata kuliah dan mengkonversinya menjadi nilai huruf (NMK) berdasarkan rentang nilai sebagai berikut:
Nilai 80 ke atas: A
Nilai 72,5 ke atas: AB
Nilai 65 ke atas: B
Nilai 57,5 ke atas: BC
Nilai 50 ke atas: ... (program belum selesai, silakan lengkapi kondisi lainnya)
Setelah mengkonversi nilai akhir mata kuliah menjadi nilai huruf, program akan menampilkan hasilnya.
Namun, perlu diingat bahwa program ini belum selesai dan masih memerlukan kondisi lainnya untuk menentukan nilai huruf yang tepat. Oleh karena itu, program ini masih perlu dilengkapi dan diperbaiki agar dapat berfungsi dengan baik.
Program ini sangat berguna untuk mengkonversi nilai akhir mata kuliah menjadi nilai huruf dengan mudah dan akurat, namun perlu dilengkapi dan diperbaiki terlebih dahulu.

*2C ( NOMOR 2b )
Berikut kesalahan program tersebut
- Tipe Data: Variable ‘nmk’ dideklarasikan sebagai ‘string’ namun tidak diberi nilai. Program mencoba mencetak ‘nmk’ yang menyebabkan error karena variable ‘nmk’ tidak terdefinisi.
- Logika if-else: Program memiliki celah pada kondisi batas antara nilai-nilai. Misalkan, jika ‘nam’ adalah 80.1, maka program tidak akan menjalankan blok if-else manapun dan ‘nmk’ tetap tidak terdefinisi.
- Tidak ada output untuk ‘nmk’ : Program tidak pernah memberikan nilai pada ‘nmk’ sehingga output yang dicetak akan kosong.

  Program Mengkonversi Nilai Akhir Mata Kuliah
Program ini digunakan untuk mengkonversi nilai akhir mata kuliah menjadi nilai huruf (NMK) berdasarkan rentang nilai yang diinput oleh pengguna. Pertama, program akan meminta input dari pengguna untuk mengisi nilai akhir mata kuliah.
Kemudian, program akan melakukan pengecekan nilai akhir mata kuliah dan mengkonversinya menjadi nilai huruf (NMK) berdasarkan rentang nilai sebagai berikut:
Nilai 80 ke atas: A
Nilai 72,5 ke atas: AB
Nilai 65 ke atas: B
Nilai 57,5 ke atas: BC
Nilai 50 ke atas: C
Nilai 40 ke atas: D
Nilai kurang dari 40: E
Setelah mengkonversi nilai akhir mata kuliah menjadi nilai huruf, program akan menampilkan hasilnya.
Program ini sangat berguna untuk mengkonversi nilai akhir mata kuliah menjadi nilai huruf dengan mudah dan akurat.
Program ini telah lengkap dan siap digunakan untuk mengkonversi nilai akhir mata kuliah menjadi nilai huruf dengan mudah dan akurat.

*2C ( NOMOR 2c )
Program Mengkonversi Nilai Akhir Mata Kuliah
Program ini digunakan untuk mengkonversi nilai akhir mata kuliah menjadi nilai huruf (NMK) berdasarkan rentang nilai yang diinput oleh pengguna. Pertama, program akan meminta input dari pengguna untuk mengisi nilai akhir mata kuliah.
Kemudian, program akan melakukan pengecekan nilai akhir mata kuliah dan mengkonversinya menjadi nilai huruf (NMK) berdasarkan rentang nilai sebagai berikut:
Nilai lebih dari 80: A
Nilai lebih dari 72,5: AB
Nilai lebih dari 65: B
Nilai lebih dari 57,5: BC
Nilai lebih dari 50: C
Nilai lebih dari 40: D
Nilai kurang dari atau sama dengan 40: E
Namun, perlu diingat bahwa kondisi pada program ini menggunakan operator "lebih dari" (>), bukan "lebih dari atau sama dengan" (>=). Ini berarti bahwa nilai yang sama dengan batas atas tidak akan termasuk dalam kategori yang sesuai.
Setelah mengkonversi nilai akhir mata kuliah menjadi nilai huruf, program akan menampilkan hasilnya.
Program ini telah lengkap dan siap digunakan untuk mengkonversi nilai akhir mata kuliah menjadi nilai huruf dengan mudah dan akurat, namun perlu diingat bahwa kondisi pada program ini menggunakan operator "lebih dari" (>), bukan "lebih dari atau sama dengan" (>=).


*2C ( NOMOR 3 )
Program Menganalisis Bilangan
Program ini digunakan untuk menganalisis bilangan yang diinput oleh pengguna dan menampilkan faktor-faktor serta status prima dari bilangan tersebut. Pertama, program akan memeriksa apakah input yang diberikan valid dan sesuai dengan format yang diharapkan.
Jika input valid, program akan menampilkan bilangan yang diinput dan faktor-faktor dari bilangan tersebut. Faktor-faktor ini diperoleh dengan melakukan perulangan dari 1 sampai bilangan yang diinput dan mengecek apakah bilangan tersebut habis dibagi oleh setiap nilai dalam perulangan.
Selanjutnya, program akan mengecek apakah bilangan tersebut prima atau tidak menggunakan fungsi 'isPrime'. Fungsi ini akan mengecek apakah bilangan tersebut memiliki faktor lain selain 1 dan dirinya sendiri. Jika tidak, maka bilangan tersebut dikatakan prima.
Program ini sangat berguna untuk menganalisis bilangan dan mengetahui faktor-faktor serta status prima dari bilangan tersebut.
