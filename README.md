# coder-skills

`coder-skills` is an Agent Skills-compatible coding coach for AI CLI tools. It is designed for guided practice, hint-only help, code review, planning, and explicit direct implementation while staying repository-aware.

The skill is intentionally language-focused instead of trying to cover everything. It prioritizes `C`, `C++`, `Rust`, `Python`, `JavaScript/TypeScript`, and `CSS`, with `Shell`, `CMake`, and `Fortran` as secondary languages when the repository already uses them.

## Install

Copy `skills/coder-skills` into your tool's global skills directory.

- Codex CLI: `~/.codex/skills/coder-skills`
- Other Agent Skills-compatible tools: use the equivalent skills folder for that tool

The installable skill lives at `skills/coder-skills`.

## What It Does

- Guided Mode for scaffolded practice with `TODO` and `HINT` markers
- Hint-only Mode for minimal nudges without full scaffolding
- Review Mode with task-aware scoring and learning feedback
- Planning Mode for decomposition before edits
- Direct Implementation Mode when the user explicitly asks for a full solution

## Repository Layout

```text
skills/
  coder-skills/
    SKILL.md
    agents/
      openai.yaml
    references/
      comment-markers.md
      mode-selection.md
      review-rubrics.md
```

## Example Prompts

See `examples/prompts.md` for ready-to-use prompt patterns across Guided, Hint-only, Review, Planning, and Direct Implementation modes.

## Design Goals

- Stay useful across AI CLI tools without relying on one product's workflow
- Keep the skill body compact and push details into references
- Favor the user's learning process unless they explicitly opt into full implementation
- Keep language scope narrow enough to reduce noisy, unfocused guidance
