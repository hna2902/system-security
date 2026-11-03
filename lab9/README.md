Lab 9
Ho Nhat Anh
1150080002

## Noi dung da thuc hien

- Thiet lap bo sung mang ATTACKNET tren VMware su dung VMnet3; pfSense duoc them interface ATTACKNET 10.10.0.1/24, giu nguyen DNSLAB 10.9.0.1/24 tren VMnet2, WAN NAT, DMZ va MGMT cua LAB truoc
- Dieu chinh dia chi IP cho Windows Server (DNS-SERVER) 10.9.0.10, Client-A (VICTIM) 10.9.0.100, AUTH-DNS/DMZ-WEB 172.16.6.20 va chuyen Kali Linux sang ATTACKNET 10.10.0.200; Kali ngat hoan toan card mang DNSLAB va dat Promiscuous Mode = Deny de dam bao tinh remote
- Thiet lap Firewall Rules tren tab ATTACKNET va DNSLAB: cho phep UDP/TCP 53 truy van Resolver va Auth-DNS, cho phep UDP 5300 cho race relay, TCP 80 truy cap Web va Block toan bo luu luong trai phep sang LAN/MGMT; kiem tra ket noi giua cac phan vung thanh cong
- Trien khai dich vu Authoritative DNS auth_dns_relay_lab10.py tren 172.16.6.20; cau hinh ban ghi hop le www.example.lab10.test tro ve Web Server DMZ 172.16.6.10, thiet lap co che race window 3s va cong relay 5300 mo phong Kaminsky
