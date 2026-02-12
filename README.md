# billing-application-penetration-test-tryhackme
End-to-end penetration testing simulation of a vulnerable billing application. Covers reconnaissance, web enumeration, CVE-based exploitation, and Linux privilege escalation following an industry-standard offensive security methodology.


Overview

This repository documents a structured penetration testing simulation conducted in a controlled lab environment. The objective was to identify vulnerabilities in a billing application, gain initial access, and escalate privileges to achieve full system compromise.

The assessment followed a professional offensive security methodology aligned with real-world penetration testing practices.

Objectives

Perform network reconnaissance and service enumeration

Identify application vulnerabilities

Exploit a publicly disclosed CVE

Obtain initial shell access

Escalate privileges to root

Document findings professionally

Methodology

The engagement followed a standard penetration testing workflow:

Reconnaissance

Enumeration

Vulnerability Identification

Exploitation

Post-Exploitation

Privilege Escalation

Reporting & Recommendations

Reconnaissance & Enumeration

Network scanning and web enumeration were conducted to identify exposed services and application components.

Activities included:

Service and version detection

Web directory enumeration

Attack surface mapping

These steps helped determine potential entry points into the system.

Vulnerability Identification

A publicly disclosed Remote Code Execution (RCE) vulnerability affecting the billing application was identified through CVE research and service analysis.

The vulnerability allowed unauthenticated command execution under specific conditions.

Exploitation

The identified vulnerability was exploited to gain remote shell access to the target system.

Key actions performed:

Exploit configuration and execution

Session establishment

Local system enumeration

This phase demonstrated how unpatched applications can result in system compromise.

Privilege Escalation

Post-exploitation analysis revealed misconfigured sudo permissions.

By leveraging improper privilege assignments, root-level access was achieved.

This highlights the risks of weak privilege management and insecure system configuration.

Tools Used

Nmap

Gobuster

Metasploit Framework

Linux Command Line Utilities

Security Impact

The simulation demonstrated how:

Unpatched vulnerabilities enable remote access

Misconfigured privileges allow full system takeover

A complete attack chain can escalate from user access to root

Recommendations

Implement regular patch management

Apply the Principle of Least Privilege

Audit and restrict sudo permissions

Perform routine security assessments

Monitor and log suspicious activity

Disclaimer

This assessment was performed in an authorized lab environment for educational purposes only. No unauthorized systems were targeted.
