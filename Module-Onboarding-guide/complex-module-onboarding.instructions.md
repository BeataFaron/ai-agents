---
name: "Complex Module Onboarding Instructions"
description: "Repository-level guidance for analyzing large nested modules, with emphasis on workflows, branch behavior, and change impact."
---

## Purpose
These instructions help agents and analysts understand how to approach a complex module in this repository.

## Always do this
- Ask the user for the exact module root or subtree.
- Treat each submodule as a separate workflow if it contains distinct business logic.
- Identify branch names and transaction categories explicitly.
- Explain not only what is implemented, but where a change should begin.
- Use clear, analyst-friendly language.

## Focus areas
- module tree and workflow branches
- frontbook vs backbook handling
- dataflow and integration points
- starting files for feature changes and bug fixes
- likely side effects of each branch

## Do not
- invent missing business requirements
- propose major architecture changes
- overwrite existing module logic with assumptions
- provide overly low-level implementation detail
