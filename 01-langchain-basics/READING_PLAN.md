# Reading Plan — Generative AI with LangChain (2nd Edition)

📖 Book: [`books/01_Generative_AI_with_LangChain.pdf`](../books/01_Generative_AI_with_LangChain.pdf)
💻 Practice code goes in this folder (`01-langchain-basics/`)
📝 Notes go in [`notes/01-generative-ai-with-langchain.md`](../notes/01-generative-ai-with-langchain.md)

> **Rule:** After each chapter — answer the end-of-chapter Questions, write 3–5 bullets in notes, rebuild one example from memory. Tick the checkbox only after all three.

---

## Week 1 — Foundations

### ☐ Day 1 — Chapter 1: The Rise of Generative AI (pages 1–23)
- Read the full chapter (concepts only, no coding)
- Key ideas: 6 limitations of raw LLMs · what an agent is (LLM + tools + memory + decisions) · LangChain vs LangGraph vs LangSmith
- Answer the 10 Questions on pages 23–24
- ✍️ Write Chapter 1 bullets in notes

### ☐ Day 2 — Chapter 2 (part 1): Setup (pages 25–32)
- Set up Python environment + dependencies (page 26)
- Set up API keys (page 28)
- Clone the book's official code repo (link in Preface)
- ✅ Goal: run one successful LLM call from this folder

### ☐ Day 3 — Chapter 2 (part 2): Building blocks (pages 32–48)
- Model interfaces, chat models, controlling model behavior
- Prompts and templates
- LCEL — LangChain Expression Language (page 42) ← most important part
- 💻 Build: a small chain with a prompt template + LCEL

### ☐ Day 4 — Chapter 2 (part 3): Local models + multimodal (pages 48–63)
- Ollama / Hugging Face local models — *optional, skip if using API keys*
- Multimodal: text-to-image, image understanding (skim)
- Answer Review questions (page 63)
- ✍️ Write Chapter 2 bullets in notes

### ☐ Day 5 — Chapter 3 (part 1): LangGraph fundamentals (pages 67–85)
- State management, reducers, configurable graphs
- Output parsing and error handling
- 💻 Build: a simple two-node LangGraph workflow

### ☐ Day 6 — Chapter 3 (part 2): Prompt engineering (pages 85–93)
- Prompt templates, zero-shot vs few-shot
- Chain of Thought, self-consistency
- 💻 Build: same task with zero-shot vs few-shot — compare results

### ☐ Day 7 — Chapter 3 (part 3): Context + memory (pages 93–104)
- Short context windows, summarizing long content
- Trimming chat history, saving history to DB, LangGraph checkpoints
- Answer Questions (page 104)
- ✍️ Write Chapter 3 bullets in notes

---

## Week 2 — RAG (the big one)

### ☐ Day 8 — Chapter 4 (part 1): RAG concepts (pages 107–127)
- Components of a RAG system, when to use RAG
- Embeddings, vector stores, indexing strategies
- 💻 Build: embed a few texts and run a similarity search

### ☐ Day 9 — Chapter 4 (part 2): RAG pipeline (pages 127–140)
- Document processing, chunking strategies, retrieval
- 💻 Build: load a PDF, chunk it, store in a vector DB

### ☐ Day 10 — Chapter 4 (part 3): Advanced RAG (pages 140–161)
- Hybrid retrieval, re-ranking, query transformation
- Corrective RAG, Agentic RAG, choosing the right technique
- ✍️ Note which techniques you'd actually use

### ☐ Days 11–13 — Chapter 4 PROJECT: Documentation chatbot (pages 161–180)
- Build the corporate documentation chatbot end to end
- Document loading → retrieval → state graph → Streamlit UI
- 💻 This is the **checkpoint project** — must work fully
- Answer Questions (page 180) + write Chapter 4 bullets

### ☐ Day 14 — Buffer / catch-up day
- Finish anything pending from Week 1–2
- Re-read your notes so far (weekly revision habit)

---

## Week 3 — Agents

### ☐ Day 15 — Chapter 5 (part 1): Tools (pages 181–209)
- What is a tool, built-in tools, ReACT
- Custom tools: wrap a Python function, Runnable, StructuredTool
- 💻 Build: an agent with one custom tool you wrote

### ☐ Day 16 — Chapter 5 (part 2): Agents (pages 209–221)
- Tool-calling paradigm, ToolNode, controlled generation
- Plan-and-solve agent
- Answer Questions (page 221) + write Chapter 5 bullets

### ☐ Day 17 — Chapter 6 (part 1): Multi-agent architectures (pages 223–247)
- Agent roles, consensus, communication, handoffs
- Read lightly — Book 5 of the learning path covers this deeply

### ☐ Day 18 — Chapter 6 (part 2): Adaptive systems (pages 248–266)
- Human-in-the-loop, Tree of Thoughts, agent memory
- Answer Questions (page 266) + write Chapter 6 bullets

---

## Week 4 — Production topics (selective reading)

### ☐ Day 19 — Chapter 8: Evaluation and Testing (pages 309–348)
- The most valuable production chapter — read fully
- Why evaluation matters, evaluating agents, offline evaluation
- 💻 Try: evaluate your Day 11–13 chatbot's answers

### ☐ Day 20 — Chapter 9: Deployment and Observability (pages 349–397)
- Read: security (350), FastAPI deployment (354), observability (382)
- Skim the rest — return to it when you actually deploy something

### ☐ Day 21 — Optional / wrap-up
- Chapter 7 (coding + data analysis agents) — skim, pick what's relevant
- Chapter 10 (future of generative AI) — skim or skip, opinion not skills
- ✍️ Final review: re-read all your notes, update LEARNING_PATH.md tracker

---

## Done when

- [ ] Documentation chatbot (Ch 4 project) works end to end
- [ ] I can build a small RAG chatbot from scratch **without copying code**
- [ ] All chapter notes written in `notes/01-generative-ai-with-langchain.md`
- [ ] Marked Book 1 complete in [`LEARNING_PATH.md`](../LEARNING_PATH.md)

→ Next: Book 2 — `02_Agentic_Coding_with_Claude_Code` (`02-claude-code/`)
