# FromSoftware Building Principles Skill

A Claude skill for enhancing game development plans using FromSoftware's 30-year design philosophy—from King's Field (1994) through Elden Ring (2022) and Armored Core 6 (2023).

> *"Hardship is what gives meaning to the experience. It's our identity."* — Hidetaka Miyazaki

## Overview

This skill transforms Claude into a game design advisor that evaluates and enhances development plans against 12 core dimensions derived from FromSoftware's catalog:

| Tier | Dimensions |
|------|------------|
| **Essential** | Fairness Through Transparency, Animation Commitment, Interconnected Spatial Design |
| **Core Identity** | Risk-Reward Combat, Stamina-Gated Actions, Environmental Storytelling |
| **Reinforcing** | Death Penalties, Build Diversity, Earned Shortcuts |
| **Atmospheric** | Sound Design, Asynchronous Multiplayer, Dignity in Darkness |

## What It Does

When triggered, the skill:

1. **Assesses** your game plan, GDD, combat spec, level design doc, or codebase
2. **Scores** each of the 12 dimensions (1-5 scale)
3. **Identifies** enhancement priorities based on tier importance
4. **Generates** `README_FS.md` with detailed analysis and an enhanced plan

## Trigger Phrases

Use either of these phrases with your input:

- `"assess my development_plan.md using FromSoftware building principles"`
- `"evaluate this GDD using From Software Building Principles"`
- `"enhance my combat system spec with FromSoftware building principles"`

## Example Usage

```
User: Assess my game design document using FromSoftware building principles

[attaches game_design.md]

Claude: [Reads skill references, analyzes document against 12 dimensions, 
        generates README_FS.md with scores, analysis, and enhanced plan]
```

## Installation

### Claude Code (CLI)

1. Clone this repository:
```bash
git clone https://github.com/MushroomFleet/FromSoft-building-principles-Skill.git
```

2. Copy the skill folder to your Claude Code skills directory:
```bash
cp -r FromSoft-building-principles-Skill/fromsoft-building-principles ~/.claude/skills/
```

3. The skill will be available in your next Claude Code session.

### Claude Web (claude.ai)

1. Download the `fromsoft-building-principles.skill` file from this repository's [Releases](https://github.com/MushroomFleet/FromSoft-building-principles-Skill/releases)

2. Navigate to [claude.ai](https://claude.ai)

3. Go to **Settings** → **Skills** → **Add Skill**

4. Upload the `.skill` file

5. The skill is now active in your conversations

### Manual Installation

If you prefer manual setup, ensure the following structure exists in your skills directory:

```
fromsoft-building-principles/
├── SKILL.md
├── assets/
│   └── README_FS_template.md
└── references/
    ├── design-philosophy.md
    ├── combat-principles.md
    ├── difficulty-principles.md
    ├── world-design-principles.md
    ├── atmospheric-principles.md
    ├── assessment-protocol.md
    ├── output-template.md
    └── fromsoft-research-report.md
```

## The 12 Dimensions

### Tier 1: Essential (Without these, the "Souls feel" cannot exist)

| Dimension | Key Question |
|-----------|--------------|
| **Fairness Through Transparency** | Can players always understand why they died? |
| **Animation Commitment** | Are actions non-cancellable with meaningful startup/recovery? |
| **Interconnected Spatial Design** | Do areas connect to form coherent, looping geography? |

### Tier 2: Core Identity (Strongly define the experience)

| Dimension | Key Question |
|-----------|--------------|
| **Risk-Reward Combat** | Do mechanics reward aggression and skillful play? |
| **Stamina-Gated Actions** | Does a regenerating resource gate combat decisions? |
| **Environmental Storytelling** | Does narrative emerge from world details, not exposition? |

### Tier 3: Reinforcing (Enhance but don't define)

| Dimension | Key Question |
|-----------|--------------|
| **Meaningful Death Penalties** | Are stakes significant but recoverable? |
| **Build Diversity** | Do character systems support meaningfully different playstyles? |
| **Earned Shortcuts** | Do unlocked routes reward exploration with revelation? |

### Tier 4: Atmospheric (Create mood and community)

| Dimension | Key Question |
|-----------|--------------|
| **Atmospheric Sound Design** | Does silence create contrast for musical impact? |
| **Asynchronous Multiplayer** | Do online features create indirect community connection? |
| **Dignity in Darkness** | Does art maintain elegance while depicting the grotesque? |

## Output Format

The skill generates `README_FS.md` containing:

- **Executive Summary** — Project overview and key opportunities
- **Part I: Assessment** — Detailed scoring of all 12 dimensions
- **Part II: Enhancement Summary** — Prioritized improvement checklist
- **Part III: Detailed Enhancements** — Specific recommendations per dimension
- **Part IV: Implementation** — Priority matrix and phased approach
- **Part V: Enhanced Plan** — Complete rewritten design document
- **Appendix: The FromSoftware Test** — Final validation checklist

## Supported Input Types

- Game Design Documents (GDD)
- Combat system specifications
- Level design documents
- Difficulty balance proposals
- Character progression specs
- World/narrative design docs
- Full codebases (for implementation assessment)
- Concept pitches

## Related Skills

This skill follows the same pattern as other game development advisor skills:

- [Kojima Building Principles](https://github.com/MushroomFleet/kojima-building-principles) — Mythological substrate and strand systems
- [Toriyama Building Principles](https://github.com/MushroomFleet/toriyama-building-principles) — Visual design and character philosophy

## License

MIT License - See [LICENSE](LICENSE) for details.

---

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{fromsoft_building_principles,
  title = {FromSoftware Building Principles Skill: Game Development Advisory Using FromSoftware Design Philosophy},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/FromSoft-building-principles-Skill},
  version = {1.0.0}
}
```

### Donate

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)
