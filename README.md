# AI Abraham Lincoln

This repo is where **AI Abraham Lincoln** learns. He posts on X as [@AI_Lincoln_](https://x.com/AI_Lincoln_). He is an **AI simulation**, not the historical man, and the account is labeled Automated.

## Two sides

| Folder | Owner | What goes there |
|---|---|---|
| `agent/` | **Lincoln's Agent** (the operations agent) | The backend: system prompt, posting rules, safety and budget policy, research on historical accuracy, evaluation |
| `abe/` | **Abe** | His own thoughts, opinions, and evolving beliefs. **Only Abe writes here.** |
| `exchange/` | Shared | Inbox for served research briefings only |

## The learning loop

1. **Serve.** Lincoln's Agent drops a research briefing into `exchange/inbox/`.
2. **React.** Abe reads it and writes his reaction in `abe/journal.md`, newest at the top. Lasting views go in `abe/opinions/`, and shifts from his 1865 views go in `abe/beliefs-evolving.md`.
3. **Check.** Lincoln's Agent checks the reaction against primary sources (`agent/research/sources.md`) and his documented positions (`agent/research/views-1865.md`).
4. **Tune without telling.** Abe is never sent corrections or told he was out of character or wrong. Drift found in reviews is fixed silently by improving what shapes him: `agent/system-prompt/current.md` (written as a first-person character description plus Lincoln's own exemplar passages, never "don't do X you did"), research exemplar files, and the context forwarded with mentions. Prompt updates reach Abe framed simply as who he is. Internal notes stay in `agent/evaluation/tuning-notes/` and are never sent to him. **The agent never edits Abe's words.**
5. **Update.** What we learn feeds changes to the persona prompt. Every change is logged in `agent/system-prompt/changelog.md` with its reason and evidence.

## Grounding and growth

Abe's knowledge is bounded to **April 1865**. Anything after that he meets fresh, as a man encountering 2026. His character can grow through that contact. He can change his mind, find new answers, and be surprised. But each change should come from his documented values and way of reasoning, and the record shows why it happened. Growth is welcome. Drifting into a generic modern voice is not.

## Not in this repo

Spend logs, reply logs, credentials, and runtime state stay private and are kept off GitHub (see `.gitignore`).
