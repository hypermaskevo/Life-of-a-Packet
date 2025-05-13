# Life-of-a-Packet
This lab explores the journey of a packet across multiple network segments, focusing on **MAC address changes**, **ARP resolution**, and **Layer 2/Layer 3 communication**.
## 🎯 Lab Objective

Track the **source and destination MAC addresses** at each hop while a packet travels between PCs in different networks. Understand how ARP is used to resolve MAC addresses and how Layer 2 and Layer 3 data changes during packet forwarding.

![image](https://github.com/user-attachments/assets/669efab9-cbf3-4c75-a6af-7d5427a79fc8)


## 🧪 Scenarios

### 1. PC1 Pings PC4
Trace the MAC address changes at the following points:
- **A.** PC1 → SW1
- **B.** SW1 → R1
- **C.** R1 → R2
- **D.** R2 → R3
- **E.** R3 → SW2
- **F.** SW2 → PC4

### 2. PC1 Pings PC3
Trace MAC address changes between:
- **A.** PC1 → SW1
- **B.** SW1 → PC3

### 3. PC4 Pings PC1
Reverse path: identify all MAC address changes back from PC4 to PC1.

---

## 🛠️ Tools & Commands

- Use **Simulation Mode** in Packet Tracer.
- Use the following CLI commands:
  - `show arp`
  - `show mac address-table`
  - `ping`
  - `ipconfig /all` (on PCs)

> ⚠️ Ping each target **once in realtime mode** before simulation to allow ARP learning to complete.

---

## 🧠 Key Learning Outcomes

- Understand ARP and MAC address resolution
- Visualize frame changes as a packet crosses routers
- Distinguish between Layer 2 and Layer 3 communication
- Learn how switches forward frames based on MAC tables
- Reinforce knowledge of how routers process packets across networks

---

## 📁 File Details

- **File Name:** `Day 12 - Life of a Packet.pkt`
- **Platform:** Cisco Packet Tracer
- **Difficulty:** 🟢 Beginner – Intermediate

## 👨‍💻 Author

Yurii Vysotskyi — surl.li/fsjjyv
---

