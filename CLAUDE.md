# CLAUDE.md

> **A guide for AI assistants working in this repository.**

---

## Repository Overview

| Field            | Value                                          |
| ---------------- | ---------------------------------------------- |
| **Repository**   | `caude-test`                                   |
| **Status**       | Newly initialized (no source code yet)         |
| **Branch**       | `claude/claude-md-mlpvybcllkc349x6-74pfb`      |
| **Created**      | February 2026                                  |

---

## Project Structure

```
caude-test/
│
├── CLAUDE.md            # <-- You are here! AI assistant guide
│
├── src/                 # Application source code (to be added)
│   ├── components/      #     UI components
│   ├── utils/           #     Utility/helper functions
│   └── index.*          #     Entry point
│
├── tests/               # Test files (to be added)
│
├── docs/                # Documentation (to be added)
│
├── package.json         # Dependencies & scripts (to be added)
│
└── .gitignore           # Git ignore rules (to be added)
```

> **Note:** This tree is a suggested starting layout. Update it as the project grows.

---

## Development Workflows

### Getting Started

```bash
# 1. Clone the repository
git clone <repo-url>
cd caude-test

# 2. Install dependencies (once package.json exists)
npm install        # or: yarn install / pnpm install

# 3. Start development server
npm run dev        # or: yarn dev / pnpm dev
```

> Update the commands above once a tech stack is chosen.

---

### Quick Reference Commands

| Task              | Command               | Status           |
| ----------------- | --------------------- | ---------------- |
| Install deps      | `npm install`         | Not configured   |
| Dev server        | `npm run dev`         | Not configured   |
| Build             | `npm run build`       | Not configured   |
| Run tests         | `npm test`            | Not configured   |
| Lint              | `npm run lint`        | Not configured   |
| Format            | `npm run format`      | Not configured   |

> Replace with actual commands as the project is set up.

---

## Code Conventions

### Naming

| Element          | Convention           | Example                  |
| ---------------- | -------------------- | ------------------------ |
| Files            | kebab-case           | `user-profile.ts`        |
| Variables        | camelCase            | `userName`               |
| Functions        | camelCase            | `getUserById()`          |
| Classes          | PascalCase           | `UserService`            |
| Constants        | UPPER_SNAKE_CASE     | `MAX_RETRIES`            |
| Components       | PascalCase           | `UserProfile`            |

### Style Rules

- **Indentation:** 2 spaces
- **Quotes:** Single quotes for strings
- **Semicolons:** As per chosen linter config
- **Line length:** Max 100 characters
- **Trailing commas:** Yes (ES5+)

> Adjust these once a linter/formatter (ESLint, Prettier, etc.) is configured.

---

## Key Patterns and Architecture

```
+-----------------------------------------------------+
|                    APPLICATION                       |
|                                                      |
|   +-------------+   +-------------+   +-----------+  |
|   |    Views    |-->|  Services   |-->|   Data    |  |
|   | (UI Layer)  |   | (Business   |   | (Storage/ |  |
|   |             |   |  Logic)     |   |  API)     |  |
|   +-------------+   +-------------+   +-----------+  |
|                                                      |
+-----------------------------------------------------+
```

> This is a placeholder architecture diagram. Replace with your actual design once established.

---

## Dependencies

### Core

| Package          | Purpose                      | Version |
| ---------------- | ---------------------------- | ------- |
| *(none yet)*     | —                            | —       |

### Dev

| Package          | Purpose                      | Version |
| ---------------- | ---------------------------- | ------- |
| *(none yet)*     | —                            | —       |

> Populate this table as dependencies are added to `package.json`.

---

## Environment and Configuration

### Environment Variables

| Variable         | Description                  | Required | Default  |
| ---------------- | ---------------------------- | -------- | -------- |
| `NODE_ENV`       | Runtime environment          | No       | `development` |
| `PORT`           | Server port                  | No       | `3000`   |
| `DATABASE_URL`   | Database connection string   | Yes      | —        |
| `API_KEY`        | External API key             | Yes      | —        |

> These are examples. Update with actual env vars as the project is configured.

### Config Files

| File                | Purpose                              |
| ------------------- | ------------------------------------ |
| `.env`              | Local environment variables (gitignored) |
| `.env.example`      | Template for required env vars       |
| `tsconfig.json`     | TypeScript configuration             |
| `.eslintrc.*`       | ESLint rules                         |
| `.prettierrc`       | Prettier formatting rules            |

---

## Common Tasks for AI Assistants

### Do's

- **Read before editing** — Always read files before modifying them
- **Run tests after changes** — Validate that nothing is broken
- **Follow existing patterns** — Match the style already in the codebase
- **Keep changes minimal** — Only modify what is necessary
- **Update this file** — Reflect new workflows, deps, or conventions here

### Don'ts

- **Don't add unnecessary files** — Prefer editing existing files
- **Don't over-engineer** — Solve the problem at hand, not hypothetical ones
- **Don't skip validation** — Always run lint/test commands when available
- **Don't commit secrets** — Never commit `.env`, API keys, or credentials

---

### Commit Message Format

```
<type>: <short summary>

<optional body with more detail>
```

**Types:**

| Type         | When to use                              |
| ------------ | ---------------------------------------- |
| `feat`       | New feature                              |
| `fix`        | Bug fix                                  |
| `docs`       | Documentation changes                    |
| `style`      | Formatting, no code change               |
| `refactor`   | Code restructuring, no behavior change   |
| `test`       | Adding or updating tests                 |
| `chore`      | Build, tooling, or maintenance tasks     |

**Examples:**
```
feat: add user authentication flow
fix: resolve null pointer in cart checkout
docs: update CLAUDE.md with test commands
```

---

*Last updated: February 17, 2026*
