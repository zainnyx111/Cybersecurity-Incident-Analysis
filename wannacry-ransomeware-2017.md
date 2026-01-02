# WannaCry Ransomware Attack (2017)

## 1. Incident Overview
In May 2017, WannaCry ransomware affected over 200,000 computers across 150+ countries. It encrypted files and demanded Bitcoin ransom. Critical sectors, including healthcare, were disrupted, causing operational delays and financial losses.

## 2. Compromised Assets
- Windows systems using SMBv1 protocol  
- Data on infected machines encrypted and inaccessible  

**Scope:** Hospitals, businesses, and government systems disrupted globally.

## 3. Attack Vector
- Exploited EternalBlue SMBv1 vulnerability  
- Unpatched systems and lack of endpoint protection  
- Insufficient network segmentation  

## 4. Threat Elimination Strategy
1. **Containment:** Disconnect infected machines and disable SMBv1  
2. **Patching:** Apply MS17-010 updates  
3. **Malware Removal:** Clean infected systems and restore backups  
4. **Incident Response:** Notify stakeholders, conduct forensic investigation  

## 5. Threat Prevention Strategy
- Regular patching and retirement of unsupported software  
- Network segmentation and Zero Trust principles  
- Endpoint detection and monitoring  
- Offline, encrypted backups for recovery  
- Employee awareness and ransomware training
