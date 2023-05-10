---
title: "Mengenal Composer: Dependency Manager PHP"
description: "Pada sebuah proyek aplikasi yang besar tentunya membutuhkan banyak library, dan umumnya setiap library ketergantungan dengan library yang lain. Instalasi library secara manual akan merepotkan dan membutuhkan waktu. Oleh karena itu, kita membutuhkan dependency manager yaitu Composer."
excerpt: "Pada sebuah proyek aplikasi yang besar tentunya membutuhkan banyak library, dan umumnya setiap library ketergantungan dengan library yang lain. Instalasi library secara manual akan merepotkan dan membutuhkan waktu. Oleh karena itu, kita membutuhkan dependency manager yaitu Composer."
date: 2022-11-17T02:55:26+07:00
lastmod: 2022-11-17T02:55:26+07:00
draft: true
weight: 50
images: []
categories: ["Tools","Pemrograman"]
tags: ["Composer", "Dependency manager PHP", "Composer PHP"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
---

## Apa itu Composer?

Pada sebuah proyek aplikasi yang besar tentunya membutuhkan banyak library, dan umumnya setiap library ketergantungan dengan library yang lain. Instalasi library secara manual akan merepotkan dan membutuhkan waktu. Oleh karena itu, kita membutuhkan dependency manager yaitu Composer. Composer adalah dependency manager untuk PHP, yaitu sebuah tools yang digunakan untuk memudahkan kita dalam mengelola library PHP yang digunakan pada aplikasi kita beserta dependensinya.

Sebagai gambaran, misalnya  kita memiliki suatu aplikasi yang membutuhkan library Reporting untuk generate dan menampilkan laporan. Library reporting yang kita butuhkan tersebut tidak berdiri sendiri, tetapi membutuhkan library lain, sebut saja FPDF (untuk generate dokumen berformat PDF) dan PHPExcell (untuk generate dokumen berformat spreadsheet). Dengan menggunakan composer, kita cukup menjalankan perintah untuk melakukan instalasi library reporting saja, selanjutnya composer akan secara otomatis melakukan instalasi library lain yang dibutuhkan oleh library tersebut. 

Composer bukanlah teknologi atau terobosan baru. Beberapa bahasa pemrograman atau tools lain sudah menggunakan cara yang relatif sama dengan cara kerja Composer. Jika anda adalah pengguna Linux maka tentu hal ini sudah tidak asing lagi, misalnya pada distro Fedora terdapat `Yum` atau pada distro Ubuntu terdapat peritnah `apt-get`, apa yang dilakukan oleh Composer mirip dengan perintah `yum` dan `apt-get` untuk melakukan instalasi atau memperbaharui suatu aplikasi. Selain bahasa pemrograman PHP, sebut saja NodeJs juga telah menggunakan tools `NPM` yang cara kerjanya seperti composer untuk instalasi library-nya.

## Apakah harus menggunakan Composer dalam pengembangan Aplikasi berbasis PHP?
Pengembangan aplikasi berbasis PHP tidaklah mutlak harus menggunakan Composer, hanya saja pada saat ini Composer telah menjadi bagian dari standar pengembangan aplikasi berbasis PHP. Banyak library PHP yang memang sejak awal didesain untuk mendukung Composer sehingga tidak ada panduan untuk menginstalnya secara manual lagi, tentu hal ini akan merepotkan kita jika kita memaksakan diri untuk tidak menggunakannya. Di samping itu, umumnya framework PHP modern menggunakan dan mendukung Composer.

## Bagaimana cara kerja Composer?
Cara kerja Composer dapat dilihat seperti gambar berikut:

<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEipgl5gJHUKLd0OwcNb6TJtJ4-Tt5HcRQTcG26KWLr_nPm7YcrS6-RwqyTISdpvaNO1LL6fsizod15ipCLe9CwbAlnLyKTceiopGc3W4Qo23PLw2rXhyUcuVdfpdKM7ZKnqspKWW3qaSagSMLZ2gavj4UZeAetGqFGRGIL9liwWj5JK6aGhss0huA2a/w640-h316/cara%20kerja%20composer.png' width="100%" class="border-0 rounded">

Keterangan:
1.	Mula-mula Composer membaca daftar library yang ingin kita instal yang mana daftar tersebut telah kita definisikan terlebih dahulu.
2.	Composer mengecek apakah di lokal komputer (cache) telah ada versi yang dimaksud. Jika di lokal komputer kita ada versi tersebut maka Composer akan mengecek lagi apakah library dimaksud membutuhkan dependensi dengan library lain atau tidak. 
3.	Jika library tersebut membutuhkan library lain, maka Composer akan mencoba melakukan instalasi atau menyalin library dependensi tersebut. Kemudian setelah itu, Composer akan memasang library utamanya ke current direktori.
4.	Apabila di lokal komputer tidak terdapat library dan dependensi dimaksud, maka Composer akan menghubungi server yang dalam hal ini adalah packagist.org (default). 
> ✔︎ Catatan: 
>Packagist (PHP package archivist) yaitu sebuah server repository yang menyimpan daftar URL dari library-library PHP seluruh dunia. Adapun kode library tersebut disimpan pada hosting lain. Sebagai contoh, framework Laravel hosting kodenya di https://github.com

5.	Setelah menemukan paket dimaksud maka kemudian Composer mengunduhnya dan memasangnya pada current directory. Di samping itu, Composer juga menyimpan paket tersebut pada cache komputer kita. Sehingga jika suatu saat kita akan menginstalnya lagi maka Composer cukup mengambil dari lokal komputer tanpa perlu men-download dari server lagi. 
kurang lebih seperti itu kira-kira cara kerja Composer. Oleh karena Composer terhubung ke server internet, maka kita perlu koneksi internet yang memadai untuk bisa menggunakan Composer dengan baik.

## Mengapa menggunakan Composer?
Intinya adalah untuk mempermudah kita. Seperti yang saya sampaikan pada awal tadi, Composer akan memudahkan kita dalam memasang suatu library PHP beserta dependensinya. Kita sebenarnya bisa saja memasang library library-library tersebut secara manual satu per satu kemudian mengkonfigurasinya. Namun, selain memakan waktu dan tidak efisien, cara manual ini juga sudah mulai ditinggalkan, yang mana saat ini banyak library PHP yang merekomendasikan untuk instalasi menggunakan Composer tanpa ada dokumentasi atau penjelasan tentang bagaimana cara melakukan instalasinya secara manual. 

Pada sebuah proyek aplikasi yang besar, dengan banyak library yang digunakan, maka memasang dengan cara manual tentu akan sangat merepotkan dan membutuhkan waktu yang lama. Jadi di samping memudahkan, Composer juga akan membuat pekerjaan kita lebih efektif dan efisien.

## Kesimpulan
Sebagai satu-satunya PHP dependency manager, saat ini Composer sudah menjadi bagian yang sangat penting dalam pengembangan aplikasi berbasis PHP, baik karena kemudahan maupun efisiensinya. Oleh karena itu, sebaikanya jika kita bergelut dalam bidang pemrograman, khususnya PHP maka penggunaan composer sangat di sarankan. Untuk download composer silakan langsung ke https://getcomposer.org, silakan baca panduan  penggunaan composer di https://getcomposer.org/book.pdf. 


