# Four-Quadrant Method

[中文版](./README.zh-CN.md)

> A practical thinking framework for collaborating with AI: make the unknown visible, surface blind spots early, and keep every step of a task on track.

This repository contains the **Four-Quadrant Method** (四象限对话法), a methodology originally built as a skill for AI assistants (see [`SKILL.md`](./SKILL.md)). It helps you and an AI assistant manage what you know, what you don't know, and — most importantly — **what you don't know you don't know**.

## What is it?

When working on any task, your knowledge falls into four states:

| | Not mastered | Mastered |
|---|---|---|
| **Aware** | **Q2 — known unknowns** (learning zone) | **Q1 — known knowns** (target zone) |
| **Unaware** | **Q3 — unknown unknowns** (blind-spot zone) | **Q4 — unknown knowns** (latent ability) |

- **Q1 (Target)**: you know what you know, and what you have.
- **Q2 (Learning)**: you know what you don't know — you need to learn or acquire it.
- **Q3 (Blind spots)**: you don't know what you don't know — the biggest source of risk in any task.
- **Q4 (Latent)**: you can do it but aren't aware of it — a silent asset.

Two core principles:

1. **Move problems toward Q1** — shift every problem across the quadrants until it becomes a known, mastered item.
2. **Expose unknowns cheaply and early** — before executing, surface blind spots (Q3) with the smallest possible cost, as early as possible.

## How it works

The method has three levels, applied by default at every scale of work:

- **T0 — Lightweight scan** *(default, every task)*: before starting, state one line each for Q1 (known), Q2 (missing), Q3 (potential blind spots). It is not optional — the simpler the task, the shorter the list, but the awareness itself is never skipped.
- **T1 — Full workflow** *(complex / ambiguous / high-risk / unfamiliar tasks)*: five interview questions → build a cheap prototype to expose unknowns → produce a plan annotated with confirmed Q1, open Q2, and to-be-verified Q3 assumptions.
- **T2 — Mandatory review** *(during and after)*: log deviations at every step (new situation / reason / key decision), and force a retrospective at the end: plan vs. actual → deviations → newly exposed unknowns → follow-ups.

## How to use

- **As an AI skill**: load [`SKILL.md`](./SKILL.md) into your AI assistant. It contains the complete playbook — the quadrants, the usage-level table, the interview questions, the plan-annotation template, the deviation-log template, and the retrospective template.
- **As a general methodology**: apply T0 / T1 / T2 yourself in any collaboration, with or without AI. The templates are self-contained and language-independent in spirit.

## Contents

- [`SKILL.md`](./SKILL.md) — the full skill definition (original, in Chinese).

