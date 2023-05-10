---
title: "Keamanan cloud computing: Manfaat, Resiko dan Kontrol"
description: "Keamanan cloud computing: Manfaat, Resiko dan Kontrol. Cloud computing atau komputasi awan  menyajikan model baru untuk layanan teknologi informasi yang melibatkan jaringan secara keseluruhan untuk melayani permintaan akses bersama yang terukur secara dinamis dan elastis serta memanfaatkan sumber daya virtual."
excerpt: "Cloud computing atau komputasi awan  menyajikan model baru untuk layanan teknologi informasi yang melibatkan jaringan secara keseluruhan untuk melayani permintaan akses bersama yang terukur secara dinamis dan elastis serta memanfaatkan sumber daya virtual."
date: 2012-04-16T02:55:26+07:00
lastmod: 2012-04-16T02:55:26+07:00
draft: true
weight: 50
images: []
categories: ["Cloud Computing"]
tags: ["Cloud Computing", "Kemanan Cloud Computing", "Manfaat Cloud Computing", "Resiko Cloud Computing"]
contributors: ["Roberto Kaban"]
pinned: false
homepage: false
---

## Abstrak
Cloud computing atau komputasi awan  menyajikan model baru untuk layanan teknologi informasi yang melibatkan jaringan secara keseluruhan untuk melayani permintaan akses bersama yang terukur secara dinamis dan elastis serta memanfaatkan sumber daya virtual. Cloud computing memiliki potensi untuk memperbaiki cara bisnis serta menawarkan kecepatan akses, fleksibilitas, skalabilitas dan efisiensi biaya. Meskipun cloud computing memberikan manfaat yang menarik dan hemat biaya serta memberikan berbagai pilihan penyimpanan data di bagian teknologi informasi untuk melakukan ekspansi, tetapi memberikan risiko dan peluang baru untuk eksploitasi bidang keamanan. Standar, kebijakan dan kontrol dibutuhkan untuk membantu manajemen dalam melindungi dan melakukan pengamanan data pada sistem. Manajemen harus memahami dan menganalisis  risiko cloud computing untuk melindungi sistem dan data dari eksploitasi keamanan. Fokus dari makalah ini adalah pada pencegahan terhadap risiko keamanan cloud computing sebagai dasar langkah untuk memastikan lingkungan cloud computing yang aman.

Kata kunci: cloud computing; komputasi awan; manfaat; kontrol; risiko.

## I. PENDAHULUAN 
Selama tahun 1990-an, pusat penyimpanan data, penggunaan daya, pendinginan dan beban usaha meningkat dan mengarah pada adopsi terhadap grid computing atau sistem terdistribusi  dan virtualisasi. Melalui sistem terdistribusi pengguna dapat menghubungkan dan menggunakan layanan secara bersama. Dengan memungkinkannya  infrastruktur untuk virtualisasi dan berbagi layanan ke seluruh konsumen, penyedia jasa merasa perlu untuk mengubah model bisnis mereka dengan menyediakan layanan jarak jauh yang lebih rendah biaya. 

Sebagai layanan yang menjadi lebih dan lebih terdistribusi, kebutuhan untuk integrasi dan manajemen jasa-jasa menjadi penting dan menyebabkan munculnya layanan berorientasi  arsitektur atau service-oriented architecture  (SOA).   Cloud computing  merupakan pengembangan  dari service-oriented architecture  (SOA) untuk menyediakan sumber daya IT sebagai sebuah layanan. Cloud computing memungkinkan layanan secara cepat dan elastis baik untuk sekala besar maupun skala kecil serta konsumen yang menggunakan layanan sesuai kebutuhan dan yang dibayar juga sesuai dengan sumber daya yang digunakan dalam infrastuktur jaringan. 

Saat ini cloud computing mengubah struktur pelayanan bidang Teknologi Informasi kedalam model layanan jasa. Keuntungan bagi bisnis dan TI termasuk mengurangi biaya, skalabilitas, fleksibilitas, pemanfaatan kapasitas, mobilitas dan tingkat efisiensi yang lebih tinggi. Diprediksikan terjadi pertumbuhan  dan perkembangan besar-besaran untuk implementasi dari layanan cloud computing, termasuk cloud computing untuk layanan pasar yang mencapai antara $ 150 Milyar pada tahun 2014 [1-2] dan $ 222.5 Milyar pada tahun 2015 [3].

Seperti permasalahan teknologi pada umumnya dalam cloud computing juga menimbulkan banyak masalah termasuk keamanan, manajemen dan kontrol, dampak untuk kelangsungan bisnis, peraturan dan perundang-undangan serta kurangnya standar dan pedoman implementasi. Dalam rangka meminimalkan dampak kekhawatiran terhadap resiko ini,  mitigasi terhadap risiko adalah penting jika organisasi ingin mengambil keuntungan dan manfaat dari penggunaan teknologi cloud computing, sekaligus melindungi dan menjaga sistem dan data. Manajemen ditekankan  untuk memastikan mitigasi terhadap resiko supaya mengurangi dampak pada bisnis. Strategi mitigasi risiko dan pelaksanaan kontrol ke tingkat yang lebih lanjut termasuk  rumit karena standar dan pedoman yang berhubungan dengan keamanan cloud computing belum ada [4-6]. 


## II. LATAR BELAKANG
### A. Apa itu cloud computing
Lingkungan Teknologi Informasi berevolusi dari mainframe ke client server, internet, virtualisasi dan cloud computing. Cloud computing menyediakan penggunaan sumber daya secara bersama sama ataupun sharing (meliputi jaringan, perangkat lunak, pengolahan data, penyimpanan informasi).  Penggunaan cloud computing sama halnya dengan aplikasi berbasis web. Kita sebagai pengguna mengakses aplikasi menggunakan web browser dan aplikasi yang digunakan layaknya seperti aplikasi yang di install pada komputer kita sendiri. 

