# Lab 3 : OSI & TCP/IP Models – Simulation Mode

## Lab 3 Objective :
Visualize how network traffic moves through the OSI and TCP/IP models using Packet Tracer’s Simulation Mode.

## 🛠️ Topology
- 2 Routers (R1, R2)
- 2 Switches (SW1, SW2)
- 1 Server (SRV1)
- 1 PC (PC1)

## 📡 Protocols Observed

| Protocol | Layer | Purpose |
| :--- | :--- | :--- |
| STP | Layer 2 | Prevents switching loops |
| OSPF | Layer 3 | Dynamic routing |
| DHCP | Layer 7 | Auto-assigns IP addresses |

## 🔍 Key Takeaways
- **STP** → Layers 1 & 2 only (Ethernet frame)
- **OSPF** → Layers 1–3 (includes IP addresses)
- **DHCP** → Layers 1–7 (UDP segment, IP header, Ethernet frame)

> ⚡ Layers 5–6 are not shown because the TCP/IP model combines them into the Application Layer.

## ✅ What I Learned
- How to use Packet Tracer’s **Simulation Mode**
- How different protocols operate at different OSI layers
- Real-world **encapsulation** process

## 📁 Lab File
[Download .pkt file](./lab-file.pkt)

---

🏷️ `CCNA` `Packet Tracer` `OSI Model` `TCP/IP` `Jeremy's IT Lab`
