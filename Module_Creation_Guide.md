# D&D ADVENTURE MODULE CREATION GUIDE
## A Process Reference for Building Original 5e Modules

*Based on the Terminus Pax development process. Examples throughout draw from that campaign.*

---

# OVERVIEW

## The Three-Document Model

A complete adventure module is built across three documents, written in this order:

1. **The Design Document** — Your private creative blueprint. Written before anything else. Locks in premise, structure, tone, NPCs, endings, and the key question: *what do players not know?*

2. **The DM Guide** — The complete adventure. Expands every section of the Design Document into full content: world-building, chapter-by-chapter scenes, mechanical systems, stat blocks, tables.

3. **The Player's Guide** — The player-facing document. Draws selectively from the DM Guide, removes secrets, and rewrites everything from the perspective of a native character. Adds custom mechanical content (races, subclasses, backgrounds) not present in the DM Guide.

## Why This Order

The Design Document answers the hard questions first, so the DM Guide doesn't have to solve them mid-draft. The Player's Guide comes last because it can only be written accurately after the full setting exists — you need to know what is true before you can decide what characters believe.

**The most important design principle:** Write your endings before you write your chapters. Knowing the 2–4 ways the adventure can resolve shapes every scene that leads to them. Stories without defined endings drift. Terminus Pax has four distinct possible endings tied to faction standings — those were designed before Chapter 1 was written.

## The Epistemic Divide

The DM Guide and Player's Guide are not the same document in two forms. They are written from fundamentally different positions:

- The DM Guide is omniscient. It knows everything, including what the players will never know unless they discover it.
- The Player's Guide is epistemically limited. It contains what characters would know as natives of the setting — which is incomplete, sometimes wrong, and deliberately so.

This distinction shapes not just content but voice. The DM Guide can state facts plainly. The Player's Guide presents facts as character belief, observation, and rumor.

---

# STEP 1 — THE DESIGN DOCUMENT

## Purpose

The Design Document is a master creative blueprint written before any adventure content. It locks in tone, premise, structure, and key creative decisions so the DM Guide has a stable foundation to expand from. It is DM-only and never shared with players.

Think of it less as a document and more as a conversation you're having with yourself before the writing begins: *What is this adventure actually about? What is the thing characters don't know that they need to find out? How can it end?*

## Required Sections

### Adventure Overview
A brief spec sheet. Include:
- **System:** D&D 5e (specify 2014 or 2024 ruleset)
- **Level Range:** e.g., Levels 1–15 across 9 chapters
- **Structure:** Number of chapters, number of acts
- **Tone:** 1–2 sentences. This guides all prose choices downstream. (*Terminus Pax: philosophical and mysterious, in the Planescape tradition*)
- **Player Character Type:** Who are the PCs in relation to the setting? Native inhabitants? Outsiders? This determines the Player's Guide's entire voice.

### Central Premise
The core secret or dramatic engine of the adventure — what is really going on beneath the surface the players see. Write it plainly. This is the answer to "what is the adventure about at its deepest level?"

*Terminus Pax example: The Pax's thousand years of stability is maintained by enslaved Anarchs — powerful chaos-shapers — kept imprisoned in arcane machines beneath the Sovereign. The realm's rulers have done this for a millennium. The realm is now failing because the machines are degrading and the Slaadi have figured out why.*

Define what players do not know at the start. This is as important as the premise itself — the shape of player ignorance determines the shape of the investigation.

### The World
Physical description of the setting. Include:
- The central location and what makes it distinctive
- Major geographical features (regions, landmarks, the hub settlement)
- The crisis or instability — the environmental or political problem that is visibly worsening
- What the setting looks like to a casual observer vs. what is actually happening

### The Antagonists
One entry per major antagonist. Include:
- Who they are and what they want
- What methods they use (misinformation? direct force? manipulation?)
- Their arc across the adventure — how do they enter, escalate, and resolve?
- Whether they are irredeemably villainous or morally complex (both are valid; decide in advance)

