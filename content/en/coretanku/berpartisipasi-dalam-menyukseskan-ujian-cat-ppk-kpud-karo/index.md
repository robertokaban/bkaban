---
title: "Berpartisipasi dalam menyukseskan ujian CAT PPK KPUD Karo"
description: "Ujian CAT (Computer Assisted Test) dilaksakanan oleh Komisi Pemilihan Umum Daerah (KPUD) seluruh Indonesia untuk menyeleksi calon Panitia Pemilihan Kecamatan (PPK). Di kabupaten Karo, kebetulan KPUD Karo bekerjasama dengan Kampus Institut Teknologi dan Bisnis Indonesia Kabanjahe."
excerpt: "Ujian CAT (Computer Assisted Test) dilaksakanan oleh Komisi Pemilihan Umum Daerah (KPUD) seluruh Indonesia untuk menyeleksi calon Panitia Pemilihan Kecamatan (PPK). Di kabupaten Karo, kebetulan KPUD Karo bekerjasama dengan Kampus Institut Teknologi dan Bisnis Indonesia Kabanjahe."
date: 2022-12-08T23:30:55+07:00
lastmod: 2022-12-08T23:30:55+07:00
draft: false
weight: 50
images: []
categories: ["Blog"]
tags: ["Kegiatanku"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
toc: true
---
## Pengantar
Ujian CAT (Computer Assignment Test) dilaksakanan oleh Komisi Pemilihan Umum Daerah (KPUD) seluruh Indonesia untuk menyeleksi calon Panitia Pemilihan Kecamatan (PPK). Di kabupaten Karo, kebetulan KPUD Karo bekerjasama dengan Kampus Institut Teknologi dan Bisnis Indonesia Kabanjahe untuk support penyelenggaran CAT khususnya dalam instalasi jaringan dan aplikasi.

Ujian CAT di kab. Karo dilaksanakan selama dua hari yaitu 6 - 7 Desember 2022, dengan lima gelombang setiap harinya. Setiap gelombang memiliki durasi waktu ujian selama 90 menit.

Agenda kegiatan ini dapat di bilang mendadak, kami mendapatkan informasi dan meninjau kelengkapan lokasi ujian pada hari Jumat 2 desember 2022. Saya dan seorang teman ditugaskan kampus untuk memastikan kegiatan ini berjalan dengan lancar. Dari kebutuhan dan penjelasan yang disampaikan pihak KPU kab. Karo, saya berpikir proses instalasi jaringan dan aplikasi tidak rumit, dan memang betul.

Ujian akan dilaksanakan di SMP Negeri 1 Kabanjahe dengan menggunakan fasilitas lab komputer sekolah tersebut. Dari pemantauan ke lokasi ujian dan arahan untuk minimal spesifikasi komputer sudah memadai.

Ujian akan dilaksanakan dalam jaringan LAN (Local), dan terkoneksi ke satu server. Dari spesifikasi yang dibutuhkan pada saat brief secara online, Komputer server minimal memiliki RAM 8GB, Core i5 dan koneksi kabel LAN 100Mbps atau 1Gps dari client. Komputer pada lokasi tes sudah memiliki spesifikasi tersebut, dan jumlah client juga sudah mencukupi (40 client).

Sistem digunakan berbasis web, dengan framework PHP (laravel) dan MySQL/MariaDB sebagai database. Tim dari KPU juga menyarankan intalasi pake XAMPP (software bundle Apache, MariaDB) untuk menjalankan Aplikasi.

Berdasarkan ujicoba pada H-1 sebelum kegiatan dengan menggunakan soal dummy hasilnya lancar, (soal real dikirim 3 jam sebelum pelaksanaan).

## Kegiatan Hari pertama
Ketika sudah setting sesi dan peserta ujian, sesi 1 dan sesi 2 bisa di bilang lancar dengan peserta sekitar 35 orang per sesi. Pada sesi 3, performance server sudah menurun sehingga berakibat sedikit lambat juga pada client, tau sendirilah servernya sekolah adalah PC sever, bukan server yang sebenarnya🙂.

## Kegiatan Hari kedua
Hari kedua, kami menggunakan 2 PC server yang mengelola 20 client setiap servernya, dan hasilnya lancar.



<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgRU8ATmkqBMHFcGSvmzxgPGVf5bTZb6NLKMzjGIEpLLUqg21ITmwNBJd5iPJ2RVV2OtRI8FMtEEZXctCBe7j8-0zP4XIgURlfLl2ulqn1s-7bxfTPvdpc8dLZpx9dV976shWwREHTtEWTWba11sC8I3XS-mX0QrwXDA1txBXLBaqR63QxeovCH_bC1/w640-h480/IMG20221205140737.jpg' width="100%" class="border-0 rounded">

<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg5fa_j5jORMz_BH_e7ca5WWdjLoO2iWcSxEOi-Ytr6t8Rc2sW-QuvNZ9XfnGgUSEuLsXs87L0vrFj28IUn_mkfluprh-hrDdl-DL8A-RBdJtnPhBVjMWT60JtHnQ4v_6mVMHlf6mUX1CxD17VzRJv1VY7CiTdLGdocgEmUyaPYLp5mZ0DT29B2ai69/w304-h640/IMG20221206065048.jpg' width="100%" class="border-0 rounded">

<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg7MWXj_lJStzj7DsY9bb6osCelBHIK3fo3CqzhPi6rzKWGF-aKWkahvl2EV6u8c4KX_SnxxDGP3jlZGn19mCH-QZ2HVOMLji-rxBNIqxhoII1qur1E4eBXoMikoxOsOgpv_vKUGYXUDsePvHIGRJD6kj67jblX5QKwLrSP9jh6Qi5w0Y49hyqCTWcP/w640-h360/Ujian-CAT-Seleksi-PPK-Karo-Pemilu-2024.jpg' width="100%" class="border-0 rounded">


<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgzzv0ybmqbJ6AmGncBj49Sv4yPeME6te7-7JoweARwwRYewDknSbEB2EUahFN5A3ynmBNYjKYN-Ve1nPE78f3dN2weugy8HwsRK67ZCXgW-L7MrIuFRM_UehYDxNNkBFHfi9Zr4U3yMoFy4U0YZhyshsujidq80HFPTu8n9kJmp5aZj1XC_INKSp3X/w640-h427/WakilBupatiKaro_071222_2-fill-300x200.jpg' width="100%" class="border-0 rounded">


<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhS8juoADSeLTfc5B3PlFC8t0_69p0-VCcxEiLFbFaHw1-RaaT_QQ125v_14q6gXUYXFBS5EgIN88FW2M3aTXXy0GRDRdOWMxtIX5VGPwKDHdg4tsAkv7WUvYCWABIiFNkef6yxg-JItVsndPefgKLyuHjDZYDqqoknaqmbWuq2kztuG-hNh_kQRuLF/w640-h427/WakilBupatiKaro_071222_3-fill-300x200.jpg' width="100%" class="border-0 rounded">

