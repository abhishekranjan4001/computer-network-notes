# Networking Concepts - Cheat Sheet

## 1. Introduction to Networks
A network is a collection of computers and devices connected together to share resources and information. It allows communication between devices.

**Examples:**
- File sharing
- Internet browsing
- Email

---

## 2. Types of Networks

### a. LAN (Local Area Network)
Covers a small geographic area like a home, office, or building.

### b. WAN (Wide Area Network)
Spans a large geographical area, like the Internet.

### c. MAN (Metropolitan Area Network)
Covers a city or large campus.

### d. PAN (Personal Area Network)
Short-range network around a person (e.g., Bluetooth).

---

## 3. Network Devices

### a. Router
Connects different networks and directs data.

### b. Switch
Connects devices in a LAN and uses MAC addresses to forward data.

### c. Hub
Broadcasts data to all devices connected.

### d. Modem
Converts digital data into signals and vice versa for Internet access.

### e. Access Point
Provides wireless access to a wired network.

---

## 4. Network Topologies
Structure of how devices are arranged in a network.

### a. Bus
All devices share a single communication line.

### b. Star
All devices are connected to a central hub.

### c. Ring
Each device is connected to two others in a circular format.

### d. Mesh
Every device is connected to every other device.

### e. Hybrid
Combination of two or more topologies.

---

## 5. OSI Model
A 7-layer model that describes how data travels from one computer to another over a network.

1. **Physical** - Transmits raw bitstream over the physical medium.
2. **Data Link** - Provides node-to-node data transfer using MAC addresses.
3. **Network** - Routes data using IP addresses.
4. **Transport** - Ensures error-free transmission (TCP/UDP).
5. **Session** - Manages sessions between applications.
6. **Presentation** - Formats, encrypts, and compresses data.
7. **Application** - End-user software like browsers and email clients.

---

## 6. IP Addressing

### a. IPv4
32-bit numeric address written in decimal (e.g., `192.168.1.1`).

### b. IPv6
128-bit address written in hexadecimal (e.g., `2001:0db8:85a3::7334`).

### c. IP Address Classes
- **Class A:** `1.0.0.0` – `126.255.255.255`
- **Class B:** `128.0.0.0` – `191.255.255.255`
- **Class C:** `192.0.0.0` – `223.255.255.255`

### d. Private IP Ranges
- `10.0.0.0` – `10.255.255.255`
- `172.16.0.0` – `172.31.255.255`
- `192.168.0.0` – `192.168.255.255`

---

## 7. LAN Implementation

### a. Setting up a Network
Use switches and routers to connect devices with Ethernet cables or Wi-Fi.

### b. Assigning IP Addresses
- **Static:** Manually configured IPs
- **Dynamic:** Assigned automatically using DHCP

### c. Testing the Network
- `ping` – Check connectivity
- `traceroute` or `tracert` – Track route to a destination
- `ipconfig` / `ifconfig` – View network settings

---

Let me know if you want to include:
- TCP/IP Model
- Subnetting
- DNS, DHCP, NAT
- Firewalls and Ports
- Real-world troubleshooting scenarios
