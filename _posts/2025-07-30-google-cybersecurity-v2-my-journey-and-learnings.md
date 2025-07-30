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

A﻿ **playbook** is a manual that defines responses to any security incident, it defines the procedures and the tools that should be used when taking an operational action. (Eg: Incident Response, Security Alert, Team Based, and Product Based)

Incident Response Playbook Phases:

1. Preparation - Policies, staffing plans, outlines roles and responsibilities and educating users.
2. Detection and Analysis - Detect and analyze events.
3. Containment - Prevent further damage and reduce impact.
4. Eradication And Recovery/IT Restoration
5. Post Incident Activity - Documenting and reporting to organizational leadership and applying lessons learned.
6. Coordination - Reporting and sharing throughout the response process.

\#﻿### Operating Systems and Linux 

My personal highlight for the course was the sheer amount of hands-on labs that the course offered, hosted on the google cloud I was given access to Linux and Windows systems for various tasks ranging from usage of SIEMs, Wireshark, CLI to Python for automation.

O﻿ne of the many things taught in the Operating Systems course were the boot process fundamentals:

When a computer is powered on, the process begins with the BIOS or UEFI chip/firmware. This firmware is responsible for initializing all system hardware and conducting the Power-On Self Test (POST) to ensure everything is operating correctly. Once POST is complete, BIOS/UEFI searches for a bootable device, scans its first sector, and loads the bootloader into memory. The bootloader’s role is to find and load the operating system kernel, after which control is handed over to the OS itself. This sequence forms the critical bridge between hardware initialization and the operating system taking control, ensuring a reliable and secure boot process for every computing session.

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

#﻿### Threat Modelling, Vulnerability Management and Assessment