# ☁️  AWS EC2 & Security Groups

I explored basic networking concepts using **Amazon EC2** and **AWS Security Groups**.

---

## 💻 What is EC2?

**Amazon EC2 (Elastic Compute Cloud)** provides resizable compute capacity in the AWS cloud.

An EC2 instance can be accessed through network protocols such as **SSH** and **HTTP**, depending on the configured network rules.

---

## 🛡️ What is a Security Group?

An **AWS Security Group** acts as a **virtual firewall** for an EC2 instance.

It controls:

- ⬇️ **Inbound traffic**
- ⬆️ **Outbound traffic**
- 🔌 **Allowed protocols**
- 🚪 **Allowed ports**
- 🌐 **Source / destination IP ranges**

---

## 📋 Example Security Group

| Type | Protocol | Port | Source | Purpose |
|---|:---:|:---:|---|---|
| 🖥️ **SSH** | TCP | `22` | My IP | Remote administration |
| 🌍 **HTTP** | TCP | `80` | `0.0.0.0/0` | Web traffic |
| 🔒 **HTTPS** | TCP | `443` | `0.0.0.0/0` | Secure web traffic |

> ⚠️ **Security Note:** Avoid exposing administrative ports such as SSH to the entire internet unless there is a specific reason to do so.

---

## 🔐 Security Principle: Least Privilege

A key concept I learned is **least-privilege network access**.

The goal is to allow **only the traffic that is actually required**.

### ❌ Avoid

```text
🌐 Allow all traffic
        ↓
   Increased Risk
```

### ✅ Prefer

```text
🎯 Required Traffic
        ↓
   🔌 Specific Ports
        ↓
   🌐 Trusted Sources
```

### 🧠 Simple Example

Instead of allowing SSH access from everywhere:

```text
❌ SSH
   Port: 22
   Source: 0.0.0.0/0
```

Prefer restricting SSH access to a trusted source:

```text
✅ SSH
   Port: 22
   Source: My IP
```

> 💡 **Key takeaway:** In cloud environments, network access should be as restrictive as practical while still allowing the application or service to function.