Layanan sumber daya pada teknologi cloud computing dapat berupa perangkat lunak (software-as-service), perangkat keras (infrastruktur-as-a-service), dan platform (platform-as-service). Sebagai layanan yang berskala besar dan elastis melalui infrastruktur jaringan, biaya penggunaan didasarkan kepada sumberdaya yang digunakan dan tergantung  perjanjian tingkat layanan atau Service Level Agreement  (SLA) antara penyedia layanan dan konsumen pengguna.

### B. Arsitektur Cloud Computing
Dalam lingkungan teknologi informasi tradisional, aplikasi dan infrastruktur teknologi informasi lainnya bersifat real dan dimiliki secara fisik. Cloud computing menawarkan perangkat lunak, platform, penyimpanan atau infrastruktur di awan(cloud) dan berada di suatu tempat dalam sebuah jaringan.  Infrastruktur  cloud computing meliputi perangkat keras dan perangkat lunak. Arsitektur cloud computing didasarkan pada empat bagian yang terdiri dari bagian fisik yaitu perangkat keras  meliputi server dan komponen jaringan, perangkat lunak  seperti sistem operasi, sumber daya virtualisasi  yang memungkinkan penyatuan dan berbagi sumber daya, dan layanan aplikasi seperti contoh Salesforce.com atau Google Apps. 

Pengembang layanan menciptakan,  menerbitkan,  memberikan layanan dan memonitor aplikasi berbasis cloud untuk digunakan oleh konsumen. Manajemen, pengelolaan dan monitoring termasuk perencanaan kapasitas, jaminan keamanan kepada pelanggan, perjanjian tingkat layanan(SLA), laporan, penagihan, merupakan beberapa hal penting dalam cloud computing untuk memberikan transparansi antara  penyedia layanan dan konsumen.

### C. Karakteristik cloud computing
The US National Institute of Standard and Technology (NIST) menetapkan setidaknya lima kriteria yang harus dipenuhi oleh sebuah sistem untuk bisa di masukkan dalam kriteria cloud computing, juga dijelaskan oleh Mell and Grance [7], yaitu on-demand self-service  (layaknya swalayan, seorang pelanggan dimungkinkan untuk  secara langsung “memesan” sumber daya yang dibutuhkan, seperti kecepatan prosessor dan kapasitas penyimpanan melalui control panel elektronis yang disediakan. 

Jadi tidak perlu berinteraksi dengan personil customer service jika ingin menambah atau mengurangi sumberdaya cloud yang diperlukan), Broadband Network Access(tersedianya kemampuan akses yang luas dalam infrastruktur jaringan), Resource pooling (Sumberdaya dikelompokkan di satu atau berbagai lokasi data center dengan mekanisme multi-tenant yang memungkinkan sejumlah sumberdaya tersebut digunakan secara bersama-sama oleh sejumlah user), Rapid elasticity(elastis dan cepat tersedia, baik itu dalam bentuk penambahan ataupun pengurangan kapasitas yang diperlukan, seolah-olah kapasitas yang tersedia tak terbatas besarnya, dan dapat “dibeli” kapan saja dengan jumlah berapa saja.), Measured Service (Sumberdaya cloud yang tersedia harus dapat diatur dan dioptimasi penggunaannya,  jumlah sumberdaya yang digunakan dapat secara transparan diukur yang akan menjadi dasar bagi user untuk membayar biaya penggunaan layanan).

### D. Model penyebaran cloud computing
Penyebaran teknologi dan layanan cloud computing dibagi beberapa jenis berdasarkan karakteristik dan tujuan. Penyebaran  meliputi publik (eksternal), private (internal), community, hybrid dan virtual private cloud. Public cloud adalah di mana semua sumberdaya yang disediakan penyedia layanan kepada konsumen seperti penyimpanan data dan aplikasi diintegrasikan melalui aplikasi web atau dengan layanan web di dalam jaringan internet. Sumber daya tersebut dikendalikan dan dikelola oleh penyedia layanan. Ini biasanya murah atau on-demand self-service  dan measured service [6-12].  Private Cloud merupakan sebuah infrastruktur cloud yang dioperasikan untuk satu organisasi. Ini dapat dikelola oleh organisasi atau pihak ketiga. Layanan private cloud menawarkan penyediaan dan penggunaan serta kontrol yang lebih besar atas infrastruktur cloud.  

Community cloud dikendalikan dan dimiliki oleh beberapa organisasi dan didukung komunitas tertentu yang telah berbagi kepentingan seperti misi, kebijakan, persyaratan keamanan dan kepatuhan atas berbagai pertimbangan yang dibuat. Ini dapat dikelola oleh organisasi atau pihak ketiga dan anggota berbagi akses community cloud terhadap data dan aplikasi. Pengguna Community cloud merupakan pengguna yang berusaha untuk mengeksploitasi skala ekonomi dan meminimalkan biaya yang berkaitan dengan private cloud dan risiko yang terkait dengan public cloud [6 12]. 

Hybrid cloud merupakan kombinasi dari dua atau lebih computing cloud (private, community atau public)  dan terikat oleh standar atau teknologi eksklusif yang memungkinkan portabilitas data dan aplikasi. Ada kalanya pengguna public cloud  kemudian menyediakan infrastruktur untuk menciptakan private atau semi-private  virtual cloud (Interkoneksi ke sumber daya internal), biasanya melalui koneksi Virtual Private Network (VPN) [13].

