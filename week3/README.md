 Project Activities

## 1. Advanced Log Analysis
- Correlated failed login attempts with outbound traffic
- Detected anomalies using Elastic Security rules
- Enriched logs using GeoIP integration

## 2. Threat Intelligence Integration
- Imported AlienVault OTX feeds into Wazuh
- Enriched alerts using IOC reputation data
- Performed threat hunting for MITRE ATT&CK T1078

## 3. Incident Escalation Practice
- Created incidents in TheHive
- Escalated alerts to Tier 2 analysts
- Drafted SITREPs and workflow automation

## 4. Alert Triage
- Investigated suspicious PowerShell execution alerts
- Validated IOCs using VirusTotal and OTX

## 5. Evidence Preservation
- Collected volatile data using Velociraptor
- Acquired memory dumps and generated SHA256 hashes
- Maintained chain-of-custody documentation

## 6. Full SOC Workflow Simulation
- Simulated Samba exploitation using Metasploit
- Detected attacks using Wazuh
- Contained threats using CrowdSec
- Escalated incidents through TheHive
- Generated incident reports and executive briefings

---

# MITRE ATT&CK Techniques Used

| Technique ID | Technique Name |
|--------------|----------------|
| T1078 | Valid Accounts |
| T1210 | Exploitation of Remote Services |

---

# Sample Detection Rule

```text
bytes_out > 1MB within 1 minute
