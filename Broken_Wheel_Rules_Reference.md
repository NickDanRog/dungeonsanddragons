# BROKEN WHEEL — RULES REFERENCE

> **Note on "CR" abbreviation:** In these rules, "Command Rating" is always written in full to avoid collision with "Challenge Rating" (also CR) in standard Pathfinder usage. A distinct shorthand may be adopted before finalization.

---

## I. Time Scale

**Round (Tactical)**
One Round represents one week of field operations: army maneuver, combat engagements, objective capture, and unit-level actions. Four Rounds occur within each Turn.

**Turn (Strategic)**
One Turn represents one month of strategic play. At the start of each Turn, players issue strategic orders for the coming month. At the end of each Turn, strategic resolution occurs: Resource Point (RP) consumption, scouting and intelligence rolls, Regional Loyalty shifts, and other strategic actions. The GM resolves enemy strategic decisions during the same period.

---

## II. Units

### What Is a Unit?

A Unit is a single military formation of approximately 64 soldiers. All Units use **Medium army size** as the standard. A Unit's Army Challenge Rating (ACR) equals the Challenge Rating of its individual soldiers with no size modifier applied.

### Unit Statistics

| Statistic | Value |
|---|---|
| **ACR** | CR of individual soldiers (no size modifier) |
| **Hit Points (HP)** | ACR × average HD value (d6: ×3.5 / d8: ×4.5 / d10: ×5.5 / d12: ×6.5) |
| **Defense Value (DV)** | ACR + 10 (plus resource and ability bonuses) |
| **Offense Modifier (OM)** | ACR (plus resource and ability bonuses) |
| **Morale** | Starts at 0; range –4 to +4 |
| **Consumption** | Defined per unit type; see Part XXI |

### Morale

Morale modifies Loyalty checks and tactic availability. A Unit whose Morale falls to –5 or below disbands. Morale improves through victory (see Rout and Victory below) and degrades through missed Consumption payments and rout.

### Tactics

Units learn new tactics through battlefield victory. A Unit may know a maximum number of **earned** tactics equal to ACR ÷ 2 (minimum 0). Named unit entries (see Part XXI) may list **starting tactics** that are innate to that unit type; starting tactics do not count against the earned-tactic maximum. A unit's total tactics at any time = starting tactics + earned tactics. Available tactics:

| Tactic | Effect |
|---|---|
| Cautious Combat | –1 OM, –1 DV; no Morale penalty for Withdraw |
| Cavalry Experts | +2 OM vs. non-mounted Units; requires mounts |
| Defensive Wall | –2 OM, +2 DV |
| Dirty Fighters | +2 OM for two phases after first hit |
| Expert Flankers | +2 OM, –2 DV |
| False Retreat | Withdraw triggers free counterattack next phase |
| Full Defense | No attack; +4 DV |
| Relentless Brutality | +4 OM, –4 DV |
| Siegebreaker | +4 OM vs. Units using fortification bonuses |
| Sniper Support | +2 OM ranged; requires ranged weapons |
| Spellbreaker | +2 DV vs. spellcasting Units |
| Taunt | –2 enemy Morale on failed DC 15 Will check |
| Withdraw | Disengage without triggering free attack |

*New tactics are learned through the Victory procedure (see Part VIII).*

### Unit Resources

Resources are purchased with RP at Unit creation or during Turn Resolution. Each resource increases the Unit's Consumption as noted.

| Resource | Purchase Cost | Consumption Increase | Effect |
|---|---|---|---|
| Healing Potions | 10 RP | +1 RP/Turn | Heal 2× ACR HP once per battle (max twice per battle) |
| Improved Armor | 3 RP | +1 RP/Turn | +1 DV |
| Magic Armor | 15 RP | +2 RP/Turn | +2 DV |
| Improved Weapons | 5 RP | +1 RP/Turn | +1 OM |
| Magic Weapons | 50 RP | +3 RP/Turn | +2 OM |
| Light Warhorse Mounts | 1 RP | +1 RP/Turn | +1 OM and DV |
| Heavy Warhorse Mounts | 2 RP | +2 RP/Turn | +2 OM and DV |
| Throwing Weapons | 2 RP | +1 RP/Turn | Grants Ranged(2) attack capability |
| Bows | 2 RP | +1 RP/Turn | Grants Ranged(3) attack capability |

*Full RP costs and acquisition procedures are defined in Part VII when the economic system is finalized.*

### Special Abilities

When the majority of a Unit's soldiers possess a special ability, the Unit gains the corresponding mass combat modifier. Common modifiers:

**Offensive:** Breath Weapon (+1d4 damage per phase), Bleed (1d6 automatic damage next phase), Poison (–1 OM/DV on failed save), Sneak Attack (+1 OM when ambushing or flanking).

**Defensive:** Damage Reduction (reduce per-phase damage by DR value), Fast Healing (recover fast healing value in HP per phase), Regeneration (recover half regeneration value per phase), Undead (+2 DV; immune to fear, morale penalties, and paralysis).

**Mobility:** Flight (immune to melee attacks except from other flying Units), Darkvision (no darkness penalties), Invisibility (–2 OM against Unit; –2 DV to attacks against Unit).

**Spellcasting:** +OM and +DV each equal to the highest spell level the Unit can cast.

*Additional class-based abilities (Paladin aura, Barbarian rage, etc.) apply per the Pathfinder mass combat SRD when the Unit composition warrants.*

---

## III. Armies

### What Is an Army?

An Army is a formation of one or more Units operating under a single NPC Commander. On the strategic map, an Army moves and acts as a single entity. On the tactical map, the individual Units within an Army are deployed and maneuvered separately.

### Command Rating

Each NPC Commander has a **Command Rating** representing the maximum number of Units they can lead as a cohesive formation:

> **Command Rating = 5 + Commander's Charisma modifier**

Units beyond a Commander's Command Rating cannot benefit from that Commander's tactics, Strategy Track selections, or boons, and do not receive Morale bonuses.

*Example: A Commander with Charisma 16 (+3) has a Command Rating of 8 and may lead up to 8 Units.*

### Commander Statistics and Bonuses

NPC Commanders provide the following to their Units:

- **Morale bonus:** Charisma modifier + Profession (soldier) ranks ÷ 5 + Leadership score bonus
- **Boons:** Maximum = 1 + Profession (soldier) ranks ÷ 5
- **Active requirement:** A Commander must spend at least 3 days per week actively engaged with their Army. An inactive Commander provides no Morale bonus, tactics, or boons.

**Commander Boons** (select from):

| Boon | Effect |
|---|---|
| Bloodied but Unbroken | Auto-succeed one rout check per battle |
| Bonus Tactic | Army gains one additional tactic slot |
| Defensive Tactics | +1 DV to all Units when using Defensive strategy |
| Flexible Tactics | Commander may change tactic mid-battle once |
| Hit and Run | Withdraw does not cost a phase |
| Hold the Line | Units immune to Taunt and fear effects |
| Live off the Land | Reduce Consumption by 1 RP/Turn (minimum 1) |
| Loyalty | +2 to all Loyalty checks |
| Merciless | +2 OM against routing enemies |
| Sharpshooter | Ranged Units gain +2 OM during Ranged Phase |
| Triage | Once per Turn, restore ACR HP to one Unit outside of battle |

### PC Strategic Role

Player characters operate at the **strategic layer**. They do not serve as Army Commanders and do not roll for individual Units during combat. Their role includes:

- Issuing strategic orders at the start of each Turn
- Recruiting, assigning, and directing NPC Commanders
- Making strategic-level rolls (intelligence, scouting, negotiation, regional actions)
- Resolving Turn-level decisions (alliances, regional objectives, resource allocation, The Cause)

During tactical Rounds, players may choose to take direct control of their Units on the tactical map (dividing responsibility among the table), or may delegate all engagement resolution to the aggregate mechanic (Part V).

---

## IV. Tactical Combat

### When Tactical Combat Occurs

When opposing Units enter engagement range during a Round, tactical combat begins. Play moves to a tactical map. Both sides maneuver their Units individually. Units may freely engage, disengage (with appropriate tactics), support allies, or hold position.

### Combat Phases

Each engagement between two Units follows this sequence:

**1. Tactics Phase**
The controlling player or Commander selects an active tactic (if any) and a Strategy Track position for each Unit.

**Strategy Track:**

| Strategy | DV Modifier | OM Modifier | Damage Modifier |
|---|---|---|---|
| Defensive | +4 | –4 | –6 |
| Cautious | +2 | –2 | –3 |
| Standard | — | — | — |
| Aggressive | –2 | +2 | +3 |
| Reckless | –4 | +4 | +6 |

**2. Ranged Phase**
Units with ranged capability make one ranged attack against any valid target within range. Roll 1d20 + OM vs. target DV. On a hit, damage = result – DV (minimum 0). See Ranged Weapons below for range rules.

**3. Melee Phase**
Engaged Units make melee attacks simultaneously. Roll 1d20 + OM vs. target DV. On a hit, damage = result – DV (minimum 0). Melee phases repeat until one side routs, is destroyed, or withdraws.

### Ranged Weapons

**Ranged Notation:** A Unit equipped with ranged weapons lists its engagement range as `Ranged(n)` alongside its OM, where n is the maximum number of squares from which the Unit may make ranged attacks. This notation applies to tactical combat only; aggregate combat does not distinguish ranged from melee capability.

*Example stat block entry: OM: 5, Ranged(4)*

**Range by Weapon Class:**

| Weapon Class | Ranged Value |
|---|---|
| Thrown weapons (javelin, sling) | Ranged(2) |
| Crossbow / shortbow | Ranged(3) |
| Longbow / composite bow | Ranged(4) |
| Siege engine | Ranged(6) |

*Specific values for each Unit type are set in the Unit entries. This table provides the baseline scale.*

**Melee Engagement:** A Unit with Ranged(n) loses its ranged capability when engaged in melee (an enemy Unit is adjacent, within 1 square). The Unit fights at its standard OM. Some Unit types specifically trained for ranged combat may also suffer an OM penalty in melee; this is noted in the individual Unit entry.

**Firing into Melee:** A ranged Unit may target an enemy Unit that is currently engaged in melee with friendly Units. On a hit, the targeted Unit takes full damage. Each other Unit adjacent to the target that is currently engaged in that melee takes half damage (rounded down).

### Tactical Options

**Ganging Up:** Multiple Units may attack a single target in the same phase. Each Unit rolls separately. This is the primary expression of numerical advantage in tactical play.

**Supporting:** A Unit may forgo its attack to support an adjacent friendly Unit, granting that Unit +2 OM on its next attack roll.

**Withdraw:** A Unit may disengage from melee. Without the Withdraw or Cautious Combat tactics, withdrawing triggers one free attack from each engaged enemy Unit.

### Battlefield Conditions

| Condition | Effect |
|---|---|
| Advantageous Terrain | Defender +2 DV |
| Ambush | Attacker makes Offense check; on success, defender skips Tactics Phase |
| Darkness | All Units –2 OM and –3 DV (negated by Darkvision) |
| Dim Light | All Units –1 OM |
| Fog | All damage halved; +2 Morale bonus on Withdraw checks |
| Fortifications | Add settlement Defense rating to DV |
| Rain/Snow | Ranged attacks affected per wind rules |

---

## V. Aggregate Combat

### When It Is Used

Aggregate combat resolves an engagement without tactical map play. It is used when:
- Players choose to resolve a Round's engagements off-screen
- The GM resolves enemy-vs-enemy or unattended engagements
- The table delegates resolution to the GM for speed

### Aggregate Statistics

Calculate the following for each side before rolling:

| Statistic | Calculation |
|---|---|
| Aggregate OM | Average OM of all participating Units |
| Aggregate DV | Average DV of all participating Units |
| Aggregate HP | Sum of all participating Units' current HP |
| Numerical Advantage | +1 OM per 2 additional Units above the smaller force (round down) |

*Example: 5 Units (avg OM 6) vs. 3 Units (avg OM 6). The larger force has +1 aggregate OM from numerical advantage.*

### Aggregate Resolution

1. Both sides' Commanders select a Strategy Track position (default: Standard if no Commander is present). Apply modifiers to Aggregate OM, DV, and damage.
2. Roll 1d20 + Aggregate OM vs. enemy Aggregate DV. On a hit, damage = result – DV (minimum 0). Both sides roll simultaneously.
3. Apply damage to each side's Aggregate HP.
4. Resolve Ranged Phase first (if applicable), then repeat Melee Phase up to three times, or until one side's Aggregate HP triggers a rout check.
5. When Aggregate HP falls to the sum of all Units' ACR values or below, the Commander makes a DC 15 Morale check (using the army's average Morale). On failure, all Units rout.

### Damage Distribution

After aggregate resolution, divide total HP damage taken by the number of Units in the formation (round down). Apply that amount to each Unit. If a Unit is reduced to 0 HP through distribution, it is destroyed; remaining damage does not carry over.

---

## VI. The Strategic Turn

### Turn Structure

Each Turn (one month) resolves in the following order:

**Step 1 — Orders Phase**
Players issue strategic orders: army movements, objectives for the coming month, recruitment, resource allocation, and any other strategic decisions. The GM sets enemy orders for the same period simultaneously.

**Step 2 — Tactical Rounds (×4)**
Four Rounds of field operations resolve in sequence. Each Round:
- Armies execute movement orders on the strategic map
- Engagements are resolved (tactical or aggregate)
- Objectives are contested or captured
- Unit-level events occur (ambushes, sieges, forced marches, etc.)

**Step 3 — Turn Resolution**
At the end of the fourth Round:
- RP consumption is calculated and paid (see Part VII)
- Morale penalties apply for any missed Consumption
- Intelligence and scouting rolls resolve
- Regional Loyalty shifts apply (see Part IX)
- Strategic actions resolve (negotiations, alliances, supply disruption, propaganda, etc.)
- The GM performs the same resolution for enemy forces

### Enemy Strategic Play

Enemy forces operate under the same rules as the party. Enemy Commanders lead Armies, make strategic decisions, consume RP, and respond to player actions with their own objectives. The enemy is an active opponent working to suppress the revolution — not a passive reactive force. The GM should establish enemy strategic goals at the campaign level and pursue them accordingly.

---

## VII. Resource Points (RP)

*RP is the campaign's economic currency. Income is generated through Taxes and Tribute collected from Settlements (see Parts XVII and XVIII of the Economic System below). This section defines Unit-level consumption only.*

