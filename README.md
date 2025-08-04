# Cyber Security Internship – Task 1

## 🔍 Task: Scan Your Local Network for Open Ports

Objective:  
Discover open ports on devices in your local network to understand network exposure using Nmap.

---

## 🛠 Tools Used:
- Nmap – Port scanning


---

## 🖥️ Steps Performed:

1. Installed Nmap from the [official website](https://nmap.org/download.html).
2. Identified local IP range using:
   `bash
   ipconfig (Windows) or ifconfig/ip a (Linux)

Example local IP: 192.168.1.0/24 3. Ran TCP SYN scan using the following command:

nmap -sS 192.168.1.0/24 -oN result.txt

4. Collected IP addresses and open ports.


5. Saved results in result.txt.




---

📄 Sample Output (from result.txt):

Nmap scan report for 192.168.1.1
Host is up (0.0020s latency).
Not shown: 997 closed ports
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https


---

📚 Key Learnings:

Learned how to identify open ports using Nmap.

Understood the risks associated with exposed services like SSH and HTTP.

Observed how port scanning helps assess network exposure.
