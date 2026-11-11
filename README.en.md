# Solo Operator Skills for Claude (free edition)

A small set of skills for people who run a solo business or side project with Claude (claude.ai or Claude Code), so you do not have to retype the same instructions every time.

These skills give Claude checklists and procedures. They do not give legal or tax advice, and they do not promise any income or results.

[日本語版 README](README.md)

## What's inside

| Skill | Use it when |
|---|---|
| `small-experiment-en` | You want to try something new, or judge the result of a test. Designs a test you can measure within two weeks and gives a record format. |
| `publish-check-en` | Before you publish or send an article, video script, post, listing, book, course, or email. Checks unsupported numbers, income promises, ad/affiliate disclosure, AI-content labels, platform rules, and privacy. |

Japanese-market skills (`jp-publish-check`, `small-experiment`, `side-job-tax-memo`, `affiliate-link-check`) are also in this repo; see the Japanese README.

Each skill lives in `skills/<skill-name>/SKILL.md`.

## Install

### claude.ai

1. Zip the skill folder (for example `skills/publish-check-en`). The zip must contain one folder named after the skill, with `SKILL.md` directly inside it.
2. In claude.ai, open Customize > Skills, upload the zip, and turn it on. Skills need code execution to be enabled. Menu names and steps may change, so check Anthropic's current help pages.

### Claude Code

1. Copy the skill folder into your project's `.claude/skills/` (for example `.claude/skills/publish-check-en/SKILL.md`).
2. To use it in every project, put it in `~/.claude/skills/` instead.
3. Restart Claude Code and ask, for example, "Check this before I publish." Claude picks the skill whose description matches.

## Usage examples

- "Check this article before I publish it."
- "Design a two-week test: I want to change my posting time next week."
- "Is this video script OK to upload? It has an affiliate link."
- "It's judging day for my thumbnail test. Here are the numbers."

## Notes

- Laws and platform rules change and differ by country. These skills list general things to check. They are not legal or tax advice. Verify against official sources (for example the FTC in the US, or your local regulator, tax authority, and each platform's current rules). When unsure, ask a qualified professional.
- Claude can be wrong. Review everything yourself before you publish, send, or file.

## License

MIT License. Author: NeuralAlpha

## Paid edition

For people running several businesses with Claude Code, there is a paid kit covering role split, autonomy levels, an experiment ledger, and daily reporting, with templates and scripts. If the free skills are enough for you, you can ignore this.
- English edition: search "NeuralAlpha AI staff kit" on Gumroad

(This is our own product.)