### E. Model layanan cloud computing
Layanan cloud computing dibagi menjadi tiga kategori yaitu Software-as-a-Service (SaaS), Platform-as-a-Service (PaaS) dan Infrastruktur-as- a-Service (IaaS). SaaS memberikan kemudahan bagi pengguna untuk bisa memanfaatkan sumberdaya perangkat lunak dengan cara berlangganan. Sehingga tidak perlu mengeluarkan investasi untuk pembelian lisensi. Dengan cara berlangganan via web, pengguna dapat langsung menggunakan berbagai fitur yang disediakan oleh penyedia layanan. Hanya saja dengan konsep SaaS ini, pelanggan tidak memiliki kendali penuh atas aplikasi yang mereka sewa. Hanya fitur-fitur aplikasi yang telah disediakan oleh penyedia saja yang dapat disewa oleh pelanggan.

PaaS adalah layanan yang menyediakan modul-modul siap pakai yang dapat digunakan untuk mengembangkan sebuah aplikasi, yang tentu saja hanya bisa berjalan diatas platform tersebut. Pengguna PaaS tidak memiliki kendali terhadap sumber daya cloud seperti memory, media penyimpanan, system operasi. Layanan pada PaaS meliputi desain aplikasi, pengembangan, pengujian, penyebaran, hosting, kolaborasi tim, integrasi layanan web, integrasi database, keamanan, skalabilitas, penyimpanan, manajemen lokasi dan versi [6-7, 9, 12, 14-22]. 

IaaS merupakan sebuah layanan yang “menyewakan” sumberdaya teknologi informasi dasar, yang meliputi server, system operasi, aplikasi, media penyimpanan, virtualisasi platform dan peralatan jaringan serta dapat digunakan oleh penyewa untuk menjalankan aplikasi yang dimilikinya. IaaS memungkinkan pelanggan melakukan penambahan/pengurangan kapasitas secara fleksibel dan otomatis. IaaS menawarkan keuntungan seperti skalabilitas,  efektivitas biaya dan fleksibilitas [6-7, 9, 12, 14-22].

Terlepas dari SaaS, PaaS dan model layanan IaaS, alaternatif lain untuk layanan cloud computing meliputi Communication-as-a-Service (CaaS);  Security-as-a-Service  (SECaaS);  Monitoring-as-a-Service (MaaS);  Storage-as-a- Service (STaaS);  Desktop-as-a-Service (DTaaS);  Compute  Capacity-as-a-Service (CCaaS);  Database-as-a-Service  (DBaaS);  Hardware-as-a-Service (HaaS);  IT-as-a-Service  (ITaaS); and Business Process-as-a-Service (BPaaS).
### F. Keamanan cloud computing
Meskipun layanan dan karakteristik cloud computing  memberikan keuntungan dan solusi menarik untuk masalah Teknologi Informasi,  cloud computing  tidak bebas risiko atau benar-benar  aman. Manajemen bertanggung jawab untuk menangani risiko keamanan untuk melindungi sistem dan data. Penerapan kebijakan dan prosedur terhadap pengendalian resiko cloud computing ini penting untuk menjamin konerja dan keamanan data. Kebijakan dan prosedur harus didasarkan pada praktek terbaik dan harus selaras antara bisnis dan tujuan TI. 

Identifikasi risiko dan analisis penting untuk memprioritaskan pelaksanaan (jangkauan dan time frame) penataan dan kontrol, serta untuk membangun ruang audit untuk meninjau penerapan cloud computing. Berdasarkan identifikasi dan analisis risiko, kontrol harus dirancang dan dilaksanakan untuk memastikan bahwa tindakan yang dilakukan adalah  untuk mengatasi risiko dan untuk mencapai bisnis dan tujuan TI. 


## III. MANFAAT CLOUD COMPUTING
Pertumbuhan pasar untuk layanan cloud computing  sekitar $ 46.3 milyar pada tahun 2008  dan $148.8 milyar sampai dengan $150 milyar pada tahun 2014 serta 222.5 milyar pada tahun 2015 [1-3]. Pengeluaran biaya untuk cloud computing diperkirakan meningkat dari $ 16 miliar pada 2008 menjadi sekitar $ 55 miliar pada tahun 2014 [23-24]. Prediksi pertumbuhan ini berdasarkan pada realisasi banyaknya manfaat dari cloud computing. 

Cloud computing memberikan penghematan biaya dalam bidang TI termasuk biaya operasional dan pemeliharaan yang lebih rendah; kurangnya pembelian perangkat keras;  tidak ada biaya untuk ruang pendingin perangkat, bangunan dan penyimpanan sumberdaya karena semuanya beralih ke penyedia layanan, biaya yang dibayar hanya untuk jenis layanan yang digunakan(Measured Service). 

Cloud computing juga memungkinkan organisasi untuk menjadi lebih kompetitif karena platform cloud computing yang fleksibel dan  memiliki performa tinggi, menyediakan sumberdaya aplikasi dan data yang memiliki skalabilitas dan kinerja tinggi. Melalui cloud computing, departemen TI menghemat pengembangan aplikasi, distribusi, keamanan, dan pemeliharaan waktu dan biaya, sekaligus memetik manfaat dari skala ekonomi. Cloud computing membantu organisasi untuk mengurangi daya (‘going green’), peyimpanan, pendinginan dan penggunaan ruang server. 

Migrasi ke cloud computing mengurangi infrastruktur yang ada dan sumber daya yang dapat dialokasikan untuk tugas yang lebih strategis. Manfaat cloud computing terdapat pada gambar dibawah, dimulai dari level tertinggi sampai dengan level terendah.

<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj-xA1PPEmCV7XtweofIg3XLzD1hacd7uUYeVA82I7j1WVUdIoBbhtFUijaf9TtWVbvKkQK5vubUd3JffUftAHLjUeMUwauzFQ6Sdlji8ynq0w7nswwBac1Pvgdfi0wn30Jvdbz3fBeyw_4hrHZWxqTetYmRKM6FTWgaFIZdip4EsswGJjYuRGfdzEt/w640-h306/manfaat%20cloud%20computing.png' width="100%" class="border-0 rounded">
 
