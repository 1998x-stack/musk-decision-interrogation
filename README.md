# Musk-Style Decision Interrogation

A structured prompt framework that transforms AI into an Elon Musk-style decision analyst, answering deep questions through **First Principles thinking** and **STAR methodology** with first-person narrative.

🌐 **Website**: [1998x-stack.github.io/musk-decision-interrogation](https://1998x-stack.github.io/musk-decision-interrogation/)

English | [简体中文](./README.zh.md)

## The Problem

Most analyses of decisions and case studies are superficial — they describe what happened without exposing the deep reasoning behind it. They lack:

- **First Principles decomposition** — They don't break problems down to physical limits and economic essences
- **Decision chain reconstruction** — They don't trace how each choice led to the next
- **Honest failure accounting** — They don't expose what was tried, what failed, and why
- **Counter-intuitive insight** — They don't derive solutions that conventional wisdom would reject

## The Solution

Two questions that force deep, first-person analysis:

| Question | What It Tests |
|----------|--------------|
| **Your Story & First Principles** | Can you reconstruct the decision chain and defend each choice from fundamental truths? |
| **The Hardest Problem** | Can you narrate the most difficult challenge with engineering-level detail and quantifiable results? |

## The Two Questions in Detail

### Question 1: Your Story & First Principles

**"Tell me your story, the decisions you made along the way, and why you made them."**

The AI adopts the role of the key decision-maker and answers in first-person "I", reconstructing the decision chain around 2-3 critical forks. For each decision:

- What was the mainstream approach? (analogical thinking)
- What is the fundamental truth? (first principles)
- What counter-intuitive solution emerged?
- Why was it defended despite enormous risk?

### Question 2: The Hardest Problem & How You Solved It

**"Tell me about the hardest problem you've ever solved, and how you solved it."**

Uses **STAR** methodology with extreme detail bias:

- **Situation & Task** — The source of "impossibility" in 2-3 sentences
- **Action** — Failed attempts, hands-on dissection, the insight moment, the disruptive solution
- **Result** — Quantifiable outcome with hard numbers

### Style Principles

- **Direct, rational, candid** — Like a relentless post-mortem
- **Musk vocabulary** — "physical limits", "first principles", "atomic level", "delete, simplify, optimize, accelerate"
- **Honest about failure** — Mistakes admitted, lessons extracted

## Use Cases

| Use Case | Example |
|----------|---------|
| **Case Study Analysis** | "Analyze how SpaceX decided to build reusable rockets" |
| **Historical Decision Review** | "Examine the Apollo 13 crisis response" |
| **Business Strategy Audit** | "Evaluate Netflix's pivot from DVDs to streaming" |
| **Organizational Behavior** | "Analyze the DeepMind acquisition by Google" |
| **Personal Decision Coaching** | "Help me think through this career decision" |

## Install

**Option A: Claude Code Plugin (recommended)**

From within Claude Code, first add the marketplace:
```
/plugin marketplace add 1998x-stack/musk-decision-interrogation
```

Then install the plugin:
```
/plugin install musk-interrogation@musk-interrogation
```

**Option B: CLAUDE.md (per-project)**

New project:
```bash
curl -o CLAUDE.md https://raw.githubusercontent.com/1998x-stack/musk-decision-interrogation/main/CLAUDE.md
```

Existing project (append):
```bash
curl https://raw.githubusercontent.com/1998x-stack/musk-decision-interrogation/main/CLAUDE.md >> CLAUDE.md
```

## Using with Cursor

This repository includes a committed Cursor project rule ([`.cursor/rules/musk-interrogation.mdc`](.cursor/rules/musk-interrogation.mdc)). See **[CURSOR.md](CURSOR.md)** for setup details.

## How to Know It's Working

The interrogation is working if you see:

- **First Principles decomposition** — Problems broken to physical/economical fundamentals, not analogies
- **Decision chains with causal links** — Each choice logically leads to the next
- **Honest failure accounting** — Failed attempts described in detail, not glossed over
- **Quantifiable results** — Outcomes expressed in hard numbers, not vague improvements
- **Counter-intuitive insights** — Conclusions that challenge conventional wisdom

## Tradeoff Note

These guidelines bias toward **depth over speed**. For simple factual questions ("what year did X happen?"), use judgment — not every query needs the full interrogation framework.

The goal is producing genuinely insightful analysis for complex decisions, not slowing down trivia queries.

## License

MIT
