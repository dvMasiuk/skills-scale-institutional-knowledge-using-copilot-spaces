# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Project Delivery Roles

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Specialty & Cross-Functional Roles

## Delivery Lead

### Role Summary
The Delivery Lead owns day-to-day execution coordination, ensuring the team stays aligned with sprint commitments and manages on-the-ground risks and dependencies.

### Responsibilities
- Coordinate daily standups and sprint ceremonies
- Manage sprint commitments and track progress against milestones
- Identify and escalate blockers and dependencies in real-time
- Update and maintain the risk register
- Ensure team has clarity on priorities and acceptance criteria
- Coordinate handoffs between development, QA, and release phases

### Goals
- Keep the team focused and unblocked
- Reduce time-to-resolution for team-level blockers
- Maintain accurate, up-to-date project state

### Interactions
- **Works with**: Project Manager (overall execution plan), Product Manager (acceptance criteria and prioritization), Developers, QA, and Release Engineer
- **Escalates to**: Project Manager for scope or timeline issues; Product Manager for priority conflicts
- **Coordinates with**: SRE/On-call Lead for deployment windows and production readiness

### Typical Communication
- Daily standup facilitation
- Sprint review and planning
- Risk and blocker triage
- Handoff coordination with QA and release teams

---

## Engineering Manager

### Role Summary
Engineering Managers provide technical leadership, resource allocation, and support for the engineering team. They own hiring, mentoring, technical practices, and code quality standards.

### Responsibilities
- Allocate engineering resources and manage capacity planning
- Hire, mentor, and develop engineers
- Define and maintain technical standards and code quality practices
- Identify and mitigate technical risks and architectural issues
- Support individual contributors in professional growth
- Participate in capacity and effort estimation

### Goals
- Build a high-performing, skilled engineering team
- Ensure sustainable, maintainable technical practices
- Reduce technical debt and prevent critical issues

### Interactions
- **Works with**: Project Manager (on capacity and estimates), Developers (mentorship and technical guidance), Delivery Lead (identifying blockers)
- **Partners with**: Product Manager (on technical feasibility and trade-offs)
- **Supports**: Technical design reviews and architecture decisions

### Typical Communication
- One-on-ones with direct reports
- Engineering team syncs on technical practices
- Capacity planning and resource allocation
- Technical design reviews and RFCs

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers validate product decisions with real user feedback and ensure solutions are usable, accessible, and delightful.

### Responsibilities
- Conduct user research and validate product assumptions
- Create design specifications and wireframes
- Ensure accessibility standards are met (WCAG, etc.)
- Participate in user testing and iterate on designs
- Provide design guidance to developers during implementation
- Review features for usability before handoff to QA

### Goals
- Ensure features meet user needs and are easy to use
- Reduce usability-related bugs and support tickets
- Maintain accessibility and inclusive design standards

### Interactions
- **Works with**: Product Manager (on success criteria and user stories), Developers (design implementation), QA (usability validation)
- **Participates in**: Sprint planning, design reviews, and demos
- **Validates**: Acceptance criteria from a usability and accessibility perspective

### Typical Communication
- User research findings and insights
- Design specs and prototypes
- Design review feedback
- Accessibility and usability testing reports

---

## Observability / Monitoring Engineer

### Role Summary
Observability Engineers define metrics, set up dashboards and alerts, and ensure the team can measure the impact of delivered features and detect production issues.

### Responsibilities
- Define Service-Level Indicators (SLIs) and Service-Level Objectives (SLOs)
- Design and maintain dashboards for key product metrics
- Set up alerts and thresholds for critical issues
- Work with developers to instrument code for observability
- Run post-deployment verification and health checks
- Provide metrics and data for Product Manager success measurement

### Goals
- Enable data-driven decision-making
- Detect and diagnose production issues quickly
- Demonstrate product impact through metrics

### Interactions
- **Works with**: Developers (on instrumentation and metrics definition), SRE/On-call Lead (alerts and incident response)
- **Partners with**: Product Manager (on success metrics definition)
- **Supports**: Release validation and post-deploy verification

### Typical Communication
- Metrics and dashboard reviews
- Alert tuning and threshold adjustments
- Post-deploy health checks
- Performance analysis and trend reports

---

## SRE / On-call Lead

### Role Summary
Site Reliability Engineers (SREs) and On-call Leads ensure production systems remain stable and reliable. They coordinate incident response, maintain runbooks, and drive continuous improvement.

### Responsibilities
- Maintain production system reliability and uptime
- Coordinate incident response and triage
- Create and maintain runbooks and escalation procedures
- Manage on-call rotations and alert handling
- Drive post-incident retrospectives and root cause analysis
- Define and monitor SLOs with the team
- Collaborate on production readiness before releases

