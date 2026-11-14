# University Hostel Booking System

### A Software Evolution Project

## 1. Project Overview

The University Hostel Booking System is an existing software system undergoing evolution as part of a Software Evolution project.

Rather than developing an entirely new application, this project focuses on extending the capabilities of the existing system, improving its internal architecture, modernizing selected components, and strengthening its reliability and maintainability.

The evolution process involves introducing new functionalities, refactoring legacy code, migrating selected modules to modern technologies, and implementing automated regression testing to ensure that existing functionality remains stable as changes are introduced.

## 2. Project Background and Motivation

As software systems grow and their requirements change, they must evolve to remain useful, reliable, and maintainable.

The existing hostel booking system provides a foundation for further development. However, additional functionality and architectural improvements are required to address emerging user needs and improve the system's overall quality.

This project therefore focuses on evolving the existing system through controlled modifications while preserving its essential functionality.

## 3. Evolution Objectives

The main objectives of this project are to:

- Extend the existing system with additional booking and payment capabilities.
- Improve the flexibility of hostel payment arrangements.
- Automate the calculation and application of late payment penalties.
- Introduce a structured room change request process.
- Refactor legacy code using modern asynchronous programming techniques.
- Migrate one core system module to TypeScript.
- Improve software reliability through an automated regression testing suite.
- Enhance the maintainability and long-term evolution of the system.

## 4. Proposed System Enhancements

The project will focus on the following evolutionary changes:

### 4.1 Installment Plans

Introduce flexible installment payment arrangements to allow students to pay hostel fees in multiple installments rather than making a single full payment.

### 4.2 Payment Management

Enhance the existing payment functionality to support improved payment processing and tracking.

### 4.3 Automated Late Penalty Charges

Introduce automated late penalty calculations and charges for payments that are not completed within specified deadlines.

### 4.4 Room Change Requests

Implement a room change request feature that allows students to formally request a change of their assigned rooms, subject to administrative review and approval.

### 4.5 Legacy Code Refactoring

Refactor the existing COBOL-related code using modern asynchronous programming techniques, including async/await where applicable, to improve code organization and asynchronous operation handling.

### 4.6 TypeScript Migration

Migrate one core system module to TypeScript to introduce stronger type checking and improve code maintainability.

### 4.7 Automated Regression Testing

Introduce an automated regression test suite to verify that existing functionality continues to operate correctly after modifications and new features are introduced.

## 5. Software Evolution Strategy

The project adopts a controlled software evolution approach involving:

- **Perfective Maintenance:** Introducing new features and improving existing functionality.
- **Preventive Maintenance:** Refactoring legacy code and improving maintainability.
- **Corrective Maintenance:** Addressing defects identified during testing and system evaluation.
- **Adaptive Maintenance:** Modifying components to accommodate changes in technologies and the operating environment.

Changes will be managed through documented Change Requests, impact analysis, code reviews, and regression testing.

## 6. Technology and Tools

The technologies and tools used in the project include:

- **Version Control:** Git
- **Repository Hosting:** GitHub
- **COBOL:** Existing legacy codebase
- **JavaScript:** Asynchronous programming using async/await
- **TypeScript:** Migration of a selected core module
- **Automated Testing:** Regression testing framework (to be finalized)
- **CI/CD:** GitHub Actions (planned)

Additional technologies will be documented as the existing system and its implementation environment are examined.

## 7. Repository Structure

```text
University-Hostel-Booking-System/
│
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── change_request.md
│   │   └── bug_report.md
│   │
│   └── PULL_REQUEST_TEMPLATE.md
│
├── docs/
│
├── CONTRIBUTING.md
├── CHANGELOG.md
└── README.md
```

## 8. Branching and Version Control Strategy

The project uses a Trunk-Based Development approach with feature branches.

| Branch | Purpose |
|---|---|
| `main` | Production-ready code |
| `develop` | Integration branch for approved changes |
| `feat/` | New feature development |
| `fix/` | Corrective changes |
| `refactor/` | Refactoring activities |

All changes must be submitted through Pull Requests and reviewed before merging.

The project also follows Conventional Commits to maintain a consistent commit history and support automated CHANGELOG generation.

Refer to [CONTRIBUTING.md](CONTRIBUTING.md) for detailed contribution guidelines.

## 9. Change Management

All proposed modifications are documented using Change Requests (CRs).

Each Change Request identifies:

- The reason for the proposed change.
- The affected subsystem.
- The scope of the modification.
- The preliminary impact set.
- The Change Control Board (CCB) decision.

Pull Requests are used to review, validate, and integrate approved modifications.

## 10. Testing and Quality Assurance

An automated regression test suite will be introduced to verify that existing system functionality is not unintentionally affected by evolutionary changes.

The project will also incorporate:

- Functional testing.
- Regression testing.
- Integration testing.
- Code quality checks.
- Pull Request reviews.

## 11. Project Team

| Team Member | Assigned Role |
|---|---|
| Team Member 1 | To be assigned |
| Team Member 2 | To be assigned |
| Team Member 3 | To be assigned |
| Team Member 4 | To be assigned |
| Team Member 5 | To be assigned |
| Team Member 6 | To be assigned |
| Team Member 7 | To be assigned |

## 12. Project Status

**Current Status:** Repository Setup and System Evolution Planning

The project is currently establishing its development workflow, documentation standards, and change management procedures.

Subsequent activities will focus on understanding the existing system, analysing its architecture, implementing approved evolutionary changes, and validating the resulting system through automated testing.

---

**University Hostel Booking System**

*Evolving an existing system through controlled change, modernization, and continuous improvement.*
