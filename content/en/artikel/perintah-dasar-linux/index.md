---
title: "Perintah dasar Linux"
description: "Linux adalah keluarga sistem operasi turunan Unix yang bersifat _open-source_ dan didasarkan pada Linux Kernel. Terdapat berbagai distribusi (Distro) linux yang populer seperti Ubuntu, Fedora, Mint, Debian, dan lain-lain. Berikut ini perintah dasar dalam Linux."
date: 2020-07-18T13:57:55+07:00
lastmod: 2020-07-18T13:57:55+07:00
draft: false
weight: 50
images: []
categories: ["Tools", "Pemrograman", "Networking"]
tags: ["Linux","Perintah Linux", "Command Line", "Command line Linux"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
toc: true
---
## Sepintas tentang Linux
Linux adalah keluarga sistem operasi turunan Unix yang bersifat _open-source_ dan didasarkan pada Linux Kernel. Terdapat berbagai distribusi (Distro) linux yang populer seperti Ubuntu, Fedora, Mint, Debian, dan lain-lain.

Sejak pertama kali dirilis pada tahun 1991, popularitas Linux terus meroket karena sifatnya yang open-source. User bebas memodifikasi Linux dan mendistribusikannya dengan memakai namanya sendiri. 

Ketika mengoperasikan Linux, kita dapat menggunakan shell yang merupakan interface yang menyediakan akses ke layanan sistem operasi. Penggunaan [command-line interface (CLI)](https://kaban.my.id/mengenal-cli-command-line-interface/ "Mengenal Command Line Interface") sangat disarankan karena lebih powerful dan efektif. Task atau tugas yang membutuhkan proses dengan banyak langkah melalui GUI dapat dilakukan hanya dalam waktu sekian detik dengan mengetikkan command atau perintah ke CLI.

Jadi, ketika hendak menggunakan Linux, kita sebaiknya tahu perintah dasar Linux. Di artikel ini, kita akan mempelajari perintah Linux yang paling mendasar.

## Perintah Dasar Linux

Sebelum menjabarkan perintah dasar sistem operasi Linux, Kita harus membuka _command line_ terlebih dulu.

Berikut daftar command dasar Linux:

### Perintah _pwd_

Perintah `pwd` _(Print Working Directory)_ berfungsi untuk mencari path dari direktori (folder) yang Anda gunakan saat ini. Perintah ini akan mengembalikan path yang absolut (penuh), yang pada dasarnya merupakan path semua direktori yang diawali dengan garis miring depan (/). Contoh dari path absolut adalah `/home/username`.

### Perintah _cd_ 

Untuk pindah direktori gunakan perintah `cd` _(change direktory)_. Perintah ini harus disertakan nama direktori yang dituju beserta lokasi/path.

Contohnya, saat ini Kita sedang berada di direktori `/home/username/Documents` dan ingin membuka direktori `Photos` yang berada di direktori `Documents`. Untuk melakukannya, kita mengetikkan `cd Photos`

Contoh lainnya, sekarang kita sedang berada di direktori `/home/username/Documents/Photos`, kemudian ingin berpindah ke direktori `/home/username/Documents/Movies` maka kita dapat mealukannya dengan mengetikkan path secara langsung, ` cd /home/username/Documents/Movies` 

Alternatif lain, kita dapat berpindah direktori dengan cara berikut:

`cd ..` (dengan dua tanda titik) untuk memindahkan satu direktori ke atas.


`cd-` (dengan tanda penghubung) untuk berpindah ke direktori sebelumnya.


### Perintah _ls_

Perintah `ls` _(lists)_ digunakan untuk untuk melihat konten atau isi dari direktori. Secara default, command ini akan menampilkan isi dari direktori yang Anda gunakan saat ini.
Sebgai contoh, kita sedang berada pada direktori `/home/username/Documents` kemudian kita ketikkan `ls` maka akan ditampilkan isi (file dan direktori) yang ada pada direktori kita berada.

Jika ingin melihat isi direktori lain, ketik `ls`, disusul dengan path direktori. Contoh, ketik `ls /home/username/Downloads` untuk melihat isi direktori `/home/username/Downloads`.

Untuk menampilkan file yang tersembunyi dalam direktori dapat menggunakan `ls -a`
Untuk menampilkan file dan direktori secara detail beserta hak akses, ukuran dan pemilik (owner) dengan perintah `ls -la`

### Perintah _cat_ 

`cat` _(concatenate)_ perintah untuk membuat daftar konten atau isi file pada standard output (sdout). Untuk menjalankan perintah ini, ketik `cat` yang kemudian diikuti dengan nama dan ekstensi file. 

Sebagai contoh, kita ingin membuat file baru maka dapat menggunakan perintah: `cat > biodata.txt` kemudian `enter` akan menghasilkan sebuah file baru dengan nama `biodata.txt` ketikkan sembarang kalimat dan tekan tombol `enter` selanjutnya `control` + `c` untuk menyimpan.

Menggabungkan isi file dapat menggunakan perintah
`cat file1 file2 > file3` artinya kita menggabungkan isi `file1` dan `file2` kedalam file baru yang bernama `file3`


### Perintah _cp_

Perintah `cp` _(copy)_ untuk menyalin file dari direktori saat ini ke direktori yang berbeda. 
Contohnya, `cp biodata.txt /home/username/Documents` untuk copy file `biodata.txt` dari direktori saat ini ke direktori `/home/username/Documents`.

contoh selanjutnya, kita copy file dari direktori lain (bukan direktori aktif kita sekarang) ke direktori lain
`cp /home/username/Documents/fotoku.jpg /home/username/Documents/Photos` artinya, kita copy file `fotoku.jpg` dari direktori `/home/username/Documents/` ke direktori `/home/username/Documents/Photos`

### Perintah _mv_

Perintah `mv` _(move)_ digunakan untuk memindahkan (mengubah) file atau direktori. Penggunaan perintah __mv__ sama dengan penggunaan perintah __cp__ .

Contoh penggunaan, `mv /home/username/Documents/fotoku.jpg /home/username/Documents/Photos` artinya, kita memindahkan file `fotoku.jpg` dari direktori `/home/username/Documents/` ke direktori `/home/username/Documents/Photos` .

contoh lain, `mv file1.txt file2.txt` berarti kita mengganti nama file `file1.txt` menjadi `file2.txt` 

### Perintah _mkdir_

Perintah `mkdir` _(make directory)_ digunakan untuk membuat direktori.
Contoh penggunaan, `mkdir foto` akan membuat sebuah direktori (folder) dengan nama `foto` pada direktori yang sedang aktif (direktori kita mengetikkan perintah).

contoh lain, ` mkdir /home/username/Documents/foto` akan membuat sebuah direktori dengan nama `foto` pada direktori ` /home/username/Documents/`


### Perintah _rmdir_ 


Perintah `rmdir` (remove directory), digunakan untuk menghapus direktori kosong.
contoh penggunaan, `rmdir foto` akan menghapus direktori `foto` pada direktori yang sedang aktif (direktori kita mengetikkan perintah).

contoh lain, ` rmdir /home/username/Documents/foto` akan menghapus direktori `foto` pada direktori ` /home/username/Documents/`


### perintah _rm_ 

Perintah `rm` (remove) berfungsi untuk menghapus direktori beserta isinya. 
contoh penggunaan, `rm foto` akan menghapus direktori `foto` beserta isinya pada direktori yang sedang aktif (direktori kita mengetikkan perintah).

contoh lain, ` rmdir /home/username/Documents/foto` akan menghapus direktori `foto` beserta isinya pada direktori ` /home/username/Documents/`

untuk menghapus file, `rm fotoku.jpg` berarti kita menghapus file yang bernama `fotoku.jpg` 

Hati-hati aat menggunakan perintah `rm`, karena file yang sudah dihapus tidak dapat dikembalikan lagi.😁

### Perintah _touch_

perintah `touch` digunakan untuk membuat file baru yang kosong melalui baris perintah Linux.
Sebagai contoh, `touch /home/username/Documents/biodataku.html` untuk membuat file `biodataku.html` di direktori `/home/username/Documents/`

### Perintah _locate_

Perintah `locate` digunakan untuk mencari file, fungsinya sama seperti pencarian di Windows. Apabila dipasangkan dengan argumen `-i `, perintah ini akan bersifat __case-insensitive__ sehingga file dapat dicari meski kita tidak mengingat namanya dengan tepat.

Untuk mencari file yang memuat dua atau lebih dari dua kata, gunakan tanda bintang (\*).
Misalnya, perintah `locate -i tugas*kampus` akan mencari file yang pada namanya termuat kata "tugas" dan “kampus”, dengan mengabaikan penulisan nama file huruf besar atau kecil.

### Perintah _find_

pPrintah `find` juga dapat digunakan untuk mencari file dan direktori. Bedanya, perintah `find` lebih ditujukan untuk mencari file yang berlokasi di dalam direktori yang diberikan.

Contoh, perintah `find /home/ -name catatan.txt` akan mencari file bernama `catatan.txt` di dalam direktori `home` dan subdirektorinya.

### Perintah _grep_


Perintah `grep` untuk melakukan pencarian di semua teks di dalam sebuah file.

Sebagai contoh, `grep medan catatanku.txt` akan mencari kata `medan` di file `catatanku.txt`. Baris yang memuat kata yang dicari akan ditampilkan seluruhnya.

### Perintah _sudo_
Perintah `sudo` (SuperUser Do) berfungsi untuk menjalankan task yang memerlukan hak akses (permission) administrative atau root. 

### Perintah _df_

Perintah `df` digunakan untuk mendapatkan laporan tentang penggunaan disk space sistem. Laporan yang ditampilkan dalam bentuk persentase dan satuan KB. Bila ingin melihat laporan berupa satuan megabyte, ketik `df -m`.

### Perintah _du_
Perintah `du` merupakan perintah dasar Linux yang berfungsi untuk mengecek seberapa banyak space yang digunakan oleh suatu file atau direktori. Hanya saja, untuk format ringkasan, penggunaan disk yang ditampilkan berupa nomor blok disk alih-alih format ukuran pada umumnya. Jika ingin melihat jumlah penggunaan disk dalam satuan byte, kilobyte, dan megabyte, tambahkan argumen `-h` ke baris perintah.

### Perintah _head_

Perintah `head` digunakan untuk melihat baris pertama dari semua file teks. Secara default, perintah ini akan menampilkan sepuluh baris pertama. Namun, jumlah baris tersebut dapat diubah sesuai keinginan kita. Misalnya, jika  hanya ingin menampilkan lima baris pertama, ketik `head -n 5 namafile.ext`

### Perintah _tail_
Perintah `tail` memiliki fungsi yang sama dengan perintah `head`. Hanya saja, perintah `tail` akan menampilkan sepuluh baris terakhir dari suatu file. Misalnya, `tail -n namafile.ext`.

### Perintah _diff_

Perintah `diff` digunakan untuk membandingkan konten atau isi dua file berdasarkan baris demi baris. Setelah menganalisis file, perintah ini akan menghasilkan output berupa line atau baris yang tidak cocok. Programmer sering menggunakan perintah ini ketika membuat perubahan program.

contoh penggunaan `diff file1.ext file2.ext`.

### Perintah _tar_

Perintah `tar` digunakan untuk mengarsipkan banyak file ke dalam format file arsip tar

### Perintah _chmod_

Perintah `chmod` digunakan untuk membaca, menulis, dan menjalankan permission (hak akses) file dan direktori. 


### Perintah _jobs_

Perintah `jobs` akan menampilkan semua jobs saat ini beserta dengan statusnya. Pada dasarnya job merupakan proses yang dimulai oleh shell.

### Perintah _kill_

 Perintah `kill` akan mengirimkan sinyal tertentu ke aplikasi yang bermasalah dan memberi instruksi kepada aplikasi tersebut untuk berakhir atau mati dengan sendirinya.

Totalnya ada 64 sinyal yang dapat digunakan, tapi biasanya orang-orang hanya menggunakan dua sinyal, yakni:

SIGTERM (15) – meminta program untuk berhenti bekerja dan memberikannya waktu untuk menyimpan semua progress. Jika tidak ada sinyal khusus yang ditentukan ketika memasukkan perintah kill, sinyal inilah yang akan digunakan. 

SIGKILL (9) – memaksa program untuk berhenti bekerja saat itu juga. Progress yang tidak tersimpan akan hilang.

Selain sinyal, Kita juga harus tahu nomor identifikasi proses (process identification number – PID) dari sebuah program yang hendak dihentikan (kill). Jika tidak tahu PID-nya, Kita bisa menjalankan perintah `ps ux`.

Setelah mengetahui sinyal yang ingin digunakan dan PID program, ketikkan ` kill [signal option] PID`.

### perintah _ping_
Perintah `ping` berfungsi untuk mengecek status konektivitas ke server. Misalnya, `ping google.com`, command akan mengecek apakah  sudah terhubung ke Google atau belum dan juga mengukur waktu respons.

### Perintah _wget_
Perintah `wget` digunakan mengunduh file dari internet dengan bantuan command wget. Anda hanya perlu mengetikkan wget yang diikuti dengan link unduhan.

### Perintah _uname_

Perintah `uname` (Unix Name) digunakan untuk menampilkan mencetak informasi lengkap mengenai sistem Linux, misalnya nama mesin, sistem operasi, kernel, dan lain-lain.

### Perintah _top_
Sebagai terminal yang setara dengan Task Manager di Windows, perintah `top` akan menampilkan daftar proses yang sedang berlangsung dan seberapa banyak ruang CPU yang digunakan oleh tiap proses tersebut. Melakukan pengawasan terhadap penggunaan resource sistem sangatlah disarankan, terutama ketika Anda harus mencari tahu mana proses yang perlu dimatikan karena terlalu banyak menggunakan resource.

### Perintah _history_

Perintah `history` untuk mengecek kembali (review) pernah yang sudah digunakan sebelumnya.

### Perintah _man_

Perintah `man` digunakan untuk menampilkan manual/ bantuan perintah pada linux. sebgai contoh `man tail` akan menampilkan opsi yang dapat digunakan pada perintah `tail`.

### perintah _echo_

Perintah `echo` dasar Linux ini digunakan untuk memindahkan beberapa data ke dalam satu file. Misalnya, jika ingin menambahkan teks, `Hello world` ke file yang bernama `hello.txt`, yang perlu diketik adalah `echo Hello, my name is John >> hello.txt`

### perintah _zip_ , _unzip_

Gunakan perintah ``zip untuk __compress__ file ke arsip _zip_ dan perintah `unzip` untuk mengekstrak file zip ke arsip zip.

### perintah _hostname_

Perintah `hostname` digunakan untuk mengetahui nama host/network. Dengan menambahkan -I di akhir perintah, alamat IP jaringan akan ditampilkan.

### Perintah _useradd_, _userdel_

`useradd` digunakan untuk membuat user baru, sedangkan `passwd` untuk menambahkan password ke akun user tersebut. Untuk menambahkan user bernama alfa, misalnya, cukup ketikkan `useradd alfa  passwd 12345678` untuk menambahkan passwordnya.

Cara menghapus user sama dengan menambahkan user. Untuk menghapus akun user, ketik `userdel UserName`.
