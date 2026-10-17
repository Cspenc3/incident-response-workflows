# Incident Response Workflows

**Status: Written playbooks and templates, plus an illustrative postmortem.** This repository documents response process design. It does **not** represent multiple completed investigations or a deployed SIEM/SOAR platform.

The documentation is informed by [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final) and is meant to support structured incident preparation, analysis, response, recovery, and continuous improvement. It is not a claim of formal NIST compliance.

## Available Materials

| Document | What it contains |
| --- | --- |
| [Phishing incident playbook](./playbooks/phishing-playbook.md) | Written detection, triage, containment, recovery, and follow-up steps |
| [Incident report template](./templates/incident-report-template.md) | Reusable structure for reporting observations and decisions |
| [Executive summary template](./templates/executive-summary-template.md) | Concise stakeholder communication |
| [Communications plan template](./templates/comms-plan-template.md) | Incident notification and coordination prompts |
| [Ransomware postmortem — fictional example](./postmortems/sample-ransomware-postmortem.md) | Illustrative report format with **invented** scenario and figures |

## How to Evaluate This Work

These files show **process design and documentation**, not evidence that the listed response steps were performed in a real incident. Future case studies should link sanitized logs, test environments, validated findings, and measurable outcomes.

## Relevant Completed Lab

- [SOC Incident Response Lab](https://github.com/Cspenc3/security-portfolio/tree/main/soc-incident-response-lab) — packet-analysis screenshots, DNS anomaly investigation, and Linux host-review evidence.
- [Network fundamentals and study notes](https://github.com/Cspenc3/network-triage-pcap) — reference notes and planned traffic-analysis exercises.
- [Cybersecurity portfolio](https://github.com/Cspenc3/security-portfolio) — consolidated project index.

## Next Steps

- Expand the phishing playbook with decision points and evidence collection requirements.
- Validate a response workflow in an isolated lab and publish results.
- Explore Splunk investigations with real lab-generated events.
- Connect incident response decisions to system design, segmentation, and industrial availability constraints.

## About

Christopher Spencer | CompTIA CySA+ | B.S. Cybersecurity (SNHU, in progress) | Developing OT/ICS security engineering skills.
