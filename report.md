# Network Scan Report

**Name:** Amrita  
**Date:** 22/10/2025

## Objective
To discover active hosts and open ports in the local network using Nmap.

## Summary of Findings
- 192.168.1.1 → Open ports: 22 (SSH), 80 (HTTP), 443 (HTTPS)
- 192.168.1.10 → Open ports: 3389 (RDP)
- 192.168.1.15 → Open ports: 23 (Telnet)

## Risks and Recommendations
- **Telnet (23):** Unencrypted — disable and replace with SSH.
- **RDP (3389):** Restrict access and enable Network Level Authentication.
- **HTTP (80):** Use HTTPS to secure communication.

## Conclusion
The scan successfully detected live hosts and their open services.  
Some insecure ports were identified and should be disabled or secured.
