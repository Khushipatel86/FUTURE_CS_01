# FUTURE_CS_01
TASK- 1
# Vulnerability Assessment Report

## Project Overview
This project presents a vulnerability assessment conducted on a legal test website using passive security testing techniques. The objective is to identify common web vulnerabilities, classify their risks, and provide remediation recommendations.

## Target Website
http://testphp.vulnweb.com  
(This is an intentionally vulnerable and legal testing website)

## Scope of Testing
- Passive vulnerability assessment only
- No exploitation performed
- No data modification


## Tools Used
- Nmap
- OWASP ZAP (Passive Scan)
- Browser Developer Tools
- Canva (Report Design)
- GitHub (Documentation)

## Key Findings
- Missing security headers
- Server information disclosure
- Cookies without security flags
- No HTTPS enforcement

## Risk Classification
- High: No HTTPS
- Medium: Missing CSP, Missing X-Frame-Options, Cookie issues
- Low: Server version disclosure

## Deliverables
- Professional vulnerability assessment report (PDF)
- Screenshots as evidence
- GitHub public repository

