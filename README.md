=========================================
👤 AUTHOR DETAILS
=========================================
Name: Harshil Patel

=========================================
🔐 FIREWALL CONFIGURATION PROJECT
(Linux UFW + Windows Firewall)
=========================================

📘 OVERVIEW:
This project demonstrates firewall configuration and network traffic filtering using:
- UFW (Uncomplicated Firewall) on Linux
- Windows Defender Firewall on Windows

It includes creating, managing, testing, and removing firewall rules to improve system security.

=========================================
🧰 TOOLS USED:
=========================================
- Linux (Ubuntu/Kali)
- UFW Firewall (Linux)
- Windows Defender Firewall
- Command Line Interface (CLI)
- Windows Firewall Advanced Security (wf.msc)

=========================================
🎯 OBJECTIVES:
=========================================
- Understand firewall basics
- Configure inbound and outbound rules
- Allow and block ports and IP addresses
- Test firewall behavior
- Learn network security fundamentals

=========================================
🐧 LINUX FIREWALL (UFW COMMANDS)
=========================================

1. Enable Firewall:
sudo ufw enable

2. Check Status:
sudo ufw status
sudo ufw status numbered

3. Default Rules:
sudo ufw default deny incoming
sudo ufw default allow outgoing

4. Allow SSH (Port 22):
sudo ufw allow 22

5. Block Telnet (Port 23):
sudo ufw deny 23

6. Allow HTTP & HTTPS:
sudo ufw allow 80
sudo ufw allow 443

7. Allow Port Range:
sudo ufw allow 1000:2000/tcp

8. Allow Specific IP:
sudo ufw allow from 192.168.1.100

9. Deny Specific IP:
sudo ufw deny from 192.168.1.200

10. Delete Rule:
sudo ufw delete <rule_number>

11. Reset Firewall:
sudo ufw reset

=========================================
🪟 WINDOWS FIREWALL (STEPS)
=========================================

1. Open Firewall:
Press Win + R → type wf.msc

2. View Rules:
Inbound Rules / Outbound Rules

3. Create Rule:
- New Rule → Port
- TCP/UDP → Enter Port Number
- Choose Allow or Block
- Apply and Name Rule

4. Example Rules:
- Block Port 23 (Telnet)
- Allow Port 22 (SSH)
- Allow Port 80 (HTTP)
- Allow Port 443 (HTTPS)

5. Delete Rule:
Right click rule → Delete

=========================================
🧪 TESTING:
=========================================
- Tested blocked port using telnet:
  telnet localhost 23
- Verified rules using:
  sudo ufw status

=========================================
📊 OUTCOME:
=========================================
- Learned firewall configuration
- Understood packet filtering
- Gained Linux + Windows firewall experience
- Improved cybersecurity fundamentals

=========================================
📌 PROJECT TYPE:
=========================================
Cybersecurity Internship Task
Firewall Configuration & Network Security Basics

=========================================
🚀 NOTE:
=========================================
This project is for educational purposes only.
