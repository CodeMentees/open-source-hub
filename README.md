<div align="center">

# Open Source Hub

**A community-driven repository for building open source projects in EdTech, AI, and beyond.**

> **Current event:** Hacktoberfest 2026. See [Current Event](#current-event).

![Hacktoberfest 2026](https://img.shields.io/badge/Hacktoberfest-2026-blueviolet)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributions](https://img.shields.io/badge/contributions-open-orange)

[Propose an Idea](../../issues/new?labels=proposal&title=Proposal%3A+) ·
[Submit a Project](#submit-an-existing-project) ·
[Browse Issues](../../issues) ·
[Join the Discussion](../../discussions)

</div>

---

## Table of Contents

- [About](#about)
- [Focus Areas](#focus-areas)
- [Ways to Contribute](#ways-to-contribute)
- [Proposal and Review Process](#proposal-and-review-process)
- [Contribution Workflow](#contribution-workflow)
- [Guidelines](#guidelines)
- [Current Event](#current-event)
- [Repository Structure](#repository-structure)
- [Community and Support](#community-and-support)
- [License](#license)

---

## About

This repository is a home for open source collaboration. We invite developers, designers, writers, and students to contribute project ideas and working implementations, or to improve projects already in the repository.

Contributions are reviewed by the maintainers. Proposals and submissions that are well-scoped, useful, and aligned with our focus areas are accepted and developed collaboratively within this repository. Not every proposal will be accepted, but every proposal will receive a response.

---

## Focus Areas

We are primarily interested in the following areas. These are priorities, not restrictions. Strong ideas from other domains are welcome.

| Area | Examples |
|---|---|
| **EdTech** | Learning platforms, quiz and flashcard tools, study planners, classroom utilities, accessibility tools for learners, open educational resources |
| **AI Integration** | AI tutors and assistants, summarization tools, recommendation systems, RAG applications, prompt engineering utilities, AI-assisted productivity tools |
| **Web and Mobile** | Frontend and backend applications, PWAs, cross-platform apps |
| **Developer Tools** | CLIs, automation scripts, editor extensions, project templates |
| **Data and Visualization** | Dashboards, datasets, analysis notebooks |
| **Accessibility and Social Impact** | Tools that make technology more inclusive and useful |
| **Documentation and Design** | Technical docs, tutorials, UI/UX design, translations |

---

## Ways to Contribute

### Propose a New Idea

Have a project idea you would like to build with the community?

1. Open a new issue using the **Project Proposal** template, or title it `Proposal: <project name>`.
2. Include:
   - **Problem statement:** what problem the project solves
   - **Proposed solution:** what you plan to build
   - **Tech stack:** languages, frameworks, and tools (suggested)
   - **Scope:** a realistic outline of what can be built in the contribution period
   - **Roles needed:** frontend, backend, ML, design, documentation, testing, etc.
3. Maintainers will review the proposal and respond with feedback, a request for changes, or approval.

### Submit an Existing Project

Already built something relevant? You can submit it for inclusion.

1. Fork this repository.
2. Create a directory at `projects/<project-name>/`.
3. Include a `README.md` in that directory containing:
   - Project overview and purpose
   - Setup and usage instructions
   - Tech stack
   - Screenshots or a demo link, if available
   - License information
4. Open a pull request titled `Project: <project name>`.

You must be the author or hold the rights to share the work.

### Contribute to an Existing Project

Look for issues labelled `good first issue` or `help wanted`. Comment on the issue to be assigned before you start working.

### Improve the Repository

Bug fixes, documentation improvements, test coverage, refactoring, and CI improvements are all valid contributions.

---

## Proposal and Review Process

```
Proposal / Submission  →  Maintainer Review  →  Feedback  →  Approval  →  Development  →  Merge
```

| Stage | What Happens |
|---|---|
| **Submission** | You open an issue (proposal) or a pull request (existing project). |
| **Review** | Maintainers evaluate scope, originality, quality, and fit with our focus areas. |
| **Feedback** | You may be asked to clarify the scope, adjust the approach, or improve documentation. |
| **Approval** | Accepted proposals are labelled `approved` and added to the project board. |
| **Development** | Contributors collaborate through issues and pull requests. |
| **Merge** | Pull requests are reviewed and merged once they meet the guidelines below. |

**What we typically accept:** original, useful, well-documented work with a clear scope and an open source license.

**What we typically decline:** duplicate or trivial submissions, projects without clear documentation, work that cannot be licensed openly, and anything that violates our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## Contribution Workflow

```bash
# 1. Fork the repository and clone your fork
git clone https://github.com/codementees/open-source-hub.git
cd open-source-hub

# 2. Add the upstream remote
git remote add upstream https://github.com/codementees/open-source-hub.git

# 3. Create a feature branch
git checkout -b feat/short-description

# 4. Make your changes and commit
git add .
git commit -m "feat: short description of the change"

# 5. Keep your branch up to date
git fetch upstream
git rebase upstream/main

# 6. Push and open a pull request
git push origin feat/short-description
```

When opening a pull request, describe **what** changed and **why**, and link the related issue (for example, `Closes #12`).

We follow [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, `chore:`, `test:`, `refactor:`).

---

## Guidelines

- **Quality over quantity.** Low-effort, spam, or automated pull requests will be closed and may be marked invalid.
- **Discuss before building.** For significant changes, open or comment on an issue first.
- **Keep pull requests focused.** One pull request should address one concern.
- **Write maintainable code.** Follow the existing style, add comments where helpful, and include tests where applicable.
- **Document your work.** New features and projects must include clear setup and usage instructions.
- **Respect licensing.** Do not submit code you do not have the right to share. Projects must carry an open source license.
- **Be respectful.** Follow the [Code of Conduct](CODE_OF_CONDUCT.md) in all interactions.

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed instructions.

---

## Current Event

### Hacktoberfest 2026

We are participating in Hacktoberfest 2026.

1. Register at [hacktoberfest.com](https://hacktoberfest.com).
2. Contribute through pull requests to this repository during the event period.
3. Valid, accepted contributions are labelled `hacktoberfest-accepted` by the maintainers.

This repository is tagged with the `hacktoberfest` topic. Contributions outside the event period are still welcome. Please refer to the official Hacktoberfest website for the current rules and eligibility requirements.

---

## Repository Structure

```
.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── project_proposal.md
│   │   └── bug_report.md
│   └── PULL_REQUEST_TEMPLATE.md
├── projects/
│   └── <project-name>/
│       ├── README.md
│       └── ...
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

---

## Community and Support

- **Questions and ideas:** [GitHub Discussions](../../discussions)
- **Bugs and proposals:** [GitHub Issues](../../issues)
- **Chat:** `<Discord / Slack / WhatsApp link>`
- **Email:** `<maintainer-email@example.com>`

---

## Contributors

Thank you to everyone who contributes to this repository.

<a href="../../graphs/contributors">
  <img src="https://contrib.rocks/image?repo=codementees/open-source-hub" alt="Contributors" />
</a>

---

## License

Distributed under the [MIT License](LICENSE). See `LICENSE` for details. Individual projects under `projects/` may carry their own license, which is stated in their respective directories.

---

<div align="center">

Maintained by **CodeMentees Team**

</div>
