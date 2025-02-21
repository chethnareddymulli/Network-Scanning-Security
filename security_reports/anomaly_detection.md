# Anomaly Detection Report

**Date:** 2025-02-21  
**Monitoring Tool:** Zeek (Bro IDS)  

## Detected Anomalies:
1. **DNS Amplification Attack**  
   - **Source:** 192.168.1.30  
   - **Description:** High-volume DNS queries detected, possibly being used for amplification.

2. **Unusual Network Behavior**  
   - **Description:** A system generated excessive outbound traffic, possibly a compromised host.

## Mitigation Steps:
- Rate-limit DNS queries to prevent amplification abuse.
- Investigate and isolate the affected system.
