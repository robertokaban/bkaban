---
title: "Pengenalan HTML"
description: "Pengertian HTML."
lead: "HTML (Hypertext Markup Language) merupakan bahasa markup yang digunakan untuk menentukan konten dan
struktur halaman web."
date: 2021-12-06T08:49:31+00:00
lastmod: 2021-12-06T08:49:31+00:00
draft: false
images: []
weight: 10
toc: true
---

## Apa itu HTML?

- HTML adalah *HyperText Markup Language*.
- HTML adalah bahasa markup standard untuk membuat halaman Web.
- HTML mendeskripsikan struktur halaman Web.
- HTML terdiri dari serangkaian elemen.
- Elemen HTML memberi tahu browser cara menampilkan konten.
- Elemen HTML memberi label potongan konten seperti "ini adalah judul", "ini adalah paragraf", "ini adalah tautan", dll.

## Penulisan Tag HTML
Elemen dalam dokumen HTML ditunjukkan dengan menggunakan tag.
Penulisan tag HTML seperti di bawah ini:

```html
<tag>text</tag>
```

Beberapa tag memiliki teks tambahan di dalamnya yang memberikan informasi tambahan tentang tag; disebut dengan atribut.

```html
<tag atribut1="nilai1" atribut2="nilai2"> text </tag>
```

Nama tag boleh ditulis dengan huruf kecil, huruf kapital, ataupun kombinasi antara huruf kecil dan huruf kapital.

## HTML Editor
Teks editor untuk membuat file HTML diantaranya:
- ![Notepad++](https://img.shields.io/badge/Notepad++-90E59A.svg?style=for-the-badge&logo=notepad%2B%2B&logoColor=black)
- ![SublimeText](https://img.shields.io/badge/sublime_text-%23575757.svg?&style=for-the-badge&logo=sublime-text&logoColor=important)
- ![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)


## Contoh HTML
``` html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html
```


**Penjelasan contoh:**

- Deklarasi `<!DOCTYPE html>` mendefinisikan bahwa dokumen ini adalah dokumen HTML5
- Elemen `<html>` adalah elemen root dari halaman HTML
- Elemen `<head>` berisi informasi meta tentang halaman HTML
- Elemen `<title>` menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul browser atau di tab halaman)
- Elemen `<body>` mendefinisikan isi dokumen, dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, hyperlink, tabel, daftar, dll.
- Elemen `<h1>` mendefinisikan heading besar
- Elemen `<p>` mendefinisikan paragraf.




## Elemen HTML?

Elemen HTML didefinisikan oleh tag awal, beberapa konten, dan tag akhir:
```html
<tagname>Konten ada di sini...</tagname>
```

Elemen HTML adalah segalanya mulai dari tag awal hingga tag akhir:
```html
<h1>Judul Pertama Saya</h1>
<p>Paragraf pertama saya.</p>
```

|     | Tag Awal |     Konten Elemen     | Tag terakhir |
| :-: | :------: | :-------------------: | ------------ |
| 01  |   `<h1>`   | Heading Pertama Saya  | `</h1>`        |
| 02  |   `<p>`    | Paragraf Pertama Saya | `</p>`         |
| 03  |   `<br>`   |         None          | None         |

> **Catatan:** Beberapa elemen HTML tidak memiliki konten (seperti elemen `<br>`). Elemen-elemen ini disebut elemen kosong. Elemen kosong tidak memiliki tag akhir!

## Web Browser

Tujuan browser web (Chrome, Edge, Firefox, Safari) adalah untuk membaca dokumen HTML dan menampilkannya dengan benar.

Browser tidak menampilkan tag HTML, tetapi menggunakannya untuk menentukan cara menampilkan dokumen

## Sejarah HTML

Sejak awal World Wide Web, ada banyak versi HTML:

|     | Tahun |                  Versi                  |
| :-: | :---: | :-------------------------------------: |
| 01  | 1989  |      Tim Berners-Lee invented www       |
| 02  | 1991  |      Tim Berners-Lee invented HTML      |
| 03  | 1993  |       Dave Raggett drafted HTML+        |
| 04  | 1995  |   HTML Working Group defined HTML 2.0   |
| 05  | 1997  |      W3C Recommendation: HTML 3.2       |
| 06  | 1999  |      W3C Recommendation: HTML 4.01      |
| 07  | 2000  |      W3C Recommendation: XHTML 1.0      |
| 08  | 2008  |     WHATWG HTML5 First Public Draft     |
| 09  | 2012  |      WHATWG HTML5 Living Standard       |
| 10  | 2014  |        W3C Recommendation: HTML5        |
| 11  | 2016  | W3C Candidate Recommendation: HTML 5.1  |
| 12  | 2017  | W3C Recommendation: HTML5.1 2nd Edition |
| 13  | 2017  |       W3C Recommendation: HTML5.2       |

Tutorial ini mengikuti standar HTML5 terbaru.
