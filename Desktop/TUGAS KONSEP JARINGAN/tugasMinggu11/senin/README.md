# Subnetting Router
**Nama** : Aulia Ilham Nur Alfian </br>
**NRP** : 3122600024 </br>
**Kelas** : 2 D4 IT A </br>
**Mata Kuliah** : Konsep Jaringan </br>
`Semua Tugas dalam repo ini merupakan tugas mata kuliah Konsep Jaringan yang dibimbing oleh Bpk. Dr. Ferry Astika Saputra,ST, M.Sc`
**Cisco Packet Tracer:**

<img src="./assets/1.png">

Konfigurasi :

## **1. Router 0**
    - Static
        - Network     : 192.168.1.0
          Next Hop    : 192.168.10.14
        - Network     : 192.168.3.0
          Next Hop    : 192.168.10.9
    - Fe 0/0
        IPv4 Address: 192.168.10.13
        Subnet Mask : 255.255.255.252

## **2. Router 1**
    - Static
        - Network     : 192.168.4.0
          Next Hop    : 192.168.10.10
        - Network     : 192.168.1.0
          Next Hop    : 192.168.10.5
    - Fe 0/0
        IPv4 Address: 192.168.10.9
        Subnet Mask : 255.255.255.252

## **2. Router 2**
    - Static
        - Network     : 192.168.4.0
          Next Hop    : 192.168.10.13
        - Network     : 192.168.2.0
          Next Hop    : 192.168.10.1
        - Network     : 192.168.3.0
          Next Hop    : 192.168.10.6
    - Fe 0/0
        IPv4 Address: 192.168.10.14
        Subnet Mask : 255.255.255.252

## **2. Router 3**
    - Static
        - Network     : 192.168.1.0
          Next Hop    : 192.168.10.2
    - Fe 0/0
        IPv4 Address: 192.168.10.1
        Subnet Mask : 255.255.255.252
