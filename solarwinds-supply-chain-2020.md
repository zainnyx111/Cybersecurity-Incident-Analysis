# SolarWinds Supply Chain Attack (2020)

## 1. Incident Overview
In December 2020, attackers compromised SolarWinds Orion software updates, affecting thousands of organizations globally, including U.S. government agencies. Malicious code (SUNBURST) allowed remote access and persistent surveillance, remaining undetected for months.

## 2. Compromised Assets
- IT management systems and networks using Orion software  
- Emails, credentials, and sensitive configurations  

**Scope:** 18,000+ organizations potentially impacted, enabling espionage and unauthorized access.

## 3. Attack Vector
- Compromise of SolarWinds software build system  
- Lack of code-signing verification and monitoring  
- Insufficient detection of abnormal communications  

## 4. Threat Elimination Strategy
1. **Containment:** Identify and isolate compromised systems  
2. **Credential Management:** Rotate all admin and service accounts, enforce MFA  
3. **Malware Removal:** Remove SUNBURST malware and backdoors  
4. **Incident Response:** Notify affected organizations, conduct forensics, collaborate with agencies  

## 5. Threat Prevention Strategy
- Secure software build pipelines and code-signing verification  
- Continuous monitoring of network traffic and endpoints  
- Least-privilege access and MFA  
- Zero Trust architecture and segmentation  
- Supply chain security awareness and threat intelligence sharing
