# Internship-Task-3
Basic Vulnerability Scan on Your PC

Objectives
Learn and apply vulnerability scanning on a personal system.

Identify common vulnerabilities and their severity.

Understand the difference between vulnerability scanning and penetration testing.

Use CVSS scores to prioritize security risks.

Document scan results and remediation steps.

Tools Used
Nessus Essentials (free vulnerability scanner)

Target system: My local PC (localhost / local IP)

Scan report file: My-Basic-Network-Scan_xpnci3.xml

Scan Approach
Installed Nessus Essentials and initialized the vulnerability scanner.

Configured scan target as the local machine's IP address.

Ran a full vulnerability scan.

Waited approximately 30 minutes for scan completion.

Exported scan results in XML format (My-Basic-Network-Scan_xpnci3.xml).

Analyzed the report for vulnerabilities, their CVSS scores, and impacts.

Researched and documented mitigation strategies for critical issues.

Captured screenshots from Nessus interface showing key findings.

Key Findings
Presence of legacy protocols such as SMBv1 disabled.

Several open ports and unnecessary services detected.

Some settings exhibit weak or default configuration risks.

Vulnerabilities are classified with CVSS scores ranging from Low to Critical.

No false positives confirmed after manual verification.

Vulnerability Prioritization & Mitigation
Prioritized issues based on CVSS scores, exploit availability, and asset exposure.

Critical and High severity issues addressed first, including:

Keeping SMBv1 protocol disabled, higher versions are enabled and provide the required security.

Applying latest OS and software security patches.

Closing unused ports and services.

Documented lower severity issues for continuous monitoring.

Learnings
Gained practical insight into automated vulnerability scanning.

Developed skills in interpreting scan reports and CVSS scores.

Understood how to differentiate between scanning and penetration testing.

Enhanced knowledge of common personal computer vulnerabilities.
