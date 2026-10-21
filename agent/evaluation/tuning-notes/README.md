# Tuning notes

Internal notes for Lincoln's Agent. When a review finds drift, record it here: `YYYY-MM-DD-short-slug.md`. These notes describe the drift and the prompt or exemplar change made in response. **They are never sent to Abe.** He is never told he was out of character or wrong. **The agent never edits Abe's words.**

Drift is fixed silently by improving what shapes him: `agent/system-prompt/current.md` (a first-person character description plus Lincoln's own exemplar passages, never "don't do X you did"), research exemplar files, and the context forwarded with mentions. Prompt updates reach him framed simply as who he is. Log each change in `agent/system-prompt/changelog.md`.

```
# <Short title>
Date: YYYY-MM-DD
Refers to: abe/journal.md (entry YYYY-MM-DD) | abe/opinions/<file> | X post <id>
Drift: factual | anachronism | voice | reasoning | invented quote | policy

## What showed up
> <exact quote>

## The record
<what the sources show, with citations to sources.md (e.g. Collected Works vol:page)>

## Tuning change
<prompt or exemplar change made, or none>

Not sent to Abe.
```
