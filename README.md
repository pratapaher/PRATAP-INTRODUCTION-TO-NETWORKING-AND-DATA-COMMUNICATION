Name : PRATAP AHER

PRN: 2125UCSM1097


# Unit 1 – LAN Mini Project

## Building a LAN in Cisco Packet Tracer

This mini-project demonstrates the design and configuration of a Local Area Network using Cisco Packet Tracer.

---

## Network Components

- 1 × Cisco 2911 Router
- 2 × Cisco 2960 Switches
- 4 × PCs
- Ethernet connections

---

## Network Topology

`R1 → SW1 → SW2`

**SW1:**
- PC1
- PC2

**SW2:**
- PC3
- PC4

---

## IP Addressing

| Device | IP Address | Subnet Mask | Gateway |
|---|---|---|---|
| R1 | 192.168.10.1 | 255.255.255.0 | — |
| PC1 | 192.168.10.11 | 255.255.255.0 | 192.168.10.1 |
| PC2 | 192.168.10.12 | 255.255.255.0 | 192.168.10.1 |
| PC3 | 192.168.10.13 | 255.255.255.0 | 192.168.10.1 |
| PC4 | 192.168.10.14 | 255.255.255.0 | 192.168.10.1 |

---

## Connectivity Test

PC1 successfully communicated with PC3 and PC4 using ICMP ping.

### PC1 → PC3
```text
Packets: Sent = 4, Received = 4, Lost = 0 (0% loss)
```

### PC1 → PC4
```text
Packets: Sent = 4, Received = 4, Lost = 0 (0% loss)
```

---

## Screenshots

### Network Topology
![Network Topology](screenshots/topology.png)

### Connectivity Test (Ping)
![Ping Test](screenshots/ping-test.png)

---

## Result

The LAN was successfully designed and configured in Cisco Packet Tracer. Static IPv4 addressing was implemented and cross-switch PC-to-PC communication was successfully verified.

---

## Files

- `ASSIGNMENT.pkt` – Cisco Packet Tracer project
- `Unit_1_LAN_Mini_Project_Report.pdf` – Complete Project Report (PDF)
- `Unit_1_LAN_Mini_Project_Report.docx` – Editable Project Report (Word)
- `screenshots/` – Topology and ping verification screenshots
