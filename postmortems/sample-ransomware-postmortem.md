# Postmortem Report: Ransomware Incident

**Date of Incident:** 2025-08-31  
**Prepared By:** Chris Spencer  

---

## 1. Incident Summary
On <date>, suspicious activity was detected involving unauthorized file encryption on a Windows server. Investigation revealed ransomware deployment via phishing email attachment.

---

## 2. Timeline
- 08:15 – Alert triggered in SIEM (multiple failed logins).
- 08:20 – User reported inability to access files.
- 08:30 – IR team confirmed ransomware note on shared drive.
- 08:45 – Containment: server isolated from network.
- 10:00 – Eradication: ransomware binary removed, backups validated.
- 12:00 – Recovery: data restored from backup.

---

## 3. Root Cause Analysis
- **Initial Access:** Spearphishing attachment (MITRE T1566.001).  
- **Execution:** Malicious macro executed in Word document.  
- **Privilege Escalation:** User had local admin rights.  
- **Impact:** 250 GB of data encrypted. No exfiltration detected.  

---

## 4. Business Impact
- 3 hours downtime for affected business unit.
- Estimated productivity loss: $25,000.

---

## 5. Lessons Learned
- Lack of MFA on user accounts increased risk.
- Endpoint security solution did not detect the malicious macro.
- Network share permissions were overly permissive.

---

## 6. Recommended Architecture Improvements
- Enforce MFA on all accounts.  
- Implement email sandboxing for attachments.  
- Review and limit shared drive permissions.  
- Improve SIEM rules to detect abnormal file encryption activity.  

---
