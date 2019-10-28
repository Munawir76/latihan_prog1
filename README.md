#Latihan1

## Mengenal Version Control System (VCS)  
VCS adalah sebuah sistem yang mencatat semua perubahan yang terjadi pada file atau sekumpulan file seiring dengan terjadinya pergantian atau perubahan yang telah dilakukan, jadi kita dapat melihat versi spesifiknya kapan saja.

### Langkah-langkah menggunakan git

1.  Install git, setelah sudah diinstall bisa dicoba CMD
2.  Untuk menggunakan git, perlu dikonfigurasi user.name dan user.email
	$ git config --global user.name "nama.user"
	$ git config --global user.email "email.user"
3.  Buat direktory astif, misal lab_pemograman
    Klik kanan pada direktory aktif tersebut dan pilih git bash.
4.  Buat direktory project praktikum pertama dengan nama latihan1
	$ mkdir latihan1
	$ cd latihan1
    Jalankan perintah git init
	$ git init
    Untuk menambahkan file pada repository coba buat satu file bernama README.md
	$ echo "#latihan1" >> README.md
    Untuk menambahkan file baru saja dibuat tersebut gunakan perintah git add
	$ git add README.md
    Untuk menyimpan perubahan pada database (commit) gunakan perintah git commit -m "komentar commit"
	$ git commit -m "file pertama saya"
5.  Membuat repository server masuk ke link "https://github.com
6.  Pilih tanda yang berada dipojok kanan atas "new repository"
7.  Buat nama repository. misal "lab_pemograman"
8.  Pilih "creat repository"
9.  Salin link yang tertera dilaman berikutnya.
10. Tempel link yang sudah disalin ke dalam direktory project
11. Untuk menambhakan remote repository server gunakan perintah git remote add origin [url]
	$ git remote add origin https://github.com/Munawir76/lab_pemograman.git
12. Untuk mengirim perubahan ke server. perintah ini akan meminta memasukan user name dan password pada akun github.com
	$ git push -u origin master
13. Melihat perubahan pada server repository'
    Buka halaman github.com dan lihat perubahan pada laman tersebut.
14. Clone repository 
    Adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositornya. 
	$ git clone https://github.com/Munawir76/lab_pemograman.git


https://github.com/Munawir76/latihan1..git