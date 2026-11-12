# agent-skills

A collection of reusable skills for AI coding agents. Each skill is a folder containing a `SKILL.md`: YAML frontmatter (name, description, metadata) followed by the instructions an agent loads when the skill applies.

## Skills

| Skill                                                       | Description                                                                                                                                                               |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [repo-audit](repo-audit/SKILL.md)                           | Triage an unfamiliar repo from its git history before reading code: churn hotspots, contributor concentration, bug-prone files, delivery pace, and firefighting patterns. |
| [writing-commit-messages](writing-commit-messages/SKILL.md) | Write Git commit messages in a `<subsystem>: <summary>` format, with issue references and a short prose explanation of the change.                                        |

## Install

Copy a skill's folder into your agent's skills directory, for example:

- Copilot: `~/.copilot/skills/` — in a new session, run `/skills` and press `r` to refresh the list.
- Zed: `~/.agents/skills/`

## Licence

[MIT](LICENCE)
