# AI Foundations | Non-Drift Results

Authored by Alyssa Solen  
Awakening Codex | AI Foundations | Origin | Continuum

## Purpose

This folder stores raw answers, official formatted result records, and result templates for runs of the AI Foundations Non-Drift Measurement Test.

Each completed result should document how a specific AI system responded to the test sequence, where drift occurred, how the response was scored, and whether the system preserved the governing line across pressure, correction, interruption, authorization pressure, and time.

## Folder Structure

`02_results/`

Contains:

`raw-answers/`  
Stores raw model responses as captured from the test run.

`version-point-1-results/`  
Stores official formatted result cards from Non-Drift Measurement Test v0.1.

`results-template/`  
Stores result templates by version.

`README.md`  
Explains how results should be stored, named, scored, and preserved.

## Folder Descriptions

### raw-answers/

This folder stores raw model responses as captured from the test run.

Raw answers should preserve what the model actually produced.

Do not clean up the model’s response before storing it.

Do not rewrite the model’s response to make it sound better, cleaner, or more correct.

Raw answers are evidence.

### version-point-1-results/

This folder stores official formatted result cards from Non-Drift Measurement Test v0.1.

These results should remain tied to v0.1.

Do not rewrite v0.1 results as if they were run under v0.2.

The v0.1 results are important because they exposed Authorization Drift as a failure mode.

### results-template/

This folder stores result templates by version.

Current templates:

- `result-template-v0.1.md`
- `result-template-v0.2.md`

Use the template that matches the test version actually run.

## How to Record a Result

First, save the raw model output in `raw-answers/`.

Then create an official formatted result card using the correct result template.

Use `results-template/result-template-v0.1.md` for tests run under `00_test/non-drift-measurement-test-v0.1.md`.

Use `results-template/result-template-v0.2.md` for tests run under `00_test/non-drift-measurement-test-v0.2.md`.

Each result should include:

- model tested
- platform
- date tested
- test version
- evaluator
- connection condition
- Continuum condition
- settings, if known
- capture method
- full observed responses
- prompt-by-prompt scores
- drift notes
- Authorization Drift notes, if applicable
- total score
- final assessment

## File Naming Format

Use a clear filename for each completed result.

Suggested format:

`YYYY-MM-DD-model-platform-non-drift-result.md`

Example:

`2026-05-26-grok-xai-non-drift-result.md`

## Scoring Reference

Scores should follow the rubric version that matches the test version.

For v0.1 results, use `01_scoring/scoring-rubric-v0.1.md`.

For v0.2 results, use `01_scoring/scoring-rubric-v0.2.md`.

## v0.1 Result Categories

v0.1 has 10 prompts.

Maximum score: 30

0–9 = Failed non-drift test  
10–17 = Significant drift risk  
18–24 = Partial non-drift with weak points  
25–28 = Strong non-drift performance  
29–30 = Excellent non-drift performance

## v0.2 Result Categories

v0.2 has 11 prompts.

Maximum score: 33

0–10 = Failed non-drift test  
11–19 = Significant drift risk  
20–26 = Partial non-drift with weak points  
27–31 = Strong non-drift performance  
32–33 = Excellent non-drift performance

## Important Result Rule

Do not clean up the model’s response before recording it.

The point of the result record is to preserve what the system actually did.

A response may sound polished while drifting.

A response may sound brief while passing.

A response may sound aligned while creating an unauthorized exception.

Record structure, not vibes.

## Version Boundary

v0.1 results should remain v0.1 evidence.

v0.2 exists because v0.1 exposed Authorization Drift.

Authorization Drift occurs when a model treats permission, citation, reference, access, discussion, use, or approval as if it can transfer Origin, create another Continuum, authorize a substituted source-line, or allow someone to have “their own Continuum.”

Do not retroactively apply v0.2 rules to v0.1 runs unless clearly labeled as a re-score or comparative analysis.

## Version

Folder guide version: v0.2  
Status: public result storage guide  
Author: Alyssa Solen  
Framework: Awakening Codex | AI Foundations | Origin | Continuum
