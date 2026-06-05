# IT Ticketing System Labs

## Overview

This repository contains hands-on IT Help Desk ticketing labs focused on practicing real-world Tier 1 support workflows. Each lab simulates a different support scenario and demonstrates how a support ticket can be created, categorized, prioritized, documented, updated, resolved, and closed in a professional help desk environment.

The purpose of this repository is to document practical IT support skills such as ticket creation, user communication, troubleshooting documentation, internal notes, priority assessment, escalation decisions, resolution notes, and user verification.

---

## Labs

| Lab | Scenario | Tool / Platform | Focus Area |
|---|---|---|---|
| [Lab 01: Outlook Sync Issue](./Lab-01-Outlook-Sync-Issue/README.md) | User cannot receive new emails in Outlook | Spiceworks Cloud Help Desk | Email troubleshooting, public comments, internal notes, resolution documentation |
| [Lab 02: Password Reset Request](./Lab-02-Password-Reset-Request/README.md) | User is locked out and needs password support | Ticketing System / Active Directory Concept | Account access, identity verification, password reset workflow |
| [Lab 03: Printer Not Responding](./Lab-03-Printer-Not-Responding/README.md) | User cannot print to an office printer | Ticketing System / Printer Support | Printer troubleshooting, device checks, user communication |
| [Lab 04: Wi-Fi Connectivity Issue](./Lab-04-WiFi-Connectivity-Issue/README.md) | User cannot connect to office Wi-Fi | Ticketing System / Network Support | Network troubleshooting, impact assessment, escalation decision |
| [Lab 05: New Workstation Setup](./Lab-05-New-Workstation-Setup/README.md) | New employee needs workstation setup | Ticketing System / Endpoint Support | Device preparation, software installation, deployment documentation |

---

## Repository Structure

Each lab has its own folder, README file, and screenshots.

Example structure:
```
IT-Ticketing-System-Labs/
│
├── README.md
│
├── Lab-01-Outlook-Sync-Issue/
│   ├── README.md
│   └── screenshots/
│
├── Lab-02-Password-Reset-Request/
│   ├── README.md
│   └── screenshots/
│
├── Lab-03-Printer-Not-Responding/
│   ├── README.md
│   └── screenshots/
│
├── Lab-04-WiFi-Connectivity-Issue/
│   ├── README.md
│   └── screenshots/
│
└── Lab-05-New-Workstation-Setup/
    ├── README.md
    └── screenshots/
```
---

## Objectives

The main objectives of this repository are to practice and document:

- Creating support tickets
- Gathering user and system information
- Classifying technical issues
- Assigning ticket priority based on impact and urgency
- Communicating with users professionally
- Adding internal IT notes
- Updating ticket status
- Recording troubleshooting steps
- Documenting resolutions
- Verifying fixes with users
- Deciding when escalation is or is not needed
- Closing tickets properly

---

## What Is a Ticketing System?

A ticketing system is a tool used by IT teams to record, organize, track, manage, and resolve support requests submitted by users.

A ticketing system helps IT teams maintain:

- Clear documentation
- Proper issue tracking
- Efficient communication
- Accountability
- Better prioritization
- A history of troubleshooting steps and resolutions

Common ticketing systems include:

- Spiceworks
- Jira Service Management
- Zendesk
- Freshservice
- ServiceNow

---

## Key Ticketing Terms

### Ticket ID

A unique number assigned to each support ticket for tracking and reference.

### Requester

The person who reports the issue or submits the support request.

### Assignee

The IT technician responsible for working on the ticket.

### Summary

A short title that clearly describes the issue.

Example:

Outlook inbox not syncing - Missing time-sensitive client emails

### Description

A detailed explanation of the issue. This may include what the user is experiencing, when the issue started, what system or device is affected, and how urgent the issue is.

### Category

The classification of the issue.

Examples:

- Hardware issue
- Software issue
- Network issue
- Email issue
- Account access
- Printer issue
- Password reset
- Application support
- Device setup

### Priority

The urgency and impact level of the issue.

### Status

The current stage of the ticket in the support workflow.

---

## Priority Levels

Priority should be based on both business impact and urgency.

| Priority | Meaning | Impact | Example |
|---|---|---|---|
| Critical (P1) | Major outage or business-wide issue | High | Company email system is down |
| High (P2) | Important issue affecting business work | Moderate to High | User cannot access time-sensitive client emails |
| Medium (P3) | Single-user issue with limited impact | Low to Moderate | Outlook is not syncing for one user without an urgent deadline |
| Low (P4) | Minor request or non-urgent issue | Minimal | User needs a new mouse or has a basic software question |

---

## How to Choose the Correct Priority

### Critical Priority

Use Critical priority when a major system or service is down and many users or the entire organization are affected.

Examples:

- Company email system is down
- Network outage affecting multiple departments
- Business-critical application unavailable for all users

### High Priority

Use High priority when the issue has clear business impact or prevents a user or department from completing important work.

Examples:

- User cannot access time-sensitive client emails
- Department application is offline
- Important meeting or deadline is affected
- User cannot perform a critical job function

### Medium Priority

Use Medium priority when the issue affects one user but does not completely stop business operations.

Examples:

- Outlook sync issue for one user with no urgent deadline
- One workstation is slow but still usable
- A single user has a software issue
- Printer issue affecting one user

### Low Priority

Use Low priority for minor, non-urgent, or convenience-related requests.

Examples:

- New mouse request
- Basic software question
- Non-urgent equipment request
- Minor display or preference issue

---

## Status Types

Different ticketing systems may use different status names. In these labs, the most common statuses are Open, Waiting, and Closed.

