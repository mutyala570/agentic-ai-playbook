# My Agentic AI Learning Path

A structured plan to go from LLM basics to building multi-agent systems, using the 5 books in [`books/`](books/). Code for every book lives in its numbered folder; my own summaries live in [`notes/`](notes/).

## The Golden Rule

> **Never read passively.** After every chapter, build something — even just re-implementing the book's example from memory. Code I wrote is code I remember.

---

## Phase 1 — Foundations (Weeks 1–3)

### Book 1: Generative AI with LangChain
📖 `books/01_Generative_AI_with_LangChain.pdf` · 💻 `01-langchain-basics/`

Learn the building blocks everything else depends on:
- How LLMs are used inside applications
- Prompts, chains, and output parsing
- RAG (retrieval-augmented generation)
- Memory and basic agents / tool use

**Done when:** I can build a small RAG chatbot from scratch without copying code.

### Book 2: Agentic Coding with Claude Code *(read in parallel with Book 1)*
📖 `books/02_Agentic_Coding_with_Claude_Code_-_Eden_Marco.pdf` · 💻 `02-claude-code/`

Learn the tool I'll use to build everything else faster:
- Claude Code workflows, planning, and prompting habits
- CLAUDE.md, skills, and project setup
- Using AI for refactoring, debugging, and reviewing

**Done when:** I use Claude Code daily and it genuinely speeds me up.

---

## Phase 2 — Practice (Weeks 4–8)

### Book 3: 30 Agents Every AI Engineer Must Build
📖 `books/03_30_Agents_Every_AI_Engineer_Must_Build_-_Imran_Ahmad.pdf` · 💻 `03-30-agents/`

Hands-on phase. **Don't do all 30 in order** — do the first few, then pick the ones most relevant to my work.

- One subfolder per agent: `03-30-agents/agent-01-<name>/`
- Each agent gets its own small README: what it does, what I learned, what broke

**Target:** 8–10 agents built and working.

---

## Phase 3 — Design (Weeks 9–11)

### Book 4: Agentic Architectural Patterns
📖 `books/04_Agentic_Architectural_Patterns_for_Building_Agents_-_Ali_Arsanjani.pdf` · 💻 `04-architectural-patterns/`

Now that I've *felt* the pain points, learn to design agents properly:
- Planner–executor, reflection, routing, orchestration patterns
- Guardrails and evaluation
- When to use which pattern (and when not to use agents at all)

**Done when:** I've gone back and refactored at least 2 of my Phase 2 agents using these patterns.

---

## Phase 4 — Advanced (Week 12+)

### Book 5: Context Engineering for Multi-Agent Systems
📖 `books/05_Context_Engineering_for_Multi-Agent_Systems_-_Denis_Rothman.pdf` · 💻 `05-context-engineering/`

The most advanced topic — read last:
- Managing context across multiple cooperating agents
- Agent-to-agent communication and shared state
- Failure modes of multi-agent systems and how to avoid them

**Done when:** I can build a small multi-agent system where agents hand off work reliably.

---

## Repo Structure

```
agentic-ai-playbook/
├── books/                     # the 5 PDFs (reading order = file number)
├── 01-langchain-basics/       # code per book, numbered in learning order
├── 02-claude-code/
├── 03-30-agents/
├── 04-architectural-patterns/
├── 05-context-engineering/
├── notes/                     # one markdown summary per book
└── LEARNING_PATH.md           # this file
```

## Habits for Revision

1. **After each chapter:** write 3–5 bullet points in `notes/` in my own words.
2. **After each project:** commit with a message describing what I learned, not just what I built.
3. **Weekly:** skim my notes from the previous week before starting new material.
4. **When stuck later at work:** search this repo first — past-me probably solved it.

## Progress Tracker

- [ ] Book 1 — Generative AI with LangChain
- [ ] Book 2 — Agentic Coding with Claude Code
- [ ] Book 3 — 30 Agents (target: 8–10 agents)
- [ ] Book 4 — Agentic Architectural Patterns
- [ ] Book 5 — Context Engineering for Multi-Agent Systems
