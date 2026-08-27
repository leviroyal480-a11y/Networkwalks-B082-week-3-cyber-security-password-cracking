# Week 3: Password Cracking Labs

![Cybersecurity](https://img.shields.io/badge/Field-Cybersecurity-00D4FF?style=for-the-badge)
![Week 3](https://img.shields.io/badge/Internship-Week%203-00FF88?style=for-the-badge)
![Password Cracking](https://img.shields.io/badge/Topic-Password%20Cracking-111827?style=for-the-badge)
![John the Ripper](https://img.shields.io/badge/Tool-John%20the%20Ripper-00D4FF?style=for-the-badge)
![Networkwalks](https://img.shields.io/badge/Training-Networkwalks-00FF88?style=for-the-badge)

Hands-on password security and password-cracking labs completed during **Week 3** of my Cybersecurity Internship at **NETWORKWALKS**.

## Overview

This repository contains my **Week 3 Cybersecurity Internship labs** focused on:

- Password security
- Hash analysis
- Password auditing
- Dictionary attacks
 - Security tools
- Technical evidence collection

> **All activities were performed only against authorized files, systems, and laboratory environments.**

##  Student Information

| Information | Details |
|---|---|
| **Name** | Monday Royal Levi |
| **Program** | B082-Networkwalks |
| **Field** | Cybersecurity |
| **Training Organization** | NETWORKWALKS |
| **Week** | Week 3 |
| **Date** | 27th Aug 2026 |
| **Assessment** | Complete report |

## Labs Completed

### W3-PM1 — John the Ripper + Johnny GUI

#### Objective

The objective of this lab was to perform password auditing on an authorized password-protected file using **John the Ripper (JTR)** and **Johnny GUI**.

#### Tools Used

| Tool | Purpose |
|---|---|
| **John the Ripper** | Password auditing |
| **Johnny GUI** | Graphical interface for John the Ripper |
| **Hash Extractor** | Extracting the password hash |

#### Methodology

1. Downloaded and extracted John the Ripper.
2. Installed and configured Johnny GUI.
3. Configured Johnny to work with John the Ripper.
4. Extracted the hash from the authorized password-protected file.
5. Saved the extracted hash.
6. Loaded the hash into Johnny.
7. Performed password audit.
8. Recorded the result.

## W3-PM1 Result Evidence

### 01 — Hash conversion
<img width="1365" height="765" alt="Screenshot 2026-08-26 001611" src="https://github.com/user-attachments/assets/c3c2e642-6c96-46ef-96a8-704cdfc43c83" />

### 02 — Hash Extracted
<img width="1013" height="510" alt="Screenshot 2026-08-27 214531" src="https://github.com/user-attachments/assets/5e28dbfc-5512-4f1e-a22f-2c90e1dad589" />

### 03 — Hash Loaded
<img width="1363" height="767" alt="Screenshot 2026-08-26 002927" src="https://github.com/user-attachments/assets/2b12a71b-efbf-4296-b696-e7a56943c9b2" />

### 04 — Password Audit Result
<img width="1365" height="767" alt="Screenshot 2026-08-26 003417" src="https://github.com/user-attachments/assets/45dcd88d-7016-4327-9ad0-403f876de95f" />

### 05 — File After Authorized Password Entry
<img width="1365" height="767" alt="Screenshot 2026-08-26 003530" src="https://github.com/user-attachments/assets/f8f07f94-300c-4aad-b89a-f0b15168621e" />

# W3-PM2 — Networkwalks Security Tools

## Objective

The objective of this lab was to use **Networkwalks-provided security tools** to perform password auditing on an authorized password-protected file.

## Tools Used

| Tool | Purpose |
|---|---|
| **Networkwalks Hash Calculator** | Hash generation/extraction |
| **Networkwalks Password Cracker** | Password security testing |

## Methodology

1. Uploaded the authorized file to the Networkwalks Hash Calculator.
2. Generate the required hash.
3. Copied the generated hash.
4. Loaded the hash into the password-testing tool.
5. Performed the available password audit with dictionary.
6. Recorded the result.

## W3-PM2 Evidence

### 01 — Hash Generated
<img width="1365" height="767" alt="Screenshot 2026-08-26 010100" src="https://github.com/user-attachments/assets/52bbc7b3-51b0-48cd-830e-9a7f08c37df9" />

### 02 — Password Audit Result
<img width="717" height="767" alt="Screenshot 2026-08-27 185508" src="https://github.com/user-attachments/assets/7744e3c7-fc27-4381-9e0d-d3adc7e229bd" />

### 03 — File After Authorized Password Entry
<img width="1365" height="759" alt="Screenshot 2026-08-27 185811" src="https://github.com/user-attachments/assets/5830fa4f-a97e-42fa-b3cb-ad408848da35" />


## Key Learnings

### Hashing vs Encryption

**Hashing** is generally a one-way transformation used to represent data as a fixed-length value.

**Encryption** is a reversible process in which information is transformed into an unreadable form and can later be recovered using an appropriate key.

Understanding the difference between hashing and encryption is important when studying password storage, authentication, and cybersecurity.

---

### Dictionary Attacks

A **dictionary attack** is a password-auditing technique that tests passwords from a predefined wordlist.

The lab demonstrated how weak, common, or predictable passwords can be vulnerable to dictionary-based password attacks.

---

### Password Security

The practical exercises demonstrated the importance of using strong and unique passwords.

Weak passwords can make accounts and protected files more vulnerable to unauthorized access.

---

### Hands-on Experience

During the labs, I gained practical experience with:

- Extracting password hashes
- Loading hashes into password-auditing tools
- Using John the Ripper
- Using Johnny GUI
- Working with wordlists
- Performing dictionary-based password audits
- Documenting technical evidence
- Analyzing password security

---

## Password Security Lessons

Strong password security practices include:

- Use long and unique passwords
- Avoid commonly used passwords
- Avoid predictable patterns
- Do not reuse passwords across multiple accounts
- Use a password manager where appropriate
- Enable multi-factor authentication (MFA)
- Use strong password policies
- Implement account lockout and rate-limiting protections where appropriate

---

## Real-World Relevance

Password-auditing techniques are useful during **authorized cybersecurity assessments** for:

- Evaluating password policies
- Identifying weak authentication practices
- Security awareness and education
- Testing password-protection mechanisms
- Understanding common password attack techniques
- Assessing the effectiveness of security controls

The purpose of ethical password auditing is to identify weaknesses so that they can be corrected before they are exploited by malicious actors.

---

## Tools & Resources

| Tool | Purpose | Resource |
|---|---|---|
| **John the Ripper** | Password auditing and security testing | [Openwall](https://www.openwall.com/john/) |
| **Johnny GUI** | Graphical interface for John the Ripper | [Johnny](https://openwall.info/wiki/john/johnny) |
| **NETWORKWALKS** | Cybersecurity training and practical labs | [Networkwalks](https://networkwalks.com/) |

---

## Skills Practiced

![Linux](https://img.shields.io/badge/Linux-Command%20Line-black?style=flat-square&logo=linux)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Password%20Auditing-00D4FF?style=flat-square)
![JTR](https://img.shields.io/badge/JTR-Password%20Auditing-00FF88?style=flat-square)
![Networking](https://img.shields.io/badge/Networking-Security-00D4FF?style=flat-square)

- Password security
- Hash analysis
- John the Ripper
- Johnny GUI
- Dictionary attacks
- Security tools
- Technical documentation
- Technical evidence collection
- Security testing
- Linux command-line usage

---


**LinkedIn post:** 

---

## Acknowledgments

Special thanks to:

**Waqas Karim (CCIE)**  
Instructor & Mentor

**NETWORKWALKS**  
For providing hands-on cybersecurity training, practical laboratory exercises, and security-focused learning opportunities.

---

##  Disclaimer

This repository was created strictly for **educational and authorized cybersecurity training purposes**.

All password-auditing techniques demonstrated in this repository were performed against authorized files and systems within a controlled training environment.

Unauthorized access, password cracking, or security testing against systems without permission may be illegal and unethical.

---

# Week 3 Complete!

**Learn. Test. Secure. Repeat.**

> 🔐 **Understand the weakness. Fix the weakness. Secure the system.**
