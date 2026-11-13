# NETWORKWALKS-WEEK2-CYBERSECURITY-HOUDA-REPORT
# CYBERSECURITY INTERNSHIP – WEEK 2 REPORT

### Footprinting, Reconnaissance & Network Scanning

**Program:** Networkwalks Cybersecurity Internship  
**Batch:** B084  
**Trainee:** Houda Benomar  
**Date:** 13 November 2026  
**Modules completed:** W2-PM1 – Kali Linux Tools | W2-PM5 – Zenmap Scanning

---

## 1. Disclaimer

All activities described in this report were conducted for educational purposes within the assigned internship scope and on my own local network. Testing was limited to authorized targets. No exploitation or unauthorized access was performed.

## 2. Introduction

This report documents my Week 2 practical activities during the Networkwalks Cybersecurity Internship.

The objectives were:
- To learn basic reconnaissance and footprinting techniques using Kali Linux.
- To identify publicly available technical information about an authorized target.
- To discover active devices on my own local network using Zenmap.
- To document the results and understand their security implications.

## 3. Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Linux environment for cybersecurity tools |
| WHOIS | Domain registration information |
| WhatWeb | Website technology identification |
| Nslookup | DNS resolution |
| Curl -I | HTTP response headers |
| Wafw00f | WAF detection |
| DNSRecon | DNS record enumeration |
| Zenmap | Network scanning and topology |
| Windows CMD | Local network information |

## 4. Activities Performed

### 4.1 Footprinting and Reconnaissance – W2-PM1

I used six Kali Linux tools to understand how reconnaissance works.

**1. WHOIS**

Command:
`whois [AUTHORIZED_DOMAIN]`

Purpose: Retrieve publicly available domain registration information.

**2. WhatWeb**

Command:
`whatweb [AUTHORIZED_DOMAIN]`

Purpose: Identify website technologies, frameworks and CMS information.

**3. Nslookup**

Command:
`nslookup [AUTHORIZED_DOMAIN]`

Purpose: Resolve a domain name to its IP address.

**4. Curl -I**

Command:
`curl -I https://[AUTHORIZED_DOMAIN]`

Purpose: Inspect HTTP response headers.

**5. Wafw00f**

Command:
`wafw00f https://[AUTHORIZED_DOMAIN]`

Purpose: Check whether a Web Application Firewall is detected.

**6. DNSRecon**

Command:
`dnsrecon -d [AUTHORIZED_DOMAIN]`

Purpose: Enumerate DNS information and records.

*Evidence: See the screenshots folder.*

### 4.2 Network Scanning – W2-PM5

I used Zenmap to discover active devices on my own local network.

The activities included:
- Identifying my local IP address and subnet.
- Performing a Ping Scan.
- Identifying live hosts.
- Collecting IP and MAC address information.
- Generating a network topology.

**Results (public version – anonymized):**

| Item | Result |
|---|---|
| Network | Private local LAN |
| Subnet | Anonymized |
| Number of live hosts | 2 |
| Host 1 | Home router |
| Host 2 | Personal computer |
| MAC addresses | Redacted |

The network topology was generated and saved as a PDF.

## 5. Risk Analysis

| Observation | Potential impact | Risk |
|---|---|---|
| Website technology information is visible | May help identify software requiring security review | Low |
| HTTP headers expose technical information | May assist reconnaissance | Low |
| DNS records provide infrastructure information | May help map the domain infrastructure | Low |
| Live devices are visible on a local network | Unknown devices should be investigated | Medium |

These observations are not confirmed vulnerabilities. Further authorized testing would be required to validate any security weakness.

## 6. Recommendations

1. Keep website technologies and plugins updated.
2. Review HTTP response headers.
3. Regularly check DNS records.
4. Maintain and monitor firewall configurations.
5. Scan local networks periodically.
6. Investigate unknown devices.
7. Perform security testing only with proper authorization.

## 7. Conclusion

During Week 2, I learned how to use six Kali Linux reconnaissance tools and Zenmap for local network discovery.

I improved my understanding of domain information, DNS resolution, HTTP headers, WAF detection, network scanning and topology mapping.

This practical experience helped me understand the importance of reconnaissance in cybersecurity and the need to document technical findings clearly and responsibly.

## 8. Evidence and Screenshots

Screenshots are organized in the `screenshots/` directory.

- WHOIS results
- WhatWeb results
- Nslookup results
- Curl results
- Wafw00f results
- DNSRecon results
- Zenmap scan results
- Network topology

---

**Author:** Houda Benomar  
**Program:** Networkwalks Cybersecurity Internship – Batch B084
