# Jarkom-Modul-4-B05-2023-




## Topologi CPT CIDR

<img width="554" alt="Cuplikan layar 2023-12-06 153507" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/9c6b0f1e-2926-4c37-a791-231ff8e84db1">

## Topologi GNS VLSM

<img width="548" alt="Cuplikan layar 2023-12-06 200747" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/8a4a6c80-e5ae-4e19-8e3c-bc6fec6aa794">


## Prefix IP Kelompok B05
Prefix IP yang kami gunakan adalah `10.11`

## Rute
Mengacu pada Modul 4 Jaringan Komputer, rute yang di dapat adalah sebagai berikut

<img width="546" alt="Cuplikan layar 2023-12-06 153910" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/47057393-4831-4e5f-a549-b47381a136c2">

## CIDR

CIDR, atau Classless Inter-Domain Routing, merupakan cara lebih efisien dalam mengalamatkan dan mengelompokkan alamat IP di Internet. Sebelum adanya CIDR, pengalamatan IP tergantung pada kelas, seperti kelas A, kelas B, dan kelas C, yang memiliki ukuran tetap untuk jaringan dan host, menyebabkan pemborosan alamat IP.

CIDR menggantikan pendekatan kelas dengan memperkenalkan notasi baru yang memberikan fleksibilitas lebih besar dalam pengelompokan dan alokasi alamat IP. Notasi CIDR terdiri dari alamat IP dan prefiks (subnet mask) dalam format biner, seperti yang ditunjukkan pada contoh berikut ini

```
10.11.0.0 /24
```

Dalam contoh ini, "10.11.0.0" merupakan alamat jaringan, dan "/24" menandakan bahwa 24 bit pertama dari alamat ini digunakan sebagai netmask (subnet mask). Penggunaan CIDR memungkinkan administrator jaringan untuk menentukan ukuran subnet sesuai kebutuhan tanpa terikat oleh pembatasan kelas tradisional.

Keunggulan utama CIDR terletak pada penghematan alamat IP dan pengurangan pemborosan. Dengan CIDR, tidak perlu lagi mengalokasikan blok alamat IP dengan ukuran yang tetap berdasarkan kelas. Sebagai contoh, jika suatu jaringan memerlukan 300 alamat IP, administrator dapat menggunakan CIDR untuk mengalokasikan subnet dengan panjang netmask yang sesuai tanpa harus memilih kelas yang lebih besar dari yang dibutuhkan.

CIDR juga mendukung agregasi rute, memungkinkan penyederhanaan tabel routing di Internet. Dengan menggabungkan beberapa blok alamat IP ke dalam satu entri routing, CIDR membantu mengurangi ukuran tabel routing dan meningkatkan efisiensi dalam pengelolaan lalu lintas jaringan global.

## Penggabungan IP

<img width="589" alt="Cuplikan layar 2023-12-06 185310" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/65bfcaec-6927-4a70-b6c7-82e03763c64e">


<img width="546" alt="Cuplikan layar 2023-12-06 153910" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/b36b8866-a591-4a01-9c48-5fb31e101a81">

## Penggabungan Node

<img width="330" alt="Cuplikan layar 2023-12-06 194607" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/c4cfda95-b370-4abe-923a-fcc34cc7a31a">
  <img width="331" alt="Cuplikan layar 2023-12-06 194620" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/a03358ab-dc6e-4814-b389-03cb2918aa13">
    <img width="330" alt="Cuplikan layar 2023-12-06 194632" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/1178f484-41c7-44d2-a1a7-8700fc49e30a">
    <img width="329" alt="Cuplikan layar 2023-12-06 194643" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/d1c053ed-6824-44c2-877e-749fb2c4ee39">
    <img width="314" alt="Cuplikan layar 2023-12-06 194702" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/9cde67e6-152c-45f9-8f44-fc714182e1a2">
    <img width="317" alt="Cuplikan layar 2023-12-06 194716" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/bad79f40-d982-453b-b867-4a9de53779bb">
    <img width="313" alt="Cuplikan layar 2023-12-06 194727" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/7a383928-43ad-468d-8993-d0eab3552044">
    <img width="314" alt="Cuplikan layar 2023-12-06 194738" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/15ed35df-8075-4b53-9ec7-833396e3f977">
    

