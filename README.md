# StewArda

**StewArda** is an AI workflow steward that helps people turn messy, ongoing information into clear signals, trusted decisions, and approved actions — without losing human control.

It’s designed for real life: emails, notifications, policies, approvals, recurring tasks, and shared work — not just one-off chats.

---

## 🚀 Judge TL;DR (1 minute)

- **Problem**: Important information gets buried. Automation is powerful but risky. People need AI that assists without taking over.
- **Solution**: StewArda introduces a structured loop — *observe → decide → approve → act → reflect*.
- **Key idea**: AI proposes, humans approve, systems execute.
- **Why it’s different**: Clear separation between thinking, planning, approval, and execution.
- **Status**: Functional prototype with mock execution and real orchestration logic.

---

## 🧠 What StewArda Does

StewArda helps users:

- Observe information streams (email, messages, documents)
- Extract **signals** that matter
- Propose **workflows and actions**
- Require **explicit approval** before execution
- Continuously **adapt and tune** behavior over time

It works across ongoing conversations — not isolated prompts.

---

## 🧭 Core Flow (Conceptual)
User Intent
↓
Observation (what should we watch?)
↓
Signals (what changed / what matters?)
↓
Action Proposal (what should we do?)
↓
Approval (human-in-the-loop)
↓
Execution (manual, assisted, or automated)
↓
Learning & Tuning (get better over time)

Each step is intentional, explicit, and reversible.

---

## ✨ Example Use Cases

- **School communications**
  - Track deadlines, fees, meetings
  - Surface urgent notices
  - Generate weekly summaries
- **Work inbox triage**
  - Highlight action-required messages
  - Propose follow-ups
  - Require approval before sending replies
- **Recurring monitoring**
  - Watch for changes
  - Notify when thresholds are crossed
  - Pause automatically if conditions change
- **Personal workflows**
  - Summaries, reminders, drafts, alerts
  - Always with human approval

---

## 🛠 How We Built It

- Agent-based architecture with strict output contracts  
- Mode-driven planning (observe, propose, signal, tune)  
- Approval-first execution model  
- LLM-agnostic design (models are swappable)  
- Mock execution layer for safe iteration  

The system is intentionally modular so that planning, approval, and execution remain decoupled.

---

## 🧩 Design Principles (Public)

These guide everything in StewArda:

1. AI proposes, humans decide  
2. No silent automation  
3. State is explicit  
4. Every action is explainable  
5. Learning is incremental, not magical  
6. Safety before scale  

This repo shows *what* StewArda does — not every internal mechanism.

---

## 🧱 Challenges We Ran Into

- Avoiding automation sprawl  
- Preventing accidental execution  
- Keeping long-running context coherent  
- Designing approvals that don’t feel heavy  
- Making AI behavior predictable across turns  

---

## 🏆 What We’re Proud Of

- A clear human-in-the-loop model  
- Deterministic orchestration outside the LLM  
- Clean separation between intent, proposal, and execution  
- A system that feels trustworthy, not magical  

---

## 📚 What We Learned

- Most automation problems are trust problems  
- Users want control *and* convenience  
- Explicit states reduce confusion  
- AI systems need memory — but also boundaries  
- Tuning over time matters more than “perfect prompts”  

---

## 🔮 What’s Next for StewArda

- Shared workflows and collaborative spaces  
- Enterprise approval chains  
- Multi-channel support (email, chat, voice)  
- Mobile-first experience  
- Smarter tuning proposals based on feedback  
- Deeper integrations with execution providers  

---

## 🧪 Repo Scope (Important)

This is a **public hackathon repository**.

It intentionally **does not include**:
- Internal schemas  
- Prompt templates  
- Approval engines  
- Execution adapters  

Those live in a separate, private development repo.

---

## 🧰 Built With

TypeScript, Vercel AI SDK, Cloudflare Workers, Cloudflare AI Gateway, OpenAI, Google Gemini, Zod, React, Node.js
