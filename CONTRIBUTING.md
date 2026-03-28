# Contributing to OpenNest

Welcome to the **OpenNest Training Ground** 🚀  
This repository helps members learn Git, open-source collaboration, and real-world workflows. Whether you're a complete beginner or brushing up on the basics, you're in the right place.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Contribution Workflow](#contribution-workflow)
- [Branch Naming Convention](#branch-naming-convention)
- [Making Good Commits](#making-good-commits)
- [Opening a Pull Request](#opening-a-pull-request)
- [Contribution Guidelines](#contribution-guidelines)
- [Beginner-Friendly Tasks](#beginner-friendly-tasks)
- [OpenNest Philosophy](#opennest-philosophy)

---

## Getting Started

### 1. Fork & Clone the Repository

```bash
git clone https://github.com/your-username/opennest.git
cd opennest
```

### 2. Create a Branch

Use the naming convention: `type/your-name-or-description`

```
feature/rishabh-intro
task/git-practice
docs/update-readme
fix/broken-link
```

```bash
git checkout -b feature/your-name-task
```

### 3. Choose a Task

Pick something that matches your current skill level:

| Task | Description |
|------|-------------|
| Introduce yourself | Add a short profile under `introduce-yourself/` |
| Practice Git | Work through beginner Git exercises |
| Improve docs | Fix typos, clarify instructions, update examples |
| Fix an issue | Look for open issues labelled `good first issue` |

### 4. Make Your Changes

Keep contributions **small**, **clear**, and **focused**.

**Example — introduce yourself** by creating `introduce-yourself/your-name.md`:

```markdown
# Your Name

## About Me
A short sentence or two about who you are.

## Interests
- Web Development
- AI/ML

## Goals
- Learn open source
- Build real projects

## Skills
Beginner / Intermediate / Advanced
```

---

## Contribution Workflow

```
1. Create a branch
        ↓
2. Make your changes
        ↓
3. Commit with a clear message
        ↓
4. Push to your fork
        ↓
5. Open a Pull Request
        ↓
6. Address review feedback
        ↓
7. Merge 🎉
```

---

## Branch Naming Convention

| Prefix | When to use |
|--------|-------------|
| `feature/` | Adding something new |
| `fix/` | Fixing a bug or broken content |
| `docs/` | Documentation updates |
| `task/` | Completing a training task |

**Examples:**

```
feature/add-introduction
docs/update-readme
fix/broken-link
task/git-practice
```

---

## Making Good Commits

Write commit messages that clearly describe *what changed* and *why*.

✅ **Good:**
```
Add introduction for Rishabh Kumar
Fix broken link in README
Update beginner tasks documentation
```

❌ **Avoid:**
```
update
changes
fix
asdf
```

A good rule of thumb: if you can't summarise your commit in one short sentence, it's probably doing too much — split it up.

---

## Opening a Pull Request

Once your changes are ready:

1. Push your branch: `git push origin feature/your-branch-name`
2. Go to the repository on GitHub and click **New Pull Request**
3. Fill in:
   - **Title** — e.g. `Add introduction for Rishabh Kumar`
   - **Description** — what you changed and why
   - **Linked issue** — reference any related issue with `Closes #123`
4. Submit and wait for a review

---

## Contribution Guidelines

- Keep commits clean and atomic (one logical change per commit)
- Follow the existing folder structure
- Write clear, descriptive commit messages
- Be respectful and constructive in code reviews
- Help other contributors — we're all learning here

---

## Beginner-Friendly Tasks

Not sure where to start? Filter issues by these labels:

- `good first issue`
- `beginner`
- `training`

These are specifically curated for new contributors and are a great way to get comfortable with the workflow before tackling larger tasks.

---

## OpenNest Philosophy

> **Build over talk. Learn by doing. Collaborate openly. Help others grow.**

- Ship something, however small
- Mistakes are part of the process
- Every contribution counts

---

Welcome to **OpenNest** — Build • Learn • Collaborate • Ship 🚀