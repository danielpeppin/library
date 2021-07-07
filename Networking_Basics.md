# Networking Basics


## OSI Layers

1) Phsysical Data Link (bits) (Coax, Fiber, Wireless)
2) Data Link (frames) (Ethernet, PPP, MAC, ARP)
3) Network (packets) (IP)
4) Transport (segments, connections) (TCP, UDP)
5) Session (data) (APIs)
6) Presentation (data) (SSL, SSH)
7) Application (data) (HTTP)


## Layer 2

Layer 2 communication to find devices on the local network

ARP
1) source broadcasts (ff:ff:ff:ff:ff:ff) who has IP `<destination IP>`? Tell IP `<source IP>`
2) destination responds to source MAC that `<destination IP>` is at MAC address `<destination MAC>`
3) source can now cache IP address to a MAC address
4) while communicating to destination, MAC address can be used and switch can set a direct line of communication from port to port rather than a broadcast to all ports

ARP Poisoning - rogue device response to ARP despite not being correct IP

## Layer 3 IP

ICMP

Routing

NAT

VLAN/subnet


## Layer 4 Transport

TCP 3 way handshake


## Data Layers

Common Ports
ftp, ssh, smtp, http, pop3, imap
rdp, ntp, 



## DNS

## NAT








Next File: Security
ssh
tls

ACL, firewalls
