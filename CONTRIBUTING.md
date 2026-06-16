# Contributing to Nivotics Lab

Thank you for taking the time to contribute. Nivotics Lab is a practical technology ecosystem, and every issue filed, bug fixed, and feature built here is real work that matters — to our team, to our learners, and to the developer community.

This guide covers everything you need to get started.

---

## Table of Contents

1. Code of Conduct
2. How you can contribute
3. Reporting bugs
4. Requesting features
5. Submitting pull requests
6. Commit message style
7. Code style
8. For Nivotics Academy learners

---

## 1. Code of Conduct

By participating in this project, you agree to our Code of Conduct. Please read it. We hold ourselves and our contributors to a simple standard: be respectful, be constructive, and be professional.

---

## 2. How You Can Contribute

There are many ways to contribute — you do not need to be an expert:

- Report a bug you found while using one of our tools
- Suggest a feature or improvement
- Fix a bug or implement a feature from the issue tracker
- Improve documentation, examples, or README files
- Review open pull requests and leave helpful feedback
- Share our tools with developers who would benefit from them

---

## 3. Reporting Bugs

Before opening a bug report, please search the existing issues to make sure it has not already been reported.

When filing a bug, use the Bug Report issue template and include:

- A clear, specific title
- Steps to reproduce the problem
- What you expected to happen
- What actually happened
- Your environment (OS, browser, WordPress version, PHP version, etc.)
- Screenshots or error logs if available

The more detail you provide, the faster we can help.

---

## 4. Requesting Features

We welcome feature requests. Use the Feature Request issue template and explain:

- The problem you are trying to solve
- The solution you would like to see
- Any alternatives you have considered

Not every request will be accepted, but every one will be read.

---

## 5. Submitting Pull Requests

### Before you start

For significant changes, please open an issue first and discuss your approach. This saves both your time and ours.

### The process

1. Fork the repository
2. Create a branch from `dev`, not `main`: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Write or update tests if applicable
5. Run the project locally and confirm it works
6. Submit a PR into the `dev` branch, never directly into `main`
7. Fill in the pull request template completely

### Pull request rules

- One pull request per feature or fix — keep it focused
- PRs that touch unrelated files will be asked to be split
- All CI checks must pass before a review begins
- At least one maintainer review is required before merging

---

## 6. Commit Message Style

We use a simple conventional commit format:

type: short description in present tense

Types:

- `feat:` — a new feature
- `fix:` — a bug fix
- `docs:` — documentation changes only
- `style:` — formatting, no logic change
- `refactor:` — code restructure, no behaviour change
- `test:` — adding or updating tests
- `chore:` — build, config, dependency updates

Examples:
feat: add dark mode support to admin dashboard

fix: resolve PHP warning on plugin activation

docs: update installation steps in README

---

## 7. Code Style

Each repository will have its own code style configuration. Generally:

- PHP: follow WordPress Coding Standards
- JavaScript: use ESLint with the project config
- CSS: follow BEM naming where applicable
- Always use meaningful variable and function names
- Comment your code where the why is not obvious from the what

---

## 8. For Nivotics Academy Learners

If you are a learner from Nivotics Academy, your contributions to Nivotics-Lab repositories count as real, verifiable portfolio work. When submitting your first pull request:

- Mention in the PR description that you are a Nivotics Academy learner
- Link to your Academy profile or cohort if applicable
- Feel free to ask questions — every maintainer here has been a learner too

We review Academy learner PRs with that context in mind and will always take the time to give constructive feedback, whether or not the PR is merged.

---

Questions about contributing? Reach out at nivoticslab@gmail.com.
