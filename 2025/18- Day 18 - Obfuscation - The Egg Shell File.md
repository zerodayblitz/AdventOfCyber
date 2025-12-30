# Day 18 - Obfuscation - The Egg Shell File
## Overview
Day 18 served as an introduction to obfuscation and its role in cybersecurity. This day piggybacked off of what we went over in Day 17. Touching further on topics of encoding/decoding.
## Objective and What I Did
Day 18 began by providing an overview of obfuscation and its role in information security. The task at hand required me to investigate and deobfuscate a script. Firstly, deobfuscated the string present in a variable in the script and ran it to find the first flag. Secondly, I had to obfuscate the API key present in script, and run it to recieve the second flag.
## Key Takeaway
Day 18 introduced the importance of obfuscation and how attackers use it. Many “gibberish” malicious strings are just common obfuscation layers (ROT, Base64, XOR, compression) that you can systematically peel back with tooling like CyberChef to understand and modify malware scripts.
