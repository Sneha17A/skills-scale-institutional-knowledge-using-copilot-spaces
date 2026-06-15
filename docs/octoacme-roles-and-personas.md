# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

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

### Key Interactions
- **Product Managers**: Collaborate on acceptance criteria and feature specs
- **Project Managers**: Participate in planning and risk identification
- **QA/Testing**: Partner on test strategies and acceptance validation
- **Security Reviewer**: Incorporate security feedback into implementations
- **Design Lead**: Align on design handoff and implementation details

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

### Key Interactions
- **Project Managers**: Align on priorities and timelines
- **Developers**: Define requirements and acceptance criteria
- **Data Analyst / Insights Owner**: Collaborate on success metrics and validation
- **Customer Success Liaison**: Incorporate customer feedback and adoption signals

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

### Key Interactions
- **Product Managers**: Coordinate on roadmap and delivery schedules
- **Developers**: Track progress and manage blockers
- **Release Engineer / DevOps Lead**: Coordinate release planning and deployment
- **All personas**: Escalate risks and communicate project status

---

## QA/Testing

### Role Summary
QA and Testing teams validate that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Create and execute test plans aligned with acceptance criteria
- Validate feature functionality and edge cases
- Report defects and track resolution
- Participate in quality metrics and coverage goals
- Provide feedback on testability during design and development

### Goals
- Ensure high-quality releases
- Reduce defects reaching production
- Enable rapid, confident delivery

### Typical Communication
- Acceptance criteria review meetings
- Defect reports and test summaries
- Sprint planning and retrospectives

### Key Interactions
- **Developers**: Partner on test strategies and defect resolution
- **Product Managers**: Clarify acceptance criteria and validation approach
- **Accessibility Advocate**: Validate accessibility compliance
- **Design Lead**: Verify design implementation and usability

---

## Additional Personas

These personas represent important cross-cutting concerns and stakeholder viewpoints that influence project delivery.

---

## Design Lead

### Role Summary
Design Leads own the user experience strategy, create user flows and wireframes, and provide final design acceptance for features. They ensure usability and accessibility are built in from the start.

### Responsibilities
- Define UX strategy and design direction aligned with product goals
- Create user flows, wireframes, and design specifications
- Conduct design reviews and provide feedback on implementations
- Ensure design consistency across the product
- Collaborate on accessibility and usability standards
- Provide final design sign-off before development or QA

### Goals
- Deliver intuitive, accessible user experiences
- Reduce design-to-implementation friction
- Maintain visual and interaction consistency
- Improve user satisfaction and adoption

### Typical Communication
- Design kickoff and review meetings
- Design spec handoff to Developers
- Design QA reviews with QA/Testing team
- Accessibility and usability feedback

### Key Interactions
- **Developers**: Provide design specs and review implementation fidelity
- **Product Managers**: Align on user research and feature priorities
- **QA/Testing**: Validate design implementation and usability
- **Accessibility Advocate**: Ensure accessible design patterns
- **Customer Success Liaison**: Incorporate user feedback into design iterations

---

## Security Reviewer

### Role Summary
Security Reviewers assess planned changes for security and compliance impact, review security scanning results, and provide remediation guidance. They ensure security is considered throughout the project lifecycle.

### Responsibilities
- Review designs and feature plans for security implications
- Evaluate security scanning results and vulnerability reports
- Define remediation guidance and security best practices
- Provide sign-off on security readiness for releases
- Participate in threat modeling and risk assessment
- Support security incidents and post-incident reviews

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness into development practices
- Maintain compliance with security standards and regulations
- Reduce security-related incidents and rework

### Typical Communication
- Security design reviews during planning
- PR and code review feedback
- Vulnerability assessment and remediation plans
- Release security sign-off

### Key Interactions
- **Developers**: Review code and implementations for security concerns
- **Project Managers**: Escalate security risks and track remediation
- **Release Engineer / DevOps Lead**: Coordinate production controls and monitoring
- **All personas**: Provide security guidance and best practices

---

## Data Analyst / Insights Owner

### Role Summary
Data Analysts / Insights Owners define success metrics, instrument feature tracking, and validate data quality for launches. They ensure projects are measured and optimized based on evidence.

### Responsibilities
- Collaborate with Product Managers to define success metrics and KPIs
- Design telemetry and instrumentation for feature tracking
- Validate data quality and completeness before and after launch
- Analyze feature adoption and impact post-release
- Provide dashboards and reporting for stakeholder visibility
- Identify optimization opportunities based on data

### Goals
- Ensure all features have clear, measurable success criteria
- Enable data-driven decisions and prioritization
- Reduce guesswork in feature validation
- Support continuous improvement through metrics

### Typical Communication
- Metric definition workshops during planning
- Data instrumentation specs for Developers
- Post-launch metric reviews and dashboards
- Weekly or milestone-based reporting to PdM and PM

### Key Interactions
- **Product Managers**: Define and validate success metrics
- **Developers**: Collaborate on telemetry and data collection
- **Project Managers**: Provide data-driven project health insights
- **Customer Success Liaison**: Analyze adoption and customer impact signals

---

## Customer Success Liaison

### Role Summary
Customer Success Liaisons represent customer needs and feedback throughout the project, surface adoption signals, and ensure communications reach customers effectively. They bridge the gap between the product team and end users.

