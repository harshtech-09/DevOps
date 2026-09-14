🌍 DNS Basics

DNS stands for Domain Name System.

It translates human-readable domain names into IP addresses.

For example:

google.com
     ↓
    DNS
     ↓
IP Address
     ↓
Web Server

Without DNS, users would need to remember IP addresses instead of domain names.

Basic DNS Flow
User enters:

https://example.com

        ↓

DNS Resolver

        ↓

DNS Server

        ↓

IP Address

        ↓

Web Server

        ↓

HTTP/HTTPS Response


🔄 How a Web Request Works

A simplified web request can be represented as:

              User
                │
                ▼
          Domain Name
                │
                ▼
              DNS
                │
                ▼
           IP Address
                │
                ▼
          TCP Connection
                │
                ▼
          HTTP / HTTPS
                │
                ▼
          Web Server
                │
                ▼
            Response


This helped me connect multiple networking concepts together instead of studying them individually.