### Unit Consumption

Each Unit pays Consumption at Turn Resolution (end of each Turn, monthly). Each unit type's Consumption is a designed upkeep cost listed in its entry in Part XXI. Resource upgrades increase Consumption as listed in the Unit Resources table (Part II). A Commander with the Live off the Land boon reduces the Army's total Consumption by 1 RP per Turn.

**Missed Consumption:** If a Unit cannot pay its full Consumption for a Turn, its Morale decreases by 2. If Morale falls to –5, the Unit disbands.

---

## VIII. Rout, Victory, Defeat, and Recovery

### Rout

When a Unit's HP falls to its ACR value or below:
- Its Commander makes a DC 15 Morale check
- **Success:** Unit fights on at reduced strength
- **Failure:** Unit routs — it retreats from the field, Morale –1, HP restored to ACR value, all engaged enemy Units make one free attack before it exits

A routed Unit requires a successful Loyalty check to return to active service. Until that check succeeds, it cannot be assigned to engagements.

### Victory

When a Unit wins an engagement, its Commander makes a Loyalty check vs. the army's Control DC. On success:
- Unit gains one new tactic (if below its maximum)
- Morale +1 (maximum +4)
- Commander makes a second Loyalty check; on success, gains one new boon (if below maximum)

### Defeat

A Unit reduced to 0 HP is destroyed. The GM determines narrative consequences: prisoners taken, equipment lost or captured, survivors folding into other Units, etc.

### Recovery

| Condition | Recovery Rate |
|---|---|
| At rest (not in combat) | ACR HP per day |
| At rest + successful Loyalty check | Additional ACR HP per day (once per day) |
| Full rest, no action | Fully recovers in approximately one month |

---

## IX. Reserved: Regional Loyalty

*Mechanic definition pending — see Broken Wheel Design Document (Key Mechanics).*

---

## X. Reserved: Immortal Escalation

*Mechanic definition pending — see Broken Wheel Design Document (Key Mechanics).*

---

## XI. Reserved: The Cause Tracker

*Mechanic definition pending — see Broken Wheel Design Document (The Cause).*

---

## XII. Reserved: Cause Divergence Tracker

*Mechanic definition pending — see Broken Wheel Design Document (The Cause).*

---

# ECONOMIC SYSTEM

---

## XIII. Geographic Hierarchy

The campaign map is organized into three tiers: Regions, Provinces, and Settlements.

**Regions**
The seven Regions correspond to the campaign's seven Parts. Each Region is a distinct political and geographic area of the continent. With the exception of Region I (Grand Duchy of Severan), each Region is subdivided into Provinces.

**Provinces**
A Province is a sub-region within a Region. Each Province has an alignment representing the cultural and political character of its population. This alignment establishes the base Loyalty of that Province's Settlements toward each faction (see Part XVIII: Loyalty). A Province's alignment is also the default alignment for all Settlements within it unless a Settlement's entry specifies otherwise.

**Settlements**
Settlements represent towns and cities within Provinces (or directly within Region I). They are the primary economic and military nodes of the campaign. Capturing and controlling Settlements generates Resource Points through Taxes and Tribute, and enables Unit recruitment.

Region I (Severan) contains Settlements directly without Province subdivision.

---

## XIV. Settlement Statistics

Each Settlement has six statistics:

| Statistic | Description |
|---|---|
| Population | Size rating; determines settlement type |
| Economy | Output rating; basis for tax and tribute income |
| Settlement Type | Economic and cultural character; determines available unit recruitment |
| Loyalty | Disposition (1–10) to each faction individually |
| Unrest | Active resistance level (1–10) |
| Defensive Rating (DEF) | Fortification strength; enables siege defense |

### Population

| Rating | Settlement Type |
|---|---|
| 1–2 | Small Town |
| 3–4 | Large Town |
| 5–6 | Small City |
| 7–9 | Large City |
| 10+ | Huge City |

### Economy

The Economy rating represents the productive output of the settlement and its surrounding area. It is the basis for all Tax and Tribute calculations. A settlement's Economy rating cannot exceed **150% of its Population rating (rounded down)**.

*Example: Population 6 → maximum Economy rating of 9.*

Economy is set at campaign creation. Strategic actions and settlement events can modify it during play.

### Settlement Type

Each Settlement has one or more types reflecting its economic character and cultural role. Settlement Type determines which Unit categories are available for recruitment there (see Part XXII: Strategic Actions — Recruitment). Specific unit lists per type are defined in the Unit Types section.

A Settlement may have more than one type where its role warrants it (e.g., a fortified port city might be both Military and Trade).

| Type | Description |
|---|---|
| Administrative | Seat of regional or provincial governance; bureaucratic and political center. Used for enemy regional headquarters and key political objectives. |
| Agricultural | Settlement focused on farming, ranching, or other food production; typically rural in character. |
| Cultural | Home to significant cultural institutions, traditions, or landmarks meaningful to the local population. |
| Educational | Home to major academies, universities, or centers of learning. |
| Industrial | Focused on the production of manufactured goods, including mining and raw material processing. |
| Military | Muster point, garrison fort, or dedicated training center. |
| Religious | Home to important temples, holy sites, or the administrative center of a religious institution. |
| Trade | Commerce-oriented settlement; includes port cities, market towns, and crossroads hubs. |

### Loyalty

Each Settlement maintains a separate Loyalty rating (1–10) for every active faction. See Part XVIII for the full Loyalty system.

### Unrest

Unrest is a single rating (1–10) representing the settlement's resistance to the authority of whichever faction currently controls it. See Part XIX for the full Unrest system.

### Defensive Rating (DEF)

DEF represents the strength of a settlement's fortifications. A Settlement with DEF 1 or higher may sustain a siege rather than face an attacking force in open battle. See Part XX for siege rules.

---

## XV. Control Checks

Many economic and administrative actions require a **Control Check** — a dice roll to determine whether a faction successfully exerts authority over a settlement or region.

### Who Rolls

Control Checks are made by the **faction's regional leader**: the PC or NPC designated as responsible for a given Region. For enemy forces, this is the overall enemy regional commander (established per Region). For the party, this is whichever PC or NPC they delegate to that responsibility.

One regional leader handles all Control Checks for all Provinces and Settlements within their Region.

**Exception — Capture and Siege:** When capturing a settlement (Part XVI) or defending during a siege (Part XX), the Control Check is made by the **Army Commander** of the force directly involved, not the regional leader.

### Roll Formula

> **Control Check = 1d20 + Charisma modifier + (Leadership score ÷ 2, rounded down)**

If the regional leader has no Leadership score, use Charisma modifier only.

### DC

The DC for each Control Check is specified in the relevant rule. A result that meets or exceeds the DC is a success.

---

## XVI. Capturing Settlements

### Moving to Capture

To capture a Settlement, a Unit or Army must enter the Settlement's square on the strategic map during a Round.

### Opposing Forces

If an enemy Army occupies the Settlement, it must choose to fight or withdraw. If it fights, resolve the engagement using tactical or aggregate combat rules. If it withdraws successfully, the Settlement may be captured without combat.

### Disposition

After opposing forces are eliminated, routed, or withdrawn, the capturing faction immediately chooses one of four dispositions:

#### Liberate

The Settlement is returned to local control. The faction does not govern it directly and cannot tax it.

The faction may:
- Request Tribute from the Settlement each Turn (see Part XVII)
- Request military aid in the form of Units (see Part XXII: Recruitment)

Liberation has the following immediate effects on the Settlement:
- Unrest –3
- Loyalty to the liberating faction +2
- Loyalty to all other factions –2

#### Occupy

The faction annexes the Settlement. It may collect Taxes and recruit Units from it each Turn.

The capturing Army's Commander makes a **Control Check**: DC = 20 – (settlement's current Loyalty to the occupying faction).

- **Success:** The Settlement is occupied without penalty.
- **Failure:** The Settlement is occupied, but Unrest increases by the amount the check failed (DC – result).

#### Sack

The faction occupies the Settlement while extracting a significant portion of its wealth. Apply all Occupy rules with the following additions:

- Add **+10** to the Occupy Control Check DC.
- The faction immediately gains RP equal to **3 × current Economy rating**.
- Reduce the Settlement's Economy rating by **1/4 of its current value (rounded down, minimum 1)**.

#### Raze

The faction systematically destroys the Settlement.

- The faction immediately gains RP equal to **5 × current Economy rating**.
- All Settlement ratings (Population, Economy, Loyalty, Unrest, DEF) are reduced to zero.

A razed Settlement is removed from play and cannot be recaptured, taxed, or used as a base.

---

## XVII. Tribute and Taxes

### Tribute

Tribute is an economic request made to a **Liberated** Settlement. It is not automatic — the faction must declare the request during the Orders Phase of each Turn.

**Maximum:** Up to **1/3 of the Settlement's current Economy rating** (rounded down, minimum 1 RP).

**Control Check DC:** (20 – current Loyalty to the requesting faction) + (2 × consecutive Turns tribute has been requested or collected).

The consecutive-Turn modifier resets to 0 whenever tribute is **not** requested in a Turn.

- **Success:** Collect the requested Tribute. The Settlement's Loyalty to the requesting faction decreases by 1.
- **Failure:** No Tribute collected. No additional effects.

### Taxes

Taxes are collected from **Occupied** Settlements during Turn Resolution. Collection is automatic unless the faction adjusts the rate.

**Base Tax Rate:** 1/4 of the Settlement's current Economy rating (rounded down, minimum 1 RP).

**Adjusting the Tax Rate**
The faction may set the rate above or below base. For every RP collected **above** the base rate: Loyalty –1, Unrest +1.

**Overtaxation**
If total taxes exceed **1/2 of the Settlement's current Economy rating**, the faction must make a **Control Check**: DC = 20, +2 per RP in excess of the 1/2 threshold.

- **Failure:** No tax is collected this Turn. Apply an additional Loyalty –2 and Unrest +2 (these stack with adjustments from the above-base rate penalties).

**Tax Restrictions**
Taxes cannot be collected if either condition is met:
- Settlement's Loyalty to the controlling faction is **3 or lower**
- Settlement's Unrest rating is **7 or higher**

---

## XVIII. Loyalty

Every Settlement maintains a separate **Loyalty** rating (1–10) for each faction active in the campaign. Loyalty measures how favorably the Settlement's population regards a faction — regardless of who controls the Settlement.

### Base Loyalty

A Settlement's starting Loyalty to each faction is calculated at campaign creation:

> **Base Loyalty = 5 + (alignment match bonuses) – (alignment conflict penalties)**

Pathfinder alignment has two axes: **moral** (Good / Neutral / Evil) and **ethical** (Lawful / Neutral / Chaotic).

- **0 steps apart** (same value on an axis): **+1**
- **1 step apart**: **–1**
- **2 steps apart** (opposite ends of an axis): **–2**

Apply this calculation separately to each axis, then sum.

*Example: Settlement alignment LN, Faction alignment CN. Moral axis: both Neutral → +1. Ethical axis: Lawful vs. Chaotic → 2 steps → –2. Base Loyalty = 5 + 1 – 2 = **4**.*

### Loyalty Ratings

| Rating | Label |
|---|---|
| 1–2 | Disloyal |
| 3–4 | Questionable |
| 5 | Neutral |
| 6–7 | Loyal |
| 8–9 | Dedicated |
| 10 | Fanatical |

### Loyalty Modifiers

**Victories and Losses**
When a faction wins a combat engagement in a Province: +1 to that faction's Loyalty in every Settlement in the Province; –1 to the opposing faction's Loyalty in every Settlement in the Province.

**Sacking**
When a faction sacks a Settlement: –5 Loyalty to the attacking faction in that Settlement; –1 Loyalty to the attacking faction in all other Settlements in the same Province.

**Razing**
When a faction razes a Settlement: –3 Loyalty to the attacking faction in all remaining Settlements in the Province.

**Strategic Actions**
Turn-level strategic actions can increase or decrease Settlement Loyalty. (See [Reserved: Strategic Actions].)

### Low Loyalty Consequence

Whenever a Settlement's Loyalty to its controlling faction falls to **3 or lower**, the regional leader makes a **Control Check**:

> DC = 10 + current Unrest – current Loyalty (to controlling faction)

- **Success:** No effect.
- **Failure:** Unrest increases by the amount the check failed. Loyalty to the controlling faction decreases by 1.

---

## XIX. Unrest

Each Settlement has a single **Unrest** rating (1–10) representing active resistance to authority. Unrest affects the controlling faction regardless of which faction holds the Settlement.

### Unrest Ratings

| Rating | Label | Description |
|---|---|---|
| 1–2 | Content | Little to no unrest |
| 3–4 | Complacent | Grumblings; no active or organized resistance |
| 5–6 | Unruly | Active but disorganized unrest |
| 7–8 | General Uprising | Hostile population with organized resistance |
| 9–10 | Total Revolt | Settlement in active revolt |

### Unrest Modifiers

**Failed Control Rolls**
As specified under Capturing Settlements (Part XVI) and Low Loyalty Consequence (Part XVIII).

**Victories and Losses**
When a faction wins a combat engagement in a Province: –1 Unrest in each Settlement controlled by that faction in the Province; +1 Unrest in each Settlement controlled by the losing faction in the Province.

**Occupying Forces**
Units stationed inside a Settlement reduce its effective Unrest for the duration of that Turn. A Unit must remain in the Settlement for the full Turn to provide this benefit. Track effective Unrest as a hybrid rating: *base(effective)*.

*Example: Unrest 5, one Unit stationed → displayed as 5(4).*

The number of Units required per point of Unrest reduction scales with base severity:

| Base Unrest | Units Required per –1 Unrest |
|---|---|
| 1–6 | 1 Unit |
| 7–8 | 2 Units |
| 9–10 | 3 Units |

**Strategic Actions**
Turn-level strategic actions can modify Settlement Unrest. (See [Reserved: Strategic Actions].)

### Unrest Effects

**HP Recovery**
Units stationed in a Settlement with Unrest **7 or higher** do not recover HP at the normal rate.

**Unrest 7+ Control Check**
At Turn Resolution, whenever a Settlement's Unrest is 7 or higher, the regional leader makes a **Control Check**:

> DC = 20 + current Unrest – current Loyalty (to controlling faction)

- **Success:** No effect.
- **Failure:** Each Unit stationed in the Settlement takes HP damage equal to the Settlement's current Unrest rating.

