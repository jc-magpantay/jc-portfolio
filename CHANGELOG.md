# Changelog

All notable changes to this portfolio project will be documented in this file.

The project follows a feature-based development workflow, with one meaningful feature per Git commit.

---

## [Unreleased]

### Planned

* Add real screenshots to project case studies
* Create additional project case studies
* Improve SEO metadata
* Add downloadable PDF resume
* Replace placeholder project cards with real projects
* Improve accessibility (alt text, aria labels, semantic HTML)

---

## [2026-06-29]

### Added

* Created `projects/README.md` documenting the case study workflow.
* Renamed `case-study-template.html` to `_TEMPLATE.html`.
* Added the first complete project documentation:

  * `vfa-recruitment-funnel.md`
  * `vfa-recruitment-funnel.html`

### Changed

* Renamed homepage sections:

  * About → About Me
  * Resume → Professional Experience
  * Services → Areas of Expertise
  * Skills → Skills & Technologies
  * Portfolio → Featured Projects

* Refactored Featured Projects:

  * Reduced from six cards to three
  * Removed Isotope filter buttons
  * Added the Virtual Freelancer Asia Recruitment Automation System as the first featured project

### Removed

* Removed the generic Stats section.
* Removed the placeholder Testimonials section.

### Development

* Adopted a Markdown → HTML workflow for project case studies.
* Established `_TEMPLATE.html` as the reusable base for all future projects.
* Standardized project documentation inside the `projects/` directory.
* Continued using the "One Commit = One Feature" development workflow.

---

## [2026-06-29]

### Added

* Added `projects/algorithmics-lms.md` as the source documentation for the Algorithmics & Clubhouse Engineers case study.
* Generated `projects/algorithmics-lms.html` from the reusable project template.
* Added a new Featured Project highlighting Technical Operations, CRM Management, and LMS Administration experience.

### Changed

* Updated the second Featured Project card on the homepage to link to the new Algorithmics case study.

### Development

* Continued using the Markdown-first workflow where Markdown is the source of truth and HTML is generated from the reusable template.

## [2026-06-29]

### Added

* Added **Microsoft Dynamics 365 Sales CRM Administration & Lead Operations** case study:

  * `projects/vimenture-dynamics365.md`
  * `projects/vimenture-dynamics365.html`
* Added the third Featured Project linking to the Microsoft Dynamics 365 case study.

### Changed

* Updated the **About Me** section with a more professional and personalized summary.
* Replaced the internal About heading:

  * **Virtual Assistant**
  * → **IT Administrator & CRM Automation Specialist**
* Removed duplicate placeholder paragraphs from the About section.
* Expanded the About section to better reflect experience in:

  * CRM Platforms
  * IT Administration
  * Database Management
  * Technical Operations
  * Cloud Technologies
  * AI-assisted Workflows

### Portfolio

* Portfolio now contains three complete Featured Project case studies:

  * Virtual Freelancer Asia Recruitment Automation System
  * Technical Operations & CRM Management for an International EdTech Company
  * Microsoft Dynamics 365 Sales CRM Administration & Lead Operations

### Documentation

* Continued using the Markdown-first documentation workflow:

  * Markdown (`.md`) remains the source of truth.
  * HTML case studies are generated from `_TEMPLATE.html`.
* Reinforced the reusable project generation workflow for future case studies.

### Development

* Continued feature-based Git workflow:

  * One meaningful feature per commit.
