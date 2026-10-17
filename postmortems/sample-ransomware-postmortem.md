# Fictional Ransomware Incident — Example Postmortem

> **ILLUSTRATIVE SCENARIO ONLY:** This is a fictional example written to practice post-incident reporting. The date, timeline, findings, affected assets, data volume, and financial impact below are **invented**. This document is **not** a real-world investigation, exercise execution log, or validated forensic report.

**Example date:** August 31, 2025 (fictional)  
**Document purpose:** Incident response reporting practice

## 1. Scenario Summary

An illustrative organization reports inaccessible files on a Windows file server. In this invented scenario, an investigation attributes encryption to malware delivered through a phishing attachment.

## 2. Example Timeline (Fictional)

| Time | Scenario event |
| --- | --- |
| 08:15 | Monitoring system alerts on multiple unsuccessful logins |
| 08:20 | User reports inability to access files |
| 08:30 | Response team observes a ransom note |
| 08:45 | Affected system is isolated |
| 10:00 | Hypothetical malware removal and backup validation |
| 12:00 | Hypothetical restoration of affected data |

## 3. Hypothetical Findings

- **Initial access:** Spearphishing attachment (MITRE ATT&CK T1566.001)
- **Execution:** Malicious macro in a document
- **Privilege / exposure issue:** Inappropriate local administrative access
- **Illustrative impact:** 250 GB of encrypted data
- **Exfiltration:** No evidence assumed in the sample; a real investigation would require validation

These are sample narrative elements, not findings from collected evidence.

## 4. Hypothetical Business Impact

- Example downtime: three hours
- Example productivity loss: $25,000

These figures are invented to demonstrate how a report might present impact.

## 5. Potential Lessons Learned

- Require phishing-resistant authentication where feasible.
- Review endpoint protection, attachment handling, and execution controls.
- Apply least privilege to user and network share access.
- Validate offline or otherwise protected backups and recovery procedures.

## 6. Example Architecture Recommendations

- Strengthen identity controls, privilege management, and endpoint monitoring.
- Restrict network access to file services by business requirement.
- Create detection rules for suspicious encryption-related behavior.
- Test backup restoration and document achievable recovery objectives.

## Portfolio Note

This sample demonstrates **communication structure and reasoning**, not incident response execution. A future lab postmortem should include actual sanitized evidence, testing methods, limitations, and measured outcomes.
