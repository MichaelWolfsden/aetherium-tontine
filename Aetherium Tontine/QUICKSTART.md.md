# Aetherium Tontine Quick Reference

## File Naming
- Regions: `world/regions/[kebab-name].md`
- Locations: `world/locations/[kebab-name].md` (must link to region)
- Factions: `world/factions/[kebab-name].md`
- NPCs: `world/npcs/[kebab-name].md` (must link to location & faction)
- Items: `items/[kebab-name].md`
- Sessions: `sessions/Session_XXX.md` (sequential, zero-padded)

## YAML Minimums
Every dynamic file MUST have:
id: [matches filename]
type: [region|location|faction|npc|item]
status: [active|dormant|destroyed|hidden]
updated: [ISO timestamp]

## Session Workflow
1. Party discusses → Submit actions
2. Cogsworth resolves → Rolls dice
3. Narrative written → Deltas generated
4. Files updated → Changelog appended
5. Next session → Reference updated state

## Key Commands
- "Cogsworth, scan for updated files since [timestamp]"
- "Cogsworth, apply delta [dX::] to [file]"
- "Cogsworth, show faction relationships"
- "Cogsworth, calculate current global Flux"

## Delta Folding
After session, run: "Cogsworth, fold Session_XXX deltas into main files"
This moves bullet points from ## Deltas to main content and clears delta section.