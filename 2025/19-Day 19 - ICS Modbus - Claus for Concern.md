# Day 19 - ICS/Modbus - Claus for Concern
## Overview
Day 19 provided users with an intro into how ISC/SCADA and Modbus work at a basic level and identified a Modbus-based logic manipulation attack.
## Objective and What I Did
I began by performing recon using ````nmap```` and Python to enumerate Modbus registers and coils on the PLC. Wrote and ran reconnaissance.py to map system state, then restore_christmas.py to disable protection, change the package type back to Christmas presents, re-enable safety controls, and retrieve the flag.
## Key Takeaway
Modbus-based aICs often lack authentication, so attacks can directly manipulate PLC logic. This being the case, security professionals need to understand the register coil logic and changing values to avoid triggering safety issues.
