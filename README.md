# Sathvik R — sathvik-zoldyck

> *I build things to understand them. I break things to protect them.*

Security engineer, founder, and builder based in Bengaluru, India.  
My work lives at the intersection of **offensive security, systems engineering, and shipping real products**.  
If it has failure modes, attracts attackers, or solves a problem nobody built a tool for yet — I'm building it.

---

## What I've Shipped

### CipherSuite — Professional Penetration Testing Workspace
**[Live → ciphersuite.alcyonesecure.in](https://ciphersuite.alcyonesecure.in)**

The tool I wished existed when doing real security work.  
Most pentesters juggle Notion for notes, Google Drive for evidence, and Word for reports.  
CipherSuite replaces all of it.

- Findings manager with CVSS scoring, severity tracking, and status workflow  
- Evidence vault with SHA-256 hashing and bidirectional finding links  
- Split-view markdown notes editor with code block support  
- Tool import parsers for Nmap, Nessus, and Burp Suite XML  
- AI-powered report generation with PDF export  
- Log analyzer with syntax highlighting  
- Just Notes mode — color-coded, self-destruct timers, tags, offline  

`Next.js 14` `TypeScript` `Firebase` `Genkit AI` `Framer Motion` `shadcn/ui`

---

### Black Box — Device Service Audit System
**[alcyonesecure.in](https://alcyonesecure.in)**

When you hand your laptop to a repair technician, nothing records what they do.  
Black Box fixes that.

Activate Repair Mode before handing over your device.  
After servicing, get a cryptographically verified forensic report.

- Windows Service running as SYSTEM — survives UI being killed  
- Three-location logging: primary log + AES-256 shadow copy + Windows Event Log  
- SHA-256 hash chain — any modification breaks the chain, report shows COMPROMISED  
- USB monitoring via WMI — captures VendorID, ProductID, serial number, timestamps  
- File activity monitoring with smart filtering — documents, photos, archives  
- PIN protection with PBKDF2 (100,000 iterations) — key never stored  
- Tamper detection — kills, service stops, safe mode attempts all logged  
- Professional installer at 2.9MB with 4-screen onboarding wizard  
- 6/6 automated tests passing  

`C#` `.NET 8` `WPF` `Windows Service` `WMI` `AES-256` `SHA-256` `PBKDF2` `Inno Setup`

---

### Alcyone Secure — Cybersecurity Company
**[alcyonesecure.in](https://alcyonesecure.in)**

Founded to help Indian SMEs, hospitals, colleges, and hotels comply with the DPDP Act 2023.  
Not just paperwork — technical assessments, system audits, and real security controls.

This is how I see how security fails in the real world.

---

## What I'm Working On

- Expanding Black Box with ETW kernel-level file monitoring and cloud log backup  
- Building a DPDP Compliance Assessment Platform for employee security awareness testing  
- Completing HackTheBox CPTS certification  
- CompTIA Security+ — exam scheduled  

---

## Technical Background

**Security**
- Penetration testing — web, network, Active Directory  
- OSINT — pattern recognition, investigation, open source intelligence  
- Threat modeling and adversarial thinking  
- Forensic logging, tamper detection, evidence integrity  
- DPDP Act 2023 compliance and data protection  

**Systems & Engineering**
- Linux internals — filesystem, processes, networking  
- Windows Services, Named Pipes, WMI, ETW, Registry  
- Cryptography — AES-256, SHA-256 hash chains, PBKDF2  
- Full-stack: Next.js, React, TypeScript, Firebase, Node.js  
- Systems programming: C#, .NET 8, Python, C/C++, Java, Bash  

**Security Practice**
- HackTheBox — CPTS learning path completed, active labs  
- Hack The Box badges: Join the Adventure, Fuzzing is Power, Dive into Requests, Every Road Leads to Root  
- Built custom wireless network security research hardware from scratch  

---

## Certifications

| Certification | Issuer |
|---|---|
| Certificate in Data Protection Law (100%) | Asian School of Cyber Laws |
| PrivacyOps Academy Certified | Securiti AI |
| Vulnerability Management Detection & Response | Qualys |
| Cybersecurity Fundamentals | Fortinet |
| Ethical Hacker | Cisco Networking Academy |
| Introduction to Cybersecurity | Cisco Networking Academy |
| CPTS Learning Path Completed | HackTheBox |

---

## Wins

**Winner — Cybersecurity Track, Recursive V2 International Hackathon**  
Powered by CloudSEK · 2000+ applicants · 24-hour build · First hackathon ever  
Top 10 Finalists · Won the cybersecurity track · ₹10,000 prize

---

## How I Think

- Build first, understand later  
- Break assumptions on purpose  
- Document decisions, not just code  
- If I can build it, I can break it — if I can break it, I can protect it  

My degree supports my learning. It does not define it.

---

## Outside Engineering

Trained boxer · Traditional and digital artist · 2D animator  
History and geopolitics · One Piece · Cat person · Coffee

These are not side notes.  
They shape how I think about conflict, patience, and long-term systems.

---

## This GitHub

Public repos show finished work.  
Private repos show active work.  
The learning is always real, even when the repo is not.

**[LinkedIn](https://linkedin.com/in/sathvik-r-dev) · [alcyonesecure.in](https://alcyonesecure.in) · [CipherSuite](https://ciphersuite.alcyonesecure.in)**
