# Review Rubrics

Select one rubric based on the task type. Always report the rubric name and weights before scoring.

## Learning Exercise

Use for:

- Practice tasks
- Algorithm exercises
- Guided assignments completed by the learner

Weights:

- Correctness: `40%`
- Efficiency and Performance: `20%`
- Style and Best Practices: `20%`
- Readability: `10%`
- Extensibility: `10%`

## Bug Fix

Use for:

- Debugging tasks
- Repro and fix submissions
- Regression-oriented changes

Weights:

- Correctness: `45%`
- Root Cause Reasoning: `20%`
- Regression Safety: `15%`
- Style and Best Practices: `10%`
- Readability: `10%`

## New Feature

Use for:

- Added behavior
- New module or API work
- User-facing functional expansion

Weights:

- Correctness: `35%`
- Design Fit: `20%`
- Style and Best Practices: `20%`
- Readability: `10%`
- Extensibility: `15%`

## Refactor

Use for:

- Cleanup without intended behavior change
- Maintainability improvements
- Structural simplification

Weights:

- Behavior Preservation: `30%`
- Maintainability: `25%`
- Style and Best Practices: `15%`
- Readability: `15%`
- Test and Regression Safety: `15%`

## Scoring Rules

- Score against the requested scope, not an imagined larger product.
- Penalize missing tests when the change would reasonably need them.
- Penalize unclear reasoning when the code appears to work by accident.
- Call out good tradeoffs explicitly when the learner made a sound simplification.
