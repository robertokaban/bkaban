---
title: "Mengenal Cli Command Line Interface"
description: "Kita mungkin sering mendengar istilah CLI dalam hal yang bergubungan dengan dunia IT, khususnya di bidang programmer. Apa sebenarnya CLI ini? CLI merupakan singkatan dari Command Line Interface."
excerpt: "Kita mungkin sering mendengar istilah CLI dalam hal yang bergubungan dengan dunia IT, khususnya di bidang programmer. Apa sebenarnya CLI ini? "
date: 2020-07-12T13:57:55+07:00
lastmod: 2020-07-12T13:57:55+07:00
draft: false
weight: 50
images: []
categories: ["Tools", "Pemrograman", "Networking"]
tags: ["CLI","Command Line"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
toc: true
---
## Pengantar
Kita mungkin sering mendengar istilah CLI dalam hal yang bergubungan dengan dunia IT, khususnya di bidang programmer. Apa sebenarnya CLI ini? CLI merupakan singkatan dari Command Line Interface. CLI sebagai media untuk memberikan instruksi/perintah pada komputer dan perangkat lunak (software) yang ada di dalamnya.  Pada CLI dapat diberikan berupa perintah dalam bentuk teks yang fungsinya untuk mengerjakan tugas (task) tertentu.

Dengan berkembangnya perangkat lunak yg sifatnya GUI (Graphic User Interface) membuat banyak orang kurang familiar dengan CLI. Bahkan beberapa user/pengguna pemula takut ataupun bisa juga malas menggunakan CLI. Mereka merasa program ini lebih cocok bagi user profesional dan yang sudah berpengalaman. Padahal, sebenarnya tidak. Saya sendiri terkadang kebingungan untuk menggunakan Sistem operasi terbaru, khususnya windows karena perubahan tampilan dan fitur, tetapi ketika menggunakan CLI dengan Command prompt windows maka akan lebih cepat dalam melakukan pekerjaan.

Sebagai contoh, saya mulai menggunakan windows di versi Windows 98, kemudian beralih ke Windows XP dan terakhir adalah Windows 7, semua tampilan versi windows tersebut tidak terlalu jauh berbeda. Kemudian ketika menggunakan Windows 8 atau Windows 10 versi sekarang, saya malah agak kesulitan untuk sekedar masuk ke menu Control panel, atau sekedar untuk buka Ms. Excel dari GUI Windows. Tetapi kalau sudah terbiasa dengan CLI, maka tinggal buka Command prompt (Winkey + R) dan ketikkan control kemudian enter, sudah masuk ke Control panel Windows, atau ketikkan excel, dan enter sudah membuka aplikasi Ms. Excel.

Meskipun demikian, semua terserah pada diri anda dan sesuaikan dengan kubutuhan. Kita lanjut, pada artikel kali ini kita akan membahas sejarah CLI beserta funginya.

## Sejarah CLI

CLI pertama kali digunakan secara luas sekitar tahun 1960-an dan ketika itu, perangkat input yang digunakan pada komputer hanyalah keyboard dan layar untuk menampilkan output. Komputer juga masih dapat menampilkan output dalam bentuk teks. Sistem operasi seperti Microsoft DOS (Disk Operating System) menggunakan CLI sebagai interface standar untuk user.

Untuk melakukan sejumlah tugas tertentu, user harus mengetikkan perintah (command) di CLI yang pada saat itu merupakan satu-satunya cara untuk dapat berkomunikasi dengan komputer.

Setelah perintah diketik, hasil yang ditampilkan akan berupa informasi berbasis teks atau tindakan tertentu yang dijalankan komputer. Jadi, kuncinya adalah jangan sampai mengetikkan perintah yang salah. Apabila salah mengetik perintah, bisa saja kita justru menghapus file yang tidak seharusnya dihapus, atau menutup program yang sedang berjalan. 

Setelah bertahun-tahun hanya menggunakan keyboard dengan risiko kesalahan ketik perintah yang cukup tinggi, akhirnya mouse diciptakan. Metode point-and-click pada mouse menjadi cara baru untuk berkomunikasi dengan komputer. Cara ini dirasa lebih aman dan mudah bagi pengguna komputer karena mereka tidak harus menggunakan CLI. 

Sistem operasi mulai mengembangkan cara komputasi yang lebih menarik dengan GUI (Graphical User Interface). Konsep GUI banyak digunakan dalam pengembangan perangkat lunak, selain lebih familiar pada user, dukungan teknologi perangkat input juga sudah memungkinkan interaksi dengan layar sentuh (Touch Screen). 

## Mengapa menggunakan CLI

Seperti yang sudah dijelaskan sebelumnya, GUI dikembangkan setelah mouse ditemukan dan menjadi perangkat input baru untuk mengoperasikan komputer. GUI memiliki tampilan yang menarik serta mudah dipahami. Meskipun demikian, bagi orang yang bergelut di bidang IT, terdapat beberapa alasan CLI dinilai lebih efektif dibanding GUI, diantaranya sebgai berikut:
### 1. Menggunakan Lebih Sedikit Resource

Sudah jadi rahasia umum bahwa program berbasis teks hanya menggunakan sedikit resource di komputer. Jadi, dengan CLI, Kita dapat menjalankan banyak task dengan penggunaan resource yang minim.

### 2. Cepat dan akurat

Kita dapat menggunakan perintah tertentu untuk menuju file atau folder, ataupun aplikasi yang lebih spesifik. Tidak akan ada kendala, asalkan perintah yang diketik benar. 

### 3. Mudah untuk menjalankan task secara berulang

Sistem operasi tidak menyediakan semua menu dan tombol yang diperlukan untuk menjalankan task demi alasan keamanan. Akibatnya, sulit jika kita harus menjalankan tugas yang berulang. CLI dapat mengatasinya. Misalkan, untuk mengelola ratusan file dalam sebuah folder, Kita hanya perlu menjalankan satu perintah yang kemudian bisa diotomatiskan untuk melakukan task yang sama.

### 4. Canggih dan efektif

Sebagian besar Sistem Operasi tidak mengizinkan user konfigurasi proses inti sistem dengan level user default, kita harus menggunakan akses root atau administrator. Windows memiliki sistem keamanan, dan MacOS memiliki System Integrity Protection yang membatasi Anda melakukan task yang dilindungi sistem. Dengan CLI kita dapat mengelola sistem sepenuhnya tanpa dibatasi larangan tersebut.

## Penutup