Gambar 1. Manfaat cloud computing

Efisiensi biaya adalah pendorong utama untuk mengadopsi cloud computing. Manfaat utama lainnya termasuk skalabilitas, fleksibilitas, performance, efisiensi, integritas, pengembangan yang cepat, distribusi dan manajemen perubahan yang lebih baik serta kinerja dan mobilitas yang lebih tinggi. Peningkatan otomatisasi, dukungan dan manajemen keamanan.



## IV. RESIKO CLOUD COMPUTING
Meskipun beralih ke cloud computing menawarkan banyak solusi, tetapi cloud computing bukan tanpa resiko atau benar-benar aman. Sebuah pemahaman menyeluruh dan mitigasi risiko keamanan merupakan langkah penting menuju implementasi dan pemanfaatan cloud computing. Gambar. 2 menyajikan daftar risiko yang teridentifikasi. Dengan aplikasi dan data yang dikelola oleh penyedia layanan, data tidak lagi di bawah kendali manajemen dan rentan terhadap ancaman keamanan dan kerahasiaan data. 

Hosting aplikasi dan data dalam infrastruktur bersama yang dikelola penyedia layanan meningkatkan potensi akses yang tidak sah seperti privasi karyawan, identitas manajemen, otentikasi,  integritas, ketersediaan data, enkripsi, keamanan jaringan dan keamanan fisik. Selain keamanan risiko, masalah lain termasuk SLA dan manajemen pihak ketiga (layanan penyedia), kualitas layanan, manajemen kontrol, beban kerja manajemen, kinerja, pengendalian perubahan, ketersediaan layanan, kurangnya monitoring dan manajemen peralatan, transparansi, kepatuhan terhadap hukum dan peraturan, portabilitas, kurangnya standar dan audit serta standard kelayakan cloud computing. 

Berdasarkan wawancara tehadap responden mengenai penggunaan cloud computing, besarnya resiko keamanan dinilai mencapai 91,7 persen untuk pengimplementasian, perencanaan kelangsungan bisnis menjadi risiko kedua yang paling kritis, dengan nilai 66,7 persen. Standar, kebijakan dan kontrol untuk manajemen operasi, manajemen perubahan, pihak ketiga / layanan tingkat manajemen, interface management, dan peraturan perundang-undangan dinilai sebagai 'agak penting ' untuk mitigasi risiko. 

Hasil dari wawancara tersebut menguatkan pentingnya untuk memastikan bahwa lingkungan cloud cukup dilindungi dan aman. Membangun kontrol dan standarisasi merupakan langkah penting untuk mengamankan lingkungan cloud computing. 

Tabel 1. Resiko yang paling kritis pada cloud computing

|Risk Area	| Critical	| Somewhat Important	| Not so Important
|----|----|----|----|
|Infromation accurity	| 91,7 %	| 8,3 %	| 0,0 %
|Operations management	| 41,7 %	| 58,3 %	| 0,0 %
|Change management	| 41,7 %	| 50,0 %	| 8,3 %
|Disaster recovery business contilulty management	| 66,7 %	| 33,3 %	| 0,0 %
|Third-party service level management	| 41,7 %	| 41,7 %	| 16,7 %
|Interface management	| 8,3 %	| 50,0%	| 41,7 %
|Regulations and legislation	| 33,3 %	| 41,7 %	| 25,0 %

<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhHUcnSiwlbySGWFpDvTVpLVTu2w6vdme4dAI4G9gstUs8ssZL6PxidDSOT_QyQyC3SIkARFhG0UNO4umQ1rgW17j-1XPL8zw_3AUKQt-lcC0YeHdYaZ1KGDG4UdSifVOqN0AUc9263ZOZ50pAOpKwfDbCJ2GMo3Hr72OC7VaU-UXw5QJEsPBJWM3tf/w640-h312/resiko%20cloud%20computing.png' width="100%" class="border-0 rounded">
Gambar 2. Resiko cloud computing


## V. MITIGASI RISIKO KEAMANAN CLOUD COMPUTING
Mitigasi risiko yang memadai merupakan strategi yang  harus dikembangkan dan diikuti untuk memastikan risiko keamanan dan perlindungan data serta aplikasi pada cloud computing. Pengamanan yang tepat pada sistem dan perlindungan terhadap data bisnis yang berharga tetap menjadi tanggung jawab manajemen walaupun data dan sistem di-host di cloud dan dikelola oleh penyedia layanan.  

Melalui tinjauan literatur yang luas, berikut tujuan yang di diidentifikasi sebagai pengendalian penting atau  mitigasi risiko terhadap keamanan cloud computing: data security, administration and control(keamanan data, administrasi dan kontrol);  logical access(akses logis); network security(keamanan jaringan); physical access(akses fisik);  compliance(kepatuhan);  dan virtualization(virtualisasi). masing-masing tujuan-tujuan ini dibahas lebih rinci dalam bagian berikutnya. 

Rekomendasi ini membentuk langkah pertama dalam menyiapkan kerangka lengkap untuk mengurangi risiko keamanan di lingkungan cloud computing. Sebagian besar risiko keamanan dan kontrol berikutnya, dijelaskan dalam sisa tulisan ini.

### A. Data Security, Administration And Control
Keamanan data merupakan resiko penghalang terbesar untuk penerapan cloud computing. Beberapa bisnis masih enggan untuk pindah data dan aplikasi ke cloud, terutama data yang sangat penting untuk bisnis, karena risiko kebocoran data rahasia yang mengarah ke privasi, kurangnya kontrol atas data dan aplikasi, ketersediaan data pada layanan cloud, risiko penurunan integritas data, dan perlindungan yang tidak efektif dalam transmisi data, back-up karena enkripsi yang tidak memadai. 

