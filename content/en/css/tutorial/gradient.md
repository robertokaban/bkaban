---
title: "Gradients"
description: "CSS gradient adalah sebuah property dari CSS untuk memberikan sebuah gradasi pada sebuah element, ada 2 property dalam gradient."
lead: ""
date: 2021-12-06T08:49:31+00:00
lastmod: 2021-12-06T08:49:31+00:00
draft: false
images: []
weight: 360
toc: true
---
# CSS GRADIENT

## Apa itu CSS gradient

CSS gradient adalah sebuah property dari CSS untuk memberikan sebuah gradasi pada sebuah element, ada 2 property dalam gradient. yaitu

- linear-gradient
- radial-gradient

## Langsung saja ke demonya agar lebih paham

### linear-gradient

```css
div {
  background-image: linear-gradient(arah, color1, color2, ...);
}
```

### Penjelasan

dalam linear-gradient kita bisa menentukan arah gradient, ada beberapa property dalam linear-gradient yaitu

- direction (bentuk default)
- to right
- to left
- to bottom
- diagonal

### Contoh pengunaan dengan 2 warna

## linear-gradient

### direction

```css
div {
  background-image: linear-gradient(direction, red, yellow);
}
```



---

### to-right

```css
div {
  background-image: linear-gradient(to right, red, yellow);
}
```


---

### to-left

```css
div {
  background-image: linear-gradient(to left, red, yellow);
}
```



### to-top

```css
div {
  background-image: linear-gradient(to top, red, yellow);
}
```



### diagonal

```css
div {
  background-image: linear-gradient(to bottom right, red, yellow);
}
```



### Menggunakan sudut

```css
div {
  background-image: linear-gradient(180deg, red, yellow);
}
```




## radial-gradient

radial-gradient hanya berpusat pada titik tengah, tidak memiliki arah.

### Contoh penggunaan

```css
div {
  background-image: radial-gradient(circle, red, yellow);
}
```



# NOTE

Penggunaan linear-gradient/radial-gradient bisa manampung warna sesuai keinginan kita bisa lebih dari 2 warna.jadi gunakanlah linear-gradient/radial-gradient sesuai kebutuhan kita.


## Referensi (https://www.w3schools.com/css/css3_gradients.asp)
