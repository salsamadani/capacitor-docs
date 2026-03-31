# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

## Project Overview

Capacitor documentation site built with Docusaurus. Source for https://capacitorjs.com/docs.

## Build & Development

```bash
npm install
npm start        # Start dev server
npm run build    # Production build
```

## Installed Plugins

### everything-claude-code (v0.1.0)
Source: https://github.com/affaan-m/everything-claude-code

Available slash commands:
- `/plan` - Implementation planning
- `/tdd` - Test-driven development
- `/code-review` - Quality review
- `/e2e` - E2E test generation
- `/build-fix` - Fix build errors
- `/refactor-clean` - Dead code removal
- `/learn` - Extract patterns from sessions
- `/verify` - Run verification loop
- `/update-docs` - Update documentation

Available agents (28): planner, architect, tdd-guide, code-reviewer, security-reviewer, build-error-resolver, e2e-runner, refactor-cleaner, doc-updater, docs-lookup, typescript-reviewer, python-reviewer, go-reviewer, rust-reviewer, java-reviewer, kotlin-reviewer, cpp-reviewer, database-reviewer, and more.

Skills: coding-standards, backend-patterns, frontend-patterns, tdd-workflow, security-review, continuous-learning, and 60+ more.
