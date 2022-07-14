---
title: "Blockchains Penggebrak Desentralisasi Privasi?"
description: "bitcoin yang memungkinkan penggunanya melakukan transfer mata uang (currency) dengan aman tanpa pengatur yang terpusat (centralized), dengan menggunakan open ledger (blockchains) yang terbukti tangguh."
excerpt: "bitcoin yang memungkinkan penggunanya melakukan transfer mata uang (currency) dengan aman tanpa pengatur yang terpusat (centralized), dengan menggunakan open ledger (blockchains) yang terbukti tangguh"
date: 2020-06-04T09:19:42+01:00
lastmod: 2020-06-04T09:19:42+01:00
draft: false
weight: 250
images: []
categories: ["Teknologi", "Blockchain", "Bitcoin", "Desentralisasi"]
tags: ["Desentralisasi privasi", "Keamanan data", "Bitcoin"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
---
## Pengantar
Pernahkah Anda ketika melakukan sign up pada sebuah website diminta untuk memberikan sejumlah informasi yang Anda tidak bisa menarik kembali apa pun keterangan yang telah Anda berikan? Ingat bahwa update informasi yang Anda lakukan sekalipun tidak menghapus data yang telah terlanjur Anda berikan. Ketidakberdayaan kita sebagai pengguna teknologi IT telah membuat para peneliti mengembangkan banyak teknik yang memfokuskan pada perlindungan terhadap data personal.
Gembar-gembor pemanfaatan blockchains mulai berdengung sejak lima tahunan yang lalu. Berawal dari bitcoin yang mendemonstrasikan transaksi dan penyimpanan dana finansial secara private dengan menggunakan legder publik, semakin booming-lah blockchains mengikuti bitcoin. Mereka toh adalah dua hal yang tidak dapat dipisahkan.

## Kesuksesan Bitcoin
Kesuksesan bitcoin membuat orang—lintas keilmuan dan kepentingan—memberikan perhatian penuh pada perkembangan blockchains. Begitu banyak keunggulan yang dijamin oleh blockchains,di antaranya—merupakan fokus semua praktisi—privasi.

Sekadar flashback, peneliti dan pembaca mungkin mengenal beberapa teknik keamanan data; (1) Data anonymization methods yang melindungi data pribadi yang bisa diidentifikasi. (2) k-anonymity, sebuah properti umum dari set data yang tak memiliki nama dan tak dapat dibedakan kecuali dengan formula k-1 record lainnya, (3) l-diversity yang merupakan pengembangan dari k-anonymity, (4) t-closeness, (5) differential privacy sebuah teknik memberikan noise dalam penyimpanan data pribadi, juga(5) encryption schemes yang memungkinkan penghitungan (komputasi) dan queries terhadap data yang sudah dienkrispsi, tetapi kurang praktis untuk diaplikasikan secara luas.

Hingga kemudian muncul sistem yang dapat dipertanggungjawabkan yaitu bitcoin yang memungkinkan penggunanya melakukan transfer mata uang (currency) dengan aman tanpa pengatur yang terpusat (centralized), dengan menggunakan open ledger (blockchains) yang terbukti tangguh.

Para peneliti melakukan begitu banyak inovasi dengan blockchains, salah satunya adalah dengan mengombinasikan blockchains dengan off-blockchains storage untuk membangun dan mengelola platform yang fokus pada privasi—kepemilikan data, transparansi dan dapat diaudit, kontrol akses yang baik—yang dapat dijelaskan sebagai berikut.

## Kepemilikan data
Sistem mengenal pengguna sebagai pemilik data dan pelayanan (services) sebagai guest (tamu) yang diberikan izin untuk mengakses data.

Data yang transparan dan dapat di-audit. Setiap pengguna sistem sepatutnya mengetahui data apa saja yang telah digali dari mereka dan bagaimana data itu diakses oleh pelayanan dan sistem.

## Kontrol terhadap akses
Sepatutnya setiap pengguna dapat mengubah serangkaian izin (set of permissions) dan mencabut akses terhadap data yang telah dikoleksi sebelumnya kapan saja sesuai keinginan dari pengguna sistem.  

Penelitian yang dilakukan oleh Guy Zyskind, et al., menerapkan mekanisme yang mampu membenahi sekaligus memperbaiki dialog perizinan yang ada di aplikasi mobile. Sementara interface usernya dibiarkan sama, kebijakan akses kontrolnya disimpan dengan aman di blockchain dan hanya penggunanya yang dapat mengubah apa pun di dalamnya.

## Tipe Transaksi Bitcoin
Blockchain menerima dua tipe transaksi: T-akses—untuk mengontol pengelolaan—dan T-data untuk penyimpanan dan retrieval data. Operasi jaringan ini dapat dengan mudah diintegrasikan ke sebuah alat pengembang software yang berbasis mobile (SDK) yang layanan-layanannya dapat digunakan dalam proses pengembangannya. Bayangkan kejadiannya seperti ini. Seorang pengguna menginstal sebuah aplikasi yang menggunakan platform rancangan peneliti ini untuk menjaga privasi sang pengguna. Ketika user melakukan sign up untuk pertama kalinya, identitas yang baru diberikan antara user dan service (pihak pemberi layanan) sekaligus dengan izin-izin tertentu yang dikaitkan dengan penyelenggaran proses tersebut kepada blockchain di dalam transaksi T-akses. Data yang yang dikumpulkan dari ponsel, misalnya data lokasi dienkripsikan menggunakan kunci enkripsi yang dibagi dan dikirim ke blockchain dalam transaksi T-data, yang merutekannya ke penyimpanan off-blockchain dengan key-value, dengan mengontrol pointer terhadap data di public ledger (pointernya dalah SHD-256 hash dari data).

Baik user maupun service dapat meng-query data dengan menggunakan transaksi T-data dengan pointer (key) yang terhubung kepada keduanya.  Sementara itu, blockchain nantinya akan melakukan verifikasi digital signature baik milik si user maupun si service. Berbeda daripada kebanyakan sistem sebelumnya, akhirnya si user dapat menggonta-ganti permission set-nya dengan sekehendak hati dan kapan saja diperlukan dengan memanfaatkan T-access transaction, termasuk mencabut data yang sebelumnya telah direkam sistem.

## Penutup
Demikianlah bagaimana desentralisasi data private dilakukan dengan menggunakan kombinasi blockchain dan off-blockchain. Karena, sepatutnya user—siapa pun mereka—tidak melibatkan pihak ketiga dalam pengelolaan data yang memberikan kesempatan untuk diserang atau disalahgunakan.

Cuplikan tentang blockchain dan off-blockchain ini merupakan bagian dari jurnal Decentralizing Privacy: Using Blockchain to Protect Personal Data (Guy Zyskin, Oz Nathan, Alex ‘Sandy’ Pentland).

oleh: Roy Sari Milda Siregar, M.Kom