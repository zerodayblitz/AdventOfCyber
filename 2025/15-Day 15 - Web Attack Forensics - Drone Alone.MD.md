# Day 15 - Web Attack Forensics - Drone Alone
## Overview
Day 15's task was blue team focused. I was tasked with detecting and analyzing malicious web activity through Apache access nd error logs. This room focused on web attack forensics on a vulnerable CGI endpoint.
## Objective and What I Did
Day 15's objective was to detect and validate a command-injection attack and determine if it reached the OS or not. Using Splunk, I searched HTTP, Apache error, and Sysmon logs for ````cmd.exe````, ````powershell````, and encoded commands to trace the weba attack. I also got practice with Base64 decoding as I decoded the attacker's PowerSell string to further understand what was behind the attack, and finally confirmed Apache spawned and what commands were run.
## Key Takeaway
As this year's advent has been hammering down, logging is imperative for security personnel. Coupled, of course, with the ability to read and correlate web logs, server error logs, and Sysmon logs, is vital to digital forensics and understanding what occurred during an attack
