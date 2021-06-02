


## Ports

System Ports: 0-1023

Registered Ports: 1024-49151

Dynamic/Private Ports: 49152-65536


## OSI Layers

1) Phsysical Data Link (bits) (Coax, Fiber, Wireless)
2) Data Link (frames) (Ethernet, PPP, MAC, ARP)
3) Network (packets) (IP)
4) Transport (segments, connections) (TCP, UDP)
5) Session (data) (APIs)
6) Presentation (data) (SSL, SSH)
7) Application (data) (HTTP)


## ARP

Layer 2 communication to find devices on the local network

1) source broadcasts (ff:ff:ff:ff:ff:ff) who has <IP>
2) destination calls back to source MAC <IP> is at <MAC>
