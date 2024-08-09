# Incident-Response-Operation

![image](https://github.com/user-attachments/assets/bbc938fc-fdac-4942-949b-f6e135e4741a)

## Introduction and Objectives
This project showcases a comprehensive approach to incident response operations using Microsoft Sentinel within the Microsoft Azure platform. The primary objective was to implement a structured incident response process following the NIST 800-61 Incident Response Plan. This involved setting up the necessary infrastructure, detecting and analyzing potential security incidents, containing and eradicating threats, and finally documenting and closing out incidents. The goal was to demonstrate proficiency in handling real-time security threats in a cloud environment and to highlight the capabilities of Microsoft Sentinel in orchestrating a robust incident response strategy.

## Technologies Employed
- <b>Microsoft Azure</b>: Core cloud platform used for deploying and managing the infrastructure.
- <b>Microsoft Sentinel</b>: Security Information and Event Management (SIEM) tool used for detecting, analyzing, and responding to security incidents.
- <b>Log Analytics Workspace</b>: Used for ingesting and analyzing logs.
- <b>NIST 800-61 Incident Response Plan</b>: Framework followed for structuring the incident response process.
- <b>Incident Response PlayBook</b>: Employed to guide the containment, eradication, and recovery phases of the incident response.

## Methodologies/Execution of Process
The execution of this project was based on the NIST 800-61 Incident Response Plan, covering the following key phases:

### Step 1: Preparation

Ingested all relevant logs into Log Analytics Workspace and Microsoft Sentinel.
Configured alert rules to monitor and detect potential security incidents.
### Step 2: Detection & Analysis

Set Severity, Status, Owner: Assigned priority and responsibility for the incident.
![image](https://github.com/user-attachments/assets/ad4e21f0-6dbf-41a6-8480-4c112a066aa5)

View Full Details: Conducted a detailed review of the incident.
Observe Activity Log: Monitored the incident's history and progression.
![image](https://github.com/user-attachments/assets/af9154dc-67ad-4d2b-88f8-8c987733c582)

Observe Entities and Incident Timelines: Analyzed the behavior of involved entities and the timeline of the incident.
Investigate the Incident: Used Sentinel’s investigation tools to map the attack and determine its scope.
Inspect Related Events: Examined related alerts and events involving the suspect entities.
![image](https://github.com/user-attachments/assets/f5f373a4-643e-4ba1-9d43-a0a2d6acaf0e)

Determine Legitimacy: Verified the incident as a True Positive by inspecting logs and corroborating details such as source accounts and IP addresses.
![image](https://github.com/user-attachments/assets/e255adf7-9be4-4ed2-8e3a-aecc2f66ca65)

### Step 3: Containment, Eradication, and Recovery

Followed a structured Incident Response PlayBook to contain the threat, eradicate it from the system, and recover affected services.
![image](https://github.com/user-attachments/assets/0d267ce2-0b3c-4bea-8e83-44c840198b11)

![image](https://github.com/user-attachments/assets/ad0fbd0a-325f-45c0-9b73-fde2857004a4)

### Step 4: Documentation and Closure

Documented all findings, actions taken, and lessons learned.
Closed out the incident in Microsoft Sentinel.
![image](https://github.com/user-attachments/assets/6632a062-7789-4405-81e7-140c5a7abd76)

## Insights and Implications
This project provided valuable insights into the practical application of the NIST 800-61 framework in a cloud environment. It highlighted the importance of real-time detection and analysis in minimizing the impact of security incidents. The project also underscored the effectiveness of using automated playbooks in streamlining the containment and recovery processes. By successfully managing the incident, the project demonstrated the critical role of thorough documentation and post-incident analysis in improving future response strategies.

## Conclusion
The execution of this project demonstrates a deep understanding of incident response operations in a cloud environment. By leveraging Microsoft Sentinel and adhering to the NIST 800-61 Incident Response Plan, I was able to efficiently detect, analyze, and mitigate a security incident. The experience has reinforced the importance of preparation, swift detection, and comprehensive documentation in handling cybersecurity threats.
