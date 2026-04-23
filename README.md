# Medium Post Writer

Master authentic Medium article generator using emotion-first, phased architecture. Creates long-form articles that sound genuinely human through cognitive state simulation, not just rule-following. Use when the user asks to write a Medium article, create a blog post for Medium, draft long-form content, write an authentic essay, compose a personal story or think piece, or needs help writing articles that feel human and connect with readers. Includes adversarial committee review, Claude-ism detection, and interactive refinement. Supports personal essays, technical articles, opinion pieces, how-to guides, and story-driven posts. Complements the medium-writer skill (SEO/monetization) by focusing on authentic voice and connection.

## What this repo contains

- `SKILL.md` — the primary agent skill definition and workflow.
- `references/` — supporting playbooks, platform rules, examples, or data used by the skill.

## Reference material

- `references/examples.md`
- `references/article-structures.md`
- `references/tool-mentions.md`
- `references/publications.md`
- `references/claude-isms.md`

## Installation

Copy this repository or the skill directory into your agent's skills directory, then load the skill by name when the task matches its use case.

```bash
# example
cp -R medium-post-writer ~/.claude/skills/medium-post-writer
```

## Repository layout

```text
references/
  article-structures.md
  claude-isms.md
  examples.md
  publications.md
  tool-mentions.md
LICENSE
SKILL.md
```

## Notes

The root README summarizes the live repository contents. The complete operational instructions remain in `SKILL.md`.