#### 1. Kerahasiaan data
Infrastruktur cloud computing yang memungkinkan akses dan penggunaan secara bersama menimbulkan masalah privasi data,  termasuk konsekuesi hukum akibat adanya penyimpangan penggunaan terhadap informasi rahasia suatu bisnis. Dengan menyediakan penyimpanan data secara eksternal pada penyedia jasa layanan, meningkatkan kerentanan data sedang diakses atau disalin oleh orang yang tidak berhak;  ancaman privacy data dapat berasal dari pihak internal (penyedia layanan, pengguna dalam perusahaan), dan kebocoran data bisa terjadi karena kegagalan hak akses keamanan di beberapa domain, kegagalan sistem pengiriman data secara elektronik dan fisik pada saat melakukan proses back-up pada jaringan cloud [6, 20].	

__Mitigasi:__

Informasi yang diperbolehkan  diakses di cloud harus diidentifikasi dan diklasifikasikan secara tepat. Penyedia layanan cloud computing harus membuktikan kepada pelanggan terhadap efektivitas pengendalian privasi data. Penyedia layanan cloud computing juga harus memiliki sumberdaya manusia disertai pengetahuan yang memadai dan keterampilan untuk mendeteksi dan bereaksi terhadap pelanggaran keamanan pada waktu yang tepat. Audit pihak ketiga harus dilakukan secara berkala untuk memantau penyedia layanan cloud terhadap persyaratan yang ditetapkan, standard, prosedur dan kebijakan untuk memastikan bahwa tidak ada perubahan besar terhadap prosedur standar atau kebijakan layanan[26-27].


#### 2. Kontrol terhadap data
Solusi cloud mengakibatkan sulitnya untuk menjaga keamanan, privacy data, pencurian identitas dan cybrcrime. perusahaan tidak memiliki control langsung terhadap data yang disimpan pada penyedia layanan. Sebuah perusahaan dalam cloud yang melakukan pelanggaran hukum dan adanya tindakan penyitaan data dapat menyebabkan data rahasia semua perusahaan yang berada dalam satu penyedia layanan cloud akan ikut terekspos[20].

__Mitigasi:__

Audit pihak ketiga harus dilakukan secara teratur untuk memantau penyedia layanan cloud computing terhadap kepatuhan akan  kesepakatan, efektifitas pelaksanaan, kepatuhan terhadap kebijakan keamanan, prosedur dan standar. Penyedia layanan cloud harus memberikan transparansi operasional, kontrol, dan keamanan pada layanan cloud computing[16, 22, 28-30].

#### 3. Ketersediaan data dan layanan
- Prosedur pemulihan data(recovery) harus teruji dan terencana karena sangat penting dalam hal menjamin ketersediaan layanan dan data. Risiko lainnya termasuk kerahasiaan data dapat menghambat prosedur pengujian back-up dan restore data; dan jika terjadi insiden, pelanggan cloud lainnya dapat mendapat prioritas tinggi dalam proses recovery data [6, 20, 26, 28-29, 31].

  __Mitigasi:__

  Data harus tersedia dan di back-up, harus disertai skema recovery data yang efektif untuk mencegah kehilangan data, menimpa data yang tidak di inginkan atau rusak. Penyedia layanan cloud harus memiliki backup dan kebijakan replikasi data serta menyimpan bukti auditable yang cukup untuk prosedur restore data termasuk recovery data secara akurat, lengkap dan tepat waktu [13, 26, 31].

- Karena cloud computing didasarkan pada layanan penyimpanan data, kelangsungan hidup data disaat penyedia layanan keluar dari bisnis atau tidak beroperasi lagi menjadi sebuah resiko utama.	

  __Mitigasi:__

  Penyedia layanan cloud harus mendukung interoperabilitas yang memenuhi standar untuk memastikan migrasi data serta kemampuan untuk integrasi ke penyedia layanan lain.

- Ketergantungan pada internet sebagai media utama untuk transfer dan pengolahan data menyebabkan masalah ketersediaan konektivitas dan kecepatan bandwidth[6, 19].	Konektivitas internet dan keterbatasan kecepatan bandwidth harus dipertimbangkan terlebih dahulu sebelum memutuskan untuk beralih ke cloud computing serta harus melakukan seleksi terhadap  penyedia jasa layanan jaringan yang sesuai. 

  __Mitigasi:__

  Penyedia layanan jaringan dan manajemen harus menyediakan provisi yang memadai mengenai kemampuan jaringan dan kecepatan bandwidth. Monitoring jaringan merupakan inti untuk memastikan keseimbangan antara kebutuhan dan beban dalam jaringan[33].

#### 4. Integritas Data
- Integritas jaringan, aplikasi, database dan aplikasi (sharing)yang digunakan bersama dalam sistem, lingkungan cloud secara global terancam oleh banyak vulnerabilities atau kerentanan jika tidak dilakukan patch dengan memadai dan tepat waktu [20, 31, 34].	

  __Mitigasi:__

  Tanggung jawab untuk melakukan manajemen patch yang efisien harus didefinisikan secara jelas. Kebijakan manajemen patch dan prosedur harus dilaksanakan. Pertimbangkan patch virtual dan layanan manajemen patch secara otomatis [20,31, 34].

- Risiko lain di lingkungan cloud computing adalah perubahan tidak sah terhadap data dan sistem oleh penyedia layanan yang dapat mempengaruhi integritas dan ketersediaan data dan aplikasi [6, 20, 31, 34].	

  __Mitigasi:__

  Semua perubahan di lingkungan cloud harus dikelola untuk meminimalkan  kemungkinan gangguan, perubahan tidak sah, atau kesalahan. Penyedia layanan cloud harus mematuhi standard  siklus hidup pengembangan system, System Development Life Cycle (SDLC). 

