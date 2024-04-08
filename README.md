# SIEM-Audit
# Botium-Toys-Security-Audit

# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Internal Security Audit Workflow](#workflow)
4. [Controls Assessment](#control-assessment)
5. [Compliance Checklist](#compliance-checklist)
6. [Conclusion](#conclusion)

-------

# Introduction <a name="introduction">

This security audit report presents an assessment conducted on Botium Toys, a fictional toy company, aimed at enhancing its cybersecurity posture. The audit aligns with industry standards and best practices, focusing on mitigating vulnerabilities classified as "high risk" and improving overall security measures.

# Scenario  <a name="scenario">
Botium Toys, a small U.S.-based toy company with an expanding online presence, initiated an internal security audit due to concerns about ensuring business continuity, compliance, and infrastructure security. The audit aims to identify and mitigate potential risks, threats, and vulnerabilities, especially related to critical assets and regulatory requirements such as GDPR and PCI DSS.

# Internal Security Audit Workflow  <a name="workflow">

The audit process consists of analyzing the scope, goals, and risk assessment, conducting the audit, completing controls assessment, and compliance checklist. It further involves reviewing results, documenting findings, and communicating recommendations to stakeholders.

Controls Assessment  <a name="control-assessment">
===================


Current Assets 
--------------


Assets managed by the IT Department include:

- On-premises equipment for in-office business needs 

- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.

- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management

- Internet access

- Internal network

- Vendor access management

- Data center hosting services 

- Data retention and storage

- Badge readers

- Legacy system maintenance: end-of-life systems that require human monitoring

### Administrative Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | X | High |
| Access control policies | Preventative; increase confidentiality and integrity of data | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |

### Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |


### Physical Controls
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attack surface/impact of physical threats | X | Medium/Low |
| Adequate lighting | Deterrent; limit “hiding” places to deter threats | X | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | X | High/Medium |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | High/Medium |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | X | Low |
| Locks | Preventative; physical and digital assets are more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | X | Medium |

Compliance checklist
====================

To review compliance regulations and standards, read the [controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance) document.
   
I found that Botium Toys will need to adhere to the following standards:
     
-   General Data Protection Regulation (GDPR)
      - GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens' data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen's data is compromised, they must be informed within 72 hours of the incident.
         - Botium Toys is expanding to offer services and handle the data of customers abroad, GDPR compliance is in scope for the handling of financial and personal information for customers in the European Union.
   

-   Payment Card Industry Data Security Standard (PCI DSS)

    - PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

       - Botium Toys must adhere to PCI DSS as it accepts payments online and person and They also store and processes customer credit card on an international scale. It's requirements and compliance need to be taken seriously based on possible consequences. The consequences of not complying with this standard is more severe in impact: Monetary fines monthly (ranging from 5,000-100,000 USD), costs of forensic audits upon a data breach, payment brand restrictions, damage to brand reputation, and possibility of lawsuit costs in the event of data breaches. 


-   System and Organizations Controls (SOC type 1, SOC type 2)
   - The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization's financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

      - Botium Toys needs to establish and maintain appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safey.
      - Both of these standards evaluate the effectiveness of a company's internal controls. While SOC1 I focused on financial reporting controls, SOC2 is concerned with information security controls, including customer data safety. 
----------------
# Conclusion  <a name="conclusion">
Thank you for reviewing my mock security audit writeup. I trust you found it informative and valuable. Should you have any feedback or suggestions for improvement, I am eager to hear them.

Self-Evaluation:

In assessing the audit, I believe I accurately identified and prioritized the controls crucial for immediate implementation to mitigate risks effectively. Furthermore, I provided clear reasoning behind Botium Toys' need to comply with selected regulations and standards. This exercise has allowed me to apply and reinforce the knowledge gained from my studies and practical experiences.

Lessons Learned:

During the process, I encountered challenges in providing detailed findings in the stakeholder's memorandum. To address this, I focused on concise and clear communication, utilizing lists and ensuring clarity through proofreading. Additionally, I initially struggled to articulate the relevance of the System and Organizations Controls standard beyond financial compliance. Through further research and reflection, I gained a deeper understanding of its broader implications for organizational security and data integrity.







   
