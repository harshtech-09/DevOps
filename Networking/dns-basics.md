# 🌍  DNS Basics

**DNS (Domain Name System)** translates human-readable domain names into IP addresses.

For example:

```text
🌐 google.com
      │
      ▼
   🔎 DNS
      │
      ▼
📍 IP Address
      │
      ▼
🖥️ Web Server
```

> 💡 **Why DNS matters:** Without DNS, users would need to remember IP addresses instead of easy-to-use domain names.

---

## 🔄 Basic DNS Flow

When a user enters a website address, DNS helps find the server's IP address.

```text
👤 User
   │
   │  https://example.com
   ▼
🔎 DNS Resolver
   │
   ▼
🌐 DNS Server
   │
   ▼
📍 IP Address
   │
   ▼
🖥️ Web Server
   │
   ▼
📦 HTTP / HTTPS Response
```

### 🧠 In Simple Words

```text
Domain Name
     ↓
    DNS
     ↓
 IP Address
     ↓
Web Server
     ↓
  Response
```

> 🚀 **Key idea:** DNS acts like the **phonebook of the Internet** — it helps translate a domain name into the IP address needed to reach the server.

---

# 🔄 7. How a Web Request Works

A web request combines several networking concepts together.

### 🌐 Request Flow

```text
👤 User
   │
   ▼
🌐 Domain Name
   │
   ▼
🔎 DNS Resolution
   │
   ▼
📍 IP Address
   │
   ▼
🔗 TCP Connection
   │
   ▼
🔒 HTTP / HTTPS
   │
   ▼
🖥️ Web Server
   │
   ▼
📦 Response
```

### 🧩 Putting Everything Together

```text
        👤 USER
          │
          ▼
    🌐 Domain Name
          │
          ▼
      🔎 DNS
          │
          ▼
     📍 IP Address
          │
          ▼
   🔗 TCP Connection
          │
          ▼
    🔒 HTTP / HTTPS
          │
          ▼
     🖥️ Web Server
          │
          ▼
       📦 Response
```

> 💡 **What I learned:** This helped me connect multiple networking concepts together instead of studying them individually.

---

## 🎯 Key Concept

| Step | What Happens |
|:---:|---|
| **1** | 👤 User enters a domain name |
| **2** | 🔎 DNS resolves the domain |
| **3** | 📍 IP address is obtained |
| **4** | 🔗 TCP connection is established |
| **5** | 🔒 HTTP / HTTPS request is sent |
| **6** | 🖥️ Web server processes the request |
| **7** | 📦 Response is returned to the user |
