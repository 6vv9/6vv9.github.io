---
layout: post
author: athil
title: Google Cybersecurity V2 - My Journey and Learnings
date: 2025-07-30T18:20:14.111Z
thumbnail: /assets/img/posts/gcs.png
category:
  - certifications
summary: My journey through and personal notes on the Google Cybersecurity V2
  Certificate
keywords: Google Cybersecurity V2 Certificate, cybersecurity certification,
  Google cybersecurity course, personal notes cybersecurity, cybersecurity
  journey, cybersecurity training, cybersecurity exam tips, cybersecurity
  skills, online cybersecurity certificate, Google certificate review,
  cybersecurity career, cybersecurity concepts, cybersecurity tools, Wireshark
  cybersecurity, Splunk cybersecurity, penetration testing basics, cybersecurity
  best practices, zero-day exploits, cybersecurity study guide, CISSP
  preparation
permalink: blog/google-cybersecurity
---
![](/assets/img/posts/certificate_landing_page~41z8rkk5s3me.jpeg "Google Cybersecurity Certificate")

This post represents lot of firsts for me, my first personal portfolio and blog website, my first post on said blog website and my first real cybersecurity certification. As the keen eyed of you may have already noticed, I passed the certificate a week ago but withheld announcing it for I wanted to make this website along with it...when it rains it pours amiright?

Why? Mainly because I wanted to give readers more than just an announcement of this achievement, by way of sharing my personal notes that I took during the course even if it were to benefit just one person or be the push that convinces them into taking the certificate, I'd say it was well worth the effort. 

![](/assets/img/posts/screenshot-2025-07-31-001308.png "Notion Notes")

I﻿ didn't think every module in every course of the certification was worth taking notes on so I've only jotted down the things I believe would be useful, interesting or worth knowing to the readers. Let's go through it together, shall we?

#### C﻿ISSP Domains

The CISSP Domains represent the core of the cybersecurity industry, each of the seven domains representing their own vast array of roles.

1. **Security and Risk Management:** Establishing goals, ensuring compliance, mitigating risks, and planning for business continuity.
2. **Asset Security:** Protecting digital and physical assets by managing data storage, retention, disposal, and controlling access.
3. **Security Architecture and Engineering:** Designing and maintaining effective security systems and tools to safeguard data.
4. **Communications and Network Security:** Securing and managing physical and network infrastructures.
5. **Identity and Access Management:** Controlling access through identification, authentication, authorization, and accountability, following the principle of least privilege.
6. **Security Assessment and Testing:** Conducting audits and vulnerability assessments to identify risks and improve security controls.
7. **Security Operations:** Investigating incidents and implementing preventive measures to respond to breaches effectively.
8. **Software Development Security:** Applying secure coding standards and rigorous testing, including design reviews and penetration testing, to ensure application security.

#### Threats, Risks and Vulnerabilities

A **Threat** is anything or anyone or essentially any circumstance that can negatively impact your assets.

A **Vulnerability** is something that a threat could use to carry out harm on an asset. Notably, a vulnerability is different from an exposure.

> **Vulnerability:** A vulnerability is a **weakness or flaw in software, hardware, or processes** that can be exploited by attackers to gain unauthorized access, disrupt operations, or steal sensitive information. These weaknesses can arise from coding errors, misconfigurations, or lapses in security practices.
>
> **Exposure:** An exposure is a **condition or state that increases the likelihood that a system will be targeted or affected by an attack**, but does **not directly allow for exploitation** without a related vulnerability. Exposures make systems more visible or accessible to potential attackers, raising overall risk in the absence of immediate vulnerabilities.

When there is hence a presence of a vulnerability and a risk in conjunction, we can therefore say that there is a **Risk** present to the CIA triad of our asset. 

> (Risk = Likelihood * Impact)

#### NIST Risk Management and Cybersecurity Framework

Something I really enjoyed about the Google Cybersecurity Certificate was the delving into different frameworks, I've felt like this is something that is unfortunately glossed over when talking about cybersecurity to newcomers. It isn't all hunched over in a dark room staring at a CLI things. Frameworks, Standards, Policies and Procedures are a major part of the various cybersecurity domains, and while I have previous knowledge in them, I appreciate that this certification gives newcomers an opportunity to touch upon this crucial topic. Making it valuable not only from a red/blue team perspective but also from the GRC side of the industry.

