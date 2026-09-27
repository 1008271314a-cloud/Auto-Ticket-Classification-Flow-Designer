# Phase 5: Project Development
## Steps Implemented:
1. Logged into ServiceNow PDI
2. Navigated to Flow Designer -> New Flow -> Name: Auto Ticket Classification
3. Added Trigger: Record Created on Incident
4. Added Action: If - Short Description contains password/email/outlook -> Update Category=Software
5. Added Else If - contains wifi/network/internet -> Category=Network
6. Else -> Category=Hardware
7. Added Update Record Action for each branch
8. Activated Flow
9. Tested by creating Incidents