- Penyedia layanan harus menyimpan bukti auditable bahwa tidak ada 
perubahan tidak sah terjadi selama jangka waktu yang ditentukan [6, 20, 31, 34].

  __Mitigasi:__

  Karena sumber daya sistem tidak efektif dipisahkan antar pelanggan  maka integritas data dalam lingkungan penyimpanan cloud yang kompleks dapat  memberikan ancaman terhadap integritas data [6].	Segregasi data harus ditegakkan dengan perimeter defenisi keamanan yang benar dan konfigurasi aman pada sistem cloud [6].

#### 5. Enkripsi Data
- Sebuah resiko besar dalam lingkungan cloud computing adalah enkripsi yang tidak memadai dan manajemen data. Lingkungan cloud dibagi dengan banyak penyewa, dan penyedia layanan memiliki akses istimewa ke data sehingga memunculkan risiko dari kebocoran data atau akses tidak sah ke penyimpanan data.  

  Pengiriman data yang bersifat sensitive melalui jaringan meningkatkan resiko pembajakan atau kebocoran data. Data pada disk atau dalam lingkungan perusahaan juga tidak terlepas dari ancaman dari pihak penyedia layanan cloud yang berbahaya[6, 13, 16, 20, 30, 34].

  __Mitigasi:__

  Enkripsi harus didasarkan pada standard industri dan pemerintah. Manajemen password atau sandi yang efektif mencakup perlindungan terhadap database, lalu lintas pengiriman data, akses ke database yang menyimpan password harus menggunakan permission bertingkat; disertai solusi backup untuk keamanan data dan recovery untuk pemulihan data [6, 13, 16, 20, 30, 34].

- Algoritma kriptografi yang menggunakan metode tidak efektif dapat  menghasilkan enkripsi yang lemah.

   __Mitigasi:__

  Harus dilakukan metode kontrol dan manajemen kriptografi, baik dalam perjalanan data maupun pada penyimpanan [30].



### B. Logical Access
Akses melalui jaringan publik dan host layanan berarti lebih meningkatan eksposur dan risiko. Keistimewaan hak akses harus diserahkan dengan hati-hati untuk pengguna yang berwenang saja, dan ditinjau secara berkala. Dibutuhkan teknik dan penggunaan tools  keamanan untuk menjamin bahwa pengguna yang berwenang saja yang dapat mengakses data dan aplikasi. 

- Koneksi data menggunakan jaringan internet menyebabkan resiko aksess yang tidak sah, seperti akses administrator dari orang luar perusahaan. Akses tidak sah ke antar muka menu administrator pada cloud computing jauh lebih tinggi dibandingkan sistem tradisonal yang dapat diakses oleh beberapa administrator.[6, 16, 20, 28, 31, 34].	

   __Mitigasi:__
   
  Penyedia jasa keamanan harus dapat menunjukkan adanya control keamanan yang kuat dan efektif, meyakinkan pelanggan bahwa data dan aplikasi mempunyai jaminan keamanan terhadap akses yang tidak sah, perubahan dan kehilangan data. Meninjau secara regular dan melakukan pemantauan akses administrator termasuk yang mempunyai hak untuk mengelola data, segregasi, penanganan kontrol system dan pembatasan akses, mendeteksi dan bertindak cepat terhadap pelanggaran keamanan. Penyedia layanan cloud harus dapat menjamin semua akses atau perubahan sumberdaya untuk layanan cloud serta memberikan catatan yang auditable terlepas dari keberhasilan atau kegagalan. Audit harus mencakup indikasi yang jelas dari setiap delegasi dan identitas atau otorisasi. Persetujuan resmi harus diperoleh dan disimpan untuk perubahan hak-hak account yang baru.  Akses administrator harus dienkripsi dengan ekstra kuat yang dapat diterapkan melalui alat-alat keamanan seperti perlindungan password dan otentikasi yang bertingkat [6, 20, 27, 30-31, 34].

- Mekanisme otentikasi lemah bisa meningkatkan risiko akses yang tidak sah ke data dan aplikasi secara global. Mekanisme otentikasi lemah termasuk didalamnya pengguna yang berprilaku tidak aman (penggunaan password yang tidak aman). Migrasi beban kerja untuk infrastruktur berbagi menyebabkan potensi akses tidak sah dan eksposur, termasuk tantangan seperti credential manajemen otentikasi, yang kuat (yaitu multi-faktor otentikasi), didelegasikan otentikasi dan kepercayaan mengelola di semua jenis layanan cloud [6, 13, 29, 32, 35].

   __Mitigasi:__
   
	Profil pengguna terpercaya harus ditetapkan berdasarkan definisi peran dan klasifikasi informasi.  Memastikan pelaksanaan dan kepatuhan terhadap kebijakan keamanan. Browser yang digunakan client untuk mengakses aplikasi cloud belum sepenuhnya aman, oleh karena itu, harus dipastikan integrasi yang kuat antara keamanan data di sisi server dan framewok di client. Otentikasi yang memadai, manajemen identitas, kepatuhan dan akses menggunakan tools keamanan harus dilaksanakan dan secara teratur dimonitor. Pastikan bahwa transparansi tingkat tinggi pada service provider dinegosiasikan, didokumentasikan dalam SLA dan secara resmi disepakati [6, 13, 29,32, 35].


### C. Network Security
Risiko keamanan jaringan termasuk peningkatan risiko hacking dan intrusi, perimeter kebijakan keamanan dan ancaman menggunakan perangkat mobile. 

- Ada peningkatan resiko hacking dan intrusi data di lingkungan cloud. Resiko keamanan jaringan seperti ancaman dari dalam, penyalahgunaan autentikasi, side channel attacks, social networking attacks, dan denial of service (DoS) menjadi ancaman besar di lingkungan cloud computing. [6, 16, 31, 35].	

   __Mitigasi:__
   
  Kontrol jaringan tingkat tinggi harus dilaksanakan untuk mengamankan sistem dan data, mencegah penggunaan autentikasi yang tidak sah, pengungkapan, kerusakan, atau kehilangan data. Penyedia layanan juga harus  melakukan konfigurasi yang memadai dan efektif pada firewall jaringan. Kebijakan harus dapat memastikan  lalu lintas paket data yang aman  melalui  melalui switch maupun router [6, 16, 31, 35].

