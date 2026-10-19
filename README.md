# NOC Skills

Small, manually invoked Claude Code skills for telecom classroom exercises.

| Skill | Purpose |
| --- | --- |
| `noc-triage` | Assess incident evidence and recommend the next diagnostic check. |
| `noc-handoff` | Prepare a reviewable shift handoff from supplied evidence. |

Each skill consists of one SKILL.md. There are no scripts or dependencies.
Review the entire file before installing it. These are analysis procedures,
not network connectors, permission policies, or production operating procedures.

Install a reviewed skill in `~/.claude/skills/<skill-name>/SKILL.md` and start
Claude Code in your evidence project. Example:

```text
/noc-handoff Read incident.md and write handoff.md.
```

Only supplied local evidence is used. No network access is provided by these skills.
The classroom risk labels do not replace an operator's real approval policy.

The course download exercise uses the `v1.0.0` tag. Preserve that version;
publish later changes under a new tag and update the course checksum accordingly.

[Claude Code skill documentation](https://code.claude.com/docs/en/skills)
