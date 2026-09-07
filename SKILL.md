---
name: prompt-library
description: Selects, fills, and improves the user's reusable prompt templates. Use when the user asks to find, apply, save, organize, or improve a prompt template or prompt library.
---

# Prompt Library

Templates live alongside this skill, organized by task category.

## Use a template

1. Read `README.md`, then select the narrowest matching template.
2. Ask only for variables that materially change the result. If context supplies a value, fill it.
3. Return a ready-to-paste prompt. Do not leave `{{variables}}` unresolved.
4. Preserve the template's constraints unless the user overrides them.

## Improve the library

- Put one reusable task in one Markdown file with YAML frontmatter.
- Reuse `_templates/prompt-template.md`.
- Edit an existing template when the task is the same; create one only for a genuinely distinct task.
- Keep instructions concrete: role, input, constraints, output format.
- Never encode private data, secrets, or one-off context in a reusable template.
