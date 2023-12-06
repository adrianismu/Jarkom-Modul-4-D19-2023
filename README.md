# Jarkom-Modul-4-D19-2023

Anggota:
| Nama | NRP |
|---------------------------|------------|
|Adrian Ismu Arifianto | 5025211116 |
|Ahmad Rafif Hikmatiar | 5025211247 |

## CPT VLSM

![cpt-vlsm](./img/cpt-vlsm.png)

#### <i>Subnetting</i>
Untuk langkah selanjutnya, kita lakukan <i>subnetting</i>
untuk mengetahui setiap ip nya. Langkah pertama yang harus dilakukan adalah menggambar atau membuat vlsm-tree. Berikut adalah vlsm-tree yang sudah saya buat:

![vlsm-tree](./img/vlsm-tree.png)

Setelah kita membuat vlsm-tree, kita lakukan <i>subnetting</i> pada setiap rute yang telah ditentukan dengan tabel berikut:

![vlsm-subnetting](./img/vlsm-subnetting.png)

#### <i>Routing</i>

## GNS3 CIDR

### Topologi

![Group 15](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/f9557f15-5597-4462-be48-eec8ef449858)

### Pembagian Subnet

![Group 3](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/7717614f-6e28-450f-bfa1-344096397e1b)

### Penggabungan Subnet
#### Penggabungan Subnet 1
![Group 5](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/f73f2aff-7dc7-4a0b-9f48-e1ddb8a89f97)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/1311ae2e-f822-4286-98c8-1b53345e0b52)

#### Penggabungan Subnet 2

![Group 6](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/a8de0684-5437-4e3f-bb62-f8c3c5cf3c21)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/96ac1080-1569-4694-aaca-3741bbf78139)

#### Penggabungan Subnet 3

![Group 7](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/5b828d4f-cb66-47f2-ae2c-400088fb83d1)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/c11d4647-bb57-4573-992b-44f1608763ff)

#### Penggabungan Subnet 4

![Group 8](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/83842dee-7315-4ca6-abcb-f2f7a4ecf6d5)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/da76f18c-f52d-414f-9744-325b1af2a14d)


#### Penggabungan Subnet 5

![Group 9](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/60b070e2-4309-4255-a067-0e904859c871)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/d779919f-d584-4a02-a2de-1484618df4ad)


#### Penggabungan Subnet 6

![Group 10](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/ad83b092-6cb2-4152-955c-e23d8ef192d3)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/1dcf1ce2-00a1-4b1f-8124-2fcd41a5823b)

#### Penggabungan Subnet 7

![Group 11](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/6d74b3d8-8a88-40ed-b537-38cad3c38c9b)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/2f87e9e5-0f40-46bb-8750-2e82bc20917a)

#### Penggabungan Subnet 8

![Group 12](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/757fadd7-ba36-4643-abdc-87e852cfa8cb)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/7ddd8478-b3b4-4075-a649-710e376bef7d)

#### Penggabungan Subnet 9

![Group 13](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/dc724cfc-cc5f-4fa3-abc5-e542279a4ba2)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/c1fc87b3-beae-4246-9cb1-790aa6326285)

#### Penggabungan Subnet 10

![Group 14](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/242709d9-a4cf-40e1-97e3-80e1fc06a6cb)

![image](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/357b8f31-bff0-4891-b8e7-0fdf65942eba)

### CIDR Tree