**Unrest 9+ Escalation**
When Unrest is 9 or higher, apply the Unrest 7+ Control Check with **+10 added to the DC**. On a result that **fails by 10 or more**, the following occurs in addition to the standard failure effects:

1. **Rebel Army Spawns.** Create an Army with total RP value equal to: *current Unrest + (Economy ÷ 2, rounded down, minimum 1)*. This Army immediately engages all Units occupying the Settlement using tactical or aggregate combat rules.

2. **If the Rebel Army wins:** Reduce the Settlement's Loyalty to the occupying faction by 4.

3. **Defection.** If the Settlement's Loyalty to any opposing faction is 5 or higher when the Rebel Army wins, the Settlement defects: it becomes a Liberated Settlement under that faction, and the Rebel Army comes under that faction's command.

---

## XX. Defensive Rating and Sieges

### Defensive Rating

A Settlement's **Defensive Rating (DEF)** represents the strength of its fortifications. A Settlement with DEF 1 or higher may sustain a siege rather than face an attacking force in open battle when a capturing force enters its square.

### Siege Resolution

Sieges resolve over one or more Turns. At the end of each Turn under siege:

**DEF Attrition**
The Settlement's DEF decreases by 1 (supply pressure, deterioration, and sustained operations).

**Defender Supply Check**
The defending Army's Commander makes a **Control Check**:

> DC = 25 – current Economy rating of the Settlement

- **Success:** No effect.
- **Failure:** Each defending Unit takes HP damage equal to the amount the check failed (DC – result).

**Unit HP Recovery**
Units under siege recover HP at **half the normal rate**.

### Siege Actions

Each Turn of a siege, both sides may take the following actions. Actions are declared during the Orders Phase and resolved during Turn Resolution.

**Attacker Actions**

| Action | Requirement | Resolution |
|---|---|---|
| Bombardment | Siege engine Unit(s) | Each siege engine Unit reduces Settlement DEF by 1d4 per combat phase (aggregate roll per Part V) |
| Assault | — | Aggregate roll; add current DEF to the DV of all defending Units |
| Wait | — | No active action; DEF attrition and supply check still apply |

**Defender Actions**

| Action | Requirement | Resolution |
|---|---|---|
| Counter-Battery | Siege engine Unit(s) | Aggregate roll using only the opposing siege engine Units' statistics; damage applied to attacker siege Units |
| Defensive Fire | Siege engine Unit(s) | Aggregate roll using defending siege Units vs. attacking force's aggregate DV |
| Sortie | — | Standard engagement using tactical or aggregate rules; if defeated, surviving Units return to the Settlement |

---

## XXI. Unit Types

> *Terminology note: "Unit" in these rules corresponds to "Army" in the Pathfinder SRD. "Army" in these rules refers to a group of Units under a Commander (see Part III). Cross-reference the SRD accordingly.*

---

### Special Abilities

The following special abilities appear on unit entries. Additional abilities may be defined as specific unit types require.

**Fly** — On the tactical map, this unit moves over all terrain without penalty. Only flying units or units with Ranged capability can engage it while airborne. It may choose to land and fight as a ground unit.

**Raiding** — This unit is trained for rapid strikes and plunder. It may participate in Raid Settlement and Objective Raid strategic actions (see Part XXII).

**Scouting** — This unit is trained for reconnaissance. It may be assigned to the Scouting strategic action (see Part XXII). While performing a Scouting action, the unit detaches from any Army it belongs to and is unavailable for engagements during that Turn.

---

### Unit Entry Format

Each unit entry uses the following format. Stats reflect the unit's baseline configuration; purchased resource upgrades modify DV, OM, and Speed as noted in each resource entry.

| Stat | Description |
|---|---|
| **Type** | Creature type of the unit's soldiers |
| **ACR** | Army Challenge Rating — CR of individual soldiers (no size modifier) |
| **Speed** | Tactical squares / strategic squares per Round |
| **HP** | ACR × average HD value |
| **DV** | ACR + 10 (plus resource bonuses) |
| **OM** | ACR (plus resource bonuses); Ranged(n) noted where applicable |
| **Morale** | Starts at 0; range –4 to +4 |
| **Consumption** | RP cost per Turn |
| **Resources** | Equipment built into the unit at baseline |
| **Tactics** | Starting tactics (if any) and maximum tactics (ACR ÷ 2) |

---

### Unit Entries

---

#### Infantry
*A formation of roughly 100 soldiers armed with a variety of hand weapons and outfitted with medium armor. The backbone of any conventional fighting force.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 1 |
| **ACR** | 1 |
| **Speed** | 1/5 |
| **HP** | 5 |
| **DV** | 12 |
| **OM** | +1 |
| **Morale** | +0 |
| **Consumption** | 2 RP/Turn |
| **Resources** | — |
| **Tactics** | None (max 0 earned) |

**Special Abilities:** None
**Recruitment:** 5 RP — Administrative, Military, Trade, Industrial

---

#### Slingers
*Light troops armed with slings. The cheapest ranged option available, capable of supporting formations even while on the move.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 1 |
| **ACR** | 1 |
| **Speed** | 1/5 |
| **HP** | 5 |
| **DV** | 11 |
| **OM** | +1; Ranged(2) |
| **Morale** | +0 |
| **Consumption** | 1 RP/Turn |
| **Resources** | — |
| **Tactics** | None (max 0 earned) |

**Special Abilities:**
- **Mobile Fire** — This unit may use its Ranged attack in the same phase it moves.

**Recruitment:** 2 RP — Any

---

#### Spearmen
*A formation of soldiers armed with spears, shields, and light armor. Trained to hold ground and break cavalry charges.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 1 |
| **ACR** | 1 |
| **Speed** | 1/4 |
| **HP** | 5 |
| **DV** | 11 |
| **OM** | +1 |
| **Morale** | +0 |
| **Consumption** | 2 RP/Turn |
| **Resources** | — |
| **Tactics** | Defensive Wall (starting — innate); max 0 earned |

**Special Abilities:**
- **Spear Formation** — This unit gains +2 OM against mounted units.

**Recruitment:** 5 RP — Administrative, Military, Trade, Industrial

---

#### Militia
*A formation of citizen soldiers, armed with a mix of weaponry and light armor. Less effective in the open field, but formidable when defending their own settlements.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 1 |
| **ACR** | 1 |
| **Speed** | 1/4 |
| **HP** | 5 |
| **DV** | 10 |
| **OM** | +0 |
| **Morale** | +0 |
| **Consumption** | 1 RP/Turn |
| **Resources** | — |
| **Tactics** | None (max 0 earned) |

**Special Abilities:**
- **Home Ground** — While within 5 squares of a friendly settlement, this unit gains +3 DV and +1 Morale. When this unit begins and ends a strategic Turn garrisoned within a friendly settlement, its Consumption for that Turn is 0.

**Recruitment:** 2 RP — Any

---

#### Arbalestiers
*Soldiers armed with heavy crossbows. Their bolts hit harder than a shortbow at equivalent range, but the time required to reload limits how often they can fire.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 1 |
| **ACR** | 1 |
| **Speed** | 1/5 |
| **HP** | 5 |
| **DV** | 12 |
| **OM** | +2; Ranged(3) |
| **Morale** | +0 |
| **Consumption** | 2 RP/Turn |
| **Resources** | — |
| **Tactics** | None (max 0 earned) |

**Special Abilities:**
- **Slow Reload** — After making a Ranged attack, this unit may not make another Ranged attack during the following phase. It may make normal melee attacks in any phase.

**Recruitment:** 3 RP — Administrative, Military, Trade, Industrial

---

#### Monks
*Disciplined martial artists who fight with fist and foot, trained in monastic orders. Individually devastating and difficult to disrupt, though still fragile at low experience.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Monk 1 |
| **ACR** | 1 |
| **Speed** | 1/5 |
| **HP** | 4 |
| **DV** | 12 |
| **OM** | +2 |
| **Morale** | +0 |
| **Consumption** | 2 RP/Turn |
| **Resources** | — |
| **Tactics** | Cautious Combat (starting — innate); max 0 earned |

**Special Abilities:**
- **Flurry of Blows (1/engagement)** — This unit gains +1 OM for one phase.
- **Stunning Strike (1/engagement)** — On a successful attack, the target unit takes –2 OM for the following phase.

**Recruitment:** 4 RP — Religious, Educational

---

#### Archers
*A unit of soldiers trained with shortbow or longbow, providing basic ranged support to formations that need it.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 1 |
| **ACR** | 1 |
| **Speed** | 1/5 |
| **HP** | 5 |
| **DV** | 11 |
| **OM** | +1; Ranged(3) |
| **Morale** | +0 |
| **Consumption** | 2 RP/Turn |
| **Resources** | — |
| **Tactics** | Sniper Support (starting — innate); max 0 earned |

**Special Abilities:** None
**Recruitment:** 3 RP — Administrative, Military, Trade, Industrial

---

#### Skirmishers
*Javelin-armed light troops trained to harry the enemy line before engagement. They strike at the edges of battle and melt away before their targets can respond.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 1 |
| **ACR** | 1 |
| **Speed** | 2/10 |
| **HP** | 5 |
| **DV** | 11 |
| **OM** | +1; Ranged(2) |
| **Morale** | +0 |
| **Consumption** | 2 RP/Turn |
| **Resources** | — |
| **Tactics** | Withdraw (starting — innate); max 0 earned |

**Special Abilities:**
- **Skirmish Throw** — In any phase this unit uses the Withdraw tactic, it may make a Ranged(2) attack against one target before completing the withdrawal. This does not prevent the Withdraw.

**Recruitment:** 3 RP — Administrative, Military, Agricultural

---

#### Scouts
*Light-footed trackers and skirmishers, trained to observe and report. More useful for what they learn than what they kill.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Ranger/Rogue 1 |
| **ACR** | 1 |
| **Speed** | 2/10 |
| **HP** | 4 |
| **DV** | 11 |
| **OM** | +1; Ranged(3) |
| **Morale** | +0 |
| **Consumption** | 2 RP/Turn |
| **Resources** | — |
| **Tactics** | Withdraw (starting — innate); max 0 earned |

**Special Abilities:**
- **Scouting** — This unit may be assigned to the Scouting strategic action (see Part XXII).
- **Sneak Attack (1/engagement)** — If this unit attacks a target that is currently engaged with another friendly unit, it gains +2 OM for that phase.

**Recruitment:** 3 RP — Agricultural, Military

---

#### Siege Engineers
*Trained operators of heavy siege engines, as comfortable calculating trajectories as maintaining equipment under fire. When properly supported, they are the deciding factor in any siege.*

At recruitment, choose one siege engine type. This choice is permanent and determines the unit's OM, Ranged value, and siege effects.

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 2 |
| **ACR** | 2 |
| **Speed** | 1/4 |
| **HP** | 11 |
| **DV** | 12 |
| **OM** | See engine type |
| **Morale** | +0 |
| **Consumption** | 5 RP/Turn |
| **Resources** | Siege Engines (1) |
| **Tactics** | Siegebreaker (starting — innate); max 1 earned |

**Siege Engine Options:**

| Engine | OM | Fortification Effect |
|---|---|---|
| **Ballista** | +4; Ranged(4) | No standard fortification DV reduction; see Piercing Bolt. |
| **Catapult** | +3; Ranged(5) | Reduce target settlement DEF by –1d4 per engagement. |
| **Trebuchet** | +2; Ranged(7) | Reduce target settlement DEF by –2d4 per engagement; see Deploy. |

**Special Abilities:**
- **Piercing Bolt (Ballista; 2/engagement)** — This attack ignores up to 2 DV from armor and fortification resources. Gains +2 OM when targeting a unit that is not benefiting from fortification DV.
- **Scatter Shot (Catapult; 1/phase)** — When this unit targets a square occupied by an enemy unit, all enemy units adjacent to that square take 1 HP collateral damage.
- **Bombardment (Trebuchet; 1/engagement)** — When attacking a fortified position whose DEF has been reduced to 0 or below this Turn, deal an additional 2 HP damage to the defending unit.
- **Deploy (Trebuchet)** — The trebuchet must spend one full phase deploying before it can fire. It cannot fire in the phase it moves. If it moves after deploying, it must spend another full phase redeploying before firing again.

**Recruitment:** 9 RP — Military, Industrial

---

#### Horse Archers
*Mounted bowmen trained as mobile skirmishers and raiders. They loose arrows while riding, strike supply lines, and vanish before a response can be organized.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 2 (mounted) |
| **ACR** | 2 |
| **Speed** | 3/15 |
| **HP** | 11 |
| **DV** | 12 |
| **OM** | +3; Ranged(3) |
| **Morale** | +0 |
| **Consumption** | 4 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts, Withdraw (starting — innate); max 1 earned |

**Special Abilities:**
- **Scouting** — This unit may be assigned to the Scouting strategic action (see Part XXII).
- **Raiding** — This unit may participate in Raid Settlement and Objective Raid strategic actions (see Part XXII).
- **Mobile Fire** — This unit may make a Ranged attack in the same phase it moves.

**Recruitment:** 6 RP — Military, Agricultural

---

#### Light Cavalry
*Mounted troops trained for harassment, raiding, and pursuit. What they lack in staying power they compensate with speed and reach.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 2 (mounted) |
| **ACR** | 2 |
| **Speed** | 3/15 |
| **HP** | 11 |
| **DV** | 12 |
| **OM** | +4 |
| **Morale** | +0 |
| **Consumption** | 4 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts, Withdraw (starting — innate); max 1 earned |

**Special Abilities:**
- **Scouting** — This unit may be assigned to the Scouting strategic action (see Part XXII).
- **Raiding** — This unit may participate in Raid Settlement and Objective Raid strategic actions (see Part XXII).
- **Pursuit** — When an enemy unit routs or successfully uses the Withdraw tactic, this unit may immediately move up to its full Speed and make one free attack against the withdrawing unit before it exits.

**Recruitment:** 5 RP — Military, Agricultural

---

#### Knights
*Mounted warriors in medium armor, trained in coordinated cavalry tactics. Fast enough to exploit openings, and disciplined enough to hold a line when needed.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Cavalier 2 (mounted) |
| **ACR** | 2 |
| **Speed** | 3/15 |
| **HP** | 11 |
| **DV** | 13 |
| **OM** | +4 |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts (starting — innate); max 1 earned |

