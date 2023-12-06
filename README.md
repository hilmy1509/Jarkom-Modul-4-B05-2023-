# Jarkom-Modul-4-B05-2023-

### Praktikum Jaringan Komputer Modul 4 Tahun 2023

Group Members:
| NRP | Name |
| ------ | ------ |
|5025211028|Keysa Anadea Aqiva Ajie|
|5025221202|Hilmy Septian Nursyekha|


## Topologi CPT CIDR

<img width="554" alt="Cuplikan layar 2023-12-06 153507" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/9c6b0f1e-2926-4c37-a791-231ff8e84db1">

## Topologi GNS VLSM

<img width="548" alt="Cuplikan layar 2023-12-06 200747" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/4097d1b7-28aa-4410-9b81-e47acab84d6b">

## Prefix IP Kelompok B05
Prefix IP yang kami gunakan adalah `10.11`

## Rute
Mengacu pada Modul 4 Jaringan Komputer, rute yang di dapat adalah sebagai berikut

<img width="546" alt="Cuplikan layar 2023-12-06 153910" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/47057393-4831-4e5f-a549-b47381a136c2">

## CIDR
CIDR adalah cara penulisan subnet mask dari sebuah sub network dengan cara mengubah notasi sub network dari desimal ke biner kemudian menghitung jumlah total nilai biner 1 yang ada. CIDR merupakan cara pengganti atau alternatif dalam klasifikasi alamat IP kelas A, B, C, D, hingga E. CIDR juga disebut sebagai SUBNETTING.

```
10.11.0.0 /24
```

IP 10.11.0.0 /24 merupakan alamat IP dengan subnet mask 255.255.255.0. Dalam notasi CIDR, /24 menunjukkan bahwa terdapat 24 bit yang digunakan untuk menentukan network address, sedangkan 8 bit sisanya digunakan untuk menentukan host address. Dengan demikian, terdapat 2^8 = 256 host address yang dapat digunakan pada subnet tersebut.

CIDR (Classless Inter-Domain Routing) adalah metode alokasi alamat IP yang meningkatkan efisiensi perutean data di internet. CIDR memungkinkan penghematan penggunaan alamat IP karena batasan-batasan yang ada pada penugasan kelas dihilangkan 1. CIDR juga memungkinkan untuk memecah-mecah subnet menjadi bagian yang lebih kecil atau lebih besar, memberikan alamat IP yang lebih spesifik untuk setiap jaringan atau perangkat, dan memungkinkan satu entri tabel perutean untuk supernet mewakili agregasi jaringan

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

## Testing

#### Ping di Frieren menggunakan IP Aura
<img width="519" alt="Cuplikan layar 2023-12-06 215948" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/86908f70-c05e-4139-8ea2-f5fad0a65a57">

#### Ping di Flamme menggunakan IP Lake Korridor
<img width="521" alt="Cuplikan layar 2023-12-06 220032" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/75d5e784-7095-4e1e-93e5-25c4def16e40">

#### Ping di Eisen menggunakan IP AppetitRegion
<img width="431" alt="Cuplikan layar 2023-12-06 220125" src="https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/f640ccc5-fd20-46d9-b931-a43b9a6a4767">

#### Ping di RoyalCapital menggunakan IP WilleRegion
![WhatsApp Image 2023-12-06 at 21 49 51_c7962011](https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/ca261f94-c888-456d-a3b2-b520a1a7b0c2)

#### Ping di LaubHills menggunakan IP AppetitRegion
![WhatsApp Image 2023-12-06 at 21 49 51_1085b2bf](https://github.com/hilmy1509/Jarkom-Modul-4-B05-2023-/assets/115638253/177d8ab9-3bab-4188-89cc-55ef261dcbc7)

