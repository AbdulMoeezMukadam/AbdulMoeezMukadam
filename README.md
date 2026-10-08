# Abdul Moeez Mukadam, Security Project Portfolio

Hands-on offensive and defensive security projects. M.S. Cybersecurity (4.0 GPA), CEH v13. Each project below is real, runnable, and documented.

| Project | What it is | Focus |
| --- | --- | --- |
| [ioc-enricher](https://github.com/AbdulMoeezMukadam/ioc-enricher) | Threat-intel enrichment CLI for IPs, domains, URLs, and hashes (VirusTotal, AbuseIPDB, OTX) with a blended risk score and HTML reporting | SOC, Blue Team |
| [reconkit](https://github.com/AbdulMoeezMukadam/reconkit) | Authorized-use reconnaissance framework: host discovery, port scan, service ID, HTTP fingerprinting, scope-guarded | Red Team |
| [CyberSentinel](https://github.com/AbdulMoeezMukadam/CyberSentinel) | Python web-application vulnerability scanner with automated remediation guidance | Red Team, AppSec |
| [cyber-range](https://github.com/AbdulMoeezMukadam/cyber-range) | Integrated Active Directory lab: attack it, detect it in Splunk, hunt in it. 12 ATT&CK-mapped detections | SOC, Blue Team, Red Team |

## By role

**SOC Analyst**
- ioc-enricher: automates the first question in alert triage, is this indicator known-bad.
- cyber-range: the Splunk SOC lab, live detections firing on real attack telemetry, plus triage playbook and incident reports.

**Blue Team / Detection Engineering**
- cyber-range: 12 Splunk detections mapped to MITRE ATT&CK, a Sysmon config, a threat-hunting guide, and tuning notes.
- ioc-enricher: IOC enrichment to support investigation and response.

**Red Team / Offensive**
- reconkit: structured reconnaissance with an authorization scope guard built in.
- CyberSentinel: web vulnerability discovery across common OWASP issues.
- cyber-range: the attack-replay runbook (standard tools plus Atomic Red Team) that drives the whole lab.

## How each maps to my resume

Every bullet on my role-tailored resumes points to one of these repos:

- "Built a Python threat-intel enrichment tool..." -> ioc-enricher
- "Developed an authorized reconnaissance framework..." -> reconkit
- "Built a web application vulnerability scanner..." -> CyberSentinel
- "Stood up a Splunk SOC lab and authored ATT&CK-mapped detections..." -> cyber-range
- "Ran hypothesis-driven threat hunts..." -> cyber-range (threat-hunting guide)

## Contact

- Email: abdulmoeez.muk@gmail.com
- Portfolio: https://abdulmoeezmukadam.github.io
- GitHub: https://github.com/AbdulMoeezMukadam