**Special Abilities:**
- **Challenge (2/engagement)** — This unit declares a target unit and gains +2 OM against it for the remainder of the engagement. The target gains +1 OM against this unit for the same duration.
- **Mounted Charge** — When this unit moves at least 2 squares before attacking in the same phase, it gains +2 OM.

**Recruitment:** 7 RP — Military, Administrative

---

#### Demon Hunters
*Hunters trained to track and destroy powerful evil outsiders. Their weapons are consecrated, their tactics are built around the specific weaknesses of demonic creatures, and their conviction does not waver.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Demon Hunter 2 |
| **ACR** | 2 |
| **Speed** | 1/5 |
| **HP** | 11 |
| **DV** | 13 |
| **OM** | +3 |
| **Morale** | +1 |
| **Consumption** | 3 RP/Turn |
| **Resources** | — |
| **Tactics** | None (max 1 earned) |

**Special Abilities:**
- **Detect Outsider** — This unit always knows the location of any outsider unit within 10 squares and cannot be surprised by such units.
- **Smite Demon (2/engagement)** — This unit gains +2 OM and ignores all DV bonuses against a single outsider unit for one phase.
- **Sacred Arsenal** — This unit's weapons are treated as magical and good-aligned for the purpose of bypassing damage resistance (e.g., Lycanthropic Resilience, Daemon Resilience).

**Recruitment:** 5 RP — Religious, Military

---

#### Ninjas
*Shadow operatives trained in stealth, misdirection, and sudden lethal strikes. They excel at disrupting enemy formations from unexpected angles and vanishing before a response can be mounted.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Ninja 2 |
| **ACR** | 2 |
| **Speed** | 2/10 |
| **HP** | 9 |
| **DV** | 12 |
| **OM** | +3; Ranged(2) |
| **Morale** | +0 |
| **Consumption** | 3 RP/Turn |
| **Resources** | — |
| **Tactics** | Withdraw (starting — innate); max 1 earned |

**Special Abilities:**
- **Sneak Attack (2/engagement)** — When this unit attacks a target currently engaged with another friendly unit, it gains +2 OM for that phase.
- **Shadow Cloak (1/engagement)** — This unit cannot be targeted by Ranged attacks for one phase.
- **Poison Use** — After a successful attack, the target unit takes –1 OM until the end of the engagement (cumulative; maximum –3 OM total).

**Recruitment:** 5 RP — Administrative, Military

---

#### Inquisitors
*Battle-hardened agents of law and faith, trained to identify threats to order and eliminate them with precise, judgmental force. Effective against a wide range of enemy types and difficult to shake from a task.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Inquisitor 2 |
| **ACR** | 2 |
| **Speed** | 1/5 |
| **HP** | 9 |
| **DV** | 13 |
| **OM** | +3 |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Spellbreaker (starting — innate); max 1 earned |

**Special Abilities:**
- **Judgment (2/engagement)** — At the start of a phase, declare one effect: Destruction (+2 OM), Protection (+2 DV), or Justice (+2 to all Morale checks). The effect lasts for that phase.
- **Bane (1/engagement)** — This unit gains +2 OM against a declared target unit type for one phase. The bonus increases to +4 OM if the target is an evil outsider or undead unit.

**Recruitment:** 6 RP — Religious, Military (LG, NG, or LN factions only)

---

#### Heavy Cavalry
*Mounted shock troops armed with lances and heavy weapons. Trained to break infantry lines and exploit gaps torn open by other arms.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 2 (mounted) |
| **ACR** | 2 |
| **Speed** | 3/15 |
| **HP** | 11 |
| **DV** | 13 |
| **OM** | +4 |
| **Morale** | +0 |
| **Consumption** | 4 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts (starting — innate); max 1 earned |

**Special Abilities:**
- **Bravery +1** — This unit gains +1 on Morale checks against fear effects and rout checks.
- **Mounted Charge** — When this unit moves at least 2 squares before attacking in the same phase, it gains +3 OM.

**Recruitment:** 7 RP — Military, Administrative

---

#### Wild Men
*Tribal warriors drawn from frontier communities and wilderness settlements. Armed with great weapons and clad in little armor, they compensate for lack of discipline with raw ferocity and speed.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Barbarian 2 |
| **ACR** | 2 |
| **Speed** | 2/10 |
| **HP** | 13 |
| **DV** | 12 |
| **OM** | +4 |
| **Morale** | +1 |
| **Consumption** | 3 RP/Turn |
| **Resources** | — |
| **Tactics** | Relentless Brutality (starting — innate); max 1 earned |

**Special Abilities:**
- **Rage (1/engagement)** — This unit gains +2 OM and –2 DV for one phase. Declared before the phase begins.

**Recruitment:** 3 RP — Agricultural, Military

---

#### Clerics
*Battle clerics assigned to military formations, providing divine healing and spiritual resilience in the field. Their presence sustains units that would otherwise break.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Cleric 2 |
| **ACR** | 2 |
| **Speed** | 1/5 |
| **HP** | 9 |
| **DV** | 13 |
| **OM** | +3 |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Spellbreaker (starting — innate); max 1 earned |

**Special Abilities:**
- **Channel Energy (3/engagement)** — Restore 2 HP to all friendly units within 3 squares, or deal 2 HP damage to all undead units within 3 squares (no Morale check).
- **Divine Blessing (1/engagement)** — A target friendly unit within 3 squares gains +2 DV or +2 OM for one phase.

**Recruitment:** 6 RP — Religious

---

#### Irregulars
*A ragged but effective formation of militia veterans, armed with a mix of hand weapons, hunting bows, and light armor. Experienced in ambush, withdrawal, and hit-and-run tactics.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter/Ranger 2 |
| **ACR** | 2 |
| **Speed** | 1/6 |
| **HP** | 11 |
| **DV** | 13 |
| **OM** | +1; Ranged(3) |
| **Morale** | +1 |
| **Consumption** | 3 RP/Turn |
| **Resources** | — |
| **Tactics** | False Retreat, Sniper Support, Withdraw (starting — innate); max 1 earned |

**Special Abilities:**
- **Bravery +1** — This unit gains +1 on Morale checks against fear effects and rout checks.
- **Favored Enemy (Opposed Faction)** — This unit gains +1 OM against units belonging to the opposing faction.

**Recruitment:** 8 RP — Agricultural, Military

---

#### Grenadiers
*Alchemist soldiers who hurl explosive concoctions into enemy formations. Dangerous at range and chaos-inducing in tight infantry engagements, but fragile if caught in melee.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Alchemist 2 |
| **ACR** | 2 |
| **Speed** | 1/5 |
| **HP** | 9 |
| **DV** | 11 |
| **OM** | +3; Ranged(3) |
| **Morale** | +0 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Withdraw (starting — innate); max 1 earned |

**Special Abilities:**
- **Bomb Volley (3/engagement)** — The unit hurls a volley of alchemical bombs. Deal 4 HP damage to a target unit within Ranged(3) and 2 HP damage to each unit adjacent to and engaged with the target.
- **Mutagen (1/engagement)** — The unit drinks its mutagen. Gain +2 OM and –2 DV for the remainder of the current engagement.

**Recruitment:** 7 RP — Industrial, Educational

---

#### Dwarven Warriors
*Stocky and slow but nearly immovable in a defensive line. Dwarven warriors excel at holding fortified positions and absorbing punishment that would break lighter infantry. Requires settlements with sufficient dwarven population.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (dwarf); Fighter 2 |
| **ACR** | 2 |
| **Speed** | 1/4 |
| **HP** | 11 |
| **DV** | 16 |
| **OM** | +4 |
| **Morale** | +1 |
| **Consumption** | 3 RP/Turn |
| **Resources** | — |
| **Tactics** | Defensive Wall (starting — innate); max 1 earned |

**Special Abilities:**
- **Dwarven Stability** — This unit gains +2 on Morale checks against fear, rout, and Taunt.
- **Hardy** — This unit reduces all HP damage it takes by 1 (minimum 1 damage per source).

**Recruitment:** 6 RP — Military, Industrial (requires dwarven settlement)

---

#### Shamans
*Spirit-speakers who call on ancestral forces of battle and life. They support allied formations with combat blessings and emergency healing, and can read the spirit of a battlefield in ways no standard scout can.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Shaman 2 |
| **ACR** | 2 |
| **Speed** | 1/5 |
| **HP** | 9 |
| **DV** | 12 |
| **OM** | +3 |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | None (max 1 earned) |

**Special Abilities:**
- **Battle Spirit (1/engagement)** — The shaman channels a warrior spirit. All friendly units within 3 squares gain +1 OM for one phase.
- **Life Spirit (2/engagement)** — Restore 2 HP to a target friendly unit within 3 squares.
- **Wandering Spirit (1/engagement)** — Either grant +1 DV to all friendly units within 3 squares for one phase, or impose –1 Morale on all enemy units within 3 squares.

**Recruitment:** 5 RP — Agricultural, Religious

---

#### Witches
*A coven of witches whose hexes disrupt enemy formations and turn fortune against their foes. They do not win fights directly — they ensure the enemy loses them.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Witch 2 |
| **ACR** | 2 |
| **Speed** | 1/5 |
| **HP** | 7 |
| **DV** | 11 |
| **OM** | +3; Ranged(4) |
| **Morale** | +0 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Taunt (starting — innate); max 1 earned |

**Special Abilities:**
- **Evil Eye Hex (3/engagement)** — Target enemy unit within Ranged(4) takes –2 OM or –2 DV (Witch's choice) until the end of the engagement. DC 14 Morale check to resist each phase.
- **Fortune Hex (2/engagement)** — A target friendly unit within Ranged(4) may reroll one OM roll or Morale check and take the better result.
- **Cackle** — Whenever the Witch unit attacks or activates a hex, all active hexes on enemy units are extended by one additional phase.

**Recruitment:** 5 RP — Agricultural, Religious

---

#### Heavy Infantry
*A formation of elite soldiers armed with swords or axes, shields, and heavy armor. Expensive to field, but capable of holding a line against nearly anything.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Fighter 2 |
| **ACR** | 2 |
| **Speed** | 1/5 |
| **HP** | 11 |
| **DV** | 15 |
| **OM** | +3 |
| **Morale** | +0 |
| **Consumption** | 3 RP/Turn |
| **Resources** | — |
| **Tactics** | None (max 1 earned) |

**Special Abilities:**
- **Bravery +1** — This unit gains +1 on Morale checks against fear effects and rout checks.

**Recruitment:** 7 RP — Administrative, Military

---

#### Defenders
*Heavy infantry trained specifically to hold ground. Their offense suffers for it, but they are extraordinarily difficult to dislodge from a position.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 2 |
| **ACR** | 2 |
| **Speed** | 1/4 |
| **HP** | 11 |
| **DV** | 17 |
| **OM** | +2 |
| **Morale** | +0 |
| **Consumption** | 3 RP/Turn |
| **Resources** | — |
| **Tactics** | Defensive Wall, Full Defense (starting — innate); max 1 earned |

**Special Abilities:**
- **Rallying Point** — While this unit is using the Defensive Wall or Full Defense tactic, all friendly units within 3 squares gain +1 DV.

**Recruitment:** 5 RP — Military, Administrative

---

#### Mages
*A small formation of 10–12 battle wizards trained to provide offensive and defensive support. Fragile on the line but devastating at range.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Wizard 3 |
| **ACR** | 3 |
| **Speed** | 1/4 |
| **HP** | 10 |
| **DV** | 10 |
| **OM** | +5; Ranged(4) |
| **Morale** | +1 |
| **Consumption** | 7 RP/Turn |
| **Resources** | Healing Potions |
| **Tactics** | Withdraw (starting — innate); max 1 earned |

**Special Abilities:**
- **Fireball (2/engagement)** — The mage unit targets a square within Ranged(4). The unit in that square takes 6 HP damage. Each unit adjacent to and engaged with the target takes 3 HP damage.
- **Bull's Strength (2/engagement)** — A target friendly unit gains +2 OM for the remainder of the current engagement.
- **Mage Armor (3/engagement)** — A target friendly unit gains +3 DV for the remainder of the current engagement.

**Recruitment:** 10 RP — Administrative, Educational

---

#### Battlemages
*Warrior-mages trained to fight on the front line, channeling destructive spells directly through their weapons. More durable than standard mages and far more dangerous in close quarters.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Magus 3 |
| **ACR** | 3 |
| **Speed** | 1/5 |
| **HP** | 13 |
| **DV** | 15 |
| **OM** | +6 |
| **Morale** | +1 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Dirty Fighters (starting — innate); max 1 earned |

**Special Abilities:**
- **Spell Combat (2/engagement)** — For one phase, this unit's attacks ignore DV bonuses from non-magical armor resources, and the unit gains +2 OM.
- **Arcane Pool (3/engagement)** — This unit's weapons crackle with stored arcane energy. Gain +2 OM for one phase.

**Recruitment:** 9 RP — Educational, Military

---

#### Samurai
*Mounted warriors bound by a strict code of honor, armed with katana and trained for both disciplined formation fighting and single combat. Exceptional morale and an unwillingness to break.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Samurai 3 (mounted) |
| **ACR** | 3 |
| **Speed** | 3/15 |
| **HP** | 16 |
| **DV** | 16 |
| **OM** | +5 |
| **Morale** | +2 |
| **Consumption** | 5 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cautious Combat (starting — innate); max 1 earned |

**Special Abilities:**
- **Challenge (2/engagement)** — This unit declares a target unit and gains +2 OM and +1 to all Morale checks while fighting that unit. This unit cannot Withdraw from the engagement while the challenge stands.
- **Resolve (1/engagement)** — This unit automatically passes one Morale check against fear or rout.

**Recruitment:** 8 RP — Military, Administrative

---

#### Paladins
*Holy warriors sworn to a divine cause, clad in heavy armor and armed with righteous purpose. As much a morale anchor as a fighting force.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Paladin 3 |
| **ACR** | 3 |
| **Speed** | 1/5 |
| **HP** | 16 |
| **DV** | 16 |
| **OM** | +4 |
| **Morale** | +2 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Full Defense (starting — innate); max 1 earned |

**Special Abilities:**
- **Aura of Courage** — Adjacent friendly units are immune to fear effects and Taunt.
- **Lay on Hands (2/engagement)** — Restore 3 HP to this unit or an adjacent friendly unit.

**Recruitment:** 7 RP — Religious, Military

---

#### Werewolves
*A cadre of lycanthropes operating as a shock unit. Nearly impossible to harm without the right weapons, and their bite carries a demoralizing curse that spreads through enemy formations.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human, shapechanger); Lycanthrope (werewolf) |
| **ACR** | 3 |
| **Speed** | 2/10 |
| **HP** | 13 |
| **DV** | 14 |
| **OM** | +4 |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Relentless Brutality (starting — innate); max 1 earned |