### Responsibilities
- Represent customer needs and feedback in prioritization and design
- Surface customer pain points and feature requests from support and accounts
- Participate in acceptance criteria and usability validation
- Author customer-facing release notes and rollout communications
- Monitor adoption signals and customer satisfaction post-launch
- Coordinate with Support for operational and customer success planning

### Goals
- Ensure features solve real customer problems
- Accelerate customer adoption and satisfaction
- Reduce support burden through clear communication
- Enable proactive customer success outcomes

### Typical Communication
- Kickoff and planning meetings with customer perspective
- Acceptance criteria and usability validation
- Release planning and communication drafting
- Post-launch adoption and customer impact reviews

### Key Interactions
- **Product Managers**: Provide customer feedback and adoption insights
- **Developers**: Clarify customer use cases and edge cases
- **Design Lead**: Validate design usability for target customers
- **Release Engineer / DevOps Lead**: Plan customer communication rollout
- **Project Managers**: Highlight customer-related risks and dependencies

---

## Release Engineer / DevOps Lead

### Role Summary
Release Engineers and DevOps Leads manage release pipelines, deployment strategies, and rollback procedures. They ensure reliable, safe releases and operational readiness.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Create release plans and deployment checklists
- Manage staging and production environment health
- Define rollback procedures and incident response protocols
- Coordinate deployment timing and communication
- Monitor production health and support incident triage

### Goals
- Enable fast, safe, reliable releases
- Minimize deployment-related incidents and downtime
- Reduce manual intervention and human error in releases
- Support rapid iteration and continuous delivery

### Typical Communication
- Release planning and deployment coordination meetings
- Pre-deployment readiness reviews
- Post-deployment verification and health checks
- Incident response and retrospectives

### Key Interactions
- **Developers**: Integrate code changes and manage deployment pipeline
- **Project Managers**: Coordinate release timing and communication
- **Security Reviewer**: Implement production controls and security checks
- **QA/Testing**: Run smoke tests and validate deployments
- **Customer Success Liaison**: Coordinate customer communication timing

---

## Accessibility Advocate

### Role Summary
Accessibility Advocates ensure features meet accessibility standards and best practices. They review requirements, provide remediation guidance, and verify acceptance for accessibility criteria.

### Responsibilities
- Review feature requirements and designs for accessibility compliance
- Provide guidance on accessible design patterns and implementations
- Define accessibility acceptance criteria and test plans
- Conduct accessibility reviews and audits
- Advocate for inclusive design practices
- Support accessibility testing and remediation

### Goals
- Ensure products are usable by people with disabilities
- Build accessibility into the design and development process from the start
- Reduce accessibility-related rework
- Maintain compliance with accessibility standards (WCAG, Section 508)

### Typical Communication
- Accessibility requirements and guidance during planning
- Design review feedback and recommendations
- Accessibility acceptance criteria and test plans
- Remediation and verification during QA

### Key Interactions
- **Design Lead**: Ensure accessible design patterns and implementations
- **Developers**: Provide accessible implementation guidance and review
- **QA/Testing**: Validate accessibility compliance and edge cases
- **Product Managers**: Advocate for accessibility prioritization
- **All personas**: Promote accessibility awareness and best practices

---

## Stakeholders

### Role Summary
Stakeholders include business leaders, sponsors, and other parties with vested interest in project outcomes. They provide strategic direction, approval, and visibility into project progress.

### Responsibilities
- Provide business context and strategic alignment
- Approve project scope, timeline, and budget
- Escalate cross-organizational dependencies and risks
- Review project status and outcomes
- Make trade-off decisions when needed

### Goals
- Ensure projects deliver business value
- Maintain alignment with organizational strategy
- Enable informed decision-making
- Reduce surprises and project-related risks

### Typical Communication
- Project charter and one-pager review
- Monthly or milestone-based status updates
- Escalation of critical risks and decisions
- Project closeout and retrospectives

### Key Interactions
- **Project Managers**: Receive status updates and escalations
- **Product Managers**: Collaborate on strategic priorities
- **All personas**: Provide direction and visibility

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the **Key Interactions** section to understand handoff points and collaboration patterns.
- Use the **Responsibilities** and **Goals** sections to align on role expectations and success criteria.

---

## RACI Matrix Example

For a typical feature release, responsibilities may align as follows:

| Activity | PdM | PM | Dev | QA | Design | Security | Data | CS | DevOps |
|----------|-----|----|----|----|----|----------|------|-------|--------|
| Define requirements | R | C | C | C | C | - | - | C | - |
| Design UX/UI | C | - | C | - | R | C | - | C | - |
| Security review | - | - | R | - | - | R | - | - | - |
| Define metrics | R | - | - | - | - | - | R | C | - |
| Implement feature | - | - | R | C | C | C | - | - | - |
| Testing & QA | - | - | C | R | C | - | - | - | - |
| Deploy to staging | - | - | C | - | - | - | - | - | R |
| Smoke testing | - | - | - | C | - | - | - | - | R |
| Production deploy | - | C | - | - | - | - | - | C | R |
| Monitor & support | - | - | - | - | - | - | C | C | R |

**Legend:** R = Responsible, A = Accountable, C = Consulted, I = Informed
