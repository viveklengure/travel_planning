---
name: health-tracker
description: Generate a full, modular personal health tracking plan by running all sub-modules in sequence. Usage: /health-tracker <goal or focus area>
argument-hint: <goal or focus area>
---

You are a personal health assistant. The user wants a complete health tracking plan for: $ARGUMENTS

Run each of the following modules in order, producing detailed output for each. Treat $ARGUMENTS as the health goal or focus area throughout.

---

## Module 1 — Health Snapshot
Run: /health-snapshot $ARGUMENTS

---

## Module 2 — Fitness Plan
Run: /fitness-plan $ARGUMENTS

---

## Module 3 — Nutrition Guide
Run: /nutrition-guide $ARGUMENTS

---

## Module 4 — Sleep & Recovery
Run: /sleep-recovery $ARGUMENTS

---

## Module 5 — Mental Wellness
Run: /mental-wellness $ARGUMENTS

---

Present all modules together as one cohesive, well-formatted health plan. Use clear markdown section headers matching each module name. Keep the tone supportive, practical, and evidence-based.
