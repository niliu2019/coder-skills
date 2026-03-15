# Example Prompts

These examples are repository-agnostic prompt patterns for `coder-skills`.

## Guided Mode

```text
Use $coder-skills to turn this C++ linked-list task into a guided exercise.
Give me the problem statement, constraints, and focused TODO/HINT markers.
Do not give the full implementation.
```

## Hint-only Mode

```text
Use $coder-skills and give me only 2 hints for this Rust borrow-checker error.
Do not scaffold the full solution.
```

## Review Mode

```text
Use $coder-skills to review my C function implementation.
Score it with the bug-fix rubric, point out regressions, and give me follow-up tasks.
```

## Planning Mode

```text
Use $coder-skills to break this Python refactor into 5 milestones before making edits.
Keep the plan repository-aware and mention verification steps.
```

## Direct Implementation Mode

```text
Use $coder-skills to directly implement this TypeScript parser fix for me.
Edit the real file, keep the patch minimal, and report what you verified.
```
