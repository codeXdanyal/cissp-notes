# Domain 1: Security and Risk Management  
**_Weightage:_** _10%_


### Table of Contents  

|      | Topics                                                                                                     |
| :--- | :--------------------------------------------------------------------------------------------------------- |
| 2.1  | [Identify and Classify Information and Assets](#21-identify-and-classify-information-and-assets)           |
| 2.2  | [ Identify and Classify Information and Assets](#22-establish-information-and-asset-handling-requirements) |

#
### 2.1 Identify and Classify Information and Assets

### What It Means:
Not all data or assets are equally valuable. Some are sensitive and must be heavily protected, while others are less critical. Classification helps an organization decide how much protection to apply. Think of it like labeling valuables at home—your passport gets locked in a safe, while old magazines stay on the coffee table.
#
### Data Classification:
This is about labeling data based on its sensitivity and importance to the organization. The goal is to protect sensitive data from unauthorized access while ensuring less critical data is still accessible when needed.

Common levels of data classification (names can vary by organization):

- **Public:** Safe to share openly (e.g., company brochures).
- **Internal Use Only**: Meant for employees but not outsiders (e.g., staff memos).
- **Confidential**: Sensitive information requiring limited access (e.g., financial reports).
- **Restricted/Highly Confidential**: Extremely sensitive, highest protection needed (e.g., trade secrets, customer PII).

<mark>**Examples:**</mark>
A hospital might classify patient records as Highly Confidential, while cafeteria menus are Public.
#
### Asset Classification:
Assets are not only data but also physical and digital resources (servers, laptops, applications, even people with critical knowledge). Asset classification ensures these resources are prioritized and protected.

Categories can include:

- **Hardware Assets:** Computers, servers, networking devices.
- **Software Assets**: Applications, operating systems, licenses.
- **Information Assets**: Databases, documents, intellectual property.
- **People Assets**: Employees with specialized knowledge or access.

<mark>**Examples:**</mark> 
An organization may classify its data center as a critical asset needing multiple security layers (locks, surveillance, fire suppression), while an office printer is a low-value asset with minimal protections.
#
### Key Takeaway:
By classifying data and assets, organizations know where to focus their security efforts. Sensitive or critical items get more protection, while less important ones don’t waste resources. This ensures the right balance between security, usability, and cost.

#

### 2.2 Establish Information and Asset Handling Requirements

### What It Means:
Once data and assets are classified (from 2.1), the next step is to define how they should be handled at every stage of their lifecycle—storage, use, transfer, and disposal. Handling requirements ensure sensitive assets are always treated with the right level of protection.
#
### Information Handling:
Handling requirements depend on the classification level of the data. The higher the sensitivity, the stricter the controls.

**Examples:**

- Public Data: Can be shared openly, no special requirements.
- Internal Use: Stored on company systems, shared only within the organization.
- Confidential: Encrypted when stored or sent, limited access with authentication.
- Highly Confidential/Restricted: Strict access control, encryption, logging of all access, physical security if printed.

<mark>**Examples:**</mark>
A financial report marked “Confidential” must be encrypted before emailing, while a press release (Public) can go on the company website.
#
### Asset Handling:
Assets (like hardware, software, and devices) also need handling rules.

**Examples:**

- **Hardware Assets:** Securely stored in controlled areas; laptops must be locked when unattended.
- **Software Assets:** Use licensed copies only, patch regularly, and control installations.
- **Information Assets:** Protect with backups, encryption, and access restrictions.
- **People Assets:** Train employees on security policies and limit their access to what they need (principle of least privilege).

<mark>**Examples:**</mark>
If an employee leaves the company, their laptop must be collected, wiped, and reissued properly, not just left in storage.
#
### Special Handling Situations:

**1.** **Storage:** Use encryption, backups, and secure physical locations.

**2.** **Transmission/Transfer:** Encrypt emails, use secure file transfer protocols, or hand-carry in sealed containers if physical.

**3.** **Printing/Copying:** Limit physical copies of sensitive information; use secure printers requiring user authentication.

**4.** **Disposal/Destruction:** Shred paper documents; wipe or physically destroy hard drives and other storage media.

<mark>**Examples:**</mark>
Throwing old hard drives in the trash could expose confidential data. Secure disposal ensures no one can recover it.
#
### Key Takeaway:
Handling requirements are about treating each piece of data or asset according to its sensitivity. Public items need minimal control, while highly confidential ones demand strict measures like encryption, access logs, and secure destruction. This ensures information stays protected throughout its entire lifecycle.

#
### 2.3 Provision Information and Assets Securely

### What It Means:
Provisioning means assigning and managing information and assets in a secure way from the moment they are created or acquired. This includes identifying who owns them, keeping an inventory, and managing them properly throughout their lifecycle.
#
### Information and Asset Ownership:
Every piece of information or asset should have a clear owner who is responsible for its security and use. The owner isn’t necessarily the person who uses it most but the one accountable for protecting it.

<mark>**Examples:**</mark>
The HR director may be the “owner” of employee records, even though HR staff handle the data daily. That director decides who can access it, how it’s protected, and how long it’s kept.
#
### Asset Inventory:
Organizations must maintain a complete list of all assets, both tangible (physical) and intangible (non-physical). This inventory helps track what needs protection.

- **Tangible Assets:** Hardware (servers, laptops, smartphones, networking gear).

- **Intangible Assets:** Data, software licenses, intellectual property, brand reputation.

<mark>**Examples:**</mark>
A company might have 100 laptops (tangible) and 50 software licenses for a database system (intangible). Both need to be tracked in the inventory system.
#

### Asset Management:
Managing assets means making sure they are secured, used properly, and maintained. This includes:

**1.** **Provisioning:** Assigning assets securely when employees need them (e.g., a new laptop with encrypted storage and antivirus before being issued).

**2.** **Tracking Usage:** Monitoring how assets are used to prevent misuse.

**3.** **Access Control:** Giving users only the level of access required (least privilege).

**4.** **Maintenance:** Regular updates, patches, and health checks.

**5.** **De-provisioning:** Securely reclaiming, wiping, or destroying assets when they are no longer needed.

<mark>**Examples:**</mark>
When a new employee joins, IT provisions a laptop with company-approved security settings. When the employee leaves, IT collects the laptop, wipes the data, and either reissues or disposes of it securely.
#
### Key Takeaway:
Secure provisioning ensures every asset has an owner, is tracked in an inventory, and is managed responsibly throughout its lifecycle. This prevents loss, misuse, or neglect of valuable information and resources.

#
### 2.4 Manage Data Lifecycle

### What It Means:
Data doesn’t stay in one place forever — it has a lifecycle: it’s collected, stored, used, maintained, and eventually destroyed. Managing this lifecycle ensures data remains protected and handled properly at every stage.
#
#### Data Roles:
Different people and groups have responsibilities for data security:

- **Owner:** Accountable for the data (decides classification, access, retention).

- **Controller:** Defines why and how data is processed (often tied to privacy laws like GDPR).

- **Custodian:** Maintains and protects data on behalf of the owner (e.g., IT team).

- **Processor:** Processes data according to the controller’s instructions (e.g., cloud provider).

- **User/Subject:** The person using the data (user) or the individual the data describes (subject).

<mark>**Examples:**</mark>
In a hospital, the patient is the subject, the hospital administration is the controller, the IT staff are custodians, and a cloud storage provider may be a processor.
#
#### Data Collection:
Collect only what’s necessary, and do it lawfully. Avoid gathering excessive personal information that creates unnecessary risk.

<mark>**Examples:**</mark>
An online shop should collect your address for delivery, but not your social security number.
#
#### Data Location:
Know where data is stored — on-premises, in the cloud, or across borders. Data location matters for compliance and legal reasons.

<mark>**Examples:**</mark>
GDPR restricts transferring EU citizens’ data to countries without strong privacy protections.
#
#### Data Maintenance:
Keep data accurate, complete, and up to date. This includes applying security measures such as encryption, patching systems, and regular access reviews.

<mark>**Examples:**</mark>
Updating customer contact details and ensuring databases are patched to prevent breaches.
#
#### Data Retention:
Data should only be kept as long as it is needed for legal, business, or regulatory reasons. After that, it must be securely deleted.

<mark>**Examples:**</mark>
A bank may keep transaction data for 7 years (legal requirement) but must delete it after that period.
#
#### Data Remanence:
Even after deleting data, traces may remain on storage media (like ghost images of files on a hard drive). Special care is needed to ensure it’s unrecoverable.

<mark>**Examples:**</mark>
Simply deleting a file from your computer doesn’t erase it completely; specialized tools can recover it unless it’s securely wiped.
#
#### Data Destruction:
Data must be destroyed securely to prevent unauthorized recovery. Methods include:

- **Shredding** paper documents.

- **Wiping** or **degaussing** hard drives.

- **Physical** destruction (smashing or incinerating drives).

<mark>**Examples:**</mark>
Old company laptops should not just be sold off with intact hard drives; the drives must be securely wiped or destroyed first.
#
### Key Takeaway:
Managing the data lifecycle ensures that information is collected responsibly, stored securely, maintained accurately, retained only as long as needed, and destroyed safely. This protects both the organization and the individuals whose data is being handled.
#

### 2.5 Ensure Appropriate Asset Retention (EOL/EOS)

### What It Means:
Every asset (hardware, software, or data) has a useful life. Over time, it reaches End of Life (EOL) or End of Support (EOS). At these points, the vendor stops updates, patches, or maintenance. If an organization continues using such assets, they become security risks. Proper asset retention means knowing when to keep, upgrade, or retire assets safely.
#
### End of Life (EOL):
The product is no longer sold or actively developed by the vendor. It may still function, but it’s considered outdated.

<mark>**Examples:**</mark>
A company using Windows 7 after Microsoft declared it EOL risks exposure to modern attacks.
#
### End of Support (EOS):
The vendor stops providing updates, patches, or technical support. This is even riskier than EOL because vulnerabilities discovered after EOS remain unpatched.

<mark>**Examples:**</mark>
A router at EOS will not get firmware updates, leaving it open to known exploits.
#
### Why It Matters:

**1. Security Risk:** No patches = open doors for hackers.

**2. Compliance Risk:** Regulations (e.g., PCI DSS) require supported systems. Using EOS/EOL assets may cause legal or audit failures.

**3. Operational Risk:** Unsupported assets may fail or not integrate with newer systems.
#
### How to Manage Asset Retention:

**1. Track Assets:** Maintain an updated inventory with purchase dates and vendor lifecycle information.

**2. Plan Ahead:** Before EOL/EOS, budget for upgrades or replacements.

**3. Migrate Securely:** Move data/software to supported platforms before the cutoff.

**4. Decommission Properly:** Wipe or destroy old hardware, revoke licenses, and archive data as per retention policy.

<mark>**Examples:**</mark>
If company laptops are nearing EOS for their operating system, IT should plan upgrades months in advance, not after vulnerabilities appear.
#
### Key Takeaway:
Asset retention is about using assets only while they are secure and supported. Once they hit EOL or EOS, they should be upgraded, replaced, or securely decommissioned. This ensures ongoing security, compliance, and business continuity.
#
### 2.6 Determine Data Security Controls and Compliance Requirements

### What It Means:
Data security controls are the measures put in place to protect information throughout its lifecycle. Compliance requirements ensure that the organization meets legal, regulatory, and contractual obligations. Determining the right controls depends on the state of data, the scope of protection, and the chosen standards.

### Data States:
Data can exist in three primary states, each requiring specific protection:

- **Data at Rest:** Stored data (databases, files, backups). Protect with encryption and access controls.

- **Data in Transit:** Data being transmitted over networks. Protect with encryption (e.g., TLS/SSL) and secure channels.

- **Data in Use:** Data actively being processed (in memory, on screens). Protect with access control and monitoring.

<mark>**Examples:**</mark>
Encrypting a database (at rest), using HTTPS for a web application (in transit), and restricting who can view or edit files in memory (in use).

### Scoping and Tailoring:
Determine which data needs protection and customize controls based on risk, value, and compliance needs. Not all data requires the same level of control.

<mark>**Examples:**</mark>
Internal emails might only need access control, while customer payment information requires strong encryption, DLP, and audit logging.

### Standards Selection:
Use recognized frameworks or standards to guide security control implementation. Common examples:

- **ISO 27001/27002 –** Information security management.

- **NIST SP 800-53 –** Security and privacy controls.

- **PCI DSS –** Payment card data.

- **GDPR/CCPA –** Privacy compliance.

<mark>**Examples:**</mark>
A company handling credit card payments follows PCI DSS to implement mandatory encryption, logging, and monitoring controls.

### Data Protection Methods:

**1. Digital Rights Management (DRM):** Controls who can access, copy, or share digital files.

**2. Data Loss Prevention (DLP):** Monitors and prevents sensitive data from leaving the organization.

**3. Cloud Access Security Broker (CASB):** Provides visibility and security controls for cloud services.

<mark>**Examples:**</mark>
Using DLP software to prevent employees from emailing sensitive financial reports to personal accounts, and using a CASB to monitor data in SaaS applications like Salesforce.

### Key Takeaway:
Determining data security controls involves understanding the state of data, defining the scope of protection, selecting appropriate standards, and implementing technical and procedural safeguards. These measures not only protect information but also ensure compliance with laws, regulations, and contractual obligations.
