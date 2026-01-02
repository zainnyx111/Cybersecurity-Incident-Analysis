# Yahoo Data Breach (2013–2016)

## 1. Incident Overview
Between 2013 and 2016, Yahoo suffered one of the largest data breaches in history. Attackers gained unauthorized access to user accounts via forged authentication cookies, bypassing passwords entirely. Over 3 billion accounts were affected, impacting users worldwide. The breach was publicly disclosed in 2016.

## 2. Compromised Assets
- Names and email addresses  
- Hashed passwords  
- Security questions and answers  

**Scope:** Billions of user accounts compromised, enabling access to sensitive communications and personal information.

## 3. Attack Vector
- Likely spear phishing of Yahoo employees to steal admin credentials  
- Lack of multi-factor authentication (MFA)  
- Forged cookie generation allowed unauthorized login  
- Insufficient monitoring of authentication systems  

## 4. Threat Elimination Strategy
1. **Containment:** Invalidate all active sessions and isolate cookie-signing servers  
2. **Credential Management:** Reset admin and user passwords, rotate cryptographic keys  
3. **Malware Removal:** Remove malicious scripts and conduct full forensic analysis  
4. **Incident Response:** Notify users and regulators, preserve evidence for investigations  

## 5. Threat Prevention Strategy
- Strong cookie-signing mechanisms and key management  
- Multi-factor authentication for all admins  
- Continuous monitoring of authentication and account activity  
- Phishing awareness training for employees  
- Zero Trust architecture and network segmentation  
- Policies for regular credential rotation and incident response updates
