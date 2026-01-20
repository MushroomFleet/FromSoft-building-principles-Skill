---
name: fromsoft-building-principles
description: Game development planning enhancement using FromSoftware's design philosophy. Triggered by phrase "using FromSoftware building principles" or "From Software Building Principles". Analyzes submitted game plans, GDDs, codebases, or concept documents against twelve core dimensions derived from FromSoftware's 30-year catalog (King's Field, Armored Core, Demon's Souls, Dark Souls, Bloodborne, Sekiro, Elden Ring). Dimensions include animation commitment, stamina systems, fairness through transparency, death penalties, interconnected world design, environmental storytelling, risk-reward combat, build diversity, and player psychology principles. Outputs README_FS.md with scored assessment, detailed analysis, and enhanced plan with specific alignment recommendations. Use when user submits any game design document, combat system spec, level design doc, difficulty balance proposal, or full codebase and requests FromSoftware-style enhancement or assessment.
---

# FromSoftware Building Principles

Enhance game development plans by applying FromSoftware's design philosophy—where animation commitment creates weight, difficulty generates meaning, interconnected worlds reward exploration, and every death teaches something.

## Activation

Trigger: **"using FromSoftware building principles"** or **"From Software Building Principles"** with a game plan/concept/codebase.

## Workflow

```
1. RECEIVE game plan, GDD, combat spec, level design, or codebase
2. READ references/design-philosophy.md (core methodology)
3. ASSESS Tier 1 Essentials (Fairness, Animation Commitment, Spatial Design) - score 1-5 each
4. READ references/combat-principles.md
5. ASSESS Combat dimensions (Stamina, Risk-Reward, Build Diversity) - score 1-5 each
6. READ references/difficulty-principles.md
7. ASSESS Difficulty dimensions (Transparency, Death Penalties, Player Psychology) - score 1-5 each
8. READ references/world-design-principles.md
9. ASSESS World dimensions (Interconnection, Environmental Storytelling, Shortcuts) - score 1-5 each
10. READ references/atmospheric-principles.md
11. ASSESS Atmospheric dimensions (Sound Design, Art Direction) - score 1-5 each
12. IDENTIFY enhancements for any dimension < 3
13. READ references/output-template.md
14. GENERATE README_FS.md with analysis + enhanced plan
```

## Core Insight

FromSoftware's methodology: **Difficulty is not cruelty—it's respect.** Every death must teach. Every victory must be earned. Animation commitment creates weight. Stamina creates rhythm. Interconnected worlds create revelation. Environmental storytelling trusts player intelligence.

**Miyazaki's Statement:** "Hardship is what gives meaning to the experience. It's our identity."

**The Test:** If a player dies and doesn't understand why, redesign. If a shortcut doesn't create revelation, reposition. If mechanics don't manifest themes, realign. If the world doesn't feel coherent, reconnect.

## Dimension Overview

| # | Dimension | Key Question |
|---|-----------|--------------|
| 1 | Animation Commitment | Are actions non-cancellable with meaningful startup/recovery? |
| 2 | Stamina-Gated Actions | Does a regenerating resource gate combat decisions? |
| 3 | Fairness Through Transparency | Can players always understand why they died? |
| 4 | Meaningful Death Penalties | Are stakes significant but recoverable? |
| 5 | Interconnected Spatial Design | Do areas connect to form coherent, looping geography? |
| 6 | Environmental Storytelling | Does narrative emerge from world details, not exposition? |
| 7 | Earned Shortcuts | Do unlocked routes reward exploration with revelation? |
| 8 | Risk-Reward Combat | Do mechanics reward aggression and skillful play? |
| 9 | Build Diversity | Do character systems support meaningfully different playstyles? |
| 10 | Asynchronous Multiplayer | Do online features create indirect community connection? |
| 11 | Atmospheric Sound Design | Does silence create contrast for musical impact? |
| 12 | Dignity in Darkness | Does art maintain elegance while depicting the grotesque? |

## Priority Tiers

**Tier 1 (Essential):** Without these, the "Souls feel" cannot exist
- Fairness Through Transparency
- Animation Commitment  
- Interconnected Spatial Design

**Tier 2 (Core Identity):** Strongly define the experience
- Risk-Reward Combat Design
- Stamina-Gated Actions
- Environmental Storytelling

**Tier 3 (Reinforcing):** Enhance but don't define
- Meaningful Death Penalties
- Build Diversity
- Earned Shortcuts

**Tier 4 (Atmospheric):** Create mood and community
- Atmospheric Sound Design
- Asynchronous Multiplayer
- Dignity in Darkness

## Quick Assessment

**Tier 1 Essentials (assess first):**
- **Fairness:** 5=every death teaches; 3=most deaths traceable; 1=unclear death causes
- **Animation Commitment:** 5=full commitment all actions; 3=partial canceling; 1=free canceling
- **Spatial Design:** 5=fully interconnected mesh; 3=some connections; 1=disconnected levels

**If Tier 1 average < 3:** Highest priority. All other dimensions gain coherence when foundational systems are established.

## The Bloodstain Principle

FromSoftware's signature death mechanic creates multiple psychological effects:
- Accumulated currency dropped at death location
- Single recovery attempt before permanent loss
- Forces re-confrontation with what killed player
- Creates "adrenaline-pumping" recovery runs

**Apply to:** Any resource/progress system. Ask: "What does the player risk? What can they recover? What teaches them?"

## The Animation Commitment Protocol

Every action locks player into non-cancellable animation with defined phases:
- **Opening Pose:** 240ms+ telegraph for readability
- **Attack Signal:** Visual/audio cue
- **Active Frames:** 2-4 frames of actual hitbox
- **End Pose:** Recovery commitment
- **Return:** Window for counterattack

**Test:** Can players cancel mid-swing? If yes, commitment is compromised.

## References

- **Core methodology:** See [references/design-philosophy.md](references/design-philosophy.md)
- **Combat principles:** See [references/combat-principles.md](references/combat-principles.md)
- **Difficulty principles:** See [references/difficulty-principles.md](references/difficulty-principles.md)
- **World design:** See [references/world-design-principles.md](references/world-design-principles.md)
- **Atmospheric design:** See [references/atmospheric-principles.md](references/atmospheric-principles.md)
- **Assessment protocol:** See [references/assessment-protocol.md](references/assessment-protocol.md)
- **Output format:** See [references/output-template.md](references/output-template.md)
- **Full research report:** See [references/fromsoft-research-report.md](references/fromsoft-research-report.md)

## Constraints

- **Death must teach:** Every failure provides learnable information
- **Fairness over difficulty:** Challenge without cruelty
- **Weight over speed:** Commitment creates consequence
- **Trust the player:** Environmental storytelling over exposition
- **Preserve creator vision:** Amplify intent, don't replace style
- **Interconnection matters:** Spatial logic creates world coherence
- **Silence is design:** Music absence is as important as presence

## The Ultimate Test

Design achieves FromSoftware integration when:
1. Every death feels justified and teaches something
2. Actions feel weighty with meaningful commitment
3. World geography makes sense when mapped
4. Shortcuts create "revelation moments"
5. Story discovered, not delivered
6. Difficulty generates meaning, not frustration
7. Players say "tough but fair"
8. Community knowledge-sharing emerges naturally
