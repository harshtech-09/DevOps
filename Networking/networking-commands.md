💻 Linux Networking Commands

I practiced several Linux networking commands useful for troubleshooting and system administration.
__________________________________________________________________________________________________________

ping

Used to test basic network connectivity between the local system and a remote host.

ping google.com

Example use:

Is the destination reachable?
__________________________________________________________________________________________________________

traceroute

Used to identify the path packets take to reach a destination.

traceroute google.com

On Windows:

tracert google.com

Useful for identifying:

• Network hops
• Routing problems
• Connection delays
__________________________________________________________________________________________________________

netstat

Used to display network connections, listening ports and network statistics.

netstat -tuln

Useful for checking which ports are listening on a system.

Note: On many modern Linux distributions, ss is preferred over netstat.

Example:

ss -tuln
__________________________________________________________________________________________________________

curl

A powerful command-line tool for making HTTP requests and interacting with web services.

curl https://example.com

Check HTTP headers:

curl -I https://example.com

Useful for:

• API testing
• HTTP troubleshooting
• Checking web servers
• Testing endpoints
__________________________________________________________________________________________________________

dig

Used for DNS queries and troubleshooting domain resolution.

dig google.com

Query specific DNS records:

dig google.com A
dig google.com MX
dig google.com NS
__________________________________________________________________________________________________________

nslookup

Another tool used to query DNS information.

nslookup google.com

Useful for quickly checking:

• IP addresses
• DNS servers
• Domain resolution




































______________________________________________________________________________________________________________________