# **SAMULCO IT Policy 05: Information Security**

**Subject:** Information Security Policy\
**Effectivity Date:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\
**Issued by:** ICT Department\
**Revised Date:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\
**Approved by:** Board of Directors\
**Last Board Review Date:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

## **1. PURPOSE**

This policy establishes the information security framework for Sta. Ana
Multipurpose Cooperative (SAMULCO) to protect information assets, ensure
business continuity, maintain member trust, and comply with regulatory
requirements. It defines security controls, procedures, and
responsibilities to safeguard against threats and vulnerabilities.

## **2. SCOPE**

This policy applies to all:

-   SAMULCO personnel (employees, officers, Board members, contractors,
    > interns)

-   Information systems and technology resources

-   Data and information assets (electronic and physical)

-   Third-party service providers with access to SAMULCO systems

-   Business processes that handle sensitive information

## **3. INFORMATION SECURITY OBJECTIVES**

### **3.1 Primary Security Objectives**

#### **3.1.1 Confidentiality**

-   Protect sensitive information from unauthorized disclosure

-   Implement access controls and data classification

-   Maintain privacy of member and employee information

-   Secure communications and data transmission

-   Ensure proper handling of confidential information

#### **3.1.2 Integrity**

-   Protect information from unauthorized modification

-   Ensure accuracy and completeness of data

-   Maintain system and data reliability

-   Implement change management controls

-   Detect and prevent data corruption

#### **3.1.3 Availability**

-   Ensure authorized access to information when needed

-   Maintain system uptime and performance

-   Implement business continuity measures

-   Provide timely recovery from disruptions

-   Ensure reliable system operations

### **3.2 Security Management Principles**

#### **3.2.1 Defense in Depth**

-   Implement multiple layers of security controls

-   Use complementary security measures

-   Provide redundant protection mechanisms

-   Address security at all system levels

-   Continuously monitor and improve defenses

#### **3.2.2 Least Privilege**

-   Grant minimum access required for job functions

-   Implement role-based access controls

-   Regular review and adjustment of privileges

-   Segregation of duties for critical functions

-   Prompt removal of unnecessary access

#### **3.2.3 Risk-Based Approach**

-   Identify and assess security risks

-   Implement controls proportionate to risks

-   Prioritize protection of critical assets

-   Regular risk assessments and updates

-   Balance security with business operations

## **4. PASSWORD POLICY**

### **4.1 Password Requirements**

#### **4.1.1 Complexity Standards**

**All passwords must meet the following minimum requirements:**

-   **Length:** Minimum 12 characters, recommended 15+ characters

