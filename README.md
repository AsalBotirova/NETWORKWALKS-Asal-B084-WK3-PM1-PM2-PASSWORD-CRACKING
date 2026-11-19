# Networkwalks Cybersecurity Internship — Week 3

**Modules:** W3-PM1 and W3-PM2  
**Topics:** Password Cracking with John the Ripper and Networkwalks Browser Tools  
**Environment:** Kali Linux ARM (UTM) and web browser

## Overview

This repository documents my Week 3 practical work for the Networkwalks Cybersecurity & Ethical Hacking Internship.

The work focused on understanding password-protected PDF files and learning how password-recovery tools test candidate passwords in an authorized educational lab.

## W3-PM1 — John the Ripper (JTR) and Johnny

### Objective

To extract password-verification data from the provided locked PDF and use John the Ripper with the instructor-provided wordlist.

### Tools used

- John the Ripper
- `pdf2john.pl`
- Johnny (John the Ripper GUI)
- Kali Linux

### Activities performed

1. Prepared the provided PDF in my Kali working directory.
2. Used `pdf2john.pl` to extract the PDF password data into a format supported by John the Ripper.
3. Saved the extracted data to a text file.
4. Used the instructor-provided wordlist with John the Ripper.
5. Verified the recovered result using John's show command.
6. Opened the original PDF to confirm that the password worked.
7. Repeated the process using the Johnny graphical interface.

### Evidence

#### 1. PDF Hash Extraction
![Hash Extraction](evidence/W3-PM1-John-the-Ripper/01-pdf-hash-extraction.png)

#### 2. Password Recovery Using John the Ripper
![Password Recovery](evidence/W3-PM1-John-the-Ripper/02-john-password-recovery.png)

#### 3. PDF Successfully Unlocked
![Unlocked PDF](evidence/W3-PM1-John-the-Ripper/03-pdf-unlocked.png)

#### 4. Password Recovery Using Johnny
![Johnny GUI](evidence/W3-PM1-John-the-Ripper/04-johnny-password-recovery.png)

## W3-PM2 — Networkwalks Browser Tools

### Objective

To use the Networkwalks browser-based tools to process the provided locked PDF and recover its password using the tool's built-in password list.

### Activities performed

1. Opened the provided PM2 PDF.
2. Used the Networkwalks Hash Calculator to generate the PDF password data required by the exercise.
3. Submitted the generated data to the Networkwalks Password Cracker.
4. Obtained the recovered password.
5. Verified it by opening the original PDF.

### Evidence

#### 1. Hash Extraction
![Hash Extraction](evidence/W3-PM2-Networkwalks-Tools/01-pm2-hash-extraction.png)

#### 2. Password Cracker Result
![Password Cracker](evidence/W3-PM2-Networkwalks-Tools/02-pm2-password-cracked.png)

#### 3. PDF Successfully Unlocked
![Unlocked PDF](evidence/W3-PM2-Networkwalks-Tools/03-pm2-pdf-unlocked.png)


## Learning Outcomes

Through these exercises, I learned:

- How password-protected PDF files use encryption.
- The purpose of extracting PDF password-verification data.
- How dictionary-based password testing works.
- How to use John the Ripper from the command line.
- How Johnny provides a graphical interface for John the Ripper.
- How browser-based password-recovery tools can be used in an educational lab.
- Why extracted password data and ordinary file checksums are not the same thing.

## Scope and Disclaimer

All practical activities documented here were performed on files provided for the internship exercises and within the educational lab scope.

This repository is for educational purposes only. No third-party accounts, systems, or networks were targeted.

## Evidence

Screenshots for W3-PM1 and W3-PM2 are organized in this repository.
