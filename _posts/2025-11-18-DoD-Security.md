---
title: "2a:asdfasdf"
date: 2025-11-04
categories:
  - Security
tags:
  - Security
  - update
---

I will go through the following topics in a manner that made most sense to me to understand how they are interconnected. I am still learning about security tools and concepts but I hope this will give me a good intro.

**Tenable**

_About_

[Tenable][Tenable-site] is a company that focuses on exposure management products/solutions to protect organizations from exposure to cyber attacks. This includes cloud security, vulnerability management, OT security, and identity security.

OT security vs IT security
- Operational Technology: Hardware and software technologies that focus on the industrial side of things -- it involves the monitor/control of devices, processes, and infrastructure 
- Information Technology: technologies that focus on the informational side of things -- it manages information processing, data, applications, and cloud systems.

Definitions gleaned from [Cisco][cisco-info]


[Tenable-site]: tenable.com
[cisco-info]: https://www.cisco.com/site/us/en/learn/topics/industrial-iot/what-is-ot-vs-it.html#tabs-7edb32179e-item-d43da2dc1e-tab

_Popular Tools/products_

1. [Nessus][nessus-site] - Vulnerability assessment solution/tool that scans for vulnerabilities/weaknesses across various assets

2. [Tenable.sc][sc-site] - Vulnerability management solution (on-premises) that measures + analyzes vulnerabilities and act on critical exposures. 

3. [Tenable.io][io-site ] - Cloud-based vulnerability management platform.

> Tenable.sc and Tenable.io are both vulnerability management solutions with mainly differences in where they're managed: on-premises vs the cloud. They are both platforms that provide centralized managment for vulnerability scanners. 

Nessus vs Tenable.sc
Nessus is a vulnerability scanning engine that performs its work locally on the dedicated scanning machine it's installed on. This machine will remotely scan all devices/assets on its network. Organizations may use several scanners to manage multiple different network segments. Workload is basically distributed amongst many scanners so one is not overloaded and each network segment can be effectively scanned.  
The security center platform would be necessary to manage all of the scanners centrally in a system and consolidate information on one management console. Configurations can also be mass-pushed. Vulnerability data is aggregated into one console to produce an easy way to track all vulnerabilities and produce reports, as well as check for compliance/policy requirements.

4. Tenable One Exposure Management Platform - platform desighned to provide a unified veiw of the attack surface, from cloud environmnents to traditional IT*****
<!-- ADDRESS THIS LATER -->
<!-- >specifics of how vulnerability mangement works
>key concepts to understamnd: centralized reporting, frameworks, commercial vs govt -->
[nessus-site]: https://www.tenable.com/products/nessus
[sc-site]: https://www.tenable.com/products/security-center
[io-site]: https://www.tenable.com/products/vulnerability-management
<br><br>

**Nessus**

_About_ 

As listed above, Nessus is a popular product developed by Tenable. It is a vulnerability scanner that identifies software flaws, missing patches, malware, and misconfigurations across an organization's attack surface (including devices, applications, networks, OSes). "The Nessus technology is widely used by the US DoD and used as the mmain scanning technology in the DoD's official sytstem for vulnerability assessment/management/compliance across networks (ACAS)."

Information from [this site][nessus-info]

[nessus-info]: https://www.techtarget.com/searchnetworking/definition/Nessus

_How it Works_***

_Hands-on Activity_

<br><br>

**ACAS Assured Compliance Assessment Solution**

_About_

ACAS is a popular system used by the US DoD. It involves a variety of different vulnerability management tools to scan for vulnerabilities and consolidate the results, asessing for compliance requirements. It is relevant in this context as the system is known for using the Nessus vulnerability scanner.

[more info][acas-info]

[acas-info]: https://www.tenable.com/sites/default/files/uploads/documents/whitepapers/Whitepaper-Assured_Compliance_Assessment_Solution_ACAS_Powered_by_Tenable.pdf
<br><br>

**RMF Risk Management Framework**