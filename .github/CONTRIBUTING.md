# Contributing to FireHub

Thank you for considering contributing to **The FireHub Project**!  
All types of contributions are encouraged and valued. This guide will help you navigate how to contribute effectively and safely.

> If you enjoy the project but cannot contribute code, there are other ways to support FireHub:
> - Star the project
> - Share it on social media
> - Refer it in your project’s README
> - Mention it at meetups or to colleagues

## Table of Contents

- [Questions](#questions)
- [Contributing Code or Documentation](#contributing-code-or-documentation)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Reporting Incidents](#reporting-incidents)
- [Suggesting Enhancements or Ideas](#suggesting-enhancements-or-ideas)
- [Reporting Security Vulnerabilities](#reporting-security-vulnerabilities)

## Questions

Before asking a question, please:

1. Check the [documentation](https://the-firehub-project.github.io/) thoroughly.
2. Search existing discussions for answers.
3. If clarification is needed, open a discussion in [Q&A](https://github.com/orgs/The-FireHub-Project/discussions/categories/q-a) and include:
- Context of your issue
- Relevant platform, PHP, and FireHub versions
- Code or configuration snippets if relevant

We will respond as quickly as possible.

## Contributing Code or Documentation

> **Legal Notice:** By contributing, you confirm that you authored the content, have the necessary rights, and agree to provide it under the FireHub project license.

### How to Contribute

1. Fork the repository and create a feature branch.
2. Write clear, concise commit messages.
3. Follow FireHub coding standards (PSR-12 for PHP, Markdown for docs).
4. Submit a pull request with a clear description and link to related issues or discussions.

## Pull Request Guidelines

All Pull Requests must follow these rules to ensure consistency, traceability, and maintainability across the FireHub ecosystem.

### Issue Linking

Every PR MUST reference related issues using:

`Closes #<issue-id>` or `Fixes #<issue-id>` or `Resolves #<issue-id>`  – when fully resolved  
`Refs #<issue-id>` or `See #<issue-id>` or `Part of #<issue-id>` – when partially related

Issue types describe context.  
PR semantics describe the actual code change.

They are intentionally different.

### Atomic Changes

Each PR must represent a single logical change.

Do not mix:
- feature + refactor
- bugfix + formatting
- infrastructure + domain logic

If multiple concerns exist, split into separate PRs.

### Description Requirements

Every PR must include:

- What was changed
- Why it was changed
- Any breaking changes (if applicable)
- Related issue(s), if available

### Testing Requirements

All changes must be covered by appropriate validation:

- Unit tests for domain logic
- Integration tests for adapters or runtime behavior
- CI pipeline must pass

No PR should be merged with failing tests.

### Architecture Compliance

Changes must respect FireHub architecture rules:

- Core remains framework-neutral
- Runtime handles execution only
- Adapters handle external integrations
- Capabilities remain reusable and isolated

Violations may result in rejection.

### Code Quality

- Follow existing coding standards
- No dead code or debug artifacts
- Maintain readability over cleverness
- Ensure consistent naming conventions

### Review Requirements

All PRs require approval from relevant CODEOWNERS teams.

Critical areas (Core, Runtime, Meta) may require multiple approvals.

### Breaking Changes

Breaking changes must:

- Be explicitly marked in the PR description
- Include migration notes
- Be approved by maintainers or core team

### Documentation Updates

If behavior changes, documentation must be updated accordingly:

- README
- Architecture docs
- API references (if applicable)

## Reporting Bugs

> **Note:** Do not report security-related bugs here; use [Security Vulnerability](#reporting-security-vulnerabilities).

### Before Submitting a Bug

- Ensure you are using the latest version.
- Confirm the issue is not caused by your environment or configuration.
- Check existing bug reports and online resources.
- Collect details:
  - Stack trace (if applicable)
  - OS, platform, PHP/SDK/runtime version
  - Input and output
  - Steps to reproduce, including with older versions if possible

### Bug Report Template

```markdown
**Steps to Reproduce:**
1. 
2. 
3. 

**Expected Behaviour:**

**Actual Behaviour:**

**Environment:**
- OS: 
- PHP version: 
- FireHub version:
```

## Reporting Incidents

Report unusual software behavior to the [Incident](https://github.com/orgs/The-FireHub-Project/discussions/categories/incident) discussion:

- Use a **descriptive title**
- Provide **step-by-step details**
- Explain the **current behavior vs. expected behavior**
- Include **alternatives attempted**

## Reporting Incidents

Report unusual software behavior to the [Incident](https://github.com/orgs/The-FireHub-Project/discussions/categories/incident) discussion:

- Use a **descriptive title**
- Provide **step-by-step details**
- Explain the **current behavior vs. expected behavior**
- Include **alternatives attempted**

---

## Suggesting Enhancements or Ideas

Use [Suggestions](https://github.com/orgs/The-FireHub-Project/discussions/categories/suggestions) for improvements and [Ideas](https://github.com/orgs/The-FireHub-Project/discussions/categories/ideas) for new features.

### Guidelines

- Ensure you’re on the **latest version**
- Check **documentation** and search for existing suggestions
- Make a strong case for how it **benefits most FireHub users**
- Reference other projects if relevant

### Enhancement / Idea Template

```markdown
**Title:** 

**Description:**

**Current Behaviour:**

**Expected Behaviour:**

**Benefits:**
```

## Reporting Security Vulnerabilities

Send all security reports **privately** to:

📧 **danijel.galic@outlook.com**

- You will receive a response within **48 hours**
- Confirmed vulnerabilities will be patched **as quickly as possible**
- **Never disclose security issues publicly**

---

## Thank You

Your contributions help make **FireHub** better for everyone.  
We appreciate your time, effort, and enthusiasm!