### Goals
- Minimize unplanned downtime and customer impact
- Enable rapid, effective incident response
- Drive continuous improvement in reliability

### Interactions
- **Works with**: Delivery Lead (on deployment windows and production readiness), Developers (on operational practices and instrumentation)
- **Notifies**: Project Manager and Stakeholders during incidents
- **Drives**: Post-incident retrospectives with full team
- **Partners with**: Observability Engineer (on metrics and alerts)

### Typical Communication
- On-call handoff notes
- Incident notifications and status updates
- Post-incident retrospectives
- Production readiness checklist reviews

---

## Release / CI Engineer

### Role Summary
Release and CI Engineers maintain deployment pipelines, automate release processes, and ensure reliable, repeatable deployments.

### Responsibilities
- Design and maintain CI/CD pipelines
- Automate testing, building, and deployment processes
- Manage rollback procedures and disaster recovery
- Coordinate release scheduling and deployment windows
- Ensure release documentation and runbooks are up-to-date
- Support security scanning and compliance checks in CI

### Goals
- Enable fast, safe, and repeatable deployments
- Reduce manual work and human error in releases
- Minimize deployment-related incidents

### Interactions
- **Coordinates with**: Developers (on CI pipeline requirements), Delivery Lead (on release scheduling), SRE (on deployment readiness and rollback)
- **Works with**: Project Manager (on release planning)
- **Supports**: Security and compliance teams on gate enforcement

### Typical Communication
- CI pipeline status and improvements
- Release notes and deployment procedures
- Smoke test results and deployment verification
- Incident communication during failed releases

---

## Compliance / Legal Reviewer

### Role Summary
Compliance and Legal Reviewers ensure that product changes align with regulatory requirements, data handling policies, and contractual obligations.

### Responsibilities
- Review product changes for regulatory risk (GDPR, HIPAA, SOC 2, etc.)
- Validate data handling and privacy practices
- Assess contractual and licensing implications
- Provide guidance on compliance requirements early in planning
- Maintain compliance documentation and evidence

### Goals
- Reduce regulatory and legal risk
- Ensure compliant, secure product delivery
- Avoid costly compliance violations or delays

### Interactions
- **Engages early**: During project planning when compliance-relevant scope is proposed
- **Works with**: Product Manager and Project Manager (on scope and timeline impact)
- **Reviews**: Feature specifications and data handling approaches
- **Escalates to**: Legal or Compliance leadership for complex or high-risk changes

### Typical Communication
- Compliance assessment reviews
- Risk assessments and mitigation recommendations
- Compliance documentation and attestations
- Regulatory change notifications

---

## Data Analyst

### Role Summary
Data Analysts define measurable success metrics, create dashboards, and analyze feature impact to drive product decisions and demonstrate ROI.

### Responsibilities
- Define and instrument success metrics aligned with product goals
- Create dashboards for tracking KPIs and feature adoption
- Analyze results post-release and provide insights
- Support A/B testing and experimentation
- Provide data to support feature validation and prioritization
- Ensure data quality and integrity

### Goals
- Make product decisions evidence-based
- Quantify feature impact and ROI
- Identify high-value optimization opportunities

### Interactions
- **Works with**: Product Manager (on metric definition and business outcomes), Observability Engineer (on metric collection and dashboard creation)
- **Analyzes**: Release impact and feature adoption
- **Informs**: Product roadmap and prioritization decisions

### Typical Communication
- Success metric definitions and tracking
- Post-release analysis and insights
- Feature adoption and usage reports
- Data quality and methodology documentation

---

## Support / Customer Success Liaison

### Role Summary
Support and Customer Success representatives are the voice of the customer, surfacing issues, feedback, and validation opportunities throughout the development process.

### Responsibilities
- Surface customer-impacting issues and bugs
- Gather and prioritize customer feedback for the roadmap
- Help validate fixes and new features with real customers
- Provide early access to features for customer testing
- Communicate feature updates and changes to customers
- Identify and resolve customer adoption barriers

### Goals
- Ensure customer needs are understood and prioritized
- Reduce customer-facing defects and support burden
- Drive feature adoption and customer satisfaction

### Interactions
- **Works with**: Product Manager (on customer feedback and prioritization), Developers (on bug investigation and reproduction)
- **Validates**: Fixes and features in staging or production with customers
- **Escalates**: Critical customer issues to the Delivery Lead or Project Manager
- **Supports**: Release announcements and customer communications

### Typical Communication
- Customer issue reports and feedback summaries
- Feature validation and testing feedback
- Customer communications and release announcements
- Support ticket trends and patterns

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning work, consider the full set of personas and their interactions to ensure comprehensive coverage and accountability.
