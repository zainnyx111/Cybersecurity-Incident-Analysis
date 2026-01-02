# Equifax Data Breach (2017)

## 1. Incident Overview
In 2017, Equifax suffered a massive data breach affecting over 147 million individuals. Attackers exploited an unpatched Apache Struts vulnerability to access sensitive information. The breach was publicly disclosed in September 2017.

## 2. Compromised Assets
- Social Security numbers  
- Names, birth dates, addresses  
- Driver’s license numbers  
- Credit card numbers (~209,000 records)  

**Scope:** Extensive exposure of highly sensitive personal and financial data.

## 3. Attack Vector
- Exploitation of Apache Struts vulnerability (CVE-2017-5638)  
- Unpatched critical systems  
- Lack of monitoring and data segmentation  

## 4. Threat Elimination Strategy
1. **Containment:** Disconnect compromised servers  
2. **Patch Management:** Apply critical updates immediately  
3. **Credential Management:** Rotate passwords and admin credentials  
4. **Malware Removal:** Remove web shells/backdoors  
5. **Incident Response:** Notify affected individuals and regulators, forensic investigation  

## 5. Threat Prevention Strategy
- Automated patching and vulnerability management  
- Continuous monitoring of sensitive data access  
- Encrypt data at rest and in transit  
- Least-privilege access controls and MFA  
- Zero Trust architecture and network segmentation  
- Employee security awareness and training
