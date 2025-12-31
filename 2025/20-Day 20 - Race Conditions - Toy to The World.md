# Day 20 - Race Conditions - Toy to The World
## Overview
This room walks through a race condition that was run in an e-commerce app. It focuses on introducing TOCTOU, shared resource, and atomicity violation race conditions.
## Objective and What I Did
I was tasked with exploiting a race condition in the TBFC shopping cart app to push item stock negative to achieve Day 20's flags. Using Burp, I proxied Firefox and captured the ````/process_checkout```` POST request and cloned it in Repeater. From this, I then sent the group to generate a multitude of successful orders from a single limited stock item.
## Key Takeaway
Properly synchronising shared resources with atomic transactions, stock checks, and rate limiting, amongst other final patches, is crucial to prevent race condition abuse in web applications.
