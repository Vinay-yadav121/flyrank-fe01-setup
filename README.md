# Frontend AI Engineering — FE-01

## Project Overview

This repository documents my development environment and AI-assisted workflow for the FlyRank AI Frontend AI Engineering internship, assignment FE-01: Environment and AI Toolchain.

## Objectives

- Verify Node.js, npm, and Git installations.
- Document the development environment.
- Establish Git and GitHub version-control practices.
- Document AI-assisted development conventions.
- Maintain a clear record of setup and verification.

## Technology Stack

- **Operating system:** Windows
- **Runtime:** Node.js v24.20.0 (Node.js 24 LTS release line)
- **Package manager:** npm 11.19.0
- **Version control:** Git 2.53.0.windows.1
- **Repository hosting:** GitHub
- **Code editor:** Visual Studio Code and Cursor
- **AI assistant:** ChatGPT and Cursor (project conventions in `CLAUDE.md`)

## Environment Verification

The following commands were executed successfully in Windows PowerShell:

```powershell
node --version
# v24.20.0

npm --version
# 11.19.0

git --version
# git version 2.53.0.windows.1
```

These results confirm that Node.js, npm, and Git are available from the terminal.

## Repository Structure

- `README.md` — project overview and environment verification.
- `CLAUDE.md` — AI assistant instructions and development conventions.
- `.gitignore` — files excluded from version control.
- `LICENSE` — repository license.

## Git Workflow

Use focused changes and Conventional Commit messages.

Examples:

- `docs: update environment verification`
- `chore: update project configuration`
- `feat: add initial frontend application`

Before committing, review changes with:

```powershell
git status
git diff
```

Never commit passwords, API keys, access tokens, or `.env` files.

## AI-Assisted Development

ChatGPT is used to help understand requirements, plan implementation, review code, troubleshoot errors, and improve documentation. Cursor is used in the editor for the same kinds of tasks, following the conventions in `CLAUDE.md`. Changes should be reviewed, tested, and understood before submission.

## Current Status

- [x] Node.js, npm, and Git verified.
- [x] GitHub repository initialized.
- [x] AI assistant instructions documented.
- [ ] Confirm all assignment-specific requirements.
- [ ] Capture any required setup evidence.
- [ ] Complete final review and submission.

## Next Steps

Complete the remaining FE-01 requirements, verify all evidence against the FlyRank assignment instructions, and commit the reviewed changes.
