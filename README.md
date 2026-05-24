# 🏗️ Floor Plan AI — Claude Skill

A professional architectural floor plan workflow for Claude that uses **floor-plan.ai** via the Claude in Chrome extension. Designed by a licensed architect for real-world project use — from a single room to large commercial buildings.

---

## What This Skill Does

When you type `/floorplan` or describe a layout need, Claude will:

1. **Gather your project requirements** (type, location, GFA, program)
2. **Build a professional architectural brief** automatically
3. **Engineer an optimized prompt** for floor-plan.ai — and show it to you before executing
4. **Open floor-plan.ai in Chrome**, configure settings, and generate the floor plan
5. **Pause and present the result** with an architectural critique — you decide what happens next
6. **Produce a written architectural brief** as a `.docx` document
7. **Auto-activate companion skills** based on project context (marketing, presentations, research)

---

## Trigger Commands

```
/floorplan
/fp
/floor-plan
"design a floor plan for..."
"I need a layout for..."
"generate a floor plan..."
```

---

## Prerequisites

| Requirement | Notes |
|------------|-------|
| [Claude.ai](https://claude.ai) account | Pro plan recommended |
| [Claude in Chrome](https://chromewebstore.google.com/detail/claude/...) extension | For browser automation |
| [floor-plan.ai](https://floor-plan.ai) account | Free account works; credits needed for generation |

---

## Install

```bash
npx skills add YOUR_GITHUB_USERNAME/floor-plan-ai
```

---

## Integrated Skills (Auto-Triggered)

This skill automatically activates companion skills based on project context:

| Trigger | Skill Activated |
|---------|----------------|
| Commercial / F&B / hospitality project | `market-researcher` |
| Client pitch or investor meeting | `presentation` |
| Japanese company involved | `co-marketing` + `presentation` |
| Visual concept board needed | `canvas-design` |
| New venue / business launching | `marketing-ideas` |

---

## Building Standards Supported

| Location | Standard Applied |
|----------|-----------------|
| 🇶🇦 Qatar | Qatar National Building Code (QNBC) |
| 🇯🇵 Japan | Building Standard Law (BSL) / BCJ |
| 🌍 International | International Building Code (IBC) |

---

## Example Usage

```
/floorplan
Restaurant in Doha, Qatar
Ground floor only, approximately 400m²
Open kitchen, dining for 80 covers, private dining room, 
bar area, staff area, storage, 2x bathrooms
```

Claude will build the brief, engineer the prompt, execute in Chrome, 
show you the result, and produce a full architectural brief document.

---

## Project Types Supported

Residential · Commercial · Hospitality & F&B · Mixed-Use · Retail · Office · Industrial · Institutional · Masterplan

---

## Author

Built by **Mohammed** — Licensed Architect, B.Arch (Hons), based in Doha, Qatar.
Specializing in Japanese–Qatari business development and architectural projects.

---

## License

MIT — free to use, modify, and distribute.
