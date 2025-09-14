# Domain 3: Security Architecture and Engineering
**_Weightage:_** _13%_


### Table of Contents  

|      | Topics                                                                                                                                                                                                   |
| :--- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 3.1  | [Research, Implement, and Manage Engineering Processes Using Secure Design Principles](#31-research-implement-and-manage-engineering-processes-using-secure-design-principles)                           |
| 3.2  | [Understand the Fundamental Concepts of Security Models](#32-understand-the-fundamental-concepts-of-security-models)                                                                                     |
| 3.3  | [Select Controls Based Upon Systems Security Requirements](#33-select-controls-based-upon-systems-security-requirements)                                                                                 |
| 3.4  | [Understand Security Capabilities of Information Systems (IS)](#34-understand-security-capabilities-of-information-systems-is)                                                                           |
| 3.5  | [Assess and Mitigate the Vulnerabilities of Security Architectures, Designs, and Solution Elements](#35-assess-and-mitigate-the-vulnerabilities-of-security-architectures-designs-and-solution-elements) |
| 3.6  | [Select and Determine Cryptographic Solutions](#36-select-and-determine-cryptographic-solutions)                                                                                                         |
| 3.7  | [Understand Methods of Cryptanalytic Attacks](#37-understand-methods-of-cryptanalytic-attacks)                                                                                                           |
| 3.8  | [Apply Security Principles to Site and Facility Design](#38-apply-security-principles-to-site-and-facility-design)                                                                                       |
| 3.9  | [Design Site and Facility Security Controls](#39-design-site-and-facility-security-controls)                                                                                                             |
| 3.10 | [Manage the Information System Lifecycle](#310-manage-the-information-system-lifecycle)                                                                                                                  |

#

### 3.1 Research, Implement, and Manage Engineering Processes Using Secure Design Principles
### What It Means:
Security architecture and engineering focus on designing systems in a way that keeps them safe from threats right from the start. Instead of fixing problems after they happen, you build security into the system. This involves following established principles and methods to make sure applications, networks, and devices are as secure as possible.
#
### Threat Modeling:
Threat modeling is like creating a “map” of possible dangers to your system. You identify what could go wrong, who might attack, and how to defend against it. This helps prioritize security measures and reduce risks before they become real problems.

**Example:**
Before launching a new web app, you list all the ways hackers could try to access user data and design protections for each case.
#
### Least Privilege:
Give users or programs only the access they absolutely need—nothing more. This limits damage if an account or system is compromised.

**Example:**
A junior employee doesn’t need admin access to the entire database. Limiting them to read-only prevents accidental or malicious changes.
#
### Defense in Depth:
Use multiple layers of security so that if one layer fails, others still protect the system.

**Example:**
A system might have a firewall, antivirus, encryption, and multi-factor authentication all working together.
#
### Secure Defaults:
Systems should be safe “out of the box.” Users shouldn’t have to change settings to be secure.

**Example:**
New software should come with strong password requirements enabled by default.
#
### Fail Securely:
When something goes wrong, the system should fail in a safe way rather than exposing sensitive information or creating a vulnerability.

**Example:**
If a login server crashes, it should deny access instead of letting everyone in by default.
#
### Segregation of Duties (SoD):
Divide responsibilities so no single person can cause a major security breach alone.

**Example:**
One employee creates new accounts, another approves them. This reduces fraud or mistakes.
#
### Keep It Simple and Small:
Complex systems are harder to secure. Simple, small components are easier to understand, manage, and protect.

**Example:**
Instead of building a giant monolithic application, break it into smaller, well-defined modules.
#
### Zero Trust / Trust but Verify:
Never trust users or systems by default, even inside your network. Always verify identity and permissions before granting access.

**Example:**
Even employees inside a company network need multi-factor authentication to access sensitive files.
#
### Privacy by Design:
Integrate privacy considerations into every stage of system development. Protect personal and sensitive data automatically.

**Example:**
An app automatically encrypts user messages and does not store unnecessary personal data.
#
### Shared Responsibility:
Security is a team effort. Everyone involved—developers, admins, cloud providers—shares responsibility for keeping systems secure.

**Example:**
In cloud computing, the provider secures infrastructure while the customer secures applications and data.
#
### Secure Access Service Edge (SASE):
A modern approach that combines networking and security functions in the cloud to protect users and data wherever they are.

**Example:**
Employees working remotely get secure access to company resources without relying on a traditional office network.
#
### Key Takeaway:
Secure design principles are like the blueprint for safe systems. By thinking about threats, limiting access, layering defenses, simplifying design, and integrating privacy and verification from the start, engineers can build resilient systems that stay safe even when things go wrong.

#
### 3.2 Understand the Fundamental Concepts of Security Models

### What It Means:
Security models are formal frameworks that describe how security policies are implemented in systems. They act like blueprints for designing and evaluating secure computer systems. Each model focuses on a specific aspect of security, such as confidentiality, integrity, or access control. For the CISSP exam, you should understand the differences and purposes of models like **Bell-LaPadul**a, **Biba**, and **Clark-Wilson** (sometimes called the Star Model in simplified references).

These models ensure that information is protected from unauthorized disclosure, modification, or corruption.
#
### Bell-LaPadula Model:
The Biba model is focused on data integrity—ensuring information is accurate and trustworthy. It prevents unauthorized or improper modifications to data.

**Core rules:**

1. **Simple Security Property (no read up) →** A user at a lower classification level (e.g., Confidential) cannot read data at a higher level (e.g., Top Secret).

2. ***-Property (no write down) →** A user at a higher level (e.g., Top Secret) cannot write information to a lower level (e.g., Confidential).

This prevents leakage of sensitive information.

**Example:** 
A military officer with "Top Secret" clearance cannot save or copy top-secret documents into a "Confidential" folder. This avoids the risk of accidental or intentional leaks.  

#
### Biba Model:
The Biba model focuses on data integrity—making sure information is not altered improperly. Its rule is “no write up, no read down.”
**Core rules:**

1. **Simple Integrity Property (no read down) →** Users cannot read data from a lower integrity level because it may be untrusted.

2. ***-Integrity Property (no write up) →** Users cannot write data to a higher integrity level because that could corrupt more reliable information.

**Example:** 
If a junior clerk (low integrity level) enters wrong data, it should not be allowed to modify or overwrite data in the financial records (high integrity level).  

#
### Clark-Wilson Model:
The Clark-Wilson model, sometimes referred to as a "star" model in commercial contexts, emphasizes well-formed transactions and separation of duties. It is widely used in business applications.

**Main ideas:**

- Data can only be modified by authorized programs (not directly by users).
- Users must go through controlled transactions that enforce rules.
- Separation of duties ensures no single person can commit fraud.

**Example:** 
In a banking system, one employee can initiate a fund transfer, but a different employee must approve it. The system ensures that only approved transactions are executed.
#
### Star (*-Property) Model:
Often linked with the Bell-LaPadula model, the Star model is used in systems that need strict rules about who can write where, usually in multi-level secure databases.

**Example:** 
In a military database, a user at a certain clearance level can only insert or modify records in levels they are authorized for, preventing accidental leaks or corruption.
#
### Why These Models Matter:
They provide a formal way to enforce security rules automatically. Instead of relying only on humans to remember rules, the system itself restricts access and modifications based on the model. This reduces mistakes, prevents breaches, and helps meet compliance requirements.
#
### Key Takeaway:
Security models are the foundation of designing secure systems. Bell-LaPadula protects confidentiality, Biba and Clark-Wilson protect integrity, and the Star model manages controlled writes. Understanding these models helps engineers build systems that are reliable, trustworthy, and resistant to misuse or mistakes.

#
### 3.3 Select Controls Based Upon Systems Security Requirements

### What It Means:
Controls are the protective measures you put in place to reduce risks in a system. Think of them as safety measures. Just like a car has seatbelts, airbags, and brakes for different kinds of risks, an information system needs multiple controls to protect it from hackers, accidents, or misuse. The key point is that you don’t pick controls randomly—you select them based on the system’s security requirements, the type of data it handles, and the risks it faces.

#
### Types of Controls:
Controls usually fall into three broad categories:

**Administrative controls:** These are people- and process-oriented. They include policies, hiring practices, background checks, training, and procedures.  
***Example:*** A company policy that says “employees must attend annual security awareness training.”

**Technical controls:** These are technology-based protections built into systems. Examples include encryption, firewalls, intrusion detection systems, and multi-factor authentication.  
***Example:*** Enabling two-factor authentication for employee logins.

**Physical controls:** These protect the actual hardware and physical spaces where systems are located. Examples include security guards, locks, cameras, fences, and biometrics.  
***Example:*** Only authorized staff can enter the server room using a badge or fingerprint scan.

Together, these types of controls form a layered defense (also called defense in depth), so if one control fails, others can still provide protection.

### System Security Requirements:
Each system is built for a purpose, and those purposes dictate its security needs. These requirements come from:

- The type of data stored or processed (public, confidential, secret, classified).
- The value of the system to the business.
- The legal and compliance rules that apply (like HIPAA for health data or PCI DSS for credit card data).  

***Example:*** A medical record system must meet very strict privacy requirements because it stores patient health information. A simple public blog, on the other hand, doesn’t need the same level of protection.

### Selecting the Right Controls:
1. To select proper controls, organizations usually follow a risk assessment process:
1. Identify the assets (data, systems, processes).
1. Identify threats (hackers, natural disasters, insider misuse).
1. Identify vulnerabilities (unpatched systems, weak passwords).
1. Assess the likelihood and impact of risks.
1. Choose controls that reduce those risks to an acceptable level. 

***Example:*** If a web application stores customer credit card numbers, a risk assessment may identify “data theft” as a high-risk threat. The organization would then select controls like strong encryption, access control, and intrusion detection to protect that data.

### Frameworks and Standards for Control Selection:
Instead of starting from scratch, organizations often use industry frameworks that provide recommended controls, such as:

- **NIST SP 800-53 →** Catalog of security and privacy controls.
- **ISO/IEC 27001 →** International standard for information security management.
- **CIS Controls →** A prioritized set of best practices.

These frameworks ensure organizations don’t miss critical protections.

### Balancing Security and Usability:
Security controls must protect the system but also keep it usable. If security is too strict, people may find ways around it, which defeats the purpose. If it’s too weak, the system becomes an easy target.

***Example:*** Requiring employees to change passwords every single day would frustrate them and lead to insecure practices like writing down passwords. Instead, a reasonable policy might be a complex password changed every 90 days combined with multi-factor authentication.

### Cost-Benefit Considerations:
Not every system can afford the most advanced controls. Organizations must balance the cost of a control with the value of what it protects. Spending $1 million on security for a system that only holds $5,000 worth of data is wasteful.

***Example:*** A small business may not be able to afford a full-time security operations center (SOC). Instead, it might rely on managed security services to get similar protection at lower cost.

#
### Key Takeaway:
Selecting controls is about finding the right balance between protection, usability, compliance, and cost. The goal is to reduce risks to an acceptable level while ensuring the system continues to serve its purpose effectively.

#
### 3.4 Understand Security Capabilities of Information Systems (IS)
### What It Means:
Information Systems (IS) are not just computers; they are the combination of hardware, software, and processes that manage and protect data. To keep information safe, these systems are designed with built-in security capabilities. These capabilities are like special features or protective shields that reduce risks, prevent misuse, and keep data reliable. Understanding them helps security professionals know what protections are available and how to apply them properly.

### Memory Protection:
Memory protection prevents one program from interfering with another program’s memory space. Without it, a malicious or faulty program could read or overwrite another program’s sensitive data.

- In simple terms, it’s like giving each tenant in an apartment building their own locked apartment, so one tenant cannot just walk into another’s room.
- Operating systems like Windows, Linux, and macOS enforce memory protection by assigning each process its own protected memory area.

Example: If a web browser crashes, memory protection prevents it from corrupting the memory of your email client running in the background.

### Trusted Platform Module (TPM):
TPM is a small, specialized chip on the motherboard of many computers that provides hardware-based security.

- It stores cryptographic keys securely.
- It ensures the integrity of the system at startup (measuring the boot process to detect tampering).
- It can be used for disk encryption, secure logins, and digital certificates.

Example: When you use BitLocker (Windows disk encryption), the encryption keys are stored in the TPM. If someone steals your hard drive, they can’t read the data without access to that chip.

### Encryption and Decryption:
Encryption is the process of converting readable data (plaintext) into scrambled, unreadable data (ciphertext) to protect it from unauthorized access. Decryption is the reverse—turning ciphertext back into plaintext for authorized users.

- This ensures confidentiality of information whether it’s stored on a disk or transmitted across the internet.
- Modern systems support both symmetric encryption (same key for encrypting and decrypting) and asymmetric encryption (public/private key pairs).

Example: When you shop online, your credit card number is encrypted before it travels across the internet. Only the receiving bank can decrypt it.

### Other Common Security Capabilities in Information Systems:

- **Access Control:** Systems enforce “who can do what” using permissions, user accounts, and roles.  
***Example:*** An HR employee can access salary data, but a regular IT staff member cannot.

- **Audit Logging and Monitoring:** Systems record activities (logins, file access, system changes) so that suspicious activity can be detected and investigated.  
***Example:*** If someone tries to log into your account from another country, logs help track that attempt.

- **Sandboxing/Isolation:** Applications can be run in restricted environments so they cannot affect the entire system.  
***Example:*** Running a suspicious file in a virtual machine so it can’t damage your real computer.

- **Integrity Checking:** Systems use hashing and digital signatures to ensure that data has not been altered.  
***Example:*** When you download software, the vendor provides a hash value so you can verify the file wasn’t tampered with.

### Key Takeaway:
Information systems come with built-in security capabilities like memory protection, TPM, and encryption. These features act as layers of defense, making it harder for attackers to steal or corrupt data. As a security professional, knowing these capabilities allows you to design stronger protections and choose the right tools for the job.

#
### 3.5 Assess and Mitigate the Vulnerabilities of Security Architectures, Designs, and Solution Elements
### What it means

This topic focuses on identifying weaknesses in different types of system architectures and applying security controls to reduce risks. Every system—whether client-based, cloud, or IoT—has unique vulnerabilities. A CISSP professional must understand these differences and know how to mitigate them effectively.

### Client-based systems

Client-based systems (like desktops, laptops, or mobile devices) are the entry points for many attacks such as malware, phishing, or privilege escalation. Weaknesses often come from poor patching, weak endpoint protection, or user error.

**Example:** A laptop without updated antivirus gets infected with ransomware through a phishing email. Endpoint detection and response (EDR) tools plus strong user training can mitigate this.

### Server-based systems

Servers host applications, data, or services and are prime targets for attackers. Vulnerabilities may come from misconfigurations, outdated OS/software, or exposed services.

**Example:** An unpatched web server is exploited using a known vulnerability. Regular patch management and secure baseline configurations reduce this risk.

### Database systems

Databases are sensitive because they store critical business and customer information. Vulnerabilities include SQL injection, weak authentication, and improper access controls.

**Example:** An attacker bypasses input validation and runs SQL injection to extract user passwords. Mitigation: parameterized queries, database activity monitoring, and encryption at rest.

### Cryptographic systems

Cryptographic solutions protect confidentiality, integrity, and authentication, but if poorly implemented, they can create weaknesses. Risks include weak algorithms, bad key management, or outdated protocols.

**Example:** Using MD5 for password hashing makes it easier for attackers to crack. Mitigation: upgrade to strong algorithms (SHA-256, bcrypt) and enforce secure key lifecycle management.

### Industrial Control Systems (ICS)

ICS and SCADA systems control critical infrastructure. Their vulnerabilities come from outdated hardware/software, flat networks, and limited security features.

**Example:** Attackers exploit weak authentication on an ICS interface to disrupt power grid operations. Mitigation: network segmentation, strict access controls, and anomaly detection.

### Cloud-based systems (SaaS, IaaS, PaaS)

Cloud environments bring risks like misconfigured storage buckets, poor identity management, and shared responsibility gaps.

**Example:** An AWS S3 bucket left public exposes customer records. Mitigation: apply least privilege, encrypt cloud storage, and use cloud security posture management tools.

### Distributed systems

Systems spread across multiple locations or nodes can suffer from synchronization issues, data integrity problems, or insecure communications.

**Example:** An attacker intercepts unencrypted communication between distributed nodes. Mitigation: enforce TLS for all inter-node communications and ensure redundancy.

### Internet of Things (IoT)

IoT devices often lack strong security controls, ship with default credentials, or don’t support patching.

**Example:** A smart camera is hacked using default admin credentials. Mitigation: enforce unique passwords, firmware updates, and network isolation for IoT devices.

### Microservices (API)

Microservices rely heavily on APIs, which can be abused if not secured. Risks include broken authentication, injection flaws, or data exposure.

**Example:** A poorly secured API endpoint allows attackers to enumerate all user data. Mitigation: enforce API gateways, input validation, and authentication tokens.

### Containerization

Containers package apps consistently but share the host OS kernel, which can lead to privilege escalation if not isolated.

**Example:** An attacker escapes from a compromised container to the host system. Mitigation: apply runtime security tools, minimal base images, and container isolation.

### Serverless

Serverless platforms run code on demand but shift security to the function and identity level. Risks include insecure code, excessive permissions, and event injection.

**Example:** An attacker triggers a serverless function with malicious input to exfiltrate data. Mitigation: apply least privilege IAM roles and validate all inputs.

### Embedded systems

Embedded devices (like medical equipment or routers) often run outdated firmware and may not support modern patching.

**Example:** A pacemaker with hardcoded credentials is exploited. Mitigation: secure firmware updates and enforce unique device authentication.

### High-Performance Computing systems

HPC systems focus on speed but may overlook security, making them vulnerable to side-channel attacks or resource abuse.

**Example:** Attackers exploit HPC nodes for crypto-mining. Mitigation: strong workload isolation, monitoring, and access control.

### Edge computing systems

Edge devices process data closer to where it’s generated. Risks include physical compromise, limited updates, and weaker defenses compared to data centers.

**Example:** An attacker tampers with an edge gateway to inject false IoT data. Mitigation: strong physical security, encryption, and tamper detection.

### Virtualized systems

Virtualization platforms can face hypervisor attacks, VM escapes, or misconfigured virtual networking.

**Example:** A compromised VM attempts a hypervisor escape attack. Mitigation: patch hypervisors regularly, use isolation, and apply micro-segmentation.

### Key takeaway

Every architecture—whether traditional, cloud, or emerging—carries unique vulnerabilities. Effective mitigation requires a mix of secure configurations, regular patching, access controls, monitoring, and awareness of the system’s operating environment. The goal is not to eliminate risk but to reduce it to an acceptable level.


#
### 3.6 Select and Determine Cryptographic Solutions
### What it means

This topic focuses on choosing the right cryptographic methods and managing them securely throughout their lifecycle. Cryptography is not just about choosing an algorithm—it includes keys, certificates, lifecycle management, and ensuring that confidentiality, integrity, and non-repudiation are achieved. A CISSP professional should be able to evaluate business requirements and threats, then select the most appropriate cryptographic solution.

### Cryptographic life cycle (e.g., keys, algorithm selection)

The cryptographic life cycle covers the stages from algorithm selection, key generation, distribution, storage, usage, rotation, to secure destruction. Poor lifecycle management can weaken even strong algorithms.

**Example:** An organization selects AES-256 for encrypting financial records. Keys are rotated annually and destroyed securely after expiration. This ensures both strong encryption and reduced risk of key compromise.

### Cryptographic methods (e.g., symmetric, asymmetric, elliptic curves, quantum)

Symmetric cryptography uses one shared key for encryption and decryption (e.g., AES). It’s fast but requires secure key distribution.

Asymmetric cryptography uses a public-private key pair (e.g., RSA). It solves key distribution but is slower.

Elliptic Curve Cryptography (ECC) provides strong security with shorter keys, making it efficient for mobile/IoT devices.

Quantum cryptography (still emerging) uses quantum mechanics (e.g., quantum key distribution) to resist brute force and quantum computing attacks.

**Example:** A messaging app uses ECC for secure key exchange (fast and lightweight) and AES for actual message encryption.

### Public Key Infrastructure (PKI) (e.g., quantum key distribution)

PKI provides the framework for issuing, distributing, validating, and revoking digital certificates that bind identities to public keys. It enables secure communications, authentication, and non-repudiation. Emerging approaches like quantum key distribution aim to protect PKI against future quantum computing threats.

**Example:** A company sets up PKI so employees can use digital certificates for VPN access. Certificate Revocation Lists (CRLs) and Online Certificate Status Protocol (OCSP) are used to manage validity.

### Key management practices (e.g., rotation)

Key management ensures that cryptographic keys are generated securely, stored safely, rotated regularly, and retired when compromised or expired. Without strong key management, even advanced algorithms fail.

**Example:** A payment system rotates encryption keys every 90 days and uses a Hardware Security Module (HSM) to protect keys. This reduces exposure if a key is leaked.

### Digital signatures and digital certificates (e.g., non-repudiation, integrity)

Digital signatures prove the origin and integrity of a message, while digital certificates link public keys to verified identities. Together, they enable non-repudiation (a sender cannot deny sending the message) and protect integrity (ensuring no tampering).

**Example:** When signing a contract digitally, a user applies a private key to generate a digital signature. The recipient verifies it using the sender’s certificate issued by a trusted Certificate Authority (CA).

### Key takeaway

Cryptographic security depends not only on the choice of algorithm but also on correct implementation, lifecycle management, and supporting infrastructure like PKI. Properly managed cryptographic solutions ensure confidentiality, integrity, authenticity, and non-repudiation, forming the backbone of secure communication and data protection.

#
### 3.7 Understand Methods of Cryptanalytic Attacks

#
### 3.8 Apply Security Principles to Site and Facility Design

#
### 3.9 Design Site and Facility Security Controls

#
### 3.10 Manage the Information System Lifecycle
