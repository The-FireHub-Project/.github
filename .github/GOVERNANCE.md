# Governance Model for The FireHub Project

This document describes the governance model for **The FireHub Project**.  
It defines roles, responsibilities, decision-making processes, RFC workflow, and release management across all FireHub repositories.

This governance applies to **all FireHub projects**, including but not limited to:

- Core frameworks (Standard, Professional, Enterprise)
- Adapters (HTTP, Console, etc.)
- Capability modules (`firehub-*-capability`)
- Adapter-specific modules (`firehub-*-module`)
- Meta, templates, and infrastructure repositories

---

## 1. Governance Principles

FireHub governance is built on the following principles:

- **Transparency** – decisions and discussions are documented and accessible
- **Meritocracy** – influence is earned through sustained contribution
- **Stability first** – backward compatibility and predictable releases are prioritized
- **Security and quality** – security, correctness, and maintainability outweigh speed
- **Open collaboration** – community input is welcomed and encouraged

---

## 2. Roles and Responsibilities

### 2.1 Project Lead

**Responsibilities:**
- Defines long-term vision and strategic direction
- Final authority on major architectural decisions
- Oversees governance, licensing, and roadmap alignment

**Current holder:**
- Danijel Galić

---

### 2.2 Maintainers

Maintainers are trusted contributors responsible for the health of one or more repositories.

**Responsibilities:**
- Review and merge pull requests
- Enforce coding standards and architectural guidelines
- Participate in RFC reviews and technical decisions
- Approve releases and changelogs

Maintainers may specialize in:
- Core framework
- Adapters
- Capabilities and modules
- Infrastructure and tooling

---

### 2.3 Core Developers

Core Developers actively contribute to FireHub codebases.

**Responsibilities:**
- Implement features and fixes
- Participate in technical discussions
- Propose RFCs and improvements
- Help review pull requests

---

### 2.4 Contributors

Contributors include anyone who submits code, documentation, ideas, or feedback.

**Responsibilities:**
- Follow the Code of Conduct
- Respect project guidelines and review processes
- Engage constructively with maintainers and the community

---

## 3. Decision-Making Process

FireHub uses a **consensus-first, maintainer-led** decision model.

### 3.1 Minor Changes
Examples:
- Bug fixes
- Documentation updates
- Internal refactors without public API impact

**Process:**
- Reviewed and approved by at least one Maintainer

---

### 3.2 Significant Changes
Examples:
- New features
- Performance optimizations
- Non-breaking architectural changes

**Process:**
- Discussion in GitHub Issues or Discussions
- Review by relevant Maintainers
- Approval by repository Maintainer(s)

---

### 3.3 Major or Breaking Changes
Examples:
- Breaking API changes
- Major architectural redesigns
- Versioning or compatibility changes

**Process:**
- RFC required
- Community discussion
- Maintainer consensus
- Final approval by Project Lead

---

## 4. RFC (Request for Comments) Process

The RFC process ensures thoughtful discussion and documentation of significant changes.

### 4.1 When an RFC Is Required

An RFC is required for:
- Breaking changes
- New core abstractions or contracts
- Cross-repository changes
- Security-sensitive changes
- Changes affecting long-term maintenance or compatibility

---

### 4.2 RFC Workflow

1. **Proposal**
  - Open an RFC discussion in the `RFC` category
  - Clearly describe motivation, design, and alternatives

2. **Discussion**
  - Maintainers and community provide feedback
  - Revisions may be requested

3. **Decision**
  - Maintainers seek consensus
  - Project Lead resolves deadlocks if necessary

4. **Acceptance or Rejection**
  - Accepted RFCs are scheduled and tracked
  - Rejected RFCs remain documented for reference

---

## 5. Release Management

FireHub follows **Semantic Versioning (SemVer)**:  
`MAJOR.MINOR.PATCH`

### 5.1 Versioning Rules

- **MAJOR** - breaking changes
- **MINOR** – backward-compatible features
- **PATCH** – bug fixes and security patches

---

### 5.2 Core, Adapters, and Modules

- Core frameworks define compatibility boundaries
- Adapters and modules follow the core version they depend on
- Major core upgrades may require adapter and module updates

---

### 5.3 Release Responsibilities

- Maintainers prepare releases and changelogs
- Security fixes are prioritized
- Project Lead approves major releases

---

## 6. Security Governance

- All security issues must be reported privately (see `SECURITY.md`)
- Security fixes may bypass normal release cadence
- Coordinated disclosure is practiced

---

## 7. Governance Changes

Changes to this governance model:
- Require Maintainer discussion
- Must be approved by the Project Lead
- Are documented via pull requests

---

## 8. Code of Conduct

All participants must adhere to the FireHub **Code of Conduct**.  
Violations are handled according to the enforcement ladder defined therein.

---

## 9. Final Notes

FireHub governance exists to ensure:
- Long-term sustainability
- High technical standards
- A respectful and inclusive community

We value every contribution, and thank you for being part of the FireHub ecosystem.