# Network Traffic Analysis Report

**Date:** 2025-02-21  
**Tool Used:** Wireshark  
**Capture File:** wireshark_capture1.pcap  

## Observations:
- **Excessive SYN Packets Detected**  
  - Possible indication of a SYN flood attack.
- **Unencrypted Credentials Detected**  
  - FTP login credentials were transmitted in plaintext.
- **High Number of ARP Requests**  
  - Possible ARP spoofing attack.

## Recommendations:
- Implement firewall rules to mitigate SYN flood attacks.
- Enforce encryption for sensitive network traffic.
- Monitor and limit ARP requests within the network.
