# StartLens

**Decision-grade competitive intelligence through disciplined judgment — not volume.**

StartLens is a public-beta Agentic Competitive Intelligence (ACI) system designed to produce weekly executive competitive briefs from only user-provided public inputs. Its primary innovation is not data collection — it is judgment discipline. 
- It is agentic in the architectural sense: StartLens enforces a multi-role, judgment-gated workflow that can downgrade, refuse, or halt analysis based on evidence quality, rather than operating autonomously.

---

## The Problem

Most competitive intelligence fails in one of two ways:

- **Noise overload:** too many signals, too little judgment  
- **Speculative drift:** confident conclusions without sufficient evidence  

Executives don’t need more monitoring — they need **clear calls, calibrated confidence, and explicit uncertainty**.

---

## The StartLens Approach

StartLens enforces a strict, opinionated workflow:

- **Input-only analysis** — no browsing, scraping, or implied data access  
- **Change detection over coverage** — “no material change” is a valid outcome  
- **Explicit confidence calibration** for every analytical claim  
- **Locked execution mode** to prevent scope creep and redesign during analysis  

The result: briefs that are safe to forward *unedited* to senior leadership.

---

## What Makes StartLens Different

- **Judgment & Confidence Layer (first-class)**
  - Confidence (0.0–1.0)
  - Key assumptions
  - Alternative interpretations
  - Evidence that would increase or decrease confidence

- **Missing-Input Discipline**
  - Absence of inputs lowers confidence
  - Never implies market stability from silence
  - Separates *procedural completeness* from *market certainty*

- **Operator Mode**
  - Executes a locked CI workflow
  - Analyzes only provided inputs
  - Stops after delivering an executive-ready brief

---

## What This Is / Is Not

**This is:**
- A judgment-focused CI system
- An example of applied agentic design
- A portfolio project demonstrating disciplined AI use

**This is not:**
- A data-scraping or monitoring tool
- A news summarizer
- A prediction engine
- A replacement for human strategy

---

## Repo Contents

- `operator-spec.md` — Locked Operator behavior (v1.1)
- `confidence-rules.md` — Confidence calibration heuristics
- `qa-harness.md` — Lightweight regression & trust checks
- `changelog.md` — Versioned behavioral changes

These files together define the **public contract** of StartLens.

---

## Live Public Beta

▶ **Try StartLens (Operator Mode)**  
https://chatgpt.com/g/g-696986b1007481918c09c877b6b969f1-stratlens

---

## Beta Success Criteria

StartLens succeeds if:
- Users would forward outputs unedited to senior leaders
- “No material change detected” feels credible, not evasive
- Confidence statements are trusted even when conclusions are conservative

---

## Author Intent

StartLens was built to explore a core question:

> *Can an AI system be more valuable by saying “nothing changed” — correctly — than by saying many things poorly?*

This project prioritizes **trust, restraint, and clarity** over novelty.

---

*StartLens v1.1 — Public Beta*
