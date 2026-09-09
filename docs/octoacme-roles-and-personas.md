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

## Technical Lead / Architect

### Role Summary
Technical Leads provide strategic technical direction, design guidance, and risk mitigation for complex features and integrations. They collaborate with developers and product leads to ensure solutions are scalable, maintainable, and aligned with system architecture. They typically own technical design decisions, architectural standards, and escalation paths for engineering risks that affect delivery.

### Responsibilities
- Review technical designs and propose architectural improvements
- Identify technical risks, dependencies, and mitigation strategies
- Guide code review and quality standards
- Mentor developers and conduct design reviews
- Collaborate with DevOps on deployment and scalability concerns

### Goals
- Ensure technical excellence and long-term system health
- Reduce rework due to poor architectural decisions
- Enable faster delivery through clear technical guidance
- Measure success through lower architectural rework, fewer unresolved technical risks, and steady delivery of maintainable solutions

### Typical Communication
- Design review meetings and code review comments
- Technical dependency and risk escalation with project leadership
- Architecture documentation and decision logs
- Regular touchpoints during planning, implementation, and technical retrospectives

### Interactions with Existing Roles
- Works with Developers to translate architectural decisions into implementation
- Partners with Project Managers on technical risk escalation and timeline impact
- Advises Product Managers on technical feasibility and trade-offs

---

## Quality Assurance Lead

### Role Summary
QA Leads own the testing strategy, validate acceptance criteria, and establish quality gates for releases. They work closely with product, development, and operations to ensure software quality and user acceptance. They typically have authority to recommend release readiness decisions based on test evidence, defect severity, and quality thresholds.

### Responsibilities
- Define test strategy and testing approach (unit, integration, end-to-end, smoke tests)
- Create and maintain test plans and test cases
- Validate acceptance criteria before marking work as done
- Execute manual QA when needed and identify defects
- Establish quality metrics and monitor them throughout the project
- Advise on release readiness and quality gates

### Goals
- Catch defects early and reduce production incidents
- Ensure features meet user expectations and acceptance criteria
- Provide confidence in release quality
- Measure success through defect escape rates, test coverage, and release readiness outcomes

### Typical Communication
- QA review during sprint planning, implementation, and acceptance
- Test reports and defect logs
- Release readiness reviews and post-release validation
- Ongoing communication of quality blockers and regression risk to project leadership

### Interactions with Existing Roles
- Collaborates with Developers to define testable acceptance criteria and review test coverage
- Reports quality metrics and blockers to Project Managers
- Works with Product Managers to validate feature acceptance

---

## DevOps / Release Manager

### Role Summary
DevOps and Release Managers manage infrastructure, deployment pipelines, and coordinate releases across development, staging, and production environments. They ensure safe, repeatable deployments and maintain system reliability. They typically own operational readiness, deployment approvals within agreed controls, and escalation during release events.

### Responsibilities
- Manage CI/CD pipelines and automated testing infrastructure
- Coordinate staging and production deployments
- Monitor deployments and handle rollbacks if necessary
- Maintain deployment documentation and runbooks
- Coordinate with on-call engineers and incident response
- Ensure security scanning and compliance checks in the deployment pipeline

### Goals
- Minimize deployment risk and downtime
- Enable fast, safe releases to production
- Maintain system reliability and observability
- Measure success through deployment frequency, change failure rate, and recovery time

### Typical Communication
- Release coordination meetings and deployment windows
- Runbook and infrastructure documentation
- Incident escalation and post-incident reviews
- Frequent status updates around release readiness across environments

### Interactions with Existing Roles
- Partners with Developers on pipeline improvements and deployment troubleshooting
- Coordinates with Project Managers on release schedules and deployment readiness
- Supports Product Managers with production monitoring and incident updates

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and approval for scope, budget, and major decisions. They represent customer interests, business goals, and organizational priorities. They typically have decision authority over funding, strategic alignment, priority trade-offs, and executive communications.

### Responsibilities
- Define business objectives and success criteria
- Approve project scope, timeline, and budget
- Provide customer and market insights
- Escalate and resolve priority conflicts
- Communicate project status to executive leadership
- Make trade-off decisions when needed

### Goals
- Ensure project aligns with business strategy
- Maximize ROI and customer value
- Provide air cover and remove organizational blockers
- Measure success through business outcomes, stakeholder alignment, and timely resolution of escalations

### Typical Communication
- Monthly stakeholder reviews and executive updates
- Scope and priority approval meetings
- Escalation and decision logs
- Scheduled milestone reviews with project leadership and product owners

### Interactions with Existing Roles
- Provides strategic direction and approval authority to Project Managers
- Collaborates with Product Managers on business objectives and prioritization
- Receives status updates and escalations from project leadership

---

## UX / Design Lead

### Role Summary
UX and Design Leads ensure user experience excellence and design consistency across features. They collaborate with product, development, and QA to validate usability and brand alignment. They typically guide design decisions, approve design direction, and escalate usability risks that could affect adoption or customer satisfaction.

### Responsibilities
- Design user interfaces and user workflows
- Conduct usability testing and gather user feedback
- Validate designs against acceptance criteria and brand standards
- Create design system documentation and reusable components
- Review feature implementations for design fidelity
- Identify and mitigate usability risks

### Goals
- Deliver delightful, intuitive user experiences
- Reduce support load through better UX
- Maintain consistent brand and design standards
- Measure success through usability feedback, design consistency, and reduced friction in key user flows

### Typical Communication
- Design review meetings and feedback sessions
- Usability testing reports and user research findings
- Design documentation and style guide updates
- Regular checkpoints during discovery, implementation, and release validation

### Interactions with Existing Roles
- Collaborates with Developers on implementation of design specifications
- Works with Product Managers to ensure designs align with product goals
- Partners with Project Managers to integrate design review into delivery timelines

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers advise on security requirements, compliance controls, and threat mitigation throughout the project lifecycle. They ensure features meet security standards and regulatory requirements. They typically guide security control decisions, recommend remediation priorities, and escalate issues that could block release or expose the organization to compliance risk.

### Responsibilities
- Identify security requirements and threat risks
- Review designs and code for security vulnerabilities
- Ensure compliance with regulatory and internal security policies
- Advise on data privacy, authentication, and authorization
- Conduct or coordinate security reviews and penetration testing
- Escalate security incidents and coordinate incident response

### Goals
- Prevent security breaches and data leaks
- Ensure regulatory and compliance adherence
- Build customer trust through secure, reliable features
- Measure success through fewer critical findings, timely remediation, and successful audit outcomes

### Typical Communication
- Security review gates in sprint planning and release
- Security incident escalation and response
- Compliance audit reports and policy documentation
- Regular reporting on security risks, remediation status, and control readiness

### Interactions with Existing Roles
- Reviews technical designs and code with Developers for security vulnerabilities
- Advises Project Managers on security-related risks and mitigation timelines
- Provides compliance and security context to Product Managers for prioritization

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
