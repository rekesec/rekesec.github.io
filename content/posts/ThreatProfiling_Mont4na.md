---
title: 'Threat Profiling: Mont4na'
date: 2024-08-31T17:00:00+00:00
draft: False
tags: ['Threat Actor', 'Mont4na', 'Cybercrime', 'SQL Injection', 'Threat Profiling']
---

# Executive Summary

**Mont4na** is a professional access broker known for selling leaked databases and exploiting web vulnerabilities. With a history of operations across major underground forums, Mont4na has targeted high-value sectors such as aviation, banking, and telecommunications, focusing on data breaches and monetization.

This post provides insights into their tactics, operations, and targeted victims.

# Mont4na: Overview

- **Role:** Initial Access Broker
- **Active Since:** November 10, 2020
- **Alternate Handles:** pumpedkicks
- **Key TTPs:** SQL Injection, RCE Vulnerabilities, Data Monetization
- **Victims:** Aviation, Banking, Education, Government, Automotive, and Telecommunications Sectors
- **Infrastructure:** Nmap, Zmap, SQLmap

## Key Timeline

1. **November 10, 2020:** Registered as "pumpedkicks" on an underground forum.
2. **January 21, 2021:** Sold SQL injection vulnerabilities affecting two major Italian banks.
3. **February 10, 2022:** Began offering leaked credentials on another underground forum under the name "mont4na."
4. **June 14, 2023:** Re-registered on a new re-created underground forum as "mont4na."
5. **August 6, 2023:** Final post selling data from AirCargo Communities servers.

# Tactics, Techniques, and Procedures (TTPs)

Mont4na employs a variety of methods to exploit vulnerabilities and monetize stolen data. Key techniques include:

1. **Vulnerability Scanning:**
   - Uses tools like Nmap and Zmap to identify vulnerable systems, focusing on CVE-2018-13379.

2. **SQL Injection Exploits:**
   - Leverages SQLmap to exfiltrate data from compromised systems.

3. **Credential Exploitation:**
   - Offers plaintext or hashed credentials, often including admin accounts.

4. **Web Shell Sales:**
   - Occasionally sells shell access to compromised servers.

# Victims and Attribution

Mont4na's activities have targeted companies in the USA, South Korea, Japan, and Europe, across sectors such as aviation, automotive, and government. Attribution efforts remain inconclusive, with conflicting claims of origin in Iran and the USA.

# Conclusion

Mont4na illustrates the persistent threat posed by professional access brokers with advanced technical capabilities. Their ability to exploit vulnerabilities across diverse sectors underscores the need for robust cybersecurity defenses and proactive monitoring.

---

### Metadata

| | |
|:-: | :-:| 
| Name | Mont4na |
| Active Since | 2020 |
| Motivation | Data Theft, Cybercrime |
| Associated Tools | Nmap, SQLmap |