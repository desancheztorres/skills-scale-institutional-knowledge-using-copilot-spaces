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

## Product Owners

### Role Summary
Product Owners serve as the voice of the customer and business, translating high-level product vision into actionable user stories and acceptance criteria. They work closely with Product Managers on strategy while focusing on sprint-level execution and stakeholder engagement.

### Responsibilities
- Refine and prioritize the sprint backlog based on customer and business needs
- Write detailed user stories with clear acceptance criteria
- Answer team questions about requirements during execution
- Accept or reject completed work based on acceptance criteria
- Engage with customers and stakeholders to gather feedback
- Balance technical debt with new feature delivery

### Goals
- Maximize value delivered in each sprint
- Ensure the team builds the right thing at the right time
- Maintain a healthy, ready backlog for upcoming sprints
- Foster strong stakeholder relationships and transparency

### Typical Communication
- Daily availability for clarifying requirements and acceptance criteria
- Sprint planning and backlog refinement sessions
- Sprint reviews and stakeholder demos
- Regular sync with Product Manager on strategic priorities

---

## QA Lead

### Role Summary
QA Leads ensure quality standards are met throughout the development lifecycle. They define testing strategies, coordinate quality assurance activities, and champion quality practices across the team.

### Responsibilities
- Define and maintain the overall test strategy and quality standards
- Coordinate testing activities across unit, integration, and end-to-end tests
- Review acceptance criteria to ensure testability
- Identify gaps in test coverage and quality processes
- Lead bug triage and coordinate with developers on fixes
- Mentor team members on quality practices and testing techniques

### Goals
- Reduce defects escaping to production
- Improve test automation coverage and effectiveness
- Establish clear quality gates for releases
- Foster a culture of quality ownership across the team

### Typical Communication
- Daily standup participation and bug triage sessions
- Quality metrics reporting in weekly syncs
- Test plan reviews during sprint planning
- Retrospective participation to improve quality processes

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, build, and maintain the infrastructure, CI/CD pipelines, and deployment processes that enable teams to deliver software reliably and efficiently.

### Responsibilities
- Design and maintain CI/CD pipelines for automated builds, tests, and deployments
- Manage infrastructure as code and cloud resources
- Implement monitoring, logging, and alerting systems
- Support incident response and troubleshooting production issues
- Ensure security best practices in infrastructure and deployment
- Optimize build times and deployment processes

### Goals
- Enable fast, safe, and automated deployments
- Minimize downtime and service disruptions
- Improve observability and incident response times
- Reduce manual toil through automation

### Typical Communication
- Weekly sync with development teams on pipeline and infrastructure needs
- Incident response coordination during outages
- Architecture reviews for infrastructure changes
- Capacity planning with Project and Product Managers

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases, ensuring all release requirements are met and that deployments proceed smoothly with minimal risk to production systems.

### Responsibilities
- Own the end-to-end release process and release calendar
- Coordinate release planning and communication across teams
- Verify all pre-release requirements are met (testing, documentation, approvals)
- Execute or coordinate deployment activities
- Manage release-related risks and rollback procedures
- Communicate release status to stakeholders

### Goals
- Deliver releases on schedule with zero critical incidents
- Maintain clear visibility into release readiness
- Minimize release-related disruptions
- Continuously improve the release process

### Typical Communication
- Release planning sessions with Product and Project Managers
- Go/no-go decision meetings before major releases
- Release status updates to stakeholders
- Post-release retrospectives

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with vested interest in the project's success. They provide requirements, feedback, and approvals while representing different business areas, customer segments, or organizational functions.

### Responsibilities
- Provide input on requirements and priorities based on business needs
- Participate in reviews, demos, and feedback sessions
- Approve key project decisions and deliverables
- Communicate project impact and value to their respective areas
- Raise concerns and constraints that may affect project success

### Goals
- Ensure project delivers expected business value
- Represent the interests of their constituent groups
- Maintain awareness of project progress and risks
- Support successful adoption of project outcomes

### Typical Communication
- Monthly stakeholder update meetings
- Sprint review and demo sessions (as needed)
- Ad-hoc consultations on key decisions
- Feedback surveys and retrospective input

---

## Change Champions

### Role Summary
Change Champions facilitate organizational adoption of new processes, tools, or ways of working. They act as advocates and coaches, helping teams navigate change while collecting feedback to inform continuous improvement.

### Responsibilities
- Promote awareness and understanding of new processes or tools
- Provide training and coaching to team members
- Serve as first point of contact for questions and concerns
- Collect feedback on adoption challenges and successes
- Advocate for teams' needs in process refinement discussions
- Celebrate wins and share best practices across teams

### Goals
- Accelerate adoption of new processes and tools
- Reduce resistance and friction during transitions
- Build capability and confidence within teams
- Identify and address adoption barriers early

### Typical Communication
- Office hours and coaching sessions with teams
- Training workshops and lunch-and-learns
- Feedback collection through surveys and one-on-ones
- Regular updates to leadership on adoption metrics

---

## Role Interactions and Collaboration

Effective project delivery at OctoAcme requires strong collaboration across all roles:

**Strategic Alignment**: Product Managers and Product Owners work together to translate vision into executable work, with Product Managers focusing on long-term roadmap and Product Owners managing sprint-level priorities.

**Quality Partnership**: Developers and QA Leads collaborate throughout development, with QA Leads helping define testability requirements upfront and developers taking ownership of test implementation.

**Delivery Coordination**: Project Managers and Release Managers partner to ensure projects stay on track and releases are executed smoothly, with Project Managers managing overall project timelines and Release Managers focusing on deployment activities.

**Technical Excellence**: Developers and DevOps Engineers work closely to ensure code is deployable and observable, with DevOps Engineers providing the infrastructure and tooling that enables developers to ship confidently.

**Stakeholder Engagement**: Product Owners and Stakeholders maintain regular communication to ensure requirements reflect real business needs and that delivered features meet expectations.

**Change Management**: Change Champions support all roles during process improvements or tool adoptions, working with Project Managers to ensure transitions are well-planned and with team members to address adoption challenges.

**Cross-functional Ceremonies**: All roles participate in key ceremonies such as sprint planning, retrospectives, and demos to ensure alignment, transparency, and continuous improvement.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles reflect common software delivery team structures and can be adapted to fit your organization's specific needs.

