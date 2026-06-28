# COPILOT.md

# Portfolio Development Guide

This document defines the development standards, workflow, and architecture for this repository.

All AI assistants (GitHub Copilot, ChatGPT, Gemini CLI, Claude Code, etc.) should read this file before making changes.

---

# Project Goal

This repository contains my personal portfolio website.

The objective is to present my professional experience through:

* A clean and modern homepage
* Real-world project case studies
* Professional documentation
* Maintainable source files
* Consistent writing and design

The portfolio should accurately represent my skills without exaggeration or fabricated achievements.

---

# Project Structure

```
/
│
├── README.md
├── ROADMAP.md
├── CHANGELOG.md
├── COPILOT.md
│
├── projects/
│   ├── README.md
│   ├── _TEMPLATE.html
│   ├── *.md
│   └── *.html
│
├── assets/
│
└── index.html
```

---

# Documentation Files

## README.md

General overview of the repository.

---

## ROADMAP.md

Contains future plans and long-term improvements.

---

## CHANGELOG.md

Records completed changes.

Every meaningful feature should be reflected in the changelog.

---

## COPILOT.md

This file.

Contains development guidelines for AI assistants.

---

# Project Workflow

Follow this workflow whenever adding or updating projects.

1. Create a Markdown document inside `/projects`.
2. Write the complete project documentation.
3. Copy `_TEMPLATE.html`.
4. Generate a new HTML page from the Markdown.
5. Never edit `_TEMPLATE.html`.
6. Link the new project from the homepage.
7. Update `CHANGELOG.md`.
8. Commit the changes.

Markdown is the source of truth.

HTML is the generated presentation.

---

# Case Study Rules

Every project should explain:

* Project Overview
* Business Problem
* My Responsibilities
* Technologies Used
* Technical Challenges
* Solution
* Results
* Lessons Learned
* Future Improvements

Focus on explaining the business value as well as the technical implementation.

---

# Development Philosophy

Prefer:

* Small commits
* Small tasks
* Small pull requests
* Reusable components
* Clear documentation

Avoid making large unrelated changes in one task.

One feature should equal one Git commit whenever practical.

---

# Editing Rules

Unless explicitly instructed:

Do NOT:

* redesign the website
* replace the BootstrapMade theme
* change the overall visual identity
* remove existing documentation
* rename files unnecessarily
* create duplicate pages

Preserve:

* responsive layout
* Bootstrap styling
* existing navigation
* accessibility improvements
* SEO improvements

---

# Template Rules

`projects/_TEMPLATE.html`

This file is the master template.

Never modify it unless specifically asked.

Instead:

* duplicate it
* generate a new HTML page
* populate it using the Markdown source

---

# Writing Guidelines

Use professional language.

Do not exaggerate accomplishments.

Do not invent:

* statistics
* testimonials
* client names
* revenue
* percentages
* performance metrics

Only use information supported by the project documentation.

When uncertain, use neutral wording.

---

# Code Guidelines

Prefer:

* semantic HTML
* reusable CSS
* readable JavaScript
* descriptive comments only when necessary

Avoid unnecessary complexity.

---

# AI Assistant Behavior

Before making changes:

1. Read README.md
2. Read ROADMAP.md
3. Read CHANGELOG.md
4. Read this file
5. Read any relevant project documentation

After making changes:

* Summarize modified files.
* Explain what changed.
* Report any assumptions made.
* Do not claim work was completed unless it actually was.

---

# Long-Term Vision

The goal is to grow this repository into a professional portfolio showcasing experience in:

* CRM Automation
* GoHighLevel
* Airtable
* IT Administration
* Technical Support
* Database Administration
* Process Automation
* Python Automation
* AI-assisted Development

Every new project should improve the overall quality, consistency, and professionalism of the portfolio.
