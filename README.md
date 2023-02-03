# kalkulator-sederhana-methode-OOP
Untuk Memenuhi Tugas MK OOP Universitas Baturaja
![image](https://user-images.githubusercontent.com/17256521/216539352-a1100a88-0714-4ddb-970b-8ca4a3168b4d.png)

Code untuk kalkulator sederhana menggunakan PHP yang bisa melakukan operasi penjumlahan, pengurangan, perkalian, dan pembagian. Pertama, didefinisikan sebuah kelas Calculator dengan empat method add, subtract, multiply, dan divide yang masing-masing melakukan operasi matematika. Kemudian, dilakukan validasi apakah request yang diterima adalah POST dan apakah input num1 dan num2 adalah angka yang valid. Bila valid, instantiasi objek dari kelas Calculator dan panggil method yang sesuai dengan operator yang dipilih. Hasil operasi akan ditampilkan dengan echo "<div class='container'>Hasil: $result</div>".

Sebuah objek dari kelas Calculator dapat dibuat dengan memanggil '$calculator = new Calculator();'. Kemudian, metode yang ada dalam kelas ini bisa dipanggil menggunakan objek itu, seperti '$result = $calculator->add($num1, $num2)' untuk menambahkan dua angka.

Kemudian, kode PHP memeriksa apakah request yang diterima adalah POST dan jika iya, maka memeriksa apakah input yang diterima adalah angka. Jika iya, maka objek $calculator akan dipanggil dan metodenya akan dipanggil sesuai dengan operator yang dipilih (tambah, kurang, kali, atau bagi).

Hasil dari operasi yang dipilih akan ditampilkan dengan mencetak string "Hasil: " diikuti dengan nilai dari operasi tersebut.
