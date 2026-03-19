# Brute-Force-Attack-Analysis-and-OS-Hardening
An analysis of brute force attack vectors and implementation of OS hardening strategies. This project covers incident investigation, log analysis, and remediation measures like MFA and password policies.
Brute Force Attack Analysis and OS Hardening
Project Overview

This project involves a comprehensive investigation of a security incident involving a Brute Force Attack on a web server. As a cybersecurity analyst, I investigated the unauthorized access, analyzed network traffic logs using tcpdump, and documented the incident to recommend effective OS Hardening and remediation strategies.
Skills & Tools Demonstrated

    Network Traffic Analysis: Investigated packet captures to identify DNS and HTTP protocol exploitation.

    Incident Documentation: Authored a professional Security Incident Report following industry standards.

    Vulnerability Assessment: Evaluated system weaknesses, such as default passwords and lack of account lockout policies.

    Remediation & Hardening: Recommended security controls like Multi-Factor Authentication (MFA) and Strict Password Policies.

    Tools Used: tcpdump, Sandbox Environment, Virtual Machines.

Investigation Details

The analysis of tcpdump logs revealed the following sequence:

    DNS Query: A request for yummyrecipesforme.com was resolved to 203.0.113.22.

    Unauthorized Redirect: A subsequent DNS request was observed for greatrecipesforme.com (192.0.2.17).

    Malware Delivery: HTTP GET requests confirmed the unauthorized file download and redirection process.

Remediation Recommendations

To prevent future occurrences, the following OS Hardening tasks were proposed:

    MFA Implementation: Mandatory multi-factor authentication for all administrative access.

    Account Lockout Policy: Automatically suspending accounts after a set number of failed login attempts to thwart automated brute force tools.

    Credential Management: Ensuring no default passwords remain active and enforcing complexity requirements.
