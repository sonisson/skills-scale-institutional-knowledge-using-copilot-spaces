# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes iterative delivery, clear ownership, and data-driven decision-making. The organization divides its project lifecycle into five primary phases: **Initiation** (validating new ideas through a lightweight one-pager to confirm business need and align stakeholders), **Planning** (breaking approved work into shippable increments with prioritized backlogs and acceptance criteria), **Execution & Tracking** (managing day-to-day delivery through daily standups and weekly syncs), **Release & Deployment** (governed by pre-release checklists, smoke testing, and rollback procedures), and **Close & Retrospective** (capturing learnings and converting them into actionable improvements).

At the heart of OctoAcme's execution model are three core roles with distinct responsibilities: **Project Managers** coordinate delivery activities and manage schedules, risks, and communications; **Product Managers** define what should be built and measure outcomes through customer and business value; and **Developers** implement features, write tests, and participate in design and code reviews. This role clarity is complemented by a consistent communication cadence including daily standups, weekly delivery syncs, weekly PM-to-PdM alignment, and monthly stakeholder updates, with risk escalation following a tiered path from team-level triage through PM, Product Lead, to sponsor-level escalation. Quality and observability are embedded throughout execution via small pull requests (≤400 lines), automated CI testing and linting, unit and integration tests, security scanning, and consistent tracking of velocity, burndown, and success metrics—enabling OctoAcme to deliver customer value reliably while maintaining psychological safety and organizational learning.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Named Project Manager and Product Lead for each project
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Documents

### 1. Project Management Overview
[📖 octoacme-project-management-overview.md](./octoacme-project-management-overview.md)

High-level introduction to OctoAcme's project approach, core roles, key artifacts, and communication cadence. Start here to understand the overall framework.

### 2. Project Initiation
[📖 octoacme-project-initiation.md](./octoacme-project-initiation.md)

Define initial steps to validate work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and decision gates for moving to planning.

### 3. Project Planning
[📖 octoacme-project-planning.md](./octoacme-project-planning.md)

Turn an approved initiative into an actionable plan and backlog for delivery. Covers backlog prioritization, estimation, Definition of Done, and risk identification.

### 4. Execution & Tracking
[📖 octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)

Guidance for managing day-to-day execution and tracking progress toward project milestones. Covers team rhythm, PR workflows, quality assurance, and blocker escalation.

### 5. Risk Management & Communication
[📖 octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)

Identify, manage, and communicate risks and dependencies across the project. Includes risk register template, stakeholder communication strategies, and escalation paths.

### 6. Release & Deployment
[📖 octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)

Standardize how OctoAcme releases features to production to reduce risk and improve observability. Covers release types, pre-release requirements, deployment checklists, and rollback procedures.

### 7. Retrospective & Continuous Improvement
[📖 octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)

Capture learnings and convert them into actionable improvements. Covers retrospective structure, running effective retrospectives, and tracking improvements.

### 8. Roles & Personas
[📖 octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)

Defines typical roles and responsibilities used in OctoAcme project docs and exercises, including Developers, Product Managers, and Project Managers.

## Quick Start for New Team Members

1. **Get oriented**: Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand OctoAcme's framework and key roles
2. **Understand your role**: Check [Roles & Personas](./octoacme-roles-and-personas.md) to learn about key responsibilities and communication patterns
3. **Find your phase**: Reference the appropriate process document(s) based on your project phase:
   - Starting a new project? → [Project Initiation](./octoacme-project-initiation.md)
   - Planning upcoming work? → [Project Planning](./octoacme-project-planning.md)
   - Delivering features? → [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - Managing risks? → [Risk Management & Communication](./octoacme-risks-and-communication.md)
   - Preparing a release? → [Release & Deployment](./octoacme-release-and-deployment.md)
   - Wrapping up a project? → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Updating These Docs

To suggest updates or additions to OctoAcme's process documentation, use the [Process Doc Update issue template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
