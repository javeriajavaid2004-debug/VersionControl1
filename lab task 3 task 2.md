# Task 2: Mission Control Sends Change Requests
## CR-01 — Emergency Safety
### Original Requirement
**FR-04:**  
The rover shall enter Safe Mode when a critical battery or thermal condition is detected.
### Updated Requirement
**FR-04:**  
The rover shall enter Safe Mode within 3 seconds when battery temperature exceeds the critical threshold or battery capacity falls below the defined emergency level.
### Reason for Change
The new requirement is more specific and measurable because it defines the conditions and the 3-second time limit.
---
## CR-02 — Mission Expansion
### Original Requirement
**NFR-04:**  
The system shall support communication with multiple rovers simultaneously.
### Updated Requirement
**NFR-04:**  
The system shall support at least 20 simultaneously connected rovers.
### Reason for Change
The new requirement is measurable because it specifies the exact number of rovers.

## CR-03 — Security Upgrade
### Original Requirement
**NFR-02:**  
Only authenticated Mission Control operators shall be permitted to issue rover commands.
### Updated Requirement
**NFR-02:**  
The system shall require authenticated and role-authorized operators before accepting rover commands.
### Reason for Change
The updated requirement improves security by requiring both authentication and role authorization.
