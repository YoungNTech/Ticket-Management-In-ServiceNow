

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
- Demo recording: Loom link above

---

## Steps Performed

### 1. Created a Password Reset Ticket
- Logged into ServiceNow.
- Opened a new incident and selected the appropriate category for password resets.
- Entered user identity and contact information, concise problem description, and any relevant context.
- Assigned the ticket to the correct support group and set initial priority and impact.
- Screenshots:
  <img width="755" height="835" alt="New ticket form with user details" src="https://github.com/user-attachments/assets/bec3818c-ec80-4837-a224-a81da8ccb669" />
  <img width="1683" height="987" alt="Ticket assigned to support group" src="https://github.com/user-attachments/assets/6502b9a1-9cb3-43c8-bb66-09cc0160e63d" />

### 2. Resolved the Ticket
- Performed identity verification according to organizational policy (e.g., challenge questions, manager confirmation, or approved MFA method).
- Reset the user’s password in Active Directory and validated access where applicable.
- Documented the exact steps taken and any temporary credentials or instructions provided to the user.
- Updated the ticket’s Resolution Notes and changed the ticket status to *Resolved*.
- Screenshot:
  <img width="1845" height="983" alt="Resolution details entered into ticket" src="https://github.com/user-attachments/assets/b224e38e-7a17-47de-9565-35860121d00a" />

### 3. Closed the Ticket
- Confirmed with the user that they could log in successfully (or allowed a verification period per SLAs).
- Reviewed the ticket to ensure all mandatory fields and audit details were completed.
- Added final notes, closed any pending tasks, and transitioned the ticket to *Closed*.
- Screenshot:
  <img width="1722" height="969" alt="Ticket closed with final notes" src="https://github.com/user-attachments/assets/2aba87f2-eb75-4565-9451-6f51c280aef0" />

---

## Outcome
The exercise demonstrated a complete and compliant ticket lifecycle within ServiceNow. The password reset request was handled promptly, with identity verification, AD password reset, thorough documentation, and proper ticket closure. This reinforces repeatable, auditable IT support practices.

## Lessons Learned
- Clear, concise resolution notes improve handoffs and audits.
- Following identity verification policies is essential to maintain security during password resets.
- Assigning the correct support group and priority up front reduces resolution time.

## Recommendations
- Add a brief checklist to the incident template for password resets (identity verification steps, AD validation steps, user confirmation).
- Standardize resolution note templates to capture key audit fields consistently.
- Consider automating parts of the workflow (e.g., status transitions or reminders) to improve SLA compliance.

