# skills

Reusable agent skills for design and workflows.

## Available Skills

- **[compound-design](./compound-design/SKILL.md)** — Extract design rules, taste decisions, anti-patterns, and component/token findings from a conversation and compound them into any design system's documentation (`AGENTS.md`, `design-system.md`, etc.).
- **[review-design](./review-design/SKILL.md)** — Review UI code, components, pages, or diffs against a design system's accumulated rules, tokens, and anti-slop guidelines.
- **[research-artifacts](./research-artifacts/SKILL.md)** — Turn raw qualitative user research into structured, visual service design artifacts (Journey Maps, Service Blueprints, Stakeholder Maps, Opportunity Solution Trees).

## Usage

Install into a project or global agent skills directory, for example:

```bash
npx skills add bergets/skills
```

Or copy a skill folder directly into `.agents/skills/` in your repository.
