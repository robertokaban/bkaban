---
title: "Input Output di dalam Python"
description: "Input Output di dalam Python."
lead: "Input Output di dalam Python."
date: 2021-12-06T08:49:31+00:00
lastmod: 2021-12-06T08:49:31+00:00
draft: false
images: []
weight: 270
toc: true
---
Disini kita akan belajar semua fungsi dasar I/O yang tersedia pada Python 3. 
## Print
Cara termudah untuk menghasilkan output adalah dengan menggunakan pernyataan cetak di mana Kita bisa melewati nol atau lebih banyak ekspresi yang dipisahkan dengan koma. Fungsi ini mengubah ekspresi yang Kita berikan ke string dan menulis hasilnya ke output standar sebagai berikut :

`print ("Python adalah bahasa pemrograman yang hebat")`

## Membaca Input Keyboard
Python 2 memiliki dua fungsi built-in untuk membaca data dari input standar, yang secara default berasal dari keyboard. Fungsi ini adalah input() dan raw_input()

Dengan Python 3, fungsi `raw_input()` tidak digunakan lagi. Selain itu, `input()` berfungsi membaca data dari keyboard sebagai string, terlepas dari apakah itu tertutup dengan tanda kutip (‘’ atau ‘”) atau tidak.

## Fungsi Input Python
Fungsi `input([prompt])` sama dengan `raw_input`, kecuali mengasumsikan bahwa input adalah ekspresi Python yang valid dan mengembalikan hasil yang smemungkinkan kita evaluasi.
```
>>> x = input("something:")
something:10

>>> x
'10'

>>> x = input("something:")
something:'10' #entered data treated as string with or without ''

>>> x
"'10'"
```