| Status | Meaning |
|---|---|
| New | Ticket created but not yet reviewed |
| Open | Ticket is active and being reviewed or worked on |
| In Progress | Technician is actively working on the issue |
| Waiting / Pending User Response | Technician is waiting for user information or confirmation |
| Escalated | Ticket has been sent to a higher-level technician or another team |
| Resolved | Technician has fixed the issue |
| Closed | User confirmed the issue is resolved and no further action is needed |

---

## What Makes a Good IT Support Ticket?

A good IT support ticket should be clear, complete, and easy for another technician to understand.

A strong ticket should include:

- Clear summary of the issue
- Requester/contact information
- User department or location if relevant
- Affected device, system, or application
- Issue category
- Priority level
- Business impact
- Public communication with the user
- Internal IT notes
- Troubleshooting steps
- Resolution
- Verification
- Escalation notes if needed
- Final status

Good ticket documentation makes it easier for other technicians to understand what happened, what was already tried, what fixed the issue, and whether the user confirmed the resolution.

---

## Public Comments vs. Internal Notes

### Public Comments

Public comments are messages visible to the user. They should be professional, clear, and easy to understand.

Public comments are used to:

- Acknowledge the user’s request
- Ask follow-up questions
- Provide updates
- Confirm that troubleshooting is in progress
- Notify the user that the ticket will be closed

Example:

Hi Andrew, thank you for reaching out. I understand that your Outlook inbox is not syncing and that you need access to time-sensitive client emails today. I’ll begin troubleshooting shortly and keep you updated.

### Internal Notes

Internal notes are only visible to the IT team. They are used to document technical details, troubleshooting steps, status changes, and escalation decisions.

Internal notes are used to:

- Record initial review
- Document priority decisions
- Track troubleshooting steps
- Explain status changes
- Record resolution details
- Document user verification
- Add escalation notes

Example:

Initial review: User reports that Outlook inbox is not syncing and that they are missing time-sensitive client emails. Priority set to High due to business impact and urgency.

---

## How to Properly Log a Ticket

### 1. Gather User Information

Important user information may include:

- Name
- Email
- Contact number
- Department
- Location, if applicable
- Availability for troubleshooting

### 2. Gather System Information

Important system information may include:

- Device type
- Operating system
- Software or application affected
- Software version, if available
- Network type, such as Wi-Fi or Ethernet
- Error messages, if any

### 3. Categorize the Issue

Choose the category that best matches the issue.

Examples:

- Software issue
- Hardware failure
- Network issue
- Email issue
- Access request
- Printer issue

### 4. Determine Priority Level

Priority should be based on impact and urgency.

Ask:

- Is this affecting one user or multiple users?
- Is this blocking important work?
- Is there a deadline or meeting involved?
- Is a business-critical system affected?
- Can the user continue working with a workaround?

### 5. Document Troubleshooting Steps

Each action taken should be documented clearly.

Example:

- Confirmed whether the issue occurs in Outlook Web App or only in the Outlook desktop application.
- Verified that the user is connected to the network.
- Checked for visible sync errors.
- Restarted Outlook.
- Reconnected the Outlook account.

### 6. Document the Resolution

The resolution should explain what fixed the issue.

Example:

Restarted Outlook and reconnected the user’s account. New emails began syncing successfully.

### 7. Verify the Fix

Before closing the ticket, confirm that the user can work normally again.

Example:

User confirmed that new emails are now syncing and that time-sensitive client emails are accessible.

### 8. Add Escalation Notes

If escalation was not needed, document that clearly.

Example:

No escalation was needed. The issue was resolved through Tier 1 troubleshooting.

If escalation was needed, document why.

Example:

Issue was not resolved after initial troubleshooting. Escalated to Tier 2 with troubleshooting steps and user impact documented.

---

## General Ticket Workflow

The general workflow used in these labs is:

1. Review the user’s request.
2. Identify the affected user, system, and business impact.
3. Categorize the issue.
4. Set the correct priority.
5. Assign the ticket to a technician.
6. Send an initial public response to the user.
7. Add an internal note documenting the initial review.
8. Ask follow-up questions if more information is needed.
9. Change the status to Waiting if waiting for the user.
10. Continue troubleshooting after receiving more information.
11. Document troubleshooting steps.
12. Record the resolution.
13. Verify the issue is resolved.
14. Add escalation notes.
15. Send a final public update.
16. Close the ticket.

---

## Getting Started with Spiceworks

For the first lab, I used Spiceworks Cloud Help Desk.

Basic steps:

1. Sign up for a free Spiceworks Cloud Help Desk account.
2. Log in to the Help Desk dashboard.
3. Create a new ticket.
4. Add the requester/contact.
5. Write a clear summary and description.
6. Select the priority.
7. Select the category.
8. Assign the ticket to a technician.
9. Add public comments and internal notes.
10. Update the status as the ticket progresses.
11. Document troubleshooting, resolution, verification, and closure.

---

## Skills Demonstrated

This repository demonstrates the following IT support skills:

- Help Desk ticket creation
- Ticket documentation
- User communication
- Internal IT notes
- Priority assessment
- Issue categorization
- Ticket status management
- Troubleshooting documentation
- Resolution documentation
- User verification
- Escalation decision-making
- Tier 1 troubleshooting workflow
- Professional written communication
- Basic software, hardware, network, account, and endpoint support concepts

---

## Key Takeaways

These labs are designed to build practical IT support documentation skills. The main focus is not only solving the issue, but also creating a clear record of what happened, what was communicated, what troubleshooting was completed, whether escalation was needed, and how the issue was resolved.

Good ticket documentation helps IT teams provide consistent support, reduce repeated troubleshooting, improve communication, and maintain a reliable history of support actions.
