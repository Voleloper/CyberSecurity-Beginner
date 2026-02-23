# 🐧 Linux for Cyber Security (KENDİNE SİBER)
This repository is for educational and ethical security research only.
Use these tools responsibly and legally.

![Linux](https://img.shields.io/badge/Platform-Linux-black?logo=linux)
![Security](https://img.shields.io/badge/Focus-CyberSecurity-red)
![Shell](https://img.shields.io/badge/Scripting-Bash-green)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)

A technical guide and reference for using Linux as a professional cyber security environment.  
Focused on terminal mastery, offensive security, defensive security, and automation.

---

## 📌 Overview

1- FİRST HARVARD UNIVERSITY CS50's Introduction to Cybersecurity Watch and take notes. -- 

2- REGISTER TRYHACKME AND HACKTHEBOX FIRST TRYHACKME SECOND HACKTHEBOX(First, select the tryhackme file above and start from there, then select hackthebox)

3- WINDOWS PC KALI LINUX = https://www.virtualbox.org  AND  https://www.kali.org/get-kali/#kali-virtual-machines  ==== WATCH INSTALL VIDEO https://www.youtube.com/watch?v=ZJFu0AoAY_g

4- MAC OS BOOT LINUX = WATCH TO VIDEO https://www.youtube.com/watch?v=6aW5qMe3Cng AND https://techolay.net/m2-macbooka-nasil-ubuntu-kurulur-adim-adim-rehber/

5- MAC OS UTM KALI LINUX = WATCH TO VIDEO https://www.youtube.com/watch?v=U09soewiu18

6- LINUX COMMAND LEARNING Linux Commands for Cyber Security Beginners https://github.com/Voleloper/CyberSecurity-Start/blob/main/Linux%20Commands%20for%20Cyber%20Security%20Beginners


Linux is the foundation of modern cyber security operations.  
This repository documents essential Linux knowledge required for:

- penetration testing
- incident response
- system hardening
- network analysis
- privilege escalation
- security automation

The goal is to build **real-world operational Linux skills**.

---

## ⚙️ Core Linux Skills

### 🔐 Permissions & Privilege Model

Understanding Linux permissions is critical for security:

- UID / GID architecture
- rwx permission model
- SUID / SGID / sticky bit
- sudo configuration
- `/etc/passwd` & `/etc/shadow` analysis

---

### 🧠 Process & System Monitoring

Detecting abnormal behavior requires system visibility:

- process tree analysis
- daemon management
- systemd services
- kernel log inspection
- signal handling (SIGTERM / SIGKILL)

---

### 🌐 Networking & Traffic Analysis

Linux networking stack enables deep inspection:

- socket analysis
- routing tables
- firewall rules
- packet capture
- port monitoring

---

### 🤖 Automation & Shell Scripting

Automation is mandatory in security operations:

- Bash scripting
- cron scheduling
- log parsing
- scanning automation
- monitoring scripts

---

## 🔴 Offensive Security Usage

Linux is the standard platform for red team operations:

- exploit development
- payload generation
- lateral movement
- persistence techniques
- privilege escalation

---

## 🔵 Defensive Security Usage

Linux powers defensive infrastructure:

- server hardening
- intrusion detection
- forensic analysis
- log centralization
- SIEM integration

---

## 🧰 Essential Linux Commands

### File & Permission Management

```
ls -la
chmod
chown
stat
getfacl
setfacl
umask
```

### User & Privilege

```
whoami
id
sudo -l
su
passwd
groups
```

### Process Monitoring

```
ps aux
top / htop
pstree
kill / killall
lsof
```

### System & Logs

```
dmesg
journalctl
last
history
```

### Networking

```
ip a
ip route
ss -tulnp
netstat -an
tcpdump
traceroute
```

### File Analysis

```
find
grep
strings
file
hexdump
xxd
```

---

## 🔍 Security Tools

### Recon / Enumeration

```
nmap
enum4linux
whois
dig
theHarvester
```

### Exploitation

```
metasploit-framework
searchsploit
msfvenom
sqlmap
```

### Web Security

```
burpsuite
nikto
wfuzz
gobuster
```

### Network Analysis

```
wireshark
tcpdump
ettercap
```

### Password Attacks

```
hydra
john
hashcat
```

### Forensics / Reverse Engineering

```
binwalk
foremost
volatility
radare2
```

---

## 🎯 Goal

Master Linux → understand systems deeply → operate securely.

Linux proficiency is not optional in cyber security.  
It is the foundation.

---

## 📜 License

MIT License — free to use, modify, and learn.

---

⭐ If this repo helps you, consider starring it.
