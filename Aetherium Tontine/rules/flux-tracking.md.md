---
id: flux-tracking
type: rule
status: active
updated: 2025-11-12T15:00:00Z
tags: [core, world-state, gm-tool, hidden-stat]
---

# Mythic Flux: The Hidden World Stat

## What is Flux?
A **hidden GM stat** (0D to 10D) tracking regional magic levels. Players don't know exact number—only "feel" through descriptions.

## Regional Categories

### Vital Zone (Flux 8D-10D)
- **Description:** "The air hums with potential. Colors are brighter. You swear the walls are breathing."
- **Mechanics:** Magic +2D, Wild Die explodes on 5-6, spirits manifest physically
- **Example:** Verdant Scar epicenter, hidden Covenant groves

### Wyld Zone (Flux 5D-7D)
- **Description:** "Magic feels natural here, like a remembered song."
- ** Mechanics: ** Standard D6 Fantasy rules apply
- ** Example: ** Jade Mandate resonance gardens, Dusk Sultanate wells

### Thin Zone (Flux 2D-4D)
- **Description:** "Magic is a whisper, harder to grasp. The world feels 'thin.'"
- ** Mechanics: ** Magic is Difficult (+5), Wild Die 1 causes **Reality Bleed ** (GM narrates surreal consequence)
- ** Example: ** Most cities, Twilight Concordant

### Blight Zone (Flux 1D)
- **Description:** "Magic is a memory. The world is numb."
- **Mechanics:** Magic +10 Difficulty, Repletion rolls at -1D penalty
- **Example:** Vostok-Prime below the Spires, Obsidian Collective refineries

### Dead Zone (Flux 0D)
- **Description:** "Silence. Pure silence. Even thoughts feel mechanical."
- **Mechanics:** No magic. Wild Die disabled. Automatons +1D Technical. Living beings lose 1 Body Point/day from "soul-thinning."
- **Example:** Ferromancer's Spine, fully rationalized zones

## GM Tracking Method
In world/regions/[region].md, update **Flux Level** after each session:
```yaml
flux-current: 2D
flux-trend: decreasing  # stable | decreasing | increasing
flux-last-change: -0.5D (Session_002)