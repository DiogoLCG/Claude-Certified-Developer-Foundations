# Claude Certified Developer – Foundations (CCDV-F): Exam Prep

## Approach

1. **Learn the concepts** — Claude, prompting, API basics, tool use, safety.
2. **Practice the technical skills** — API requests, tool calling, structured outputs, application workflows.
3. **Take mock exams** — exam-style questions, find weak areas, repeat.

---

## 1. Exam Overview

| | |
|---|---|
| **Certification** | Claude Certified Developer – Foundations |
| **Exam code** | CCDV-F |
| **Format** | Multiple choice / multiple response |
| **Duration** | 120 minutes |
| **Passing score** | 720 / 1000 (scaled) |
| **Provider** | Pearson VUE |
| **Validity** | 12 months |
| **Fee** | ~$125 USD (confirm on the registration portal) |

The exam is developer-oriented: it tests building applications, using APIs, working with tools, troubleshooting, optimizing and securing Claude-based systems — not just prompting.

> **Important:** An exam guide update is scheduled for **December 7, 2026**. If you sit the exam after that date, use the updated blueprint rather than relying only on older practice materials.

---

## 2. Exam Domains

Sorted by weight (from the published blueprint).

| # | Domain | Weight |
|---|---|---|
| 2 | Applications & Integration ⭐ | 33.1% |
| 5 | Model Selection & Optimization | 16.8% |
| 1 | Agents & Workflows | 14.7% |
| 6 | Prompt & Context Engineering | 11.0% |
| 8 | Tools & MCP | 10.6% |
| 7 | Security & Safety | 8.1% |
| 3 | Claude Code | 3.1% |
| 4 | Evaluation, Testing & Debugging | 2.6% |

### Domain 2 — Applications & Integration (33.1%) ⭐ Highest priority
- Claude API fundamentals, Messages API
- API requests and responses
- Streaming
- Tool use
- Image and multimodal input
- Error handling
- API integration and SDK fundamentals
- Application architecture and configuration management
- Production application design

### Domain 5 — Model Selection & Optimization (16.8%)
- Choosing the correct Claude model; model tradeoffs
- Tokens and token counting
- Context windows
- Latency and performance optimization
- Cost optimization
- Prompt caching
- Batch processing
- Thinking / reasoning options

### Domain 1 — Agents & Workflows (14.7%)
- What an agent is and how the agent loop works
- Agent architecture
- Multi-step workflows
- Subagents and supervisor patterns
- Agent SDK and custom agent loops
- Tool-based agent workflows
- Choosing between a workflow and an autonomous agent

### Domain 6 — Prompt & Context Engineering (11%)
- System prompts, user prompts, instruction hierarchy
- Prompt structure
- Few-shot examples
- Structured output
- Context management and context window optimization
- Context bloat and compaction
- Handling long conversations

### Domain 8 — Tools & MCP (10.6%)
- Tool calling, tool definitions, JSON schemas
- Tool execution loops
- Tool errors and validation
- MCP concepts: clients and servers
- MCP resources, prompts and tools
- MCP transport types
- Built-in tools vs custom tools vs Skills vs MCP

### Domain 7 — Security & Safety (8.1%)
- Prompt injection and untrusted inputs
- Tool security and permission management
- Data leakage and PII
- Guardrails
- Secure API key handling
- Human approval for dangerous actions
- Safe agent design

### Domain 3 — Claude Code (3.1%)
- Claude Code fundamentals and configuration
- CLAUDE.md, rules and instructions
- Skills, commands, agents
- Settings
- Hooks
- Headless mode

### Domain 4 — Evaluation, Testing & Debugging (2.6%)
- Troubleshooting API errors
- Debugging agent behavior and tracing failures
- Evaluation basics
- Distinguishing model errors from application errors
- Retry and recovery strategies

---

## 3. Resources

