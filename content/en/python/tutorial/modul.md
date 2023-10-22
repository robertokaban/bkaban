---
title: "Modul di dalam Python"
description: "Modul di dalam Python."
lead: "Modul di dalam Python."
date: 2021-12-06T08:49:31+00:00
lastmod: 2021-12-06T08:49:31+00:00
draft: false
images: []
weight: 260
toc: true
---
Modul memungkinkan Kita mengatur kode Python secara logis. Mengelompokkan kode terkait ke dalam modul membuat kode lebih mudah dipahami dan digunakan. Modul adalah objek Python dengan atribut yang diberi nama yang bisa Kita bind dan dijadikan referensi.

Secara sederhana modul adalah file yang terdiri dari kode Python. Modul dapat mendefinisikan fungsi, kelas dan variabel. Modul juga bisa menyertakan kode yang bisa dijalankan “runable”.

Berikut adalah contoh modul sederhana pada Python :
```
def print_func( par ):
   print "Halo : ", par
   return
```
## Import Statement
Kita dapat menggunakan file sumber Python apapun sebagai modul dengan mengeksekusi pernyataan impor di file sumber Python lainnya. Impornya memiliki sintaks berikut.

Ketika interpreter menemukan sebuah pernyataan import, ia mengimpor modul jika modul tersebut ada di jalur pencarian. Jalur pencarian adalah daftar direktori yang ditafsirkan juru bahasa sebelum mengimpor modul. Misalnya, untuk mengimpor modul hello.py, Kita perlu meletakkan perintah berikut di bagian atas script.

# Import module support
import support

# Anda bisa memanggil fungsi defined sebagai berikut
support.print_func("Andy")