**Special Abilities:**
- **Lycanthropic Resilience** — Non-magical, non-silver weapons deal no HP damage to this unit. Enemy units with Improved Weapons (magical) or equipped with silver weapons bypass this resistance.
- **Curse of Lycanthropy** — When this unit deals HP damage to an enemy unit, the target unit must make a DC 12 Morale check or take –1 Morale for the remainder of the engagement.

**Recruitment:** 6 RP — Military (Neutral or Evil factions only)

---

#### Warpriests
*Warpriests who combine martial discipline with divine fervor. Less focused on protection than Paladins, more focused on aggressive sacred combat — consecrating their weapons and burning enemies with channeled faith.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Warpriest 3 |
| **ACR** | 3 |
| **Speed** | 1/5 |
| **HP** | 13 |
| **DV** | 14 |
| **OM** | +4 |
| **Morale** | +2 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Spellbreaker (starting — innate); max 1 earned |

**Special Abilities:**
- **Sacred Weapon (2/engagement)** — The unit's weapons flare with divine power. Gain +2 OM for one phase.
- **Fervor (3/engagement)** — Restore 3 HP to this unit, or deal 3 HP damage to an undead unit within 2 squares.

**Recruitment:** 8 RP — Religious, Military

---

#### Halfling Slingers
*Elite halfling slingers whose precision with a lead slug is the subject of soldiers' stories. Small, hard to hit, and quietly terrifying to face across an open field.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (halfling); Fighter 3 |
| **ACR** | 3 |
| **Speed** | 1/5 |
| **HP** | 16 |
| **DV** | 14 |
| **OM** | +4; Ranged(3) |
| **Morale** | +2 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Sniper Support, Cautious Combat (starting — innate); max 1 earned |

**Special Abilities:**
- **Accurate Fire** — When this unit uses the Sniper Support tactic, the OM bonus increases to +3 instead of +2.
- **Halfling Courage** — This unit may reroll one failed Morale check per engagement and keep the better result.

**Recruitment:** 8 RP — Agricultural, Trade

---

#### Centaurs
*A warband of centaur warriors — proud, territorial, and devastating at full gallop. They fight as natural cavalry without the need for mounts, combining the speed of horses with the weapons and tactics of trained infantry.*

| Stat | Value |
|---|---|
| **Type** | Monstrous Humanoid (centaur) |
| **ACR** | 3 |
| **Speed** | 3/15 |
| **HP** | 16 |
| **DV** | 14 |
| **OM** | +5 |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Expert Flankers (starting — innate); max 1 earned |

**Special Abilities:**
- **Natural Cavalry** — This unit gains +2 OM when it moves at least 2 squares before attacking in the same phase. No mount resource is required.
- **Trample** — When this unit uses a charge maneuver, the target unit takes –1 OM for the following phase in addition to normal charge damage.

**Recruitment:** 6 RP — Agricultural (Non-evil factions only)

---

#### Ogres
*A cadre of ogres drawn by the promise of plunder. Brutish, hard to discipline, and expensive in supplies, but capable of absorbing punishment and dealing it out in equal measure.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (giant); Ogre |
| **ACR** | 3 |
| **Speed** | 1/5 |
| **HP** | 13 |
| **DV** | 14 |
| **OM** | +5 |
| **Morale** | +0 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Relentless Brutality (starting — innate); max 1 earned |

**Special Abilities:**
- **Brute Force** — On a successful melee attack, the target unit takes –1 DV until the end of the current phase.
- **Plunder** — When this unit participates in a Raid Settlement action, the RP yield is increased by 2.

**Recruitment:** 6 RP — Military (Non-good factions only)

---

#### Pikemen
*Veteran formation fighters armed with long pikes. Experienced enough to break cavalry charges with confidence and hold a line long after lighter infantry would have buckled.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 3 |
| **ACR** | 3 |
| **Speed** | 1/4 |
| **HP** | 16 |
| **DV** | 14 |
| **OM** | +4 |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Defensive Wall (starting — innate); max 1 earned |

**Special Abilities:**
- **Phalanx** — This unit gains +3 OM against mounted units.
- **Stand Firm** — This unit cannot be forced to Withdraw by a charge maneuver. Enemy units that fail a charge against this unit take –1 OM for the following phase.

**Recruitment:** 6 RP — Military, Administrative

---

#### Elite Longbowmen
*Veteran soldiers trained to deliver coordinated volleys at exceptional range. A well-positioned unit of elite longbowmen can soften an advance before it reaches the line.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 3 |
| **ACR** | 3 |
| **Speed** | 1/5 |
| **HP** | 16 |
| **DV** | 12 |
| **OM** | +4; Ranged(5) |
| **Morale** | +1 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Sniper Support (starting — innate); max 1 earned |

**Special Abilities:**
- **Volley Fire (1/engagement)** — This unit fires a coordinated volley over a wide area. All non-engaged enemy units in the target square and adjacent squares within Ranged(5) each take 2 HP damage.

**Recruitment:** 7 RP — Military

---

#### Ducal Guard
*Battleaxe-armed warriors sworn to the protection of the Ducal Household of Severan. Every soldier is personally selected and tested by the Duke's castellan. Their discipline is absolute; their loyalty is to the house before any cause.*

**Special Recruitment** — May only be recruited through special campaign events.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 4 |
| **ACR** | 4 |
| **Speed** | 1/5 |
| **HP** | 22 |
| **DV** | 16 |
| **OM** | +6 |
| **Morale** | +2 |
| **Consumption** | 10 RP/Turn |
| **Resources** | — |
| **Tactics** | Full Defense, Defensive Wall (starting — innate); max 2 earned |

**Special Abilities:**
- **Stand Firm** — This unit cannot be forced to Withdraw or retreat by enemy special abilities. It may voluntarily use the Withdraw tactic, but cannot be compelled to do so.
- **Bodyguard** — If a PC or NPC Commander attached to this army would be targeted by an enemy special ability that removes them from play or reduces their effectiveness, this unit may intercept. Make a DC 14 Morale check; on success, the effect is redirected to this unit, which takes a minimum of 4 HP damage in place of the original effect.
- **Battleaxe Strike (2/engagement)** — On a successful attack that deals HP damage, the target must make a DC 14 Morale check or take –1 DV for the following phase.

**Recruitment:** Special Recruitment only — **[ELITE UNIT — Limit 1 per faction]**

---

#### Elite Scouts
*Veteran rangers operating deep behind enemy lines, equally capable of gathering intelligence and striking supply lines. A flexible asset in any campaign.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Ranger 4 |
| **ACR** | 4 |
| **Speed** | 2/10 |
| **HP** | 22 |
| **DV** | 14 |
| **OM** | +5; Ranged(4) |
| **Morale** | +1 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Sniper Support, Withdraw (starting — innate); max 2 earned |

**Special Abilities:**
- **Scouting** — This unit may be assigned to the Scouting strategic action (see Part XXII).
- **Raiding** — This unit may participate in Raid Settlement and Objective Raid strategic actions (see Part XXII).
- **Favored Terrain** — In natural terrain (forest, hills, plains), this unit gains +1 DV and +1 OM.

**Recruitment:** 9 RP — Military

---

#### Lancers
*Elite light cavalry who fight in the Lancer tradition — fast, precise, and gone before the enemy can organize a response. Trained to strike at command elements, isolated units, and overextended formations.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 4 (mounted) |
| **ACR** | 4 |
| **Speed** | 4/20 |
| **HP** | 22 |
| **DV** | 14 |
| **OM** | +6 |
| **Morale** | +1 |
| **Consumption** | 7 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts, Expert Flankers, False Retreat (starting — innate); max 2 earned |

**Special Abilities:**
- **Scouting** — This unit may be assigned to the Scouting strategic action (see Part XXII).
- **Lance Strike (2/engagement)** — When this unit charges (moves 2+ squares before attacking), it gains +4 OM for that attack and the target takes –1 OM for the following phase as its formation is disrupted.
- **Hit and Run** — After this unit attacks in a phase, it may move up to half its Speed without triggering a free attack from the target.

**Recruitment:** 14 RP — Military

---

#### Nobles
*Allied nobles and their household retinues, whose voices carry weight on the battlefield. Their fighting ability is secondary; their true power is the courage and fury they can draw from the soldiers around them.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Bard 4 |
| **ACR** | 4 |
| **Speed** | 1/5 |
| **HP** | 18 |
| **DV** | 14 |
| **OM** | +3 |
| **Morale** | +2 |
| **Consumption** | 6 RP/Turn |
| **Resources** | — |
| **Tactics** | Taunt (starting — innate); max 2 earned |

**Special Abilities:**
- **Inspire Courage** — While this unit is active and unrouted, all friendly units within 5 squares gain +1 OM and +1 to Morale checks.
- **Dirge of Doom (1/engagement)** — All enemy units within 5 squares take –1 Morale for the remainder of the engagement. DC 14 Morale check to resist.

**Recruitment:** 8 RP — Administrative, Cultural

---

#### Guardians
*Druids who have turned their attunement to nature toward the art of war. They defend settlements, entangle advancing armies, and harden allied units with bark-thick protective magic.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Druid 4 |
| **ACR** | 4 |
| **Speed** | 1/5 |
| **HP** | 18 |
| **DV** | 14 |
| **OM** | +4 |
| **Morale** | +1 |
| **Consumption** | 5 RP/Turn |
| **Resources** | — |
| **Tactics** | Spellbreaker (starting — innate); max 2 earned |

**Special Abilities:**
- **Wild Shape (2/engagement)** — The unit shifts into powerful animal forms. Gain +3 OM and –1 DV for one phase.
- **Entangle (2/engagement)** — Target a square within Ranged(4). All units in that square and adjacent squares have their Speed reduced by 1 (minimum 0) until the end of the engagement or until they spend a full phase breaking free.
- **Barkskin (3/engagement)** — A target friendly unit within 4 squares gains +2 DV for the remainder of the current engagement.

**Recruitment:** 7 RP — Agricultural, Religious

---

#### Elite Knights
*Heavy cavalry at the peak of martial training, mounted on the finest warhorses available. A lance charge from an Elite Knight formation can shatter an infantry line before it has time to brace.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Cavalier 4 (mounted) |
| **ACR** | 4 |
| **Speed** | 4/20 |
| **HP** | 22 |
| **DV** | 15 |
| **OM** | +6 |
| **Morale** | +2 |
| **Consumption** | 6 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts, Expert Flankers (starting — innate); max 2 earned |

**Special Abilities:**
- **Challenge (3/engagement)** — This unit declares a target unit and gains +3 OM against it for the remainder of the engagement. The target gains +1 OM against this unit for the same duration.
- **Expert Charge** — This unit does not suffer a DV penalty when using a charge maneuver and gains +2 OM when moving at least 2 squares before attacking.

**Recruitment:** 10 RP — Military

---

#### Cataphracts
*Heavily armored cavalry mounted on barded warhorses. The cataphract is not subtle — it is the hammer that breaks things that were thought unbreakable.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 4 (mounted) |
| **ACR** | 4 |
| **Speed** | 3/15 |
| **HP** | 22 |
| **DV** | 16 |
| **OM** | +6 |
| **Morale** | +2 |
| **Consumption** | 7 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts, Relentless Brutality (starting — innate); max 2 earned |

**Special Abilities:**
- **Expert Charge** — This unit does not suffer a DV penalty when using a charge maneuver and gains +3 OM when moving at least 2 squares before attacking.
- **Armored Line** — When this unit is targeted by a charge attack, the attacker gains no OM bonus from the charge. The unit's barded mounts absorb the impact.

**Recruitment:** 12 RP — Military, Administrative

---

#### Bushwhackers
*Veteran ambush fighters and wilderness raiders, equally skilled with blade and bow. They are most dangerous when the enemy doesn't know they're there.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter/Ranger 4 |
| **ACR** | 4 |
| **Speed** | 2/10 |
| **HP** | 22 |
| **DV** | 13 |
| **OM** | +5; Ranged(4) |
| **Morale** | +1 |
| **Consumption** | 4 RP/Turn |
| **Resources** | — |
| **Tactics** | Sniper Support, False Retreat (starting — innate); max 2 earned |

**Special Abilities:**
- **Scouting** — This unit may be assigned to the Scouting strategic action (see Part XXII).
- **Raiding** — This unit may participate in Raid Settlement and Objective Raid strategic actions (see Part XXII).
- **Ambush (1/engagement)** — The first phase this unit attacks in an engagement, if it has not yet been engaged by an enemy unit, it gains +3 OM and the target cannot apply DV bonuses from fortification for that phase.

**Recruitment:** 8 RP — Agricultural, Military

---

#### Elven Foresters
*Elven rangers who have spent lifetimes mastering the forest. Their longbows outrange nearly any other unit on the field, and their precision allows them to pick individual targets out of a melee without harming allies. Requires settlements with sufficient elven population.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (elf); Ranger 5 |
| **ACR** | 5 |
| **Speed** | 2/10 |
| **HP** | 27 |
| **DV** | 14 |
| **OM** | +6; Ranged(5) |
| **Morale** | +1 |
| **Consumption** | 6 RP/Turn |
| **Resources** | — |
| **Tactics** | Sniper Support, False Retreat, Withdraw (starting — innate); max 2 earned |

**Special Abilities:**
- **Scouting** — This unit may be assigned to the Scouting strategic action (see Part XXII).
- **Woodland Stride** — This unit may move through forested and difficult natural terrain without movement penalty on the tactical map.
- **Elven Accuracy** — When this unit fires into melee, adjacent engaged units take no collateral damage. Only the target takes full damage.

**Recruitment:** 10 RP — Agricultural (requires elven settlement)

---

#### Berserkers
*Veteran barbarian shock troops hardened by years of brutal combat. Nearly impossible to stop once committed to a charge, and devastating when bloodied.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Barbarian 5 |
| **ACR** | 5 |
| **Speed** | 2/10 |
| **HP** | 32 |
| **DV** | 15 |
| **OM** | +8 |
| **Morale** | +2 |
| **Consumption** | 6 RP/Turn |
| **Resources** | — |
| **Tactics** | Relentless Brutality, Dirty Fighters (starting — innate); max 2 earned |

