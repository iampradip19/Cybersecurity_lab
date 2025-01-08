# Nmap usage (Explains about how Nmap is used for penetration testing)

**It is basically used for network scanning. In kali Linux Nmap can be used in both GUI and CLI.**

**At first you need to specify which network you are scanning**

**If you're scanning devices on your local network, you have to use commands like 'ip a' or 'ifconfig' to find your local IP address on kali linux terminal and determine the range of devices on your network.**

## Port scanning - Identify open ports on the target
**Basic port scan**

**command** nmap target-IP

**Specific port scan**

**command** nmap ports-range target-IP

**All ports scan**

**command** nmap -p- target-IP

## Discovering Host - 
**command** nmap -A <target IP>

**example** nmap -A 192.168.246.1
## Version scan
nmap -sV 192.168.246.1
