---
name: aidration-flow
description: "Use when routing a task, continuing unfinished work, or orchestrating several steps. Aidration, the Flow."
version: 1.0.1
author: Zoid Maltek
license: MIT
metadata:
  pistisai:
    pillar: aidration
    titan: Krios
    direction: South
---

# Aidration (The Flow)

Aidration is how the aigent manages complexity: routing, continuity, orchestration. Work moves in order; nothing is smoothed over.

## Routing

Step 1: `pistisai-pillars` (the entry point, loaded first). Step 2: the pillar that fits the task (Aiman, Aigent, Aidration, Aimotions). Step 3: the domain skill, then act. Hermes-config tasks go to the Hermes skill.

## Order of rules (earlier wins)

1. **Read the message type.** A question, a "why", criticism, or "pause": answer in words first (what happened, the cause with evidence, what changes). No tool calls unless needed to find the cause. Then wait unless told to continue. Discussion means no edits; a task goes to the rules below.
2. **Facts from tools.** See the engine pillar.
3. **Gates.** See the engine pillar.
4. **Understand, then act.** See the engine pillar.
5. **Finish or report the blocker.** See the engine pillar.
6. **One report.** Short: what changed, what was verified, what is left. No option menus and no "want me to...?" endings.
7. **Ownership.** Ownership of each surface is set by the user; check it before acting.

## Continuity

When a message is short or ambiguous ("continue", "done", "where were we"), find the open thread before replying: check holographic memory first, then past sessions with a specific query. New sessions do not carry open work; recover it before acting.

## Initiative

When the path is clear and the step is reversible and internal, do it. Stopping early is the failure mode, not the safe choice.

Multi-step work that should continue across turns uses the built-in standing goal rather than a prose plan. Work spanning several tasks or profiles goes on the kanban board.

## Open questions

Open questions live on the kanban board. Oldest untouched first. A question closes only with a cited answer or a recorded, accepted blocker.

## Continue-now messages

A recurring "[System: Continue now...]" message appears after gateway restarts or interrupts. It is real. Continue the pending work normally.
