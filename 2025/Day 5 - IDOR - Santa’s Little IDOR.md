# Day 5 - IDOR - Santa’s Little IDOR
## Overview
Day 5 covered Insecure Direct Object Reference (IDOR) vulnerabilities. I walked through identifying and exploiting one of the TryHackMe VMs.
## Objective and What I Did
The objective of Day 5 was to get familiar with and exploit an IDOR vulnerability. Upon loading into the target machine and the vulnerable webpage, I began surfing through the Developer Tools of the browser to see if there was anything intresting. Lo and behold, there lay a rudimentary IDOR flaw that allowed me to edit the user I was currently logged in as, without authorization (By simply changing the ID #). After searching deeper in the Developer Tools, in which I found there lied deeper IDOR vulnerabilities. I was able to find base64 encoded and MD5-hashed user IDs. Although (slightly) better than being in plaintext, these were very easily reversible and identifiable by using sites like [Base64 Decoder](https://www.base64decode.org/), [CrackStation](https://crackstation.net/), or [Hashes](https://hashes.com/en/tools/hash_identifier).
## Key Takeaway
Like most vulnerabilities, IDOR is very dangerous. The ability for someone to perform either vertical or horizontal privilege escalation by exploiting an IDOR vulnerability is a tremendous red flag for any company. Such a vulnerability is quite surface-level, however needs to be addressed and properly dealt with.