Essentially, Frameworks are guidelines that are used to secure an organizations physical and digial assets to mitigate threats and risks. They consist of different steps, controls, mitigations and provide a base for organizations to build their security posture on.

For instance, one of the frameworks touched upon in the course is the **NIST RMF**, the core steps of which are as follows:

* **Prepare**: Necessary activities to be done before a threat occurs.
* **Categorize**: Develop risk management processes for different types of threats.
* **Select**: choose, customize and document safeguards (controls) that need to be implemented.
* **Implement**: Implementing the plans for risk mitigation/making better changes where needed.
* **Assess**: Determine if established controls are working properly and efficiently and meeting organizational needs.
* **Authorize**: Increases accountability by assigning 1 person to authorize security implementations in an organization, can include POA&Ms.
  <small>POA&M: Plans of Action & Milestones that are created when a security audit reveals risks within an organization's security </small>
* **Monitor**: Be aware of how systems are operating, RMM & SIEM used here, SOC Analysts work here, maintaining a low level of risk by how current systems are working.

S﻿imiliarly, the NIST CSF was also brought up, the steps for which are:

* **Govern:** Establishing cybersecurity policies, risk management strategies, compliance requirements, and organizational roles to ensure effective security leadership and accountability.
* **Identify:** Developing an understanding of organizational assets, risks, and vulnerabilities to manage cybersecurity risks effectively.
* **Protect:** Implementing safeguards such as access control, data security, awareness training, and maintenance to limit or contain cybersecurity events.
* **Detect:** Establishing continuous monitoring and detection processes to identify cybersecurity incidents promptly.
* **Respond:** Planning and executing actions to contain, mitigate, and communicate about cybersecurity incidents during and after detection.
* **Recover:** Developing and implementing plans for timely restoration of services and processes after a cybersecurity event to maintain resilience.

CSF Components:

1. Core: Identifies 5 broad functions (Identify, Protect, Detect, Respond, Recover)
2. Tiers: Measure performance across each of the levels (Level 1(LOW) - Level 4(HIGH))
3. Profiles: Current state of security plan

\#﻿### Security Audits and Controls

A﻿ security audit is a review of an organizations security policies, procedure and systems in place against a set of expectations. They begin with a set of scopes and goals. 

I﻿f the audit reveals holes in the organizations security standing that prevent it from reaching the goals of the audit, additional controls may be implemented. Controls are safeguards that are put in place to reduce specific risks.

C﻿ontrols are divided into mainly 3 categories:     

* **Administrative/Managerial controls** - Human component, mainly policies that may be enforced through technical and physical measures.
* **Technical controls** - Firewalls, IDS, IPS, Anti-Viruses, SIEM.
* **Physical/Operational Controls** - Security Cameras, Fingerprint readers, biometric verification, fences and security personnel.

Control types include, but are not limited to:

1. Preventative
2. Corrective
3. Detective
4. Deterrent

Through the certification, I had the opportunity to conduct my own security audit on a company.

#### OWASP Secure Design Principles

The Open Worldwide Application Security Project, commonly known as OWASP was created to protect the websites that you and I visit everyday by helping secure them through best practices and exposing vulnerabilities so that they may be fixed in an appropriate fashion. Because as we all know, security through obscurity has never been a feasible solution.

A﻿s part of this, there are a few OWASP Secure Design Principles that need to be kept in mind anytime we develop an application. A few are as follows: 

* **Secure Defaults** – Systems should be secure out of the box.
* **Fail Securely** – On error, default to a secure state (deny access, not allow).
* **Least Privilege** – Grant only the minimum access needed.
* **Defense in Depth** – Use multiple layers of security controls.
* **Separation of Duties** – Split roles and responsibilities to reduce risk.
* **Avoid Security by Obscurity** – Don’t rely on hiding information for security.
* **Keep Security Simple** – Simpler designs are less prone to errors.
* **Fix Issues Correctly** – Address root causes, not just symptoms.
* **Compartmentalize** – Isolate components to limit impact of a breach.
* **Least Common Mechanism** – Reduce shared components across users or services.

