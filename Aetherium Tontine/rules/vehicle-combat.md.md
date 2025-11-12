---
id: vehicle-combat
type: rule
status: active
updated: 2025-11-12T15:00:00Z
tags: [combat, vehicles, airships, trains, optional]
---

# Vehicle & Device Combat (Skyships, Trains, Steam-Tanks)

## Scale System
- **Personal:** 0D (PCs, NPCs)
- **Vehicle:** +3D (airships, trains, tanks)
- **Capital:** +6D (sky-cities, fortresses)

## Subsystem Targeting
Instead of overall HP, target specific systems:

| System | Effect When Damaged | Destroyed |
|--------|---------------------|-----------|
| **Engines** | -1D speed/round | Vehicle stalls |
| **Weapons** | -1D fire rate | No attacks |
| **Sensors** | -1D Perception | Blind fighting |
| **Hull** | -1D defense | Breach, decompression |
| **Crew** | Scaled dice penalties | Abandon ship |

## Damage Track (per system)
- **Lightly:** -1D to related rolls
- **Heavily:** -2D, plus environmental hazard (steam vent, electrical surge)
- **Severely:** System offline, requires Difficult (20) repair
- **Catastrophic:** System destroyed, collateral damage (4D to adjacent systems)

## Example: Skyship "HMS Thunderclank"

