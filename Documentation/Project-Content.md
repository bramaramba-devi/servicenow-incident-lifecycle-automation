# ServiceNow – Incident Lifecycle Automation: Project Content

## 1. INTRODUCTION

### 1.1 Project Overview

ServiceNow is used as the platform for demonstrating an IT Service Management incident lifecycle. The project follows a corporate VPN connectivity incident from creation through investigation and resolution. The supplied project report identifies the practical incident as `INC0010001` and describes the issue as **Unable to connect to Corporate VPN from home office**.

The project demonstrates the use of the Service Operations Workspace, Incident Management, Activity stream, Work notes, Agent Assist, Knowledge content, Assignment management, Related Records, SLA information, state management, cause documentation, and resolution.

### 1.2 Purpose

The purpose is to demonstrate a traceable incident-management workflow in which user information and technical troubleshooting information are maintained in one ServiceNow record. The workflow covers classification, ownership, investigation, change dependency, resolution, and validation.

## 2. IDEATION PHASE

### 2.1 Problem Statement

The identified problem is a corporate VPN connectivity failure experienced from a home office. The Internet connection is working, while the corporate VPN cannot be connected and an authentication error is reported. The issue therefore needs to be captured as a structured incident rather than treated as a general Internet outage.

The project workflow uses Network as the category and VPN as the subcategory. The incident later reaches **On Hold – Awaiting Change**, and the documented probable cause is that the **PowerEdge service was suspended and required restart**.

### 2.2 Empathy Map Canvas

- **Says:** The user reports that the Corporate VPN cannot be connected from the home office and an authentication error is received.
- **Thinks:** The user expects the VPN to work because Internet connectivity is available and expects support to restore access.
- **Does:** Attempts the VPN connection and contacts support by phone.
- **Feels:** Concerned about losing access to corporate resources while the basic Internet connection still works.
- **Support need:** The support team needs a clear symptom, classification, priority, ownership, troubleshooting history, and final resolution.

### 2.3 Brainstorming

Possible troubleshooting directions described in the supplied project materials include checking Internet connectivity, VPN configuration/authentication, knowledge guidance, assignment to the Network team, and the relevant VPN service. If a service restart or infrastructure action is required, the incident can use the change process and an On Hold state while the dependency is handled.

## 3. REQUIREMENT ANALYSIS

### 3.1 Customer Journey Map

1. User experiences Corporate VPN connectivity failure.
2. Service Desk records the incident.
3. The incident is classified as Network / VPN.
4. Priority information is captured from the incident fields.
5. Agent Assist and knowledge content are reviewed.
6. The incident is assigned/reassigned to the appropriate technical team.
7. Level 2 investigation continues with activity and work-note traceability.
8. The configuration item is updated as documented in the project workflow.
9. The incident is placed On Hold with **Awaiting Change** when a change dependency exists.
10. Related/child records are handled as part of the workflow.
11. Cause and resolution are documented.
12. SLA and related-record information are validated before final completion.

### 3.2 Solution Requirement

The solution must support unique incident tracking; caller, location, channel, short and detailed descriptions; category and subcategory; impact, urgency, priority; assignment group and assigned user; Activity stream and Work notes; On Hold and reason; probable-cause documentation; resolution code and notes; SLA visibility; related records/parent-child relationships; and knowledge/Agent Assist support.

### 3.3 Data Flow Diagram

**Caller → ServiceNow Incident → Classification → Prioritization → Network Assignment → Investigation → Change/Workaround → Validation → Resolution → Closure**

### 3.4 Technology Stack

- **Platform:** ServiceNow cloud platform
- **Application:** IT Service Management (ITSM) – Incident Management
- **Workspace:** Service Operations Workspace
- **Knowledge support:** Agent Assist and knowledge articles
- **Process elements:** classification, assignment, state management, SLA tracking, related records, and resolution
- **Interface:** Web-based ServiceNow user interface

## 4. PROJECT DESIGN

### 4.1 Problem Solution Fit

The ServiceNow workflow fits the VPN incident because the problem needs ownership, tracking, escalation, dependency management, and documented closure. The incident record combines user context with technical context and maintains the activity history needed for traceability.

