---
title: "Blockchain: Solusi Resiko Keterlibatan Pihak Ketiga yang Tidak Bertanggung Jawab"
description: "Tidak ada satu pun transaksi dalam kehidupan manusia modern yang berhubungan dengan internet yang benar-benar terlepas dari pihak ketiga. Dalam sistem blockchain, pihak ketiga ini disebut “services” (yang memberikan layanan)."
excerpt: "Tidak ada satu pun transaksi dalam kehidupan manusia modern yang berhubungan dengan internet yang benar-benar terlepas dari pihak ketiga. Dalam sistem blockchain, pihak ketiga ini disebut “services” (yang memberikan layanan)."
date: 2020-06-04T09:19:42+01:00
lastmod: 2020-06-04T09:19:42+01:00
draft: false
weight: 50
images: []
categories: ["Teknologi", "Blockchain", "Bitcoin", "Desentralisasi"]
tags: ["Desentralisasi privasi", "Keamanan data", "Bitcoin" ,"Ancaman pihak ketiga"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: true
---
## Pengantar
Begitu banyak kegiatan/transaksi di dalam kehidupan kita memanfaatkan pihak ketiga. Ketiga Anda menggunakan jasa bank, sistem informasi pendaftaran ke sekolah pilihan, bahkan untuk bersosialisasi di dunia maya seperti facebook. Dan, siapa pun tahu bahwa facebook pernah menjual data para user-nya dan mendapatkan keuntungan. 

Tidak ada satu pun transaksi dalam kehidupan manusia modern yang berhubungan dengan internet yang benar-benar terlepas dari pihak ketiga. Dalam sistem blockchain, pihak ketiga ini disebut “services” (yang memberikan layanan), bedanya mereka diberikan aturan yang kuat dan aman yang membuat mereka hanya bisa mengakses apa yang diizinkan oleh user. Dengan kata lain, user tetap memegang otoritas tertinggi atas data mereka. 

Bayangkan contoh seperti ini, ketika Anda menggunakan Facebook, Anda memberikan data juga dengan kunci sekaligus. Pihak Facebook bisa melihat data itu sebagai data tak bertuan, mereka punya datanya, tapi tidak tahu milik siapa sehingga tidak dapat menyelewengkan penggunaan data itu. Dan, suatu kali user ingin menghapus atau menarik kembali informasi yang telah diberikan, user dapat sewaktu-waktu mengubah “kontrak” atau izinnya.

## Ketakutan pengguna
1. Ketakutan—sebetulnya yang wajar—dari user terhadap pihak ketiga umumnya adalah:
2. Ketika tiba-tiba mereka tidak dapat dipercaya
3. Jika tiba-tiba diserang (hacked?) dan semua data dicuri
4. Adanya pihak ketiga kadang membuat komunikasi terhambat, mengapa tidak langsung berkomunikasi dari peer-to-peer?
5. Otentifikasi dan validasi sangat penting, lantas bagaimana mengetahui otentifikasi dan validasinya dilakukan oleh orang yang benar atau tidak?

Ketika Satoshi Nakamoto menemukan blockchain untuk diterapkan dalam bitcoin, permasalahan di atas terjawab sudah. Bitcoin menggunakan kiptocurrency dengan desentralisasi yang pertama di dunia. Sistem pada Bitcoin menukar dan mentransfer dengan menggunakan ledger (buku induk) yang merekam semua rincian setiap transaksi tanpa memerlukan jasa pelayanan sentral yang terpercaya sekalipun. Masing-masing pihak terlibat mendapatkan satu salinan buku besar. Untuk otentifikasi dan identifikasi, setiap transaksi akan ditandatangani secara digital oleh si pemilik dengan sebuah kunci private. 
## Mekanisme Konsensus
Agar semua transaksi itu dapat dipantau secara simultan, maka transaksi berulang digrupkan secara terstruktur dan disebut sebagai “block” yang dapat dibedakan dengan hash dan timestamp yang unik. Untuk mengurasi resiko pengguna yang tidak dapat dipercaya (distruted user) maka diberlakukan mekanisme konsensus, artinya setiap ada perubahan dalam buku induk akan di-update oleh konsensus/perjanjian (agreement) dari simpul-simpul mayoritas (majorities of nodes).  

Proses input data baru di dalam sistem blockchain sehingga membentuk block yang baru memerlukan waktu 10 menit. Dalam arti kata, dengan detilnya pekerjaan yang dilakukan untuk dapat menghasilkan block yang baru dipastikan kecurangan data dapat disingkirkan.

## Validasi Block
Beberapa langkah dalam validasi block antara lain:
- Semua transaksi yang terisi di dalam block diverifikasi dengan langkah sebagai berikut: setiap transaksi sebagai output dihasilkan dari nodes penerima yang diotorisasi di dalam transaksi dengan menggunakan public key hash. Dengan kunci publik pengguna dapat memberikan data dengan tetap merahasiakan identitasnya. Mereka dikenal sebagai pseudonymous identity. Namun demikian, user tetap membutuhkan kunci private untuk mengakses kontrol mereka terhadap bitcoin (contoh kasus). Hanya user dengan kunci private yang dapat melakukan claim terhadap output dari transaksi yang mereka lakukan.
- Block’s hash yang sebelumnya digunakan sebagai acuan bagi pembentukan block berikutnya dan dicek dari genesis block.
- Akurasi dari time stamp diverifikasi
- Proof-or-work dari block yang dibentuk dinyatakan valid.
Oleh: Roy Sari Milda Siregar, ST, M.Kom