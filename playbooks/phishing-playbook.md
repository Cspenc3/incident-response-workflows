# Phishing Incident Playbook

## Phase 1: Detection & Analysis
- Alert from SIEM or user-reported suspicious email.
- Collect email headers, attachments, and URLs.
- Check against threat intel feeds.

## Phase 2: Containment
- Quarantine suspicious emails.
- Block malicious domains/URLs at email gateway/firewall.
- Reset credentials for affected accounts.

## Phase 3: Eradication & Recovery
- Remove phishing messages from all inboxes.
- Ensure no malware persistence remains.
- Monitor for re-delivery attempts.

## Phase 4: Post-Incident
- Conduct user awareness training if applicable.
- Update detection rules (SIEM, Sigma).
- Document timeline and lessons learned.

**MITRE ATT&CK:**  
- T1566.001 – Spearphishing Attachment  
- T1566.002 – Spearphishing Link
