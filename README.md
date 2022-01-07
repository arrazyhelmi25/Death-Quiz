# DeathQuiz

**Proyek Mata Kuliah Rekayasa Perangkat Lunak (RPL)**

**Universitas Indonesia, Fakultas Teknik, Teknik Komputer 2018**

**Judul Aplikasi : "Death Quiz"**

Death Quiz merupakan sebuah aplikasi kuis (multiple choice quiz) berbasis android, dimana mempunyai beberapa pilihan kategori dan level kuis yang dapat dipilih oleh user. Informasi kredensial user, level kuis, kategori kuis, serta kumpulan soal kuis disimpan dan diolah melalui firebase. 

Aplikasi ini ditujukan kepada siapa saja yang ingin mengisi waktu luangnya untuk menguji dan menambah wawasannya melaui soal - soal kuis yang diberikan paad aplikasi. Aplikasi ini bisa digunakan dimana saja dan tidak membutuhkan akses internet jika memilih opsi "Login as Guest", membutuhkan akses internet jika memilih opsi "Login with Account", karena harus mengecek informasi kredensial yang diinputkan oleh user ke database. Aplikasi ini bekerja selama 24 jam jadi bisa digunakan kapan saja ketika user ingin menggunakannya.

**Screenshot Program Aplikasi :**
1. Login

![](image/login.png)

2. Register

![](image/register.png)

3. Main

![](image/main.png)

4. Food Detail

![](image/detail1.png)

5. Cart

![](image/cart1.png)

6. About Us

![](image/aboutus1.png)

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
