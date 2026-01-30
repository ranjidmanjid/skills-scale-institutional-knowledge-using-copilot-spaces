# OctoAcme Project Management Documentation

## Purpose

Welcome to OctoAcme's project management documentation hub. This collection of documents provides a comprehensive guide to how we plan, execute, and deliver projects across our organization. Whether you're a new team member getting up to speed or an experienced contributor looking for specific process details, these documents will help you understand our methodology and navigate our project management practices.

## Who Should Read This

- **New team members** joining OctoAcme who need to understand our project management approach
- **Developers, Product Managers, and Project Managers** involved in cross-functional projects
- **Stakeholders and leadership** seeking clarity on our delivery processes
- **External partners** collaborating on OctoAcme projects
- **Anyone** contributing to product features, services, or integrations at OctoAcme

## Overview of OctoAcme's Project Management Process

OctoAcme follows a structured, iterative project management approach built on five core principles: customer-first prioritization, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Every project flows through a defined lifecycle beginning with **Initiation**, where teams create a Project One-pager to validate business need, define SMART goals, identify success metrics, and secure stakeholder alignment before moving forward. Once approved, projects enter **Planning**, where cross-functional teams break work into shippable increments with clear acceptance criteria, estimate effort using T-shirt sizing or story points, and establish a Definition of Done. Dependencies and risks are captured in a Risk Register, and a release plan with milestone mapping ensures alignment across teams. The planning phase culminates in a kickoff meeting that brings stakeholders and delivery teams together to review the prioritized backlog and agree on timelines.

During **Execution and Tracking**, OctoAcme teams maintain a consistent rhythm with daily 15-minute standups focused on progress and blockers, weekly delivery syncs to review updates and risks, and sprint-end demos. Work flows through a GitHub Projects board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests follow strict conventions: they should be small (≤400 lines when possible), include issue links and acceptance criteria, pass automated tests and linting in CI, and require at least one approval before merging. Quality assurance is embedded throughout, with unit tests for new logic, integration and end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Blocker escalation follows a three-tier path—team-level triage at standup, PM escalation to Product Leads and dependent teams, and sponsor-level escalation for business-impacting issues.

OctoAcme defines three distinct **personas** that collaborate throughout the project lifecycle. **Developers** design, build, and test software, focusing on reliable and maintainable code with high test coverage. **Product Managers** own the product vision, define problem statements and success metrics, prioritize the backlog, and validate solutions through user research and metrics to maximize customer value. **Project Managers** coordinate delivery activities, manage schedules and risks, maintain project documentation, facilitate key meetings (kickoffs, planning, retrospectives), and ensure transparent stakeholder communication through weekly status updates, risk registers, and decision logs. This clear role delineation ensures accountability while fostering collaboration.

**Release and Deployment** follows a standardized process to minimize risk and improve observability. Releases are classified as patch (hotfixes), minor (incremental features), or major (significant functionality or breaking changes). Pre-release requirements include passing CI and security scans, completed acceptance criteria, drafted release notes, and a documented rollback plan. Deployments move through staging smoke tests before production, followed by post-deploy verifications and stakeholder announcements. If issues arise, an incident response triggers with immediate rollback if necessary, followed by root cause triage. After each sprint, release, or milestone, teams conduct **Retrospectives** using a structured format to identify what went well, what could improve, and 2-3 prioritized action items with clear owners and due dates. These action items feed into the project backlog, creating a continuous improvement loop that measures impact and celebrates incremental progress. Throughout all phases, **communication** follows defined templates for weekly status updates (progress, next steps, risks, decisions needed) and incident responses, with escalation paths from team level through PM to Product Lead and ultimately to Sponsor, ensuring transparency and rapid resolution.

## Process Documentation

Explore our detailed process documents organized by project lifecycle phase:

### Core Overview
- **[Project Management Overview](octoacme-project-management-overview.md)** - Introduction to OctoAcme's approach, roles, and key artifacts

### Project Lifecycle
1. **[Project Initiation](octoacme-project-initiation.md)** - How to start a project with clear goals and stakeholder alignment
2. **[Project Planning](octoacme-project-planning.md)** - Breaking down work, estimating effort, and creating release plans
3. **[Execution and Tracking](octoacme-execution-and-tracking.md)** - Daily standups, sprint management, and quality assurance practices
4. **[Release and Deployment](octoacme-release-and-deployment.md)** - Shipping software safely with proper testing and rollback plans
5. **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Learning from experience and implementing improvements

### Supporting Processes
- **[Roles and Personas](octoacme-roles-and-personas.md)** - Detailed responsibilities for Developers, Product Managers, and Project Managers
- **[Risks and Communication](octoacme-risks-and-communication.md)** - Managing risks, escalations, and stakeholder communication

## How to Use These Docs

1. **Getting Started**: Begin with the [Project Management Overview](octoacme-project-management-overview.md) to understand our overall approach
2. **Starting a New Project**: Follow the [Project Initiation](octoacme-project-initiation.md) guide to create your project charter
3. **During Execution**: Refer to [Execution and Tracking](octoacme-execution-and-tracking.md) for daily practices and workflows
4. **Shipping Features**: Use the [Release and Deployment](octoacme-release-and-deployment.md) checklist before every release
5. **Understanding Your Role**: Check [Roles and Personas](octoacme-roles-and-personas.md) for role-specific guidance
6. **Reference as Needed**: Use these documents as living references throughout your project lifecycle

### For Copilot Spaces

To enable GitHub Copilot Spaces to use these process documents as context for your project:
- Copy relevant process documents into your project's `.copilot/` directory
- This allows Copilot to provide project-specific guidance based on OctoAcme's processes

## Contributing and Suggesting Updates

These documents are living resources that improve through team feedback and lessons learned. If you have suggestions for improvements:

1. **Small Updates**: Create a pull request with your proposed changes
2. **Larger Changes**: Open an issue to discuss the change with the team first
3. **Questions or Clarifications**: Reach out to your Project Manager or open an issue for discussion
4. **After Retrospectives**: Share action items that could improve these processes

All contributions should maintain:
- Clear, concise language accessible to all team members
- Consistency with OctoAcme's core principles
- Practical, actionable guidance
- Alignment with existing processes and terminology

## Questions?

If you have questions about these processes or need clarification on specific practices, please:
- Reach out to your Project Manager or team lead
- Open a discussion issue in this repository
- Bring questions to your team's standup or planning meetings

---

**Last Updated**: 2026-01-30