![Desktop - 1 (2)](https://github.com/adrianismu/Jarkom-Modul-4-D19-2023/assets/71255346/0ea16a1b-3d01-4a6a-a360-c5f066837601)


### Pembagian IP CIDR

| Subnet | Network ID  | Netmask         | Broadcast      | Gabungan                                               |
|--------|-------------|-----------------|----------------|--------------------------------------------------------|
| A1     | 10.31.16.0  | 255.255.248.0   | 10.31.23.255   | Fern-Switch4-AppetitRegion-Switch4-LaubHills          |
| A2     | 10.55.128.0 | 255.255.255.224 | 10.55.128.31   | Frieren-Switch3-LakeKorridor                          |
| A3     | 10.39.0.0   | 255.255.255.128 | 10.39.0.127    | Denkern-Switch2-RoyalCapital-Switch2-WllleRegion       |
| A4     | 10.57.0.0   | 255.255.252.0   | 10.57.3.255    | Lugner-Switch10-TurkRegion                            |
| A5     | 10.56.0.0   | 255.255.255.0   | 10.56.0.255    | Lugner-Switch9-GrobeForest                            |
| A6     | 10.55.16.0  | 255.255.254.0   | 10.55.17.255   | Linie-Switch11-GranzChannel                           |
| A7     | 10.55.0.0   | 255.255.255.192 | 10.55.0.63     | Lawine-Switch7-BredtRegion-Switch7-Heiter             |
| A8     | 10.55.4.0   | 255.255.252.0   | 10.55.7.255    | Heiter-Switch8-Sein-RiegelCanyon                      |
| A9     | 10.31.4.0   | 255.255.255.248 | 10.31.4.7      | Himmel-Switch6-SchweMountains                         |
| A10    | 10.31.0.0   | 255.255.252.0   | 10.31.3.255    | Flamme-Switch5-RohrRoad                               |
| A11    | 10.31.8.0   | 255.255.255.252 | 10.31.8.3      | Fern-Flamme                                           |
| A12    | 10.31.4.4   | 255.255.255.252 | 10.31.4.7      | Flamme-Himmel                                         |
| A13    | 10.31.32.0  | 255.255.255.252 | 10.31.32.3     | Flamme-Frieren                                        |
| A14    | 10.31.128.0 | 255.255.255.252 | 10.31.128.3    | Frieren-Aura                                          |
| A15    | 10.33.0.0   | 255.255.255.252 | 10.33.0.3      | Aura-Denken                                           |
| A16    | 10.32.0.0   | 255.255.255.252 | 10.32.0.3      | Aura-Eisen                                            |
| A17    | 10.59.0.0   | 255.255.255.252 | 10.59.0.3      | Eisen-Switch0-Stark                                   |
| A18    | 10.31.64.0  | 255.255.255.252 | 10.31.64.3     | Eisen-Lugner                                          |
| A19    | 10.55.64.0  | 255.255.255.248 | 10.55.64.7     | Eisen-Switch1-Revolte-Switch1-Richter                 |
| A20    | 10.55.32.0  | 255.255.255.252 | 10.55.32.3     | Eisen-Linie                                           |
| A21    | 10.55.8.0   | 255.255.255.252 | 10.55.8.3      | Linie-Lawine                                          |


### Config CIDR pada GNS3

Berikut merupakan config pada setiap node berdasarkan IP yang sudah didapatkan pada pembagian IP CIDR

#### AppetitRegion
```
auto eth0
iface eth0 inet static
	address 10.31.16.2
	netmask 255.255.248.0
	gateway 10.31.16.1
```
#### LaubHills
```
auto eth0
iface eth0 inet static
	address 10.31.16.3
	netmask 255.255.248.0
	gateway 10.31.16.1
```

#### Fern
```
auto eth0
iface eth0 inet static
	address 10.31.8.1
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.31.16.1
	netmask 255.255.248.0
```

#### Flamme
```
auto eth0
iface eth0 inet static
	address 10.31.32.1
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.31.8.2
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.31.0.1
	netmask 255.255.252.0

auto eth3
iface eth3 inet static
	address 10.31.4.5
	netmask 255.255.255.252    
```

#### RohrRoad
```
auto eth0
iface eth0 inet static
	address 10.31.0.2
	netmask 255.255.252.0
	gateway 10.31.0.1
```

#### Himmel
```
auto eth0
iface eth0 inet static
	address 10.31.4.6
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.31.4.1
	netmask 255.255.255.248
```

#### SchwerMountain
```
auto eth0
iface eth0 inet static
	address 10.31.4.2
	netmask 255.255.255.248
	gateway 10.31.4.1
```

#### Frieren
```
auto eth0
iface eth0 inet static
	address 10.31.128.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.31.32.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.55.128.2
	netmask 255.255.255.224

```

#### LakeKorridor
```
auto eth0
iface eth0 inet static
	address 10.55.128.2
	netmask 255.255.255.224
	gateway 10.55.128.1
```

#### Aura
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 10.33.0.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.31.128.2
	netmask 255.255.255.224

auto eth3
iface eth3 inet static
	address 10.32.0.1
	netmask 255.255.255.252
```

#### Denken
```
auto eth0
iface eth0 inet static
	address 10.33.0.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.39.0.1
	netmask 255.255.255.128
```

#### RoyalCapital
```
auto eth0
iface eth0 inet static
	address 10.39.0.2
	netmask 255.255.255.128
	gateway 10.39.0.1
```

#### WilleRegion
```
auto eth0
iface eth0 inet static
	address 10.39.0.3
	netmask 255.255.255.128
	gateway 10.39.0.1
```

#### Eisen
```
auto eth0
iface eth0 inet static
	address 10.32.0.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.59.0.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.55.64.1
	netmask 255.255.255.248

auto eth3
iface eth3 inet static
	address 10.31.64.1
	netmask 255.255.255.252

auto eth4
iface eth4 inet static
	address 10.55.32.1
	netmask 255.255.255.252
```

#### Stark
```
auto eth0
iface eth0 inet static
	address 10.59.0.2
	netmask 255.255.255.252
	gateway 10.59.0.1
```

#### Revolte
```
auto eth0
iface eth0 inet static
	address 10.55.64.3
	netmask 255.255.255.248
	gateway 10.55.64.1
```

#### Richter
```
auto eth0
iface eth0 inet static
	address 10.55.64.2
	netmask 255.255.255.248
	gateway 10.55.64.1
```

#### Lugner
```
auto eth0
iface eth0 inet static
	address 10.31.64.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.56.0.1
	netmask 255.255.255.0

auto eth2
iface eth2 inet static
	address 10.57.0.1
	netmask 255.255.252.0
```

#### TurkRegion
```
auto eth0
iface eth0 inet static
	address 10.57.0.2
	netmask 255.255.252.0
	gateway 10.57.0.1
```

#### GrobeForest
```
auto eth0
iface eth0 inet static
	address 10.56.0.2
	netmask 255.255.255.0
	gateway 10.56.0.1
```

#### GranzChanel
```
auto eth0
iface eth0 inet static
	address 10.55.16.2
	netmask 255.255.252.0
	gateway 10.55.16.1
```


#### Linie
```
auto eth0
iface eth0 inet static
	address 10.55.32.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.55.8.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.55.16.1
	netmask 255.255.254.0
```

#### Lawine
```
auto eth0
iface eth0 inet static
	address 10.55.8.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 10.55.0.1
	netmask 255.255.255.192
```

#### BredRegion
```
auto eth0
iface eth0 inet static
	address 10.55.0.3
	netmask 255.255.255.192
	gateway 10.55.0.1
```

#### Heiter
```
auto eth0
iface eth0 inet static
	address 10.55.0.2
	netmask 255.255.255.192

auto eth1
iface eth1 inet static
	address 10.55.4.1
	netmask 255.255.252.0
```

#### Sein
```
auto eth0
iface eth0 inet static
	address 10.55.4.2
	netmask 255.255.252.0
	gateway 10.55.4.1
```

#### RiegelCanyon
```
auto eth0
iface eth0 inet static
	address 10.55.4.3
	netmask 255.255.252.0
	gateway 10.55.4.1
```

### Routing CIDR pada GNS3

Berikut merupakan cara melakukan routing CIDR pada GNS3 dengan menggunakan `route add -net <NID subnet> netmask <netmask> gw <IP gateway>`

#### Aura
```bash
route add -net 10.31.32.0 netmask 255.255.255.252 gw 10.31.128.1 #A13

route add -net 10.55.128.0 netmask 255.255.255.224 gw 10.31.128.1 #A2

route add -net 10.31.8.0 netmask 255.255.255.252 gw 10.31.128.1 #A11

route add -net 10.31.16.0 netmask 255.255.248.0 gw 10.31.128.1 #A1

route add -net 10.31.0.0 netmask 255.255.252.0 gw 10.31.128.1 #A10

route add -net 10.31.4.4 netmask 255.255.255.252 gw 10.31.128.1 #A12

route add -net 10.31.4.0 netmask 255.255.255.248 gw 10.31.128.1 #A9


route add -net 10.39.0.0 netmask 255.255.255.128 gw 10.33.0.2 #A3


route add -net 10.59.0.0 netmask 255.255.255.252 gw 10.32.0.2 #A17

route add -net 10.31.64.0 netmask 255.255.255.252 gw 10.32.0.2 #A18
```

#### Frieren
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.31.128.2

route add -net 10.31.8.0 netmask 255.255.255.252 gw 10.31.32.1

route add -net 10.31.4.4 netmask 255.255.255.252 gw 10.31.32.1

route add -net 10.31.4.0 netmask 255.255.255.248 gw 10.31.32.1

route add -net 10.31.0.0 netmask 255.255.252.0 gw 10.31.32.1

route add -net 10.31.16.0 netmask 255.255.248.0 gw 10.31.32.1
```

#### Flamme
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.31.32.2

route add -net 10.31.16.0 netmask 255.255.248.0 gw 10.31.8.1

route add -net 10.31.4.0 netmask 0.0.0.0 gw 10.31.4.6
```

#### Fern
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.31.8.2
```

#### Himmel
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.31.4.5
```

#### Denken
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.33.0.1
```

#### Eisen
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.32.0.1

route add -net 10.57.0.0 netmask 255.255.252.0 gw 10.31.64.2

route add -net 10.56.0.0 netmask 255.255.255.0 gw 10.31.64.2

route add -net 10.55.16.0 netmask 255.255.254.0 gw 10.55.32.2

route add -net 10.55.8.0 netmask 255.255.255.252 gw 10.55.32.2

route add -net 10.55.0.0 netmask 255.255.255.192 gw 10.55.32.2

route add -net 10.55.4.0 netmask 255.255.252.0 gw 10.55.32.2
```

#### Lugner
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.31.64.1
```

#### Linie
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.55.32.1

route add -net 10.55.0.0 netmask 255.255.255.192 gw 10.55.8.2

route add -net 10.55.4.0 netmask 255.255.252.0 gw 10.55.8.2
```

#### Lawine
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.55.8.1

route add -net 10.55.4.0 netmask 255.255.252.0 gw 10.55.0.2

```

#### Heiter
```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.55.0.1
```


