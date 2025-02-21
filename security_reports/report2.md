# Database Security Assessment

**Date:** 2025-02-21  
**Target:** 192.168.1.20 (MySQL Server)  
**Scanner Used:** Nessus  

## Findings:
1. **Weak Password Policy**  
   - **Severity:** High  
   - **Description:** The MySQL database allows weak passwords, increasing the risk of brute-force attacks.  
   - **Recommendation:** Enforce strong password policies.

2. **Open Database Port (3306)**  
   - **Severity:** Medium  
   - **Description:** MySQL is exposed on the network, allowing potential attackers to attempt access.  
   - **Recommendation:** Restrict MySQL access to internal systems only.
