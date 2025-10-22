# NMAP_TASK1 — Network Reconnaissance Assignment

**Name:** Amrita  
**Date:** 22/10/2025

## Description
This project demonstrates the use of Nmap for network reconnaissance.  
It includes host discovery, port scanning, and version detection.

## Commands Used
nmap -sn 192.168.1.0/24 -oN outputs/host_discovery.txt
nmap -sS 192.168.1.0/24 -oN outputs/syn_scan.txt -oX outputs/syn_scan.xml
nmap -sV -O 192.168.1.1 -oN outputs/detailed_192.168.1.1.txt


## Files in Repo
- `outputs/` → Raw Nmap scan results  
- `screenshots/` → Screenshots of commands and outputs  
- `report.md` → Summary and findings
