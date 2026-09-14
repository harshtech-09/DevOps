#  🔗 OSI Model

The **OSI (Open Systems Interconnection) Model** helps us understand how data moves between systems by dividing network communication into **7 layers**.

## 📊 OSI Layers

| Layer | Name | Purpose | Examples |
|:---:|---|---|---|
| **7** | Application | Provides network services to applications | HTTP, HTTPS, DNS, SSH |
| **6** | Presentation | Data formatting, encryption & compression | SSL/TLS, JPEG, JSON |
| **5** | Session | Establishes & manages sessions | RPC, NetBIOS |
| **4** | Transport | End-to-end communication | TCP, UDP |
| **3** | Network | Routing & logical addressing | IP, ICMP |
| **2** | Data Link | Frame delivery & MAC addressing | Ethernet, ARP |
| **1** | Physical | Transmission of raw bits | Cable, Fiber, Radio |

---

## 🌐 Example: Opening a Website

When you open a website, data passes through multiple networking layers:

```text
Application
    ↓
HTTP / HTTPS
    ↓
Transport
    ↓
TCP
    ↓
Network
    ↓
IP
    ↓
Data Link
    ↓
Ethernet
    ↓
Physical Network
```

> 💡 **Why it matters:** Understanding these layers helps identify where a networking problem is occurring.

---

#  🌐 TCP/IP Model

The **TCP/IP model** is commonly used for real-world networking and Internet communication.

## 📊 TCP/IP Layers

| Layer | Examples |
|---|---|
| **Application** | HTTP, HTTPS, DNS, SSH, FTP |
| **Transport** | TCP, UDP |
| **Internet** | IP, ICMP |
| **Network Access** | Ethernet, Wi-Fi, ARP |

## 🔄 OSI vs TCP/IP

| OSI Model | TCP/IP Model |
|---|---|
| Application | Application |
| Presentation | Application |
| Session | Application |
| Transport | Transport |
| Network | Internet |
| Data Link | Network Access |
| Physical | Network Access |

---
