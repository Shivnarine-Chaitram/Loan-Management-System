# Assured Financials — Loan Management System

**Software Engineering | Requirements, Project Planning, System Design & Test Planning**

> **Project status:** Academic software engineering **design and documentation project** (2024). This repository presents a proposed system and its planning deliverables; it does **not** contain a working or deployed loan-management application.

## Project overview

Assured Financials is a proposed **Loan Management System (LMS)** for a microfinance institution. The project examines how a web-based system could improve the management of loan applications, staff reviews, repayment information, and communication with applicants.

The goal was to translate business needs into a documented software solution—from identifying requirements and project risks to modeling system interactions and planning tests.

## Why this project is useful

Manual or fragmented loan workflows can make it difficult for applicants to track their requests and for staff to coordinate reviews. The proposed LMS aims to:

- **Centralize loan information** and application records.
- **Improve visibility** into loan status and repayment schedules.
- **Streamline staff workflows** for reviewing applications and responding to clients.
- **Support informed decisions** through reports and relevant loan data.
- **Plan for privacy and security** through role-based access, encryption, and authentication requirements.

These are **design objectives and specified requirements**, not claims about a functioning product.

## Proposed system capabilities

The requirements and design documents cover the following planned features:

| Area | Proposed functionality |
| --- | --- |
| Loan applications | Applicants submit applications and supporting information through an online portal. |
| Application review | Loan officers verify information and progress applications through review and approval steps. |
| Status tracking | Applicants view their loan status and relevant loan details. |
| Repayment management | Track installments, repayment history, upcoming payments, and balances. |
| Communication | Submit queries and provide notifications to applicants and staff. |
| Reporting | Provide operational and loan-related information for management. |
| Access and security | Define different user roles and requirements for protecting sensitive data. |
| Loan tools | Specify a loan calculator and refinancing-related interactions. |

## Documentation

All four deliverables are in the [`docs/`](docs/) folder. Their links below assume the original Word filenames are retained when uploaded.

| Document | What's inside |
| --- | --- |
| [Project Plan](docs/AssuredFinancials_Submission_ProjectPlan%28doc%29.docx) | Project scope and objectives, organization, responsibilities, risk analysis, resources, work breakdown, and schedule. |
| [Software Requirements Specification (SRS)](docs/Software%20Requirement%20Specification.docx) | Functional requirements, user classes, system features, constraints, security and other nonfunctional requirements. |
| [System Design Plan](docs/AssuredFinancials_Submission_DesignPlan%28doc%29.docx) | Context model, activity diagram, use-case diagram, sequence diagram, class diagram, and proposed MVC architecture. |
| [Test Plan](docs/Test%20Plan.docx) | Planned test cases, prerequisites, steps, input scenarios, and expected results for accessing applications and viewing loan status. |

### Suggested reading order

1. **Project Plan** — Understand the problem, scope, resources, schedule, and risks.
2. **SRS** — See what the proposed system should do and its constraints.
3. **Design Plan** — Explore the system models, interactions, and architecture.
4. **Test Plan** — Review how selected requirements would be verified.

## Project approach and engineering concepts

This team project followed a **plan-driven / waterfall-oriented approach**, as discussed in the Project Plan. The documentation demonstrates:

- Requirements elicitation and specification
- Scope definition, risk assessment, and project scheduling
- UML and other system modeling techniques
- Model–View–Controller (MVC) architectural planning
- Role-based access and security requirements analysis
- Test-case design and expected-outcome documentation

## Project management and collaboration

This was a **collaborative university software engineering project**, not an individual implementation. The Project Plan identifies **Shivnarine Chaitram as Project Manager**, with responsibilities including planning, organizing tasks, coordinating deliverables, tracking milestones, and overseeing schedules. The Test Plan also documents his coordination and compilation of team contributions.

Other team responsibilities covered frontend/web design, backend/database planning, security, quality assurance, and documentation. Credit for the project's work belongs to the contributing team members.

## How to use this repository

**No installation or programming environment is required.** This is a documentation-only repository.

1. Open the **Documentation** section above.
2. Select a document to review its requirements, diagrams, plans, or test cases.
3. Download the Word file if you want to inspect it offline.
4. Use the documents as examples of how an academic software project can be planned and specified before development.

The documents are **reference materials**, not a ready-to-deploy financial system or verified production specifications.

## Repository layout

```text
Assured-Financials-Loan-Management-System/
├── README.md
└── docs/
    ├── AssuredFinancials_Submission_ProjectPlan(doc).docx
    ├── Software Requirement Specification.docx
    ├── AssuredFinancials_Submission_DesignPlan(doc).docx
    └── Test Plan.docx
```

## Potential next steps

Future work could include implementing a prototype, connecting a database, building the client and staff interfaces, expanding automated test coverage, and validating the proposed controls with realistic security and usability testing.



