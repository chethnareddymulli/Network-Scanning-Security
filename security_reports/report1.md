# Web Server Security Assessment

**Date:** 2025-02-21  
**Target:** 192.168.1.10 (Apache Web Server)  
**Scanner Used:** Nessus  

## Findings:
1. **CVE-2022-12345 - Apache 2.4.29 Remote Code Execution**  
   - **Severity:** High  
   - **Description:** The detected Apache version is outdated and vulnerable to RCE attacks.  
   - **Recommendation:** Upgrade Apache to the latest version.

2. **Weak TLS Configuration**  
   - **Severity:** Medium  
   - **Description:** The server supports outdated TLS versions (TLS 1.0, 1.1).  
   - **Recommendation:** Disable TLS 1.0/1.1 and enforce TLS 1.2+.
