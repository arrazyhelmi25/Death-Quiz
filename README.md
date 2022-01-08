# DeathQuiz

**Proyek Mata Kuliah Rekayasa Perangkat Lunak (RPL)**

**Universitas Indonesia, Fakultas Teknik, Teknik Komputer 2018**

**Judul Aplikasi : "Death Quiz"**

Death Quiz merupakan sebuah aplikasi kuis (multiple choice quiz) berbasis android, dimana mempunyai beberapa pilihan kategori dan level kuis yang dapat dipilih oleh user. Informasi kredensial user, level kuis, kategori kuis, serta kumpulan soal kuis disimpan dan diolah melalui firebase yang berperan sebagai database aplikasi. Dari setiap soal kuis yang ditampilkan ada timer (pewaktu) selama 10 detik, sehingga jika user tidak menjawab soal tersebut dalam waktu 10 detik, maka akan langsung dipindahkan ke soal berikutnya. Hal ini berarti user tidak mendapatkan poin dari soal tersebut. Untuk level kuis, semakin tinggi level yang dipilih oleh user, maka soal yang diberikan juga akan semakin sulit. Diakhir kuis akan ditampilkan score yang berhasil didapatkan.

Aplikasi ini ditujukan kepada siapa saja yang ingin mengisi waktu luangnya untuk menguji dan menambah wawasannya melaui soal - soal kuis yang diberikan pada aplikasi. Aplikasi ini bisa digunakan dimana saja dan tidak membutuhkan akses internet jika memilih opsi "Login as Guest", membutuhkan akses internet jika memilih opsi "Login with Account", karena harus mengecek informasi kredensial yang diinputkan oleh user ke database. Aplikasi ini bekerja selama 24 jam, jadi bisa digunakan kapan saja ketika user ingin menggunakannya.

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
