# Python Packet Sniffer

## Overview

This project is a simple network packet sniffer developed in Python using the Scapy library. It captures live network traffic and displays useful packet information such as source IP address, destination IP address, protocol type, and packet payload.

This project was created as part of a Cyber Security laboratory assignment to demonstrate basic packet analysis and network monitoring.

---

## Features

- Capture live network packets
- Display source and destination IP addresses
- Detect common protocols (TCP, UDP, ICMP)
- Show packet payload (when available)
- Lightweight and easy to understand

---

## Technologies Used

- Python 3
- Scapy
- Kali Linux

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Packet-Sniffer.git
```

Install Scapy

```bash
pip install scapy
```

---

## Usage

Run the program with administrator/root privileges.

```bash
sudo python3 packet_sniffer.py
```

Generate network traffic by browsing websites or using ping commands.

Example:

```bash
ping google.com
```

---

## Sample Output

```
Source IP: 192.168.1.20
Destination IP: 8.8.8.8
Protocol: TCP

Payload:
...
```

---

## Learning Outcomes

- Understanding packet structures
- Understanding IP addressing
- Basic protocol analysis
- Practical use of Scapy for network monitoring

---

## Disclaimer

This tool is intended for educational purposes only. Capture traffic only on networks that you own or have permission to monitor.
