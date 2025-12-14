

---
# IT Support / Service Desk Portfolio

This repository contains a structured portfolio demonstrating **entry-level to early L2 IT Support capability**, with a focus on:

- Service Desk ticket handling
- ITIL-aligned incident management
- Networking and endpoint troubleshooting
- Clear, reusable documentation
- MSP-style operational practices

The portfolio is organised to reflect how work is actually performed in **Managed Service Provider (MSP)** and internal IT environments, rather than academic or certification-driven content.

---

## How to Navigate This Portfolio

The site is structured around **four core areas**, each serving a distinct purpose:

- **Projects** → Evidence of real-world capability  
- **Knowledge Base** → Conceptual understanding and reference documentation  
- **Implementation Walkthroughs** → End-to-end, reproducible technical workflows  
- **Playbooks** → Operational checklists and templates used during live support  

Hiring managers and recruiters are encouraged to start with **Projects**.

---

## Idealised File Structure

The structure below represents the **intended and maintained organisation** of the portfolio.  
Legacy files are migrated into this structure as content is refined.

```text
/
├── index.md
├── README.md
├── about/
│   └── index.md
│
├── projects/
│   ├── index.md
│   ├── service-desk-ticket-lifecycle/
│   │   ├── index.md
│   │   └── tickets/
│   │       ├── ticket-01-no-internet-single-user.md
│   │       ├── ticket-02-application-slow-peak.md
│   │       ├── ticket-03-account-lockout.md
│   │       ├── ticket-04-printer-unavailable.md
│   │       ├── ticket-05-email-delays.md
│   │       ├── ticket-06-shared-files-inaccessible.md
│   │       ├── ticket-07-workstation-crashes.md
│   │       ├── ticket-08-new-starter-access.md
│   │       ├── ticket-09-wifi-intermittent.md
│   │       └── ticket-10-change-caused-outage.md
│   ├── itil-incident-case-study/
│   │   └── index.md
│   ├── user-lifecycle/
│   │   ├── index.md
│   │   ├── lifecycle-handling-guide.md
│   │   ├── access-validation-checklist.md
│   │   └── request-handling-flow.md
│   └── home-lab/
│       └── windows-ad/
│           └── index.md
│
├── knowledge-base/
│   ├── index.md
│   ├── networking/
│   │   ├── index.md
│   │   ├── connectivity.md
│   │   ├── dns-dhcp.md
│   │   └── wifi-vpn.md
│   ├── ticketing/
│   │   ├── lifecycle.md
│   │   ├── prioritisation.md
│   │   └── escalation.md
│   ├── endpoint-support/
│   │   ├── workstation.md
│   │   └── peripherals.md
│   └── itil/
│       ├── incident-vs-problem.md
│       └── change-basics.md
│
├── walkthroughs/
│   ├── index.md
│   ├── network-connectivity/
│   │   └── index.md
│   ├── endpoint-troubleshooting/
│   │   └── index.md
│   ├── user-access-onboarding/
│   │   └── index.md
│   └── service-desk-ticket-handling/
│       └── index.md
│
├── playbooks/
│   ├── index.md
│   ├── checklists/
│   │   ├── network.md
│   │   ├── hardware.md
│   │   └── software.md
│   └── templates/
│       ├── incident-template.md
│       └── ticket-template.md
│
├── assets/
│   ├── css/
│   ├── diagrams/
│   └── screenshots/
│
├── _sass/
├── _config.yml
````

---

## Section Overview

### Projects

Demonstrates applied capability through structured case studies and ticket examples.
Projects focus on **decision-making, escalation, documentation, and service restoration**, not just technical fixes.

### Knowledge Base

A practical reference library covering:

* Networking fundamentals
* Ticketing and ITSM practices
* Endpoint behaviour
* ITIL concepts

Content is written to support **understanding and troubleshooting**, not exam preparation.

### Implementation Walkthroughs

Documented, end-to-end technical workflows showing how systems are configured, tested, and validated.
These walkthroughs demonstrate the ability to **execute and document real support tasks**, not just describe them.

### Playbooks

Operational documentation used during live support, including:

* Troubleshooting checklists
* Incident and ticket templates
* Standardised documentation formats

These mirror the type of content maintained in MSP knowledge systems such as Confluence, IT Glue, or SharePoint.

---

## Design Principles

All content in this portfolio follows these principles:

* **Practice-first**: aligned with real Service Desk work
* **Tool-agnostic where possible**: transferable across environments
* **Clear and scannable**: usable during live support
* **Escalation-aware**: written for multi-level support teams
* **Documentation-driven**: prioritises clarity and reuse

---

## Status

The overall structure is finalised.
Content continues to be migrated and refined within the defined sections to improve clarity, depth, and realism.
