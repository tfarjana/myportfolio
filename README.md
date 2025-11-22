# My GitHub Resume Project
# https://tfarjana.github.io/myportfolio/index.html
# Tanvin Farjana  

## Cybersecurity & Cloud | SOC Analyst (in training) | CTF Winner  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/tanvin-f-1563a0214/)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black)](https://github.com/tfarjana)

---

##  About Me  

Hi there! I’m **Tanvin Farjana**, a cybersecurity professional with hands-on training in **threat detection, cloud security, and system hardening** through a 400+ hour technical fellowship.  

I bring a strong foundation in **Linux, Windows Server/Active Directory, networking, and AWS**, combined with a background in **customer service and operations** where I’m used to solving problems under pressure and handling sensitive information with care.  

In 2025, I earned **1st place in Bloomberg’s “Hack the Knowledge” CTF**, where my team identified web app vulnerabilities and applied secure coding practices under tight time constraints. I’m currently pursuing **CompTIA Network+** and **AWS Solutions Architect – Associate** to deepen my cloud security expertise and grow into roles such as **SOC Analyst** or **Cloud Security Engineer**.  

---

##  Technical Skills  

**SOC & Security Tools**  
- Splunk, Wireshark, Nmap, Burp Suite, Metasploit, Netcat, Cisco Packet Tracer  

**Operating Systems**  
- Windows 10/11, Windows Server 2022  
- Linux: Ubuntu, Kali  

**Networking & Security**  
- TCP/IP, DNS, DHCP, NAT, VLANs  
- Firewall configuration  
- OWASP Top 10, Secure Coding Practices  

**Incident Response & Analysis**  
- Threat hunting & log analysis  
- Packet inspection & basic forensics  
- Writing technical reports and summaries  

**Scripting, Automation & Tools**  
- Bash, Python (beginner)  
- Git & GitHub  
- Windows Terminal, VS Code, Chrome DevTools  

**Virtualization & Labs**  
- VirtualBox, multi-VM environments  
- Windows Server / Active Directory enterprise-style labs  
- Linux node clusters  

**Cybersecurity Concepts**  
- Vulnerability assessment  
- Principle of least privilege & MFA  
- Secure system and lab design  

**Web & Cloud**  
- HTML5, JavaScript  
- Serverless architectures (AWS Lambda, API Gateway)  
- AWS EC2, S3, SES, IAM  

**Soft Skills**  
- Communication, customer service, teamwork  
- Attention to detail, problem-solving, adaptability  

---

## Certifications & Training  

- **Google IT Support Certificate**  
- **IBM Cybersecurity Analyst Badge**  
- **AWS Cloud Foundations Badge**  
-  **1st Place – Bloomberg “Hack the Knowledge” CTF (2025)**  
- **Currently pursuing:**  
  - CompTIA Network+  
  - AWS Certified Solutions Architect – Associate  

---

## Featured Projects   

>  Update the GitHub links once your repos are created.