\#﻿### Playbooks and Phases of Incident Response

A﻿ **playbook** is a manual that defines responses to any security incident, it defines the procedures and the tools that should be used when taking an operational action. (Eg: Incident Response, Security Alert, Team Based, and Product Based).There are broadly 3 types of playbooks: Non-Automated, Automated, Semi-Automated    

Incident Response Plans Contain: Procedures for Incident Response based on type, System Information, Additional Information like contact information and documentation.

Incident Response Playbook Phases:

1. Preparation - Policies, staffing plans, outlines roles and responsibilities and educating users.
2. Detection and Analysis - Detect and analyze events.
3. Containment - Prevent further damage and reduce impact.
4. Eradication And Recovery/IT Restoration
5. Post Incident Activity - Documenting and reporting to organizational leadership and applying lessons learned.
6. Coordination - Reporting and sharing throughout the response process.

> Incident Response Lifecycle frameworks allow for organizations to develop standardized >incident response approach so that they are managed in an effective and consistent way.

NIST Incident Response Lifecycle Framework Substeps: 

1. Preparation
2. Detection and Analysis
3. Containment, Eradication and Recovery
4. Post Incident Process

I﻿t should be noted that the Incident Response Lifecycle is not linear, as in steps can be reversed or forwarded as needed.

\#﻿### Operating Systems and Linux 

My personal highlight for the course was the sheer amount of hands-on labs that the course offered, hosted on the google cloud I was given access to Linux and Windows systems for various tasks ranging from usage of SIEMs, Wireshark, CLI to Python for automation.

O﻿ne of the many things taught in the Operating Systems course were the boot process fundamentals:

When a computer is powered on, the process begins with the BIOS or UEFI chip/firmware. This firmware is responsible for initializing all system hardware and conducting the Power-On Self Test (POST) to ensure everything is operating correctly. Once POST is complete, BIOS/UEFI searches for a bootable device, scans its first sector, and loads the bootloader into memory. The bootloader’s role is to find and load the operating system kernel, after which control is handed over to the OS itself. This sequence forms the critical bridge between hardware initialization and the operating system taking control, ensuring a reliable and secure boot process for every computing session.

H﻿ypervisors and virtual machines were also a crucial part of this topic.

* **Type 1 Hypervisor:**\
  Runs directly on the hardware of the host (also called “bare-metal hypervisor”) and manages virtual machines natively—offers high efficiency and isolation.
* **Type 2 Hypervisor:**\
  Runs atop the host operating system (like a typical application), then manages virtual machines—easier for desktop/laptop environments, but with some overhead.

A﻿long with this, I dwelved into the Linux architecture made up of: 

1. User
2. Application
3. Shell
4. Filesystem Hierarchy Standard (FHS)
5. Kernel
6. Hardware

Types of Authorizations and Permissions in Linux:

1. Read
2. Write
3. Execute

Types of Owners:

1. User
2. Group
3. Other

Denoted using 10 character strings like “drwxrwxrwx”

S﻿ome of the Linux CLI commands that I had the opportunity to get hands-on with were:
<﻿blockquote>
grep: Find string with specified substring

piping ( | ): Use output of previous command as input 

ls (-l) (-a): list contents of directory

pwd: print working directory

cat: content at

tail: last 10 lines

head: first 10 lines 

echo: print something 

find (directory) (-name/-iname) (-mtime)

mkdir: creates new directory

rmdir: removes directory

touch: new file

rm: deletes files

mv: moves to new location

cp: copies to new location

nano: basically cli notepad

chmod(g+w),(o-r): changes permissions

sudo: normal users can execute superuser commands

useradd: add users to groups

userdel: delete users from groups

usermod: modify user permissions (-g to add to primary groups, -G to add to supplementary groups)

chown: change ownership of a file (: to designate as group)
<﻿/blockquote>

\#﻿### Public Key Infrastructure (PKI)

T﻿his was a topic I really enjoyed as it was something that is much deeper than what the course brushes over, heres my understanding of PKI from personal research:

