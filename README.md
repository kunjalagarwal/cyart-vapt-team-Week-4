# cyart-vapt-team-Week-4

# Lab 1 – Advanced Exploitation Lab

## Objective

Perform vulnerability discovery and exploit research in a controlled lab environment.

## Tools Used

- Nmap
- Exploit-DB
- Python
- Metasploitable2

## Activities Performed

1. Configured vulnerable target machine.
2. Discovered target IP address.
3. Performed service enumeration using Nmap.
4. Identified vulnerable services.
5. Analyzed publicly available Proof-of-Concept exploits.
6. Documented findings and remediation recommendations.

## Deliverables

- Target discovery screenshots
- Nmap scan screenshots
- Exploit analysis notes
- Vulnerability documentation

---

# Lab 2 – API Security Testing Lab

## Objective

Understand API security testing methodology using Burp Suite and Postman.

## Tools Used

- Burp Suite
- Postman

## Activities Performed

1. Configured Burp Suite proxy.
2. Created GET requests using Postman.
3. Created POST requests using Postman.
4. Captured HTTP traffic through Burp Suite.
5. Reviewed request and response headers.
6. Documented API testing workflow.

## Sample Findings

| Test ID | Vulnerability | Severity |
|----------|-------------|----------|
| 008 | Authorization Testing | Critical |
| 009 | Input Validation Testing | High |

## Deliverables

- Burp Suite screenshots
- Postman screenshots
- Request/Response screenshots
- API testing notes

---

# Lab 3 – Privilege Escalation and Persistence

## Objective

Perform Linux privilege escalation enumeration and study persistence mechanisms.

## Tools Used

- LinPEAS
- Kali Linux

## Activities Performed

1. Downloaded LinPEAS.
2. Studied privilege escalation methodology.
3. Enumerated:
   - SUID binaries
   - Cron jobs
   - Services
   - Permissions
4. Studied persistence techniques.
5. Documented findings.

## Deliverables

- LinPEAS screenshots
- Enumeration screenshots
- Documentation report

---

# Lab 4 – Network Protocol Attacks

## Objective

Study common network protocol attack techniques and packet analysis.

## Tools Used

- Wireshark
- Responder
- Ettercap

## Activities Performed

1. Studied ARP spoofing.
2. Studied SMB authentication.
3. Analyzed packet captures.
4. Documented protocol attack workflow.
5. Recorded observations.

## Deliverables

- Wireshark screenshots
- Packet analysis screenshots
- Documentation notes

---

# Lab 5 – Mobile Application Testing

## Objective

Perform Android application security assessment using MobSF.

## Tools Used

- MobSF
- Docker
- Android APK

## Activities Performed

1. Installed MobSF.
2. Configured Docker environment.
3. Uploaded Android APK.
4. Performed static analysis.
5. Reviewed permissions and security findings.
6. Documented vulnerabilities.

## Sample Finding

| Test ID | Vulnerability | Severity | Target App |
|----------|-------------|----------|-----------|
| 016 | Insecure Storage | High | Android APK |

## Deliverables

- MobSF screenshots
- APK upload screenshots
- Analysis screenshots
- Findings report

---

# Lab 6 – Capstone Project (PTES Methodology)

## Target Information

- Target Machine: Metasploitable2
- Target IP: 192.168.56.101

## Tools Used

- Kali Linux
- Nmap
- Burp Suite
- OpenVAS
- Metasploit

## Reconnaissance Results

| Port | Service | Version |
|--------|----------|----------|
| 21 | FTP | vsftpd 2.3.4 |
| 22 | SSH | OpenSSH 4.7p1 |
| 23 | Telnet | Linux telnetd |
| 25 | SMTP | Postfix |
| 53 | DNS | ISC BIND 9.4.2 |
| 80 | HTTP | Apache 2.2.8 |
| 139 | SMB | Samba 3.x |
| 445 | SMB | Samba 3.0.20 |
| 3306 | MySQL | 5.0.51a |
| 5432 | PostgreSQL | 8.3 |
| 8180 | Tomcat | Apache Tomcat 5.5 |

## PTES Timeline

| Timestamp | Target IP | Activity | PTES Phase |
|------------|------------|------------|------------|
| 10:00 | 192.168.56.101 | Host Discovery | Reconnaissance |
| 10:10 | 192.168.56.101 | Service Enumeration | Intelligence Gathering |
| 10:20 | 192.168.56.101 | Vulnerability Identification | Vulnerability Analysis |
| 10:35 | 192.168.56.101 | Traffic Validation | Validation |
| 10:45 | 192.168.56.101 | Report Preparation | Reporting |

## Remediation Recommendations

1. Disable anonymous FTP access.
2. Remove Telnet service.
3. Upgrade Apache and Samba services.
4. Restrict database access.
5. Apply latest security patches.
6. Implement least privilege access.
7. Conduct regular vulnerability assessments.
8. Enable security monitoring and logging.

## Conclusion

The VAPT assessment successfully identified multiple exposed services, outdated software components, and security weaknesses within the controlled laboratory environment. The engagement demonstrated reconnaissance, enumeration, validation, reporting, and remediation planning activities aligned with PTES methodology. Appropriate recommendations were provided to reduce attack surface and improve overall security posture.
