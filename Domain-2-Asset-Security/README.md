# Domain 2: Asset Security  
**_Weightage:_** _10%_


### Table of Contents  
|     | Topics                                                                                                                           |
| --- | :------------------------------------------------------------------------------------------------------------------------------- |
| 2.1 | [Identify and Classify Information and Assets](#21-identify-and-classify-information-and-assets)                                 |
| 2.2 | [Establish Information and Asset Handling Requirements](#22-establish-information-and-asset-handling-requirements)               |
| 2.3 | [Provision Information and Assets Securely](#23-provision-information-and-assets-securely)                                       |
| 2.4 | [Manage Data Lifecycle](#24-manage-data-lifecycle)                                                                               |
| 2.5 | [Ensure Appropriate Asset Retention (EOL, End of Support)](#25-ensure-appropriate-asset-retention-eol-end-of-support)            |
| 2.6 | [Determine Data Security Controls and Compliance Requirements](#26-determine-data-security-controls-and-compliance-requirements) |
|     | [Summary](#domain-2-asset-security--summary)                                                                                     |

#
### 2.1 Identify and Classify Information and Assets

**What It Means:**  
Identifying and classifying assets is about knowing **what you have, how important it is, and how it should be protected**. In cybersecurity, an asset is anything valuable to an organization—data, hardware, software, or even people. Once you know what assets exist, you can prioritize security measures based on their sensitivity or criticality.

**Data Classification:**  
Data classification is the process of **categorizing information based on its sensitivity and impact if lost or disclosed**. Common categories include public, internal, confidential, and highly confidential. Classifying data helps determine who can access it and what security controls are needed.

*Example:* Employee salary information might be classified as confidential, while a company’s press release could be public. Confidential data requires stronger access controls, encryption, and monitoring.

**Asset Classification:**  
Asset classification extends beyond data to **all types of organizational assets**. Each asset—whether it’s a laptop, server, intellectual property, or software—should be assigned a value and a protection level. This helps in prioritizing resources and responding effectively during incidents.

*Example:* A company’s customer database is a high-value asset, so it might be stored on secure servers with encryption and restricted access. On the other hand, old office furniture would be low-value and need minimal protection.

**Key Takeaway:**  
Knowing **what assets you have and how critical they are** is the foundation of protecting an organization. Proper classification ensures that sensitive data and high-value assets receive appropriate security measures while reducing unnecessary costs on less critical items.


#
### 2.2 Establish Information and Asset Handling Requirements

**What It Means:**  
Establishing information and asset handling requirements is about **defining how assets and information should be treated, stored, transmitted, and disposed of** based on their classification. Once assets are identified and classified (from 2.1), organizations need clear rules to ensure that everyone handles them securely. This reduces the risk of accidental leaks, misuse, or unauthorized access.

**Handling Requirements Based on Classification:**  
Each type of data or asset may require **different handling procedures** depending on its sensitivity and value. The handling requirements typically cover:  

- **Access Control:** Who is allowed to view, modify, or distribute the asset.  
- **Storage Requirements:** How and where the asset should be stored (e.g., encrypted drives, locked cabinets).  
- **Transmission Requirements:** How assets are sent or shared (e.g., secure email, VPN, encrypted USB drives).  
- **Usage Rules:** How assets should be used in daily operations without exposing them to unnecessary risk.  
- **Retention and Disposal:** How long assets should be kept and how to securely dispose of them once they are no longer needed.

*Example:* A confidential customer database might only be accessible to certain employees, stored on encrypted servers, transmitted over a secure VPN, and shredded or securely deleted after a retention period. In contrast, publicly available marketing material may have minimal restrictions.

**Formal Policies and Procedures:**  
Organizations often define **formal policies and procedures** for handling assets. These documents provide a **reference point** for employees, auditors, and management. Policies might include:  

- **Information Security Policies:** General rules on handling sensitive data.  
- **Standard Operating Procedures (SOPs):** Step-by-step instructions for day-to-day tasks involving assets.  
- **Incident Response Guidelines:** Instructions on what to do if assets are compromised, lost, or misused.  

*Example:* A policy might state that all USB drives containing confidential data must be encrypted and logged when used. An SOP could outline the exact procedure to securely transfer files to an external vendor.

**Roles and Responsibilities:**  
Clear roles help ensure compliance with handling requirements. This includes:  

- **Asset Owners:** Responsible for classifying assets and defining handling rules.  
- **Custodians:** Individuals or teams who implement and enforce handling procedures.  
- **Users:** Everyone who interacts with assets must follow the defined handling requirements.  

*Example:* The IT department may act as a custodian by maintaining encrypted storage and access logs, while employees are users who must follow rules on password protection and data sharing.

**Regulatory and Legal Considerations:**  
Handling requirements are often influenced by **laws, regulations, and industry standards**, such as:  

- GDPR (data privacy in Europe)  
- HIPAA (health information in the US)  
- PCI-DSS (payment card data)  

These regulations can dictate how data is stored, transmitted, and destroyed, so handling requirements must align with legal obligations.

**Key Takeaway:**  
Establishing handling requirements ensures that every asset and piece of information is **protected throughout its lifecycle**, from creation to disposal. By clearly defining policies, procedures, roles, and compliance requirements, organizations reduce risk, prevent data breaches, and maintain trust.


#
### 2.3 Provision Information and Assets Securely

**What It Means:**  
Provisioning information and assets securely is about **ensuring that when an asset is created, assigned, or made available, it is done in a way that maintains its confidentiality, integrity, and availability**. It ensures that only authorized individuals have access and that all assets are tracked and managed throughout their lifecycle. Secure provisioning reduces the risk of misuse, loss, or unauthorized access right from the start.

**Information and Asset Ownership:**  
Every asset and piece of information must have a clearly assigned **owner** who is responsible for its protection and proper use. The owner defines how the asset is classified, who may access it, and how it should be handled. Ownership ensures accountability and reduces confusion about responsibilities.  

*Example:* A company's financial database might be owned by the finance manager. This manager decides access levels, who can update the data, and how it should be backed up.

**Asset Inventory (Tangible and Intangible Assets):**  
Maintaining an **asset inventory** is essential for secure provisioning. Assets can be:  

- **Tangible Assets:** Physical items such as servers, laptops, storage devices, or network hardware.  
- **Intangible Assets:** Non-physical items such as data, software, intellectual property, or licenses.  

An inventory includes information about each asset’s **location, owner, classification, and status**. This ensures assets are accounted for and helps in monitoring, auditing, and incident response.  

*Example:* A company might maintain a spreadsheet or automated system listing all laptops issued to employees, their serial numbers, assigned users, and classification based on the sensitivity of stored data.

**Asset Management:**  
Asset management refers to the **processes and practices used to manage assets securely throughout their lifecycle**, from acquisition to disposal. Key activities include:  

- **Tracking:** Keeping records of asset usage, location, and ownership.  
- **Maintenance:** Ensuring assets are updated, patched, and functioning securely.  
- **Access Control:** Limiting who can use or modify the asset based on its classification.  
- **Secure Disposal:** Safely decommissioning assets when they are no longer needed, including wiping data or physically destroying devices.  

*Example:* Before disposing of an old server, all sensitive data is securely erased, and the server is physically destroyed or recycled according to company policy. This prevents potential data breaches.

**Secure Provisioning Process:**  
A typical secure provisioning process includes:  

1. **Request and Approval:** The asset is requested by an authorized user and approved by management.  
2. **Classification and Ownership Assignment:** Asset is classified based on sensitivity, and an owner is assigned.  
3. **Configuration:** Security settings, access controls, and encryption are applied.  
4. **Delivery/Deployment:** Asset is delivered to the user securely, ensuring no data or device tampering.  
5. **Documentation:** All provisioning details are recorded in the asset inventory for accountability and auditing.  

*Example:* When issuing a new laptop, the IT team installs required software, enables full-disk encryption, sets strong passwords, and logs the device in the asset inventory with the employee’s name and department.

**Key Takeaway:**  
Secure provisioning ensures that every asset and piece of information starts its lifecycle **with security built in**, reducing risks of unauthorized access, loss, or misuse. Clear ownership, complete inventories, and robust asset management processes create accountability and help maintain organizational security.


#
### 2.4 Manage Data Lifecycle

**What It Means:**  
Managing the data lifecycle is about **understanding and controlling how data flows and is handled throughout its entire existence**, from creation to destruction. Proper lifecycle management ensures that data remains secure, accurate, and available while complying with legal, regulatory, and organizational requirements.

**Data Roles:**  
Different roles are responsible for various aspects of data management:  

- **Data Owners:** Define how data should be classified, accessed, and protected. They are ultimately accountable for the data.  
- **Data Controllers:** Determine the purpose and means of processing personal or sensitive data (common in GDPR contexts).  
- **Data Custodians:** Handle the technical aspects of protecting data, such as storage, backups, and access control.  
- **Data Processors:** Carry out operations on the data on behalf of the owner or controller, e.g., cloud service providers.  
- **Users/Subjects:** Individuals who access or interact with the data following defined policies and permissions.  

*Example:* The HR manager (owner) decides that employee records are confidential. The IT team (custodian) ensures these records are encrypted and backed up, while employees (users) can only view their own records.

**Data Collection:**  
Data should be collected **lawfully, ethically, and with minimal risk**. Only the necessary data for a specific purpose should be gathered to reduce exposure.  

*Example:* A company collects only the email and phone number of customers for account registration, not unnecessary details like home address unless required for service.

**Data Location:**  
Where data is stored affects its security. Organizations must **track the physical and digital location** of data, including cloud services, on-premises servers, and backup systems.  

*Example:* Confidential client files may be stored on a secured on-premises server, while public marketing data could be hosted on a cloud platform.

**Data Maintenance:**  
Data must be **kept accurate, updated, and secure** during its lifecycle. This includes patching systems, correcting errors, and ensuring authorized access.  

*Example:* Updating customer contact information regularly and removing outdated entries to prevent errors in communication.

**Data Retention:**  
Retention policies define **how long data is kept** based on legal, regulatory, or operational needs. Storing data longer than necessary increases risk and storage costs.  

*Example:* Financial transaction records may be retained for seven years for compliance, after which they should be securely disposed of.

**Data Remanence:**  
Even after data is deleted, remnants may remain on storage devices. Organizations must account for **data remanence** to prevent accidental leaks.  

*Example:* A deleted file on a hard drive could still be recovered using forensic tools unless properly overwritten or wiped.

**Data Destruction:**  
Secure destruction ensures that data is **completely removed and unrecoverable** when no longer needed. This can include shredding physical documents or wiping digital storage using certified tools.  

*Example:* Old hard drives containing sensitive client data are physically shredded or securely wiped before disposal.

**Key Takeaway:**  
Managing the data lifecycle ensures that data remains **confidential, accurate, available, and compliant** from creation to destruction. By clearly defining roles, maintaining proper handling, and securely destroying data, organizations minimize risks and maintain trust.

#
### 2.5 Ensure Appropriate Asset Retention (EOL, End of Support)

**What It Means:**  
Ensuring appropriate asset retention is about **managing assets throughout their lifecycle, especially when they reach the end of their useful life**. Assets include hardware, software, data, and other organizational resources. If assets are retained too long, they can become a security risk, and if they are disposed of too early, it can affect operations. Proper retention planning balances operational needs, legal compliance, and security considerations.

**End of Life (EOL):**  
End of Life refers to the point when an asset is **no longer supported or maintained by the manufacturer or vendor**. After EOL, there are **no more updates, patches, or official support**, making the asset vulnerable to security risks.  

*Example:* A server running Windows Server 2012 reached EOL in October 2023. No security updates are provided anymore, which makes it susceptible to cyberattacks if still in use.

**End of Support:**  
End of Support is closely related to EOL but emphasizes that **vendor support (technical assistance, bug fixes, or patches) is no longer available**. Organizations must decide whether to replace, upgrade, or continue using the asset with mitigations.  

*Example:* A cloud software service may continue running after its End of Support date, but any issues or vulnerabilities discovered will not be patched by the vendor.

**Asset Retention Policies:**  
Organizations should have formal policies that define **how long assets are kept, when they are replaced, and how they are disposed of**. Key considerations include:  

- **Legal and Regulatory Requirements:** Some data or software may need to be retained for compliance, e.g., financial records for 7 years (SOX) or medical records for 10 years (HIPAA).  
- **Operational Needs:** Some assets may be kept longer for historical analysis or reporting purposes.  
- **Security Risks:** Assets that are outdated or unsupported can become high-risk targets.  

*Example:* Retaining an old version of a CRM system may be necessary for financial audits, but it must be isolated from the network if it no longer receives security patches.

**Planning for EOL and End of Support:**  
A proper retention strategy involves:  

1. **Inventory and Tracking:** Keep detailed records of all assets, their purchase date, expected lifespan, and support status.  
2. **Replacement/Upgrade Schedule:** Plan timely upgrades or replacements before EOL or End of Support to avoid disruptions and security gaps.  
3. **Mitigation Measures:** If immediate replacement is not possible, implement compensating controls such as network segmentation, restricted access, or enhanced monitoring.  
4. **Secure Disposal:** Ensure retired assets are disposed of securely, following secure data destruction procedures for data-containing devices.

*Example:* Before decommissioning a server, the IT team performs a secure wipe of all data drives, updates the asset inventory to mark it retired, and replaces it with a new server that is supported and patched.

**Key Takeaways:**  
- Asset retention is **not just about keeping assets; it’s about managing risks and compliance throughout their lifecycle**.  
- EOL and End of Support assets are **high-risk if left in production**; they should be upgraded, replaced, or isolated.  
- Proper policies, inventory management, and secure disposal are critical for maintaining **confidentiality, integrity, and availability** of organizational assets.  

**Exam Relevance:**  
CISSP may test your understanding of:  
- Differences between EOL and End of Support  
- Risk implications of retaining outdated assets  
- Policies and processes for asset lifecycle management  
- Regulatory compliance affecting retention periods  

#
### 2.6 Determine Data Security Controls and Compliance Requirements

**What It Means:**  
Determining data security controls and compliance requirements is about **identifying the safeguards, standards, and methods necessary to protect data throughout its lifecycle**, while ensuring the organization meets all legal, regulatory, and contractual obligations. This step ensures that information is secure, risks are managed, and compliance requirements are met.

**Data States:**  
Data can exist in three primary states, and each state requires specific controls:  

- **Data in Use:** Data actively being processed or accessed by users or applications. This includes data in memory, caches, or being edited. Controls focus on preventing unauthorized access and leakage during processing.  
  *Example:* Accessing financial records in an accounting application. Use role-based access control (RBAC) and session monitoring to secure the data while in use.  

- **Data in Transit:** Data moving across networks or between systems. Controls protect it from interception or tampering during transmission.  
  *Example:* Sending customer information over the internet using TLS encryption ensures that data is not read or modified by unauthorized parties.  

- **Data at Rest:** Data stored on physical or cloud storage, databases, or backups. Controls protect against theft, unauthorized access, or data loss.  
  *Example:* Encrypting sensitive files on a company server or using secure cloud storage with access logging.

**Scoping and Tailoring:**  
Not all controls are applicable to every type of data or every environment. **Scoping** is the process of identifying which systems, processes, or datasets are relevant. **Tailoring** involves adjusting security controls to fit organizational needs, risk appetite, and regulatory requirements.  

*Example:* For a healthcare organization, patient data requires strict HIPAA-compliant controls, whereas publicly available marketing materials need only basic protection.

**Standards Selection:**  
Selecting appropriate standards ensures **consistent security practices**. Common frameworks and standards include:  

- **ISO/IEC 27001 & 27002:** International standards for information security management systems and controls.  
- **NIST SP 800-53:** Security and privacy controls for federal information systems.  
- **COBIT:** Governance and management framework for enterprise IT.  
- **PCI-DSS:** Security standard for payment card data.  

*Example:* An organization storing credit card information must comply with PCI-DSS requirements, including encryption, access control, and regular audits.

**Data Protection Methods:**  
Several technical and administrative methods are used to protect data depending on its type, sensitivity, and risk:  

- **Digital Rights Management (DRM):** Controls the use, modification, and distribution of digital content.  
  *Example:* DRM in a PDF document prevents unauthorized copying or printing of confidential reports.  

- **Data Loss Prevention (DLP):** Detects and prevents sensitive data from leaving the organization via email, cloud, or removable media.  
  *Example:* A DLP system blocks an employee from emailing a customer database outside the company network.  

- **Cloud Access Security Broker (CASB):** Enforces security policies between users and cloud service providers, providing visibility, compliance, and threat protection.  
  *Example:* CASB can detect and block unsanctioned uploads of sensitive files to public cloud storage services like Dropbox.  

**Compliance Requirements:**  
Organizations must align data protection measures with **legal, regulatory, and contractual obligations**, which may vary by industry and geography. Common considerations include:  

- Data privacy laws (e.g., GDPR, CCPA, HIPAA)  
- Industry-specific standards (e.g., PCI-DSS, FINRA for finance)  
- Internal policies and contractual obligations with clients or partners  

*Example:* GDPR requires organizations to implement measures such as pseudonymization, access controls, and data breach notification procedures for personal data of EU residents.

**Key Takeaways:**  
- Protect data in all states (in use, in transit, at rest) using appropriate technical and administrative controls.  
- Scope and tailor controls to the organization’s environment, risk profile, and compliance needs.  
- Select recognized standards to ensure consistency and regulatory alignment.  
- Apply specialized methods like DRM, DLP, and CASB to enforce security policies and prevent data breaches.  
- Compliance is not optional—aligning with legal and regulatory requirements reduces legal, financial, and reputational risk.

**Exam Relevance:**  
CISSP questions may focus on:  
- Differences in protecting data in different states  
- Selection and tailoring of security controls  
- Recognizing the purpose of standards and frameworks  
- Identifying appropriate data protection methods for specific scenarios  

#
### Domain 2: Asset Security – Summary

**Purpose:**  
Domain 2 emphasizes the protection of organizational assets and information throughout their lifecycle. It covers everything from identifying and classifying assets to managing data securely, ensuring proper handling, retention, and compliance.

**Identify and Classify Information and Assets:**  
The first step in asset security is knowing what assets exist and understanding their value. Data classification involves categorizing information based on sensitivity, such as public, internal, confidential, or highly confidential. Asset classification applies to all organizational resources, both tangible, like servers or laptops, and intangible, like software, databases, or intellectual property. Proper classification allows organizations to prioritize security efforts and allocate resources effectively.

**Establish Information and Asset Handling Requirements:**  
Once assets are classified, organizations must define how they are handled. This includes rules for storage, transmission, access, and secure disposal. Formal policies and procedures guide employees and custodians on proper usage and incident response. Assigning clear responsibilities to asset owners, custodians, and users ensures accountability. Compliance with legal and regulatory requirements is a critical part of handling policies, minimizing organizational risk.

**Provision Information and Assets Securely:**  
Secure provisioning ensures that assets are configured, assigned, and delivered in a way that maintains their confidentiality, integrity, and availability from the start. This includes assigning ownership, maintaining a complete inventory, and applying access controls and security configurations. A structured provisioning process, from request and approval to documentation, prevents misuse and unauthorized access.

**Manage Data Lifecycle:**  
Data lifecycle management tracks information from creation to secure destruction. Roles such as owners, controllers, custodians, processors, and users define responsibilities for protection, processing, and access. Key activities include collection, storage location, maintenance, retention, addressing remanence, and ensuring secure destruction. Proper lifecycle management reduces risk, ensures data accuracy, and maintains availability for authorized purposes.

**Ensure Appropriate Asset Retention:**  
Assets have an End of Life (EOL) and End of Support (EOS), after which they become vulnerable if still in use. Organizations must implement retention policies that balance operational needs, compliance requirements, and security considerations. Planning replacements, upgrades, or secure disposal before assets become obsolete mitigates security risks and prevents business disruption.

**Determine Data Security Controls and Compliance Requirements:**  
Data must be protected in all states: in use, in transit, and at rest. Security controls should be scoped and tailored to fit organizational risk and regulatory requirements. Standards such as ISO/IEC 27001, NIST SP 800-53, PCI-DSS, and COBIT provide frameworks for consistent security. Methods like Digital Rights Management (DRM), Data Loss Prevention (DLP), and Cloud Access Security Brokers (CASB) help enforce policies. Compliance with laws, regulations, and contractual obligations ensures that organizational practices meet required standards.

**Key Takeaways:**  
Asset security is foundational to protecting organizational information. Understanding and classifying assets, defining handling rules, provisioning securely, managing the data lifecycle, planning retention, and implementing proper security controls ensures that assets remain protected, compliant, and effectively managed. Security is not just technical; it is a combination of processes, policies, and accountability.
