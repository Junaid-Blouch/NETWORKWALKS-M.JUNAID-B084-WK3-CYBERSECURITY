# NETWORKWALKS-M.JUNAID-B084-WK3-CYBERSECURITY-PROJECT

## 📋 Project Overview

This repository contains my submission for Week 3 of the Networkwalks Cybersecurity & Ethical Hacking Internship (Batch B084). It documents a password-cracking exercise performed using offline dictionary-attack techniques against password-protected PDF files provided by Networkwalks for training purposes.

All activities were performed strictly for educational purposes against files explicitly supplied by the course for this exercise. No unauthorized systems, files, or third-party data were targeted at any point.

---

## 🧰 Module Completed

| Module | Title | Tool(s) Used |
|---|---|---|
| PM1 | Password Cracking with John the Ripper (Johnny GUI) | Johnny, John the Ripper, Online HashCrack (pdf2john/pdf2hashcat converter) |

---

## 📁 Repository Structure

NETWORKWALKS-M.JUNAID-B084-WK3-CYBERSECURITY-PROJECT/
│
├── README.md
└── PM1-Password-Cracking-JohnTheRipper.docx

---

## 🔍 Module Summary

### PM1 — Password Cracking with John the Ripper (Johnny GUI)

Three password-protected PDF files (My-Locked-PDF1.pdf, My-Locked-PDF2.pdf, My-Locked-PDF3.pdf) were provided as part of the training exercise. For each file:

1. The encrypted PDF's password hash was extracted using an online pdf2john/pdf2hashcat converter.
2. Johnny (a GUI front-end for John the Ripper) was installed and configured with the correct John the Ripper executable path.
3. The extracted hash was loaded into Johnny, and a dictionary (wordlist) attack was launched.
4. John the Ripper successfully recovered the plaintext password for each file (e.g. password1, 1qaz2wsx).
5. Each recovered password was used to unlock its corresponding PDF, revealing a unique training "flag" confirming successful completion.

This exercise demonstrates how PDF encryption can be converted into a crackable hash format and attacked offline, and highlights why weak or common passwords are recovered almost instantly — reinforcing the importance of strong password policies in real-world security.

---

## ⚠️ Disclaimer

All activities in this repository were conducted strictly for educational purposes as part of a structured cybersecurity internship curriculum, using files explicitly provided by Networkwalks for this exercise. No exploitation, unauthorized access, or intrusive activity was performed against any third-party system. These techniques must never be applied to files or systems without explicit, documented permission from their owner.

---

## 📄 Full Report

See PM1-Password-Cracking-JohnTheRipper.docx for the complete step-by-step write-up with screenshots and explanations.

---

## 👤 Author

M. Junaid
Cybersecurity Internship — Batch B084, Networkwalks
