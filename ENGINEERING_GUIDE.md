# Engineering Guide

> This document defines the engineering principles, development workflow, and coding standards for the **jc-portfolio** repository.
>
> The goal is to ensure that every change improves the portfolio's quality while keeping the project maintainable, scalable, and professional.

---

# 1. Project Philosophy

This portfolio is more than a personal website.

It is a long-term software project that demonstrates:

- Technical ability
- Software engineering practices
- UI/UX thinking
- Documentation quality
- Professional project organization

Every feature should contribute toward those goals.

---

# 2. Core Principles

## Maintainability

Choose simple, readable solutions over clever implementations.

Future updates should be straightforward.

---

## Scalability

Features should support future growth without requiring major rewrites.

Examples:

- Reusable project cards
- Reusable case study templates
- Shared styling
- Consistent layouts

---

## Accessibility

Accessibility is required, not optional.

Every UI component should:

- Support keyboard navigation
- Include meaningful alt text
- Maintain sufficient color contrast
- Avoid hover-only interactions
- Use semantic HTML

---

## Performance

Prefer lightweight solutions.

Avoid unnecessary JavaScript.

Avoid unnecessary third-party libraries.

Optimize images whenever possible.

---

## Authenticity

Never exaggerate or fabricate project contributions.

Every case study must accurately represent:

- My role
- My responsibilities
- My technologies
- My contributions

---

# 3. Repository Structure

The repository is organized as follows:

- assets/
- projects/
- resume/

Root documentation:

- README.md
- ROADMAP.md
- CHANGELOG.md
- COPILOT.md
- ENGINEERING_GUIDE.md

---

# 4. Development Workflow

Every feature follows the same process.

1. Planning
2. Design Review
3. Approval
4. Implementation
5. Testing
6. Documentation
7. Git Commit

No major implementation should begin without first explaining the proposed approach.

---

# 5. Sprint Workflow

Every sprint should remain focused on a single objective.

Example:

Sprint 1

Featured Projects Redesign

Deliverables

- Responsive project cards
- Accessibility improvements
- Reusable component structure

---

# 6. Coding Standards

## HTML

- Use semantic HTML.
- Avoid unnecessary wrappers.
- Keep markup readable.

## CSS

- Reuse existing styles whenever practical.
- Group related rules.
- Avoid duplicated styling.
- Prefer reusable utility classes.

## JavaScript

- Keep scripts modular.
- Avoid global variables.
- Remove unused code when appropriate.
- Prefer readability over cleverness.

---

# 7. UI Principles

The portfolio should feel modern while remaining simple.

Prioritize:

- Clear hierarchy
- Consistent spacing
- Responsive layouts
- Professional typography
- Reusable components

Avoid visual clutter.

---

# 8. Case Studies

Every case study should follow the standards defined in:

projects/_CASE_STUDY_GUIDE.md

Case studies should tell a story, not simply describe technology.

---

# 9. Documentation

Documentation is part of development.

Whenever appropriate:

- Update CHANGELOG.md
- Update ROADMAP.md
- Update README.md

Do not leave documentation behind.

---

# 10. Git Standards

One sprint should generally produce:

- One focused feature
- One logical Git commit
- One CHANGELOG entry

Avoid mixing unrelated work into the same commit.

---

# 11. Definition of Done

A sprint is complete when:

- The objective is achieved.
- Code is clean.
- Accessibility has been reviewed.
- Mobile responsiveness has been verified.
- Documentation has been updated.
- No unnecessary code has been introduced.
- A suitable Git commit message has been prepared.

---

# 12. Future Evolution

This portfolio should continue evolving as new projects are completed.

The long-term vision is to build a professional portfolio that demonstrates:

- Software Engineering
- CRM Administration
- Process Automation
- Website Development
- Technical Leadership
- Documentation Quality