### A. Official (start here)
- **[Anthropic Academy](https://anthropic.skilljar.com/)** — free official courses (with certificates) on the API, MCP, Agent Skills and Claude Code.
- **[Claude API documentation](https://platform.claude.com/docs/en/build-with-claude/overview)** — primary technical reference: API, models, tool use, streaming, integrations.
- **[Claude Code best practices](https://www.anthropic.com/engineering/claude-code-best-practices)** — configuration, CLAUDE.md, hooks, agentic coding workflows.
- **[Model Context Protocol (MCP)](https://modelcontextprotocol.io)** — how MCP connects AI applications to external tools, data and services.
- **[Anthropic Engineering blog](https://anthropic.com/engineering)** — agents, tools and context engineering articles.
- **[Claude Cookbooks](https://github.com/anthropics/claude-cookbooks)** — runnable code examples.

### B. Practice questions and mock exams (unofficial)

> These are independently written — not Anthropic exam questions, and not guaranteed to match the real exam.

| Resource | Cost | What it offers |
|---|---|---|
| **Bytefork** (recommended start) | Free, no sign-up | 139 questions, study guide, practice by topic |
| **LearningClaude** | Free | Topic study guides, runnable demos, 8 domains, 3 mock papers, 77 questions |
| **WeClaudeCode** | Free | Full syllabus, practice questions, domain material, mock exam, 4-week plan |
| **Claude Certification Guides** | Free | Diagnostic test, mock exam, flashcards, lessons, practice by domain |
| **Udemy practice tests** | Paid | Diagnostic, learning and full mock tests with explanations — check it matches the current blueprint |

---

## 4. 3-Week Study Plan

Assumes ~1.5–2 hours/day, 5 days/week.

### How to study each topic
1. **Read (20–30 min)** — the official doc page; skim, then re-read the code parts.
2. **Build (30–45 min)** — run the doc example, then change one thing (parameter, schema, error case).
3. **Test (20–30 min)** — 10–15 practice questions on that domain; for each wrong answer, write *why* the right one is right.
4. **Summarize (5 min)** — 3–5 lines in your notes. These become your Week 3 revision material.

> Short on time? Skip reading, not building or testing.

### Week 1 — API & Fundamentals
*Goal: understand Claude as a developer platform.*
- [ ] Claude models and capabilities
- [ ] API basics and Messages API
- [ ] System prompts and prompt engineering
- [ ] Tokens and context windows
- [ ] JSON and structured outputs
- [ ] Streaming
- [ ] API errors
- [ ] Cost optimization and prompt caching
- [ ] Batch processing and extended thinking
- [ ] **Project:** CLI chat with streaming, structured JSON output and token count per turn
- [ ] 30–40 practice questions

| Topic | Resource |
|---|---|
| Main course | [Academy: Claude with the Anthropic API](https://anthropic.skilljar.com/claude-with-the-anthropic-api) |
| Platform overview | [Academy: Claude Platform 101](https://anthropic.skilljar.com/claude-platform-101) |
| Messages API / streaming | [Messages API reference](https://platform.claude.com/docs/en/api/messages/create) |
| Prompt engineering | [Prompt engineering docs](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering.md) · [Interactive tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) (written for Claude 3) |
| Model selection | [Choosing a model](https://docs.claude.com/en/docs/about-claude/models) |
| Prompt caching | [Prompt caching](https://docs.claude.com/en/docs/build-with-claude/prompt-caching) |
| Batch processing | [Message Batches](https://platform.claude.com/docs/en/build-with-claude/batch-processing) |
| Thinking | [Extended thinking](https://platform.claude.com/docs/en/build-with-claude/extended-thinking) |

### Week 2 — Tools, Agents & Security
*Goal: build interactive applications and agents, and run them safely.*
- [ ] Tool use / function calling
- [ ] Tool schemas
- [ ] Agent loops and Agent SDK
- [ ] Workflows vs agents
- [ ] MCP servers and clients
- [ ] Security and prompt injection
- [ ] Claude Code, CLAUDE.md, skills and hooks
- [ ] Evaluation and debugging
- [ ] **Project:** agent with 2–3 custom tools + a small MCP server; try a prompt injection via a tool result, then defend against it
- [ ] 40–50 practice questions

| Topic | Resource |
|---|---|
| Agents (read first) | [Building effective agents](https://anthropic.com/engineering/building-effective-agents) |
| Tool design | [Writing effective tools for agents](https://anthropic.com/engineering/writing-tools-for-agents) |
| Context engineering | [Effective context engineering for AI agents](https://anthropic.com/engineering/effective-context-engineering-for-ai-agents) |
| Agent SDK | [Agent SDK overview](https://platform.claude.com/docs/agent-sdk/intro) · [Building agents with the Agent SDK](https://anthropic.com/engineering/building-agents-with-the-claude-agent-sdk) |
| MCP | [modelcontextprotocol.io](https://modelcontextprotocol.io) · Academy: *Introduction to MCP* |
| Security | [Mitigate jailbreaks and prompt injections](https://platform.claude.com/docs/en/test-and-evaluate/strengthen-guardrails/mitigate-jailbreaks) |
| Claude Code | [Claude Code best practices](https://www.anthropic.com/engineering/claude-code-best-practices) · Academy: *Claude Code in Action* |

**Videos** (verify links before relying on them):
- [How to Build Effective AI Agents](https://www.youtube.com/watch?v=LP5OCa20Zpg) — Anthropic
- [How We Build Effective Agents](https://www.youtube.com/watch?v=D7_ipDqhtwk) — Barry Zhang, AI Engineer Summit 2025
- [Building Agents with MCP](https://www.youtube.com/watch?v=kQmXtrmQ5Zg) — Mahesh Murag (workshop)
- [Claude Code best practices](https://www.youtube.com/watch?v=gv0WHhKelSE) — Cal Rueb

### Week 3 — Exam Preparation
*Goal: train for the format and eliminate weaknesses. Use the practice sites in section 3B and your Week 1–2 summaries.*
- [ ] Review weak domains
- [ ] Mock exam 1 → review every incorrect answer
- [ ] Mock exam 2 → revise notes
- [ ] Mock exam 3 (timed) → review mistakes
- [ ] Final revision

---

## Readiness Target

Consistently score **80–85%+** on independent timed practice exams, and be able to explain *why* each answer is correct. (A preparation target, not an official passing-score conversion.)