![WhatsApp Image 2023-12-06 at 19 26 48_0d4fb629](https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/92ad9b66-bdb0-43b0-83ce-e8c3d4018162)

## Tree

![CIDR_B05(1)](https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/7c20fa27-2615-49e3-ba19-ca66833c5296)


## Pembagian IP

<img width="668" alt="Cuplikan layar 2023-12-06 153404" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/4ebbac80-d01c-4fb3-9a7c-06bec466bb01">

## VLSM
VLSM, yang dikenal sebagai Variable Length Subnet Masking, adalah teknik `subnetting` untuk efisien pembagian IP di dalam jaringan. Dengan VLSM, `netmask` disesuaikan dengan jumlah komputer atau `host` yang membutuhkan alamat `IP` di suatu `subnet`. Ini memberikan fleksibilitas kepada administrator jaringan untuk mengoptimalkan penggunaan alamat IP tanpa mengikuti pembatasan seragam.

Proses implementasi `VLSM` melibatkan pembagian jaringan besar menjadi `subnet` yang lebih kecil dengan ukuran yang bervariasi. Setiap `subnet` diberikan `netmask` sesuai dengan jumlah host yang diperlukan. `Subnet` dengan lebih banyak `host` mendapatkan `netmask` dengan bit yang lebih sedikit, sementara `subnet` yang membutuhkan lebih sedikit `host` mendapatkan `netmask` dengan bit yang lebih banyak.

Keunggulan utama `VLSM` adalah efisiensi penggunaan alamat `IP`, menghindari memberikan `subnet` besar kepada jaringan kecil yang hanya membutuhkan alamat `IP` sedikit. `VLSM` juga membantu mengurangi konsumsi alamat `IP` secara keseluruhan dalam jaringan, mendukung pertumbuhan dan perluasan jaringan secara efektif.

## Tree

![VLSM_B05(1)](https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/fd3b180a-6f4f-4ece-9f33-4fe479cc77f0)

## Pembagian IP

<img width="631" alt="Cuplikan layar 2023-12-06 184239" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/377a1a84-5842-4d89-85bc-1283e055e1d6">

## Konfigurasi

#### Royal Capital (63 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.9.2
	netmask 255.255.255.0
	gateway 10.11.9.0
```

#### Wiilie Region (63 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.9.3
	netmask 255.255.255.0
	gateway 10.11.9.0
```

#### Denken
```
auto eth0
iface eth0 inet static
	address 10.11.7.142
	netmask 255.255.255.252
	gateway 10.11.7.141

auto eth1
iface eth1 inet static
	address 10.11.9.1
	netmask 255.255.255.0
 ```

#### Aura
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 10.11.7.9
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.11.7.25
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.11.7.141
	netmask 255.255.255.252
```

#### Frieren
```
auto eth0
iface eth0 inet static
	address 10.11.7.10
	netmask 255.255.255.252
	gateway 10.11.7.9

auto eth1
iface eth1 inet static
	address 10.11.7.13
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.11.7.161
	netmask 255.255.255.224
```

#### LakeKorridor
```
auto eth0
iface eth0 inet static
	address 10.11.7.162
	netmask 255.255.255.224
	gateway 10.11.7.160
```

#### Flamme
```
auto eth0
iface eth0 inet static
	address 10.11.7.14
	netmask 255.255.255.252
	gateway 10.11.7.13

auto eth1
iface eth1 inet static
	address 10.11.7.17
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.11.12.1
	netmask 255.255.252.0

auto eth3
iface eth3 inet static
	address 10.11.7.21
	netmask 255.255.255.252
```

#### Fern
```
auto eth0
iface eth0 inet static
	address 10.11.7.18
	netmask 255.255.255.252
	gateway 10.11.7.17

