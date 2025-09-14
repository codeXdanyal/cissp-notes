# Domain 5: Identity and Access Management (IAM)
**_Weightage:_** _13%_

### Table of Contents  

|     | Topics                                                                                                                                                                          |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 5.1 | [Control physical and logical access to assets](#51-control-physical-and-logical-access-to-assets)                                                                              |
| 5.2 | [Design identification and authentication strategy (e.g., people, devices, and services)](#52-design-identification-and-authentication-strategy-eg-people-devices-and-services) |
| 5.3 | [Federated identity with a third-party service](#53-federated-identity-with-a-third-party-service)                                                                              |
| 5.4 | [Implement and manage authorization mechanisms](#54-implement-and-manage-authorization-mechanisms)                                                                              |
| 5.5 | [Manage the identity and access provisioning lifecycle](#55-manage-the-identity-and-access-provisioning-lifecycle)                                                              |
| 5.6 | [Implement authentication systems](#56-implement-authentication-systems)                                                                                                        |


#
### 5.1 Control Physical and Logical Access to Assets
### What it means 
This topic focuses on controlling who or what can access an organization’s resources—both physically and digitally. Access control ensures that only authorized users, processes, or devices can interact with sensitive information, systems, and facilities, reducing the risk of unauthorized disclosure, modification, or destruction.

### Key takeaway
Effective access control combines physical and logical measures to protect all types of assets. Layered controls, strong authentication, role-based permissions, monitoring, and enforcement of least privilege principles are essential to minimize risk and prevent unauthorized access.

### Information
Protecting data from unauthorized access involves classification, labeling, and enforcing access controls based on sensitivity.

**Example:** Confidential customer records are stored in an encrypted database, accessible only to HR and compliance staff.

### Systems
Access to servers, workstations, and network devices must be controlled using authentication, role-based permissions, and monitoring.

**Example:** Only system administrators can log into production servers via SSH using key-based authentication; all access is logged.

### Devices
Endpoint devices, mobile devices, and IoT devices require controls to prevent unauthorized use or theft.

**Example:** Company laptops enforce full-disk encryption, strong passwords, and remote wipe capabilities if lost or stolen.

### Facilities
Physical locations such as offices, data centers, and labs must be protected with layered security measures.

**Example:** A data center uses biometric entry, mantraps, and security guards to prevent unauthorized entry.

Applications
Applications must restrict access to authorized users and processes, often through authentication, authorization, and session management.

**Example:** A payroll application requires multi-factor authentication and role-based access to limit sensitive operations to payroll staff.

### Services
Network and cloud services require controls to prevent unauthorized use or abuse.

**Example:** Cloud storage buckets are configured with least privilege access policies, and API keys are rotated regularly.

### Key takeaway

Effective access control combines physical and logical measures to protect all types of assets. Layered controls, strong authentication, role-based permissions, monitoring, and enforcement of least privilege principles are essential to minimize risk and prevent unauthorized access.


# 
### 5.2 Design identification and authentication strategy (e.g., people, devices, and services)
### What it means 
This topic is about creating a comprehensive strategy to identify and authenticate users, devices, and services. A robust strategy ensures that only verified entities can access resources while maintaining usability. It combines processes, technologies, and policies to manage identity throughout its lifecycle.  

### Groups and Roles
Organizing users into groups or assigning roles simplifies access control and ensures consistency. Roles define permissions based on job functions.

**Example:** The IT admin group has full access to network devices, while the finance group can only access accounting systems.

### Authentication, Authorization, and Accounting (AAA)
AAA frameworks manage identity verification, control what authenticated entities can do, and track their actions. Multi-factor authentication (MFA) or password-less methods strengthen security.

**Example:** Employees log in with a password plus a hardware token (MFA). Access logs track successful and failed attempts.

### Session Management
Sessions maintain authenticated connections. Proper management prevents session hijacking and unauthorized access.

**Example:** Web applications implement automatic session timeouts after inactivity and invalidate tokens on logout.

### Registration, Proofing, and Establishment of Identity
Identity must be verified before granting access, typically during onboarding, through documentation or out-of-band validation.

**Example:** A new employee provides government ID and corporate email verification before receiving system credentials.

### Federated Identity Management (FIM)
FIM allows users to use a single identity across multiple systems or organizations while maintaining trust relationships.

**Example:** Employees use their corporate credentials to access partner services via SAML-based SSO.

### Credential Management Systems
Systems like password vaults securely store and rotate credentials to reduce the risk of compromise.

**Example:** Administrators store database passwords in a vault that requires MFA to retrieve and rotates credentials automatically.

### Single Sign-On (SSO)
SSO reduces the number of authentication events by allowing users to access multiple services with a single verified identity.

**Example:** Logging into the corporate portal grants access to email, HR systems, and project management tools without re-entering credentials.

### Just-In-Time (JIT)
JIT provisioning grants access dynamically when needed, reducing standing privileges and exposure to unnecessary risk.

**Example:** Temporary admin rights are granted for a task and automatically revoked after completion.

### Key takeaway
A strong identification and authentication strategy combines verification, credential management, session control, and least-privilege principles. Using MFA, SSO, FIM, and just-in-time access reduces risk, simplifies administration, and ensures only authorized entities access critical resources.

#
###  5.3 Federated identity with a third-party service
### What it means 
This topic covers using federated identity to allow users to access resources across different organizations or platforms without creating separate accounts. Federation improves security, reduces password fatigue, and simplifies management by leveraging a trusted identity provider (IdP). It applies to on-premises, cloud, or hybrid environments.

### On-Premises
Federation within on-premises systems allows different internal applications or domains to trust a central authentication authority.
Example: A company uses Active Directory Federation Services (ADFS) to let employees access multiple internal applications with a single set of credentials.

### Cloud
Cloud federation enables users to authenticate to cloud services using corporate credentials, reducing the need to manage multiple accounts.
Example: Employees log into Microsoft 365 or Salesforce using their corporate Active Directory accounts via SAML or OAuth 2.0 federation.

### Hybrid
Hybrid federation integrates on-premises and cloud environments, providing seamless access across both. Users authenticate once and gain access to both internal and cloud resources.
Example: A hybrid setup allows employees to access internal HR systems and cloud-based project management tools using the same credentials, managed via a federated identity provider.

### Key takeaway
Federated identity simplifies access management, strengthens security, and enhances user experience by centralizing authentication. Proper implementation—whether on-premises, cloud, or hybrid—requires careful configuration of trust relationships, protocols (SAML, OAuth, OpenID Connect), and lifecycle management.

#
### 5.4 Implement and manage authorization mechanisms
### What it means 
This topic covers methods for granting or restricting access to assets based on rules, roles, attributes, or risk levels. Authorization ensures that authenticated users or systems can only perform actions they are permitted to, supporting the principle of least privilege and reducing potential damage from misuse.

### Role-based access control (RBAC)
Access is assigned based on roles within an organization. Users inherit permissions associated with their roles rather than individual rights.

**Example:** A finance role can approve invoices, while HR can access employee records. Changing roles automatically updates access rights.

### Rule-based access control
Access is determined by predefined rules or conditions, often time-based or location-based.

**Example:** A network firewall allows access to internal servers only during business hours or from corporate IP ranges.

### Mandatory access control (MAC)
Access is enforced by a central authority based on classification labels; users cannot override restrictions.

**Example:** A top-secret document is accessible only to users with top-secret clearance; even an administrator cannot bypass it.

### Discretionary access control (DAC)
Resource owners decide who can access their objects. Flexibility is high but may lead to inconsistent permissions.

**Example:** A file owner grants read access to a colleague; if they forget to revoke access, the colleague retains it indefinitely.

### Attribute-based access control (ABAC)
Access decisions are based on attributes of users, resources, environment, or actions. Provides fine-grained control.

**Example:** A system allows editing of a document only if the user’s department matches the document’s department attribute and the request comes from the office network.

### Risk-based access control
Access is granted or adjusted dynamically based on risk assessment, such as device trust level, location, or user behavior.

**Example:** A banking app blocks login if it detects an unusual device or location, prompting additional verification.

### Access policy enforcement
Controls are implemented using policy decision points (PDP) that evaluate rules and policy enforcement points (PEP) that enforce the decisions.

**Example:** A network access control (NAC) system evaluates device compliance (PDP) and enforces network access restrictions (PEP).

### Key takeaway
Authorization mechanisms ensure that users and systems access only what they are permitted to, balancing security and usability. Using a combination of RBAC, ABAC, MAC/DAC, and risk-based controls with strong policy enforcement creates a flexible, secure environment that supports least privilege and mitigates unauthorized access risks.

#
### 5.5 Manage the identity and access provisioning lifecycle
### What it means 
This topic focuses on managing accounts and permissions throughout their entire lifecycle—from creation and role assignment to modification and eventual deactivation. Proper lifecycle management ensures that users and systems have the right access at the right time, preventing unauthorized access and reducing security risks.

### Account access review
Periodic reviews ensure that user, system, and service accounts still have appropriate permissions and that unused or outdated accounts are disabled.
**Example:** Quarterly audits identify dormant accounts in a cloud platform; inactive accounts are disabled to reduce attack surface.

### Provisioning and deprovisioning
Access is granted when users join, transfer, or change roles, and removed promptly when they leave or no longer need it. Delays in deprovisioning can lead to unauthorized access.
**Example:** A new employee in finance receives access to payroll systems on day one, while a departing employee’s accounts are disabled immediately on exit.

### Service accounts management
Special accounts used by applications, scripts, or services must be controlled, monitored, and rotated securely.
**Example:** A database service account uses a strong, rotated password stored in a secure vault rather than hardcoded credentials.

### Role definition and transition
Roles define sets of permissions. When personnel change positions, their access must be updated to reflect the new role, and old privileges must be removed.
**Example:** An IT technician promoted to sysadmin has new access granted, while old junior-level permissions are revoked.

### Privilege escalation
Use of elevated privileges (e.g., sudo) should be monitored and audited to prevent misuse. Proper processes control who can escalate privileges and when.
**Example:** Developers can use sudo only for specific commands; all actions are logged and reviewed weekly.

### Key takeaway
Managing the identity and access provisioning lifecycle ensures that users and systems have appropriate access at all times. Regular reviews, proper onboarding/offboarding, controlled service accounts, and careful handling of role transitions and privilege escalation minimize the risk of unauthorized access and help enforce least privilege principles.

#
### 5.6 Implement authentication systems
### What it means 
This topic covers methods and systems for verifying the identity of users, devices, or processes before granting access. Authentication is the first line of defense in access control and ensures that only legitimate entities can interact with protected assets. Effective authentication balances security, usability, and scalability.

### Passwords and passphrases
Traditional method using something the user knows. Security depends on complexity, length, and protection against attacks like brute force or credential stuffing.

**Example:** A system enforces a 12-character minimum with a mix of letters, numbers, and symbols, along with account lockout after multiple failed attempts.

### Multi-factor authentication (MFA)
Combines two or more factors: something you know (password), something you have (token/device), or something you are (biometrics).

**Example:** Logging into an email account requires a password plus a one-time code sent to a mobile device.

### Biometric authentication
Uses unique physical or behavioral traits, such as fingerprints, retina scans, or voice recognition. Provides convenience but requires protection of biometric templates.

**Example:** A smartphone unlocks via fingerprint recognition, with the template stored securely in a Trusted Execution Environment.

### Tokens and smart cards
Physical devices that generate or store credentials for authentication, often used with PINs or passwords.

**Example:** An employee uses a smart card to access both the building and network systems; the card contains a certificate for digital authentication.

### Single sign-on (SSO)
Allows users to authenticate once and access multiple systems or applications without re-entering credentials. Reduces password fatigue but requires strong session management.

**Example:** An employee logs into the corporate portal and gains seamless access to email, CRM, and internal apps.

### Certificate-based authentication
Uses digital certificates to verify identity, often in PKI systems. Strong against phishing and impersonation attacks.

**Example:** A VPN requires a client certificate for access, ensuring only authorized devices can connect.

### Adaptive authentication
Adjusts authentication requirements dynamically based on context or risk factors such as location, device, or behavior.

**Example:** A banking app requests only a password from a known device but triggers MFA if login occurs from a new location.

### Key takeaway
Authentication systems are critical to establishing trust before access is granted. Combining multiple factors, secure credential storage, and adaptive mechanisms enhances security while maintaining usability. Strong authentication reduces the risk of unauthorized access and supports compliance with organizational policies.