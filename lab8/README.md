Lab 8
Ho Nhat Anh
1150080002

## Noi dung da thuc hien

- Thiet lap bo sung mang DNSLAB tren VMware su dung VMnet4; pfSense duoc them interface DNSLAB 10.9.0.1/24, giu nguyen WAN NAT, LAN, DMZ va MGMT cua LAB 7
- Dieu chinh dia chi IP cho Windows Server 10.9.0.10, Client-A 10.9.0.100 va Kali Linux 10.9.0.200; Kali giu ket noi dong thoi DNSLAB 10.9.0.0/24 va DMZ 172.16.6.0/24
- Cai dat va cau hinh DNS Server tren Windows Server 2025; tao zone external.lab9.test va ban ghi www.external.lab9.test tro ve Web Server hop le 172.16.6.10
- Thiet lap Firewall Rules tren tab DNSLAB de cho phep ping Gateway 10.9.0.1 va cho phep Client trong DNSLAB truy cap Web Server DMZ qua TCP/80; kiem tra ket noi giua Client-A, Windows Server, Kali va pfSense thanh cong
