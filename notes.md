# Networking Concepts - Complete Cheat Sheet

This cheat sheet covers the most essential networking concepts for beginners and professionals alike.

---

## Table of Contents

1. Introduction to Networks  
2. Types of Networks  
3. Network Devices  
4. Network Topologies  
5. OSI Model  
6. TCP/IP Model  
7. IP Addressing  
8. Subnetting  
9. DNS, DHCP, and NAT  
10. Firewalls and Ports  
11. Real-world Troubleshooting  
12. Important Network Commands  
13. Additional Key Networking Concepts  

---

## 1. Introduction to Networks
A network is a collection of interconnected devices that can share data and resources.

**Example use cases:**
- Email
- File sharing
- Internet access

---

## 2. Types of Networks

| Type | Description |
|------|-------------|
| **LAN** | Local Area Network – covers small areas like homes, offices |
| **WAN** | Wide Area Network – large-scale networks like the internet |
| **MAN** | Metropolitan Area Network – spans a city or campus |
| **PAN** | Personal Area Network – short-range (e.g., Bluetooth) |
| **CAN** | Campus Area Network – interconnects LANs within a campus |

---

## 3. Network Devices

- **Router** – Connects different networks and routes traffic.
- **Switch** – Connects devices in a LAN using MAC addresses.
- **Hub** – Broadcasts data to all devices (less efficient than switch).
- **Modem** – Converts analog signals to digital for Internet.
- **Access Point** – Wireless gateway to a wired network.
- **Firewall** – Filters and protects network traffic.

---

## 4. Network Topologies

| Topology | Description |
|----------|-------------|
| **Bus** | All devices share a single communication line. |
| **Star** | Devices connect to a central hub or switch. |
| **Ring** | Each device connects to two others, forming a ring. |
| **Mesh** | Devices are interconnected directly. |
| **Hybrid** | Combination of two or more topologies. |

---

## 5. OSI Model (7 Layers)

1. **Physical** – Cables, hardware transmission.
2. **Data Link** – MAC addresses, switches.
3. **Network** – IP addressing, routers.
4. **Transport** – Reliable transmission (TCP/UDP).
5. **Session** – Managing sessions (start/end).
6. **Presentation** – Data format and encryption.
7. **Application** – User-level applications (HTTP, FTP, DNS).

---

## 6. TCP/IP Model (4 Layers)

1. **Network Access (Link)** – Hardware & drivers
2. **Internet** – IP addressing and routing
3. **Transport** – TCP/UDP (segmentation and flow)
4. **Application** – Protocols like HTTP, DNS, FTP

OSI and TCP/IP are conceptual models for network communication.

---

## 7. IP Addressing

- **IPv4:** 32-bit, e.g., `192.168.1.1`
- **IPv6:** 128-bit, e.g., `2001:0db8:85a3::8a2e:0370:7334`

### Classes:
- **A**: 1.0.0.0 – 126.255.255.255
- **B**: 128.0.0.0 – 191.255.255.255
- **C**: 192.0.0.0 – 223.255.255.255

### Private IP Ranges:
- `10.0.0.0/8`
- `172.16.0.0/12`
- `192.168.0.0/16`

---

## 8. Subnetting

Subnetting divides a large network into smaller parts.

- **CIDR Notation:** e.g., `192.168.1.0/24`
- Helps in:
  - Efficient IP usage
  - Improved security
  - Easier management

---

## 9. DNS, DHCP, and NAT

- **DNS (Domain Name System):** Converts domain names to IP addresses.
- **DHCP (Dynamic Host Configuration Protocol):** Automatically assigns IP addresses.
- **NAT (Network Address Translation):** Converts private IPs to a public IP for internet access.

---

## 10. Firewalls and Ports

- **Firewall:** A security device or software that controls incoming/outgoing traffic.
- **Port:** A virtual point for network access.

**Common Ports:**
- **80** – HTTP
- **443** – HTTPS
- **22** – SSH
- **21** – FTP
- **25** – SMTP

---

## 11. Real-world Troubleshooting

- **ping [IP]** – Check if host is reachable.
- **tracert/traceroute [domain]** – View path to destination.
- **ipconfig/ifconfig** – View system IP configuration.
- **nslookup [domain]** – Check DNS resolution.
- **netstat** – View active connections and ports.

---

## 12. Important Network Commands

| Command | Description |
|---------|-------------|
| `ping` | Tests connectivity |
| `traceroute` | Displays the route to a host |
| `netstat` | Shows network connections |
| `nslookup` | Resolves DNS names |
| `ipconfig` / `ifconfig` | Displays IP info |
| `telnet` | Tests ports/services manually |

---

## 13. Additional Key Networking Concepts

- **MAC Address:** Unique hardware address for each device.
- **Bandwidth:** Maximum data transfer capacity.
- **Latency:** Delay in data transmission.
- **Throughput:** Actual data transfer rate.
- **Packet:** Small unit of data sent across a network.
- **Port Forwarding:** Route external traffic to specific internal services.
- **Proxy Server:** Acts as an intermediary for requests.
- **VPN (Virtual Private Network):** Encrypts connection over the internet.
- **Load Balancer:** Distributes network traffic across multiple servers.

---

## 📌 Summary

Computer networking is essential to modern communication and infrastructure. This cheat sheet offers a foundational understanding, from physical cables to application protocols. Keep learning by practicing subnetting, exploring protocols, and setting up basic LANs!

---