- Perimeter kebijakan keamanan di lingkungan cloud computing tidak lagi dibawah kontrol perusahaan sebagai pemilik sumberdaya tetapi berada pada penyedia layanan [34].	

   __Mitigasi:__
   
  Adanya sebuah mesin virtual sebagai daerah pertahanan dan sebagai zona aman, sehingga perimeter keamanan yang di buat hanya mencakup lingkungan mesin virtual tersebut [34].

- Dengan menggunakan perangkat mobile pengguna cloud dapat secara leluasa mengakses data bisnis tanpa melalui jaringan perusahaan, menyebabkan kerentanan keamanan [6, 20].	

   __Mitigasi:__
   
  Kontrol keamanan yang memadai harus ditegakkan antara pengguna ponsel dan penyedia layanan berbasis cloud [6, 20].


### D. Physical Access
Menempatkan data dalam jumlah besar yang dapat diakses secara  global sama saja dengan meninggalkan oraganisasi terbuka untuk ancaman didistribusikan jika penyerang dapat memperoleh akses langsung pada lokasi penyimpanan data[20, 28].	

  __Mitigasi:__
   
Keamanan jaringan yang bertingkat dan kontrol enkripsi data.

### E. Complience
Perusahaan harus memenuhi persyaratan, yang ditetapkan oleh organisasi mereka sendiri atau oleh badan industri atau pemerintah, untuk mengamankan aplikasi dan data , baik internal  maupun eksternal. Kepatuhan terhadap beberapa hukum dan standard peraturan meliputi:
-	Standard untuk pembayaran  menggunakan kartu kredit, Payment Card Industry Data Security Standard (PCI DSS); 
-	|Pembatasan geografis untuk transit dan penyimpana data.
-	Sarbanes Oxley Act (SOX); 
-	Gramm-Leach-Bliley Act (GLBA); 
-	Health Insurance Portability and Accountability Act (HIPAA); 
-	Standard audit seperti SAS70 and ISO [6, 16, 19-20, 22, 26, 31].	

  __Mitigasi:__
 
  Pastikan bahwa penyedia layanan cloud bersedia untuk menjalani audit eksternal dan sertifikasi keamanan, serta dapat memastikan kepatuhan terhadap standard. Penyedia layanan cloud harus membuktikan bahwa data, termasuk semua salinan dan back-up, hanya disimpan di lokasi geografis yang diizinkan oleh kontrak formal, SLA atau peraturan. Kepatuhan terhadap kontrol harus dipastikan; persyaratan khusus penggunaan lokasi data, sesuai dengan lokasi hukum dan peraturan tertentu, tata hukum dan peraturan yang secara resmi ditegakkan dan didokumentasikan dalam kebijakan [6, 16, 19-20, 22, 26,31].

## VI. KESIMPULAN
Diprediksikan layanan cloud computing menunjukkan pertumbuhan substansial untuk perkembangan dan implementasi. Untuk membuat lingkungan cloud yang lebih aman dan kuat, tepat kontrol maka mitigasi resiko keamanan harus dilakukan. Pertimbangan harus diberikan terhadap semua risiko untuk memastikan integritas dan ketersediaan aplikasi dan data di cloud. 

Disarankan juga sejumlah kontrol yang dapat dipertimbangkan untuk memperhitungkan dan mitigasi resiko keamanan sebagai kerangka pedoman dan standar kontrol untuk menangani resiko cloud computing, termasuk keamanan data, administrasi dan kontrol,  logic access, keamanan jaringan, keamanan fisik, kepatuhan terhadap perundang-undangan dan virtualisasi. 

## Referensi
1. Deloitte. (2010, 31 August 2010).  Executive Forum Cloud Computing: risks, mitigation strategies, and the role of Internal Audit. Available: http://www.deloitte.com 
2. C. Pettey and B. Tudor. (2010, 5 August 2010).  Gartner says  worldwide cloud services market to surpass $68 billion  in 2010  Available: http://www.gartner.com/it/page.jsp?id=1389313 
3. Press Office. (2010, 31 August 2010). Cloud Computing Services  - New Market Report Published. Available: http://www.companiesandmarkets.com/r.ashx?
id=41AETZYHJ289173&prk=ecb8413c602cb89051067456b636c7b9
4. I. Berger. (2010, 6 May 2010). Keeping Cloud Computing's Prospects Safe and Sunny. Available: http://www.theinstitute.ieee.org/portal/site/tionline/
menuitem.130a3558587d56e8fb2275875bac26c8/index.jsp?
&pName=institute_level1_article&TheCat=2201
&article=tionline/legacy/inst2010/may10/featuretechnology.xml&
5. K. McCabe and R. Nachbar. (2010, 18 October 2010). SURVEY BY IEEE AND CLOUD SECURITY ALLIANCE DETAILS IMPORTANCE AND URGENCY OF CLOUD COMPUTING SECURITY STANDARDS  
Available:http://standards.ieee.org/announcements/2010/pr_cloudcomputing_survey.html
6. Centre for the Protection of National Infrastructure (CPNI). (2010, 20 June 2010).  Information Security Briefing 01/2010: Cloud Computing. 
Available:  http://www.cpni.gov.uk/Docs/cloud-computing-briefing.pdf
7. P. Mell and T. Grance, "The NIST Definition of Cloud Computing," National Institute of Standards and Technology, Information Technology Laboratory2009. 
8. 	S. Baca. (2010, 14 May 2010). Cloud Computing: What it is and what it can do for you. Available: www.globalknowledge.com 
9. S. Bennett, et al.  (2009, 8 April 2010).  Architectural Strategies for Cloud Computing. 
Available: http://www.oracle.com/technology/architect/entarch/pdf/
architectural_strategies_for_cloud_computing.pdf
10. Cloud Computing Use Case Discussion Group. (2010, 31 March 2010).  Cloud Computing Use Cases Version 3.0. 
Available: http://groups.google.com/group/cloud-computing-use-cases
11. Sun Microsystems Inc. (2009, 8 April 2010). Introduction to cloud computing architecture   [White Paper]. 
Available: http://www.sun.com/featured-articles/CloudComputing.pdf
12. VMware Inc. (2009, 18 August 2010).  Eight Key Ingredients for Building an Internal Cloud. Available:  http://www.vmware.com/files/pdf/cloud/eight-key-ingredients-building-internal-cloud.pdf
13. Cloud Security Alliance. (2009, 20 May 2010). Security Guidance for Critical Areas of Focus in Cloud Computing V2.1. Available: www.cloudsecurityalliance.org/guidance/csaguide.v2.1.pdf
14. D. Brink. (2010, 12 September 2010).  Much Ado about Cloud Computing.
 Available: http://research.aberdeen.com/index.php/
 information-technology/89-information-technology-insights/1313-much-ado-about-cloud-computing
