# Day 9 - Passwords - A Cracking Christmas
## Overview
Day 9 focused on introducing password-based encryption, dictionary and brute-force attacks, and the importance of strength in password protection. 
## Objective and What I Did
The objective was to crack the PDF and zip files on the TryHackMe VM to retrieve Day 9's flags. I began with a dictionary attack. I used the popular ````rockyou.txt```` wordlist with the ````pdfcrack```` argument, then used ````john```` for the zip file.
## Key Takeaway
Cracking basic passwords is easy, so password hardening is important. Utilizing a criterion such as the OWASP password guidelines is a great option in ensuring your passwords are strong.
