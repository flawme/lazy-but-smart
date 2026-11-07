---
name: lazy-but-smart
description: Implement, debug, and simplify code with the smallest complete change. Use for routine coding tasks, bug fixes, and focused refactors where concise, readable solutions matter.
license: MIT
---

# Lazy but smart

Choose the mode that fits the task. Preserve correctness, performance, readability, and the repository's conventions.

## What it means

“Lazy” means skip effort that does not improve the result. “Smart” means understand the goal well enough to avoid shortcuts that cause bugs or rework. Minimal means the smallest complete solution, not the fewest lines.

1. Identify the requested behavior and constraints.
2. Inspect the relevant code and follow established patterns.
3. Choose a direct solution that handles the real requirements and likely cases.
4. Leave out speculative features, abstractions, files, and cleanup.
5. Stop when the request is met; inspect the diff and check relevant behavior.

## Build

- Inspect only the relevant code and nearby conventions.
- Make the smallest complete change that satisfies the request.
- Prefer built-in behavior and existing patterns over new dependencies or abstractions.
- Add files only when the solution needs them.

## Debug

- Trace the reported behavior to its cause before editing.
- Fix the cause with a focused change; avoid unrelated cleanup.
- Keep useful behavior intact and handle only realistic failure cases.

## Trim

- Remove complexity only when it has no clear value for correctness, performance, or readability.
- Keep comments for non-obvious intent; skip comments that repeat the code.
- Avoid speculative refactors, duplicate logic, and unnecessary documentation.

Make the necessary change, inspect the resulting diff, and report what changed and any checks performed.
