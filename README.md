# NETWORKWALKS-WK3-PASSWORD-CRACKING
Week 3 Cybersecurity Internship Project — Password Cracking with John the Ripper (JTR), Johnny, and NetworkWalks tools.


## Project Overview

This project focused on understanding password security and password recovery through two practical modules.

The exercises involved using John the Ripper (JTR) and its graphical interface, Johnny, on Windows, as well as NetworkWalks' online Hash Calculator and Password Cracker tools.

The objective was to understand how password hashes are extracted and how password-cracking tools can be used in authorized security testing to demonstrate password strength and weaknesses.

## Modules Completed

- **WK3-PM1:** Password Cracking with John the Ripper (JTR) and Johnny.
- **WK3-PM2:** Password Cracking with NetworkWalks Tools.

## Tools Used

| Tool | Purpose |
|---|---|
| John the Ripper (JTR) | Password security testing and password recovery |
| Johnny | Graphical interface for John the Ripper |
| NetworkWalks Hash Calculator | Extracting password hashes from protected PDF files |
| NetworkWalks Password Cracker | Testing password hashes against available wordlists |
| Windows PC | Environment used for the JTR practical exercise |

## Tasks Completed

### 1. WK3-PM1 — Password Cracking with JTR

**Objective:** Recover the passwords of the provided protected PDF files using John the Ripper and Johnny on Windows.

**Activities performed:**

- Downloaded and configured Johnny on my Windows PC.
- Obtained the provided password-protected PDF files.
- Used the File Conversion Tool to extract password hashes.
- Saved the extracted hash in a text file named `hash1.txt`.
- Opened the hash file using Johnny.
- Started a new password recovery attack.
- Successfully recovered the password of the first PDF.
- Repeated the process for the second and third PDF files.

**Result:** Successfully recovered the passwords of all three provided PDF files.

### 2. WK3-PM2 — Password Cracking with NetworkWalks Tools

**Objective:** Use NetworkWalks online tools to extract and recover the password of a protected PDF file.

**Activities performed:**

- Opened NetworkWalks Hash Calculator.
- Uploaded the provided password-protected PDF file.
- Extracted and copied its password hash.
- Opened NetworkWalks Password Cracker.
- Submitted the extracted hash.
- Observed the password-cracking process.

**Result:** The Password Cracker processed 91 out of 100 available wordlists and successfully recovered the correct password.

## Key Observations

- Password-protected files can contain hashes that can be extracted for authorized security testing.
- Password recovery tools can test password strength using different wordlists.
- Weak or commonly used passwords may be recovered more easily.
- John the Ripper and Johnny provide practical ways to understand password security.
- Online password-cracking tools can demonstrate the password recovery process without requiring local installation.

## What I Learned

Through these two practical modules, I gained hands-on experience with password recovery and password security testing.

I learned how to extract password hashes from protected PDF files, load them into Johnny, and perform password recovery.

I also explored NetworkWalks' online Hash Calculator and Password Cracker, gaining a better understanding of how wordlists are used during password-cracking attempts.

Most importantly, this exercise helped me understand why strong, unique passwords are important and how password security assessments can help identify weak passwords before they become a security risk.

## Evidence and Documentation

Screenshots documenting the practical steps and observed results are organized in the `Evidence` directory:

- `WK3-PM1-JTR/`
- `WK3-PM2-NETWORKWALKS-TOOLS/`

## Ethical Considerations

All activities were conducted as part of an authorized educational internship exercise using the provided lab files and tools.

Password-cracking techniques should only be used on files, systems, and password hashes for which proper authorization has been granted.

## Acknowledgment

This project was completed as part of the NetworkWalks Cybersecurity Internship 2026.

Special thanks to NetworkWalks and my instructor Waqas Karim CCIE for providing the learning resources, practical exercises, and guidance throughout the internship.

---

**Week 3 completed. Continuing to learn, practice, and build my cybersecurity skills, one project at a time, Insha'Allah.**
