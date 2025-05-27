
Internship Task 1 - Nmap scan
# Cyber Security Internship – Task 1

## Objective:
Perform a TCP SYN scan using Nmap on my local network to identify open ports and potential security risks.

## Tools Used:
- Nmap (Port Scanner)
- Kali Linux
- Wireshark (optional)

## IP Range Used:
Local IP : 192.168.147.120      
Scanned Subnet : 192.168.147.0/24

## Commands Used 
sudo apt update        
ifconfig         
sudo nmap -sS 192.168.147.120 -oN scanresult.txt

## Steps Performed:
1. Found local IP using `ifconfig`
2. Ran TCP SYN scan using:
3. Captured results and noted:
- Host 192.168.147.120 has port 53 open (DNS service)
- Other hosts have all ports filtered or ignored
4. Saved results in `scanresult.txt`
5. Took screenshots as proof of activity
  
## Security Risk Identified 
53     DNS Risk of DNS Spoofing if not Secured

## Outcome :
- Network reconnaissance 
- Gained basic understanding of port scanning
- Identified running services and network exposure
  
## Files included 
scanresult.jpg        
ip result.jpg               
nmap result.jpg      
README.md - Command log

## Screenshot Proof:
(Uploaded below in repo)
