# Network Mapping & Ping Test

## Introduction

This project demonstrates how to map and test a home/office network.  
It shows the devices connected, identifies network settings such as IP address, subnet mask, default gateway, and DNS server, and tests connectivity using the `ping` command.  
A simple network diagram is included to show how the devices are connected to the router and the internet.

---

## My Network Information

- **IPv4 Address:** 172.20.6.190  
- **Subnet Mask:** 255.255.254.0  
- **Default Gateway:** 172.20.6.1  
- **DNS Server:** 8.8.8.8

---

## Network Diagram

This diagram shows how my devices connect to the router and the internet:

![Network Diagram](network-diagram.png)

*Diagram description: Internet connects to the Router (172.20.6.1), which connects to a Laptop (172.20.6.190) and a Phone.*

---

## Ping Test Results

### 1. Ping Router (Default Gateway)
![Ping Router](ping-router.png)

**Result:** Successful – confirms the local network is working.

### 2. Ping Internet (Google DNS 8.8.8.8)
![Ping Internet](ping-8888.png)

**Result:** Successful – confirms the internet connection is working.

### 3. Ping Website (google.com)
![Ping Google](ping-google.png)

**Result:** Successful – confirms DNS resolution is working.

---
## 3. Network Diagram
```
Internet
|
Router (172.20.6.1)
|
Laptop (172.20.6.88)
```

## Conclusion

- The local network (router and devices) is functioning correctly.  
- The internet connection is working properly.  
- DNS services are functioning correctly.  
- Network mapping and ping tests confirm that TCP/IP communication is working.

---

## Tools & Commands Used

- **Command Prompt / Terminal**  
- **ipconfig / ifconfig** – to find network information  
- **ping** – to test connectivity between devices and the internet  
- **Diagram tool** – PowerPoint, Draw.io, Paint, or hand-drawn diagram