* **Subject (e.g., Website) Prepares:** The website (or any entity needing a certificate) first generates its own **public key** and **private key** pair. It keeps its private key secret and secure.
* **Certificate Signing Request (CSR) to CA:**

  * The website creates a **Certificate Signing Request (CSR)**.
  * This CSR contains:

    * Information about the website (domain name, organization, etc.).
    * **The website's public key.** (This is the public key that will eventually be used to encrypt data sent *to* the website).
  * This CSR is then sent to a **Certificate Authority (CA)**.
* **CA's Verification and Signing Process:**

  * The **CA** receives the CSR.
  * The **CA verifies the identity** of the website (e.g., confirms domain ownership, organization details).
  * If verification is successful, the CA constructs the digital certificate using the information from the CSR and other details.
  * The CA then takes a cryptographic **hash** (fingerprint) of this entire certificate content.
  * The CA encrypts *this hash* using its **own private key**. This encrypted hash is the **digital signature**.
  * The CA attaches this digital signature to the certificate.
  * The CA sends the completed digital certificate back to the website.
* **Website Installs Certificate:** The website installs the newly issued digital certificate on its server.
* **User Verification (When Someone Needs to Verify It):**

  * When a user (e.g., your browser) connects to the website, the website sends its **digital certificate** to the user.
  * The user's browser (or system) performs these steps to verify the certificate:

    * It extracts the digital signature from the certificate.
    * It uses the **CA's public key** (which is already trusted in the browser's certificate store) to **decrypt** the digital signature. This reveals the hash value that the CA originally created.
    * Simultaneously, the user's browser calculates its *own* hash of the entire certificate content (excluding the signature).
    * The browser compares the hash it *decrypted from the signature* with the hash it *just calculated*.
    * **If the hashes match**, the certificate is considered legitimate (authentic and untampered).
