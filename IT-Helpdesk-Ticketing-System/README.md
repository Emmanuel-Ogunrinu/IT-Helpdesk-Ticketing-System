# IT Helpdesk Ticketing System (Support Simulation Project)

## Project Overview
This project simulates an enterprise IT service desk environment. It demonstrates how support tickets are received, categorized, prioritized, assigned, resolved, documented, escalated, and closed using IT helpdesk best practices.

The project is designed for entry-level IT Support Technician, Help Desk Analyst, Desktop Support, and Service Desk roles.

## Project Goals
- Simulate real-world IT service desk operations
- Manage the full incident lifecycle from intake to closure
- Apply SLA-based prioritization using impact and urgency
- Document troubleshooting steps and resolutions
- Create reusable knowledge base articles
- Track support metrics such as ticket volume, resolution time, escalation rate, and SLA compliance

## Tools & Concepts Used
- Ticketing workflow simulation
- SLA prioritization
- Incident management
- Troubleshooting documentation
- Knowledge base documentation
- Windows support concepts
- Networking fundamentals
- Account access support concepts
- Customer service communication

## Repository Structure
```text
IT-Helpdesk-Ticketing-System/
├── README.md
├── sample-tickets.xlsx
├── docs/
│   ├── SLA-and-Priority-Matrix.md
│   ├── Escalation-Workflow.md
│   └── Ticket-Lifecycle.md
├── knowledge-base/
│   ├── KB001-Password-Reset.md
│   ├── KB002-Network-Connectivity.md
│   ├── KB003-Software-Installation.md
│   ├── KB004-Printer-Troubleshooting.md
│   └── KB005-Slow-Computer.md
├── reports/
│   └── Monthly-Helpdesk-Report.md
└── screenshots/
    └── add-screenshots-here.txt
```

## Ticket Categories Simulated
- Password reset
- Account lockout
- Software installation
- Network connectivity failure
- Printer issue
- Slow computer
- VPN access issue
- Email access issue
- Hardware issue

## SLA Rules Used
| Priority | Response SLA | Resolution SLA | Example |
|---|---:|---:|---|
| Critical | 15 minutes | 4 hours | Department-wide outage |
| High | 30 minutes | 8 hours | User cannot work |
| Medium | 4 hours | 2 business days | Software install request |
| Low | 1 business day | 5 business days | General how-to request |

## Sample Metrics
The workbook includes a dashboard that tracks:
- Total tickets
- Open tickets
- Closed tickets
- Escalated tickets
- SLA compliance
- Average resolution hours
- Ticket volume by category
- Ticket count by priority

## Resume Bullet Version
**IT Helpdesk Ticketing System (Support Simulation Project)**  
- Simulated enterprise IT service desk operations by managing 30 support tickets from intake through closure using ITIL-aligned incident lifecycle practices.
- Resolved common end-user issues including password resets, account lockouts, software installations, printer failures, and network connectivity problems.
- Applied SLA-based prioritization using impact and urgency to determine response targets, resolution targets, and escalation requirements.
- Documented troubleshooting steps and resolutions in knowledge base articles to improve repeat issue handling and support consistency.
- Created reporting dashboard to track ticket volume, average resolution time, escalation rate, and SLA compliance.

## How to Use This Project
1. Open `sample-tickets.xlsx`.
2. Review the `Tickets` sheet to see the simulated incident queue.
3. Review the `Dashboard` sheet to see support metrics.
4. Read the knowledge base articles in the `knowledge-base` folder.
5. Add screenshots from your own Jira, Zendesk, ServiceNow developer instance, or Google Sheets dashboard into the `screenshots` folder.
6. Upload this repository to GitHub and include the link on your resume.

## Portfolio Presentation Tip
When presenting this project to recruiters, explain it as:
> “I built a helpdesk simulation to practice the same workflow used in enterprise IT support: ticket intake, prioritization, troubleshooting, escalation, documentation, and SLA reporting.”
