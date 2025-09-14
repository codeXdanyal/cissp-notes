#
### 7.1 Understand and comply with investigations
### What it means
This topic focuses on how to properly conduct, support, or comply with investigations in the context of information security incidents. CISSP professionals must understand legal, procedural, and technical aspects of investigations to preserve evidence, document findings, and support legal or regulatory requirements. Improper handling can invalidate evidence or expose the organization to liability.

#
### Evidence collection and handling
Collecting evidence requires following strict procedures to maintain integrity and chain of custody. Improper handling can make evidence inadmissible in court or undermine an internal investigation. Evidence can be physical, digital, or electronic.

**Example:** When seizing a compromised laptop, investigators document its condition, photograph it, and use write-blockers to prevent modification of storage devices.

#
### Reporting and documentation
Accurate, thorough, and timely documentation ensures that all actions taken during an investigation are recorded. This includes incident reports, chain-of-custody logs, and internal findings. Documentation supports audits, legal proceedings, and organizational learning.

**Example:** After detecting a phishing incident, the security team prepares a report detailing affected systems, actions taken, timeline of events, and lessons learned to prevent recurrence.

#
### Investigative techniques
Investigators use structured methods to identify, analyze, and verify security incidents. Techniques include interviewing witnesses, analyzing logs, tracing network activity, and reconstructing events. Following proper protocols ensures reliability and defensibility of findings.

**Example:** Security analysts reconstruct a ransomware attack by correlating system logs, backup data, and network flows to determine infection point and spread.

#
### Digital forensics tools, tactics, and procedures
Digital forensics involves specialized tools and procedures to capture, preserve, analyze, and present electronic evidence. This includes disk imaging, memory analysis, network forensics, and malware reverse engineering. Tools must be used carefully to avoid altering evidence.

**Example:** Using FTK Imager or EnCase to create a forensically sound image of a server’s hard drive for later analysis.

#
### Artifacts (data, computer, network, mobile device)
Artifacts are objects of interest that may provide evidence of an incident. These include log files, configuration files, email, network packets, or mobile device data. Understanding where and how to collect artifacts is crucial for effective investigation.

**Example:** Investigators analyze a mobile device backup to find traces of unauthorized access to corporate email accounts.

#
### Key takeaway
Complying with investigations requires maintaining evidence integrity, using proper documentation and reporting, applying structured investigative techniques, and leveraging digital forensics tools to collect and analyze artifacts. Following these practices ensures investigations are credible, defensible, and support both organizational security and legal requirements.


#
### 7.2 Conduct logging and monitoring activities
### What it means
Logging and monitoring are critical for detecting, analyzing, and responding to security events in real time or retrospectively. Effective monitoring ensures that anomalies, policy violations, and attacks are identified early, allowing the organization to respond before significant damage occurs. A CISSP professional must understand both the tools and processes for capturing, analyzing, and acting on security-related information.

### Intrusion Detection and Prevention (IDPS)
IDPS systems detect and potentially block malicious activity on networks or hosts. Intrusion Detection Systems (IDS) alert security teams, while Intrusion Prevention Systems (IPS) can actively stop threats.

**Example:** A network IPS detects a SQL injection attempt targeting a web server and blocks the malicious traffic in real time, alerting the security operations center (SOC).

### Security Information and Event Management (SIEM)
SIEM platforms aggregate logs from multiple sources (servers, network devices, applications) and analyze them for patterns indicating potential threats. They provide alerts, dashboards, and reporting.

**Example:** A SIEM correlates multiple failed login attempts across systems and triggers an alert for a potential brute-force attack, allowing security analysts to respond immediately.

### Continuous Monitoring and Tuning
Security monitoring is not a one-time setup; systems must be continuously monitored and tuned to reduce false positives, detect new threats, and adapt to changes in the environment.

**Example:** Firewall logs are reviewed weekly, and IDS signature rules are updated to detect new malware variants.

### Egress Monitoring
Monitoring outbound traffic helps detect data exfiltration, unauthorized connections, or malware attempting to communicate with command-and-control servers.

**Example:** A monitoring system flags unusual outbound traffic from a workstation to an unknown external IP, prompting investigation and containment.

### Log Management
Capturing, storing, and protecting logs ensures traceability of events, compliance with regulations, and forensic readiness. Logs must be centralized, time-synchronized, and protected from tampering.

**Example:** All server and firewall logs are forwarded to a centralized, tamper-evident storage system to support audit and incident investigations.

### Threat Intelligence (e.g., threat feeds, threat hunting)
Threat intelligence provides information on emerging threats, indicators of compromise (IoCs), and attacker tactics. Security teams use this data to proactively hunt for threats and improve defenses.

**Example:** Threat feeds indicate a new ransomware variant; analysts use IoCs to scan internal systems and detect early infection signs.

User and Entity Behavior Analytics (UEBA)
UEBA tools monitor normal behavior of users and devices and flag deviations that may indicate insider threats, account compromise, or malware activity.

**Example:** UEBA detects a user downloading an unusually large volume of sensitive files outside normal hours, triggering an alert for possible insider data theft.


### Key takeaway
Effective logging and monitoring combine multiple tools and practices to detect, alert, and respond to threats. IDPS, SIEM, UEBA, continuous tuning, egress monitoring, and threat intelligence work together to provide visibility, detect anomalies, and enable timely incident response. Proper log management ensures traceability, accountability, and regulatory compliance.

#
### 7.3 Perform configuration management (CM) (e.g., provisioning, baselining, automation)
### What it means


### Key takeaway

#
### 7.4 Apply foundational security operations concepts 
### What it means


### Key takeaway

#
### 7.5 Apply resource protection
### What it means


### Key takeaway

#
### 7.6 Conduct incident management
### What it means


### Key takeaway

#
### 7.7 Operate and maintain detection and preventative measures
### What it means


### Key takeaway

#
### 7.8 Implement and support patch and vulnerability management
### What it means


### Key takeaway

#
### 7.9 Understand and participate in change management processes
### What it means


### Key takeaway

#
### 7.10 Implement recovery strategies
### What it means


### Key takeaway

#
### 7.11 Implement disaster recovery (DR) processes 
### What it means


### Key takeaway

#
### 7.12 Test disaster recovery plans (DRP) 
### What it means


### Key takeaway

#
### 7.13 Participate in Business Continuity (BC) planning and exercises
### What it means


### Key takeaway

#
### 7.14 Implement and manage physical security 
### What it means


### Key takeaway

#
### 7.15 Address personnel safety and security concerns
### What it means


### Key takeaway




