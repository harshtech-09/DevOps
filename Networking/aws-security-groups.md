☁️ AWS EC2 & Security Groups

I explored basic networking concepts using Amazon EC2 and AWS Security Groups.

What is EC2?

Amazon EC2 provides resizable compute capacity in the AWS cloud.

An EC2 instance can be accessed through network protocols such as SSH and HTTP depending on the configured network rules.

What is a Security Group?

A Security Group acts as a virtual firewall for an EC2 instance.

It controls:

• Inbound traffic
• Outbound traffic
• Allowed protocols
• Allowed ports
• Source/destination IP ranges

Example Security Group

Type	  Protocol   Port	Source	  Purpose
SSH	  TCP	   22	My IP	  Remote administration
HTTP	  TCP	   80	0.0.0.0/0	  Web traffic
HTTPS  TCP	   443	0.0.0.0/0	  Secure web traffic

Security Principle

A key concept I learned is least-privilege network access.

Instead of opening unnecessary ports to everyone:

❌ Allow all traffic
        ↓
    Increased risk

Prefer:

✅ Allow only required traffic
        ↓
   Specific ports
        ↓
   Trusted sources