CAPITAL SHIP OPERATION: 4D (Captain's Command + Perception) INITIATIVE: Coordination + Perception ÷ 2 PRESSURE: 2D (engine stress)

SUBSYSTEMS:

- **Engines:** Maneuverability 4D
    
- **Aetheric Cannon (Forward):** 6D damage, Range 100/200/400
    
- **Steam-Gatling (Port):** 4D+2 damage, Rate 3
    
- **Pneumatic Harpoon (Starboard):** 5D damage, Grapple +2D
    
- **Hull:** 5D soak
    
- **Crew:** 3D command dice (morale)


### Combat Example: Round 1

SITUATION: Thunderclank vs. Pirate Zeppelin (Vehicle scale, 3D)

CAPTAIN: "Hard to port! Full power to forward cannon!"

- **Command Roll:** 4D vs. Moderate (15) → Success, +1D Maneuver
    

PILOT: Evasive maneuvers

- **Maneuver Roll:** 4D + 1D (captain) vs. Enemy Gunnery 5D → Opposed, 18 vs. 16 (Success)
    

GUNNER: Fire Aetheric Cannon!

- **Attack Roll:** 6D vs. Difficulty 20 → Wild Die 6! → 28 (Critical Hit)
    
- **Damage:** 6D vs. Zeppelin Hull 3D → 22 vs. 12 → **Catastrophic breach**
    

ENGINEER: Venting steam from overload

- **Technical vs. 15:** Success, -1D Pressure (2D → 1D)
    

ENEMY: Zeppelin's hull is Catastrophic—crew abandons ship


## Crew Roles
Each role rolls separately, results combined:

### **Captain**
- **Skill:** Command, Leadership
- **Action:** Roll initiative, issue orders, coordinate crew
- **Bonus:** Success gives +1D to one other crew member's roll

### **Pilot**
- **Skill:** Piloting, Maneuver
- **Action:** Evasion, positioning, grapple attempts
- **Bonus:** Success increases defense by +1D

### **Gunner**
- **Skill:** Heavy Weapons, Gunnery
- **Action:** Fire ship weapons, subsystem targeting
- **Bonus:** Success can shift damage to specific subsystem

### **Engineer**
- **Skill:** Technical, Repair
- **Action:** Repair subsystems, manage pressure, vent steam
- **Bonus:** Success repairs 1 level of damage or vents 1D Pressure

### **Secondary Roles (if extra crew)**
- **Navigator:** +1D to Pilot's maneuvers
- **Sensor Officer:** +1D to Gunner's targeting
- **Medic:** Heal crew casualties ( scaled dice penalties)
- **Boarding Party:** Personal combat during boarding actions

## Pressure in Vehicles
Vehicle Pressure is **separate** from combat Pressure but **linked**.

### Gaining Vehicle Pressure
+1D when:
- **Engine damage** (any level)
- **Hull breach** (Heavily+)
- **Outnumbered in ship-to-ship combat** (enemy has 2+ ships)

### Vehicle Pressure Effects
- **1D-2D:** Warning alarms, minor steam leaks (aesthetic)
- **3D-4D:** Systems stressed, +5 Difficulty to all rolls
- **5D:** **Catastrophic Overload**—roll on table:

| d6 | Catastrophic Effect |
|----|---------------------|
| 1 | Boiler explosion (4D damage to all crew, engines Catastrophic) |
| 2 | Reality bleed (ship phases in/out for 1d6 rounds, -2D all rolls) |
| 3 | Aetherium cascade (all reserves burn at once, -10D regional Flux) |
| 4 | Crew mutiny (Morale check vs. 20 or they turn) |
| 5 | Hull implosion (Catastrophic breach, decompression) |
| 6 | **Miracle:** Ship achieves temporary sentience, helps crew (Pressure → 0) |

### Venting Vehicle Pressure
**Engineer action:** Technical vs. 15
- **Success:** -1D Vehicle Pressure
- **Cost:** -1D engine power for this round (ship is slower/weaker)
- **Wild Die 6:** Pressure -2D, no power loss
- **Wild Die 1:** Vent fails, +1D Pressure (feedback surge)

### Pressure Cascade (Vehicle → Crew)
When Vehicle Pressure reaches **5D**, all crew gain **+1D personal Pressure**.

## Boarding Actions

### Grapple
**Pilot vs. Difficult (20):** Attach to enemy ship
- **Success:** Ships locked, boarding possible next round
- **Failure:** Ships drift apart, must re-attempt
- **Wild Die 6:** Instant grapple, no time delay
- **Wild Die 1:** Your hull is damaged in attempt (Lightly)

### Board
**Coordination vs. 15:** Leap/cross to enemy deck
- **Success:** On enemy ship, personal combat begins
- **Failure:** Fall—take 2D damage, must retry
- **Wild Die 6:** Acrobatic landing, +1D to first attack
- **Wild Die 1:** Fall into engine/gap: Catastrophic damage

### On Deck (Personal Combat)
- Use **standard personal combat rules**
- **Environmental Hazards:** (roll d6 each round)
  1. **Moving deck:** Coordination vs. 10 or fall prone
  2. **Steam vent:** 2D damage, Difficult 20 to avoid
  3. **Aetherium leak:** Reality Bleed for 1 round
  4. **Rigging collapse:** Block area, -1D to movement
  5. **Crew panic:** Mob of fleeing sailors (obstacle)
  6. **Clear:** No hazard this round

### Capturing a Ship
**Goal:** Reduce enemy crew Morale to 0  
**Morale:** 3D command dice, -1D per 25% crew lost  
**Surrender:** Morale check vs. 15 when:
- Captain incapacitated
- 50% crew lost
- Engines Catastrophic

## Flux Effects on Vehicles

### Flux 6D+ (Vital)
- **Aetherium weapons:** +1D damage (magic empowers tech)
- **Reality storms:** May target ship (Pilot vs. 20 to evade)
- **Wild Die 6:** Ship systems get bonus effect (engine sings, gun overcharges)

### Flux 0D (Dead)
- **Automaton crew:** +1D Technical (world is logical)
- **Organic crew:** -1D all rolls (soul-thinning)
- **Aetherium devices:** Inoperative (ship becomes dead hulk)
- **Wild Die:** Disabled (combat becomes mechanical)

### Flux 3D-5D (Wyld)
- **Standard operation:** No modifiers
- **Balance:** Ship functions as designed

## Sample Vehicle: Steam-Tank "Iron Claw"

VEHICLE SCALE: +3D CREW: 4 (Captain, Driver, Gunner, Engineer)

SUBSYSTEMS:

- **Engine:** 3D Maneuver (tracked)
    
- **Cannon:** 4D damage, Range 50/100/200
    
- **Hull:** 4D soak
    
- **Crew:** 2D morale
    

PRESSURE: 0D (starts at 0)

SPECIAL:

- **Tracked:** Cannot be grappled, ignores difficult terrain
    
- **Steam Vent:** Engineer can vent for 2D area damage (Pressure +1)


## Vehicle Creation Rules
**Invention system applies** (see rules/invention-system.md)

**Complexity:** Vehicle = 3 (Machine) to 5 (Miracle)  
**Design:** Technical vs. 25  
**Build:** 1 month to 1 year  
**Test:** Pilot vs. 20  

**Crew Requirements:** 1 per subsystem minimum

## Chases & Pursuit
**Opposed Piloting rolls** each round:  
- **Winner:** Can attack, escape, or close distance
- **Loser:** Can only defend, cannot attack
- **Margin of Success:** Every 5 points = +1D to next round

**Escaping:** Must win 3 consecutive rounds  
**Catching:** Must win 2 consecutive rounds, then Grapple

## Vehicle vs. Personal
**Vehicle attacks person:** +3D to damage (scale difference)  
**Person attacks vehicle:** -3D to damage, must target subsystem

**Exception:** Tezcatlipoca's Breath ignores scale vs. Aetherium engines
