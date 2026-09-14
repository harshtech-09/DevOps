# 💻 Linux Networking Commands

I practiced several Linux networking commands useful for **troubleshooting, network diagnostics, and system administration**.

---

## 📡 `ping`

Used to test basic network connectivity between the local system and a remote host.

### Command

```bash
ping google.com
```

### 💡 What does it tell us?

```text
Is the destination reachable?
```

> ✅ **Use case:** Quickly check whether a remote host is reachable over the network.

---

## 🛰️ `traceroute`

Used to identify the **path packets take** to reach a destination.

### Command

```bash
traceroute google.com
```

### 🪟 Windows

```cmd
tracert google.com
```

### 🔍 Useful for identifying

- Network hops
- Routing problems
- Connection delays

> 💡 **Use case:** Helps identify where network traffic is getting delayed or interrupted.

---

## 🔌 `netstat`

Used to display **network connections, listening ports, and network statistics**.

### Command

```bash
netstat -tuln
```

Useful for checking which ports are currently listening on a system.

> ⚠️ **Note:** On many modern Linux distributions, `ss` is preferred over `netstat`.

### Modern alternative

```bash
ss -tuln
```

> 💡 **Use case:** Check which services are listening for network connections.

---

## 🌍 `curl`

A powerful command-line tool for making **HTTP requests** and interacting with web services.

### Basic Request

```bash
curl https://example.com
```

### Check HTTP Headers

```bash
curl -I https://example.com
```

### 🔍 Useful for

- 🧪 API testing
- 🌐 HTTP troubleshooting
- 🖥️ Checking web servers
- 🔗 Testing endpoints

> 💡 **Use case:** Quickly test whether a web server or API endpoint is responding correctly.

---

## 🔎 `dig`

Used for **DNS queries** and troubleshooting domain resolution.

### Basic Query

```bash
dig google.com
```

### Query Specific DNS Records

```bash
dig google.com A
dig google.com MX
dig google.com NS
```

| Record | Purpose |
|---|---|
| `A` | IPv4 address |
| `MX` | Mail server |
| `NS` | Name server |

> 💡 **Use case:** Useful for investigating DNS configuration and domain resolution problems.

---

## 🔍 `nslookup`

Another command-line tool used to query **DNS information**.

### Command

```bash
nslookup google.com
```

### 🔍 Useful for checking

- IP addresses
- DNS servers
- Domain resolution

> 💡 **Use case:** Quickly verify whether a domain is resolving correctly.

---

# 🧰 Quick Command Reference

| Command | Purpose |
|---|---|
| `ping` | Test network connectivity |
| `traceroute` | Trace the network path |
| `ss` | Check listening ports & connections |
| `netstat` | View network statistics & connections |
| `curl` | Test HTTP requests & APIs |
| `dig` | Perform DNS queries |
| `nslookup` | Check DNS resolution |

---

> 🚀 **DevOps Connection:** These commands are essential for troubleshooting connectivity, diagnosing services, testing APIs, investigating DNS issues, and understanding how systems communicate across a network.
