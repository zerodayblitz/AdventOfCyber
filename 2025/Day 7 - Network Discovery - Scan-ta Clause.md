# Day 7 - Network Discovery - Scan-ta Clause
## Overview
Day 7 was an introduction to Nmap. I got hands-on practice with the basics of network service discovery using Nmap, and engaged with network protocols and concepts.
## Objective and What I Did
I began by running a basic Nmap scan from the TryHackMe AttackBox on the target VM, scanning the top 100 most common ports, and found open ````ssh```` and ````http```` ports. I then used the ````-p-```` argument to instead scan **all** ports and the ````--script=banner```` argument to see what's behind the port. I found the first key by using the ````ftp```` argument, ````nc```` to find the second, and scanned for UDP ports using ````sU```` for the third. These keys allowed me to access the tbfc-devqa01 QA server. Using the terminal there, I then ran commands that allowed me to see the database content (````mysql````).
## Key Takeaway
Port scanning is a powerful and necessary part of the enumeration process for penetration testers. The ability to run simple scans on systems to find out useful information goes a long way in the later parts and processes of pentration testing. It is also helpful in blue team operations, allowing security professionals to understand the attack surface of the systems they're trying to protect, among other advantages.