| Project | Description | Tools |
|--------|-------------|-------|
| [Umi Nur – Cloud-Native Cybersecurity for Sensitive Healthcare](https://github.com/tfarjana/REPO-UMI-NUR-CAPSTONE) | Group capstone building a privacy-first cloud platform for reproductive & mental health data. Role: cloud/security team member. | AWS VPC, AWS KMS, DynamoDB, Wazuh SIEM, Docker, Nginx + Certbot (HTTPS), Flask, Python |
| [Sentiment Analysis Web Tool](https://github.com/tfarjana/REPO-SENTIMENT-APP) | Secure full-stack journaling app that analyzes and visualizes user sentiment over time, with a hardened cloud deployment. | Python, Flask, SQLite, TextBlob, Chart.js, AWS EC2 (Ubuntu), UFW, SSH keys, Git |
| [Static Website with Serverless Contact Form](https://github.com/tfarjana/REPO-SERVERLESS-CONTACT) | Static portfolio-style site hosted on S3 with a fully serverless contact form using Lambda, SES, and API Gateway. | HTML, CSS, JavaScript, AWS S3, Lambda, SES, API Gateway, IAM |
| [Windows Server 2022 & Active Directory Lab](https://github.com/tfarjana/REPO-WIN-SERVER-AD-LAB) | Multi-server Windows domain environment with AD, DHCP, DNS, and automated user provisioning via PowerShell. | Windows Server 2022, Active Directory, DNS, DHCP, RAS, PowerShell, VirtualBox |
| [Ubuntu Multi-Node Cluster](https://github.com/tfarjana/REPO-UBUNTU-CLUSTER) | Secure 3-node Ubuntu cluster with static IPs, passwordless SSH, and firewall rules for controlled internal networking. | Ubuntu Server, Bash, SSH, UFW, VirtualBox, Netplan |

---

## Project Summaries  

###  Umi Nur – Cloud-Native Cybersecurity for Sensitive Healthcare (Capstone, Team Project)  

_Group capstone building a privacy-first cloud platform for reproductive and mental health data._  
**Role:** Cloud/Security team member  

- **Co-designed**, as part of a team, a cloud-native architecture in a private VPC using domain-segregated AWS KMS keys for women’s and behavioral health data, enforcing defense-in-depth and least-privilege access.  
- Collaborated with teammates to implement a secure consent workflow where a Flask API encrypts patient consent with AWS KMS and stores it in DynamoDB, while Wazuh SIEM monitors access and modifications for anomalies.  
- Helped run the Privacy AI Assistant (PAM) and its analysis backend in Docker containers behind HTTPS (`uminur.app`), supporting secure, audit-ready access for staff and patients.  
- Contributed to compliance dashboards and mappings that tie SIEM alerts and KMS events to HIPAA and NIST controls, producing plain-language summaries for non-technical stakeholders.  

---

### Sentiment Analysis Web Tool — Secure Web App Project  

- Developed and deployed a **secure journaling web app** using **Python, Flask, SQLite, and TextBlob** to analyze and visualize user sentiment over time.  
- Hardened an **AWS EC2 (Ubuntu)** instance with **UFW firewall rules**, **SSH key-only access**, and **least-privilege configurations**, reducing the attack surface.  
- Applied **secure coding practices** (input validation, CSRF protection, parameterized queries) and integrated **Chart.js** for real-time sentiment visualization and private data storage.  

---

### Static Website with Serverless Contact Form — AWS Cloud  

- Designed and deployed a **static website** on **Amazon S3** with a responsive **HTML/CSS/JS** frontend.  
- Built a **serverless contact form** using **AWS Lambda, SES, and API Gateway** (with CORS support), enabling real-time email delivery without traditional servers.  
- Configured **IAM roles** and automated parts of the infrastructure setup to enforce **least privilege**, verify SES identities, and streamline production-ready deployment.  

---

###  Windows Server 2022 & Active Directory Lab  

- Deployed a **multi-server Windows domain environment** with Primary/Replica Domain Controllers, configuring **DHCP, DNS, and RAS** for IP and name resolution.  
- Automated creation of **70+ Active Directory user accounts** with **PowerShell + CSV**, improving speed and consistency of provisioning.  
- Joined Windows 10 clients to the domain and applied **Group Policy Objects (GPOs)** to enforce security baselines while troubleshooting replication and scripting issues in a VirtualBox lab.  

---

###  Ubuntu Multi-Node Cluster Setup (VirtualBox)  

- Built a **secure 3-node Ubuntu server cluster** with NAT and internal networking on the **192.168.1.0/24** subnet, using **Netplan** for static IPs and hostname resolution.  
- Automated **passwordless SSH** between control and worker nodes and configured **UFW firewall rules** to restrict access to only required ports.  
- Used this lab to practice **network testing, remote administration**, and hardening techniques in a Linux environment.  

### Bloomberg Hackathon – Cybersecurity CTF (2025)  

- Secured **1st place** in Bloomberg’s 2025 cyber CTF by identifying and exploiting web application vulnerabilities, then applying **secure coding and remediation strategies**.  
- Solved real-time **HTML and web security challenges** in a fast-paced team environment, demonstrating strong debugging, problem-solving, and communication skills.  
- Applied **OWASP Top 10** principles to analyze flaws and test mitigation strategies across multiple scenarios.

---

##  Professional Experience  

### Cybersecurity Fellow – The Knowledge House (NYC)  
**Jan 2025 – Present**  

- Completed **400+ hours** of hands-on cybersecurity and cloud training focused on **AWS, networking, incident response, and secure system design**.  
- Designed and deployed **secure cloud infrastructure** using **AWS (EC2, VPC, S3)** and **Azure VMs**, implementing IAM policies, MFA, and least privilege to reduce risk.  
- Collaborated on **Agile team projects**, delivered technical presentations, and helped improve team efficiency and on-time delivery.  

### Secretary / Medical Receptionist – Flex Staff @ Northwell Health  
**Jan 2025 – Present | New York, NY**  

- Handle ~**40+ daily calls** from patients, coordinating appointments across multiple providers and locations.  
- Use tools like **Sorian, TouchWorks, and HealthPay** to verify insurance and maintain accurate, HIPAA-conscious records.  
- Perform scheduling, cancellations, and secure communications (fax/email) to support clinical workflows.  

### Course Support Assistant (Promoted to Lead) – City College of New York  
**Mar 2021 – Aug 2022 | New York, NY**  

- Assisted ~4 professors with **virtual instruction**, including recording, editing, and posting high-quality lecture content.  
- Collaborated with **7+ support assistants** to design presentations for **Open House and Graduation**.  
- Promoted to **Course Assistant Leader**, delegating tasks based on team strengths and improving overall productivity.

---

##  Education  

**Cybersecurity & Cloud Fellowship – The Knowledge House**  
*Jan 2025 – Expected Dec 2025*  
- Intensive fellowship focused on **cybersecurity and cloud computing** with labs in AWS, networking, and security.  
- Building both **technical expertise** and **professional skills** to support readiness for cloud and cybersecurity roles.  

**B.S., Chemistry (Minor in Psychology) – The City College of New York**  
*Graduated June 2024 | GPA: 3.65*  

---

**Next Steps / Roadmap**  

- Finish and publish **detailed documentation** (methodology, findings, screenshots) for each major lab.  
- Add a **SOC/Threat Detection** project (SIEM or log analysis) to the portfolio.  
- Continue building cloud-focused labs (GuardDuty, Security Hub, automated remediation).  

---

##  Highlights  

-  1st Place – Bloomberg “Hack the Knowledge” CTF (2025)  
- Completed 400+ hours of cybersecurity & cloud training  
- Built end-to-end labs in **Linux, Windows AD, and AWS**  
- Strong cross-over experience from **customer-facing roles**  

---

##  Ethical & Security Disclaimer  

This portfolio and its associated labs are for **educational and demonstration purposes only**.  
No real client data, credentials, or sensitive information are used. All environments are **sanitized, simulated, or self-contained**.  

---

## Let’s Connect  

-  **Email:** [tfarjana000@gmail.com](mailto:tfarjana000@gmail.com)  
-  **LinkedIn:** [linkedin.com/in/tanvin-f-1563a0214](https://www.linkedin.com/in/tanvin-f-1563a0214/)  
-  **GitHub:** [github.com/tfarjana](https://github.com/tfarjana)  