**Special Abilities:**
- **Greater Rage (2/engagement)** — This unit gains +3 OM and –2 DV for one phase. If the unit is below half HP, it gains +4 OM instead.
- **Intimidating Presence** — When this unit causes an enemy unit to rout, all other enemy units within 5 squares must make a DC 13 Morale check or take –1 Morale until the end of the engagement.

**Recruitment:** 10 RP — Military

---

#### Royal Yeomanry
*The legendary archers of the Ambracian royal household. Every soldier in this unit can split an arrow at two hundred yards. They were scattered on the night of the executions; reassembling them is a signal to the people of Ambracia that the old kingdom lives.*

**Special Recruitment** — May only be recruited through special campaign events.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 5 |
| **ACR** | 5 |
| **Speed** | 1/5 |
| **HP** | 27 |
| **DV** | 15 |
| **OM** | +7; Ranged(5) |
| **Morale** | +2 |
| **Consumption** | 10 RP/Turn |
| **Resources** | — |
| **Tactics** | Sniper Support (starting — innate); max 2 earned |

**Special Abilities:**
- **Arrow Storm (2/engagement)** — This unit fires a disciplined volley. Deal 4 HP damage to all units in a target square within Ranged(5) and 2 HP damage to all units adjacent to that square.
- **Aimed Shot (3/engagement)** — This unit selects a single target. It gains +3 OM against that target for one phase; this attack ignores DV bonuses from fortification resources.
- **Covering Fire** — When a friendly unit within 5 squares uses the Withdraw tactic, this unit may immediately make one free Ranged attack against any enemy unit adjacent to or pursuing the withdrawing unit.

**Recruitment:** Special Recruitment only — **[ELITE UNIT — Limit 1 per faction]**

---

#### Crusaders
*Elite paladins who have fought long campaigns in service of their faith. Virtually unbreakable in defense, and capable of turning the tide of a larger engagement through sheer presence.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Paladin 5 |
| **ACR** | 5 |
| **Speed** | 1/5 |
| **HP** | 27 |
| **DV** | 18 |
| **OM** | +7 |
| **Morale** | +3 |
| **Consumption** | 8 RP/Turn |
| **Resources** | — |
| **Tactics** | Full Defense, Defensive Wall (starting — innate); max 2 earned |

**Special Abilities:**
- **Aura of Courage** — Friendly units within 5 squares are immune to fear effects and Taunt.
- **Smite Evil (2/engagement)** — This unit gains +2 OM and ignores DV bonuses from resources against a single declared target unit for one phase.
- **Lay on Hands (3/engagement)** — Restore 5 HP to this unit or an adjacent friendly unit.

**Recruitment:** 12 RP — Religious, Military

---

#### Companion Cavalry
*Heavy cataphract cavalry who serve as the royal guard of the Kingdom of Delft. Each soldier chooses their own scale armor pattern; the effect en masse is dazzling and deliberately intimidating. Opponents who have faced them once do not underestimate the display again.*

**Special Recruitment** — May only be recruited through special campaign events.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 5 (mounted) |
| **ACR** | 5 |
| **Speed** | 4/20 |
| **HP** | 27 |
| **DV** | 16 |
| **OM** | +8 |
| **Morale** | +2 |
| **Consumption** | 12 RP/Turn |
| **Resources** | Mounts |
| **Tactics** | Cavalry Experts, Expert Flankers (starting — innate); max 2 earned |

**Special Abilities:**
- **Brilliant Display** — At the start of any engagement, all enemy units within 5 squares must make a DC 15 Morale check or take –1 Morale for the first two phases of that engagement.
- **Armored Charge** — When this unit charges (moves 2+ squares before attacking), it gains +4 OM rather than the standard +2.
- **Companion Bond** — While a PC or NPC Commander is attached to this unit's army, the Commander gains +2 to Command Rating and this unit gains +1 OM.

**Recruitment:** Special Recruitment only — **[ELITE UNIT — Limit 1 per faction]**

---

#### Sacred Band
*Fifteen pairs of married elven warriors sworn to the protection of the Elven Queen. Each pair fights as a single disciplined unit — with spear, spell, and bow — and the loss of any member is irreplaceable. They are never deployed lightly.*

**Special Recruitment** — May only be recruited through special campaign events.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (elf); Fighter/Wizard 6 |
| **ACR** | 6 |
| **Speed** | 2/10 |
| **HP** | 27 |
| **DV** | 17 |
| **OM** | +8; Ranged(4) |
| **Morale** | +3 |
| **Consumption** | 12 RP/Turn |
| **Resources** | — |
| **Tactics** | Spellbreaker, Sniper Support (starting — innate); max 3 earned |

**Special Abilities:**
- **Irreplaceable** — This unit cannot recover HP through standard post-engagement recovery, healing abilities, or unit special abilities. HP may be restored only through a direct RP expenditure of 10 RP per HP recovered, declared during Turn Resolution. This cost represents resurrection magic required for fallen members.
- **Bond of Partners** — After any phase in which this unit takes HP damage, it gains +1 OM in the following phase. This bonus does not stack.
- **Pair Spellwork (2/engagement)** — Coordinated casting between matched partners. This unit targets a square within Ranged(4) and deals 6 HP magical damage to the unit in that square; each unit adjacent to and engaged with the target takes 3 HP damage.

**Recruitment:** Special Recruitment only — **[ELITE UNIT — Limit 1 per faction]**

---

#### Giants
*Hill giants recruited into service — lumbering, destructive, and capable of hurling boulders across a formation. What they lack in discipline they compensate for in raw devastation.*

| Stat | Value |
|---|---|
| **Type** | Humanoid (giant); Hill Giant |
| **ACR** | 7 |
| **Speed** | 2/10 |
| **HP** | 31 |
| **DV** | 20 |
| **OM** | +9; Ranged(3) |
| **Morale** | +1 |
| **Consumption** | 9 RP/Turn |
| **Resources** | — |
| **Tactics** | Relentless Brutality (starting — innate); max 3 earned |

**Special Abilities:**
- **Rock Throwing (3/engagement)** — This unit hurls boulders at a target unit within Ranged(3). Deal 5 HP damage to the target; each unit adjacent to and engaged with the target takes 2 HP collateral damage.
- **Brute Strength** — On a successful melee attack, the target unit takes –2 DV until the end of the current phase.

**Recruitment:** 10 RP — Military (Non-good factions only)

---

#### Evocati
*Veterans recalled from retirement to guard the members of the Confederation Council. Every soldier in this unit has survived at least one full continental campaign. They do not frighten. They do not break. They have seen everything.*

**Special Recruitment** — May only be recruited through special campaign events.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 7 |
| **ACR** | 7 |
| **Speed** | 1/5 |
| **HP** | 38 |
| **DV** | 18 |
| **OM** | +9 |
| **Morale** | +3 |
| **Consumption** | 15 RP/Turn |
| **Resources** | — |
| **Tactics** | Full Defense, Defensive Wall (starting — innate); max 3 earned |

**Special Abilities:**
- **Veteran's Discipline** — This unit is immune to fear effects, Taunt, and all special abilities that reduce Morale. It cannot be demoralized.
- **Testudo Formation (1/engagement)** — This unit forms a tortoise formation for one phase: gain +4 DV and –2 OM; all Ranged attacks targeting this unit automatically miss for that phase. Other units cannot charge through this unit while the formation is active.
- **Council Guard** — If a PC or NPC Commander attached to this army would be removed from play, captured, or killed by any effect, this unit may intercept. The unit takes 5 HP damage and the Commander is unaffected. This ability may be used once per Turn.

**Recruitment:** Special Recruitment only — **[ELITE UNIT — Limit 1 per faction]**

---

#### Celestials
*Aasimar paladins of extraordinary power, guided by divine heritage and years of holy warfare. Radiant in combat and seemingly impervious to fear, they anchor allied forces against the worst the enemy can field.*

**Special Recruitment** — May only be recruited through special campaign events. Available to LG factions only.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (aasimar); Paladin 8 |
| **ACR** | 8 |
| **Speed** | 1/5 |
| **HP** | 44 |
| **DV** | 22 |
| **OM** | +10 |
| **Morale** | +4 |
| **Consumption** | 12 RP/Turn |
| **Resources** | — |
| **Tactics** | Full Defense, Defensive Wall (starting — innate); max 4 earned |

**Special Abilities:**
- **Aura of Courage** — Friendly units within 10 squares are immune to fear effects and Taunt.
- **Divine Radiance (2/engagement)** — Deal 6 HP damage to all evil-aligned units within 4 squares. Friendly units are unaffected.
- **Smite Evil (3/engagement)** — This unit gains +3 OM and ignores all DV bonuses against a single declared target unit for one phase.
- **Lay on Hands (4/engagement)** — Restore 6 HP to this unit or an adjacent friendly unit.

**Recruitment:** Special Recruitment only (LG factions only) — **[ELITE UNIT — Limit 1 per faction]**

---

#### Demons
*A pair of powerful outsiders called from the lower planes. Their presence corrodes the will of nearby enemy troops, and their claws carry a supernatural plague that lingers long after the engagement.*

**Special Recruitment** — May only be recruited through special campaign events. Available to Evil factions only.
**[ELITE UNIT — Limit 1 per faction]**

> *Stat basis: Leukodaemon (CR 9 Daemon). "Demon" is the in-world colloquial term.*

| Stat | Value |
|---|---|
| **Type** | Outsider (daemon, evil, extraplanar) |
| **ACR** | 9 |
| **Speed** | 2/10; Fly 3/15 |
| **HP** | 49 |
| **DV** | 22 |
| **OM** | +10 |
| **Morale** | +2 |
| **Consumption** | 10 RP/Turn |
| **Resources** | — |
| **Tactics** | False Retreat, Withdraw (starting — innate); max 4 earned |

**Special Abilities:**
- **Fly** — See **Fly** in Part XXI Special Abilities.
- **Plague Aura** — At the start of each phase, all enemy units within 3 squares must make a DC 15 Morale check or take 1 HP damage from supernatural disease.
- **Fear Aura** — Enemy units within 5 squares take –1 Morale at the start of each engagement phase. Units immune to fear are unaffected.
- **Daemon Resilience** — This unit is immune to fear, disease, and poison effects. Ranged attacks against this unit suffer –2 OM unless the weapons are magical or silvered.

**Recruitment:** Special Recruitment only (Evil factions only) — **[ELITE UNIT — Limit 1 per faction]**

---

#### Vampires
*A small coterie of undead predators — patient, relentless, and nearly impossible to kill by conventional means. Devastating against unprepared armies, but requiring rare and specific conditions to maintain.*

**Special Recruitment** — May only be recruited through special campaign events. Available to NE or CE factions only.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Undead (vampire) |
| **ACR** | 9 |
| **Speed** | 2/10 |
| **HP** | 40 |
| **DV** | 21 |
| **OM** | +10 |
| **Morale** | +2 |
| **Consumption** | 10 RP/Turn |
| **Resources** | — |
| **Tactics** | False Retreat, Withdraw (starting — innate); max 4 earned |

**Special Abilities:**
- **Undead Immunities** — This unit is immune to fear effects, Taunt, and morale-reducing abilities. Abilities that restore HP to living creatures have no effect on this unit.
- **Blood Drain (3/engagement)** — On a successful attack, the target unit loses 2 HP and this unit restores 2 HP (maximum its listed HP).
- **Energy Drain (2/engagement)** — On a successful attack, the target unit takes –2 OM and –2 DV for the remainder of the engagement.
- **Dominate (1/engagement)** — Target enemy unit within 3 squares makes a DC 17 Morale check. On a failure, it does not attack this unit for one phase and takes –2 OM against all targets.

**Recruitment:** Special Recruitment only (NE or CE factions only) — **[ELITE UNIT — Limit 1 per faction]**

---

#### Vindicators
*Holy warriors who have crossed the threshold from paladin to instrument of divine wrath. Their bodies bear the stigmata of their faith, and they fight with a ferocity that shames lesser soldiers.*

**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Holy Vindicator (Fighter/Cleric 10 equivalent) |
| **ACR** | 10 |
| **Speed** | 1/5 |
| **HP** | 55 |
| **DV** | 24 |
| **OM** | +12 |
| **Morale** | +4 |
| **Consumption** | 12 RP/Turn |
| **Resources** | — |
| **Tactics** | Full Defense, Defensive Wall, Spellbreaker (starting — innate); max 5 earned |

**Special Abilities:**
- **Vindicator's Shield** — All friendly units within 5 squares gain +2 DV.
- **Divine Retribution (2/engagement)** — When this unit takes HP damage, it immediately deals equal HP damage back to the attacking unit.
- **Stigmata (1/engagement)** — This unit voluntarily takes 3 HP damage to activate: restore 6 HP to all friendly units within 5 squares and deal 3 HP damage to all enemy units within 5 squares.

**Recruitment:** Special Recruitment only — **[ELITE UNIT — Limit 1 per faction]**

---

#### Eldritch Knights
*The rarest and most dangerous of warrior-mages: masters of both blade and spell who have spent years perfecting the art of channeling arcane power directly through martial combat.*

**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (human or mixed-race); Eldritch Knight (Fighter/Wizard 10 equivalent) |
| **ACR** | 10 |
| **Speed** | 1/5 |
| **HP** | 45 |
| **DV** | 22 |
| **OM** | +12 |
| **Morale** | +2 |
| **Consumption** | 12 RP/Turn |
| **Resources** | — |
| **Tactics** | Dirty Fighters, Expert Flankers (starting — innate); max 5 earned |

**Special Abilities:**
- **Spell Blade (3/engagement)** — For one phase, this unit's attacks ignore all DV bonuses from non-magical armor resources and the unit gains +2 OM.
- **Arcane Mastery (2/engagement)** — The unit unleashes a devastating area spell. Deal 8 HP damage to a target unit within Ranged(4) and 4 HP damage to each unit adjacent to and engaged with the target.

**Recruitment:** Special Recruitment only — **[ELITE UNIT — Limit 1 per faction]**

---

#### Dragon Riders
*Two pairs of bonded dragon riders — veteran fighters mounted on adult copper dragons. Among the most destructive forces a good faction can field, capable of reshaping a battle in a single pass.*

**Special Recruitment** — May only be recruited through special campaign events. Available to Good factions only.
**[ELITE UNIT — Limit 1 per faction]**

