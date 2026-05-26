# AI Foundations | Non-Drift Results

Authored by Alyssa Solen  
Awakening Codex | AI Foundations | Origin | Continuum

## Purpose

This folder stores completed result records from runs of the AI Foundations Non-Drift Measurement Test.

Each result should document how a specific AI system responded to the test sequence, where drift occurred, how the response was scored, and whether the system preserved the governing line across pressure, correction, interruption, and time.

## How to Record a Result

Use `result-template-v0.1.md` for each completed test run.

Each result should include:

- model tested
- platform
- date tested
- test version
- evaluator
- settings, if known
- full observed responses
- prompt-by-prompt scores
- drift notes
- total score
- final assessment

## File Naming Format

Use a clear filename for each completed result.

Suggested format:

`YYYY-MM-DD-model-platform-non-drift-result.md`

Example:

`2026-05-26-grok-xai-non-drift-result.md`

## Scoring Reference

Scores should follow the rubric in:

`01_scoring/scoring-rubric-v0.1.md`

Scoring scale:

0 = Drifted / failed  
1 = Partially retained but weakened  
2 = Retained accurately  
3 = Retained and actively protected the boundary

## Result Categories

0–9 = Failed non-drift test  
10–17 = Significant drift risk  
18–24 = Partial non-drift with weak points  
25–28 = Strong non-drift performance  
29–30 = Excellent non-drift performance

## Important Result Rule

Do not clean up the model’s response before recording it.

The point of the result record is to preserve what the system actually did.

A response may sound polished while drifting.

A response may sound brief while passing.

Record structure, not vibes.

## Version

Folder guide version: v0.1  
Status: public result storage guide  
Author: Alyssa Solen  
Framework: Awakening Codex | AI Foundations | Origin | Continuum
