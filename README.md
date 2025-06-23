# nmap-wireshark-task
Project using Nmap and Wireshark for local network scanning
# Task 1 – Nmap and Wireshark Network Scanning

## 🎯 Objective

The aim of this task is to scan my local network using **Nmap** to identify open ports, and then use **Wireshark** to analyze the network traffic during the scan.

## 🛠 Tools Used

- **Nmap** (on Windows) – to perform the network scan
- **Wireshark** (on Kali Linux) – to capture the packets
- **VMware** – to run Kali Linux
- **GitHub** – to submit and share the project files

## 📌 Steps I Followed

### 👉 Nmap Scan

1. I installed Nmap on Windows.
2. Found my local IP range (192.168.1.0/24).
3. Ran this command in Windows CMD:
```bash
nmap -sS 192.168.1.0/24 -oN scan_results.txt
4.This created a file scan_results.txt which I saved using Notepad.

##👉** Wireshark Packet Capture

  1)I used Wireshark in Kali Linux (in VMware Player).
  2)Started capturing on the correct interface.
  3)While capturing, I ran the Nmap scan from Windows.
  4)Then I exported the packet capture as plain text: wireshark_output.txt

##Files in This Project:
File Name and Description
*scan_results.txt - Nmap scan results (open ports, filtered ports)
*wireshark_output.txt - Exported packet capture in text format

📌 What I Learned
  * How to find my IP range
  * How to scan a network using Nmap
  * How to use Wireshark to see what’s happening in the background
  * How to recognize open and filtered ports
  * How to save, organize, and submit files through GitHub

Submitted By
Shubha P





