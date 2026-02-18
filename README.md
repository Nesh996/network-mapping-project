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

Internet
   |
Router (172.20.6.1)
   |
Laptop (172.20.6.190)
   |
Phone


*Diagram description: Internet connects to the Router (172.20.6.1), which connects to a Laptop (172.20.6.190) and a Phone.*

---

## Ping Test Results

### 1. Ping Router (Default Gateway)
<img width="650" height="444" alt="ping-router png" src="https://github.com/user-attachments/assets/2e69ed49-2979-423e-badd-742ae944c453" />


**Result:** Successful – confirms the local network is working.

### 2. Ping Internet (Google DNS 8.8.8.8)
<img width="597" height="340" alt="ping-google png" src="https://github.com/user-attachments/assets/0c141e30-1152-4a80-a0bd-47179de5ac0b" />


**Result:** Successful – confirms the internet connection is working.

### 3. Ping Website (google.com)
<img width="580" height="424" alt="ping-8888 png" src="https://github.com/user-attachments/assets/175e27fe-17a4-4a93-8075-bcee718f28a4" />


**Result:** Successful – confirms DNS resolution is working.

```
![Ping Google](ping-google.png)

**Result:** Successful – confirms DNS resolution is working.

---

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
