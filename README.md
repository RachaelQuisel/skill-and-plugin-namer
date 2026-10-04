# Skill & Plugin Namer

<img src="assets/skill-and-plugin-namer.png" width="160" alt="Skill and Plugin Namer icon: a charcoal name tag on muted blush">

Give your idea a name people understand. Turn a skill or plugin concept into a clear name, a tagline, and listing copy.

## What it does

- Suggests three to five names for a concept
- Recommends a winner with a short explanation
- Writes a tagline with personality
- Drafts a description and scannable feature bullets
- Explains how to use the tool in plain language

## Install in Codex

Ask Codex:

> Install the skill from the root of https://github.com/RachaelQuisel/skill-and-plugin-namer with the name skill-and-plugin-namer.

The skill is available on your next turn after installation.

## Use

```text
$skill-and-plugin-namer
Name a skill that turns meeting transcripts into useful follow-up questions.
The audience is independent consultants.
Give me a shortlist, a recommended name, and listing copy.
```

Provide what the tool does, its inputs and outputs, and who it is for. The skill favors clear names, puts personality in the copy, and uses confirmed capabilities rather than invented facts. Any time budget should be presented as an estimate unless it has been measured.

## Files

- `SKILL.md`: the skill instructions
- `agents/openai.yaml`: Codex display name, prompts, and icon references
- `assets/skill-and-plugin-namer.png`: the skill icon
- `references/listing-formula.md`: the listing structure and worked examples
