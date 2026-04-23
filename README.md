# Pinterest Post Writer

Creates Pinterest content (pin titles, descriptions, board titles, Idea Pin text) using an 8-phase emotion-first cognitive simulation system. Specialized for Pinterest's unique nature as a visual search engine with evergreen content, not a traditional social platform. Optimizes for search discoverability, save intent, and long-term traffic while maintaining authentic, human voice. Use when creating ANY Pinterest content - product pins, blog post pins, Idea Pins, board descriptions, or adapting existing content for Pinterest. Interactive by default with adversarial committee review to eliminate Claude-isms and generic marketing language.

## What this repo contains

- `SKILL.md` — the primary agent skill definition and workflow.
- `references/` — supporting playbooks, platform rules, examples, or data used by the skill.

## Use cases

- Creating pin titles and descriptions for blog posts, products, or resources
- Writing board titles and descriptions for content organization
- Drafting Idea Pin text overlays and narration
- Adapting existing content for Pinterest's search-first environment
- Optimizing underperforming pins for better discoverability
- Creating seasonal or evergreen pin content strategies

## Reference material

- `references/examples.md`
- `references/tool-mentions.md`
- `references/pin-formats.md`
- `references/communities.md`
- `references/claude-isms.md`

## Installation

Copy this repository or the skill directory into your agent's skills directory, then load the skill by name when the task matches its use case.

```bash
# example
cp -R pinterest-post-writer ~/.claude/skills/pinterest-post-writer
```

## Repository layout

```text
references/
  claude-isms.md
  communities.md
  examples.md
  pin-formats.md
  tool-mentions.md
LICENSE
SKILL.md
```

## Notes

The root README summarizes the live repository contents. The complete operational instructions remain in `SKILL.md`.
