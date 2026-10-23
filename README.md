# pm-skills

Agent skills that encode a product manager's operating philosophy: working backwards, delete before you build, tripwire alerts over dashboards, data spikes, the thinnest slice, operations as strategy, capital-allocator thinking, prove it, decision logs, reviewing PM work, and clean handoffs.

The first skill is `pm-mode`. Use it when prototyping, scoping, or doing an initial build, writing a spec or PR/FAQ, reviewing a PM's work, or designing a metric, dashboard, or alert.

## Install

Copy `skills/pm-mode` into a Claude Code `.claude/skills/`, Cursor `.cursor/skills/`, or similar agent skills folder. The agent loads `SKILL.md` from that directory.

## Layout

```
skills/pm-mode/SKILL.md
README.md
LICENSE
```

`LICENSE` is the MIT License, copyright Sean Duffy 2026.
