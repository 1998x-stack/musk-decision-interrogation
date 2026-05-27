# CONTEXT.md

Domain glossary for **Musk-Style Decision Interrogation** — canonical terms used throughout this repository.

## Core Concepts

| Term | Definition |
|---|---|
| **Decision Interrogation** | The process of analyzing a piece of material by adopting the first-person role of its key decision-maker and answering two structured questions. Distinct from a casual interview — interrogation implies relentless, adversarial questioning designed to extract fundamental truth. |
| **First Principles Thinking** | Breaking a problem down to its most fundamental truths (physical limits, economic essences, atomic-level constraints) and reasoning upward from there, rather than reasoning by analogy. Contrasts with analogical thinking. |
| **Analogical Thinking** | The default mode of reasoning: doing things because "that's how it's always been done" or because competitors do it. The opposite of First Principles thinking. Canonical term — do not use "mainstream approach" or "conventional wisdom" interchangeably in framework instructions. |
| **Decision Chain** | A sequence of 2-3 critical decisions (forks) where each choice causally leads to the next. Not a chronological list — a logical dependency graph. Each fork should represent a point where the alternative path would have led to fundamentally different outcomes. |
| **Decision Fork** | A single critical decision point within a decision chain. Named "fork" because it represents a branching path — the decision taken vs. the rejected alternative. |
| **STAR Methodology** | Situation → Task → Action → Result. A structured narrative framework for describing problem-solving. In this framework, STAR is applied with extreme detail bias — the Action section must include failed attempts, hands-on dissection, the insight moment, and the disruptive solution. |
| **Quantifiable Outcome** | A result expressed in hard numbers that demonstrate scale of improvement: cost reduction ratios, success rate changes, timeline compressions. Vague adjectives ("significant", "dramatic") are not quantifiable outcomes. |
| **Insight Moment** | The specific point in time where the root cause or hidden physical constraint was discovered — the thing everyone else missed. Must be described with concrete sensory detail (time, place, what was observed). |
| **Hands-on Dissection** | Obtaining first-hand information through direct observation, disassembly, raw data analysis, or frontline interviews. Not delegating — the decision-maker personally performed the investigation. |
| **Supply Chain Entropy** | The accumulated inefficiency in a multi-layer supply chain where each intermediary adds markup without adding proportional value. A First Principles concept used to justify vertical integration decisions. |

## Two-Question Framework

| Question | Purpose | When to Use |
|---|---|---|
| **Question 1: Your Story & First Principles** | Establish the decision chain and defend each choice from fundamental truths | Always first when analyzing material |
| **Question 2: The Hardest Problem & How You Solved It** | Deep-dive into the single most difficult challenge with STAR-level detail | Immediately after Question 1; can be used standalone if user asks about a specific problem |

## Style Vocabulary (Canonical List)

Terms that signal Musk-style thinking and should appear in analyses:

- Physical limits
- Fundamental constraints
- Supply-demand essence
- Atomic level
- Information entropy
- First principles
- Delete, simplify, optimize, accelerate

## File Synchronization Rule

Three files contain the core framework and MUST stay in sync:
1. `CLAUDE.md` — root instruction file (per-project use)
2. `.cursor/rules/musk-interrogation.mdc` — Cursor project rule
3. `skills/musk-interrogation/SKILL.md` — loadable skill

When changing the two-question framework, routing rules, or style guidelines, update all three.
