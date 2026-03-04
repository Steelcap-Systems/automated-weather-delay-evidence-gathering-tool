# AI Spec Engineering for Weather Delay Evidence
## Agent-Generated, Language-Agnostic Tooling with Conformance Checks

Most teams are still asking, "How do we use AI to code faster?"

This repo is built around a better question:
**How do humans design systems so AI can deliver reliable software across any stack?**

---

## Why This Exists

Weather delays are common in construction.  
Defensible weather delay evidence is not.

A diary note alone is weak. BOM station data is authoritative, but local storms can miss nearby stations. Claims fail when evidence is incomplete.

The goal is a repeatable evidence bundle:
- diary event timestamp
- BOM station observations for the delay window
- radar/synoptic visual sequence showing storm movement over site coordinates

---

## Human Role in an AI-First Workflow

In an AI-first world, humans are not replaced by agents.  
Humans own the high-leverage work agents cannot infer:

1. Encode local truth
2. Write execution contracts
3. Build conformance checks
4. Decide confidence from results

This repository is a practical example of that model.

---

## What This Repo Actually Does

This is intentionally **not** a packaged app.

It is a spec-first project that lets you generate the tool in your own stack with your AI agent, then verify behavior against shared expectations.

### Specifically, this repo focuses on:

1. **Local truth (domain edge cases)**  
   Localized storm behavior, time-window sensitivity, and site-vs-station mismatch are treated as first-class requirements.

2. **Execution contract (agent-readable spec)**  
   The weather-delay evidence workflow is described as an implementation contract, not vague product prose.

3. **Verification mindset (conformance, not vibes)**  
   Generated implementations are meant to be tested and logged, so reliability claims can be backed by evidence.

4. **Human confidence calls (evidence over assumptions)**  
   Reliability is judged from repeat runs and logged outcomes, not a single successful generation.

---

## Who This Is For

- Engineers who want to showcase strong AI-era software practice
- Product teams that need language freedom (Python, Node, C#, etc.)
- Builders who prefer "generate in my stack" over adopting a single vendor package

If you read this and think, "this person understands how to use AI well," great.  
If you read this and think, "I should clone this and try it," even better.

---

## Use It Yourself

1. Clone the repo.
2. Feed the spec to your AI coding agent.
3. Generate an implementation in your language of choice.
4. Run verification scenarios.
5. Log pass/fail outcomes across repeated runs.

That is the point of this project:  
**you should be able to take this and produce working code yourself.**

---

## Status

Open source. Free to use.  
Built as an AI-first pattern for producing defensible weather delay evidence tooling.
