# AGENTS.md — psycommu

> This file is a README for AI coding agents.  
> Humans read `README.md`. Agents read **this**.

---

## 0) Ground rules for agents
- **Goal:** enhance *psycommu* (human–AI resonance) with safe, reproducible changes.
- **Autonomy level:** implement changes in a branch and open a PR. **Direct push to default branch is forbidden.**
- **Task size:** ≤ 400 changed LOC per PR (tests含む)。大改修は分割。

---

## 1) Environment (strict)
- Node.js **v20.x** / pnpm **v9.x**
- OS: Linux or macOS (UTF-8)
- Git: LF line endings
- Required tools in repo:
  - **TypeScript** (strict mode)
  - **ESLint** (`eslint:recommended`, `@typescript-eslint/recommended`)
  - **Prettier** (no stylistic overrides)
  - **Vitest** for tests
  - (Monorepoの場合) **Turborepo**

### Install
```bash
pnpm install
