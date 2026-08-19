# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

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

## Delivery Lead / Engineering Lead

### Role Summary
The Delivery Lead (also referred to as Engineering Lead) is accountable for the day-to-day execution of delivery commitments. They bridge the gap between project management and engineering, ensuring that technical work aligns with sprint goals and release milestones.

### Responsibilities
- Own the delivery cadence and track progress against sprint and release goals
- Identify and resolve cross-team dependencies and blockers
- Communicate delivery risks and trade-offs to the Project Manager and stakeholders
- Coordinate with QA/Testing to ensure readiness gates are met before releases
- Support developers in breaking down work and maintaining a healthy backlog

### Goals
- Predictable, on-time delivery of committed scope
- Reduced dependency-related delays and escalations
- Clear visibility into delivery health for the whole team

### Inputs Needed from Other Roles
- Prioritized backlog and acceptance criteria from Product Manager
- Scope, timelines, and constraints from Project Manager
- Technical risk signals and estimates from Developers

### Decisions and Approvals Owned
- Scope adjustments within a sprint when blockers arise
- Escalation decisions when delivery commitments are at risk

### Typical Communication
- Daily standups and sprint reviews with Developers and QA/Testing
- Weekly delivery status syncs with Project Manager and Product Manager
- Dependency logs and risk updates

---

## Scrum Master / Iteration Facilitator

### Role Summary
The Scrum Master facilitates agile ceremonies and coaches the team on iterative delivery practices. They protect the team from process friction and help create an environment where continuous improvement is possible.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove organizational impediments that slow the team down
- Coach team members on agile practices and principles
- Track team metrics (velocity, cycle time) and surface insights
- Escalate systemic issues to the Project Manager or Delivery Lead

### Goals
- High-functioning, self-organizing team
- Continuous improvement in team practices and predictability
- Reduced waste and friction in the delivery process

### Inputs Needed from Other Roles
- Team health signals and impediment reports from Developers
- Strategic context and upcoming changes from Project Manager and Product Manager
- Retrospective feedback from all team members

### Decisions and Approvals Owned
- Facilitation approach for ceremonies
- Process experiment proposals for retrospective action items

### Typical Communication
- Daily touchpoints with Developers and Delivery Lead
- Regular syncs with Project Manager on systemic blockers
- Retrospective outputs shared with the broader team

---

## Product Operations / Program Analyst

### Role Summary
The Product Operations or Program Analyst supports the Product Manager and Project Manager by managing data, operational processes, and cross-functional coordination. They ensure the right information flows to the right people at the right time.

### Responsibilities
- Maintain dashboards, reports, and operational metrics for project and product health
- Coordinate intake processes and triage of new requests with Product Manager and Project Manager
- Document decisions, meeting notes, and action items
- Identify process gaps and propose improvements
- Support stakeholder communications with data and status summaries

### Goals
- High-quality operational data for decision-making
- Consistent and efficient processes across the program
- Reduced administrative burden on Product Manager and Project Manager

### Inputs Needed from Other Roles
- Status updates and risk data from Project Manager and Delivery Lead
- Feature and roadmap data from Product Manager
- Metrics and telemetry from Developers

### Decisions and Approvals Owned
- Process and tooling recommendations for operational improvements
- Reporting cadence and format decisions

### Typical Communication
- Regular syncs with Project Manager and Product Manager
- Async reporting to stakeholders via dashboards or status emails
- Working sessions with Developers and QA/Testing to gather data

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness, deployment sequencing, and go-live communications. They act as the single point of coordination between engineering, QA/Testing, and stakeholders for every production release.

### Responsibilities
- Define and maintain the release calendar in alignment with the Project Manager
- Coordinate release readiness reviews with Developers, QA/Testing, and the Delivery Lead
- Manage release checklists, go/no-go criteria, and deployment runbooks
- Communicate release scope, timelines, and post-release status to stakeholders
- Lead rollback decisions if critical issues arise post-deployment

### Goals
- Safe, predictable, and well-communicated production releases
- Minimal unplanned downtime or release-related incidents
- Clear audit trail of release approvals and deployment decisions

### Inputs Needed from Other Roles
- QA sign-off and test results from QA/Testing
- Deployment readiness confirmation from Developers and Delivery Lead
- Scope and priority guidance from Product Manager and Project Manager

### Decisions and Approvals Owned
- Go/no-go decision for production deployments
- Rollback initiation in response to post-release incidents

### Typical Communication
- Pre-release coordination meetings with QA/Testing and Developers
- Release notes and go-live announcements to stakeholders
- Post-release incident reports when needed

---

## UX / Design Lead

### Role Summary
The UX/Design Lead is responsible for the end-to-end user experience of the product. They translate user needs and product requirements into designs that are validated, accessible, and implementable by the development team.

### Responsibilities
- Conduct user research and translate findings into design decisions
- Create wireframes, prototypes, and high-fidelity designs for new features
- Define and maintain the design system and UX standards
- Collaborate with the Product Manager to align design with product strategy
- Partner with Developers to ensure faithful implementation of designs
- Participate in QA reviews to validate UX quality before release

### Goals
- Intuitive, accessible, and consistent user experiences
- Design decisions grounded in user research and data
- Reduced implementation rework through clear design specifications

### Inputs Needed from Other Roles
- Problem statements and success metrics from Product Manager
- Technical constraints and feasibility feedback from Developers
- Acceptance criteria and release timelines from Project Manager and Delivery Lead

### Decisions and Approvals Owned
- Design direction and UX standards for the product
- Approval of final designs before handoff to development

### Typical Communication
- Design reviews and critique sessions with Product Manager and Developers
- Usability testing readouts shared with stakeholders
- Design handoff documentation and annotated specs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

