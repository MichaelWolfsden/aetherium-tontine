
---
id: global-flux-calculation
type: rule
status: active
updated: 2025-11-12T16:00:00Z
tags: [gm-tool, world-state, tracking, mathematical]


# Global Flux Calculation

## Formula
**Global Flux = (Sum of all Regional Flux) ÷ Number of Regions**

## Regions (8 Emporiums)
Each region has **Base Flux** and **Current Flux**:

| Region | Base Flux | Current (Y500) | Trend |
|--------|-----------|----------------|-------|
| Aetheric Admiralty | 5D | 1D | Decreasing |
| Iron Compact | 5D | 0D | Stable (dead) |
| Obsidian Senate | 6D | 2D | Decreasing |
| Twilight Concordant | 5D | 2D | Unstable |
| Raven Throne | 7D | 3D | Decreasing |
| Dusk Sultanate | 7D | 4D | Stable |
| Jade Mandate | 8D | 5D | Stable |
| Obsidian Sun Collective | 6D | 1D | Critical |

## Calculation Example (Year 500)

Sum = 1D + 0D + 2D + 2D + 3D + 4D + 5D + 1D = 18D Regions = 8 Global Flux = 18D ÷ 8 = 2.25D (round to 2D)
## Critical Thresholds

### Global Flux 5D-10D (Vital Age)
- **Era:** "The Fracture is manageable"
- **Tone:** Hopeful exploration
- **Magic:** Abundant
- **Threat:** Faction politics

### Global Flux 3D-4D (Thin Age)  
- **Era:** "The Tontine tightens"
- **Tone:** Noir desperation
- **Magic:** Scarce
- **Threat:** Resource wars

### Global Flux 1D-2D (Blight Age)  
- **Era:** "The last gasp" *(Current)*
- **Tone:** Survival horror
- **Magic:** Dying
- **Threat:** Extinction

### Global Flux 0D (Silence Age)
- **Era:** "The silence after"
- **Tone:** Reconstruction or surrender
- **Magic:** Dead
- **Threat:** Automaton supremacy

## Tracking Spreadsheet (GM Use)

SESSION #___ Regional Updates:

- Admiralty: 1D → ___ (charges: ___, Repletion: ___)
    
- Compact: 0D → ___ (stable)
    
- Senate: 2D → ___ (charges: ___, Repletion: ___)
    
- Concordant: 2D → ___ (charges: ___, Repletion: ___)
    
- Throne: 3D → ___ (charges: ___, Repletion: ___)
    
- Sultanate: 4D → ___ (charges: ___, Repletion: ___)
    
- Mandate: 5D → ___ (charges: ___, Repletion: ___)
    
- Collective: 1D → ___ (charges: ___, Repletion: ___)
    

NEW GLOBAL FLUX: ___D Trend: ↑ (if +1D or more) ↓ (if -1D or more) → (if stable) Doom Track Progress: ___/6


## Session Impact
After each session:
1. **Sum all charges burned** across all regions
2. **Apply Depletion:** -0.1D per 10 standard rods (round down)
3. **Apply Repletion:** +0.5D per successful ritual (max +1D/session)
4. **Apply Recovery:** +0.1D if ZERO charges used in region
5. **Recalculate Global Flux**
6. **Check Thresholds:** If crossing from 2D→1D or 1D→0D, narrate world-change

## Narrating Global Flux Changes
**When Global Flux drops from 2D to 1D:**
- "The world feels... smaller. The songs have stopped."
- **Effect:** All regions feel Thin Zone effects, even Vital ones
- **GM:** Increase all difficulties by +2 for one session (adjustment period)

**When Global Flux rises from 1D to 2D (Repletion):**
- "A breath of fresh air. For the first time in months, you see a real bird."
- **Effect:** All regions gain +0.5D (temporary boost of hope)
- **GM:** Decrease all difficulties by -2 for one session

## Endgame Triggers
**If Global Flux remains 0D for 3 consecutive sessions:**
- **Event:** The Final Theorem (Consortium victory)
- **Result:** Campaign ends or shifts to **Silence Era** reboot

**If Global Flux reaches 10D (Repletion miracle):**
- **Event:** Mythic Rebirth
- **Result:** Campaign ends or shifts to **Reconstruction Era**