---
title: "Alamat Ipv4: Pengalamatan Internet Protocol Versi 4"
description: "IP (Internet Protocol) Address Versi 4 sering disebut dengan Alamat IPv4 merupakan sebuah sistem pengalamatan 32-bit yang digunakan di dalam protokol jaringan TCP/IP sebagai alamat identifikasi untuk tiap host dalam jaringan Internet."
excerpt: "IP (Internet Protocol) Address Versi 4 sering disebut dengan Alamat IPv4 merupakan sebuah sistem pengalamatan 32-bit yang digunakan di dalam protokol jaringan TCP/IP sebagai alamat identifikasi untuk tiap host dalam jaringan Internet. "
date: 2012-07-01T13:54:26+07:00
lastmod: 2012-07-01T13:54:26+07:00
draft: false
weight: 50
images: []
categories: ["Teknologi", "Networking" ]
tags: ["IPv4", "Internet Protocol", "IP Internet"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
---
## IP Address (Internet Protocol) Versi 4
IP (Internet Protocol) Address Versi 4 sering disebut dengan Alamat IPv4 merupakan sebuah sistem pengalamatan 32-bit yang digunakan di dalam protokol jaringan TCP/IP sebagai alamat identifikasi untuk tiap host komputer dalam jaringan Internet. 

IPv4 disebut dengan sistem pengalamatan 32 bit karena total jumlah bit ip dalam biner adalah sebanyak 32 bit yang dibagi kedalam 4 oktet/blok. Dalam penerapannya dan untuk lebih mudah mengingatnya ke empat oktet/blok tersebut di representasikan kedalam bentuk desimal dan dipisahkan dengan.(titik). 

Pengalamatan IPv4 berbeda dengan pengalamatan pada IPv6 yang menggunakan skema 128 bit dan direpresentasikan dalam bentuk heksadesimal. 

## Contoh IPv4
Contoh format IPv4  seperti `192.168.0.1` . 
Dikonversi kedalam biner mejadi `11000000.10101000.00000000.00000001` (total 32 bit dan dipisahkan oleh tanda titik) jadi maksimal format pengalamatan IPv4 adalah `255.255.255.255` atau dalam biner `11111111.11111111.11111111.11111111`. Lebih lengkapnya dapat dilihat pada tabel dibawah;

Ket	| Oktet 1(W)	| Oktet 2 (X)	| Oktet3 (Y)	| Oktet 4 (Z)
-|-|-|-|-
Format IP(Decimal) |	192 |	168 |	0 |	1 |
Format IP(Biner) |	11000000 | 	10101000 |	00000000 |	00000001 |
Max IP |	255 |	255 |	255 |	255 |
Max IP(Bin) |	11111111 |	11111111 |	11111111 |	11111111 |
Total Max Bit |	32 bit |

Alamat IP versi 4 dibagi ke dalam beberapa kelas, yang menjadi pembeda kelas IP v4 adalah pola biner yang terdapat dalam oktet pertama /high-order bit

## Pembagian kelas IPv4
Kelas Alamat	| Oktet 1(W) |	Digunakan oleh |	Bagian untuk Network Indentifier |	Bagian untuk Host Indentifier |	Jlh.Jaringan Maksimum	| Jlh. Host dalam satu jaringan(max)
-|-|-|-|-|-|-
Kelas A	 | 1–126	| Alamat unicast untuk jaringan skala besar  | 	W	 | X.Y.Z	 | 126  | 	16,777,214
Kelas B	 | 128–191	| Alamat unicast untuk jaringan skala menengah hingga skala besar  | 	W.X	 | Y.Z	 | 16,384	 |  65,534
Kelas C	 | 192–223	| Alamat unicast untuk jaringan skala kecil  | 	W.X.Y	 | Z	 | 2,097,152 |  	 254
Kelas D  | 	224-239	| Alamat multicast (bukan alamat unicast)	 | Multicast IP Address  | 	Multicast IP Address	 | Multicast IP Address	 | Multicast IP Address
Kelas E | 	240-255	| Direservasikan;umumnya digunakan sebagai alamat percobaan(eksperimen); (bukan alamat unicast) | 	Dicadangkan;  | eksperimen	Dicadangkan;  | eksperimen	Dicadangkan;  | eksperimen	Dicadangkan; eksperimen

Alamat dengan oktet awal 127 tidak diizinkan, karena digunakan untuk mekanisme Interprocess Communication (IPC) di dalam mesin yang bersangkutan atau biasa juga disebut localhost.

## Alamat unicast
Setiap antarmuka (interface) jaringan yang menggunakan protokol TCP/IP harus diidentifikasikan dengan menggunakan sebuah alamat logis yang unik, yang disebut dengan alamat unicast (unicast address). Alamat unicast inilah yang harus digunakan oleh semua host TCP/IP agar dapat saling terhubung. 

Komponen alamat ini terbagi menjadi dua jenis, yakni alamat host (host identifier) dan alamat jaringan (network identifier). 

## Network Identifier/NetID
Network Identifier/NetID atau Network Address (alamat jaringan), merupakan alamat yang digunakan khusus untuk mengidentifikasikan alamat jaringan di mana host tersebut berada. 

Semua sistem di dalam sebuah jaringan fisik yang sama harus memiliki alamat network identifier yang sama. Network identifier juga harus bersifat unik dalam sebuah jaringan Internet

## Host Identifier/HostID
Host Identifier/HostID atau Host address (alamat host), merupakan alamat yang digunakan khusus untuk mengidentifikasikan alamat host (dapat berupa workstation, server atau sistem lainnya yang berbasis teknologi TCP/IP) di dalam jaringan. 

Alamat host identifier  harus bersifat unik di dalam network identifier/segmen jaringan di mana ia berada. Sebuah alamat unicast dibedakan dengan alamat lainnya menggunakan skema __subnet mask__ (akan bahas mengenai subnet mask pada artikel lain).

## Intranet dan Internet
Sebuah intranet (jaringan local) yang tidak terkoneksi ke Internet, semua alamat IP dalam ruangan kelas alamat unicast dapat digunakan, tetapi jika koneksi dilakukan menggunakan teknik routing ataupun menggunakan proxy server maka ada dua jenis alamat yang dapat digunakan di dalam Internet, yaitu public address dan private address . 

## Public Address
Public Address adalah alamat-alamat yang berisi beberapa buah network identifier yang telah dijamin unik (artinya, tidak ada dua host yang menggunakan alamat yang sama) jika intranet tersebut telah terhubung ke Internet.

Pada kasus Internet, setiap node di dalam sebuah jaringan yang terhubung keInternet akan membutuhkan sebuah alamat yang unik secara global terhadap Internet. Karena perkembangan Internet yang sangat amat pesat, organisasi-organisasi yang menghubungkan intranet miliknya ke Internet membutuhkan sebuah alamat publik untuk setiap node di dalam intranet miliknya tersebut. Tentu saja, hal ini akan membutuhkan sebuah alamat publik yang unik secara global.

## Private Address
Ketika menganalisis kebutuhan pengalamatan yang dibutuhkan oleh sebuah organisasi, para desainer Internet memiliki pemikiran yaitu kebanyakan host di dalam intranet organisasi tersebut tidak harus terhubung secara langsung ke Internet. 

Host-host yang membutuhkan sekumpulan layanan Internet, seperti halnya akses terhadap web atau e-mail, biasanya mengakses layanan Internet tersebut melalui gateway yang berjalan di atas lapisan aplikasi seperti proxy server atau e-mail server. 

Hasilnya, kebanyakan organisasi hanya membutuhkan alamat publik dalam jumlah sedikit saja yang nantinya digunakan oleh node-node tersebut (hanya untuk proxy, router, firewall) yang terhubung secara langsung ke Internet.


Untuk host-host di dalam sebuah organisasi yang tidak membutuhkan akses langsung ke Internet, alamat-alamat IP yang bukan duplikat dari alamat publik yang telah ditetapkan mutlak dibutuhkan. 

Untuk mengatasi masalah pengalamatan ini, para desainer Internet mereservasikan sebagian ruangan alamat IP dan menyebut bagian tersebut sebagai ruangan alamat pribadi. Sebuah alamat IP yang berada di dalam ruangan alamat pribadi tidak akan digunakan sebagai sebuah alamat publik. 

Alamat IP yang berada di dalam ruangan alamat pribadi dikenal juga dengan alamat pribadi atau Private Address dan jaringan yang menggunakan alamat IP privat disebut juga dengan jaringan privat atau private network. 

Karena alamat-alamat IP di dalam ruangan alamat pribadi tidak akan ditetapkan oleh Internet Network Information Center (InterNIC)  (atau badan lainnya yang memiliki otoritas) sebagai alamat publik, maka tidak akan pernah ada rute yang menuju ke alamat-alamat pribadi tersebut di dalam router Internet. 

Kompensasinya, alamat pribadi tidak dapat dijangkau dari Internet. Oleh karena itu, semua lalu lintas dari sebuah host yang menggunakan sebuah alamat pribadi harus mengirim request tersebut ke sebuah gateway (seperti halnya proxy server), yang memiliki sebuah alamat publik yang valid, atau memiliki alamat pribadi yang telah ditranslasikan ke dalam sebuah alamat IP publik yang valid dengan menggunakan Network Address Translator (NAT) sebelum dikirimkan ke Internet.

## Jenis Private Address
Berikut beberapa jenis Private Address;

### 10.0.0.0/8
Jaringan pribadi 10.0.0.0/8 memiliki 24 bit host yang dapat digunakan untuk skema subnetting di dalam sebuah organisasi privat. alamat IP yang valid dari 10.0.0.1 hingga 10.255.255.254

### 172.16.0.0/12
Jaringan pribadi 172.16.0.0/12 dapat diinterpretasikan sebagai sebuah block dari 16 network identifier kelas B atau sebagai sebuah ruangan alamat yang memiliki 20 bit yang dapat ditetapkan sebagai host identifier, yang dapat digunakan dengan menggunakan skema subneting di dalam sebuah organisasi privat. Alamat jaringan privat 172.16.0.0/12 mengizinkan alamat-alamat IP yang valid dari 172.16.0.1 hingga 172.31.255.254.

### 192.168.0.0/16
Jaringan pribadi 192.168.0.0/16 dapat diinterpretasikan sebagai sebuah block dari 256 network identifier kelas C atau sebagai sebuah ruangan alamat yang memiliki 16 bit yang dapat ditetapkan sebagai host identifier yang dapat digunakan dengan menggunakan skema subnetting  apapun di dalam sebuah organisasi privat. Alamat jaringan privat192.168.0.0/16 dapat mendukung alamat-alamat IP yang valid dari 192.168.0.1 hingga 192.168.255.254.

### 169.254.0.0/16
Alamat IP yang mungkin dalam ruang alamat ini adalah 169.254.0.1 hingga 169.254.255.254, dengan alamat subnet mask 255.255.0.0. Alamat ini digunakan sebagai alamat IP privat otomatis (dalam Windows, disebut denganAutomatic Private Internet Protocol Addressing (APIPA)).
Hasil dari penggunaan alamat-alamat privat ini oleh banyak organisasi adalah menghindari kehabisan dari alamat publik, mengingat pertumbuhan Internet yang sangat pesat.



## Broadcast Address
Alamat Broadcast, merupakan alamat IPv4 yang didesain agar diproses oleh setiap node IP dalam segmen jaringan yang sama. Alamat broadcast untuk IP versi 4 digunakan untuk menyampaikan paket-paket data "satu-untuk-semua". 

Jika sebuah host pengirim yang hendak mengirimkan paket data dengan tujuan alamat broadcast, maka semua node yang terdapat di dalam segmen jaringan tersebut akan menerima paket tersebut dan memprosesnya. Berbeda dengan alamat IP unicast atau alamat IP multicast, alamat IP broadcast hanya dapat digunakan sebagai alamat tujuan saja, sehingga tidak dapat digunakan sebagai alamat sumber.


## Multicast Address
Alamat multicast merupakan alamat IPv4 yang didesain agar diproses oleh satu atau beberapa node dalam segmen jaringan yang sama atau berbeda. Alamat IP Multicast (Multicast IP Address) adalah alamat yang digunakan untuk menyampaikan satu paket kepada banyak penerima. 

Dalam sebuah intranet yang memiliki alamat multicast IPv4, sebuah paket yang ditujukan ke sebuah alamat multicast akan diteruskan oleh router ke subjaringan di mana terdapat host-host yang sedang berada dalam kondisi "listening" terhadap lalu lintas jaringan yang dikirimkan ke alamat multicast tersebut. 

Dengan cara ini, alamat multicast pun menjadi cara yang efisien untuk mengirimkan paket data dari satu sumber ke beberapa tujuan untuk beberapa jenis komunikasi.
