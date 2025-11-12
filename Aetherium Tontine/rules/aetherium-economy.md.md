---
id: aetherium-economy
type: rule
status: active
updated: 2025-11-12T15:00:00Z
tags: [core, resource-management, depletion-mechanic, economy]
---

# The Aetherium Economy: Depletion & Scarcity

## Core Principle
**Magic is fuel. Fuel is finite. Every use burns the world's soul.**

## Rod Types

### Standard Aetherium Rod
- **Charges:** 10
- **Cost:** £100 (Consortium zones) / £150 (black market)
- **Weight:** 0.5 kg
- **Flux Cost:** -0.1D per charge in 1-mile radius
- **Availability:** Common (but decreasing)

### Hyperflux Rod
- **Charges:** 50
- **Cost:** £1000 (restricted)
- **Weight:** 1 kg
- **Flux Cost:** -1D per activation
- **Availability:** Consortium military only (illegal for civilians)
- **Special:** Required for Reality-Killer devices

### Blood-Mana Flask (Obsidian Sun)
- **Charges:** 20
- **Cost:** £500 (illegal in 6 empires)
- **Flux Cost:** -0.2D per use (concentrated)
- **Effect:** +2D to spell potency
- **Availability:** Black market only

### Phlogiston Residue (Waste)
- **Charges:** 1 (single use)
- **Cost:** £10 (to dispose of) / £50 (to buy as weapon)
- **Flux Cost:** +0.1D (briefly raises Flux through chaotic backfire)
- **Risk:** 1-in-6 chance of Alchemical Unleashing on user

## Depletion Curve (Mathematical Model)

**Formula:** `Flux Loss = (Charges Used × Rod Multiplier) ÷ Regional Radius`

| Rod Type | Multiplier | Example (10 charges, 1-mile radius) |
|----------|------------|--------------------------------------|
| Standard | 0.1D | -1.0D total |
| Hyperflux | 1.0D | -10.0D total (catastrophic) |
| Blood-Mana | 0.2D | -2.0D total |
| Phlogiston | -0.1D* | +1.0D total (chaotic) |

*Phlogiston is waste—burning it releases trapped mythic energy chaotically

## Recovery Rate
- **Natural:** +0.1D per session if ZERO Aetherium used in region
- **Assisted:** +0.5D per session if Repletion ritual performed
- **Mythic Echo:** +1D permanent if Echo is nurtured for 5 sessions

## Exponential Decay Warning
In high-use zones (cities, battlefields), depletion doubles. What takes 10 charges to deplete in wilderness takes 5 charges in cities.

## Price Inflation
After each session where Aetherium is scarce in region:
- **Cost Increase:** +10% per session of scarcity
- **Maximum:** 5x base cost (£500 for standard rod)

## GM Tracking
Use **Mythic Ledger** to track regional Flux. Each session:
1. Note total charges burned in region
2. Calculate Flux loss
3. Apply recovery (if any)
4. Update world/regions/[region].md Flux Level

## Player-Facing
Players can **scavenge** for Aetherium:
- **Scavenge Roll:** Perception vs. Difficulty 25 in blight zones
- **Success:** Find 1d6-2 charges (minimum 0)
- **Wild Die 6:** Find intact rod (10 charges)
- **Wild Die 1:** Find "tainted" rod (causes Reality Bleed on use)