### 4.2 Proposed Solution

The proposed workflow begins with the **Remote Access** service and **Corporate VPN** service offering. The incident scenario is recorded with caller **Michael Hoefer**, initial assignment group **Service Desk**, Network/VPN classification, Phone channel, and urgency **2 - Medium**. The documented workflow then moves toward Network assignment and Level 2 investigation.

The project materials document **ThinkStationS20** as the initial configuration item and **PowerEdge** later in the workflow. The Level 2 user is **David Loo**. When a change dependency is present, the incident is placed On Hold with **Awaiting Change**.

The documented probable cause is: **PowerEdge service was suspended and required restart.**

- **Resolution code:** Workaround provided
- **Resolution notes:** Restarted VPN-SRV-02 service as per emergency change request.

### 4.3 Solution Architecture

The solution uses ServiceNow Incident Management as the central record. User/service information enters the incident, classification determines routing, Agent Assist and Knowledge support investigation, assignment controls ownership, state and change dependency control the lifecycle, and cause/resolution/SLA/related-record information provide closure evidence.

## 5. PROJECT PLANNING & SCHEDULING

### 5.1 Project Planning

The supplied project report describes a sequence based on requirement identification, workflow mapping, evidence collection, testing, and documentation.

### Planned stages

1. Problem identification and incident creation
2. Classification, prioritization, and assignment
3. Investigation, knowledge support, and activity tracking
4. Change dependency and On Hold management
5. Cause identification and service restoration
6. Resolution code, resolution notes, and closure
7. Testing, screenshot collection, and final documentation

### Milestones

- Incident Record Creation
- Incident Classification
- Knowledge Integration
- Reassignment & Escalation
- Change Request Creation
- Child Incident Creation
- Incident Resolution
- Knowledge Creation
- SLA & Related Record Validation

## 6. FUNCTIONAL AND PERFORMANCE TESTING

### 6.1 Performance Testing

The supplied project materials describe functional verification of the incident lifecycle and review of SLA information. The evidence focuses on the correctness and traceability of incident fields, state transitions, assignment, activity, related records, cause, and resolution. No unsupported numeric performance benchmark has been introduced into this repository.

## 7. RESULTS

### 7.1 Output Screenshots

The original screenshot evidence supplied inside the project report is intended to be preserved and organized by lifecycle phase. The available evidence includes incident creation, classification, Agent Assist/knowledge support, assignment, investigation/activity, On Hold/Awaiting Change, related-record context, probable cause, resolution, Resolve dialog, and SLA/summary information.

## 8. ADVANTAGES AND DISADVANTAGES

### Advantages

- Structured lifecycle tracking
- Clear ownership and reassignment
- Knowledge-assisted investigation
- Activity and work-note traceability
- Explicit handling of change dependencies
- Cause and resolution documentation
- SLA and related-record visibility

### Disadvantages

- Depends on accurate data entry
- Some resolution activities depend on other operational teams
- Behavior depends on ServiceNow instance configuration and user roles
- The project represents a training/developer-instance workflow rather than a production deployment

## 9. CONCLUSION

The project demonstrates an end-to-end ServiceNow Incident Management lifecycle for a Corporate VPN issue. The workflow links incident creation, classification, assignment, knowledge support, investigation, change dependency, cause, resolution, related records, activity history, and SLA validation into a traceable record.

## 10. FUTURE SCOPE

Future work can extend the project with automated classification and routing, richer knowledge recommendations, incident correlation, proactive monitoring, automated change coordination, and recurring-incident/problem management. These are future extensions and are not claimed as completed functionality in the supplied evidence.

## 11. APPENDIX

### Source Code (if any)

This is a ServiceNow platform-based practical implementation. No standalone application source code is required for the demonstrated workflow.

### Dataset Link

Not applicable. The project does not depend on a conventional external dataset; the evidence is based on ServiceNow incident records and the practical configuration/workflow.

### GitHub & Project Demo Link

GitHub repository: `bramaramba-devi/servicenow-incident-lifecycle-automation`

Project demo: no actual screen-recording link was provided in the supplied project materials. See `Demo/demo-link.txt` for the required placeholder.