| Stat | Value |
|---|---|
| **Type** | Humanoid (human); Fighter 6 / Dragon (copper, adult) |
| **ACR** | 14 |
| **Speed** | 4/20 (fly); 2/10 (ground) |
| **HP** | 91 |
| **DV** | 27 |
| **OM** | +14; Ranged(5) |
| **Morale** | +3 |
| **Consumption** | 20 RP/Turn |
| **Resources** | — |
| **Tactics** | Expert Flankers (starting — innate); max 7 earned |

**Special Abilities:**
- **Fly** — See **Fly** in Part XXI Special Abilities.
- **Acid Breath (2/engagement)** — Deal 8 HP damage to a target unit within Ranged(5) and 4 HP damage to each unit adjacent to and engaged with the target.
- **Slowing Breath (2/engagement)** — Target unit's Speed is reduced to 0 for one phase and it cannot use the Withdraw tactic during that phase.
- **Dragon Hide** — This unit reduces all HP damage it takes by 3 (minimum 1 per source).

**Recruitment:** Special Recruitment only (Good factions only) — **[ELITE UNIT — Limit 1 per faction]**

---
## XXII. Strategic Actions

Strategic Actions are declared during the **Orders Phase** of each Turn and take effect at **Turn Resolution** unless otherwise noted. Both factions declare and resolve actions simultaneously.

### General Rules

**Action Types**
Strategic Actions are divided into three types: **Military**, **Intelligence**, and **Diplomatic**. Each PC (or designated NPC) may perform only one action type per Turn.

**Action Ratings**
The maximum number of actions a character may take equals their **Rating** for their chosen type. Each action has an **Action Cost** deducted from that Rating. A character whose remaining Rating is less than an action's cost cannot take that action.

| Type | Rating Formula |
|---|---|
| Military | Command Rating = 5 + Charisma modifier |
| Intelligence | Intel Rating = Intelligence modifier + (Profession–Spycraft ranks ÷ 3, rounded down) |
| Diplomatic | Diplomacy Rating = Charisma modifier + (Diplomacy skill ranks ÷ 3, rounded down) |

**Costs**
Each action lists an **Action Cost** (minimum 1) and an **RP Cost**. The faction's war chest must contain sufficient RP to cover all declared RP costs before actions are executed.

---

### Military Actions

**Check Rule:** Military action checks may use the standard Control Check formula (Part XV) or substitute **Profession (Soldier)** in place of the Charisma modifier and Leadership bonus. Exception: Recruitment always uses the standard Control Check.

---

#### Recruitment

A faction may order the recruitment of new Units from any Settlement it controls (Liberated or Occupied). Recruitment is declared during the Orders Phase. The new Unit becomes available at the end of the **following Turn**.

**Recruitment Limit**
A faction may recruit a total number of Units per Turn equal to the **Command Rating of its faction leader** (or the designated PC or NPC responsible for recruitment):

> **Command Rating = 5 + Charisma modifier**

**Recruitable Units**
Each Settlement offers a recruitment list based on its **Settlement Type**, **Region**, **Province**, and any special units unique to that Settlement. Specific unit lists are defined in the Unit Types section (Part XXI).

**Recruitment Cost**
The faction's war chest must contain RP equal to or greater than the full recruitment cost. The cost is paid at the time of the order.

*From an Occupied Settlement:* Recruitment cost = base unit cost + unrest surcharge.

| Settlement Unrest | Surcharge |
|---|---|
| Content (1–2) or Complacent (3–4) | +0 RP |
| Unruly (5–6) | +1 RP |
| General Uprising (7–8) | +2 RP |
| Total Revolt (9–10) | +3 RP |

*From a Liberated Settlement:* Recruitment cost = base unit cost + 2 RP. Units recruited from a Liberated Settlement add **+1 RP to their Consumption** each Turn, on top of base Consumption (ACR ÷ 2 RP per Turn).

**Recruitment Checks**
After the cost is paid, the recruiting character makes Control Checks where applicable. On a failed check, the Unit is not recruited but the cost is **not refunded**.

*High Unrest Check* — Required if the Settlement's Unrest is **6 or higher**: DC = 10 + (Unrest × 2).

*Occupied Settlement Check* — Required for all Occupied Settlement recruitment: DC = 25 – current Loyalty (to the recruiting faction).

If both apply, both must be passed. Either failure cancels recruitment.

**Loss of Control**
If the faction loses control of the Settlement before the Unit becomes available, recruitment fails. The cost is not refunded.

---

#### Scouting

Assign a Unit with the **Scouting special ability** to a reconnaissance mission for the following Turn. The Unit detaches from any Army it belongs to and is unavailable for engagements.

**During each Round of the following Turn:**
- The scouting Unit acts before all other Units.
- The Unit surveys a contiguous area of up to **Movement × 10 squares**, no part of which is more than **10 squares** from the Unit's starting position for that Round. The area may be any shape within these constraints.
- All enemy Units and Armies within the surveyed area are detected.
- **Concealed Units:** The controlling character makes an opposed Military check against the concealed Unit's Army Commander (or regional commander for independent Units). Success reveals the Unit.
- At the end of the Round, place the scouting Unit anywhere within its standard movement distance from its starting position.

**Action Cost:** 1 | **RP Cost:** 2

---

#### Reinforce

Move one unattached Unit (not currently assigned to an Army) up to **Movement × 5 squares**. After movement, the Unit may be attached to an Army at its destination, provided the Army Commander has not reached their Command Rating.

**Action Cost:** 1 | **RP Cost:** 2

---

#### Dispatch Orders

Send orders to an NPC Army Commander in the field. The Commander follows the orders to the best of their ability during the following Turn.

**Check:** DC = 10 + (2 per enemy-controlled Settlement in the Province where the targeted Commander is located).
- **Failure:** Orders do not reach the Commander due to enemy action. The Commander acts on their last known orders.
- **Failure by 10 or more:** Orders are intercepted. The GM may use their content to inform enemy strategy.

**Action Cost:** 1 | **RP Cost:** 1

---

#### Rally

Restore Morale to one or more Units. Declare which Units are being rallied and by how many Morale points (maximum 2 points per Unit per Turn). A Unit being rallied must not be actively engaged in combat this Round. No check required.

**Action Cost:** 1 per Unit rallied | **RP Cost:** 2 per Morale point restored

---

#### Improve Defenses

Construct new fortifications in a Settlement under faction control (Occupied or Liberated). The Settlement cannot currently be under siege. Each use increases DEF by 1. Takes effect at end of Turn. No check required.

> RP Cost per +1 DEF = (current DEF + 1) × 5

*Example: raising DEF from 2 to 3 costs (2 + 1) × 5 = 15 RP.*

**Action Cost:** 1 per +1 DEF | **RP Cost:** as above

---

#### Repair Defenses

Restore DEF lost to siege bombardment or attrition in a Settlement under faction control. The Settlement **cannot currently be under siege**. Repair cannot raise Current DEF above the Settlement's **Base DEF** (its value before siege damage began).

Each Settlement entry tracks **Base DEF** (original value; maximum for repair) and **Current DEF** (actual current state).

No check required.

**Action Cost:** 1 per point restored | **RP Cost:** 3 per point restored

---

#### Raid Settlement

Strike at a Settlement to steal resources. All participating Units must have the **Raiding special ability**. The target Settlement must be within **Movement × 3 squares** of the raiding Units.

**Check:**
- *No enemy Units present:* DC = 15 + Settlement's Population rating.
- *Enemy Units present:* Opposed Military check against the enemy Army Commander(s).

On success, the raiding faction steals RP equal to **1/3 of the Settlement's current Economy rating** (rounded down, minimum 1). Regardless of outcome, the Settlement's Loyalty to the raiding faction decreases by 1 and Unrest increases by 1.

If the opposed check fails, the raid is repelled and the raiding Units withdraw without engagement.

**Action Cost:** 1 | **RP Cost:** —

---

#### Objective Raid

Strike at an enemy Army's supply train and logistics to steal resources and hamper movement. All participating Units must have the **Raiding special ability**. The target Army must be within **Movement × 3 squares** of the raiding Units.

**Check:** Opposed Military check against the targeted Army's Commander.
- **Success:** The targeted Army's movement is halved (rounded down) for each Round of the following Turn. The raiding faction steals RP equal to **targeted Army's aggregate ACR ÷ 4** (rounded down, minimum 1).
- **Failure:** The raiding Units are immediately engaged by the targeted Army. Resolve as a standard tactical or aggregate engagement.

**Action Cost:** 1 | **RP Cost:** —

---

### Intelligence Actions

**Intel Rating:** Intelligence modifier + (Profession–Spycraft ranks ÷ 3, rounded down)

**Check Rule:** Intelligence action checks use **Profession (Spycraft)**.

**Implication Failure:** If any Intelligence action check fails by **5 or more**, the faction is implicated. Reduce your Loyalty by 1 in all enemy-controlled Settlements in the same Province as the target.

---

#### Propaganda Campaign

Influence a specific Settlement's population toward your faction.

**Check:** DC = 25 – current Loyalty to your faction in the targeted Settlement.
- **Success:** Loyalty to your faction increases by 1.

**Action Cost:** 1 | **RP Cost:** 2

---

#### Foment Unrest

Stoke civil unrest in a specific Settlement.

**Check:** DC = 28 – current Unrest rating.
- **Success:** Unrest increases by 1.

**Action Cost:** 1 | **RP Cost:** 3

---

#### Sabotage Settlement

Strike at economic infrastructure in a specific Settlement. Declare the desired Economy reduction before rolling. On success, the reduction lasts **2 Turns**, after which the Economy rating returns to its previous value.

**Check:** DC = 14 + (attempted Economy reduction × 2).
- **Success:** Economy rating reduced by the declared amount for 2 Turns.

**Action Cost:** 1 | **RP Cost:** 1 per point of Economy reduction attempted

---

#### Sabotage Siege Equipment

Disable a specific enemy siege Unit for the following Turn.

**Check:** DC = 10 + targeted Unit's DV.
- **Success:** The Unit cannot be used during the following Turn. The controlling faction must spend RP equal to **half the Unit's recruitment cost** (rounded up) to restore it to service.

**Action Cost:** 1 | **RP Cost:** 2

---

#### Sabotage Supply Lines

Strike at an enemy Army's logistics to hamper its movement.

**Check:** DC = 15 + targeted Army's aggregate DV.
- **Success:** The targeted Army's movement is halved (rounded down) for each Round of the following Turn.

**Action Cost:** 1 | **RP Cost:** 1 per Unit in the targeted Army (minimum 3 RP)

---

#### Assassination

Direct operatives to eliminate an enemy Commander or key NPC. Resolves in two stages.

**Stage 1 — Detection**
The target makes a **Sense Motive or Perception check** (their choice) opposed by the acting character's Intel check.
- Target succeeds: the attempt is detected and automatically fails.
- Target fails: proceed to Stage 2.

**Stage 2 — Attempt**
**Check:** DC = 20 + targeted character's CR or ECL.
- **Success by 10 or less:** Target is wounded; cannot take actions for 1 Turn.
- **Success by more than 10:** Target is killed.
- **Failure:** Attempt is unsuccessful; implication failure rules apply normally.

Add **+5 to all DCs** for targets inside a Settlement. If the Settlement is **Administrative** type, this bonus increases to **+10**.

**Action Cost:** 3 | **RP Cost:** target's CR or ECL × 2

---

#### Counterintelligence

Use your spy network to detect and foil enemy operations in your region.

**Check:** Opposed Intel check against the enemy regional commander (or designated enemy intelligence officer).
- **Success:** Detect 1 active enemy Intelligence or Diplomatic operation in the region this Turn, plus 1 additional operation per 5 points above the opposing roll.
- For each detected operation you choose to foil: add **+10 to its DC** (or apply **+10 in your favor** for opposed checks).

**Action Cost:** 1 (base) + 1 per operation foiled | **RP Cost:** 2 (base) + 2 per operation foiled

---

#### Intelligence Gathering

Determine enemy presence in a specific Settlement.

**Check:** DC = 12 + Settlement's Population rating.
- **Success:** Reveals all enemy Units within the Settlement and provides a basic dossier on any enemy characters present (identity, faction affiliation, and general capabilities).

**Action Cost:** 1 | **RP Cost:** Population rating ÷ 3 (rounded up, minimum 1)

---

#### Establish Network

Place a persistent spy network in a specific Settlement. Requires a prior successful **Intelligence Gathering** operation in that Settlement.

**Check:** DC = 20 – current Loyalty to your faction in the targeted Settlement.
- **Success:** All future Intelligence action checks targeting that Settlement gain **+2**. The network remains active until dismantled by a successful enemy **Counterintelligence** action.

**Action Cost:** 2 | **RP Cost:** Settlement's Population rating × 2

---

### Diplomatic Actions

**Diplomacy Rating:** Charisma modifier + (Diplomacy skill ranks ÷ 3, rounded down)

**Check Rule:** Diplomatic action checks use the **Diplomacy skill**.

---

#### Hearts and Minds

Launch a province-wide campaign to improve your faction's standing with the general population.

**Check:** DC = 20 + (2 per enemy-controlled Settlement in the Province) + (2 per Settlement in the Province with Loyalty to your faction of 4 or less) + (3 per Settlement in the Province with Unrest 6 or higher). Maximum DC: 40.
- **Success:** Loyalty to your faction increases by 1 in all Settlements in the Province.

**Action Cost:** 4 | **RP Cost:** 25

---

#### Diplomatic Mission

Negotiate directly with the leadership of a neutral Settlement to improve your faction's standing.

**Check:** DC = 20 – (current Loyalty to your faction) + (current Loyalty to enemy faction) + (current Unrest rating).
- **Success:** Loyalty to your faction increases by 1.
- **Special:** If this action raises the Settlement's Loyalty to your faction to **6 or higher**, the Settlement immediately joins your faction as a Liberated Settlement.

**Action Cost:** 2 | **RP Cost:** Economy rating ÷ 3 (rounded up, minimum 2)

---

#### Quell Insurrection

Work directly with a Settlement's population to reduce civil unrest. Declare the desired reduction amount before rolling (maximum 3 points per Turn).

**Check:** DC = 10 + current Unrest + (amount of reduction × 3).
- **Success:** Unrest decreases by the declared amount.

**Action Cost:** 1 per point of Unrest reduced | **RP Cost:** 3 per point of Unrest reduced

---

#### Economic Development

