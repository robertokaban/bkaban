---
title: "Image Fit"
description: "Property CSS `object-fit` digunakan untuk menentukan bagaimana tag `<img>` atau `<video>` diubah ukurannya agar sesuai dengan wadah atau containernya."
lead: ""
date: 2021-12-06T08:49:31+00:00
lastmod: 2021-12-06T08:49:31+00:00
draft: false
images: []
weight: 480
toc: true
---
## CSS object-fit

### Apa itu CSS object-fit?

Property CSS `object-fit` digunakan untuk menentukan bagaimana tag `<img>` atau `<video>` diubah ukurannya agar sesuai dengan wadah atau containernya.

Beberapa value dari `object-fit` diantaranya :

- `fill`
- `contain`
- `cover`
- `scale-down`
- `none`

### Studi kasus :

**Gambar yang akan digunakan :**


### object-fit: cover;

Gambar akan mempertahankan aspek rasionya dan memenuhi dimensi yang diberikan, lalu gambar akan dipotong agar menyesuaikan wadah atau containernya :

### Sintaksis :

```html
<img class="cover" src="natures.jpg" alt="..." />
```

```css
img {
	width: 300px;
	height: 400px;
	border: 2px solid blue;
}

.cover {
	object-fit: cover;
}
```


### object-fit: fill;

Gambar akan diubah ukurannya untuk memenuhi dimensi yang diberikan. Jika perlu, gambar akan direnggangkan agar menyesuaikan wadah atau containernya :

### Sintaksis :

```html
<img class="fill" src="natures.jpg" alt="..." />
```

```css
img {
	width: 300px;
	height: 400px;
	border: 2px solid blue;
}

.fill {
	object-fit: fill;
}
```


### object-fit: contain;

Gambar akan mempertahankan aspek rasionya, tetapi diubah ukurannya agar sesuai dengan dimensi yang diberikan :

### Sintaksis :

```html
<img class="contain" src="natures.jpg" alt="..." />
```

```css
img {
	width: 300px;
	height: 400px;
	border: 2px solid blue;
}

.contain {
	object-fit: contain;
}
```



### object-fit: scale-down;

Gambar akan diperkecil ke versi terkecil dari gambar tersebut :

### Sintaksis :

```html
<img class="scale-down" src="natures.jpg" alt="..." />
```

```css
img {
	width: 300px;
	height: 400px;
	border: 2px solid blue;
}

.scale-down {
	object-fit: scale-down;
}
```


### object-fit: none;

Gambar tidak akan diubah ukurannya dan tetap dengan ukuran aslinya :

### Sintaksis :

```html
<img class="none" src="natures.jpg" alt="..." />
```

```css
img {
	width: 300px;
	height: 400px;
	border: 2px solid blue;
}

.none {
	object-fit: none;
}
```



### Referensi

Untuk referensi lengkapnya, kalian bisa mengunjungi website berikut:

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)
- [W3Schools](https://www.w3schools.com/css/css3_object-fit.asp)
