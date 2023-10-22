---
title: "Ngrok: Mengenal Ngrok, Instalasi dan Konfigurasi "
description: "Ngrok adalah alat tunnelling (tunneling tool) yang digunakan untuk membuat saluran aman antara dua titik akhir (endpoints) melalui internet atau jaringan lokal. Alat ini memungkinkan kita untuk memberikan akses ke server atau layanan yang berjalan di komputer lokal kita ke internet, bahkan jika komputer tersebut berada di belakang firewall atau jaringan NAT (Network Address Translation)."
excerpt: "Ngrok adalah alat tunnelling (tunneling tool) yang digunakan untuk membuat saluran aman antara dua titik akhir (endpoints) melalui internet atau jaringan lokal. Alat ini memungkinkan kita untuk memberikan akses ke server atau layanan yang berjalan di komputer lokal kita ke internet, bahkan jika komputer tersebut berada di belakang firewall atau jaringan NAT (Network Address Translation)."
date: 2023-09-18T13:57:55+07:00
lastmod: 2023-09-18T13:57:55+07:00
draft: false
weight: 50
images: []
categories: ["Pemrograman"]
tags: ["Ngrok","Share Webserver Local"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
toc: true
---
## Apa itu NGROK
Ngrok merupakan sebuah tools mungkin tepatnya layanan yang memungkinkan kita untuk melakukan tunnelling (tunneling tool) untuk membuat koneksi yang aman antara dua titik (endpoints) melalui internet atau jaringan lokal. Dengan Ngrok kita dapat memberikan akses di komputer lokal kedalam jaringan internet. 

Ngrok sering digunakan oleh programmer khususnya pengembang website untuk demo dan pengujian website yang dibangun. Contoh sederhananya, kita sedang membuat website di komputer lokal dan sebelum upload ke internet, kita ingin menampilkan hasil terlebih dahulu ke client yang memesan website. Sebenarnya kita dapat upload ke server online (demo) di internet, tetapi akan membutuhkan waktu memindahkan semua gile. Disini Ngrok dapat menjembatani hal tersebut tanpa harus upload file ke internet, kita cukup konfigurasi Ngrok di komputer local dan memberikan alamatnya website ke clien. Alamat website yang diakses client akan langsung terhubung ke webserver ataupun komputer local kita.

## Fitur dalam Ngrok

Untuk lebih jelasnya, berikut ini beberapa fitur yang dapat kita gunakan dengan Ngrok:

### Port Forwarding
Kita dapat mengarahkan koneksi yang masuk ke alamat Ngrok ke port tertentu pada komputer lokal kita, sehingga aplikasi yang berjalan pada port tersebut dapat diakses dari luar.

### Share Lokalhost
Ngrok memungkinkan kita melakukan demo aplikasi yang berjalan di localhost dengan pihak lain, cukup dengan memberikan URL Ngrok yang unik.

### Pengujian dan Debugging
Kita dapat menggunakan Ngrok untuk melakukan pengujian dan debugging aplikasi web secara eksternal tanpa perlu mendeploy aplikasi ke server production yang  live di internet.

### Callback Webhook
Ngrok dapat digunakan untuk membuat koneksi yang aman untuk menerima callback dari layanan pihak ketiga yang memerlukan akses ke server kita.

### Environment Sharing
Kita juga dapat berbagi lingkungan pengembangan dengan pihak lain, sehingga memungkinkan kolaborasi yang lebih mudah dalam pengembangan perangkat lunak.


## Daftar
Untuk dapat menggunakan layanan Ngrok, silakan daftar terlebih dahulu akun di website resminya di __https://ngrok.com__

## Konfigurasi di komputer local (macOs)
Download terlebih dahulu Ngrok, dapat menggunakan brew dan ketikkan printah di command prompt
```
brew install ngrok/ngrok/ngrok
```
Atau dapat juga download manual dan ekstrak file archive, kemudian pindahkan file Ngrok ke direktori `/usr/local/bin`
```
sudo cp ngrok /usr/local/bin
```
Konfigurasi Ngrok dengan memberikan authentikasi untuk mengakses komputer lokcal kita dengan mengisikan token yang diberikan oleh Ngrok
```
ngrok config add-authtoken ISIKAN_TOKEN_YANG_DIBERIKAN_NGROK
```
Jalankan service Ngrok dengan perintah
```
ngrok http 80
```

