<img src="img/Picture2.png">

<br>

<h1 align="center"> Time Complexity dan Big-O Notation </h1>

<p align="justify">&nbsp &nbsp &nbsp Setiap programmer yang baik akan menggunakan cara yang paling efektif dan efisien dalam menyelesaikan suatu permasalahan. Dan untuk bisa melakukan hal tersebut, <b>kita harus bisa meminimalisir kompleksitas dari algoritma yang kita gunakan.</b> Kompleksitas suatu algoritma dibagi menjadi 2, yaitu Time Complexity dan Space Complexity. <b>Time Complexity</b> adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan <b>Space Complexity</b> adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. Dan disini kita hanya akan membahas tentang Time Complexity.

<br>

#### Pengertian Algoritma :

<p align="justify">&nbsp &nbsp &nbsp Algoritma adalah serangkaian proses yang dilakukan secara berurutan untuk menyelesaikan sebuah permasalahan. Algoritma bisa bermacam-macam tergantung kepada siapa yang membuat algoritma tersebut. Namun permasalahannya adalah <b><i>algoritma mana yang lebih efektif dan efisien?</i></b>

<p align="justify"><b>Time Complexity Analysis</b> adalah <i>suatu cara sederhana untuk mengetahui berapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma dengan input tertentu (n).</i> Biasanya lebih dikenal dengan sebutan <b>Big-O Notation</b>. <i><b>Big O Notation</b></i> digunakan untuk mengukur tingkat kompleksitas suatu algoritma.

<br>

<h2 align="center">Big-O Nation</h2>

<p align="justify">&nbsp &nbsp &nbsp Big-O Notation adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk Aljabar, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.

<p align="center"><img src="img/gambar1.png" width="500px"></p>

<p align="justify">Sederhananya, semua contoh yang ada diatas mengatakan bahwa <b>“kita hanya akan melihat faktor yang memiliki dampak paling besar terhadap nilai yang dihasilkan oleh algoritma tersebut”</b>.

<br>

Terdapat beberapa macam __time complexity__, diantaranya :

## O(1) — Constant Time

__Constant Time__ artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses _(runtime)_ dari algoritma tersebut.

<p align ="center"><img src="img/gambar2.png" width="500px"></p>

<p align="justify">&nbsp &nbsp &nbsp Dari contoh di atas, terdapat sebuah fungsi untuk mengambil elemen pertama dari sebuah input array. Kita bisa melihat bahwa berapapun jumlah array yang diberikan kepada fungsi tersebut, dia akan selalu melakukan 1 hal, yaitu mengambil elemen pertama. Itu artinya <b>jumlah input yang diberikan tidak mempengaruhi waktu proses <i>(runtime)</i> dari algoritma tersebut.</b>

<p align="center"><img src="img/gambar3.png" width="500px"></p>

<br>

## O(log n) — Logarithmic Time

<p align="justify"> &nbsp &nbsp &nbsp <b>Logarithmic Time</b> artinya ketika kita memberikan input sebesar n terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor. Salah satu contohnya adalah algoritma <b>Binary Search.</b> Binary Search adalah algoritma yang kita gunakan dalam mencari posisi nilai dari suatu array dengan cara ‘mengeliminasi’ setengah dari array input untuk mempercepat proses pencarian.

<p align="center"><img src="img/gambar4.jpg" width="500px"></p>

_Note: Fungsi rekursif biasanya Logarithmic_

<br>

## O(n) — Linear Time

<p align="justify"><b>Linear Time</b> adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.

<p align="center"><img src="img/gambar5.png" width="500px"></p>

<p align="justify">Kita bisa melihat bahwa <b>semakin banyak jumlah input yang diberikan, maka waktu proses/<i>runtime</i> dari fungsi tersebut akan semakin besar.</b>

<p align="center"><img src="img/gambar6.png" width="500px"></p>

<br>

## O(n²) — Quadratic Time

<p align="justify">&nbsp &nbsp &nbsp <b>Quadratic Time</b> adalah ketika runtime dari fungsi kita adalah sebesar n^2, dimana n adalah jumlah input dari fungsi tersebut. Hal tersebut bisa terjadi karena kita menjalankan <b>fungsi linear didalam fungsi linear</b> (n*n).

<p align="center"><img src="img/gambar7.jpg" width="500px"></p>

<p align="center"><img src="img/gambar9.png" width="500px"></p>

<br>


## O(2^n) — Exponential Time

<p align="justify"> &nbsp &nbsp &nbsp <b>Exponential Time</b> biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap <b>kombinasi</b> dan <b>permutasi</b> dari semua kemungkinan.

<p align="center"><img src="img/gambar8.png" width="500px"></p>

<br>

### Kesimpulan 

<p align="justify">&nbsp &nbsp &nbsp Sebagai programmer, kita sering kali dihadapkan dengan adanya beberapa solusi untuk sebuah permasalahan dan kita dibingungkan dengan pertanyaan <b><i>“mana solusi yang lebih efisien?”</i></b> Dengan memahami Big-O Notation, kita akan lebih mudah dalam melihat mana algoritma yang lebih efisien yang bisa kita gunakan untuk menyelesaikan permasalahan yang sedang dihadapi.

<p align="center"><img src="https://www.gambaranimasi.org/data/media/466/animasi-bergerak-terima-kasih-0111.gif" width="700px"></p>
