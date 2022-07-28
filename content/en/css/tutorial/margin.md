---
title: "Margin"
description: "margin digunakan untuk membuat jarak pada antar elemen, di bagian luar"
lead: ""
date: 2021-12-06T08:49:31+00:00
lastmod: 2021-12-06T08:49:31+00:00
draft: false
images: []
weight: 100
toc: true
---
## CSS Margins

### Apa Itu CSS Margins?

Properti CSS `margin` digunakan untuk membuat jarak pada antar elemen, di bagian luar.

Margin memiliki beberapa property, antara lain:

- `margin-top` - Untuk mengatur margin atas
- `margin-right` - Untuk mengatur margin kanan
- `margin-bottom` - Untuk mengatur margin bawah
- `margin-left` - Untuk mengatur margin kiri
- `margin` (shorthand) - Untuk mengatur margin di semua arah

Contoh:

```css
p {
  margin-top: 10px;
  margin-right: 20px;
  margin-bottom: 30px;
  margin-left: 40px;
}
```

### Margin Shorthand

Properti `margin` (shorthand) ini, memiliki beberapa parameter nilai.

Contoh pertama:

```css
p {
  margin: 10px;
}
```

Code tersebut memiliki arti yaitu :

- Nilai pertama - Untuk margin semua bagian.

Contoh kedua:

```css
p {
  margin: 10px 20px;
}
```

Code tersebut memiliki arti yaitu :

- Nilai pertama - Untuk margin bagian atas dan bawah.
- Nilai kedua - Untuk margin bagian kanan dan kiri.

Contoh ketiga:

```css
p {
  margin: 10px 20px 30px;
}
```

Code tersebut memiliki arti yaitu :

- Nilai pertama - Untuk margin bagian atas.
- Nilai kedua - Untuk margin bagian kanan dan kiri.
- Nilai ketiga - Untuk margin bagian bawah.

Contoh keempat:

```css
p {
  margin: 10px 20px 30px 40px;
}
```

Code tersebut memiliki arti yaitu :

- Nilai pertama - Untuk margin bagian atas.
- Nilai kedua - Untuk margin bagian kanan.
- Nilai ketiga - Untuk margin bagian bawah.
- Nilai keempat - Untuk margin bagian kiri.
