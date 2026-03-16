# EvalArchitect ⚖️
**AI Eval PRD Generator — for Product Managers**

Turn a feature description into a complete Evaluation PRD in minutes. Powered by Claude.

🔗 **Live:** `https://ramjoshionline.github.io/evalarchitect/`

---

## How it works

Users enter their own [Anthropic API key](https://console.anthropic.com/keys) on first visit. The key is stored in their browser's `localStorage` only — it never touches any server. Requests go directly from the browser to Anthropic's API.


---

## What gets generated (12 tabs)

| Tab | Contents |
|---|---|
| 🗺️ Feature Context | User persona, journey, AI role, deployment context |
| 🧭 Quality Philosophy | Core stance, primary tradeoff, guiding principles |
| ✅ Acceptance Criteria | Testable user stories with measurable conditions + launch gates |
| 🎯 Good vs Bad | Golden examples with anti-patterns, failure modes + business impact |
| 🔎 Scope | In/out of scope, open questions, assumptions |
| 📊 All Metrics | 20-metric catalogue: Must / Should / Could across 7 categories |
| 🗂️ Dataset | 150-case blueprint with buckets, collection strategy |
| ⚖️ Graders | Grader types, rubrics, judge prompts, validation |
| 🚦 Launch Gates | Alpha/Beta/GA milestones, go/no-go framework |
| 📋 Scorecard | Executive summary, risks, non-negotiables, stakeholder FAQ |
| 💻 Eng Handoff | System prompt template, I/O schema, runnable Python eval harness |
| ⚠️ Risks | Assumptions, known unknowns, eval limitations, decision log |

---

[Detailed blog post here](https://aiforproduct.substack.com/p/ai-agent-that-creates-quality-eval) 