-   **Complexity:** Must contain at least three of the following:

    -   Uppercase letters (A-Z)

    -   Lowercase letters (a-z)

    -   Numbers (0-9)

    -   Special characters (!@#\$%\^&\*()\_+-=\[\]{}\|;:,.\<\>?)

-   **Uniqueness:** Must not reuse the last 12 passwords

-   **Dictionary Words:** Must not be based on dictionary words

-   **Personal Information:** Must not contain personal information
    > (name, birthdate, etc.)

#### **4.1.2 Passphrase Alternative**

**For enhanced security and usability, passphrases are encouraged:**

-   Minimum 20 characters using multiple unrelated words

-   Include spaces and punctuation for complexity

-   Example: \"Coffee#Mountain\$River!Sky92\"

-   Must not be common phrases or quotes

-   Should be memorable but not predictable

#### **4.1.3 System-Specific Requirements**

**High-Privilege Accounts (Administrators, Database Access):**

-   Minimum 15 characters

-   Must include all four character types

-   Change every 60 days

-   Multi-factor authentication required

**Standard User Accounts:**

-   Minimum 12 characters

-   Change every 90 days

-   Self-service password reset available

-   Account lockout after 5 failed attempts

**Service Accounts:**

-   Minimum 20 characters randomly generated

-   Change every 180 days or when staff changes

-   Managed through privileged access management system

-   Regular review of service account usage

### **4.2 Password Management**

#### **4.2.1 Creation and Storage**

-   **Password Creation:** Use approved password generators for complex
    > passwords

-   **Storage:** Store passwords securely using approved password
    > managers

-   **Sharing:** Never share passwords with others under any
    > circumstances

-   **Writing Down:** Avoid writing passwords down; if necessary, store
    > securely

-   **Default Passwords:** Change all default passwords immediately upon
    > installation

#### **4.2.2 Password Managers**

**Approved Password Management Solutions:**

-   Enterprise password management systems

-   Individual password managers for personal accounts

-   Encrypted storage with master password/key

-   Regular backup and synchronization

-   Two-factor authentication for password manager access

#### **4.2.3 Password Rotation**

-   **Scheduled Changes:** Follow established change intervals

-   **Compromise Response:** Change immediately if compromise suspected

-   **Staff Changes:** Change shared passwords when staff leave

-   **System Updates:** Consider password changes after major system
    > updates

-   **Incident Response:** Change passwords as part of security incident
    > recovery

### **4.3 Multi-Factor Authentication (MFA)**

#### **4.3.1 MFA Requirements**

**Mandatory MFA for:**

-   Administrative accounts and privileged access

-   Remote access to SAMULCO systems

-   Access to sensitive member data

-   Financial and accounting systems

-   Email and collaboration platforms

-   Cloud-based applications and services

#### **4.3.2 Authentication Factors**

**Something You Know (Knowledge Factor):**

-   Passwords and passphrases

-   Personal identification numbers (PINs)

-   Security questions and answers

**Something You Have (Possession Factor):**

-   Mobile phone SMS or authentication apps

-   Hardware security tokens

-   Smart cards and certificates

-   USB security keys

**Something You Are (Inherence Factor):**

-   Fingerprint recognition

-   Voice recognition

-   Facial recognition

-   Retina or iris scanning

#### **4.3.3 MFA Implementation**

-   **Primary Method:** Mobile app-based authenticators (preferred)

-   **Backup Method:** SMS or voice calls (secondary)

-   **Hardware Tokens:** For high-security requirements

-   **Biometrics:** Where available and appropriate

-   **Recovery Procedures:** Secure methods for MFA reset

## **5. ACCESS CONTROL MANAGEMENT**

### **5.1 Access Control Framework**

#### **5.1.1 Identity and Access Management (IAM)**

-   **User Provisioning:** Standardized process for creating user
    > accounts

-   **Role-Based Access Control (RBAC):** Access based on job roles and
    > responsibilities

-   **Attribute-Based Access Control (ABAC):** Dynamic access based on
    > multiple attributes

-   **Privileged Access Management (PAM):** Special controls for
    > administrative access

-   **Single Sign-On (SSO):** Centralized authentication where feasible

#### **5.1.2 Access Request Process**

1.  **Request Initiation:** HR for new employee or manager submits
    > formal access request

2.  **Business Justification:** Clear explanation of access need and
    > duration

3.  **Manager Approval:** Direct supervisor approves the business need

4.  **Security Review:** Security team reviews risk and appropriateness

5.  **Technical Implementation:** IT team provisions access according to
    > specifications

6.  **Verification:** Requester confirms access is working as expected

7.  **Documentation:** Access grant recorded in access management system

### **5.2 Role-Based Access Control (RBAC)**

#### **5.2.1 Standard Role Definitions**

**~~Executive~~ ACCOUNTANT Level:** This group comprises the Executive
and Financial Authority responsible for primary decision-making,
transactional approval, and system governance. Their collective roles
ensure the Segregation of Duties (SoD) and maintain audit integrity.

-   ~~Board Members: Governance oversight and strategic information
    > access~~

-   ~~General Manager: Full operational access with executive
    > reporting~~

-   ~~Department Heads: Full departmental access with cross-functional
    > viewing rights~~

  -----------------------------------------------------------------------
  Group                       Role\*
  --------------------------- -------------------------------------------
  Board of Directors          Governance oversight and strategic
                              information access

  CEO, COO                    Operational oversight and executive
                              decision processes

  CFO, Treasurer              Financial and Resource oversight

  CCM, Accounting Manager,    Operational and transactional approval
  Accounting Supervisors      including reviews

  Internal Audit, Compliance  Independent audits and compliance reviews
  -----------------------------------------------------------------------

*\* Including cross-functional viewing authority*

**~~Management Level:~~**

-   ~~Branch Managers: Branch operations with regional oversight
    > capabilities~~

-   ~~Supervisors: Team management with departmental operational
    > access~~

-   ~~Team Leads: Project coordination with limited administrative
    > rights~~

**BOOKEEPER LEVEL:** This segment is responsible for the recording,
reconciling, and reporting financial transactions

  -----------------------------------------------------------------------
  Group                   Role\*
  ----------------------- -----------------------------------------------
  Accounting Associate    Preparing accounting entries in the system for
                          review. Review and post entries prepared by
                          other departments in the system.

  Payroll clerk           Prepares payroll entries and other related
                          payroll transactions

  Bookkeeper              Reviews and post the accounting entries.
                          Preparation of the financial reports
  -----------------------------------------------------------------------

*\* Viewing access is limited to the books of the branch maintained.*

**~~Operational Level:~~**

-   ~~Tellers: Customer service functions with transaction processing
    > rights~~

-   ~~Loan Officers: Credit assessment and loan processing
    > capabilities~~

-   ~~Accountants: Financial data access with reporting and analysis
    > rights~~

-   ~~Administrative Staff: Support functions with document management
    > access~~

**CASHIER LEVEL:** This segment defines the Front Office Cash Management
Role. Users assigned this privilege are authorized to execute and record
all primary cash movements, ensuring proper reconciliation and daily
control.

Personnel performing Head Cashier functions will have this access.

**CLERK LEVEL**: This group is designated as Membership Database
Administration. Personnel within this role are granted specific user
access rights to perform essential member life-cycle management
functions.

  -----------------------------------------------------------------------
  Group                   Role\*
  ----------------------- -----------------------------------------------
  Members Relations       Members personal information and accounts
  Accounts Associate      administration. This covers from account set
                          up, information maintenance and account system
                          closure

  Loans Clerk             Loan account set-up, loan entry set-up in Loan
                          Processing module

  Loans Supervisor        Loan hold outs updates and preliminary loan
                          disbursement entry creation
  -----------------------------------------------------------------------

**CREDIT MANAGER LEVEL:** This access segment covers the functions vital
for credit risk control. It grants the system rights for system-based
loan approvals and includes all necessary access for the monitoring and
continuous risk assessment of SAMULCO\'s total loan portfolio. This
functions reserves to Credit Analysts and Loan Officers

**TELLER LEVEL:** This access segment is specifically reserved for
personnel who perform core Front Office Transaction Services. This
privilege is assigned to Tellers and Collection Associates, whose
primary functions require direct system interaction with member accounts
for financial transactions.

**MEMBERSHIP HEAD LEVEL:** This segment is designated to provide member
asstance on the accounts and data analytics. This is for the Marketing,
Research and Members Relations Department.

**MANAGER LEVEL:** This access segment grants personnel elevated system
authority necessary to validate and approve critical operational
processes. This function reserves to the branch managers, satellite
officers and loan officers.

**INQUIRY ONLY LEVEL**: This access segment grants personnel read-only
system privileges to view member accounts and related profile
information. The purpose is strictly for verification, compliance, and
fulfilling assigned functions that require informed decision-making
without the ability to transact or alter data. This access is logically
divided into two tiers based on the requirement for physical
documentation:

  -----------------------------------------------------------------------
  Group                    Reserve for
  ------------------------ ----------------------------------------------
  With printing authority  Accounts Specialists, Credit Investigators

  With out printing        Other authorized personnel not mention in this
  authority                section 5.2.1
  -----------------------------------------------------------------------

**Technical Level:**

-   Chief ICT Officer: Full system administration with security oversight

-   System Administrators: Infrastructure management and user support

-   Database Administrators: Database operations with backup and
    > recovery rights

-   Developers: Application development with limited production access

#### **5.2.2 Access Matrix Example**

+------------+------------+----------------+------------+-------------+
| **~~Role~~ | **Member   | **Financial    | **Admin    | **Reporting |
| Level**    | Data**     | Systems**      | Systems**  | Tools**     |
+============+============+================+============+=============+
| ACCOUNTANT | Read Only  | Generation,    | Read       | Full Access |
|            |            | Printing       | Access     |             |
+------------+------------+----------------+------------+-------------+
| BOOKKEEPER | Read Only  | Back Office    | Audit logs | ###         |
|            |            | Module         | for        | Full Access |
|            | Tagging    |                | Subsidiary |             |
|            | Closed     |                | ledgers    |             |
|            | members    |                |            |             |
|            | thru       |                |            |             |
|            | i          |                |            |             |
|            | nvoluntary |                |            |             |
|            | t          |                |            |             |
|            | ermination |                |            |             |
+------------+------------+----------------+------------+-------------+
| CASHIER    | Read       | Front Office   | None       | Front       |
|            | Access     | Module         |            | Office      |
|            |            |                |            | reports     |
+------------+------------+----------------+------------+-------------+
| TELLER     | Read       | Front Office   | None       | Front       |
|            | Access     | Module         |            | Office      |
|            |            |                |            | reports     |
+------------+------------+----------------+------------+-------------+
| MEMBERSHIP | Read       | None           | None       | Data        |
| HEAD       | Access     |                |            | Analytics   |
+------------+------------+----------------+------------+-------------+
| CLERK      | Profile    | Loan Module    | None       | Limited to  |
|            | Ceation,   |                |            | membership  |
|            | Account    |                |            | t           |
|            | Setup,     |                |            | ransactions |
|            | I          |                |            |             |
|            | nformation |                |            |             |
|            | Ma         |                |            |             |
|            | intenance, |                |            |             |
|            | Profile    |                |            |             |
|            | Closure    |                |            |             |
+------------+------------+----------------+------------+-------------+
| CREDIT     | Read       | Loan Module    | None       | Aging and   |
| MANAGER    | Access     |                |            | related     |
|            |            |                |            | analytics   |
+------------+------------+----------------+------------+-------------+
| MANAGER    | Profile    | Transactional  | None       | Branch      |
|            | Approval   | Approval       |            | operations  |
|            | including  |                |            | reports and |
|            | updates,   |                |            | related     |
|            | Account    |                |            | analytics   |
|            | Set-up and |                |            |             |
|            | Closure    |                |            |             |
|            | Approval   |                |            |             |
+------------+------------+----------------+------------+-------------+
| INQUIRY    | Read       | None           | None       | For TIER 1: |
| LEVEL      | Access     |                |            | Statement   |
|            |            |                |            | of          |
|            |            |                |            | Accounts,   |
|            |            |                |            | Aging per   |
|            |            |                |            | zone        |
|            |            |                |            |             |
|            |            |                |            | TIER 2:     |
|            |            |                |            | None        |
+------------+------------+----------------+------------+-------------+

### **5.3 Annex A -- IAccs2013 User Access Rights Implementing Rules and Regulations (IRR)**

*The detailed procedures, controls, and implementing rules governing
user access rights are defined in the iAccs User Access Rights
Implementing Rules and Regulations (IRR).*

*This document serves as the operational standard for access
provisioning, modification, review, and revocation and must be read in
conjunction with this Information Security Policy.*

### **(Document Reference: SAMULCO-CMP-11)**

[[user access rights version
final.docx]{.underline}](https://docs.google.com/document/u/0/d/1Y72U7BGQNZjOk8lfREtff77Osb2zB4PK/edit)

### **5.4 Privileged Access Management**

#### **5.4.1 Privileged Account Types**

**Administrative Accounts:**

-   System administrators with full server access

-   Database administrators with data modification rights

-   Network administrators with infrastructure control

-   Security administrators with policy management rights

**Service Accounts:**

-   Application service accounts for system-to-system communication

-   Batch processing accounts for automated tasks

-   Integration accounts for inter-system connections

-   Backup and recovery service accounts

**Emergency Access:**

-   Break-glass accounts for emergencies

-   Vendor support accounts for third-party assistance

-   Incident response accounts for security events

-   Business continuity accounts for disaster recovery

#### **5.4.2 Privileged Access Controls**

-   **Approval Workflow:** Multi-level approval for privileged access
    > requests

-   **Time-Limited Access:** Automatic expiration of temporary
    > privileged access

-   **Session Monitoring:** Recording and monitoring of privileged user
    > sessions

-   **Access Reviews:** Regular certification of privileged access
    > necessity

-   **Segregation of Duties:** Separation of conflicting privileged
    > functions

### **5.5 Access Review and Certification**

#### **5.5.1 Regular Access Reviews**

**Monthly Reviews:**

-   New access grants and modifications

-   Terminated employee access removal verification

-   Service account usage and necessity

-   Failed access attempts and anomalies

**Quarterly Reviews:**

-   Departmental access certification by managers

-   Role-based access appropriateness assessment

-   Privileged access necessity verification

-   System access usage analysis

**Annual Reviews:**

-   Comprehensive access rights certification

-   Role definition updates and modifications

-   Access control effectiveness assessment

-   Compliance with regulatory requirements

#### **5.5.2 Access Recertification Process**

1.  **Automated Reports:** System generates current access reports

2.  **Manager Review:** Department managers review their staff\'s access

3.  **Attestation:** Managers certify access is appropriate and
    > necessary

4.  **Exception Handling:** Address access that cannot be certified

5.  **Remediation:** Remove or modify inappropriate access

6.  **Documentation:** Record certification results and actions taken

## **6. DEVICE AND WORKSTATION SECURITY**

### **6.1 Endpoint Security Requirements**

#### **6.1.1 Mandatory Security Software**

**Anti-Malware Protection:**

-   Enterprise-grade anti-virus and anti-malware software

-   Real-time scanning and protection enabled

-   Automatic signature updates configured

-   Regular full system scans scheduled

-   Centralized management and reporting

**Host-Based Intrusion Prevention (HIPS):**

-   Behavioral monitoring and anomaly detection

-   Application whitelisting where appropriate

-   Network connection monitoring

-   File integrity monitoring for critical systems

-   Automated threat response capabilities

**Data Loss Prevention (DLP):**

-   Content inspection and classification

-   Endpoint data protection controls

-   Removable media control and encryption

-   Network data transmission monitoring

-   Policy enforcement and user education

#### **6.1.2 Operating System Security**

**Patch Management:**

-   Automated patch deployment for critical updates

-   Testing procedures for significant updates

-   Scheduled maintenance windows for patching

-   Emergency patching procedures for critical vulnerabilities

-   Patch compliance monitoring and reporting

**System Configuration:**

-   Hardened operating system configurations

-   Unnecessary services and applications disabled

-   Security policies enforced through Group Policy

-   User Account Control (UAC) enabled on Windows systems

-   Secure boot and TPM utilization where available

### **6.2 Workstation Security Controls**

#### **6.2.1 Physical Security Measures**

**Screen Lock Requirements:**

-   Automatic screen lock after 15 minutes of inactivity

-   Manual screen lock when leaving workstation (Windows + L)

-   Password or biometric authentication required to unlock

-   Screen saver password protection enabled

-   Privacy screens for sensitive data viewing in public areas

**Physical Protection:**

-   Cable locks for portable devices in offices

-   Secure storage for devices when not in use

-   Clean desk policy for sensitive documents

-   Equipment inventory and asset tagging

-   Visitor access controls and supervision

#### **6.2.2 Software Installation Controls**

**Approved Software Only:**

-   Centralized software deployment and management

-   Application whitelisting on critical systems

-   User restrictions on software installation

-   Regular software inventory and compliance checking

-   Removal of unauthorized or unnecessary software

**Software Licensing:**

-   Compliance with all software license agreements

-   Regular license audits and true-up processes

-   Documentation of software ownership and entitlements

-   Vendor relationship management for support

-   Legal review of software licensing terms

### **6.3 Mobile Device Security**

#### **6.3.1 Mobile Device Management (MDM)**

**Device Enrollment:**

-   Mandatory enrollment for SAMULCO-owned devices

-   Optional enrollment for personal devices used for business (BYOD)

-   Device registration and inventory management

-   Compliance verification before network access

-   User acknowledgment of security policies

**Security Policies:**

-   Device encryption requirements

-   Strong authentication (PIN, password, biometrics)

-   Remote wipe capabilities for lost or stolen devices

-   Application approval and blacklisting

-   Network access controls and VPN requirements

#### **6.3.2 BYOD (Bring Your Own Device) Policy**

**Eligibility Requirements:**

-   Written agreement and acknowledgment of policies

-   Device meets minimum security requirements

-   Installation of required security applications

-   Separate business and personal data containers

-   Compliance with SAMULCO acceptable use policies

**Security Controls:**

-   Multi-factor authentication for business applications

-   Encrypted storage for business data

-   Automatic security updates enabled

-   Regular compliance monitoring and reporting

-   Immediate reporting of device loss or compromise

## **7. ENCRYPTION AND DATA PROTECTION**

### **7.1 Encryption Standards**

#### **7.1.1 Approved Encryption Algorithms**

**Symmetric Encryption:**

-   AES (Advanced Encryption Standard) 256-bit minimum

-   3DES acceptable for legacy systems only

-   ChaCha20-Poly1305 for modern implementations

-   Regular review of encryption algorithm strength

-   Migration planning for deprecated algorithms

**Asymmetric Encryption:**

-   RSA 2048-bit minimum (4096-bit recommended)

-   Elliptic Curve Cryptography (ECC) P-384 minimum

-   Digital signature algorithms with equivalent strength

-   Key exchange protocols with forward secrecy

-   Certificate-based authentication where appropriate

**Hashing Algorithms:**

-   SHA-256 minimum for new implementations

-   SHA-3 for enhanced security requirements

-   HMAC for message authentication codes

-   Bcrypt or scrypt for password hashing

-   Prohibition of MD5 and SHA-1 for security purposes

#### **7.1.2 Key Management Requirements**

**Key Generation:**

-   Use certified random number generators

-   Sufficient entropy for cryptographic strength

-   Hardware security modules (HSM) for critical keys

-   Documented key generation procedures

-   Regular testing of key generation systems

**Key Storage:**

-   Secure key storage separate from encrypted data

-   Hardware security modules for high-value keys

-   Key escrow for business continuity purposes

-   Access controls for key management systems

-   Audit logging of all key management activities

**Key Lifecycle Management:**

-   Regular key rotation based on risk assessment

-   Secure key distribution and deployment

-   Key revocation and replacement procedures

-   End-of-life key destruction processes

-   Documentation of key lifecycle activities

### **7.2 Data Encryption Requirements**

#### **7.2.1 Data at Rest Encryption**

**Database Encryption:**

-   Transparent Data Encryption (TDE) for database files

-   Column-level encryption for highly sensitive data

-   Encrypted database backups and archives

-   Key management integration with database systems

-   Performance impact assessment and optimization

**File System Encryption:**

-   Full disk encryption for all laptops and portable devices

-   File-level encryption for sensitive document repositories

-   Encrypted storage for backup and archive systems

-   Network attached storage (NAS) encryption

-   Cloud storage encryption with customer-managed keys

#### **7.2.2 Data in Transit Encryption**

**Network Communications:**

-   TLS 1.3 for web-based applications and APIs

-   VPN encryption for remote access connections

-   Encrypted email for sensitive communications

-   Secure file transfer protocols (SFTP, FTPS)

-   Network segmentation and micro-segmentation

**Application Communications:**

-   API encryption with proper certificate validation

-   Database connection encryption (SSL/TLS)

-   Inter-system communication encryption

-   Message queue encryption for asynchronous processing

-   Service mesh encryption for microservices architectures

### **7.3 Certificate Management**

#### **7.3.1 Digital Certificate Requirements**

**Certificate Authority (CA) Trust:**

-   Use of trusted public CAs for external communications

-   Internal CA for organizational certificates

-   Regular CA certificate validation and updates

-   Certificate transparency monitoring

-   Revocation checking (OCSP/CRL) implementation

**Certificate Lifecycle:**

-   Automated certificate enrollment and renewal

-   Certificate inventory and expiration monitoring

-   Regular certificate audits and compliance checks

-   Secure certificate storage and deployment

-   Certificate revocation procedures

#### **7.3.2 Certificate Policies**

**Certificate Usage:**

-   Purpose-specific certificates (web server, email, code signing)

-   Extended Validation (EV) certificates for public-facing services

-   Wildcard certificate usage restrictions

-   Certificate pinning for critical applications

-   Regular certificate policy reviews and updates

## **8. REMOTE WORK SECURITY**

### **8.1 Remote Access Requirements**

#### **8.1.1 VPN (Virtual Private Network) Requirements**

**Mandatory VPN Usage:**

-   All remote connections must use approved VPN solutions

-   Multi-factor authentication required for VPN access

-   Split tunneling prohibited for business applications

-   Regular VPN client updates and security patches

-   Centralized VPN logging and monitoring

**VPN Configuration Standards:**

-   Strong encryption protocols (IPSec, OpenVPN, WireGuard)

-   Perfect Forward Secrecy (PFS) enabled

-   Automatic VPN connection for business applications

-   Kill switch functionality to prevent data leakage

-   DNS leak protection and secure DNS resolution

#### **8.1.2 Remote Desktop and Application Access**

**Secure Remote Desktop:**

-   Network Level Authentication (NLA) enabled

-   Strong encryption for remote desktop sessions

-   Multi-factor authentication integration

-   Session timeout and automatic disconnection

-   Restricted remote desktop access based on role

**Cloud-Based Application Access:**

-   Single Sign-On (SSO) for cloud applications

-   Conditional access policies based on device and location

-   Application-specific security policies

-   Regular access reviews and certifications

-   Zero-trust architecture implementation

### **8.2 Home Office Security**

#### **8.2.1 Network Security Requirements**

**Home Network Protection:**

-   WPA3 encryption for home Wi-Fi networks

-   Default password changes for home network equipment

-   Firmware updates for routers and network devices

-   Network segmentation for business and personal use

-   Guest network setup for visitors and family members

**Internet Connection Security:**

-   Avoid public Wi-Fi for business activities

-   Use mobile hotspot as backup internet connection

-   VPN usage for all business communications

-   Secure DNS configuration (1.1.1.1, 8.8.8.8)

-   Network monitoring for suspicious activities

#### **8.2.2 Physical Security Measures**

**Home Office Setup:**

-   Dedicated workspace separate from family areas

-   Locking file cabinets for confidential documents

-   Privacy screens to prevent shoulder surfing

-   Secure storage for business devices when not in use

-   Visitor restrictions and supervision protocols

**Environmental Controls:**

-   Adequate lighting for security and productivity

-   Climate control to protect electronic equipment

-   Power surge protection for business equipment

-   Backup power solutions for critical work periods

-   Fire safety measures for home office area

### **8.3 Remote Work Monitoring and Compliance**

#### **8.3.1 Security Monitoring**

**Endpoint Monitoring:**

-   Centralized endpoint detection and response (EDR)

-   Real-time security status monitoring

-   Automatic security policy enforcement

-   Compliance checking and reporting

-   Incident detection and automated response

**Network Monitoring:**

-   VPN connection logging and analysis

-   Network traffic monitoring for anomalies

-   DNS query monitoring and filtering

-   Bandwidth usage monitoring and management

-   Geographic access monitoring and alerting

#### **8.3.2 Compliance Requirements**

**Regular Check-ins:**

-   Weekly security status reviews with supervisors

-   Monthly remote work security assessments

-   Quarterly home office security audits

-   Annual remote work policy compliance certification

-   Continuous security awareness training updates

**Documentation and Reporting:**

-   Remote work setup documentation and approval

-   Security incident reporting procedures

-   Regular compliance status reporting

-   Equipment inventory and condition reporting

-   Policy acknowledgment and certification records

## **9. SECURITY AWARENESS AND TRAINING**

### **9.1 Security Training Programs**

#### **9.1.1 General Security Awareness**

**All Employee Training:**

-   Annual comprehensive security awareness training

-   Monthly security tips and updates

-   Quarterly phishing simulation exercises

-   Security policy updates and changes notification

-   Incident response procedures training

**Training Topics:**

-   Password security and multi-factor authentication

-   Email and phishing attack recognition

-   Social engineering tactics and prevention

-   Physical security and clean desk policies

-   Data classification and handling procedures

-   Incident reporting and response procedures

#### **9.1.2 Role-Specific Training**

**IT Staff Training:**

-   Advanced security technologies and tools

-   Threat intelligence and vulnerability management

-   Incident response and forensics procedures

-   Security architecture and design principles

-   Compliance and audit requirements

**Management Training:**

-   Security governance and risk management

-   Business continuity and disaster recovery

-   Vendor management and third-party risk

-   Regulatory compliance requirements

-   Crisis communication and leadership

### **9.2 Security Communication Program**

#### **9.2.1 Regular Communications**

**Security Newsletters:**

-   Monthly security awareness newsletters

-   Timely threat alerts and warnings

-   Security success stories and recognition

-   Policy updates and reminders

-   Security tip of the month

**Communication Channels:**

-   Email announcements and updates

-   Intranet security portal and resources

-   Staff meetings and briefings

-   Poster campaigns and visual reminders

-   Interactive training sessions and workshops

#### **9.2.2 Incident-Based Learning**

**Lessons Learned:**

-   Security incident post-mortem reviews

-   Root cause analysis and prevention measures

-   Best practices identification and sharing

-   Process improvements and updates

-   Success stories and recognition programs

## **10. SECURITY MONITORING AND INCIDENT RESPONSE**

### **10.1 Security Monitoring Framework**

#### **10.1.1 Security Operations Center (SOC)**

**Monitoring Capabilities:**

-   24/7 security monitoring and alerting

-   Real-time threat detection and analysis

-   Automated incident response and containment

-   Threat intelligence integration and correlation

-   Security dashboard and reporting capabilities

**Detection Technologies:**

-   Security Information and Event Management (SIEM)

-   Endpoint Detection and Response (EDR)

-   Network Traffic Analysis (NTA)

-   User and Entity Behavior Analytics (UEBA)

-   Threat hunting and advanced analytics

#### **10.1.2 Key Security Metrics**

**Security KPIs:**

-   Mean Time to Detection (MTTD)

-   Mean Time to Response (MTTR)

-   Security incident volume and trends

-   Vulnerability management metrics

-   Security awareness training completion rates

-   Phishing simulation click rates

-   Patch management compliance rates

-   Access review completion rates

### **10.2 Incident Classification and Response**

#### **10.2.1 Incident Severity Levels**

**Critical (Severity 1):**

-   Active data breach or confirmed compromise

-   System outage affecting critical business operations

-   Malware infection with active data exfiltration

-   Successful insider threat or fraud

-   Regulatory notification required

**High (Severity 2):**

-   Suspected data breach or security compromise

-   System performance significantly degraded

-   Malware infection contained but not eliminated

-   Failed attempt at unauthorized access to critical systems

-   Significant policy violation

**Medium (Severity 3):**

-   Security control failure or bypass

-   Minor system performance issues

-   Suspicious activity requiring investigation

-   Minor policy violations

-   Vendor security incident affecting SAMULCO

**Low (Severity 4):**

-   Security awareness or training issues

-   Minor configuration or policy compliance issues

-   Routine security maintenance activities

-   User education opportunities

-   Documentation or process improvements needed

#### **10.2.2 Response Procedures**

**Immediate Response (0-1 hour):**

-   Incident detection and initial assessment

-   Incident commander assignment and team assembly

-   Initial containment and evidence preservation

-   Stakeholder notification according to severity

-   Documentation of initial findings

**Investigation Phase (1-24 hours):**

-   Detailed forensic analysis and evidence collection

-   Root cause determination and impact assessment

-   Additional containment and eradication measures

-   Recovery planning and implementation

-   Regulatory and legal consultation as needed

**Recovery and Lessons Learned (1-7 days):**

-   System restoration and validation

-   Monitoring for additional compromise

-   Post-incident review and lessons learned

-   Process improvements and documentation updates

-   Training and awareness updates based on findings

## **11. COMPLIANCE AND AUDIT**

### **11.1 Security Compliance Framework**

#### **11.1.1 Regulatory Requirements**

**Data Privacy Compliance:**

-   Data Privacy Act of 2012 (RA 10173) requirements

-   National Privacy Commission regulations and guidelines

-   Cross-border data transfer restrictions and safeguards

-   Individual privacy rights and request processing

-   Privacy impact assessments and documentation

**Financial Services Regulations:**

-   Bangko Sentral ng Pilipinas (BSP) cybersecurity guidelines

-   Anti-Money Laundering Act (AMLA) requirements

-   Consumer protection and data security requirements

-   Financial reporting and audit trail requirements

-   Business continuity and disaster recovery mandates

#### **11.1.2 Industry Standards**

**ISO 27001/27002:**

-   Information security management system implementation

-   Security control selection and implementation

-   Risk assessment and treatment procedures

-   Management review and continuous improvement

-   Certification and compliance validation

**PCI DSS (if applicable):**

-   Payment card data protection requirements

-   Network security and access control measures

-   Vulnerability management and testing procedures

-   Security monitoring and incident response

-   Regular compliance assessments and validations

### **11.2 Internal Audit and Assessment**

#### **11.2.1 Security Audit Program**

**Internal Security Audits:**

-   Quarterly technical security assessments

-   Annual comprehensive security program review

-   Policy compliance audits and testing

-   Vulnerability assessments and penetration testing

-   Third-party security assessments

**Audit Methodology:**

-   Risk-based audit planning and scoping

-   Standardized audit procedures and checklists

-   Evidence collection and analysis

-   Finding classification and prioritization

-   Management response and remediation tracking

#### **11.2.2 Continuous Monitoring**

**Automated Monitoring:**

-   Security control effectiveness monitoring

-   Compliance dashboard and reporting

-   Real-time security posture assessment

-   Trend analysis and predictive analytics

-   Exception reporting and alerting

**Manual Assessments:**

-   Periodic security walk-throughs and inspections

-   Security awareness and culture assessments

-   Vendor security assessments and reviews

-   Business process security evaluations

-   Emergency response procedure testing

## **12. EFFECTIVE DATE**

This policy becomes effective ten (10) days after approval by the Board
of Directors and supersedes all previous information security policies.

**Document Control:**

-   **Version:** 1.0

-   **Classification:** Internal Use

-   **Distribution:** All SAMULCO Personnel

-   **Review Cycle:** Annual

-   **Next Review Date:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Approval:**

Board Chairman\
Date: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Chief Executive Officer\
Date: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Chief ICT Officer\
Date: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
