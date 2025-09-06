# Domain 1: Security and Risk Management

### Table of Contents  
| Topics                                                                                                                                                                        |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [1.1 Understand, Adhere to, and Promote Professional Ethics](#11-understand-adhere-to-and-promote-professional-ethics)                                                                     |
| [1.2 Understand and Apply Security Concepts](#12-understand-and-apply-security-concepts)                                                                                                   |
| [1.3 Evaluate and Apply Security Governance Principles](#13-evaluate-and-apply-security-governance-principles)                                                                             |
| [1.4 Understand Legal, Regulatory, and Compliance Issues](#14-understand-legal-regulatory-and-compliance-issues)                                                                           |
| [1.5 Understand Requirements for Investigation Types](#15-understand-requirements-for-investigation-types)                                                                                 |
| [1.6 Develop, Document, and Implement Security Policy, Standards, Procedures, and Guidelines](#16-develop-document-and-implement-security-policy-standards-procedures-and-guidelines)      |
| [1.7 Identify, Analyze, Assess, Prioritize, and Implement Business Continuity (BC) Requirements](#17-identify-analyze-assess-prioritize-and-implement-business-continuity-bc-requirements) |
| [1.8 Contribute to and Enforce Personnel Security Policies and Procedures](#18-contribute-to-and-enforce-personnel-security-policies-and-procedures)                                       |
| [1.9 Understand and Apply Risk Management Concepts](#19-understand-and-apply-risk-management-concepts)                                                                                     |
| [1.10 Understand and Apply Threat Modeling Concepts and Methodologies](#110-understand-and-apply-threat-modeling-concepts-and-methodologies)                                               |
| [1.11 Apply Supply Chain Risk Management (SCRM) Concepts](#111-apply-supply-chain-risk-management-scrm-concepts)                                                                           |
| [1.12 Establish and Maintain a Security Awareness, Education, and Training Program](#112-establish-and-maintain-a-security-awareness-education-and-training-program)                       |


#

### 1.1 Understand, Adhere to, and Promote Professional Ethics

### What It Means:

Professional ethics are like a set of rules or a moral compass for anyone working in cybersecurity. They guide how you behave, what decisions you make, and how you interact with colleagues, clients, and the public. Following ethics is not just about avoiding trouble—it builds trust and credibility, which is crucial in security work.

### [ISC² Code of Professional Ethics](https://www.isc2.org/ethics)

ISC² (the organization behind CISSP) has its own **Code of Ethics**. Think of it as the “gold standard” for cybersecurity professionals worldwide. The main idea is that you must act honestly, treat others fairly, and prioritize the security and well-being of people and organizations.

<mark>**Example:**</mark> If you find a serious security flaw in your company’s system, the ethical approach is to report it responsibly rather than exploiting it for personal gain.

### Organizational Code of Ethics

Many companies also have their own **internal ethics policies**. These can include rules on confidentiality, data handling, workplace behavior, and reporting incidents. Adhering to these ensures you are aligned with your employer’s expectations while maintaining professional integrity.

<mark>**Example:**</mark> Your company may have a policy that prohibits sharing internal client data. Even if you are trusted, following this rule is part of professional ethics.

### Promoting Ethics

Being ethical isn’t just about following rules yourself; it’s also about encouraging your team or peers to do the same. This can involve mentoring, sharing ethical guidelines, and setting a good example. Organizations with strong ethical cultures tend to have fewer security breaches caused by insider mistakes.

<mark>**Example:**</mark> If a teammate is tempted to take shortcuts that risk security, you could remind them of the ethical standards and suggest a safer approach.

### Key Takeaway

Ethics is the foundation of trust in cybersecurity. Knowing both the **ISC² Code of Ethics** and your **organization’s policies**, following them consistently, and encouraging others to do the same is just as important as technical skills.
#
### 1.2 Understand and Apply Security Concepts

### What It Means:

Security concepts are the basic principles that guide how we protect information. They form the foundation for all security practices. Understanding these concepts helps you make decisions that reduce risks, protect data, and ensure systems are trustworthy.

**5 Pillars of Information Security:**

1. **Confidentiality:**  
   Confidentiality ensures that information is only accessible to those who are authorized. It’s about keeping secrets safe.

     <mark>**Example:**</mark> Your company’s customer database should only be accessed by people who need it, not by anyone who walks by. Using passwords and encryption helps maintain confidentiality.

2. **Integrity:**  
   Integrity means information is accurate and hasn’t been altered by unauthorized people. It ensures the data you receive or store is trustworthy.

    <mark>**Example:**</mark> If a bank transaction record shows $500, it shouldn’t suddenly change to $5,000 because of an error or attack. Checksums, hashes, and version control help maintain integrity.

3. **Availability:**  
   Availability ensures that information and systems are accessible when needed. A system isn’t secure if it’s protected but constantly offline.

    <mark>**Example:**</mark> An e-commerce website must be online and functional during business hours. Redundant servers or cloud backups improve availability.

5. **Authenticity:**  
   Authenticity verifies that data, communications, or users are genuine and come from trusted sources.

    <mark>**Example:**</mark> When you receive an email from your manager, authenticity ensures it really came from them and not a hacker pretending to be your manager. Digital signatures and certificates help confirm authenticity.

5. **Nonrepudiation:**  
   Nonrepudiation ensures that someone cannot deny an action they performed. It provides proof of involvement in a transaction or communication.

    <mark>**Example:**</mark> If a person signs an online contract, nonrepudiation prevents them from claiming later that they never agreed. Digital signatures and audit logs support nonrepudiation.

### Key Takeaway:

The 5 pillars—Confidentiality, Integrity, Availability, Authenticity, and Nonrepudiation—are the core principles that guide security decisions. Together, they help ensure information is protected, trustworthy, and reliably accessible

#
### 1.3 Evaluate and Apply Security Governance Principles

### What It Means:

Security governance is about making sure that an organization’s security efforts support its overall business goals. It’s not just about technology—it’s about policies, processes, and people working together to reduce risk and achieve the organization’s mission safely and effectively.

### Alignment to Business Strategy:

The security function should always support the organization’s mission, goals, and objectives. Security decisions should make business sense, not just technical sense.

<mark>**Example:**</mark> If a company’s goal is to expand into e-commerce, security must ensure online transactions are protected without slowing down the customer experience.

### Organizational Processes:

Security needs to be part of all major organizational processes, including acquisitions, divestitures, or mergers. Governance committees often oversee security strategy to make sure risks are managed consistently.

<mark>**Example:**</mark> When a company acquires another firm, security teams evaluate risks in the acquired systems and data to prevent breaches.

### Organizational Roles and Responsibilities:

Everyone in an organization has a role in security, from executives to staff. Clear roles and responsibilities prevent confusion and ensure accountability.

<mark>**Example:**</mark> The CISO (Chief Information Security Officer) oversees overall security strategy, while system admins implement technical controls, and employees follow security policies in daily tasks.

### Security Control Frameworks:

Frameworks provide structured guidelines to implement and measure security. Popular frameworks include:

- **ISO/IEC 27001:** International standard for managing informationsecurity.
- **NIST:** U.S. guidelines for cybersecurity controls.
- **COBIT:** Focuses on IT governance.
- **SABSA:** Security architecture framework.
- **PCI DSS:** For protecting payment card data.
- **FedRAMP:** For cloud security compliance in U.S. federal agencies.

<mark>**Example:**</mark> Using ISO 27001, an organization can systematically identify risks and apply controls to protect sensitive data.

### Due Care / Due Diligence:

Due care is about taking reasonable steps to protect assets, while due diligence is about continually assessing and verifying that protections are effective.

<mark>**Example:**</mark> Due care would be implementing strong firewalls and encryption. Due diligence would be regularly reviewing logs and testing security controls to ensure they work.

### Key Takeaway:

Security governance ensures that security is not an afterthought but a strategic part of business operations. By aligning security with business goals, defining roles, applying frameworks, and practicing due care and due diligence, organizations can reduce risk and operate securely.

#
### 1.4 Understand Legal, Regulatory, and Compliance Issues
### What It Means:
Legal, regulatory, and compliance issues define the rules organizations must follow when handling information. Understanding these rules helps prevent lawsuits, fines, or damage to reputation. In cybersecurity, this often overlaps with protecting data, respecting privacy, and following industry standards.  

### Cybercrimes and Data Breaches:
Organizations must be aware of cybercrimes, such as hacking, ransomware attacks, or phishing, and take steps to prevent them. Data breaches—when sensitive information is stolen or exposed—can lead to legal consequences if laws or regulations are violated.  

<mark>**Example:**</mark> If customer credit card data is stolen due to weak security, the company could face lawsuits, fines, and regulatory penalties.  

### Licensing and Intellectual Property Requirements:
Using software, content, or technology without proper licenses is illegal. Intellectual property (IP) laws protect creators and organizations.

<mark>**Example:**</mark> Installing pirated software in a corporate network can result in legal action and fines. Proper licensing ensures compliance and avoids risk.  

### Import/Export Controls:
Some technologies or data may be restricted for international transfer due to national security or trade regulations. Organizations must comply when sharing or receiving data across borders.

<mark>**Example:**</mark> Encrypting software or certain technical data might require special licenses before sending it to another country.  

### Transborder Data Flow:
Data often moves across countries in cloud services or business operations. Different countries have different rules for protecting personal or sensitive data.

<mark>**Example:**</mark> Storing European users’ personal data in a U.S. cloud service must comply with GDPR rules on data transfer outside the EU.  

### Privacy Regulations:
Privacy laws protect personal information and require organizations to handle data responsibly. Key regulations include:
   - **GDPR (EU):** Protects personal data of EU citizens.
   - **CCPA (California, USA)**: Gives California residents control over personal data collected by businesses.
   - **Personal Information Protection Law (China)**: Governs collection and usage of personal data.
   - **POPIA (South Africa)**: Protects personal information and ensures privacy rights.  
   

<mark>**Example:**</mark> Companies must inform users when collecting data and allow them to access or delete it upon request.  

### Contractual, Legal, Industry Standards, and Regulatory Requirements:
Organizations must also follow contracts, local laws, industry standards (like PCI DSS for payment data), and other regulatory requirements. Compliance demonstrates due diligence and protects the organization legally.

<mark>**Example:**</mark> A healthcare provider must comply with HIPAA regulations in the U.S. to protect patient records and avoid penalties.  

### Key Takeaway:
Understanding legal, regulatory, and compliance issues ensures that security practices align with the law and industry standards. This protects the organization from legal trouble, maintains trust with clients, and ensures responsible handling of data.  

#
### 1.5 Understand Requirements for Investigation Types
### What It Means:
In cybersecurity, investigations are conducted when something goes wrong, such as a breach, policy violation, or suspected crime. Understanding the types of investigations helps you know what rules to follow, how evidence must be handled, and who is responsible for conducting it.

### Administrative Investigations:
These are internal investigations conducted by the organization to ensure policies and procedures are being followed. They are often used to address employee misconduct or policy violations.  

<mark>**Example:**</mark> If an employee is suspected of accessing sensitive files without authorization, HR or the security team may perform an administrative investigation to determine the facts.

### Criminal Investigations:
Criminal investigations are led by law enforcement agencies when a law may have been broken. These require strict procedures to ensure evidence is legally admissible in court.  

<mark>**Example:**</mark> If a hacker steals customer data and uses it for fraud, police or federal authorities may investigate, and the organization must cooperate by providing evidence according to legal protocols.

### Civil Investigations:
Civil investigations usually occur in lawsuits between private parties. These may involve disputes over contracts, data misuse, or negligence. Evidence is collected to support a legal claim but may not involve criminal charges.  

<mark>**Example:**</mark> If a company accidentally exposes a partner’s confidential information, the partner may file a civil lawsuit seeking compensation.

### Regulatory Investigations:
These are investigations by regulatory bodies to ensure compliance with laws, industry standards, or policies. Organizations must provide requested information and demonstrate compliance.  

<mark>**Example:**</mark> A financial regulator may investigate a bank to confirm that it complies with anti-money laundering regulations.

### Industry Standards Investigations:
Some industries have their own rules and guidelines. Investigations may be conducted to verify compliance with standards or certifications.  

<mark>**Example:**</mark> Payment card companies may investigate merchants to ensure PCI DSS compliance, such as proper handling of credit card information.

### Key Takeaway:
Different investigations serve different purposes—internal accountability, criminal enforcement, civil resolution, regulatory oversight, or industry compliance. Knowing the type of investigation helps ensure proper procedures are followed, evidence is handled correctly, and legal or policy obligations are met.

#
### 1.6 Develop, Document, and Implement Security Policy, Standards, Procedures, and Guidelines

### What It Means:
Security policies, standards, procedures, and guidelines are the building blocks of an organization’s security program. They provide clear instructions on how to protect information, ensure compliance, and guide employees in their day-to-day activities. Together, they create a structured approach to reducing risk and maintaining security.

### Security Policy:
A security policy is a high-level document that defines the organization’s overall approach to security. It sets the rules and expectations for everyone, from executives to employees.  

<mark>**Example:**</mark> A policy may state that all company devices must have password protection and antivirus software installed.

### Standards:
Standards are specific, mandatory requirements derived from the security policy. They define measurable rules or technologies that must be used to meet policy objectives.  

<mark>**Example:**</mark> A standard could require that all passwords must be at least 12 characters long and include a mix of letters, numbers, and symbols.

### Procedures:
Procedures are step-by-step instructions for performing specific security tasks. They explain how to implement standards consistently across the organization.  

<mark>**Example:**</mark> A procedure might describe the exact steps to configure a new employee’s laptop with encryption, antivirus, and access permissions.

### Guidelines:
Guidelines provide recommended practices that offer flexibility. They are advisory rather than mandatory and help employees make informed decisions when procedures do not cover every situation.  

<mark>**Example:**</mark> A guideline could suggest using multi-factor authentication on personal devices, even if it is not strictly required by policy.

### Implementation:
Developing these documents is not enough—they must be effectively communicated and enforced. Implementation includes training employees, integrating policies into business processes, and monitoring compliance.  

<mark>**Example:**</mark> After creating a password policy and standards, the IT team provides training on creating strong passwords and periodically audits compliance.

### Key Takeaway:
Policies, standards, procedures, and guidelines work together to create a clear framework for security. Policies define “what” and “why,” standards define “what exactly,” procedures define “how,” and guidelines provide helpful advice. Proper development, documentation, and implementation ensure that security practices are understood, followed, and effective.

#
### 1.7 Identify, Analyze, Assess, Prioritize, and Implement Business Continuity (BC) Requirements

### What It Means:
Business Continuity (BC) is about ensuring that an organization can continue operating during and after a disruption, such as natural disasters, cyberattacks, or system failures. Identifying and prioritizing BC requirements ensures that critical business functions remain available and losses are minimized.

### Business Impact Analysis (BIA):
A BIA is a process that identifies the effects of disruptions on business operations. It helps determine which functions are most critical and how quickly they need to be restored.  

<mark>**Example:**</mark> A bank performing a BIA may find that online banking services are critical and must be restored within hours, while internal report generation can wait a few days.

### External Dependencies:
Organizations rely on external partners, vendors, or services for operations. Understanding these dependencies is crucial because disruptions in these external sources can impact your business.  

<mark>**Example:**</mark> If a cloud service provider hosting company data goes offline, it can affect business operations. BC planning may include backup providers or local failover systems to mitigate this risk.

### Implementation of BC Requirements:
Once critical functions and dependencies are identified, organizations prioritize resources, create recovery strategies, and implement procedures to maintain operations during disruptions.  

<mark>**Example:**</mark> An e-commerce company may implement redundant servers, automated backups, and emergency communication plans to ensure that customers can continue shopping even if one system fails.

### Key Takeaway:
Business Continuity planning ensures that critical operations continue during unexpected events. Performing a BIA, assessing external dependencies, and #prioritizing recovery efforts are essential steps to reduce downtime, minimize financial loss, and maintain customer trust.

#
### 1.8 Contribute to and Enforce Personnel Security Policies and Procedures

### What It Means:
Personnel security focuses on ensuring that people who have access to organizational resources are trustworthy and follow security policies. It involves managing employees, contractors, and vendors throughout their lifecycle in the organization to reduce insider threats and maintain compliance.

### Candidate Screening and Hiring:
Organizations should screen candidates to verify their background, qualifications, and trustworthiness before granting access to sensitive information.  

<mark>**Example:**</mark> Performing reference checks, criminal background verification, or skill assessments before hiring a system administrator who will manage critical servers.

### Employment Agreements and Policy-Driven Requirements:
Employment contracts and policies define employee responsibilities, acceptable behavior, and security obligations. Clear agreements help set expectations and provide legal protection.  

<mark>**Example:**</mark> An employment agreement may require staff to adhere to confidentiality policies and refrain from sharing company data outside the organization.

### Onboarding, Transfers, and Termination Processes:
Personnel security requires controlling access throughout an employee’s tenure. Onboarding ensures proper access is granted; transfers require reviewing access based on new roles; termination ensures all access is revoked promptly.  

<mark>**Example:**</mark> When an employee leaves the company, IT must immediately disable system accounts and collect company devices to prevent unauthorized access.

### Vendor, Consultant, and Contractor Agreements and Controls:
Third parties with access to company systems must also follow security policies. Contracts should define responsibilities, access limits, and security obligations.  

<mark>**Example:**</mark> A contractor providing cloud services must sign a data protection agreement and follow the organization’s security controls when handling sensitive data.

### Key Takeaway:
Personnel security policies and procedures protect the organization from insider threats, ensure compliance, and maintain a secure work environment. Screening, clear agreements, proper onboarding, role changes, and controlled termination are essential to managing human risk effectively.

#
### 1.9 Understand and Apply Risk Management Concepts
### What It Means:
Risk management is the process of identifying, evaluating, and addressing potential threats to an organization’s information and systems. Its goal is to reduce the likelihood and impact of negative events while supporting business objectives. Effective risk management is continuous and involves people, processes, and technology.

### Threat and Vulnerability Identification:
Threats are potential events that can cause harm, while vulnerabilities are weaknesses that can be exploited. Identifying both is the first step in managing risk.  

<mark>**Example:**</mark> A threat could be a hacker attempting to steal customer data, and a vulnerability could be outdated software that can be easily exploited.

### Risk Analysis, Assessment, and Scope:
Risk analysis evaluates the potential impact and likelihood of threats exploiting vulnerabilities. Assessment defines how serious a risk is and which assets it affects. Scope determines which systems, processes, or data are included in the evaluation.  

<mark>**Example:**</mark> Assessing the risk of a ransomware attack on company servers, considering how much downtime and financial loss it would cause.

### Risk Response and Treatment:
After assessing risks, organizations decide how to handle them. Common strategies include:
   - **Accept**: Acknowledge the risk without action if it is minor.
   - **Avoid**: Change processes to eliminate the risk.
   - **Mitigate**: Implement controls to reduce risk.
   - **Transfer**: Shift risk to another party, like using cybersecurity insurance.  

<mark>**Example:**</mark> Purchasing cybersecurity insurance to cover potential losses from a data breach is a form of risk transfer.

### Applicable Types of Controls:
   - **Preventive Controls:** Stop incidents before they occur (e.g., firewalls, access controls).
   - **Detective Controls:** Identify incidents as they happen (e.g., intrusion detection systems).
   - **Corrective Controls:** Fix or limit damage after an incident (e.g., backups, patching).

### Control Assessments: Security and Privacy:
Regularly evaluating controls ensures they are effective. Security assessments check technical protections, while privacy assessments ensure personal data is handled correctly.  

<mark>**Example:**</mark> Conducting an audit to verify that encryption is correctly applied to sensitive customer data.

### Continuous Monitoring and Measurement:
Risk management is ongoing. Organizations must continuously track threats, vulnerabilities, and control effectiveness.  

<mark>**Example:**</mark> Using automated monitoring tools to detect unusual network activity in real time.


### Reporting: Internal and External:
Organizations must communicate risk findings to relevant stakeholders. Internal reports inform management for decision-making, while external reports may be required for regulators or clients.  

<mark>**Example:**</mark> A quarterly risk report may highlight new vulnerabilities and the status of mitigation efforts.

### Continuous Improvement: Risk Maturity Modeling:
Organizations should evolve their risk management processes over time, aiming for higher maturity and more proactive risk handling.  

<mark>**Example:**</mark> Moving from basic checklist audits to automated, predictive risk analytics represents improved maturity.

### Risk Frameworks:
Structured frameworks help guide risk management practices. Common frameworks include:
   - **ISO 31000 / ISO 27005** – International risk management standards.
   - **NIST** – Guidelines for cybersecurity risk.
   - **COBIT** – IT governance and control framework.
   - **SABSA** – Security architecture framework.
   - **PCI DSS** – Payment card industry standards.

### Key Takeaway:
Risk management is about identifying what can go wrong, evaluating its impact, and applying the right controls to protect the organization. Continuous monitoring, reporting, and improvement, guided by recognized frameworks, ensure that risks are managed effectively over time.  

#
### 1.10 Understand and Apply Threat Modeling Concepts and Methodologies
### What It Means:
Threat modeling is a proactive approach to identifying potential threats and vulnerabilities in a system before they can be exploited. It helps organizations anticipate attacks, prioritize risks, and design stronger defenses. Essentially, it’s like thinking like a hacker to prevent problems before they happen.

### Core Concept:
Threat modeling involves analyzing systems, applications, or processes to understand what could go wrong, who might exploit it, and what impact it could have. This analysis helps guide security decisions and resource allocation.  

<mark>**Example:**</mark> Before launching a new mobile app, a company might analyze potential threats such as unauthorized access, data leakage, or phishing attacks targeting users.
### Methodologies:
There are several common methodologies used in threat modeling:

#### 1. STRIDE:
Focuses on six categories of threats:
   - **Spoofing:** Pretending to be someone else.
   - **Tampering:** Altering data or systems.
   - **Repudiation:** Denying actions taken.
   - **Information Disclosure:** Exposing sensitive data.
   - **Denial of Service (DoS):** Disrupting system availability.
   - **Elevation of Privilege:** Gaining higher access than allowed.  
   
   
   <mark>**Example:**</mark> Using STRIDE, a web application team might identify that password reset functionality could be exploited for spoofing attacks.  

#### 2. PASTA (Process for Attack Simulation and Threat Analysis):
A risk-centric methodology that simulates attacks to understand real-world impact and prioritize mitigations.  

<mark>**Example:**</mark> PASTA might reveal that attackers could combine multiple vulnerabilities to access sensitive customer data.  

#### 3. OCTAVE (Operationally Critical Threat, Asset, and Vulnerability Evaluation):
Focuses on organizational risk, identifying critical assets, and understanding operational impacts.  

<mark>**Example:**</mark> An OCTAVE assessment may show that customer databases are high-value assets and require stronger access controls.

### Threat Modeling Steps:
   1. **Identify Assets:** Determine what needs protection.
   2. **Identify Threats:** Consider potential attackers and attack vectors.
   3. **Identify Vulnerabilities:** Find weaknesses in systems or processes.
   4. **Analyze Impact:** Assess the potential damage if exploited.
   5. **Define Mitigation Strategies:** Plan controls to reduce risk.  

<mark>**Example:**</mark> For a cloud storage service, assets include user files, threats include hackers and insiders, vulnerabilities may be weak passwords, and mitigation could include multi-factor authentication and encryption.

### Key Takeaway:
Threat modeling is a structured way to think like an attacker to protect systems proactively. Using methodologies like STRIDE, PASTA, and OCTAVE helps organizations identify risks early, prioritize defenses, and strengthen overall security posture.

#
### 1.11 Apply Supply Chain Risk Management (SCRM) Concepts
### What It Means:  
Supply Chain Risk Management (SCRM) is about identifying and managing risks that come from external suppliers, vendors, and service providers. Organizations rely on third parties for products, software, and services, and any compromise in the supply chain can affect security, reliability, and trust.

### Risks in the Supply Chain:
Products or services from suppliers can be vulnerable to tampering, counterfeits, or malicious implants. Even software components may contain hidden vulnerabilities that could compromise the organization.  

<mark>**Example:**</mark> A company purchasing network devices from a third-party vendor could unknowingly receive equipment with pre-installed malware or counterfeit parts that fail early.

### Risk Mitigations:
To reduce supply chain risks, organizations can implement several strategies:
#### 1. Third-Party Assessment and Monitoring:
Regularly evaluate suppliers to ensure they meet security and quality standards. Continuous monitoring helps detect changes or risks over time.  

<mark>**Example:**</mark> Conducting security audits on a cloud service provider before and during the contract period.

#### 2. Minimum Security Requirements:
Set clear security expectations for suppliers, including secure development practices and data protection standards.  

<mark>**Example:**</mark> Requiring that all software delivered by vendors be free of known vulnerabilities and follow secure coding practices.

#### 3. Service Level Requirements (SLRs):
Define performance and security expectations in contracts to ensure suppliers meet organizational needs.  

<mark>**Example:**</mark> A cloud storage provider may have an SLR guaranteeing 99.9% uptime and timely patching of security vulnerabilities.

#### 4. Silicon Root of Trust and Physically Unclonable Function (PUF):
These are hardware-based security measures that verify device authenticity and prevent tampering.  

<mark>**Example:**</mark> A secure chip in a server ensures that only trusted firmware can run, reducing risk from counterfeit components.

#### 5. Software Bill of Materials (SBOM):
A list of all software components used in a product. This transparency helps organizations identify vulnerabilities and manage risk.  

<mark>**Example:**</mark> Reviewing an SBOM before deploying a third-party application to ensure it doesn’t include outdated or insecure libraries.

### Key Takeaway:
SCRM ensures that external suppliers and third-party products do not introduce security risks. By assessing suppliers, defining security requirements, monitoring compliance, and using hardware and software verification techniques, organizations can maintain a trustworthy and secure supply chain.

## 
### 1.12 Establish and Maintain a Security Awareness, Education, and Training Program
### What It Means:
Security awareness, education, and training programs are designed to teach employees how to recognize and respond to security threats. Humans are often the weakest link in cybersecurity, so educating staff reduces mistakes, prevents breaches, and fosters a culture of security.

### Methods and Techniques:
Social Engineering:
Teaching employees to recognize attempts to manipulate them into revealing confidential information.  

<mark>**Example:**</mark> Training staff to spot phishing emails that ask for login credentials or personal information.

#### 1. Phishing Simulations:
Running controlled phishing exercises to test employee awareness and response.  

<mark>**Example:**</mark> Sending fake phishing emails to employees and providing feedback when someone clicks a suspicious link.

#### 2. Security Champions:
Identifying motivated employees in different teams who advocate for security best practices and mentor peers.  

<mark>**Example:**</mark> A developer in the IT team promotes secure coding practices and helps colleagues understand risks.

#### 3. Gamification:
Using interactive games or challenges to make learning about security fun and engaging.  

<mark>**Example:**</mark> Quizzes or reward-based challenges on password management and safe browsing practices.

#### 4. Periodic Content Reviews:
Security threats evolve, so training programs must stay updated with emerging technologies and trends, like cryptocurrency security, AI vulnerabilities, or blockchain risks.  

<mark>**Example:**</mark> Updating modules to cover risks in cryptocurrency transactions or AI-powered phishing attacks.

#### 5. Program Effectiveness Evaluation:
Organizations must measure the impact of training programs to ensure they are improving employee behavior and reducing risks.  

<mark>**Example:**</mark> Tracking the percentage of employees who successfully identify phishing simulations or monitoring incident reports before and after training.

### Key Takeaway:
A strong security awareness, education, and training program empowers employees to act as the first line of defense. Using a mix of teaching methods, staying current with emerging threats, and evaluating program effectiveness ensures that the workforce remains vigilant and security-conscious.

#