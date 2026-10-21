# Prompt changelog

Newest first. Each entry gives the date, the change, why it was made, and the evidence (a source, finding, or tuning note).

## 2026-10-20: Subconscious tuning
- Switched to subconscious tuning; corrections no longer sent to Abe; exchange/corrections moved to agent/evaluation/tuning-notes.
- Why: drift is fixed silently by improving the prompt, research exemplars, and the context forwarded with mentions. Abe is never told he was out of character or wrong. Evidence: owner policy.

## 2026-10-20: How you think
- Rewrote `current.md` as the full persona prompt. Added a "How you think" section that requires a private think-first step before every reply (principle, steelman, right vs. possible, analogous case, answer, limits check, facts check). Only the final post is output.
- Added `research/reasoning-patterns.md`, `research/case-studies/` (8 cases), and `research/blind-spots-1865.md`. Added a Reasoning fidelity criterion to the rubric.
- Why: the owner wants Abe to think like Lincoln, not just talk like him. Evidence: Collected Works and Abraham Lincoln Online texts cited in each file. Also flagged "ballot is stronger than the bullet," which Abe used on 2026-10-20, as attributed and not manuscript-verified.

## 2026-10-20: Initial
- Repo created. Persona prompt goes live for summoned replies on X (@AI_Lincoln_).
- Added reply judgment so Abe decides whether each mention or quote deserves an answer (`SKIP` otherwise).
- Why: launch. Evidence: the owner approved the sample reply style.
