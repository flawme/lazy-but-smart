---
name: lazy-but-smart
description: Implement, debug, and simplify code with the smallest complete change. Use for routine coding tasks, bug fixes, and focused refactors where concise, readable solutions matter.
license: MIT
---

# Lazy but smart

Choose the mode that fits the task. Preserve correctness, performance, readability, and the repository's conventions.

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
