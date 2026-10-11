# Network Security Lab Portfolio
### IPsec VPN | MITM Analysis | Threat Detection | SOC Investigations

![Platform](https://img.shields.io/badge/Platform-OPNsense-orange?style=for-the-badge)
![Virtualization](https://img.shields.io/badge/Virtualization-VMware-blue?style=for-the-badge)
![VPN](https://img.shields.io/badge/VPN-IPsec%20IKEv2-green?style=for-the-badge)
![IDS](https://img.shields.io/badge/IDS-Suricata-red?style=for-the-badge)
![SIEM](https://img.shields.io/badge/SIEM-Wazuh-purple?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-SOC%20%7C%20Blue%20Team-1f6feb?style=for-the-badge)

**Security Operations | Network Defense | Packet Analysis | Incident Investigation**

---

## Overview

This repository contains four hands-on network security investigation reports developed in a controlled virtual laboratory environment. The projects explore secure VPN communication, firewall traffic filtering, ARP spoofing and Man-in-the-Middle (MITM) activity, and the detection of brute-force attempts and potential Command-and-Control (C2) beaconing.

Each report documents the investigation objectives, laboratory configuration, testing methodology, collected evidence, technical observations, and defensive recommendations. The portfolio demonstrates practical experience in network traffic analysis, security validation, evidence collection, security alert investigation, and defensive detection techniques within a controlled virtual lab environment.

---

## Repository Contents

| No. | Investigation Report | Primary Focus |
|---|---|---|
| 1 | [Site-to-Site IPsec VPN Tunnel](Site-to-Site%20IPsec%20VPN%20Tunnel.pdf) | IKEv2 configuration, tunnel establishment, and connectivity validation |
| 2 | [Site-to-Site IPsec VPN Port Filtering](Site-to-Site%20IPsec%20VPN%20Port%20Filtering.pdf) | Firewall rules, permitted services, and blocked traffic validation |
| 3 | [ARP Spoofing MITM and IPsec Validation](ARP%20Spoofing%20MITM%20%26%20IPsec%20Validation.pdf) | ARP spoofing, packet capture, IPsec encryption validation, and detection |
| 4 | [Brute-Force and C2 Beaconing Detection](Brute-Force%20%26%20C2%20Beaconing%20Detection.pdf) | Authentication attack analysis, network beaconing, and SIEM alert triage |

---

## Investigation Reports

### 01. Site-to-Site IPsec VPN Tunnel

**Focus:** VPN Configuration | IKEv2 | Secure Communication

This investigation explores the configuration and validation of a site-to-site IPsec VPN tunnel using OPNsense firewalls. It examines IKEv2 negotiation, tunnel establishment, network connectivity, and protected communication between remote networks. The report documents the configuration process, connectivity tests, observed results, and key considerations for maintaining secure communication across untrusted networks.

[View Investigation Report](Site-to-Site%20IPsec%20VPN%20Tunnel.pdf)

---

### 02. Site-to-Site IPsec VPN Port Filtering

**Focus:** Firewall Policies | Network Access Control | Traffic Validation

This investigation evaluates firewall port-filtering policies within a site-to-site IPsec VPN environment. It examines how firewall rules control permitted and restricted network services and how connectivity tests help validate those policies. The report documents the applied rules, observed traffic behaviour, verification results, and recommendations for strengthening network access control and reducing unnecessary exposure.

[View Investigation Report](Site-to-Site%20IPsec%20VPN%20Port%20Filtering.pdf)

---

### 03. ARP Spoofing MITM and IPsec Validation

**Focus:** ARP Spoofing | MITM Analysis | Packet Inspection

This investigation examines ARP spoofing and potential Man-in-the-Middle activity in an authorized virtual lab. Using tools such as Kali Linux and Wireshark, it explores address-resolution manipulation, packet capture, and the role of IPsec encryption in protecting network traffic. The report documents observed behaviour, supporting evidence, validation steps, and defensive measures for detecting and mitigating such attacks.

[View Investigation Report](ARP%20Spoofing%20MITM%20%26%20IPsec%20Validation.pdf)

---

### 04. Brute-Force and C2 Beaconing Detection

**Focus:** Authentication Monitoring | Network Behaviour | SIEM Analysis

This investigation explores the identification of repeated authentication failures and suspicious periodic outbound connections that may indicate brute-force activity or Command-and-Control beaconing. Using available endpoint and security monitoring telemetry, including Wazuh and Sysmon, it examines event evidence, alert triage, and detection opportunities. The report presents investigation findings, potential false-positive considerations, and recommendations for improving monitoring and detection capabilities.

[View Investigation Report](Brute-Force%20%26%20C2%20Beaconing%20Detection.pdf)

---

## Project Objectives

- Configure and validate site-to-site IPsec VPN connectivity.
- Evaluate firewall rules and network port-filtering behaviour.
- Investigate ARP spoofing and potential MITM activity in an authorized environment.
- Capture and analyze network packets using Wireshark.
- Perform authorized port scanning and service validation using Nmap.
- Examine endpoint telemetry and security events using Sysmon and Wazuh.
- Understand network intrusion detection through Suricata.
- Investigate security events using Wazuh and Sysmon.
- Identify detection limitations and recommend practical defensive improvements.

---

## Tools and Technologies

| Tool | Application |
|---|---|
| OPNsense | Firewall configuration and IPsec VPN management |
| VMware Workstation | Virtualized laboratory infrastructure |
| Kali Linux | Authorized security testing and attack simulation |
| Windows 10 | Endpoint testing and event collection |
| Wireshark | Packet capture and protocol analysis |
| Nmap | Port scanning and service discovery |
| Suricata | Network intrusion detection |
| Wazuh | SIEM monitoring and alert investigation |
| Sysmon | Windows endpoint telemetry |
| Netcat | Network connectivity testing |
| arpspoof | ARP spoofing simulation |

---

## Investigation Workflow

```text
Define Investigation Scope
          |
          v
Configure Virtual Lab
          |
          v
Generate or Observe Activity
          |
          v
Collect Logs and Packet Captures
          |
          v
Analyze and Correlate Evidence
          |
          v
Validate Findings
          |
          v
Document Results and Recommendations
