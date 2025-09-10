# Domain 5: Identity and Access Management (IAM)
**_Weightage:_** _13%_

### Table of Contents  
|     | Topics                                                                                             |
| --- | :------------------------------------------------------------------------------------------------- |
| 5.1 | [Control physical and logical access to assets](#51-control-physical-and-logical-access-to-assets) |


#
### 5.1 Control physical and logical access to assets

### What It Means:
Identity and Access Management (IAM) ensures that only the right people, with the right permissions, at the right time can access organizational assets. This includes both physical access (to buildings, rooms, or equipment) and logical access (to digital systems, data, and applications). The goal is to reduce the risk of unauthorized access, insider threats, and data breaches.

#
### Information

Information is the most valuable asset an organization owns. It can exist in many forms (digital files, printed documents, backups). Protecting information means ensuring only authorized individuals can view, modify, or destroy it, based on its sensitivity.

- **Role-Based Access Control (RBAC):** Assigns access based on job function.

- **Data Classification:** Information is categorized (e.g., public, confidential, secret) and access rules are applied.

- **Encryption:** Protects sensitive data from being read if intercepted.

<mark>**Example:**</mark>  
HR employees can view payroll records, but only finance staff can modify them. Others have no access.

#
### Systems

Systems are IT components like servers, operating systems, and databases that process and store information. Unauthorized access can compromise availability and integrity.

- **Authentication:** Ensures the user is who they claim (passwords, biometrics, MFA).

- **Authorization:** Grants permissions only to approved resources.

- **Audit Logging:** Records who accessed what and when.

<mark>**Example:**</mark>  
A developer logs into a test server but cannot access the production server, as access is limited to operations staff.

#
### Devices

Devices are the user-facing endpoints such as laptops, desktops, smartphones, and IoT devices. Since they are distributed widely among employees and often leave the secure office environment, they are usually the weakest link in the security chain.

<mark>**Example:**</mark>  
From a logical perspective, organizations install mobile device management (MDM) software, encrypt hard drives, and enforce endpoint antivirus protection. Physically, employees may secure their laptops with cable locks, store devices in secure lockers, or even use biometric authentication like fingerprint or facial recognition to prevent unauthorized access. an employee loses a corporate smartphone, the IT team can remotely wipe all data before it falls into the wrong hands.

#
### Facilities

Facilities are the physical locations where information and systems reside, including offices, data centers, and branch sites. Protecting these facilities prevents unauthorized people from physically entering and tampering with systems or stealing data.

<mark>**Example:**</mark>  
Access to sensitive areas is restricted through guards, CCTV surveillance, smart card readers, mantraps, and biometric scanners. Visitor logs are also maintained to track who enters and exits secure areas. In some organizations, even logical systems like smart building controls are integrated with central identity and access management platforms.  

#
### Applications

Applications are the software systems that help businesses perform daily functions, such as email systems, accounting software, HR portals, and customer management tools. Since they often handle sensitive data, protecting applications from unauthorized access is critical.  

<mark>**Example:**</mark>  
Access is controlled by applying role-based access control (RBAC), single sign-on (SSO), and least privilege principles to ensure users only have the access required for their job. For instance, an HR employee may be able to view salary records but not modify them, and developers are prevented from accessing production servers directly.
#
### Services

Services refer to IT and network-based offerings like cloud platforms, web applications, DNS, and email services. Since services often connect to the outside world, they are a common target for attackers and need strong access controls.  

<mark>**Example:**</mark>  
Access to services can be controlled through the use of API keys, VPN connections, or secure communication protocols like TLS. Cloud-based services are protected with IAM policies and monitoring, while physically the hosting data centers are locked down to allow only administrators and service engineers entry.

#
### Key Takeaway

Controlling access to assets always requires thinking in two layers: physical and logical controls. Protecting information, systems, devices, facilities, applications, and services is not a one-time task but an ongoing effort that involves applying the right security measures at both layers. The best protection strategy is defense-in-depth, where multiple overlapping controls are used so that if one fails, another still provides protection. Finally, different access control models—such as discretionary access control (DAC), mandatory access control (MAC), role-based access control (RBAC), and attribute-based access control (ABAC)—guide how permissions are assigned and enforced, ensuring that only the right people get access to the right assets at the right time.