auto eth1
iface eth1 inet static
	address 10.11.24.1
	netmask 255.255.248.0
```

#### Appetit Region (625 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.24.2
	netmask 255.255.248.0
	gateway 10.11.24.0
```

#### LaubHills(397 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.24.3
	netmask 255.255.248.0
	gateway 10.11.24.0
```

#### RohrRoad (1000 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.12.2
	netmask 255.255.252.0
	gateway 10.11.12.0
```

#### Himmel
```
auto eth0
iface eth0 inet static
	address 10.11.7.22
	netmask 255.255.255.252
	gateway 10.11.7.21

auto eth1
iface eth1 inet static
	address 10.11.7.145
	netmask 255.255.255.248
```

#### SchwerMountains (5 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.7.146
	netmask 255.255.255.248
	gateway 10.11.7.144
```

#### Eisen
```
auto eth0
iface eth0 inet static
	address 10.11.7.26
	netmask 255.255.255.252
	gateway 10.11.7.25

auto eth1
iface eth1 inet static
	address 10.11.7.153
	netmask 255.255.255.248

auto eth2
iface eth2 inet static
	address 10.11.7.133
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.11.7.129
	netmask 255.255.255.252

auto eth4
iface eth4 inet static
	address 10.11.7.29
	netmask 255.255.255.252
```

#### Stark
```
auto eth0
iface eth0 inet static
	address 10.11.7.30
	netmask 255.255.255.252
	gateway 10.11.7.28
```

#### Lugner
```
auto eth0
iface eth0 inet static
	address 10.11.7.130
	netmask 255.255.255.252
	gateway 10.11.7.129

auto eth1
iface eth1 inet static
	address 10.11.8.1
	netmask 255.255.255.0

auto eth2
iface eth2 inet static
	address 10.11.16.1
	netmask 255.255.252.0
```

#### TurkRegion (1000 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.16.2
	netmask 255.255.252.0
	gateway 10.11.16.0
```

#### GrobeForest (250 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.8.2
	netmask 255.255.255.0
	gateway 10.11.8.0
```

#### Richter
```
auto eth0
iface eth0 inet static
	address 10.11.7.154
	netmask 255.255.255.248
	gateway 10.11.7.152
```

#### Revolte
```
auto eth0
iface eth0 inet static
	address 10.11.7.155
	netmask 255.255.255.248
	gateway 10.11.7.152
```

#### Linie
```
auto eth0
iface eth0 inet static
	address 10.11.7.134
	netmask 255.255.255.252
	gateway 10.11.7.133

auto eth1
iface eth1 inet static
	address 10.11.7.137
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.11.10.1
	netmask 255.255.254.0
```

#### GranzChannel (254 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.10.2
	netmask 255.255.254.0
	gateway 10.11.10.0
```

#### Lawine
```
auto eth0
iface eth0 inet static
	address 10.11.7.138
	netmask 255.255.255.252
	gateway 10.11.7.137

auto eth1
iface eth1 inet static
	address 10.11.7.193
	netmask 255.255.255.192
```

#### BredtRegion (29 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.7.194
	netmask 255.255.255.192
	gateway 10.11.7.192
```

#### Heiter
```
auto eth0
iface eth0 inet static
	address 10.11.7.195
	netmask 255.255.255.192
	gateway 10.11.7.193

auto eth1
iface eth1 inet static
	address 10.11.20.1
	netmask 255.255.252.0
```

#### Sein
```
auto eth0
iface eth0 inet static
	address 10.11.20.3
	netmask 255.255.252.0
	gateway 10.11.20.0
```

#### RiegelCanyon (510 Host)
```
auto eth0
iface eth0 inet static
	address 10.11.20.2
	netmask 255.255.252.0
	gateway 10.11.20.0
```

## Routing

<img width="465" alt="Cuplikan layar 2023-12-06 204757" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/6614acb1-1bcc-4248-94d5-0eeaa54fc876">






