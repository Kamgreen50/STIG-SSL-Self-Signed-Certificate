# STIG – SSL Self-Signed Certificate (Plugin ID: 57582)

## Before
- Finding: System is using a self-signed SSL certificate (CN=Windows-Client2).
- Risk: Certificate not trusted by a recognized Certificate Authority (CA).
- Evidence:  

![Tenable Finding](before-tenable-finding.png)  
![Certificate Details](before-cert-details.png)  

## Remediation
- Replace the self-signed certificate with one issued by a trusted CA.
- Options:  
  1. Public CA (Let’s Encrypt, DigiCert, etc.)  
  2. Enterprise CA (Active Directory Certificate Services).  
- Verify the certificate chain using browser or `certutil`.

## After
- Expected outcome: Certificate trusted by a recognized CA.
- Evidence (placeholders for now – no VM access):  

![After Cert Placeholder](placeholder-after-cert-details.png)  
![After Tenable Placeholder](placeholder-after-tenable-rescan.png)  

---
**Note:** Actual remediation not performed due to no VM access. Placeholders used.


