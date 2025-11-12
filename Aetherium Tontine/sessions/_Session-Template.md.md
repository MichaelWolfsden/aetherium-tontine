---
session: XXX
date: YYYY-MM-DD
players: [Player1, Player2, Player3]
gm: Cogsworth
starting-flux: XD (global)
starting-pressure: XD (if using Pressure rules)
location: world/locations/template-location.md
faction-status: [consortium-active, covenant-patrol, unchained-hidden]
tags: [session-log, in-progress, episode-arc]
---

# Session XXX: [Episode Title]

## Narrative Summary
*Write a noir-steampunk style summary of events. Include sensory details, character moments, and world-building.*

Example: "The Engine Song echoed through the soot-lanes as Gear-Heart's wrench slipped on the valve. The pressure gauge hit red-line. In the shadows, Jaguar-Knight's blade caught the steam-light..."

## Key Events
1. **[Event 1]:** [Brief description with mechanical context]
2. **[Event 2]:** [Brief description with mechanical context]
3. **[Event 3]:** [Brief description with mechanical context]
4. **[Event 4]:** [Brief description with mechanical context]

## Deltas
*Append-only list of world-state changes. Use [dX::] format for AI parsing.*

- [d1::] world/locations/[location].md → [specific change]
- [d2::] world/npcs/[npc].md → [HP/status/relationship change]
- [d3::] world/factions/[faction].md → [reputation/resource change]
- [d4::] world/regions/[region].md → [Flux level/Doom Track change]
- [d5::] items/[item].md → [charges/holder/status change]
- [d6::] rules/[rule].md → [optional: mechanical rule adjustment]