* **Secure Communication (Using the Website's Public Key):**

  * **Once the certificate is verified as legitimate,** the user's browser extracts the **website's public key** *from within the now-trusted certificate*.
  * The user's browser then uses **the website's public key** to encrypt data (like your credit card details) that it sends to the website.
  * Only the website, with its corresponding **private key**, can decrypt this data.

\#﻿### Threat Modelling, Vulnerability Management and Assessment

T﻿hreat modelling is the process of identifying potential threats to your assets and vulnerabilities that they can exploit, it involves :

1. Scope
2. Identify Threats (Attack Tree)
3. Characterize the environment 
4. Analyze Threats (Identify Gaps and Existing Protection, Assign Risk score)
5. Mitigate Risks (Avoid Risk, Transfer Risk, Reduce Risk, Accept Risk)
6. Evaluate Findings

A commonly used framework for threat modelling is PASTA, Process for Attack Simulation And Threat Analysis.

The stages of it are:

1. Define business and security objectives
2. Define the technical scope
3. Decompose the application
4. Threat Analysis
5. Vulnerability Analysis
6. Attack Modelling (Attack Tree)
7. Analyze Risk and Impact
   Vulnerability Management Steps
8. **Identify Vulnerabilities:** Detect and catalog vulnerabilities across systems and applications.
9. **Consider Potential Exploits:** Analyze how vulnerabilities could be exploited by attackers and the impact of such exploits.
10. **Prepare Defenses:** Develop and implement security controls and mitigations to protect against identified vulnerabilities.
11. **Evaluate the Defenses:** Continuously monitor and test the effectiveness of defenses to ensure vulnerabilities remain managed

Vulnerability Assessment Steps

1. **Identification:** Discover and document vulnerabilities through scanning, enumeration, and information gathering.
2. **Testing:** Perform penetration tests, exploit simulations, or vulnerability scanning to confirm exposure and severity.
3. **Risk Assessment:** Analyze the potential impact and likelihood of vulnerabilities to prioritize remediation efforts.
4. **Remediation:** Apply patches, configuration changes, or other fixes to eliminate or reduce vulnerabilities.

\#﻿### CSIRTs - Computer Security Incident Response Teams

According to NIST, an incident is **"an occurrence that actually or imminently jeopardizes, without lawful authority, the confidentiality, integrity, or availability of information or an information system; or constitutes a violation or imminent threat of violation of law, security policies, security procedures, or acceptable use policies."**

> All security incidents are events but not all events are security incidents (An event is an observable occurrence on a network, system, or device. \[Logs are records of events that occur within an organizations systems])

The Five W's of an incident:

1. Who triggered the incident?
2. What happened?
3. When the incident took place?
4. Where the incident took place?
5. Why the incident occurred?

S﻿ecurity incidents in an organization are handled by a designated team known as the CSIRT.

Roles in a CSIRT Include:

1. Security Analyst: Detect security incidents and determine if they need action based on the severity, some can be remediated and don't need escalation
2. Technical Lead/Ops Lead: When alerts require escalation they are handled by technical leads who guide through the lifecycle.
3. Incident Coordinator: Tracks and manages the CSIRT and cross coordination with other teams in the organization.

\#﻿### Networking and Network Analysis

Components of a Packet:

1. Header - Contains Protocol, Port, Source, Destination
2. Payload - Data
3. Footer - End of Packet

Packet Capture (P-Cap) - A file that contains data packets that have been intercepted from an interface or a network.

![](/assets/img/posts/image.png)

**Transmission Control Protocol (TCP):**\
A core internet protocol ensuring reliable, ordered, and error-checked delivery of data between two devices by establishing a connection before streaming data.

**Internet Protocol (IP):**\
The foundational protocol suite governing the addressing and routing of data packets across networked devices, ensuring data reaches its correct destination.

**Wired Equivalent Privacy (WEP):**\
The original Wi-Fi security standard developed in 1999 to offer wireless privacy level comparable to wired networks. WEP has known vulnerabilities and is considered obsolete.

**Wi-Fi Protected Access (WPA) Standards:**

* **WPA:** Introduced as WEP’s successor, uses TKIP (Temporal Key Integrity Protocol) but is vulnerable to the KRACK attack.
* **WPA2:** Employs AES encryption for stronger security, yet still susceptible to KRACK.
* **WPA3:** Addresses KRACK vulnerabilities, leverages SAE (Simultaneous Authentication of Equals), and enforces more robust encryption (128-bit standard; 192-bit in Enterprise mode).

**Virtual Private Networks (VPNs):**\
VPNs secure data by encrypting and decrypting it locally and encapsulating it before transmission to VPN servers, protecting privacy and integrity. Common protocols: WireGuard, IPSec.

**Firewall Types:**

* **Stateless Firewalls:** Filter packets solely based on set rules; do not keep track of ongoing connections.
* **Stateful Firewalls:** Analyze the context of traffic (behavioral analysis), maintaining session information.
* **Next-Generation Firewalls (NGFW):** Add cloud-based threat intelligence and application-level inspection to traditional stateful capabilities.

**Network Security Zones:**

* **DMZ (Demilitarized Zone):** Hosts public-facing services (e.g., web, DNS servers); isolated from internal networks for added protection.
* **Internal Network:** Strictly for internal organizational use.
* **Restricted Zone:** Subset of the internal network with access limited to specific groups.

**Classless Inter-Domain Routing (CIDR):**
Notation using a slash (‘/’) to specify the number of bits for the network portion of an IP address (e.g., 192.168.1.0/24), improving routing efficiency and flexibility.

**Proxy Servers and NAT:**

* **Forward Proxy:** Alters outgoing requests’ source IP, masking users’ identities on external requests.
* **Reverse Proxy:** Shields internal servers’ IP addresses from external users, often used for load balancing and protecting backend services.
* **Email Proxy:** Intercepts and filters email for spam and malicious content.

\#﻿### Tools and Techniques

A﻿lthough this certificate is aimed towards T1 SoC Analysts, it did bring up important red/blue team tools and techniques that are paramount to the industry, including different types of XSS (Reflected, Stored, DOM), Intrusion Detection and Prevention Systems, End-point detection and response systems, Security Information and Event Management Systems, NIDS, RMM, HIDS, Threat hunting and Cyber deception.

> Threat hunting is the proactive search for threats on a network. Security professionals use threat hunting to uncover malicious activity that was not identified by detection tools and as a way to do further analysis on detections. (Eg: Fileless malware on memory which can't be detected by detection systems; Threat hunters perform research on emerging threats and attacks and then determine the probability of an organization being vulnerable to a particular attack.)
>
> ﻿Cyber deception involves techniques that deliberately deceive malicious actors with the goal of increasing detection and improving defensive strategies.

**Honeypots** are an example of an active cyber defense mechanism that uses deception technology. Honeypots are systems or resources that are created as decoys vulnerable to attacks with the purpose of attracting potential intruders. For example, having a fake file labeled *Client* *Credit Card Information - 2022* can be used to capture the activity of malicious actors by tricking them into accessing the file because it appears to be legitimate. Once a malicious actor tries to access this file, security teams are alerted.

P﻿robably one of my favorite parts of the course was the introduction of the **IoC Pyramid of Pain**, that visually represented how difficult it would be for attackers to perform when these IoCs are blocked by defenders.

![](/assets/img/posts/image-1-.png)

V﻿arious network intrusion terms and techniques were also taught on:

Denial-of-Service (DoS) vs. Distributed Denial-of-Service (DDoS)

* **DoS (Denial-of-Service):**\
  A single device targets a server or service with overwhelming requests to disrupt its normal functioning.
* **DDoS (Distributed Denial-of-Service):**\
  Multiple devices or servers (often a botnet) coordinate to flood the target, making defense and mitigation harder.

Types of DoS Attacks

* **SYN Attack:**\
  Exploits the first step of TCP handshake (SYN) by sending numerous SYN requests, overwhelming the server’s connection queue.
* **ICMP Flood Attack:**\
  Bombards the server with ICMP echo requests (“are you there?” messages), consuming resources and slowing the system.
* **Ping of Death:**\
  Sends oversized ICMP packets (>64KB), causing buffer overflows and potential crashes on vulnerable systems.

Packet Sniffing

* **Passive Packet Sniffing:**\
  Intercepts and reads data traveling across the network without altering it; used for eavesdropping.
* **Active Packet Sniffing:**\
  Intercepts, then manipulates or injects data in transit, potentially altering communication or injecting malicious payloads.

IP Spoofing Attacks

* **On-Path Attack (Man-in-the-Middle):**\
  The attacker places themselves between the sender and receiver, intercepting and possibly impersonating either party.
* **Replay Attack:**\
  Valid data transmissions are captured and maliciously retransmitted to trick the system or gain unauthorized access.
* **Smurf Attack:**\
  The attacker spoofs the victim’s IP address and floods a network with ICMP echo requests, amplifying the attack to overwhelm the target (combines DDoS and IP spoofing techniques).

\#﻿### Conclusion and Takeaway

T﻿his course has taught me to develop a proactive habit of continuously seeking information on emerging security threats and incidents and demonstrating this security mindset in job interviews to stand out. 

Understand the distinct roles in data protection: Data Controllers define data processing purposes; Data Processors handle data on behalf of controllers; Data Custodians manage access and implement security controls; Data Protection Officers (DPOs) monitor compliance and advise on protection standards.

Recognize key stakeholders — Risk Managers, CEO, CFO, CISO, and Operations Managers — who oversee organizational data security. When communicating security issues, clearly address what the problem is, its organizational impact, and resolution steps, using visual aids, emails, and calls for effective stakeholder engagement.

Stay informed through reputable security blogs, security organizations, and conferences.

Join cybersecurity associations to build professional networks aligned with your career goals,
 find a mentor who can guide you through the vast world of cybersecurity.

When using generative AI tools, adopt a thoughtful prompting strategy (T-C-R-E-I: Task, Context, References, Evaluate, Iterate) and tailor queries for clear, useful outputs—especially useful for interview preparation through sample questions and answer comparisons.

For career preparation, craft your resume with facts and your cover letter to express your passion for cybersecurity, reflecting personal motivations. Practice technical interviews by asking clarifying questions and structure responses using the STAR method, while rehearsing non-technical interviews to improve communication skills.

I﻿ hope this post has helped atleast a few of you decide if this certificate is for you, if not then that you got to learn a handful of new pieces of knowledge.

### R﻿emember, 
E﻿very Lock a Key; Every System a Vulnerability