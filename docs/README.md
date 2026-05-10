# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Documentation. This folder contains comprehensive, standardized guidance for how OctoAcme runs projects—from initial concept through delivery, release, and continuous improvement. Use these docs as your central reference for project management processes, roles, and best practices.

---

## 📖 What This Documentation Is For

OctoAcme manages projects using a structured five-stage lifecycle that emphasizes clear ownership, iterative delivery, and data-informed decisions. These documents are designed to:

- **Onboard new team members** quickly by providing a single source of truth for how we work
- **Ensure consistency** across projects by standardizing workflows, roles, and artifacts
- **Scale institutional knowledge** by converting tacit team insights into searchable, versioned documentation
- **Reduce single-person dependency** by making processes and decisions transparent and documented
- **Enable predictable execution** through clearly defined roles, communication cadences, and quality gates

---

## 🎯 Core Principles

All OctoAcme projects are guided by five foundational principles:

1. **Customer-First**: Prioritize customer value and usability in all decisions
2. **Iterative Delivery**: Build and ship small, testable increments to gather feedback early
3. **Clear Ownership**: Every project has named owners (PM, PdM, team lead) with defined responsibilities
4. **Data-Informed Decisions**: Measure impact and iterate based on evidence, not assumptions
5. **Psychological Safety**: Create an environment where feedback, questions, and learning are encouraged

---

## 📚 Process Documentation

### 1. [Project Management Overview](./octoacme-project-management-overview.md)
**Start here** for a concise introduction to the OctoAcme approach.
- Core roles and responsibilities (PM, Product Manager, Developers, QA)
- Key artifacts and templates
- High-level project lifecycle (Initiation → Planning → Execution → Release → Close)
- Communication cadence and how to use these docs

### 2. [Project Initiation](./octoacme-project-initiation.md)
**Use when**: You have a new project idea or feature proposal ready to validate.
- Confirm business need and measurable outcomes
- Identify stakeholders and create a communication plan
- Develop a lightweight Project One-pager
- Decision gates for moving to planning

### 3. [Project Planning](./octoacme-project-planning.md)
**Use when**: A project is approved and ready to be broken into actionable work.
- Turn initiatives into prioritized backlogs
- Define acceptance criteria and Definition of Done
- Estimate scope and identify dependencies
- Create release plans and milestone maps

### 4. [Execution & Tracking](./octoacme-execution-and-tracking.md)
**Use during**: Day-to-day project delivery and sprint execution.
- Team rhythm (standups, syncs, demos)
- Pull request and code review workflows
- Quality and testing standards
- Blocker escalation paths
- Progress tracking and metrics

### 5. [Risk Management & Communication](./octoacme-risks-and-communication.md)
**Use when**: Identifying risks, managing dependencies, or communicating project status.
- Risk Register structure and lifecycle
- Stakeholder communication templates
- Status reporting formats
- Incident communication and escalation paths

### 6. [Release & Deployment](./octoacme-release-and-deployment.md)
**Use when**: Preparing features for production release.
- Release types (patch, minor, major)
- Pre-release requirements and deployment checklists
- Rollback and incident procedures
- Release notes templates

### 7. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
**Use when**: Capturing learnings after sprints, releases, or milestones.
- Retrospective structure and facilitation
- Action item templates and tracking
- Building a continuous improvement culture

### 8. [Roles and Personas](./octoacme-roles-and-personas.md)
**Reference**: Detailed descriptions of key roles and personas used in OctoAcme projects.
- Developer responsibilities and goals
- Product Manager responsibilities and goals
- Project Manager responsibilities and goals
- How these personas shape project interactions

---

## 🚀 Quick Start: Starting a New Project

Follow these steps to launch a project aligned with OctoAcme practices:

1. **Initiation Phase** (Week 1)
   - Read [Project Initiation](./octoacme-project-initiation.md)
   - Create a Project One-pager with your team (Problem, Goal, Success Metrics)
   - Align stakeholders and get sponsor approval
   - Confirm go/no-go decision

2. **Planning Phase** (Week 2–3)
   - Read [Project Planning](./octoacme-project-planning.md)
   - Hold a project kickoff with the delivery team
   - Build and prioritize your backlog with acceptance criteria
   - Define Definition of Done and test approach
   - Identify dependencies and create a release plan

3. **Execution Phase** (Ongoing)
   - Read [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - Establish daily standups and weekly syncs
   - Use a project board (GitHub Projects or similar) with: Backlog, Ready, In Progress, In Review, QA, Done
   - Review [Risk Management & Communication](./octoacme-risks-and-communication.md) and maintain a Risk Register
   - Run demos and gather feedback regularly

4. **Release Phase** (As Ready)
   - Read [Release & Deployment](./octoacme-release-and-deployment.md)
   - Follow the deployment checklist
   - Conduct post-deployment verification
   - Announce the release to stakeholders and support

5. **Retrospective Phase** (After Release)
   - Read [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
   - Hold a retrospective with the team
   - Capture action items with owners and due dates
   - Feed learnings back into this documentation

---

## 💡 Using These Docs in Copilot Spaces

OctoAcme uses Copilot Spaces to centralize project management knowledge and make it discoverable across the organization. Here's how to get the most out of these docs:

### For Project Managers and Teams
- Add the `/docs` folder or individual process docs to your Copilot Space context
- Ask Copilot questions like: "What's the Project Manager's role in risk escalation?" or "What should our Definition of Done include?"
- Reference specific sections when onboarding new team members

### For New Team Members
- Start with [Project Management Overview](./octoacme-project-management-overview.md)
- Then read the specific process document for your current phase (Initiation, Planning, Execution, etc.)
- Ask Copilot to help you understand your role and responsibilities using the [Roles and Personas](./octoacme-roles-and-personas.md) doc

### For Knowledge Management
- These docs are version-controlled and searchable
- Update them as you learn and improve processes
- Use GitHub Issues to propose changes (see issue template: `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`)
- Tag updates with clear rationale to maintain institutional knowledge

---

## 📋 Key Artifacts at a Glance

| Artifact | Purpose | Owned By | When Created |
|----------|---------|----------|--------------|
| Project One-pager | Capture problem, goal, success metrics | Product Manager | Initiation |
| Backlog | Prioritized list of work items | Product Manager | Planning |
| Acceptance Criteria | Define what "done" means | Product Manager / Developers | Planning |
| Definition of Done | Quality gates before work is complete | Team | Planning |
| Risk Register | Track and monitor project risks | Project Manager | Planning (ongoing) |
| Project Board | Visualize work in progress | Team | Planning / Execution |
| Release Notes | Communicate what shipped | Product Manager | Release |
| Retrospective Notes | Capture learnings and action items | Project Manager / Team | Close & Retrospective |

---

## 🤝 Support and Feedback

Have questions about these processes? Found something unclear or outdated?

1. **Ask in a Copilot Space**: Upload these docs to your Copilot Space and ask for clarification or examples
2. **Create an Issue**: Use the issue template [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates
3. **Reach out to your Product Lead or Project Manager**: They can walk you through specific sections

---

## 📖 Document History

| Date | Change | Author |
|------|--------|--------|
| 2026-05-10 | Created comprehensive README and process documentation index | Copilot |

---

**Last Updated**: 2026-05-10

For the latest updates, check the modification date on individual process documents in the `/docs` folder.