## Ending State
- **Party Location:** [Where they end the session]
- **Regional Flux:** X.XD (updated from starting)
- **Mythic Resonance:** XD (party pool)
- **Doom Track:** X/6 (if applicable)
- **Immediate Threats:** [What's bearing down on them next session]
- **New Hooks:** [Plot threads introduced]
- **Player Notes:** [Unresolved questions, plans for next session]

## Mechanical Totals
*For GM quick-reference:*
- **Aetherium Charges Used:** X standard, X hyperflux
- **Repletion Actions:** X attempted, X successful
- **Depletion Applied:** -X.XD (regional)
- **Character Points Spent:** X total
- **Fate Points Spent:** X total
- **Wild Die 1s:** X occurrences
- **Wild Die 6s:** X occurrences

## Next Session Hook
*Clear trigger for next episode:*
- "As the blast doors lock, Inquisitor Voss offers a choice..."
- "The garden's echo attracts a Remnant Choir entity..."
- "Engine #8's stress pattern hits critical..."

---

### **SESSION CHECKLIST FOR GM**

**Pre-Session:**
- [ ] Copy template to `sessions/Session_XXX.md`
- [ ] Update YAML with session number, date, players
- [ ] Note starting Flux/Pressure from previous session's "Ending State"
- [ ] Prepare 3-5 potential hooks based on unresolved deltas

**During Session:**
- [ ] Track Aetherium usage per player
- [ ] Note Wild Die distribution (1s vs 6s)
- [ ] Record Repletion attempts and justification
- [ ] Monitor Doom Track progression
- [ ] Update NPC HP/status in real-time

**Post-Session:**
- [ ] Write narrative summary (noir-steampunk style)
- [ ] List all mechanical changes as deltas
- [ ] Update target files with [dX::] markers
- [ ] Calculate Flux Depletion/Repletion
- [ ] Advance Doom Track if applicable
- [ ] Update Mythic Resonance pool
- [ ] Note "Next Session Hook"
- [ ] Append to `logs/changelog.md`

**Delta Folding (Between Sessions):**
- [ ] Run: `Cogsworth, fold Session_XXX deltas`
- [ ] Verify target files updated with new bullet points
- [ ] Clear ## Deltas section (ready for next session)
- [ ] Update `updated:` timestamps in affected files

---

### **EXAMPLE SESSION FILLED**

---
session: 001
date: 2025-11-12
players: [Gear-Heart, Jaguar-Knight, Skald-Berserker]
gm: Cogsworth
starting-flux: 5D (global), 2D (Vostok-Prime regional)
starting-pressure: 0D
location: world/locations/vostok-prime.md
faction-status: [consortium-active, covenant-cells, unchained-hidden]
tags: [session-log, complete, engine-song-arc]
---

# Session 001: The Engine Song

## Narrative Summary
The Engine District of Vostok-Prime never sleeps, but it dreams. Gear-Heart heard the song first—a harmonic in the steam-pipes that wasn't in the schematics. His wrench slipped on the pressure valve, and for a moment, the entire district held its breath. The gauge hit red-line. The Mythic Flux rippled. And in the shadows below, Jaguar-Knight's blade caught the steam-light as Inquisitor Voss's boots rang on the catwalk. The Song had an audience.

Skald-Berserker's voice rose above the hiss, an old saga in a language the workers had forgotten they knew. They looked up. They remembered. For three seconds, the engine of the world sang back.

## Key Events
1. **Engine #7 Discovery:** Gear-Heart identified Repletion potential in the steam harmonics while performing "routine maintenance."
2. **Song-Echo Creation:** Skald-Berserker's saga resonated with the engine's frequencies, creating a Mythic Echo that workers began humming.
3. **Inquisitor Confrontation:** Voss detected the Flux spike but hesitated due to the Echo's beauty, giving party 30 seconds before blast doors locked.
4. **Jaguar-Knight Infiltration:** Used chaos to slip into Phlogiston Storage, discovering a leak causing 3 workers to mutate (Alchemical Unleashing).

## Deltas
- [d1::] world/locations/vostok-prime.md → Engine #7 offline for 1d6 hours, Song-Echo active
- [d2::] world/locations/vostok-prime.md → Regional Flux 2D → 3D (local Repletion)
- [d3::] world/npcs/inquisitor-voss.md → Disposition confused, Social Debt triggered (1 favor owed)
- [d4::] world/regions/aetheric-admiralty.md → Doom Track 0/6 → 1/6 (Engine #8 stress +20%)
- [d5::] world/factions/consortium.md → Alert Level: HIGH (new), Reputation -1D (district control)
- [d6::] world/factions/covenant.md → Reputation +1D (Repletion witnessed)

## Ending State
- **Party Location:** Split—Gear-Heart in Engine Room, Jaguar-Knight in Phlogiston Storage, Skald-Berserker with workers in Soot-Lanes
- **Regional Flux:** 3D (Vostok-Prime), 4.9D (Global)
- **Mythic Resonance:** +1D (party pool now 1D)
- **Doom Track:** 1/6 (Engine #8 showing stress patterns)
- **Immediate Threats:** Enforcer Automatons deploying to break strike, Remnant Choir attracted to Echo
- **New Hooks:** "The Inquisitor's Mercy" (24-hour reprieve), "Phlogiston Leak" (mutating workers), "Song in the Pipes" (Consortium investigation)
- **Player Notes:** Can they fix Engine #8 without killing the Song? What's Alpha-7's offer?

## Mechanical Totals
- **Aetherium Charges Used:** 5 standard rods (party), 10,000 (city depletion abstracted)
- **Repletion Actions:** 1 attempted, 1 successful (Song-Echo)
- **Depletion Applied:** -0.5D (city abstracted), -0.1D (party) = -0.6D regional
- **Character Points Spent:** 2 total (Gear-Heart 1, Jaguar-Knight 1)
- **Fate Points Spent:** 0 total
- **Wild Die 1s:** 1 (Gear-Heart's venting attempt)
- **Wild Die 6s:** 2 (Skald-Berserker's performance, Jaguar-Knight's stealth)

## Next Session Hook
As the blast doors begin their pneumatic scream, Inquisitor Voss's voice cuts through: "You have twenty-four hours. Fix the engine, erase your debt—or I vent the entire district into the sky and let the Soot-Lanes choke on your legend."

In the storage bay below, the mutating workers turn their new eyes to Jaguar-Knight. One speaks, voice like grinding gears: "We can hear the Song too. Will you teach us to sing it?"