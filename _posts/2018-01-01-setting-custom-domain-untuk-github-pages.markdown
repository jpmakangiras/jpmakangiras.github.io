---
layout: post
title:  "Setting Custom Domain Untuk Github Pages"
date: 2018-01-01
comments: true
---
Agar [Github Pages](https://pages.github.com/) yang dimiliki mengarah ke sebuah domain pribadi, kita perlu melakukan  beberapa pengaturan dari repo github pages dan penyedia layanan domain.

1.	Masuk ke repo github pages anda, lalu klik _settings_ dan pada pilihan custom domain silakan masukkan domain pribadi yang dimiliki 
![Alt](../../../assets/img/art01/01.png "pengaturan cname"){:class="img-responsive"}

2.	Setelah klik _save_ maka secara otomatis akan ada sebuah file baru dengan nama CNAME di repo anda

3.	Langkah selanjutnya adalah masuk ke halaman penyedia domain anda lalu pilih menu yang berkaitan dengan DNS dan atur DNSnya seperti ini
![Alt](../../../assets/img/art01/02.png "pengaturan dns"){:class="img-responsive"}

4.	Tunggu sekitar 5-10 menit atau bahkan lebih untuk melihat hasilnya, tergantung masa propagansi dns.