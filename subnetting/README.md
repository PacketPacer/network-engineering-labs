# Subnetting Lab 01

## Objective
Understand how to divide a /24 network into smaller subnets using CIDR notation and calculate network ranges.

---

## Starting Network

192.168.1.0/24

---

# Subnetting Practice

## 1. Splitting into 2 Subnets

### New CIDR
/25

### Block Size
128

### Subnets

Subnet 1  
Network: 192.168.1.0/25  
Host Range: 192.168.1.1 – 192.168.1.126  
Broadcast: 192.168.1.127  

Subnet 2  
Network: 192.168.1.128/25  
Host Range: 192.168.1.129 – 192.168.1.254  
Broadcast: 192.168.1.255  

---

## 2. Splitting into 4 Subnets

### New CIDR
/26

### Block Size
64

### Subnets

Subnet 1
Network: 192.168.1.0/26  
Host Range: 192.168.1.1 - 192.168.1.62
Broadcast: 192.168.1.63

Subnet 2
Network: 192.168.1.64/26 
Host Range: 192.168.1.65 - 192.168.1.126
Broadcast: 192.168.1.127

Subnet 3
Network: 192.168.1.128/26  
Host Range: 192.168.1.129 - 192.168.1.190
Broadcast: 192.168.1.191

Subnet 4
Network: 192.168.1.192/26  
Host Range: 192.168.1.193 - 192.168.1.254
Broadcast: 192.168.1.255

---

## 3. Splitting into 8 Subnets

### New CIDR
/27

### Block Size
32

### Subnets


Subnet 1  
Network: 192.168.1.0/27  
Host Range: 192.168.1.1 – 192.168.1.30  
Broadcast: 192.168.1.31  

Subnet 2  
Network: 192.168.1.32/27  
Host Range: 192.168.1.33 – 192.168.1.62  
Broadcast: 192.168.1.63  

Subnet 3  
Network: 192.168.1.64/27  
Host Range: 192.168.1.65 – 192.168.1.94  
Broadcast: 192.168.1.95  

Subnet 4  
Network: 192.168.1.96/27  
Host Range: 192.168.1.97 – 192.168.1.126  
Broadcast: 192.168.1.127  

Subnet 5  
Network: 192.168.1.128/27  
Host Range: 192.168.1.129 – 192.168.1.158  
Broadcast: 192.168.1.159  

Subnet 6  
Network: 192.168.1.160/27  
Host Range: 192.168.1.161 – 192.168.1.190  
Broadcast: 192.168.1.191  

Subnet 7  
Network: 192.168.1.192/27  
Host Range: 192.168.1.193 – 192.168.1.222  
Broadcast: 192.168.1.223  

Subnet 8  
Network: 192.168.1.224/27  
Host Range: 192.168.1.225 – 192.168.1.254  
Broadcast: 192.168.1.255  

---

## Status

✔ Subnetting completed  
⏳ Packet Tracer lab in progress

# Tools Used

- Cisco Packet Tracer
- Subnetting practice
- Networking fundamentals
