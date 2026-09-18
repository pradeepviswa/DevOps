# network concept
```
Networking
AWS

Regions
	Availability Zone
		Local Zone

IP address
192.168.1.7
__8__ . _8___ . __8___ . ___8__
octate = 4 octates
each octate has 8 bits = 32 bits in 1 ip address
host bits = fixed portion
network bits = this one changes
192.1.1.1
192.1.1.2
.
.
192.1.1.254
255.255.255.0
1st IP called as Network Address. usually assigned to routers
last IP is called broadcast address used by switches and hubs

   IPv4 Address: 192.168.1.7
   Subnet Mask : 255.255.255.0
10 computers
192.168.1.0 to 192.168.1.254
192.168.1.7
192.168.1.8
192.168.1.9
192.168.1.254


IPv4
subnet 1
192.168.1  .2
255.255.255.0 (total 254)
5 or 10

	gateway

subnet 2
192.168.2  .2
255.255.255.0

Private IP Address, 4 classes (1st octate):
1.0.0.1
1.0.0.2
1.0.0.254
1.0.1.2
1.0.1.254
1.0.2.1


private range
A: 10.0.0.0 – 10.255.255.255
	255.0.0.0.0 /8
	Loopback address: 127 (reserved)
B: 172.16.0.0 – 172.31.255.255
	255.255.0.0	/16
C: 192.168.0.0 – 192.168.255.255
	255.255.255.0   /24

my public ip is : 223.233.80.173

Subnetting - CIDR (classless inter domain routing)
192.168.0.1/27
255.255.255.0
host bits are 3 (blocked for subnetting)
32-27 = there are 5 network bits
2^5 = 2*2*2*2*2 = 32 IP are there
1st and last ip cannot be used
that means total usable Ips are 30
IP address 
 
How many networks can be created:
2^3 = 2*2*2 = 8 networks can be created

HR_Subnet
192.168.0.0/27
192.168.0.1
192.168.0.2
192.168.0.3

DB_subnet
192.168.0.33 - 192.168.0.62
192.168.0.33 
192.168.0.34
 

192.168.0.33 unable to access server 192.168.0.2
	check gateway.
	it is subnet or network issue.

192.168.0.33 > 192.168.0.32 > how to route packet 

192.168.0.33 unable to access server 192.168.0.35

EC2: Elastic Cloud Compute (ram, CPU, OS)
S3 : Simple Storage Service
Route53: DNS Port 53




```
