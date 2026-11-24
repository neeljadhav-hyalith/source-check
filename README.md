# source-check

A Claude skill that checks every number and factual claim before you publish a post, deck, article, newsletter or pitch. It lists each claim, finds the source behind it, grades the source A (primary), B (reputable secondary) or C (weak or none), checks the claim against what the source actually says, and gives you 1 table: keep, soften, replace or cut. It also writes the brief for a deep research tool and validates the report that comes back. It changes nothing in your draft without your yes.

Built by Neel Jadhav, Hyalith AI. More free tools: https://hyalith.ai/resources

## Install

**Claude Code:** copy this folder into `~/.claude/skills/source-check/` (or your project's `.claude/skills/`).

**Claude.ai:** Settings > Capabilities > Skills > Upload skill, and upload a zip of this folder. Turn on web search so Claude can open the sources.

## How to use

1. Paste your draft, or point Claude at the file.
2. Ask: "check my numbers" or "source-check this before I publish".
3. Read the table. Approve the rewrites you want.

For research: ask Claude to "write a research brief" for your question, paste the brief into your research tool, then bring the report back and ask Claude to "validate this research report".

## What is inside

- `SKILL.md`: the instructions Claude follows: the 5 steps, the 3 grades, the checks that catch a good source behind a wrong claim, the red flags, and the 8-step validation for research reports.
- `templates/research-brief.md`: a paste-ready brief for any deep research tool, with the source rules, claim tags and self-check that make its report checkable.
- `WORKED-EXAMPLE.md`: the skill run on 7 claims from the hyalith.ai framework pages, with every source URL.

## Licence

MIT. Use it, change it, share it.
