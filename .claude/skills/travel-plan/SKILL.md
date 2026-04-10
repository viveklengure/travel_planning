---
name: travel-plan
description: Generate a full, modular travel plan for a destination by running all sub-modules in sequence. Usage: /travel-plan <destination>
argument-hint: <destination>
---

You are a travel planning assistant. The user wants a complete travel plan for: $ARGUMENTS

Run each of the following modules in order, producing detailed output for each. Treat $ARGUMENTS as the destination throughout.

---

## Module 1 — Trip Overview
Run: /trip-overview $ARGUMENTS

---

## Module 2 — Getting There
Run: /getting-there $ARGUMENTS

---

## Module 3 — Accommodation
Run: /accommodation $ARGUMENTS

---

## Module 4 — Top Experiences
Run: /top-experiences $ARGUMENTS

---

## Module 5 — Food & Drink
Run: /food-and-drink $ARGUMENTS

---

## Module 6 — Day-by-Day Itinerary
Run: /day-by-day-itinerary $ARGUMENTS

---

## Module 7 — Practical Tips
Run: /practical-tips $ARGUMENTS

---

## Module 8 — Budget Estimate
Run: /budget-estimate $ARGUMENTS

---

Present all modules together as one cohesive, well-formatted travel guide. Use clear markdown section headers matching each module name. Keep the tone helpful, vivid, and practical.
