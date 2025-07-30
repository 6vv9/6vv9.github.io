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

Why? Mainly because I wanted to give readers more than just an announcement of this achievement, by way of sharing my personal notes that I took during the course even if it were to benefit just one person, I'd say it was well worth the effort. 

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

A **Vulnerability** is something that a threat could use to carry out harm on an asset.

When there is hence a presence of a vulnerability and a risk in conjunction, we can therefore say that there is a **Risk** present to the CIA triad of our asset.

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