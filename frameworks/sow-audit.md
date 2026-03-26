# SOW Audit — Framework

> *Understanding your work before selecting your tools.*

## What Is a SOW Audit?

A **Statement of Work (SOW) Audit** is a structured self-assessment that maps every task a team performs, evaluates how much of each task AI can handle, and calculates the team's overall AI augmentation potential. It is the essential first step before any AI tooling or workflow redesign decision.

Most organizations fail at AI adoption because they pick tools before understanding their own work. The SOW Audit fixes that.

---

## The 3 Questions

| # | Question | Purpose | Output |
|:--|:---|:---|:---|
| 1 | **What are your tasks?** | List every recurring task (daily/weekly/sprint-level) | Complete task inventory |
| 2 | **Can AI participate in this task?** | Classify: AI handles fully / AI assists / Human only | AI applicability rate |
| 3 | **How much can AI handle per task?** | Estimate % of task effort AI can take over | AI participation rate + effort reduction estimate |

---

## How to Run It

**Step 1 — List all tasks**
Every team member independently lists their recurring tasks for a typical week/sprint. No filtering, no editing. Just a raw list.

**Step 2 — Classify each task**

| Classification | Definition |
|:---|:---|
| ✅ AI can fully handle | AI produces output with minor human review. (e.g., draft documentation, test case generation) |
| 🔶 AI assists | AI handles a significant portion, human does the rest. (e.g., stakeholder meeting summaries) |
| ❌ Human only | Requires judgment, empathy, or context AI cannot replace. (e.g., client negotiation) |

**Step 3 — Estimate AI participation**
For each ✅ or 🔶 task, estimate: *"If we used AI effectively on this task, what % of the effort would AI handle?"*

**Step 4 — Calculate the baseline**
Add hours, compute the AI Augmentation Rate, and identify the Top 5 highest-impact quick wins.

---

## Template

```markdown
| Task | Hours/Week | AI Applicable? | % AI Handles | Notes |
|:-----|:----------:|:--------------:|:------------:|:------|
| [Task Name] | Xh | ✅ / 🔶 / ❌ | X% | |
| ...          |    |                |     | |
| **TOTAL** | **Xh** | **X/Y tasks (X%)** | **Avg X%** | |
```

---

## Example Output — BA Team (5 people)

| Task | Hours/Week | AI Applicable? | % AI Handles |
|:---|:---:|:---:|:---:|
| Writing requirement docs | 8h | ✅ | 70% |
| Creating test scenarios | 4h | ✅ | 80% |
| Stakeholder meeting summaries | 6h | 🔶 | 30% |
| Data analysis & reporting | 5h | ✅ | 60% |
| Client negotiation | 4h | ❌ | 0% |
| **Total** | **27h** | **4/5 tasks (80%)** | **Avg ~48%** |

**Interpretation**: This team has ~13h/week of AI-reclaimable effort. Priority: requirement writing and test scenario generation.

---

## How to Track Progress

Run the SOW Audit at the start of each implementation phase. Add the "Effort After" column to measure real reduction:

| Task | Effort Before | Effort After | Reduction |
|:---|:---:|:---:|:---:|
| Writing requirement docs | 8h | 2.5h | **–69%** |

---

## Where This Framework Is Used

- [AI Adoption Program](../programs/ai-adoption/) — Phase 1 Foundation, W3–W4
- [Agentic AI for Enterprise](../programs/agentic-ai-for-enterprise/) — Workflow prioritization