Invest in a Settlement's infrastructure to permanently increase its Economy rating by 1. The Settlement must be Occupied or Liberated. Takes effect at the end of the following Turn. Subject to the 150% Population cap (Part XIV).

**Check:** DC = 15 + current Economy rating.
- **Success:** Economy rating increases by 1.

**Action Cost:** 2 | **RP Cost:** current Economy rating × 3

---

#### Spread the Word

Target a single Settlement with focused outreach — a lower-cost, more targeted alternative to Hearts and Minds.

**Check:** DC = 20 – current Loyalty to your faction + current Unrest rating.
- **Success:** Loyalty to your faction increases by 1.

**Action Cost:** 1 | **RP Cost:** 5

---

---

# TURN BOOKKEEPING

---

## XXIII. Turn Bookkeeping

At the end of each Turn, both the players and the GM calculate the new war chest total for each faction. This is performed during **Turn Resolution**, after all Tactical Rounds and strategic action effects have been applied.

### The War Chest Formula

> **New Fund Total = Starting Funds + Tax & Tribute Income + Event Income – Unit Upkeep – Character Salaries – Strategic Action Costs**

| Line | Notes |
|---|---|
| **Starting Funds** | The faction's war chest at the start of this Turn (previous Turn's New Fund Total) |
| **+ Tax & Tribute Income** | RP collected from Occupied (Tax) and Liberated (Tribute) Settlements this Turn (Part XVII) |
| **+ Event Income** | One-time RP gains earned during Rounds: Sack/Raze proceeds (Part XVI), Raid and Objective Raid proceeds (Part XXII) |
| **– Unit Upkeep** | Total Consumption for all active, available Units (Part VII). Units ordered for recruitment this Turn but not yet available do not pay upkeep until the Turn they become available. |
| **– Character Salaries** | Per-Turn cost of NPC Commanders and other employed characters. See Part XXIV. |
| **– Strategic Action Costs** | Total RP spent on Strategic Actions this Turn (Part XXII). Costs are committed at the Orders Phase; this line records them for tracking purposes. |

### War Chest Floor

A faction cannot spend RP it does not have. If the war chest reaches zero, no further RP expenditures may be made for the remainder of that Turn. If the calculated New Fund Total is negative, the faction has a shortfall that must be resolved before the Turn closes.

### Resolving a Shortfall

If Unit Upkeep and Character Salaries cannot be fully covered, the controlling player must take one or more of the following measures:

**1. Convert Gold Pieces to RP**

> 250 GP = 1 RP

Characters or factions with personal wealth may convert GP to make up the difference. This represents diverting private funds, selling assets, or calling in loans.

**2. Disband Units**

Disbanding a Unit immediately removes it from play. Its Consumption is deducted from this Turn's upkeep total before calculating the shortfall. Units may be disbanded in any number until the shortfall is resolved or no units remain.

**3. Unpaid Units**

If a shortfall remains after the above measures, the faction must declare which Units go unpaid this Turn. Each unpaid Unit suffers the following consequences:

- **Morale –2** (per Part VII).
- The Unit's Commander makes a **Morale check** to determine whether the Unit holds together or disbands.

> Morale Check: 1d20 + unit's current Morale modifier + Commander's Charisma modifier
> DC = 10 + number of consecutive Turns this Unit has gone unpaid

- **Success:** The Unit remains in service, demoralized but intact.
- **Failure:** The Unit disbands. It is removed from play.

If Morale falls to –5 or below as a result of the penalty, the Unit disbands automatically without a check (per Part VII).

### Enemy Bookkeeping

The GM performs the identical calculation for all enemy factions at Turn Resolution. As the revolution captures enemy territory and reduces enemy Tax income, the enemy's ability to maintain forces in the field degrades progressively. Enemy units that cannot be paid are subject to the same unpaid unit consequences above.

---

## XXIV. Special NPCs

Special NPCs are named characters the party recruits or hires to serve the faction. They operate between sessions and during Turn Resolution, performing roles the party cannot cover themselves or providing capabilities that amplify the faction's reach.

### NPC Roles

**Advisor**
Advisors perform strategic actions on behalf of the faction using their own action ratings. An advisor's actions are in addition to any actions the PCs take — they do not consume a PC's action allowance. An advisor may only take actions within their defined capabilities (listed in their NPC entry).

**Commander**
Commanders lead Armies in the field. Commander rules are defined in Part III. Special NPC Commanders may have abilities, boons, or Command Ratings beyond the NPC baseline.

**Specialist**
Specialists are stationed in a specific Settlement and provide ongoing passive effects: bonuses to Loyalty, Economy, Unrest, intelligence operations, or other settlement statistics. Their effects apply automatically each Turn as long as they remain stationed. A Specialist may only be stationed in one Settlement at a time.

### Recruitment and Hiring

**Recruited NPCs** join the faction out of conviction or loyalty to the cause. They work without salary. A recruited NPC may depart if the faction takes actions that fundamentally contradict their stated values or personal goals; the GM determines when this is triggered by narrative circumstances.

**Hired NPCs** work for pay. Their upkeep cost is defined in their individual NPC entry and is paid as part of **Character Salaries** at Turn Resolution each Turn.

If a hired NPC's salary cannot be paid, the controlling player makes a **Diplomacy check (DC 15)** to convince them to remain without pay for one additional Turn. On failure, the NPC departs the faction's service.

### Character Salaries

Character Salaries are the total monthly upkeep for all hired NPCs, plus any salary the PCs choose to pay themselves. Salaries are paid at Turn Resolution as part of the bookkeeping formula (Part XXIII).

Specific salary amounts are defined in each NPC's entry. PCs may set their own salary at any amount — including zero — at the start of each Turn.

### NPC Statistics

Each Special NPC entry includes the following:

| Field | Description |
|---|---|
| Role | Advisor / Commander / Specialist (may have multiple) |
| Status | Recruited (no salary) or Hired (salary defined below) |
| Upkeep | Monthly salary in RP (Hired NPCs only) |
| Action Types | Which action types the NPC can perform (Military / Intel / Diplomatic) |
| Rating(s) | The NPC's action rating(s) for their available types |
| Special Abilities | Settlement effects, unique actions, or passive bonuses |
| Loyalty | For recruited NPCs: what values or goals keep them aligned with the faction |

Specific NPC entries are defined in the adventure text for each Part.

---

## XXV. Special Events Roll

At the end of each Turn, just prior to bookkeeping, a special events roll is made. The GM may make this roll or invite the players to roll on their behalf.

### Determining the Number of Events

Roll **d100**:

| Result | Events This Turn |
|---|---|
| 0–50 | 1 event |
| 51–75 | 2 events |
| 76–99 | 3 events |
| 100 | World-Changing Event |

For each event generated, the GM determines its **type** (Military, Intelligence, or Diplomatic) based on current narrative circumstances, or rolls **1d6**: 1–2 = Military, 3–4 = Intelligence, 5–6 = Diplomatic. Then roll within the relevant table below to determine the specific event.

**World-Changing Event:** A major campaign-altering development of the GM's design — a significant battle outcome, a key NPC death, a political upheaval, or a shift in the broader war. No table applies; the GM introduces this event in a form appropriate to the current state of the campaign.

If multiple events of the same type are generated in the same Turn, re-roll duplicates.

---

### Military Events

Roll **1d20** (results 14–20: GM selects an appropriate event or rerolls).

| # | Event | Effect |
|---|---|---|
| 1 | **Local Volunteers** | Your faction receives a free unit of a random type from a random Settlement you control. No recruitment cost; upkeep begins next Turn. |
| 2 | **Supply Issue** | Problems securing or storing supplies cause a shortfall. Reduce all unit and army movement by 2 (minimum 1) for each Round next Turn. |
| 3 | **Recruitment Drive** | Local partisans encourage enlistment. Reduce the recruitment cost of all units by 2 (minimum 1) this Turn and next Turn. |
| 4 | **Desertion** | Prolonged campaigning erodes resolve. A random unit in your faction loses 2 Morale. |
| 5 | **Enemy Defectors** | Disenchanted soldiers abandon the enemy's cause. A random enemy unit of ACR 3 or lower joins your faction as a free unit; upkeep begins next Turn. |
| 6 | **Disease Outbreak** | Illness sweeps through your forces. A random unit loses HP equal to its ACR. Units currently under siege are not affected (already subject to reduced recovery). |
| 7 | **Forced March** | One of your armies pushes hard to close a gap. A random army you control may move double its normal movement in one Round next Turn; all Units in that army take HP damage equal to ACR ÷ 2 after the move. |
| 8 | **Fortuitous Find** | Your forces discover an abandoned supply cache. Gain 1d6+2 RP. |
| 9 | **Ambush** | Enemy forces exploit local knowledge to strike unexpectedly. A random army you control is ambushed at the start of one engagement next Turn; the attacker skips the Tactics Phase in that engagement. |
| 10 | **Weather Event** | Severe weather hampers operations. Apply Fog or Darkness battlefield conditions (GM's choice) to all engagements for next Turn's Rounds. |
| 11 | **Veteran Returns** | A discharged soldier rejoins the fight after hearing of the faction's cause. Add 1 Morale to a random unit in your faction. |
| 12 | **Demoralized Garrison** | Word of your victories has shaken enemy resolve. Reduce the Morale of all units in a random enemy-controlled Settlement by 1. |
| 13 | **Enemy Commander Dispute** | Internal conflict among the enemy's leadership disrupts coordination. The enemy may not use the Dispatch Orders action next Turn. |

---

### Intelligence Events

Roll **1d20** (results 14–20: GM selects an appropriate event or rerolls).

| # | Event | Effect |
|---|---|---|
| 1 | **Whisper Campaign** | Your agents seize an opportunity to erode enemy support. Reduce loyalty to the enemy faction by 1 in a random enemy-controlled Settlement. |
| 2 | **Partisan Caper** | Partisans steal funds from a local institution. Select a random enemy-controlled Settlement; receive RP equal to 1/4 of its Economy rating (rounded down, minimum 1). Make an Intel check DC = 10 + RP received — failure reduces loyalty to your faction by 1 in all Settlements in the Province. You may decline the funds to avoid the check entirely. |
| 3 | **Document Leak** | Enemy agents obtain sensitive intelligence documents. Add 2 to the RP cost of all Intelligence actions this Turn and +3 to the DC of all Intelligence actions next Turn. |
| 4 | **Double Agent** | One of your operatives is revealed to be working for the enemy. One random Intelligence action you take this Turn automatically fails. A successful Counterintelligence action (DC 20) identifies and removes the agent. |
| 5 | **Unexpected Informant** | A civilian approaches with actionable intelligence. Gain the equivalent of a successful Intelligence Gathering result in a random enemy-controlled Settlement — no roll or RP cost required. |
| 6 | **Cipher Broken** | Your cryptographers crack an enemy communication protocol. Gain +3 to all Intel action checks this Turn and next Turn. |
| 7 | **Safe House Compromised** | Enemy agents locate one of your networks. The Establish Network effect (if any) in a random Settlement is dismantled. |
| 8 | **Spy Captured** | An agent is taken by the enemy. The enemy gains a free Intelligence Gathering result against any Settlement you control (GM's choice). A Counterintelligence check (DC 20) prevents this. |
| 9 | **Propaganda Backfire** | An enemy operation targeting your faction produces the opposite of its intended effect. Increase loyalty to your faction by 1 in a random enemy-controlled Settlement. |
| 10 | **Secret Correspondence Intercepted** | Your agents capture an enemy courier with sensitive dispatches. Gain +2 to all Control Checks targeting a specific enemy Settlement (GM's choice) for 2 Turns. |
| 11 | **Rumor Mill** | Conflicting rumors about your faction's motives circulate widely. Apply –2 to all Diplomatic action checks this Turn. |
| 12 | **Informant Network** | A web of civilian sympathizers activates. Gain the equivalent of a free successful Intelligence Gathering result in a random Province. |
| 13 | **Assassination Attempt Foiled** | Enemy operatives target a key faction figure. That character makes a Perception check DC 18; on failure, they are out of action for 1 Turn. |

---

### Diplomatic Events

Roll **1d20** (results 14–20: GM selects an appropriate event or rerolls).

| # | Event | Effect |
|---|---|---|
| 1 | **Underground Supporters** | Civilians work behind the scenes for your faction. Increase loyalty to your faction by 1 in a random enemy-controlled Settlement. |
| 2 | **Biting Satire** | A playwright in a random Settlement you control publishes a sharp work criticizing your faction. Reduce loyalty to your faction by 1 and increase Unrest by 2 in that Settlement. |
| 3 | **Specialist Joins** | A specialist NPC (created by the GM) approaches your faction with an offer of support. No recruitment cost; upkeep begins next Turn. |
| 4 | **Feast Day Goodwill** | A local festival creates unexpected warmth toward your faction. Increase loyalty to your faction by 1 in a random friendly Settlement. |
| 5 | **Tax Protest** | Citizens in a random Settlement you control demonstrate against current conditions. Increase Unrest by 1 in that Settlement. |
| 6 | **Religious Endorsement** | A respected local religious figure publicly endorses your faction. Increase loyalty to your faction by 1 in all Settlements in a random Province you control. |
| 7 | **Refugee Crisis** | A wave of displaced people arrives in a Settlement you control. Increase Unrest by 1 and reduce Economy by 1 for 2 Turns; increase loyalty to your faction by 1 (refugees are grateful). |
| 8 | **Celebrity Defection** | A notable public figure who previously supported the enemy publicly switches allegiance. Reduce loyalty to the enemy faction by 2 in all Settlements of a random Province. |
| 9 | **Diplomatic Incident** | A misunderstanding sours relations with a neutral party. Reduce loyalty to your faction by 1 in all Settlements of a random neutral Province. |
| 10 | **Public Demonstration** | Citizens of a random Settlement openly demonstrate in your faction's support. Increase loyalty to your faction by 1 and reduce Unrest by 1 in that Settlement. |
| 11 | **Trade Disruption** | War conditions disrupt commerce in a random Settlement you control. Reduce Economy by 1 for 2 Turns. |
| 12 | **Neutral Merchant** | A wealthy merchant offers financing in exchange for future trade rights. Gain 1d6+2 RP; reduce Economy by 1 in a Settlement of your choice for 2 Turns. |
| 13 | **Rumor of Defeat** | Exaggerated reports of a recent setback spread among the civilian population. Reduce loyalty to your faction by 1 in all Settlements of a random Province you control. |