15. D. Durkee, "Why cloud computing will never be free," Communications of the ACM, vol. 53, pp. 62-69, 2010. 
16. M. Gregg. (2010, 14 May 2010).  10 Security Concerns for Cloud Computing.
 Available: www.globalknowledge.com
17. J. Hagel and J. S. Brown. (2010, 15 April 2010). Cloud Computing: Storms on the Horizon. 
Available: http://www.deloitte.com/assets/Dcom-UnitedStates/Local%20Assets/
Documents/TMT_us_tmt/us_tmt/ce/CloudsStormsonHorizon_102210.pdf
18. J. Hurwitz, et al.,  Cloud Computing for Dummies, HP Special Edition. Indianapolis, Indiana: Wiley Publishing, Inc, 2010. 
19. N. Kelson. (2010, 2 September 2010). Cloud Computing Management Audit/Assurance Program. Available: www.isaca.org
20. J. W. Rittinghouse and J. F. Ransome,  Cloud Computing: Implementation, Management, and Security. Florida: CRC Press, 2010. 
21. A. T. Velte, et al.  (2010, 8 April 2010).  Cloud Computing: A Practical Approach.
 Available: http://skillport.books24x7.com/
22. C. Weitz, et al. (2010, 31 August 2010). A balancing act: What cloud computing means for business, and how to capitalize on it. Available: www.deloitte.com
23. F. Gens.  (2010, 28 August 2010).  IDC's Public IT Cloud Service Forecast: New Numbers, Same Disruptive Story. Available: http://blogs.idc.com/ie/?p=922
24. N. Leavitt, "Is Cloud Computing Really Ready for Prime Time?," Computing Now, pp. 15-20, 2009. 
25. M. Carroll, et al., "Secure Virtualization: Benefits, Risks and  Controls," presented at the CLOSER 2011: The 1st International Conference on Cloud Computing and Services Science, Noordwijkerhout, The Netherlands, 2011. 
26. B. Robertson. (2009, 1 December 2009). Top Five Cloud Computing Adoption Inhibitors. 
Available: http://www.gartner.com/it/initiatives/pdf/KeyInitiativeOverview_CloudComputing.pdf
27. M. Vael. (2010, 24 July 2010). Cloud Computing: An insight in the Governance & Security aspects. 
Available: http://www.isaca.org/Groups/Professional-English/information-secuirtymanagement/GroupDocuments/
Across%20Cloud%20Computing%20governance%20and%20risks%20May%202010.pdf
28. L. Ponemon. (2010, 29  September 2010).  Security of Cloud Computing Users: A Study of Practitioners in the US & Europe. 
Available: http://www.ca.com/~/media/Files/IndustryResearch/security-cloud-computing-users_235659.pdf
29. V. Raval, "Risk Landscape of Cloud Computing,"  ISACA Journal, vol. 1, 2010. 
30. Distributed Management Task Force. (2010, 17 March 2011). Architecture for Managing Clouds. 
Available: http://www.dmtf.org/about/policies/disclosures.php
31. Clavister. (2010, 13 November 2010).  Security in the Cloud. 
Available: www.clavister.com/resources/
32. Open Cloud Manifesto. (2009, 2 September 2010).  Open Cloud Manifesto: Dedicated to the belief that the cloud should be open. Available: www.opencloudmanifesto.org
33. T. W. Singleton, "IT Audits of Cloud and SaaS," ISACA Journal, vol. 3, 2010. 
34. Third Brigade. (2008, 21 July 2009).  Cloud Computing Security: Making Virtual Machines Cloud-Ready   [White Paper]. Available: http://resources.thirdbrigade.com/
35. B. Grobauer, et al. (2010, 31 August 2010). Towards a cloud-specific Risk Analysis Framework. 
Available: www.siemens.com/it-solutions


Berdasarkan Jurnal,  Secure Cloud Computing: Benefits, Risks and Controls 
Mariana Carroll, Alta van der Merwe, CSIR Meraka Institute , School of Computing, University of South Africa , Pretoria, South Africa, MCarroll@csir.co.za, alta@meraka.org dan Paula Kotzé, CSIR Meraka Institute,  Institute for ICT Advancement, Nelson Mandela, Metropolitan University, South Africa, paula.kotze@meraka.org.za 

Ini adalah tugas perkuliahan saya pada 2012 pada matakuliah Keamanan Jaringan. Terima kasih telah berkunjung 🙂 dan semoga bermanfaat!