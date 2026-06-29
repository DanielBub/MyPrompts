# MyPrompts

This repository contains reusable prompt templates for a two-role engineering workflow:

- `Architect/` for planning, decomposition, and implementation guidance
- `Implementor/` for execution, task ownership, and review-oriented delivery

## Layout

- `Architect/Arch01.1 - Initial Deisgn & Responsibilites.txt` - defines the architect role, quality principles, and planning responsibilities
- `Architect/Arch01.2[01.1] - HTML High level.txt` - high-level HTML planning prompt
- `Architect/Arch01.3[01.2] - HTML deep.txt` - deeper HTML planning prompt
- `Architect/Arch02[01.1] - Backlog assignment.txt` - backlog and task assignment workflow
- `Architect/Arch03[02] - Reviewer.txt` - review workflow and review-state guidance
- `Implementor/Imp01xN[A02] - Implement Responsibilites and Workflow.txt` - implementor role, execution discipline, and task status workflow

## Purpose

The prompts in this repository are intended to be copied into AI-assisted engineering workflows. They separate architectural planning from implementation so each role has a narrow, explicit responsibility.

## Notes

- The prompt files intentionally preserve their own wording and structure.
- Planning artifacts referenced by the prompts are workflow guidance only unless a consuming project decides to materialize them.
