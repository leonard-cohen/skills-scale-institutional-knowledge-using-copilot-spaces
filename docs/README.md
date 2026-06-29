# OctoAcme Project Management Documentation

## Overview

Welcome to OctoAcme's Project Management Docs. These documents provide standardized guidance for running cross-functional projects from initiation through retrospective, emphasizing customer value, iterative delivery, and data-informed decisions.

OctoAcme follows a structured, lifecycle-based approach to project management that ensures every project has explicit stakeholder alignment and measurable outcomes. Our methodology is organized around five key phases: **Initiation** (validate business need and create a lightweight Project One-pager), **Planning** (break work into prioritized backlog items with clear acceptance criteria), **Execution** (coordinate delivery through disciplined team rhythms and structured workflows), **Release** (standardize deployments to reduce risk and improve observability), and **Retrospective** (capture learnings and convert them into actionable improvements).

Execution at OctoAcme is coordinated through a disciplined team rhythm that includes daily standups (15 minutes) focused on progress and blockers, weekly delivery syncs to track advancement and flag risks, and regular demos. We use GitHub Projects to maintain visibility across work stages and enforce small pull requests (≤400 lines) with automated CI testing and linting before review. Quality is ensured through unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. A three-level blocker escalation process ensures that impediments are surfaced and resolved quickly.

The organization defines clear roles and responsibilities to enable accountability and smooth collaboration. **Project Managers** coordinate delivery, manage schedules, risks, and communications; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; **Developers** implement features, write tests, and identify technical risks. Weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, and monthly stakeholder updates create a consistent communication cadence. Risk management is continuous, with a Risk Register maintained throughout the project and reviewed weekly. Release and continuous improvement are baked into our operating model—teams complete pre-release requirements including security scans and rollback plans, and conduct retrospectives after each sprint or milestone to capture learnings and generate prioritized action items.

## Quick Start

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles, roles, and key artifacts.

## Process Guides by Lifecycle Stage

### 1. Project Initiation
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, create a project one-pager, and make the go/no-go decision for planning.

### 2. Project Planning
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, define acceptance criteria, estimate scope, identify dependencies, and create a release plan.

### 3. Execution & Tracking
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, maintain quality standards, track velocity, ensure pull request quality, and escalate blockers.

### 4. Risk Management & Communication
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify and manage risks, maintain the risk register, and communicate status to stakeholders using templates and escalation paths.

### 5. Release & Deployment
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize releases, use deployment checklists, manage rollbacks, maintain release notes, and ensure post-deploy verification.

### 6. Retrospective & Continuous Improvement
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, run effective retros, track improvement action items, and measure impact of changes.

## Reference

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of Project Managers, Product Managers, Developers, and other key roles used across OctoAcme projects.

## Key Principles

- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments.
- **Clear ownership**: Each project has a named PM and Product Lead.
- **Data-informed**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning.

## Core Roles at a Glance

| Role | Responsibility | Key Goals |
|------|---|---|
| **Project Manager** | Coordinates delivery, manages schedules, risks, and communications | Deliver projects on time, minimize escalations, maintain transparency |
| **Product Manager** | Defines outcomes, prioritizes backlog, measures success | Maximize customer value, make data-driven decisions, ensure product-market fit |
| **Developer** | Implements features, writes tests, identifies technical risks | Deliver reliable code, reduce cycle time, maintain high test coverage |
| **QA/Testing** | Validates quality and acceptance criteria | Ensure feature acceptance, catch regressions, maintain quality standards |

## Communication Cadence

- **Daily**: Standups (15 min) — progress, blockers, dependencies
- **Weekly**: Delivery sync — progress update, risks, and flags
- **Weekly**: PM + Product Manager alignment — roadmap, priorities, outcomes
- **Monthly**: Stakeholder updates — status, metrics, decisions needed
- **Ad-hoc**: Escalations as needed

## Getting Started

1. If you're **starting a new project**, begin with [Project Initiation](./octoacme-project-initiation.md) to create your Project One-pager.
2. If you're **in the planning phase**, use [Project Planning](./octoacme-project-planning.md) to organize your backlog and milestones.
3. If you're **executing**, refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day guidance and quality standards.
4. If you're **preparing to release**, follow [Release & Deployment](./octoacme-release-and-deployment.md) to ensure a smooth rollout.
5. If you're **reflecting on a project**, use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and action items.

## Questions or Updates?

To propose new content or updates to these process docs, please use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
