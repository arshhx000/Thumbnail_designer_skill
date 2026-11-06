# Thumbnail Designer Skills

A structured [Agent Skill](https://github.com/anthropics/skills) for [Claude Code](https://code.claude.com/docs/en/skills), [Claude.ai](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills), [OpenAI Codex](https://developers.openai.com/plugins/build/skills), and other compatible AI agents. It captures a complete YouTube thumbnail workflow, creative principles, and visual design preferences for creating clear, compelling, clickable thumbnails.

## Quick Install (`npx skills`)

Install directly into Claude Code, OpenAI Codex, Cursor, or 75+ supported agents using the [`npx skills` CLI](https://github.com/vercel-labs/skills):

```bash
npx skills add arshhx000/Thumbnail_designer_skill --skill Thumbnail_designer_skills
```

To install globally across all your projects:

```bash
npx skills add arshhx000/Thumbnail_designer_skill --skill Thumbnail_designer_skills -g
```

## How to Use

* **Claude Code**: Type `/Thumbnail_designer_skills <video topic>` or ask naturally for a YouTube thumbnail.
* **OpenAI Codex**: Type `$thumbnail-designer-skills <video topic>` or ask naturally to trigger the thumbnail workflow.
* **Claude.ai (Web / Desktop)**: Download `Skills/Thumbnail_designer_skills/SKILL.md`, zip the `Thumbnail_designer_skills` folder, and upload it under **Customize > Skills > + Create skill > Upload skill** ([Claude Help Center](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)).

## What This Skill Does

1. **Finds the Core Concept**: Identifies the single most interesting idea, emotional hook, or curiosity gap.
2. **Plans the Composition**: Establishes focal hierarchy, subject placement, depth, balance, and negative space.
3. **Controls Visual Execution**: Guides lighting, colour, typography, shadows, cutouts, dimensionality, and image quality.
4. **Packages Thumbnail + Title**: Creates a visual hook and supporting title that work together without repeating each other.
5. **Keeps It Clickable and Clear**: Maintains legibility, contrast, and readability at small YouTube thumbnail sizes.

This document is used as the default process whenever a new thumbnail is requested.

## License

MIT
