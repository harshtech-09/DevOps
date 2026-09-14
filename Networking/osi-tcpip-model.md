🔗 OSI & TCP/IP Models

Understanding networking models is essential for troubleshooting and understanding how data moves between systems.

OSI Model

Layer	 Name	            Purpose	                                         Examples
7	    Application	   Provides network services to applications	        HTTP, HTTPS, DNS, SSH
6	    Presentation	   Data formatting, encryption and compression	     SSL/TLS, JPEG, JSON
5	    Session	         Establishes and manages sessions	                 RPC, NetBIOS
4	    Transport	      Reliable/fast end-to-end communication	           TCP, UDP
3	    Network	         Routing and logical addressing	                 IP, ICMP
2	    Data Link	      Frame delivery and MAC addressing	              Ethernet, ARP
1	    Physical	      Transmission of raw bits	                       Cables, Fiber, Radio

Example

When accessing a website:

Browser
   ↓
HTTP / HTTPS
   ↓
TCP
   ↓
IP
   ↓
Ethernet
   ↓
Physical Network

Understanding these layers helps identify where a networking problem is occurring.



🌐 TCP/IP Model

The TCP/IP model is commonly used in real-world networking and Internet communication.

Layer	             Examples
Application	       HTTP, HTTPS, DNS, SSH, FTP
Transport	       TCP, UDP
Internet	          IP, ICMP
Network Access	    Ethernet, Wi-Fi, ARP

OSI vs TCP/IP
OSI Model                 TCP/IP Model

Application  ─────┐
Presentation ─────┤
Session      ─────┤──→   Application
Transport    ─────────→  Transport
Network      ─────────→  Internet
Data Link    ─────┐
Physical     ─────┴──→   Network Access