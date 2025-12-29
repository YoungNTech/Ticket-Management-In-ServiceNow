

## Lab Overview
This lab exercised end-to-end ticket management in ServiceNow (SNOW). The primary objective was to simulate a common IT support workflow by creating, resolving, and closing a password reset incident.

## Objectives
- Create a password reset incident with accurate user and issue details.
- Verify identity and perform a password reset in Active Directory (AD).
- Document resolution steps and transition the ticket through Resolved → Closed.
- Practice best-practice ticket lifecycle management and documentation in ServiceNow.

## Environment
- Platform: ServiceNow
- Directory: Active Directory (for password reset)


---

## Steps Performed

### 1. Created a Password Reset Ticket
- Logged into ServiceNow.
- Opened a new incident and selected the appropriate category for password resets.
- Entered user identity and contact information, concise problem description, and any relevant context.
- Assigned the ticket to the correct support group and set initial priority and impact.

<img width="1605" height="1186" alt="Screenshot 2025-12-07 114901" src="https://github.com/user-attachments/assets/6d862c05-8f2c-4116-bc85-b9b3f33864f5" />
<img width="2880" height="1510" alt="Screenshot 2025-12-07 115504" src="https://github.com/user-attachments/assets/4a9b3370-0b64-4097-ac04-5c7c4b1347a3" />


  

### 2. Resolved the Ticket
- Performed identity verification according to organizational policy (e.g., challenge questions, manager confirmation, or approved MFA method).
- Reset the user’s password in Active Directory and validated access where applicable.
- Documented the exact steps taken and any temporary credentials or instructions provided to the user.
- Updated the ticket’s Resolution Notes and changed the ticket status to *Resolved*.
- Screenshot:<img width="2880" height="1509" alt="Screenshot 2025-12-07 115254" src="https://github.com/user-attachments/assets/7c9a4e8f-20a6-4735-a106-865ecd2d845c" />




  

### 3. Closed the Ticket
- Confirmed with the user that they could log in successfully (or allowed a verification period per SLAs).
- Reviewed the ticket to ensure all mandatory fields and audit details were completed.
- Added final notes, closed any pending tasks, and transitioned the ticket to *Closed*.


<img width="2880" height="1376" alt="Screenshot 2025-12-07 115608" src="https://github.com/user-attachments/assets/39c7eb09-7f1d-4628-81a3-2e36d20ce9c8" />

## Outcome
The exercise demonstrated a complete and compliant ticket lifecycle within ServiceNow. The password reset request was handled promptly, with identity verification, AD password reset, thorough documentation, and proper ticket closure. This reinforces repeatable, auditable IT support practices.

