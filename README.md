
# Network Security Lab Portfolio: IPsec VPN, MITM Attacks, and Threat Detection

![Platform](https://img.shields.io/badge/Platform-OPNsense-orange)
![Virtualization](https://img.shields.io/badge/Virtualization-VMware-blue)
![VPN](https://img.shields.io/badge/VPN-IPsec%20IKEv2-green)
![IDS](https://img.shields.io/badge/IDS-Suricata-red)
![SIEM](https://img.shields.io/badge/SIEM-Wazuh-purple)
![Focus](https://img.shields.io/badge/Focus-SOC%20%7C%20Blue%20Team-blue)

**Focus Areas:** SOC Analysis | Network Security | Threat Detection | Incident Investigation

## Overview

This repository contains four hands-on network security investigation reports covering IPsec VPN configuration, firewall port filtering, ARP spoofing and Man-in-the-Middle (MITM) analysis, and brute-force and Command-and-Control (C2) beaconing detection.

These projects demonstrate practical experience in network traffic analysis, security validation, evidence collection, security alert investigation, and defensive detection techniques within a controlled virtual lab environment.

## Repository Contents

| No. | Investigation Report | Primary Focus |
|---|---|---|
| 1 | [Site-to-Site IPsec VPN Tunnel](Site-to-Site%20IPsec%20VPN%20Tunnel.pdf) | IKEv2 configuration, tunnel establishment, and connectivity validation |
| 2 | [Site-to-Site IPsec VPN Port Filtering](Site-to-Site%20IPsec%20VPN%20Port%20Filtering.pdf) | Firewall rules, permitted services, and blocked traffic validation |
| 3 | [ARP Spoofing MITM and IPsec Validation](ARP%20Spoofing%20MITM%20%26%20IPsec%20Validation.pdf) | ARP spoofing, packet capture, IPsec encryption validation, and detection |
| 4 | [Brute-Force and C2 Beaconing Detection](Brute-Force%20%26%20C2%20Beaconing%20Detection.pdf) | Authentication attack analysis, network beaconing, and SIEM alert triage |

## Project Objectives

- Configure and validate site-to-site IPsec VPN tunnels.
- Evaluate firewall rules and port-filtering behaviour through authorized testing.
- Investigate ARP spoofing and potential MITM activity in a controlled environment.
- Analyze network traffic using Wireshark and Nmap.
- Investigate security events using Wazuh and Sysmon.
- Examine Suricata alerts and network intrusion detection capabilities.
- Identify potential detection gaps and propose defensive improvements.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| OPNsense | Firewall management and IPsec VPN configuration |
| VMware Workstation | Virtual lab environment |
| Kali Linux | Authorized security testing and attack simulation |
| Windows 10 | Endpoint testing and event collection |
| Wireshark | Packet capture and network traffic analysis |
| Nmap | Port scanning and service validation |
| Suricata | Network intrusion detection |
| Wazuh | Security monitoring and SIEM alert analysis |
| Sysmon | Windows endpoint telemetry collection |
| Netcat | Network connectivity testing |
| arpspoof | ARP spoofing simulation |

## Key Learning Outcomes

- Understand IPsec tunnel establishment and network traffic protection.
- Validate firewall policies through controlled network testing.
- Recognize indicators of ARP spoofing and potential MITM activity.
- Correlate network and endpoint evidence during security investigations.
- Analyze repeated outbound connections and potential C2 beaconing behaviour.
- Investigate SIEM alerts, assess potential false positives, and document detection gaps.
- Prepare structured technical investigation reports with supporting evidence and recommendations.

## Investigation Methodology

1. Define the investigation scope and objectives.
2. Configure the required virtual lab environment.
3. Generate or observe relevant network and endpoint activity.
4. Collect packet captures, system logs, and security alerts.
5. Analyze and correlate evidence using the available security tools.
6. Document findings, limitations, and recommended defensive measures.

## References

- [OPNsense Documentation](https://docs.opnsense.org/)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Wazuh Documentation](https://documentation.wazuh.com/)
- [Suricata Documentation](https://docs.suricata.io/)
- [Microsoft Sysmon Documentation](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)

## Disclaimer

These reports are intended for educational purposes and authorized defensive security testing within a controlled laboratory environment.

- Testing must only be performed on systems and networks for which appropriate authorization has been granted.
- Findings should be interpreted in the context of the evidence, lab configuration, and limitations documented in each report.
- Credentials, sensitive information, and private organizational details should not be disclosed publicly.

## About

I am developing practical skills in Security Operations Center (SOC) analysis, network security, security monitoring, and incident investigation.

This repository documents my hands-on learning through lab configuration, network traffic analysis, security alert investigation, evidence-based reporting, and defensive security recommendations.

## License and Usage

These reports are shared for educational and professional portfolio purposes. Refer to the individual reports for their specific methodologies, evidence, limitations, and usage conditions.
