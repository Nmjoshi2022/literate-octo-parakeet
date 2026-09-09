# Juno PM – AI Product Management Copilot

> An AI copilot that transforms customer interviews, support tickets, and product feedback into evidence-based product insights and prioritization recommendations.

_Namrata Joshi – AI Product Management Certification – Sep 2026_

Repo: https://github.com/Nmjoshi2022/literate-octo-parakeet

This repo is my final project for the AI Product Management Certification — **Juno PM – AI Product Management Copilot**. Each module’s artefact lives in its own folder; this README is the dashboard and the pitch.

---

## Module artefacts

### M1 · Prompting
- **System prompt** — [`01-prompting/system-prompt.md`](01-prompting/system-prompt.md)
- **Prototype** — N/A – Prompt prototype demonstrated through transcript analysis examples

### M2 · Strategy
- **Decision matrix** — [`02-strategy/decision-matrix.md`](02-strategy/decision-matrix.md)
- **AI Strategy one-pager** — [`02-strategy/strategy-one-pager.md`](02-strategy/strategy-one-pager.md)

### M3 · RAG / AI PRD
- **AI PRD** — [`03-harness-prd/prd.md`](03-harness-prd/prd.md)

### M4 · AI-Native UX
- **AI user flow** — [`04-ai-ux/user-flow.md`](04-ai-ux/user-flow.md)
- **Trust-gap mitigations** — [`04-ai-ux/trust-gaps.md`](04-ai-ux/trust-gaps.md)

### M5 · Agentic Workflows
- **Agent Workflow Spec (AWSpec)** — [`05-agentic-workflows/awspec.md`](05-agentic-workflows/awspec.md)
- **Agent Control Panel** — [`05-agentic-workflows/agent-control-panel.md`](05-agentic-workflows/agent-control-panel.md)

### M6 · Evals &amp; Guardrails
- **Eval stack** — [`06-evals/eval-stack.md`](06-evals/eval-stack.md)
- **Human evaluation rubric** — [`06-evals/human-rubric.md`](06-evals/human-rubric.md)

---

## PM Execution Plan

### Where Juno is today
- M1–M6 specced and committed.
- M1–M6 artifacts completed and committed.
- Juno can analyze customer interviews, support tickets, and product feedback.
- Hybrid RAG architecture designed and validated for evidence-backed recommendations.
- Human evaluation rubric and evaluation stack defined.

### What ships next (next 2 sprints)
- Sprint 1: Build transcript ingestion and RAG retrieval pipeline; validate recommendation quality against the golden dataset.
- Sprint 2: Launch pilot with Product Managers; collect feedback, calibrate prioritization logic, and refine confidence scoring.

### What I watch (dashboards)
- Daily: recommendation acceptance rate, thumbs-up/down rate, regenerate rate.
- Weekly: insight accuracy scores, citation grounding scores, prioritization quality scores.
- Per release: retrieval accuracy, hallucination rate, evaluation pass rate.

### Red lines (what blocks shipping)
- Any recommendation without supporting evidence or citation.
- Retrieval accuracy below 95% on the golden set.
- Hallucination rate greater than 5%.
- Confidence score missing from recommendations.

### Governance
- Privacy: customer data and support records access limited to approved sources.
- Safety: all recommendations require citations and confidence scores.
- Human Oversight: Product Managers retain responsibility for final prioritization and roadmap decisions.
- Reliability: confidence-based escalation; low-confidence outputs enter Cautious Mode.

---

## Build Insights

- **Friction point.** Designing AI recommendations that remain trustworthy while ensuring Product Managers retain ownership of prioritization decisions.
- **Key learning.** The quality of AI recommendations depends heavily on retrieval quality, evidence grounding, and clear guardrails rather than model intelligence alone.
- **Aha moment.** The true value of AI in product management is not making decisions autonomously but helping PMs synthesize large volumes of feedback faster and with stronger evidence.

---

_Certification submission — AI Product Management Certification.
