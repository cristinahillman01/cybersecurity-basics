# Nmap Basics Lab 
# Objective 
The purpose of this lab was to gain hands-on experience using Nmap to identify opoen ports and understand how exposed services can increase a system;s attack surface. 
## Enviroment 
- Operating System : Windows
- Tool Used: Nmap 
- Target: Localhost ( 127.0.0.1) 
# Scan command used 
nmap 127.0.0.1 
Starting Nmap 7.98 ( https://nmap.org ) at 2026-01-03 19:09 +0000
Nmap scan report for localhost (127.0.0.1)
Host is up (0.00051s latency).
Not shown: 997 closed tcp ports (reset)
PORT     STATE SERVICE
135/tcp  open  msrpc
445/tcp  open  microsoft-ds
5357/tcp open  wsdapi

Nmap done: 1 IP address (1 host up) scanned in 0.68 seconds

## Analysis / Results 
The scan identified the network ports that were open on a local system. Open ports indicate services that are listening for connections , which could potentially be targeted by attacks if they are misconfigured or unpatched. Scanning localhost helped demonstrate how attackers can gather information about a system using simple reconnaissance techhniques. 
## Security Takeaway 
Reducing the number of open ports helps minimize the attack surface of a system. Services thAT are not required should be disabled or protected by a firewall. 

# Scan command used 
Starting Nmap 7.98 ( https://nmap.org ) at 2026-01-03 19:09 +0000
Nmap scan report for localhost (127.0.0.1)
Host is up (0.00051s latency).
Not shown: 997 closed tcp ports (reset)
PORT     STATE SERVICE
135/tcp  open  msrpc
445/tcp  open  microsoft-ds
5357/tcp open  wsdapi

Nmap done: 1 IP address (1 host up) scanned in 0.68 seconds
## Additional Scan 
A SYN was used to gather more detailed information about open ports while minimizing detection. 

## Reflection 
This lab helped reinforce the importance of reconnaisannce in cybersecurity. 
