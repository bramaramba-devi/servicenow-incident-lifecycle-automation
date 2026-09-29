# ServiceNow – Incident Lifecycle Automation

## Project Overview

This repository documents an end-to-end ServiceNow Incident Management workflow for a Corporate VPN connectivity issue. The supplied project materials cover service and incident setup, classification, Agent Assist and knowledge support, assignment and escalation, Level 2 investigation, configuration-item context, change dependency, related/child records, cause, resolution, knowledge creation, SLA validation, and final end-to-end validation.

## Objective

Demonstrate a traceable ServiceNow incident lifecycle from reported problem through investigation, change dependency, resolution, and validation.

## Problem Statement

A user was unable to connect to the Corporate VPN from a home office. The issue was captured as a structured incident so that caller, service, classification, priority, ownership, investigation history, cause, and resolution could be maintained together.

## Functional Scope

- Service: Remote Access
- Service offering: Corporate VPN
- Scenario: Unable to connect to Corporate VPN from home office
- Caller: Michael Hoefer
- Initial assignment group: Service Desk
- Category / Subcategory: Network / VPN
- Channel: Phone
- Urgency: 2 - Medium
- Configuration item: ThinkStationS20, later PowerEdge
- Network assignment: Network
- Level 2 user: David Loo
- On Hold reason: Awaiting Change
- Probable cause: PowerEdge service was suspended and required restart.
- Resolution code: Workaround provided
- Resolution notes: Restarted VPN-SRV-02 service as per emergency change request.
- Knowledge Base: IT
- Template: Standard

## Stakeholders

End Users; Service Desk Agents; Level 2 Support / Network / Hardware Teams; Change Management Team; ServiceNow Administrator.

## Workflow

Service Creation → Service Offering Creation → Incident Record Creation → Incident Classification → Agent Assist → Knowledge Article Search → Knowledge Article Helpful/Attach → Watch List → Work Notes List → Reassignment to Network → Level 2 Investigation → Configuration Item Update → On Hold – Awaiting Change → Child Incident Creation → Cause Documentation → Resolution Documentation → Incident Resolution → Knowledge Article Creation → SLA Validation → Related Records Validation → Final End-to-End Validation.

## Milestones

- Incident Record Creation
- Incident Classification
- Knowledge Integration
- Reassignment & Escalation
- Change Request Creation
- Child Incident Creation
- Incident Resolution
- Knowledge Creation
- SLA & Related Record Validation

## Technology / ServiceNow Modules

ServiceNow cloud platform, ITSM Incident Management, Service Operations Workspace, Agent Assist, Knowledge, assignment/state management, Related Records, SLA information, and the incident resolution workflow.

## Project Structure

```text
servicenow-incident-lifecycle-automation/
├── README.md
├── Documentation/
│   ├── Project-Report.pdf
│   ├── Project-Report.docx
│   ├── Project-Content.md
│   └── Submission-Evidence.md
├── Screenshots/
│   ├── 01-Service-Configuration/
│   ├── 02-Incident-Creation/
│   ├── 03-Incident-Classification/
│   ├── 04-Agent-Assist/
│   ├── 05-Knowledge-Integration/
│   ├── 06-Assignment-Reassignment/
│   ├── 07-Level-2-Investigation/
│   ├── 08-Configuration-Item/
│   ├── 09-On-Hold-Awaiting-Change/
│   ├── 10-Child-Incident/
│   ├── 11-Cause/
│   ├── 12-Resolution/
│   ├── 13-Knowledge-Creation/
│   └── 14-Final-Validation/
├── Testing/
│   ├── Test-Cases.md
│   └── Test-Results.md
├── Demo/
│   └── demo-link.txt
└── assets/
    └── diagrams/
```

## Testing

Detailed test cases and final validation are in [Testing/Test-Cases.md](Testing/Test-Cases.md) and [Testing/Test-Results.md](Testing/Test-Results.md). Evidence-backed results are distinguished from project-content steps where no separate screenshot was supplied.

## Results

The supplied project evidence covers incident creation, classification/priority, Agent Assist and knowledge content, assignment/related records, investigation/activity, On Hold/Awaiting Change, related-record context, probable cause, resolution, the Resolve dialog, and SLA/summary information.

## Advantages

- Traceable incident lifecycle
- Clear ownership and reassignment
- Knowledge-assisted investigation
- Activity and work-note history
- Explicit change dependency handling
- Cause and resolution documentation
- SLA and related-record visibility

## Disadvantages

- Depends on accurate data entry
- Some actions depend on other operational teams
- Behavior depends on ServiceNow instance configuration and roles
- The project represents a training/developer-instance workflow rather than a production deployment

## Future Scope

Possible extensions documented in the project include automated classification/routing, richer knowledge recommendations, incident correlation, proactive monitoring, automated change coordination, and recurring-incident/problem management.

## Conclusion

The project demonstrates a structured ServiceNow Incident Management lifecycle for a Corporate VPN issue, connecting creation, classification, assignment, knowledge support, investigation, change dependency, cause, resolution, related records, activity history, and SLA validation.

## Screenshots

Original screenshot evidence supplied in the project report is organized by lifecycle phase. Available evidence includes:

- [Incident Creation](Screenshots/02-Incident-Creation/01-Incident-Record-Overview.png)
- [Incident Classification](Screenshots/03-Incident-Classification/02-Incident-Classification-and-Priority.png)
- [Agent Assist](Screenshots/04-Agent-Assist/03-Agent-Assist-and-Assignment.png)
- [Knowledge Integration](Screenshots/05-Knowledge-Integration/04-Agent-Assist-Knowledge-Article.png)
- [Assignment / Related Records](Screenshots/06-Assignment-Reassignment/05-Assignment-and-Related-Records.png)
- [Level 2 Investigation](Screenshots/07-Level-2-Investigation/06-Investigation-and-Activity.png)
- [Parent Incident Relationship](Screenshots/10-Child-Incident/07-Parent-Incident-Relationship.png)
- [On Hold – Awaiting Change](Screenshots/09-On-Hold-Awaiting-Change/08-On-Hold-Awaiting-Change.png)
- [Probable Cause](Screenshots/11-Cause/09-Probable-Cause.png)
- [Cause and Resolution](Screenshots/12-Resolution/10-Cause-and-Resolution.png)
- [Resolve Dialog](Screenshots/12-Resolution/11-Resolve-Dialog.png)
- [SLA and Incident Summary](Screenshots/14-Final-Validation/12-SLA-and-Incident-Summary.png)

No separate screenshot was supplied for Service Configuration, Configuration Item Update, or Knowledge Article Creation; those phases are documented without fabricated visual evidence.

## Documentation

- [Project Report – PDF](Documentation/Project-Report.pdf)
- [Project Report – DOCX](Documentation/Project-Report.docx)
- [Project Content](Documentation/Project-Content.md)
- [Submission Evidence](Documentation/Submission-Evidence.md)

## Demo

No actual screen-recording link was supplied. See [Demo/demo-link.txt](Demo/demo-link.txt).

## GitHub Repository Information

Repository: bramaramba-devi/servicenow-incident-lifecycle-automation

No passwords, access tokens, ServiceNow credentials, or authentication information are stored in this repository.
