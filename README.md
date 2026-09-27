# Auto Ticket Classification using Flow Designer - ServiceNow

## Project Overview
This project automates Incident ticket classification in ServiceNow using Flow Designer. It auto-categorizes tickets based on Short Description keywords, reducing manual effort.

## Team Details
- Team ID: 1008271314a
- Project: Auto Ticket Classification - Flow Designer
- Platform: ServiceNow PDI

## Problem Statement
IT support teams receive 100+ tickets daily. Manual categorization causes delay, wrong assignment and SLA breach.

## Solution & Workflow
1. User Creates Incident
2. Flow Trigger: Record Created on Incident Table
3. If Condition checks Short Description:
   - contains "password/login/email" -> Category = Software
   - contains "wifi/network/internet" -> Category = Network
   - contains "laptop/hardware/mouse" -> Category = Hardware
4. Update Record: Set Category and Assignment Group
5. Ticket auto-classified in 2-3 seconds

## Tools Used
- ServiceNow Personal Developer Instance
- Flow Designer
- Incident Table [incident]

## Benefits
- 80% faster classification
- No-code automation
- Accurate routing
- Improved SLA

## Project Phases
All 8 phases are documented in this repo.

## Demo Video
(Will be updated with Google Drive link)

## Created By
1008271314a-cloud
