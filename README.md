# CAPA
Corrective Action, Preventive Action

This repository serves as a centralized log of Corrective and Preventive Actions (CAPA) taken in response to outages, performance degradations, or operational issues across our infrastructure.

⚙️ What Qualifies as a CAPA

To maintain consistency and focus, this repository only logs incidents that meet our internal CAPA criteria — events that materially impact availability, reliability, or productivity.

# Category 1: Customer-Facing Failures
- Incidents where customers or end users cannot access key functionality, including (but not limited to):
- Contact form submissions not working
- Donate button or payment flow errors
- Primary site downtime or major content delivery failures
- Any issue that prevents a customer from successfully interacting with us

# Category 2: Development & Productivity Failures
- Incidents where internal teams experience sustained disruption to development workflows, such as:
- Broken or blocked development branches
- Failed or inconsistent builds across environments
- CI/CD failures that halt deployments
- Major tooling or infrastructure downtime impacting delivery velocity

# Eligibility & Ownership Rules
Items are added to this repository only when the specific team collectively agrees that:

- The issue cannot be resolved within the team's activites and
- The incident warrants postmortem documentation and preventive action.

CAPA entries may only be created or approved by Executive Team members.

# Handling Workflow

Immediate Triage

- Once a CAPA issue is opened, it is treated as a high-severity event.
- A member of the DevSecOps team and SWAT team should be assigned within minutes of creation (e.g., within 15–20 minutes).
- The assigned owner is responsible for initial validation and coordination with the affected team.

Collaborative Assignment
- Identify and tag the originating team (e.g., ML, Web, or API) within the comments.
- Ensure at least one technical representative from that team is added as an assignee or collaborator.
- Progress Tracking with Timestamps
- All updates must be logged as comments on the GitHub issue, including timestamps. (Even which member was contacted and when!)
- Once resolved, update the issue with - Summary of corrective actions taken and Preventive measures planned.


