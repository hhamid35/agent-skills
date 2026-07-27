# Agent Skills

A collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities.

Skills follow the [Agent Skills](https://agentskills.io/) format.

[![skills.sh](https://skills.sh/b/vercel-labs/agent-skills)](https://skills.sh/vercel-labs/agent-skills)

## Available Skills

### Languages & Frameworks

| Skill | Description |
| --- | --- |
| [`python-pro`](skills/python-pro) | Build Python 3.11+ apps with type safety, async patterns, mypy strict mode, and pytest suites validated with black and ruff. |
| [`javascript-pro`](skills/javascript-pro) | Write, debug, and refactor modern JavaScript (ES2023+) with async/await, ESM modules, and Node.js/browser performance in mind. |
| [`typescript`](skills/typescript) | TypeScript style and type-safety guide for TS/TSX/MTS — fixing types, `interface` vs `type`, avoiding `any`, `import type`, and async flow. |
| [`fastapi-expert`](skills/fastapi-expert) | Build high-performance async Python APIs with FastAPI and Pydantic V2 — REST endpoints, auth flows, async SQLAlchemy, WebSockets, and OpenAPI. |
| [`react-native-architecture`](skills/react-native-architecture) | Architect production React Native apps with Expo, navigation, native modules, offline sync, and cross-platform patterns. |
| [`react-native-design`](skills/react-native-design) | Master React Native styling, navigation, and Reanimated animations for cross-platform mobile development. |
| [`expo-api-docs`](skills/expo-api-docs) | Write TSDoc comments for Expo SDK APIs following official conventions (`@platform`, `@example`, `@deprecated`, `@default`). |

### Architecture & Design

| Skill | Description |
| --- | --- |
| [`architecture-designer`](skills/architecture-designer) | Design high-level system architecture, author ADRs, evaluate technology trade-offs, and plan for scalability. |
| [`fullstack-guardian`](skills/fullstack-guardian) | Build security-focused full-stack features across frontend, backend, and database with layered security at every level. |
| [`websocket-engineer`](skills/websocket-engineer) | Build real-time systems with WebSockets/Socket.IO — bidirectional messaging, Redis scaling, presence, and room management. |
| [`database-optimizer`](skills/database-optimizer) | Optimize PostgreSQL and MySQL performance — index design, query rewrites, execution-plan analysis, partitioning, and lock contention. |
| [`mermaid-diagrams`](skills/mermaid-diagrams) | Create software diagrams with Mermaid — class, sequence, flowchart, ERD, C4, state, git graph, and more. |

### Quality, Testing & Review

| Skill | Description |
| --- | --- |
| [`code-reviewer`](skills/code-reviewer) | Analyze diffs and files for bugs, security issues, code smells, and architectural concerns, producing a prioritized review report. |
| [`security-reviewer`](skills/security-reviewer) | Run security audits with severity-rated reports and remediation guidance — SAST, dependency audits, secrets scanning, compliance checks. |
| [`test-master`](skills/test-master) | Generate test files, mocking strategies, and coverage analysis across functional, performance (k6/Artillery), and security testing. |
| [`debugging-wizard`](skills/debugging-wizard) | Parse errors, trace stack traces, correlate logs, and apply hypothesis-driven methodology to find root causes. |

### Process

| Skill | Description |
| --- | --- |
| [`brainstorming`](skills/brainstorming) | Pre-implementation ideation for creative work — features, components, and behavior changes before writing code. |
| [`android-e2e-testing`](skills/android-e2e-testing) | Test Expo Router features on Android emulators using ADB after implementing native features. |

## Skill Structure

Each skill contains:

- `SKILL.md` - Instructions for the agent
- `scripts/` - Helper scripts for automation (optional)
- `references/` - Supporting documentation (optional)