*Terminus Pax has three antagonist tiers: the Autarchs (desperate preservers who made a terrible choice), Vraakon the Ascendant (mid-campaign military threat), and Thantarnax the Unraveler (final antagonist, ancient, patient, with a legitimate grievance).*

### Key NPCs
A table. At minimum: name, pronouns, role, chapter of first appearance, one-sentence arc. Name every major NPC before you begin writing — this prevents drift and ensures consistency across a long document.

| Name | Pronouns | Role | First Appears | Arc |
|---|---|---|---|---|
| Example | he/him | Foundation Scholar; reluctant truth-teller | Chapter 1 | His conditioned loyalty cracks under the weight of what he witnesses |

### Adventure Structure
Act-by-act breakdown, then chapter list. For each chapter: title, level range, one-sentence summary of what happens and what players discover.

**Acts provide dramatic shape. Chapters provide pacing.**

*Three-act structure standard:*
- *Act I: Introduction and escalation (Chapters 1–2, Levels 1–4)*
- *Act II: Complication and revelation (Chapters 3–5, Levels 4–9)*
- *Act III: Confrontation and resolution (Chapters 6–9, Levels 9–15)*

### Possible Endings
Define 2–4 distinct outcomes. For each, specify: what player choices lead to it, what faction standings are required, and what the outcome means for the setting and its inhabitants. Endings that are purely good or bad are less interesting than endings that involve genuine trade-offs.

This is the most important section to write early. It answers the question: *what are players actually working toward, and does their agency matter?*

| Ending | How It's Reached | Outcome |
|---|---|---|
| Example: Reform | High standing with key institution; truth revealed through official channels | The system changes from within; slow and incomplete, but the enslaved are freed |

### Key Mechanics to Design
A checklist of systems that must be built before writing chapters. Identify:
- Any setting-specific movement or navigation rules
- Environmental hazard mechanics
- Faction relationship tracking (if using)
- Optional PC mechanics tied to setting abilities
- The multiple-endings framework

### Institutions and Factions
Who holds power in this setting, who challenges it, and what groups are accessible to player characters. For each:
- Public face (what everyone knows)
- Hidden truth (DM only)
- Relationship to the central premise

### Calendar and Holidays
Optional but useful if the adventure is tied to a specific in-world event. If the adventure has a time-pressure hook (a millennium celebration, a festival, a scheduled event), define it here.

### Documents to Create
A simple checklist so you know what you're building:
- [ ] DM Guide
- [ ] Player's Guide

---

## Design Document Format

- Markdown H1/H2/H3
- Prose for narrative/descriptive sections
- Tables for data-heavy sections (NPCs, factions, endings, mechanics, holidays)
- Bold for keywords and proper names on first use

---

# STEP 2 — THE DM GUIDE

## Purpose

The complete adventure, for the DM's eyes only. The DM Guide expands every section of the Design Document into full, usable content: detailed world-building, scene-by-scene chapter content, mechanical systems, stat blocks, and reference tables. It is the authoritative source. The Player's Guide draws from it.

---

## Document Structure

### Front Matter

**Title block:**
```
# CAMPAIGN TITLE
## Dungeon Master's Guide

*A D&D 5th Edition adventure for characters of levels X–Y*
```

**About This Adventure** — 2–3 paragraphs covering: the setting, the central premise (stated plainly for the DM), the two or three major antagonists, and a statement about player agency. This is where you frame the adventure's dramatic shape for the DM before they read anything else.

**How to Use This Guide** — Brief navigation aid. Name the four major sections of the document (The Realm, Running the Adventure, Chapters, Appendices) and describe what each contains in 1–2 sentences.

**Adventure Synopsis** — One paragraph per act (3–4 sentences each). What happens, what players discover, what changes.

**Themes and Tone** — 1 paragraph. What distinguishes this adventure's emotional and philosophical texture? What should the DM be reaching for in every scene? (*Terminus Pax: the feeling of living inside a comfortable lie that is starting to show its seams*)

**Adjusting for Your Party** — Practical guidance on: scaling encounters, handling parties that rush or stall, optional content that can be added or cut, what to do if players skip a key scene.

---

### The Realm

The world-building section. Written with full DM knowledge; sections containing secrets are labeled accordingly.

