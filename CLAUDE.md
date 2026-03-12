# CLAUDE.md

This file provides guidance for AI assistants working with this repository.

## Repository Overview

**best-repo-ever** is a minimal demonstration repository created by Chris Nugent (bignuge). It contains no application code — it serves as a learning/practice repository for exploring GitHub workflows such as branching, pull requests, and merge conflict resolution.

## Repository Structure

```
best-repo-ever/
├── README.md       # Project readme with brief notes
├── bigFile.md      # A large Lorem ipsum placeholder file
└── CLAUDE.md       # This file
```

### File Descriptions

- **README.md** — A short readme with placeholder change notes. Not a technical document.
- **bigFile.md** — A large file containing Lorem ipsum filler text. Not functionally significant; likely used for testing file size handling or diff tooling.

## Git History & Workflow Conventions

The repository's commit history shows a standard GitHub pull request workflow:

1. Feature branches are created off `master` (e.g. `myfeaturebranch`, `new-branch-1`, `new-branch-2`).
2. Changes are committed to the feature branch.
3. A pull request is opened and merged into `master`.
4. Merge conflicts are resolved with an explicit commit before merging.

### Branch Naming

Historical branches follow simple descriptive names (`myfeaturebranch`, `new-branch-1`, `new-branch-2`). There are no enforced naming conventions beyond that.

### Commit Style

Commits use short, plain-English messages (e.g. `"My first commit"`, `"Changes to the README"`, `"More changes to the README"`). No conventional commit format (feat/fix/chore) is enforced.

## Development Workflow

Since this repo has no build system, test suite, linter, or package manager, the workflow is purely git-based:

1. Create a branch from `master`.
2. Make changes to files.
3. Commit with a descriptive message.
4. Push the branch and open a pull request against `master`.
5. Resolve any merge conflicts if they arise.
6. Merge the PR.

## Key Conventions for AI Assistants

- **No build or test commands** — there is nothing to build, test, or lint.
- **No dependencies** — there is no `package.json`, `requirements.txt`, `Makefile`, or similar.
- **Markdown only** — all files are Markdown; edits should preserve valid Markdown formatting.
- **Base branch is `master`** — not `main`.
- **Keep changes minimal** — this repo exists for workflow demonstration, not feature development. Avoid adding unnecessary files or complexity.
