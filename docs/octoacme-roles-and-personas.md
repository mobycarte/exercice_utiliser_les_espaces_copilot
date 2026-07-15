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

## Additional Personas

### Release Coordinator

#### Role Summary
Release Coordinators orchestrate the end-to-end release process across teams. They ensure all readiness requirements are met, coordinate approvals, and manage rollback procedures to enable smooth, predictable deployments.

#### Responsibilities
- Coordinate release schedules across engineering, product, and platform teams
- Validate deployment readiness across all dimensions (code, infrastructure, communication)
- Own runbook updates, rollback procedures, and post-release validation
- Communicate release timelines to stakeholders and manage expectations
- Facilitate release meetings and resolve blockers

#### Goals
- Enable predictable, on-time releases with minimal risk
- Reduce time-to-rollback and incident resolution time
- Ensure clear communication across all release stakeholders

#### Interactions
- **Product Manager**: Align on release scope and customer impact
- **Engineering Lead**: Validate code readiness and deployment procedures
- **QA Lead**: Confirm testing completion and sign-off
- **Platform Engineer**: Ensure infrastructure readiness and capacity
- **Project Manager**: Coordinate timeline and stakeholder communication

#### Typical Communication
- Release readiness checklists and sign-offs
- Release notes and deployment procedures
- Incident reports and post-mortems

---

### Platform/Infrastructure Owner

#### Role Summary
Platform/Infrastructure Owners maintain platform health and stability. They define SLAs, approve infrastructure changes, manage capacity planning, and provide guardrails for safe deployments.

#### Responsibilities
- Define and monitor SLAs for platform services and infrastructure
- Approve infrastructure changes and deployments
- Own capacity planning, scaling strategy, and cost optimization
- Maintain runbooks and incident response procedures
- Conduct infrastructure reviews and performance audits

#### Goals
- Maximize platform reliability and uptime
- Enable rapid, safe deployments through scalable infrastructure
- Optimize resource utilization and cost efficiency

#### Interactions
- **Engineering Leads**: Review technical designs and deployment plans
- **Release Coordinator**: Provide infrastructure readiness assessment
- **Security Liaison**: Collaborate on security architecture reviews
- **Developers**: Advise on infrastructure best practices and constraints

#### Typical Communication
- Infrastructure capacity reports and SLA metrics
- Change approval documents and deployment procedures
- Architecture review meetings and incident reports

---

### Security Liaison

#### Role Summary
Security Liaisons embed security practices into the development and release process. They perform threat assessments, ensure compliance requirements are met, and coordinate vulnerability management.

#### Responsibilities
- Perform threat assessments and security reviews for features and infrastructure changes
- Ensure security checklists are completed before release
- Coordinate vulnerability identification, prioritization, and remediation
- Maintain security documentation and compliance procedures
- Advise on secure coding practices and architectural decisions

#### Goals
- Reduce security vulnerabilities and compliance risks
- Enable secure development without blocking delivery
- Build security awareness across the organization

#### Interactions
- **Engineering**: Review designs, code, and propose security enhancements
- **QA Lead**: Coordinate security testing and validation
- **Product Manager**: Ensure security requirements align with feature scope
- **Release Coordinator**: Provide security sign-off for releases
- **Platform/Infrastructure Owner**: Review security architecture and controls

#### Typical Communication
- Security review checklists and threat assessments
- Vulnerability reports and remediation plans
- Security architecture decisions and compliance updates

---

### Product Operations (Product Ops)

#### Role Summary
Product Operations professionals manage the operational side of product delivery. They coordinate release communications, track metrics, and ensure stakeholders have visibility into product performance and outcomes.

#### Responsibilities
- Manage release communications and stakeholder reporting
- Track and report on key product metrics and health indicators
- Coordinate cross-team communication during releases and incidents
- Maintain product documentation and process consistency
- Support retrospectives and continuous improvement initiatives

#### Goals
- Ensure clear, timely communication to all stakeholders
- Provide data-driven insights into product performance
- Reduce information asymmetries across teams

#### Interactions
- **Product Manager**: Report on metrics and coordinate product updates
- **Release Coordinator**: Manage release notifications and communications
- **Project Manager**: Track timelines and deliverables
- **Communications**: Coordinate external messaging and announcements

#### Typical Communication
- Release announcements and stakeholder updates
- Product metrics dashboards and performance reports
- Meeting facilitation and minutes

---

### Customer Success Representative

#### Role Summary
Customer Success Representatives serve as the voice of the customer within the organization. They surface customer-impacting issues, escalate critical problems, and help prioritize work based on customer needs.

#### Responsibilities
- Surface customer-impacting issues and escalate urgent problems
- Coordinate with Product and Engineering to understand customer impact
- Participate in prioritization discussions for customer-facing bugs and features
- Contribute to incident reviews to prevent customer impact
- Provide customer feedback and usage insights to inform product decisions

#### Goals
- Minimize customer-impacting incidents and reduce resolution time
- Ensure customer voice is represented in prioritization
- Build strong customer relationships and satisfaction

#### Interactions
- **Product Manager**: Report customer feedback and impact assessments
- **Engineering Lead**: Coordinate on urgent customer-impacting issues
- **Release Coordinator**: Notify of customer-critical deployments and changes
- **Project Manager**: Escalate urgent customer needs

#### Typical Communication
- Customer issue reports and severity assessments
- Customer feedback summaries and usage insights
- Incident reviews and impact assessments

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Interactions section when designing workflows or communication procedures to ensure all necessary stakeholders are involved.