**The Central Location**
- Physical description: geography, major features, what makes it distinctive
- The Crisis: what is visibly going wrong, how it manifests, how fast it is accelerating
- Regions: 5–7 distinct areas, each with terrain, culture, main settlement, relationship to the crisis

**The Hub/Capital**
- Physical description: layout, architecture, feel
- Districts and key locations: 6–10 significant places the adventure will use
- What daily life looks like here

**The Power Structure**
- Who rules, how they present themselves publicly
- How they are accessed (formal channels, ceremonies, etc.)
- `### The Dark Secret (DM Only)` — what is actually going on; the truth behind the public face

**The Primary Institution**
- Public face: what citizens believe about it
- Recruitment, structure, public roles
- `### The Dark Truth (DM Only)` — what the institution conceals

**Key Factions**
One entry per faction. Include: description of the faction, its presence in the setting, its relationship to PCs, its attitude toward the central crisis, and what it wants. Cover internal factions, external factions, and any planar or outside groups.

**Key NPCs**
One H3 per NPC. Include:
- Physical appearance
- Personality and mannerisms
- Role in the adventure (how they're introduced, when they become important)
- Secrets or hidden motivations
- Reference to stat block in Appendix B (if they're a combatant)

---

### Running the Adventure

The mechanical and narrative infrastructure section. Write this before the chapters.

**Milestone Leveling**
When characters level up. Tie to chapter completion and specific plot beats rather than XP. List each milestone explicitly: *"Characters reach level X after completing [event]."*

**The Faction Relationship Tracker**
If the adventure uses faction mechanics:
- Starting standings table (each faction's initial disposition toward the PCs)
- How standings change (specific actions that raise or lower standing)
- How standings gate ending availability
- A simple tracking sheet or note format

**Setting-Specific Mechanics**
Any rules unique to this adventure's environment. Examples: navigation rules in planar or unusual terrain, environmental hazard tables, unique conditions. Write each as a named subsystem with full mechanical text.

**Optional PC Mechanics**
If the setting has abilities specific to certain character types (e.g., innate powers tied to the setting's nature), describe them here. Label as optional and explain how to introduce them.

**Managing the Revelation of Secrets**
Guidance on pacing. When should the central truth emerge? What triggers it? What happens to the NPCs the players trust when it does? This section gives DMs the tools to handle the story's emotional climax.

**Managing Multiple Endings**
A decision tree or reference table mapping player choices and faction standings to ending availability. The DM needs to be able to track this across sessions without re-reading the chapter text.

---

### Chapters

One H2 per chapter. Each chapter follows this structure:

#### Chapter N: [Title] *(Levels X–Y)*

**`### Chapter Summary`**
What happens in this chapter, what players discover, what changes. 1–2 paragraphs. Include the level range and name the major beats.

**`### Scene 1: [Name]`** (repeat for 3–5 scenes)

Each scene contains:

1. **Scene overview** — 1 paragraph. Where, when, who is present, what is at stake.

2. **Read-aloud text** — What players see, hear, and experience. Written to be read aloud or paraphrased. Use blockquote format:
```
> *The market stretches along both banks of the river, loud with the sounds of a city that has been doing this for a thousand years. Somewhere nearby, a man in a black robe is haranguing foot traffic from a corner. Nobody seems particularly bothered.*
```
   - Present tense
   - Sensory and atmospheric; avoid stating conclusions characters haven't reached
   - Length varies: one sentence to several paragraphs depending on scene

3. **DM notes** — *Italicized.* Practical guidance on running the scene: NPC behavior and motivations, likely divergences and how to handle them, skill check DCs, conditional outcomes. Name specific NPCs and what they do. Address "if the party does X instead of Y."

4. **Encounter information** (if the scene includes combat or a structured challenge):
   - Creature types and stat block references (Appendix A)
   - Tactics and priorities
   - Terrain features that affect the encounter
   - What happens if the PCs win, flee, or lose

5. **Investigation hooks / Skill checks** — DCs listed inline. If the scene has discoverable information, specify: what is found, at what DC, and what it means.

**`### Chapter N Encounters`** *(optional)*
Consolidated encounter statistics for chapters with multiple combat scenes. Useful for chapters where creatures recur or travel encounters are likely.

**`### Chapter N Conclusion`**
Leveling milestone (if applicable) and transition to the next chapter. 1–2 sentences.

---

### Appendices

#### Appendix A: Monster Stat Blocks
All new or custom creatures. Use standard 5e stat block format:

```
## Creature Name
*Size Type (subtype), alignment*

**Armor Class** X (source) | **Hit Points** X (XdY+Z) | **Speed** X ft.

| STR | DEX | CON | INT | WIS | CHA |
|-----|-----|-----|-----|-----|-----|
| X (+X) | X (+X) | X (+X) | X (+X) | X (+X) | X (+X) |

**Saving Throws** ...
**Skills** ...
**Damage Resistances** ...
**Damage Immunities** ...
**Condition Immunities** ...
**Senses** darkvision X ft., passive Perception X
**Languages** ...
**Challenge** X (X,XXX XP)

---

**Trait Name.** Trait description.

**Spellcasting.** The creature is a Xth-level spellcaster. Its spellcasting ability is [Ability] (spell save DC X, +X to hit with spell attacks). It has the following spells prepared: [spell list]

#### Actions

**Multiattack.** The creature makes X attacks: ...

**Attack Name.** *Melee/Ranged Weapon Attack:* +X to hit, reach/range X ft., one target. *Hit:* X (XdY+Z) damage type damage. [Additional effect if any.]

#### Legendary Actions

The creature can take X legendary actions, choosing from the options below. Only one legendary action option can be used at a time, and only at the end of another creature's turn. Spent legendary actions are regained at the start of each turn.

**Option Name.** Description.
**Option Name (Costs 2 Actions).** Description.
```

#### Appendix B: NPC Stat Blocks
Combatant NPCs. Same format as Appendix A. Include only NPCs the party is likely to fight; social NPCs do not need stat blocks.

#### Appendix C: Magic Items and Treasures
Three subsections:

**Setting-Specific Items** — Custom magic items unique to the adventure:
```
### Item Name
*Wondrous item, rarity (requires attunement by [condition] if applicable)*

One sentence describing appearance. Mechanical effects, including charges, recharge conditions, saving throw DCs, and durations.

*Where/how this item is obtained in the adventure.*
```

**Selected SRD Items** — A table of standard items appropriate to the adventure, with rarity and chapter found:

| Item | Rarity | Found In |
|---|---|---|
| Example Item | Uncommon | Chapter 3, Scene 2 |

**Custom Spells** — Any new spells introduced by the adventure:
```
### Spell Name
*Xth-level [school]*

**Casting Time:** 1 action · **Range:** X feet · **Components:** V, S, M (description) · **Duration:** Concentration, up to X minutes

Description of effect. Mechanical text including saving throws, damage, and conditions.
```

#### Appendix D: Random Tables
Four standard tables; add more as needed.

**Table 1: Environmental Hazards** — What happens when characters are in the adventure's distinctive dangerous environment. d20 table. Results should range from inconvenient to severe, with a few results that are merely atmospheric.

```
| d20 | Effect |
|-----|--------|
| 1–5 | Mild atmospheric effect (descriptive only) |
| 6–10 | Minor inconvenience (DC X save or [minor effect]) |
| 11–15 | Significant hazard (damage or condition) |
| 16–19 | Severe hazard (significant damage, difficult terrain, or separation) |
| 20 | Extreme event (requires immediate party response) |
```

**Table 2: Random Encounters by Region** — Subtables for each major region. d6 or d8. Roll once per travel day or hour depending on region danger level.

**Table 3: NPC Personality Traits** — For improvising unnamed NPCs. d10 table. Useful for frontier or wilderness encounters where the DM needs a quick personality hook.

**Table 4: Rumors** — In-setting rumors characters might hear. Use in taverns, market scenes, or investigation sequences. Include a mix of: true rumors, false rumors, rumors that are partially true, and rumors that point toward the central mystery. Format as character speech: *"I heard that..."*

---

# STEP 3 — THE PLAYER'S GUIDE

## Purpose

The player-facing document. It contains everything a native character would know about the setting — and nothing else. No DM secrets. Some information is deliberately framed as uncertain, incomplete, or wrong, because characters are not omniscient. The guide's opening explicitly tells players this.

The Player's Guide is not a summary of the DM Guide. It is a parallel document written from a different position: not what is true, but what characters believe.

---

## Document Structure

### Title and Opening Note

```
# CAMPAIGN TITLE
## Player's Guide to [the Setting]

*A setting guide for players in the [Campaign Name] campaign*

---

> **A note to players:** This guide contains everything your character would know as a native of [the Setting]. It does not contain secrets. Some things described here are incomplete or partly wrong — that is intentional, because your character's knowledge is also incomplete and partly wrong. You will learn more as you play.

---
```

The opening blockquote is essential. It establishes the epistemological contract with players: this is character knowledge, not truth. This single framing device makes players appropriately uncertain about the information they receive, which is the right emotional register for an adventure built on revelation.

---

### Welcome to the Realm

**[The Setting's Distinctive Quality]**
Introduce what makes this setting remarkable — the central thing that distinguishes it from any other place. Frame it as something characters have grown up with and take for granted. Then introduce the tension: something is changing. End with a hint of the crisis, framed as characters experience it (rumor, visible symptoms, official explanations that feel thin).

*Terminus Pax example: A thousand years of impossible stability in a plane of chaos. Citizens grew up taking this for granted. Now the edges are fraying. The official explanation is "known Slaadi behavioral variance." Most citizens accept this.*

**Life in [the Setting]**
Daily life, population, social structures. What do ordinary people do? What institutions do they belong to? What does the hub look like from the inside? Include:
- Population figures and rough distribution
- Social backbone (guilds, religious orders, civic organizations)
- Three "daily life" entries for distinct areas: hub city, productive interior, frontier/edge

---

### The World Around You

**Geography**
Physical regions of the setting. 5–7 entries. Each region gets: terrain description, economy and culture, relationship to the crisis, main settlement (name + population + one-sentence description).

**[The Hub/Capital]**
Architecture, feel, and key landmarks. 6–8 landmarks characters would know by name. Write this with genuine affection — players need to care about this place before it is threatened.

**[The Power Structure]**
Who rules, how they're perceived, how they're accessed. Frame what is known (the public face) and what is simply unknown (the mystery). Do not reveal the secret. The gap between what citizens believe and what is actually happening is the adventure's engine — the Player's Guide should make that gap feel real rather than explaining it.

**[The Edge/Crisis]**
Whatever is going wrong. Describe it as characters experience it: visible symptoms, rumors, official explanations. Include a section on what characters *do not know* — named explicitly. This is unusual in a player document and very effective. It signals that the characters' ignorance is meaningful, not accidental.

**[The Outside]**
What exists beyond the setting's borders. Common knowledge only. What do characters know about the wider world, the dangers beyond the edge, the factions that exist in the spaces between?

---

### Society and Culture

One H2 per entry. 5 entries standard.

**The Primary Institution**
The most trusted and central organization. Write its public face warmly — citizens should feel genuine attachment to it. Include: what it does publicly, how it recruits, what its public reputation is. Withhold the dark truth entirely. Let the warmth be real so the eventual revelation is painful.

**The Primary Belief System**
Religion, philosophy, or tradition most citizens follow. Describe it as an insider would: not "this religion believes X" but "this is what people in this community mean when they talk about what matters." Include holiday observations.

**The Fringe Voice**
A tolerated dissident group. Make them sympathetic and not ridiculous. The fringe voice should be saying something that turns out to be true — their credibility should be rising as the adventure begins. Citizens should be able to both dismiss them and feel a little uneasy doing it.

**The Practical Organization**
A guild, company, or network useful to adventurers. Pragmatic rather than ideological. This is the faction players will work with most directly for practical tasks. Give it a memorable leader.

**Unusual Inhabitants** *(optional)*
If the setting has unusual groups with full citizen status — constructs, planar immigrants, creatures not typical of the setting's geography — introduce them here. Connect them to institutions where possible.

---

### Factions / Outside Groups

For planar settings, label this **Factions of the Planes**. For other settings, use **Major Outside Factions** or similar.

4–6 factions. Each entry:
- Description of the faction's philosophy and presence in the setting
- How they relate to the central premise (do they threaten the setting? benefit from it? watch it curiously?)
- **Membership:** A note for PC members — how a member of this faction thinks and what they're committed to. This is a roleplay hook, not a mechanical benefit.

---

### Character Creation

#### Races

Open with: *"All officially published 5e races are available to characters native to [the Setting]. [The Setting] has been drawing people from across [wherever] for [however long]; there is no 'unusual' race here, only more and less common ones."*

Then: rarity tiers (very common → rare) with examples at each tier.

For any custom races specific to the setting, add a full entry below the tiers:

**Custom Race Entry Format:**
1. **Prose lore** — 4 paragraphs:
   - *Origin:* Where do these beings come from? What is their history in the setting?
   - *Physical description:* What do they look like? What is distinctive? What varies between individuals?
   - *Social position:* How do they fit into the setting? How are they treated? What relationships do they have with institutions?
   - *Personality, gender, names:* How do they relate to biological concepts? How do names work?
2. **Racial traits block** — Standard 5e format: Ability Score Increase, Age, Alignment, Size, Speed, named traits with mechanical text, Languages.

#### Classes

One H2 per class. Each entry:
- **2–3 paragraphs** placing the class in the setting's culture: what role do they fill? What institutions do they interact with? What does the class's particular skill set mean in this specific world?
- **One custom subclass** *(optional — include only if custom subclasses are being designed for this module)*:
  - H3 heading: `### [Subclass Name]`
  - Flavor tagline in italics: `*Short evocative description*`
  - Feature list by level, following the subclass's level progression for the class
  - Each feature: bold name + level in parentheses, then mechanical text
  - Mechanical design principle: **custom features should reinforce setting themes, not just add power**

#### Custom Backgrounds

3 setting-specific backgrounds. Each entry:

```
### Background Name

[One paragraph of prose: who is this character, what did their life look like before the adventure,
what is their relationship to the setting's institutions, what is the narrative weight of this background?]

**Skill Proficiencies:** ...
**Tool Proficiencies:** ...
**Languages:** One of your choice
**Equipment:** ...

**Feature: [Feature Name].** [Mechanical text: what the feature does, when it applies, what the DM provides.]

*Suggested personality:* [1–2 sentences framing the character's emotional relationship to the adventure
they're about to enter — what they believe, what they stand to lose, what they might become.]
```

The suggested personality line is the most important part of a background entry. It is the point of contact between the player's character and the adventure's themes.

#### Character Hooks

5–6 open-ended questions for players to answer. These should:
- Connect the character to the setting's institutions (who did you give to the Foundation? who do you know in the Guild?)
- Surface the character's relationship to the central secret (do you have the relevant ability? do you believe the official story?)
- Establish something the character has to lose
- End with a philosophical question — the one the adventure is actually asking

*These answers are shared with the DM. They become plot-relevant.*

---

### What Your Character Knows

**Common Knowledge**
5–8 bullet points. The things every native character would know without question. This is the player's baseline — the assumed knowledge that needs no in-character explanation.

**The Rumors Table**
A d12 table of rumors characters might have heard before play begins. Rules: 2 of the 3 rumors a player rolls are true in some sense; 1 is false. Players don't know which is which.

Format: rumors in quoted character speech (*"I heard that..."*). Mix categories:
- Institutional anomalies (the powerful acting strangely)
- Environmental signs (infrastructure, resources, the crisis)
- Personal mysteries (individuals behaving oddly)
- Factional tensions (groups in conflict or contact)

Every rumor should gesture toward the adventure's themes without resolving them.

---

### Closing

```
---

*Setting guide compiled: [In-world date or event]*
*For player use only — no DM-only content is present in this document*
```

---

# TONE AND VOICE

## Setting Sections (Player's Guide)

Write from the perspective of an intelligent, observant native — someone who finds their world genuinely interesting and knows it well. Resist over-explaining. Trust the reader to infer.

Use understated prose for unsettling details. The most effective technique is to state something strange matter-of-factly and then immediately note that no one finds it troubling: *"Most citizens do not find this troubling enough to discuss."* This signals wrongness more effectively than dramatic emphasis.

Frame uncertainty as thematic rather than accidental. When you don't want to reveal something, don't avoid it — address the gap directly and acknowledge that the character doesn't know either.

Economy of language. Every sentence should earn its place. Long paragraphs are fine when the content warrants them; padding is not.

## Mechanical Sections (Classes, Backgrounds, Stat Blocks)

State rules completely and without ambiguity. Specify: the trigger, the effect, the duration, the DC (if any), the recharge condition (if any). Don't leave anything to interpretation.

Lead with flavor before mechanics in class and subclass write-ups. Players should understand what a character with this subclass is and feels like before they understand what the features do.

Design principle: **custom mechanics should reinforce setting themes, not just add power.** A subclass for a setting about free will should feel different to play than a subclass for a setting about survival. The mechanics are an argument about the setting.

## DM Guidance (Notes, Chapter Framing)

Direct, practical, and anticipatory. Address what DMs actually need to know in the moment, not just what is true in general.

Address likely divergences explicitly: *"If the party skips this scene,"* *"If players are suspicious of X,"* *"If the party sides with Y instead."* DMs need conditional logic, not just description.

Name NPC motivations explicitly so DMs can improvise consistently. A DM who knows that an NPC *"will help the party, but only if they don't ask about the third sub-order — that question panics him and he deflects"* can handle any scene with that NPC. A DM who only knows the NPC is friendly cannot.

---

# FORMATTING REFERENCE

| Element | Format |
|---|---|
| Document title | `# ALL CAPS` |
| Document subtitle | `## Title Case` |
| Major section divider | `# ALL CAPS` |
| Section heading | `## Title Case` |
| Subsection heading | `### Title Case` |
| Sub-subsection | `#### Title Case` |
| Player-facing blockquote | `>` |
| Read-aloud text | `> *italicized*` |
| DM notes | `*Italicized inline*` |
| DM-only section | `### Section Name (DM Only)` |
| Spell, item, subclass names | `*italics*` |
| NPC, place, faction names | `**bold**` on first use |
| Mechanical keywords | `**bold**` |
| Tables | Markdown pipe tables |
| Stat block ability scores | Pipe table (6 columns) |
| Stat block actions section | `#### Actions` |
| Stat block legendary actions | `#### Legendary Actions` |

---

# THE THREE-DOCUMENT RELATIONSHIP

```
Design Document
    │
    │  Expands every element into full content
    ▼
DM Guide
    │
    │  Selectively draws from; rewrites from character perspective;
    │  adds player-facing mechanical content
    ▼
Player's Guide
```

**Design Document → DM Guide:**
Every NPC in the Design Document becomes a full entry with personality, secrets, and stat block. Every faction becomes a full description with DM knowledge. Every chapter outline becomes scene-by-scene content. Every mechanic listed gets fully designed.

**DM Guide → Player's Guide:**
- Setting geography → rewritten as character knowledge (partial, impressionistic, sometimes wrong)
- Factions → player-accessible descriptions; secrets removed
- NPCs → surface-level impressions only (how they appear, not what they hide)
- Institutions → public face only; dark truths withheld entirely
- Adventure hooks → transformed into character backgrounds and character hooks

New content added in the Player's Guide that does not appear in the DM Guide:
- Custom subclasses (mechanical content designed for players)
- Custom race entries (if applicable)
- Custom backgrounds (with mechanical features)
- The Rumors Table
- Character Hooks

**The key principle:** The Player's Guide is not a shorter version of the DM Guide. It is a document written from a fundamentally different epistemic position. The DM Guide states facts. The Player's Guide presents beliefs. The gap between those two documents is the adventure.

---

*Module Creation Guide compiled: March 2026*
*Reference document — for DM use when designing new adventure modules*
