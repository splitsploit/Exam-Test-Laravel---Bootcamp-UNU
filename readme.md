<h1 align="center" id="title">Exam Test [ Laravel ] - Bootcamp Loh Jinawi Teknologi</h1>

Konsep Layanan dan Gateway
1.	Jelaskan apa yang dimaksud dengan layanan (service) dalam konteks pengembangan aplikasi web dan sebutkan keuntungannya.
2.	Apa itu API gateway dan mengapa penting dalam arsitektur mikroservices?
3.	Jelaskan langkah-langkah untuk membuat dan mengonfigurasi Service Provider di Laravel.

Konsumsi API Eksternal dengan Layanan (Services)
1.	Buatlah sebuah layanan (service) di Laravel yang bertanggung jawab untuk mengkonsumsi API eksternal dari JSONPlaceholder. Layanan ini harus memiliki metode fetchPosts yang mengembalikan data dalam bentuk array.
2.	Implementasikan layanan ini ke dalam sebuah controller yang bernama PostController. Tulis metode fetchAndStorePosts yang menggunakan layanan tersebut untuk mengambil data dari API eksternal dan menyimpannya ke dalam tabel posts di database.

Gateway Sederhana
1.	Buatlah gateway sederhana di Laravel untuk pintu depan yang bertindak sebagai penghubung antara aplikasi dan layanan PostService. Gateway ini harus memiliki metode untuk mengambil data dari layanan dan mengarahkannya ke PostController.
2.	Implementasikan gateway ini ke dalam rute Laravel sehingga semua permintaan ke endpoint /posts diarahkan melalui gateway sebelum mencapai PostController.

Penyimpanan Data ke Database
1.	Buat migrasi untuk tabel posts dengan kolom id, user_id, title, dan body. Tulis kode migrasinya.
2.	Tulis model Post yang sesuai dengan tabel posts dan jelaskan bagaimana Anda akan menyimpan data yang diambil dari layanan ke dalam tabel ini menggunakan Eloquent ORM.

Membuat API untuk Menampilkan Data
1.	Buatlah sebuah route di Laravel yang mengarah ke controller PostController metode index untuk menampilkan semua data dari tabel posts.
2.	Tulis kode untuk PostController metode index yang mengambil semua data dari tabel posts dan mengembalikannya dalam format JSON.

Notes:

-	Hasil dari task dapat disubmit ke repo yang sudah ditentukan dan buat folder sendiri-sendiri ( Nama folder nya adalah nama kalian masing-masing )

https://github.com/splitsploit/Exam-Test-Laravel-Bootcamp-UNU.git

-	Untuk bahasa pemrogramannya menggunakan Laravel ( versi 10 atau keatas )
-	Untuk databasenya bebas menggunakan apa saja
-   Waktu pengerjaan nya adalah 5 hari ( until friday, 14 june 2024 )
-	Selamat mengerjakan!