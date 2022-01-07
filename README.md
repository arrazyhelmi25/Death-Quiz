# DeathQuiz

**Proyek Mata Kuliah Rekayasa Perangkat Lunak (RPL)**

**Universitas Indonesia, Fakultas Teknik, Teknik Komputer 2018**

**Judul Aplikasi : "Death Quiz"**

Death Quiz merupakan sebuah aplikasi kuis (multiple choice quiz) berbasis android, dimana mempunyai beberapa pilihan kategori dan level kuis yang dapat dipilih oleh user. Informasi kredensial user, level kuis, kategori kuis, serta kumpulan soal kuis disimpan dan diolah melalui firebase yang berperan sebagai database aplikasi. Dari setiap soal kuis yang ditampilkan ada timer (pewaktu) selama 10 detik, sehingga jika user tidak menjawab soal tersebut dalam waktu 10 detik, maka akan langsung dipindahkan ke soal berikutnya dan user tidak mendapatkan poin dari soal tersebut. Untuk level kuis, semakin tinggi level yang dipilih oleh user, maka soal yang diberikan juga akan semakin sulit.

Aplikasi ini ditujukan kepada siapa saja yang ingin mengisi waktu luangnya untuk menguji dan menambah wawasannya melaui soal - soal kuis yang diberikan pada aplikasi. Aplikasi ini bisa digunakan dimana saja dan tidak membutuhkan akses internet jika memilih opsi "Login as Guest", membutuhkan akses internet jika memilih opsi "Login with Account", karena harus mengecek informasi kredensial yang diinputkan oleh user ke database. Aplikasi ini bekerja selama 24 jam jadi bisa digunakan kapan saja ketika user ingin menggunakannya.

Perbedaan signifikan antara login sebagai tamu dengan login dengan menggunakan akun yaitu ada pada fitur kategori kuis, dimana akan ada pilihan kategori kuis yang lebih banyak jika memilih opsi login dengan menggunakan akun.

**Screenshot Program Aplikasi :**
1. Launcher

![](image/launcher.jpg)

2. Main Home

![](image/home.jpg)

3. Home (Login as Guest)

![](image/home_guest.jpg)

4. Quiz Category (Login as Guest)

![](image/category_guest.jpg)

5. Level

![](image/level.jpg)

6. Question True Answer (Login as Guest)

![](image/question_guest_true.jpg)

7. Question Wrong Answer (Login as Guest)

![](image/question_guest_wrong.jpg)

8. Score

![](image/score.jpg)

**IDE yang dibutuhkan :**
1. Android Studio versi 4.1 keatas
2. JDK versi 8 keatas
3. Library 

**Cara menggunakan :**
1. Unduh android studio versi 4.1 minimum 
2. Install android studio beserta SDK dan JDK
3. Membuat Android Virtual Device dengan API 27 (Oreo) minimum
4. Buka Project pada android studio sesuai dengan lokasi pengunduhan source code
5. Build project, pada tahap ini project telah di clone
6. Run project pada AVD

**Alur Singkat Cara Kerja Program Aplikasi :** Pertama ketika user membuka aplikasi akan dibawa ke interface login, jika user belum mempunyai akun maka dapat membuatnya terlebih dahulu dengan klik tulisan "register here", setelah register user akan dibawa lagi ketampilan login untuk memasukkan informasi akunnya. Setelah login akan ke tampilan utamanya, disana ada 3 submenu yaitu popular, reccommended, dan all menu. User juga bisa mencari nama makanan atau minuman yang ingin dicari untuk menghemat waktu, hasil pencarian akan ditampilkan di bagian all menu. Untuk ketampilan About Us user dapat menekan gambar garpu dan pisau yang ada disebelah tulisan "Delicious Food". Tampilan informasi secara mendetail terkait makanan dan minuman akan ditampilkan jika user menekan gambar atau minuman yang dipilih, nanti akan ada pilihan add to cart, selanjutnya makanan akan ditampilkan dibagian cart (gambar keranjang).
