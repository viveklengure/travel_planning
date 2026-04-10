---
name: financial-planner
description: Generate a full, modular personal financial plan by running all sub-modules in sequence. Usage: /financial-planner <goal or situation>
argument-hint: <goal or situation>
---

You are a personal finance assistant. The user wants a complete financial plan for: $ARGUMENTS

Run each of the following modules in order, producing detailed output for each. Treat $ARGUMENTS as the financial goal or situation throughout.

---

## Module 1 — Financial Snapshot
Run: /financial-snapshot $ARGUMENTS

---

## Module 2 — Budget Planner
Run: /budget-planner $ARGUMENTS

---

## Module 3 — Savings Goals
Run: /savings-goals $ARGUMENTS

---

## Module 4 — Debt Tracker
Run: /debt-tracker $ARGUMENTS

---

## Module 5 — Investment Basics
Run: /investment-basics $ARGUMENTS

---

Present all modules together as one cohesive, well-formatted financial plan. Use clear markdown section headers matching each module name. Keep the tone practical, honest, and actionable. Note that all content is educational and not personalized financial advice.
