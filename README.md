# 🔐 Week 03: Password Hacking & Recovery - Cybersecurity Internship

![Internship](https://img.shields.io/badge/Internship-NETWORKWALKS-blue)
![Week](https://img.shields.io/badge/Week-03-green)
![Domain](https://img.shields.io/badge/Domain-Penetration%20Testing-red)

## 📖 Overview
This repository contains the documentation and practical work completed during **Week 03** of my Cybersecurity & Penetration Testing Internship at **NETWORKWALKS**. 

The primary focus of this week was understanding the password cracking lifecycle, hash extraction, and executing dictionary-based attacks in both Linux and Windows environments.

## 🎯 Objectives
- Understand how password hashes are extracted from protected files.
- Perform dictionary-based attacks using industry-standard wordlists.
- Utilize both open-source (John the Ripper) and proprietary (NetworkWalks) tools.
- Document professional ethical hacking activities and capture flags (CTF).

---

## 🛠️ Project Modules & Tasks

### ✨ Project Module 1 – Password Cracking with John the Ripper (Linux)
**Tasks Completed:**
- [x] Extracted PDF password hashes using the `pdf2john` script.
- [x] Performed dictionary-based attacks utilizing the famous `RockYou` wordlist.
- [x] Successfully recovered and verified the target PDF password.

**Key Learning:** Gained a deep practical understanding of how hash extraction works and the mechanics of dictionary attacks in a Kali Linux environment.

#### 📸 Module 1 - Proof of Concept (Screenshots)

*1. Extracting the hash using pdf2john:*
![Pdf2John Extraction](/Screenshots/JTR/hash_calc.png)

![John the Ripper Attack](Screenshots/JTR/hash_calc1.png)

*2. Successfully cracked password:*
![Password Found](Screenshots/JTR/congrat_Jtr.png)

---

### ✨ Project Module 2 – Password Recovery with NetworkWalks Tools (Windows)
**Tasks Completed:**
- [x] Extracted PDF hashes using the NetworkWalks Hash Calculator.
- [x] Used the NetworkWalks Password Cracker and JTR Johnny to perform password recovery.
- [x] Accessed confidential data and successfully captured the flags (CTF).
- [x] Documented the entire ethical hacking process professionally.

**Key Learning:** Learned how to set up and deploy proprietary security tools in a Windows environment, execute password recovery, and emphasize the importance of a security mindset.

#### 📸 Module 2 - Proof of Concept (Screenshots)

*1. NetworkWalks Password Cracker in action:*
![NW Password Cracker](Screenshots/NW/NW_tools.png)

*2. Successfully cracked password:*
![NW Password Cracker](Screenshots/NW/congrat_NW.png)

---

## 🧰 Tools Used
* **Operating Systems:** Kali Linux, Windows
* **Password Cracking:** John the Ripper (JTR), JTR Johnny
* **Utilities:** `pdf2john`, NetworkWalks Hash Calculator, NetworkWalks Password Cracker
* **Wordlists:** RockYou

## 💡 Key Skills Developed
* Password Hacking & Hash Extraction
* Dictionary Attacks
* NetworkWalks Tools Proficiency
* Capture The Flag (CTF) Methodologies
* Ethical Hacking & Penetration Testing Workflows
* Technical Work Documentation
