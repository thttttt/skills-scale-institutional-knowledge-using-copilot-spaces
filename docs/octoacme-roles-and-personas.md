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

## UX/UI Designer or User Researcher

### Role Summary
UX/UI Designers and User Researchers own the user experience and validate design decisions through research and testing. They collaborate with Product Managers to ensure solutions meet user needs and with Developers and QA/Testing to ensure feasibility and testability.

### Responsibilities
- Conduct user research and usability testing
- Define user workflows, journeys, and information architecture
- Design and prototype user interfaces and interactions
- Develop and maintain design systems and guidelines
- Validate design acceptance criteria with stakeholders
- Collaborate on accessibility and inclusivity standards

### Goals
- Deliver intuitive, usable experiences that delight users
- Reduce design-to-development rework through clear specifications
- Ensure designs are technically feasible and testable
- Build consistency and efficiency through reusable design patterns

### Typical Communication
- Design reviews and feedback sessions with Product Managers and Developers
- Usability testing reports and insights
- Design specifications and component documentation
- Participation in planning and retrospectives

### Interaction with Existing Roles
- Works with **Product Managers** to understand customer needs and success metrics
- Partners with **Developers** and **QA/Testing** on feasibility, technical constraints, and testability
- Collaborates with **Technical Lead** on design system integration and scalability
- Provides input to **Project Managers** on design review milestones and timeline dependencies

---

## Technical Lead or Software Architect

### Role Summary
Technical Leads and Software Architects guide technical strategy, design decisions, and implementation standards. They partner with Developers, Product Managers, and Project Managers to balance scope, quality, and delivery constraints while identifying and mitigating technical risks.

### Responsibilities
- Define and document technical architecture and design patterns
- Guide technical decision-making and code review standards
- Identify and mitigate technical risks and dependencies
- Mentor Developers and ensure adherence to coding standards
- Collaborate with Security, Data/Analytics, and Release/DevOps on integration points
- Advocate for technical health and long-term maintainability

### Goals
- Enable scalable, maintainable, and performant systems
- Reduce technical debt and rework through sound design
- Accelerate delivery by providing clear technical direction
- Foster a culture of continuous learning and improvement

### Typical Communication
- Technical design reviews and architecture documentation
- Code review guidance and mentoring
- Risk registers and technical dependency tracking
- Planning sessions to assess feasibility and estimate effort

### Interaction with Existing Roles
- Partners with **Developers** on design, code reviews, and implementation standards
- Aligns with **Product Managers** and **Project Managers** on trade-offs between scope and technical quality
- Coordinates with **Security and Privacy Representative** on threat modeling and compliance
- Works with **Release/DevOps Engineer** on deployment architecture and monitoring
- Collaborates with **Data/Analytics Lead** on instrumentation and observability design

---

## Security and Privacy Representative

### Role Summary
Security and Privacy Representatives identify, assess, and mitigate security, privacy, compliance, and threat-modeling requirements. They work with Technical Lead, Developers, QA/Testing, and Release/DevOps to ensure controls and scans are addressed before release and incidents are escalated appropriately.

### Responsibilities
- Identify security, privacy, and compliance requirements
- Conduct threat modeling and security design reviews
- Define and validate security controls and testing standards
- Ensure security scanning and penetration testing in CI/CD pipelines
- Manage security incident escalation and response coordination
- Provide guidance on data protection, access control, and audit requirements

### Goals
- Prevent security and privacy breaches and data loss
- Ensure compliance with regulatory and organizational requirements
- Enable secure-by-design practices across all projects
- Build trust with customers and stakeholders

### Typical Communication
- Security design reviews and threat modeling sessions
- Security scanning and vulnerability reports
- Compliance and audit documentation
- Incident response and post-incident retrospectives

### Interaction with Existing Roles
- Works with **Technical Lead** and **Developers** on secure design and implementation
- Collaborates with **QA/Testing** on security test plans and validation
- Partners with **Release/DevOps Engineer** on security controls in deployment pipelines
- Coordinates with **Project Managers** on security milestones and risk escalation
- Provides requirements to **Product Managers** for feature acceptance criteria

---

## Data/Analytics Lead

### Role Summary
Data/Analytics Leads define instrumentation, measurement plans, and data quality expectations. They work with Product Managers and Project Managers to connect delivery outputs to measurable outcomes and with Developers to implement observability.

### Responsibilities
- Define success metrics and measurement plans
- Design data collection, logging, and analytics infrastructure
- Establish data quality standards and validation processes
- Create dashboards and reporting for stakeholders
- Analyze usage, performance, and business impact data
- Provide insights to inform prioritization and optimization decisions

### Goals
- Connect delivery to measurable business and customer outcomes
- Enable data-driven decision-making across teams
- Provide visibility into product health and usage patterns
- Reduce guesswork in feature prioritization and optimization

