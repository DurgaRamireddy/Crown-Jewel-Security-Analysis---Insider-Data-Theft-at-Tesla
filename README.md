# Crown-Jewel-Security-Analysis---Insider-Data-Theft-at-Tesla

## Overview
This project analyzes an insider threat scenario involving the alleged exfiltration of sensitive data from Tesla. The analysis focuses on identifying and protecting the organization's crown jewel assets using the Bowtie risk analysis model. The study evaluates how insider threats can compromise critical intellectual property and examines the preventive and mitigative security controls necessary to reduce such risks.

## Objective
The objective of this project was to:
- Identify Tesla’s crown jewel assets
- Analyze the insider threat scenario
- Apply the Bowtie Model to visualize risk pathways
- Identify threats, consequences, and control failures
- Recommend preventive and mitigative security controls

## Security Framework Used
**Bowtie Risk Analysis Model**
The Bowtie Model is a visual risk analysis framework used to understand how threats lead to security incidents and how controls can prevent or mitigate their impact.

It consists of:
| Component           | Description                     |
| ------------------- | ------------------------------- |
| Hazard              | Valuable asset at risk          |
| Top Event           | Loss of control over the asset  |
| Threats             | Causes leading to the event     |
| Preventive Barriers | Controls preventing the event   |
| Consequences        | Impact if the event occurs      |
| Mitigative Barriers | Controls reducing impact        |
| Escalation Factors  | Conditions that weaken controls |

## Crown Jewel Assets
The critical assets analyzed in this scenario include:
- Proprietary engineering designs
- Manufacturing automation systems
- Internal intellectual property
- Sensitive corporate data stored within internal networks
These assets represent high strategic value and require strong access controls and monitoring mechanisms.

## Threat Scenario
The analyzed scenario involves an insider data theft incident where an employee with legitimate access allegedly exfiltrated confidential company data. The insider exploited authorized access privileges to remove sensitive information from the internal network environment.

## Bowtie Model Analysis
**Hazard**
Tesla’s proprietary engineering data and intellectual property stored within internal systems.

**Top Event**
Unauthorized exfiltration of sensitive data by an insider.
**Threats**
- Disgruntled employee with privileged access
- Poor enforcement of access policies
- Privilege creep from outdated permissions
- Lack of real-time user behavior monitoring
**Consequences**
- Exposure of proprietary engineering data
- Loss of competitive advantage
- Reputational damage
- Legal and financial consequences
- Loss of stakeholder trust 

## Preventive Security Controls
The following controls help reduce the likelihood of insider data theft:
| Control                          | Purpose                                            |
| -------------------------------- | -------------------------------------------------- |
| Role-Based Access Control (RBAC) | Restricts access based on job function             |
| User Behavior Analytics (UBA)    | Detects abnormal user activity                     |
| Background Checks                | Identifies potential insider risk                  |
| Security Awareness Training      | Educates employees about security responsibilities |
| Non-Disclosure Agreements (NDAs) | Legally protects sensitive data                    |

## Mitigative Security Controls
If preventive controls fail, these controls help reduce the impact:
| Control                               | Purpose                              |
| ------------------------------------- | ------------------------------------ |
| Incident Response Plan (IRP)          | Structured breach response           |
| Endpoint Detection and Response (EDR) | Detects compromised systems          |
| Data Loss Prevention (DLP)            | Prevents unauthorized data transfers |
| Digital Forensics Investigation       | Identifies root cause of breach      |

## Escalation Factor
A key escalation factor in this scenario is privilege creep, caused by the absence of periodic access reviews. Employees may accumulate unnecessary permissions over time, violating the principle of least privilege and increasing insider threat risk. This often results from weak identity governance or lack of proper access management processes.

## Key Security Takeaways
- Insider threats pose significant risks to high-value organizational assets.
- Access control policies must be continuously reviewed and enforced.
- Security is not purely technical; organizational governance and employee oversight are equally critical.
- Risk modeling frameworks like Bowtie help organizations understand complex security failures.

## Skills Demonstrated
- Cyber Risk Analysis
- Crown Jewel Analysis
- Insider Threat Modeling
- Security Control Evaluation
- Risk Visualization using Bowtie Model
- Security Governance and Policy Analysis
- Security Incident Impact Assessment

## Author

Durga Sai Sri Ramireddy </br>
Master’s Student - Cybersecurity </br>
University of Houston

*This project was developed for academic purposes and is intended to demonstrate cybersecurity risk analysis techniques using publicly known insider threat scenarios.*
