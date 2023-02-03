# kalkulator-sederhana-methode-OOP
Untuk Memenuhi Tugas MK OOP Universitas Baturaja
![image](https://user-images.githubusercontent.com/17256521/216539352-a1100a88-0714-4ddb-970b-8ca4a3168b4d.png)

Kode di atas adalah contoh implementasi dari konsep pemrograman berorientasi objek (OOP) dalam membuat sebuah kalkulator sederhana.

Pada bagian inisialisasi class, dibuat class bernama "Calculator" dengan 4 method/fungsi: add(), subtract(), multiply(), dan divide(). Masing-masing method akan menjalankan operasi aritmatika sesuai dengan namanya dan memberikan hasil kembalian dari operasi tersebut.

Lalu, bagian dari skrip PHP memeriksa apakah formulir telah dikirimkan melalui metode POST. Jika iya, maka skrip akan memeriksa apakah input pada formulir adalah angka dengan memanggil fungsi is_numeric(). Jika kedua input adalah angka, maka akan dibuat sebuah objek baru dari class Calculator dan memanggil salah satu method sesuai dengan tombol yang ditekan pada formulir. Hasil dari operasi akan ditampilkan pada halaman web.

Dengan menggunakan konsep OOP, kode menjadi lebih terstruktur dan mudah dikembangkan. Pemeliharaan dan peningkatan kode juga lebih mudah dilakukan karena terbagi menjadi beberapa bagian yang terpisah dan terorganisir.

Pada bagian class Calculator, kita membuat beberapa method atau operasi seperti add(), subtract(), multiply(), dan divide(). Setiap method memiliki parameter $num1 dan $num2 sebagai operand atau angka yang akan dioperasikan. Setiap method memiliki kembalian sebagai hasil dari operasi.

Kemudian pada bagian if ($_SERVER['REQUEST_METHOD'] === 'POST'), kita cek apakah form telah dikirimkan dengan metode POST. Jika iya, maka kita akan mengambil nilai num1 dan num2 yang dikirimkan melalui form. Kemudian kita mengecek apakah nilai num1 dan num2 adalah angka dengan menggunakan is_numeric(). Jika bukan angka, maka akan menampilkan pesan "Masukkan angka yang valid". Jika iya, maka kita membuat objek baru dari class Calculator dan memanggil method yang sesuai dengan operator yang dipilih oleh pengguna. Hasil dari operasi akan ditampilkan.

Sebuah objek dari kelas Calculator dapat dibuat dengan memanggil '$calculator = new Calculator();'. Kemudian, metode yang ada dalam kelas ini bisa dipanggil menggunakan objek itu, seperti '$result = $calculator->add($num1, $num2)' untuk menambahkan dua angka.

Kemudian, kode PHP memeriksa apakah request yang diterima adalah POST dan jika iya, maka memeriksa apakah input yang diterima adalah angka. Jika iya, maka objek $calculator akan dipanggil dan metodenya akan dipanggil sesuai dengan operator yang dipilih (tambah, kurang, kali, atau bagi).

Hasil dari operasi yang dipilih akan ditampilkan dengan mencetak string "Hasil: " diikuti dengan nilai dari operasi tersebut.