### Typical Communication
- Metrics and KPI specifications during planning
- Dashboard and reporting updates during execution
- Analytics insights and retrospective reviews
- Data validation and quality discussions with Developers

### Interaction with Existing Roles
- Collaborates with **Product Managers** and **Project Managers** to define and track success metrics
- Partners with **Developers** on instrumentation implementation and data quality
- Works with **Release/DevOps Engineer** on monitoring and observability infrastructure
- Provides insights to **UX/UI Designer** for usage pattern analysis
- Supports **Technical Lead** with performance and scalability data

---

## Release or DevOps Engineer

### Role Summary
Release and DevOps Engineers own deployment readiness, environments, CI/CD pipelines, monitoring, rollback plans, and operational handoffs. They coordinate with Developers, QA/Testing, Security, Project Managers, and Support/Operations during release and incident response.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and automation
- Manage deployment environments (staging, production, etc.)
- Ensure backup, disaster recovery, and rollback capabilities
- Monitor application health, performance, and availability
- Coordinate deployments and manage deployment windows
- Lead incident response and post-incident automation improvements
- Document runbooks and operational procedures

### Goals
- Enable fast, reliable, and repeatable deployments
- Maximize system availability and reduce mean time to recovery
- Reduce manual effort and human error through automation
- Support the full application lifecycle from build to production

### Typical Communication
- Deployment checklists and release notes coordination
- CI/CD pipeline status and quality gates
- Monitoring dashboards and alerting configurations
- Incident response coordination and post-incident reports

### Interaction with Existing Roles
- Works with **Developers** on CI/CD pipeline integration and deployment validation
- Coordinates with **QA/Testing** on staging environment setup and smoke tests
- Partners with **Security and Privacy Representative** on security scanning and compliance checks
- Collaborates with **Technical Lead** on architecture and scalability
- Coordinates with **Project Managers** on release timelines and deployment windows
- Supports **Customer Support/Operations Representative** with runbook documentation and operational handoffs
- Works with **Data/Analytics Lead** on monitoring and observability

---

## Customer Support or Operations Representative

### Role Summary
Customer Support and Operations Representatives contribute customer-impact insights, support readiness, runbooks, and feedback after release. They collaborate with Product Managers, Project Managers, Release/DevOps, and stakeholders to prepare communications and close the feedback loop.

### Responsibilities
- Gather and prioritize customer feedback and support insights
- Develop support documentation, runbooks, and FAQs
- Prepare customer-facing release notes and communications
- Support release readiness through UAT and training
- Monitor customer issues and escalate critical problems
- Facilitate post-release customer success and feedback loops
- Identify patterns in support requests for product improvement

### Goals
- Ensure customer success and satisfaction with features and releases
- Reduce support burden through clear documentation and proactive communication
- Create feedback loops that inform product and operational decisions
- Build customer trust and retention

### Typical Communication
- Support readiness documentation and training materials
- Customer feedback summaries and prioritization
- Release communication drafts and customer announcements
- Post-release customer issue reports and escalations

### Interaction with Existing Roles
- Collaborates with **Product Managers** and **Project Managers** on release readiness and customer impact
- Partners with **Release/DevOps Engineer** on runbook documentation and operational handoffs
- Works with **Developers** on feature documentation and technical FAQ
- Provides insights to **UX/UI Designer** on usability pain points from customer feedback
- Coordinates with all roles on customer communication and post-release support

---

## Business Sponsor or Executive Stakeholder

### Role Summary
Business Sponsors and Executive Stakeholders provide strategic direction, funding decisions, and escalation support for business-impacting risks. They work with Product Managers and Project Managers at decision gates and receive milestone updates and risk communications.

### Responsibilities
- Define business objectives and strategic priorities
- Allocate budget and resources to projects
- Approve scope changes and major decisions at decision gates
- Escalate and resolve business-level blockers and conflicts
- Communicate outcomes and impact to broader leadership
- Provide executive sponsorship for cross-functional coordination

### Goals
- Ensure project delivery aligns with business strategy
- Maximize return on investment for project initiatives
- Resolve strategic conflicts and enable bold decisions
- Build confidence and transparency with the board and customers

### Typical Communication
- Monthly or milestone-based status updates
- Decision gate reviews and approval meetings
- Risk escalation and mitigation discussions
- Business outcome reporting and learnings

### Interaction with Existing Roles
- Partners with **Product Managers** on strategy alignment and market priorities
- Works with **Project Managers** on decision gates, escalations, and resource approvals
- Receives risk and dependency information from **Project Managers**
- Provides strategic input to **Technical Lead** on long-term technology investments
- Supports **Release/DevOps Engineer** with infrastructure investment decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction sections to understand cross-functional dependencies and communication patterns.
- Use the responsibility and goal statements to clarify ownership and accountability across the project lifecycle.
