---
title: "Exception"
description: "Exception dalam Python."
lead: "Exception dalam Python."
date: 2021-12-06T08:49:31+00:00
lastmod: 2021-12-06T08:49:31+00:00
draft: false
images: []
weight: 280
toc: true
---
Python menyediakan dua fitur yang sangat penting untuk menangani kesalahan tak terduga dalam program Python Anda dan menambahkan kemampuan debugging di dalamnya.

## Exception Handling
Assertions Exception adalah sebuah peristiwa, yang terjadi selama pelaksanaan program yang mengganggu aliran normal instruksi program. Secara umum, ketika skrip Python menemukan situasi yang tidak dapat diatasi, hal itu menimbulkan pengecualian. Exception adalah objek Python yang mewakili kesalahan.
Ketika skrip Python menimbulkan Exception, maka harus menangani Exception begitu saja sehingga berhenti dan berhenti.

## Standard Exceptions
Nama | Penjelasan
-|-
Exception	| Kelas dasar untuk semua pengecualian / exception
StopIteration	| Ditampilkan ketika metode (iterator) berikutnya dari iterator tidak mengarah ke objek apa pun.
SystemExit	| Ditampilkan oleh fungsi sys.exit ().
StandardError	| Kelas dasar untuk semua pengecualian built-in kecuali StopIteration dan SystemExit.
ArithmeticError	| Kelas dasar untuk semua kesalahan yang terjadi untuk perhitungan numerik.
OverflowError	| Ditampilkan saat perhitungan melebihi batas maksimum untuk tipe numerik.
FloatingPointError	| Ditampilkan saat perhitungan floating point gagal.
ZeroDivisonError	| Ditampilkan saat pembagian atau modulo nol dilakukan untuk semua tipe numerik.
AssertionError	| Ditampilkan jika terjadi kegagalan pernyataan Assert.
AttributeError	| Ditampilkan jika terjadi kegagalan referensi atribut atau penugasan.
EOFError	| Ditampilkan bila tidak ada input dari fungsi raw_input () atau input () dan akhir file tercapai.
ImportError	| Ditampilkan saat sebuah pernyataan impor gagal.
KeyboardInterrupt	| Ditampilkan saat pengguna menyela eksekusi program, biasanya dengan menekan Ctrl + c.
LookupError	| Kelas dasar untuk semua kesalahan pencarian.
IndexError	| Ditampilkan saat sebuah indeks tidak ditemukan secara berurutan.
KeyError	| Ditampilkan saat kunci yang ditentukan tidak ditemukan dalam kamus.
NameError	| Ditampilkan saat pengenal tidak ditemukan di namespace lokal atau global.
UnboundLocalError	| Ditampilkan saat mencoba mengakses variabel lokal dalam suatu fungsi atau metode namun tidak ada nilai yang ditugaskan padanya.
EnvironmentError	| Kelas dasar untuk semua pengecualian yang terjadi di luar lingkungan Python.
IOError	| Ditampilkan saat operasi input / output gagal, seperti pernyataan cetak atau fungsi open () saat mencoba membuka file yang tidak ada.
OSError	| Dibangkitkan untuk kesalahan terkait sistem operasi.
SyntaxError	| Ditampilkan saat ada kesalahan dengan sintaks Python.
IndentationError	| Ditampilkan saat indentasi tidak ditentukan dengan benar.
SystemError	| Ditampilkan saat penafsir menemukan masalah internal, namun bila kesalahan ini ditemui juru bahasa Python tidak keluar.
SystemExit	| Ditampilkan saat juru bahasa Python berhenti dengan menggunakan fungsi sys.exit (). Jika tidak ditangani dalam kode, menyebabkan penafsir untuk keluar.
TypeError	| Ditampilkan saat operasi atau fungsi dicoba yang tidak valid untuk tipe data yang ditentukan.
ValueError	| Ditampilkan ketika fungsi bawaan untuk tipe data memiliki jenis argumen yang valid, namun argumen tersebut memiliki nilai yang tidak valid yang ditentukan.
RuntimeError	| Ditampilkan saat kesalahan yang dihasilkan tidak termasuk dalam kategori apa pun.
NotImplementedError	| Ditampilkan ketika metode abstrak yang perlu diimplementasikan di kelas warisan sebenarnya tidak dilaksanakan.