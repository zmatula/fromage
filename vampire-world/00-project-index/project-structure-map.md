# Project Structure Map

Complete mapping of the vampire-world project: what's where, what it does, and how it connects.

---

## Directory Overview

```
vampire-world/
├── 00-project-index/     # Navigation and tracking
├── 01-core-framework/    # Foundational concepts
├── 02-timeline/          # History and events
├── 03-cultures/          # Races and societies
├── 04-factions/          # Political entities
├── 05-geography/         # Places and locations
├── 06-characters/        # People
├── 07-artifacts-magic/   # Items and systems
├── 08-secrets/           # Hidden information
├── 09-plot-architecture/ # Story structure
├── 10-style-guide/       # Writing guidance
├── 11-validation/        # Consistency checking
└── 12-grrm-review/       # Review and enrichment
```

---

## 00-project-index/ - Navigation Hub

| File | Purpose | Key Connections |
|------|---------|-----------------|
| master-index.md | Project table of contents | Links to everything |
| session-log.md | Development history | Tracks changes |
| next-steps.md | Outstanding tasks | Guides work |

**Use**: Start here. Find anything.

---

## 01-core-framework/ - Foundation

| File | Purpose | Key Connections |
|------|---------|-----------------|
| premise-constraints.md | What the world IS | → Everything must align |
| thematic-pillars.md | Core themes | → Plot, characters must support |
| core-mysteries.md | Central questions | → Secrets, plot revelations |

**Use**: Check here when adding anything. Does it fit?

---

## 02-timeline/ - History

### Master Files

| File | Purpose | Key Connections |
|------|---------|-----------------|
| master-timeline.md | Complete chronology Year -1200 to 1200 | → All events reference this |
| vampire-factions.md | The three covenants | → Collapse, artifacts, secrets |
| collapse-event.md | Day 0 in detail | → Everything after |
| collapse-scenes.md | Dramatized collapse | → Style guide |
| year-812-discovery.md | First stasis vampire found | → Seven's precedent |
| historical-figures.md | Named people who shaped eras | → Cultural memory, conflicts |

### era-breakdowns/ - Detailed Periods

| File | Period | Key Events |
|------|--------|------------|
| era-pre-vampire.md | Year -1200 to -1000 | Vampire rise, unification |
| era-rise.md | Year -1000 to -500 | Conquest, covenants form |
| era-golden-age.md | Year -500 to -100 | Peak and rot |
| era-final-century.md | Year -100 to 0 | Collapse approach |
| era-immediate-aftermath.md | Year 0 to 50 | Liberation chaos |
| immediate-aftermath-horror.md | Year 0-10 detail | The 40 million dead |
| era-dark-ages.md | Year 50 to 300 | Knowledge loss |
| era-warring-kingdoms.md | Year 300 to 700 | Conflicts |
| era-consolidation.md | Year 700 to 1100 | Empire formation |
| era-recent-past.md | Year 1100 to 1200 | Current tensions |

**Additional Scene Files**: golden-age-scenes.md, pre-vampire-scenes.md, great-gathering.md, technology-loss-scenes.md

**Interactions**:
- Timeline → provides context for everything
- Historical figures → bring timeline to life
- Cultural memory → different races remember differently

---

## 03-cultures/ - Peoples and Societies

### Main Files

| File | Purpose | Key Connections |
|------|---------|-----------------|
| cultural-memory-matrix.md | How races remember history | → Contested histories |
| cultural-conflicts.md | Inter-race tensions | → Plot conflicts |
| contested-histories.md | Specific disagreements | → Character arguments |
| cultural-texture.md | Songs, sayings, customs | → Dialogue, scenes |

### races/ - Individual Cultures

| File | Race | Key Aspects |
|------|------|-------------|
| humans.md | Humans | Dominant, varied, historical |
| elves.md | Elves | Isolated, secretive, long-lived |
| elven-deep-dive.md | Elves detailed | Politics, factions, Thandril |
| dwarves.md | Dwarves | Craftsmen, stubborn, Forge of Souls |
| goblins.md | Goblins | Modified by vampires, persecuted |
| goblin-tragedy.md | Goblin history | What was done to them |
| vampires.md | Vampires | The fallen civilization |
| vampire-figures.md | Named vampires | Mordecai, Cassius, Selene, Velanna |

**Interactions**:
- Races → have different views on history (contested-histories)
- Cultural texture → used in dialogue and scene-setting
- Vampire figures → Seven's memories connect to them

---

## 04-factions/ - Political Entities

### Main Files

| File | Purpose |
|------|---------|
| faction-relationship-map.md | Who's allied, who's opposed |

### empires/ - Major Powers

| File | Faction | Current Crisis |
|------|---------|----------------|
| valdrian-empire.md | Valdris | Succession crisis |
| northern-dominion.md | Northern Kingdom | Expansion plans |
| maritime-republic.md | Maritime Republic | Coup aftermath |
| sanctified-states.md | Sanctified States | Persecution campaign |
| ironpeak-confederation.md | Dwarven holds | Isolationist |
| silverwood-domain.md | Elven territory | Closed borders |
| broken-lands.md | Goblin territory | Contained, angry |

### secret-societies/ - Hidden Powers

| File | Society | Stance on Seven |
|------|---------|-----------------|
| inheritors.md | Inheritors of Blood | Study/preserve |
| order-of-dawn.md | Order of Dawn | Destroy |
| veil-keepers.md | Veil Keepers | Expose |
| origin-stories.md | Founding narratives | How they began, compromised |

**Interactions**:
- Empires → present-day crises (09-plot-architecture)
- Secret societies → compete for Seven, artifacts
- Faction relationships → drive plot conflicts

---

## 05-geography/ - Places

### Main Files

| File | Purpose |
|------|---------|
| world-map-description.md | Overall layout |
| relic-distribution.md | Where artifacts are |
| location-character.md | Sensory details, personality |

### regions/ - Major Areas

| File | Region | Key Features |
|------|--------|--------------|
| valdrian-heartlands.md | Valdris core | Cities, agriculture |
| northern-highlands.md | Northern Kingdom | Cold, military |
| maritime-coast.md | Republic territory | Ports, trade |
| sanctified-lands.md | Church territory | Religious |
| ironpeak-mountains.md | Dwarven holds | Underground |
| silverwood.md | Elven forest | Closed |
| broken-lands.md | Goblin territory | Dangerous |
| the-scar.md | Collapse site | Dimensional breach |
| border-marches.md | Contested territory | Tension |

### vampire-ruins/ - Key Sites

| File | Site | Significance |
|------|------|--------------|
| vel-thoras.md | Where Seven wakes | Protagonist origin |
| neth-korath.md | Collapse site | The Scar |
| sel-naroth.md | Northern site | Year 812 discovery |
| vel-krath.md | Throne stronghold | Military site |
| minor-sites.md | Other ruins | Exploration targets |

**Interactions**:
- Ruins → contain artifacts, secrets
- Regions → control ruins, conflict over them
- Location character → makes scenes vivid

---

## 06-characters/ - People

### Main Files

| File | Purpose | Key Connections |
|------|---------|-----------------|
| protagonist.md | Vessel Seven | Central character |
| character-relationship-map.md | Who knows whom | Plot connections |
| pov-character-independence.md | Each POV's personal story | Arcs without Seven |

### major-characters/ - POV Characters

| File | Character | Role | Personal Crisis |
|------|-----------|------|-----------------|
| marcus-ashford.md | Marcus | Church scholar | Sister executed for heresy |
| kira-frost.md | Kira | Northern spy | Betrayed lover, he died |
| elara-goldstone.md | Elara | Maritime merchant | Searching for daughter |
| thandril-shadowleaf.md | Thandril | Elven agent | Ordered to let sister die |
| gritha-bloodsinger.md | Gritha | Goblin shaman | Son killed, has plague |
| vera-nighthollow.md | Vera | Inheritor leader | (needs enrichment) |

### supporting-cast/

| File | Purpose |
|------|---------|
| supporting-cast-registry.md | Secondary characters |

**Interactions**:
- POV independence → each has arc without Seven
- Character relationships → drive plot
- Connect to factions, secrets, crises

---

## 07-artifacts-magic/ - Items and Systems

| File | Purpose | Key Connections |
|------|---------|-----------------|
| magic-system.md | How magic works | → Limits, costs |
| magic-disagreements.md | Schools of thought | → Character conflicts |
| vampire-technology.md | What vampires made | → Artifacts, ruins |
| relic-registry.md | List of artifacts | → Plot items |
| artifact-histories.md | Major artifacts detailed | → Conflicts, quests |
| artifact-plot-connections.md | How artifacts drive story | → Plot architecture |

**Key Artifacts** (in artifact-histories.md):
- Crown of Seeing → Veil Keepers have it
- Forge of Souls → Dwarves sealed it
- Blood Archives → Split between factions
- Mind Codex → Contains Mordecai's mind
- Living Artifact → Possibly Vessel Eleven

**Interactions**:
- Artifacts → everyone fights over them
- Magic disagreements → drive scholarly/religious conflict
- Connect to economic framework (very valuable)

---

## 08-secrets/ - Hidden Information

| File | Purpose | Who Knows |
|------|---------|-----------|
| protagonist-true-history.md | Seven's real backstory | Reader only |
| vessel-seven-memories.md | Seven's 7 years awake | Seven (fragmented) |
| sanguine-vessels-registry.md | All 12 Vessels | Hidden in Vel'Thoras |
| discoverable-secrets.md | When characters learn what | Plot pacing |
| shadow-truths.md | Disputed facts | Reader knows truth |
| permanent-mysteries.md | Never resolved | Stays unknown |

**Interactions**:
- Secrets → revealed through plot
- Discoverable secrets → paces revelations
- Connect to artifacts, ruins, characters

---

## 09-plot-architecture/ - Story Structure

| File | Purpose | Key Connections |
|------|---------|-----------------|
| story-arcs.md | Main plot threads | → All characters |
| character-arcs.md | Individual journeys | → POV characters |
| intersection-points.md | Where stories meet | → Scene planning |
| consequence-chains.md | Cause and effect | → Stakes |
| present-day-crises.md | Year 1200 tensions | → Immediate conflict |
| economic-framework.md | Money and power | → Faction motivations |

**Present-Day Crises**:
- Valdrian succession → 4 claimants
- Maritime coup → Banks vs Stormwind
- Northern expansion → Aldric XII's plans
- Sanctified persecution → Church hunting everyone

**Interactions**:
- Crises → drive immediate plot
- Economics → explain faction behavior
- Arcs → track character development

---

## 10-style-guide/ - Writing Guidance

| File | Purpose |
|------|---------|
| grrm-writing-principles.md | Core GRRM approach |
| narrative-voice.md | Tone and POV |
| dialogue-guidelines.md | How characters speak |
| scene-construction.md | Building scenes |

**Interactions**:
- Apply to all written scenes
- Cultural texture → informs dialogue
- Character voices → distinct per person

---

## 11-validation/ - Consistency

| File | Purpose |
|------|---------|
| timeline-validator.md | Date/event checks |
| consistency-checks.md | Logic verification |
| character-tracker.md | Who knows what when |
| integration-tests.md | Cross-reference checks |

**Use**: Check work against these.

---

## 12-grrm-review/ - Reviews and Plans

| File | Purpose |
|------|---------|
| 00-comprehensive-review.md | Initial full review |
| 01-05 | Specific improvement plans |
| 06-10 | Implementation and validation |
| 11-pre-awakening-history-enrichment.md | First enrichment pass |
| 12-second-enrichment-plan.md | Second enrichment pass |

**Use**: Track what's been improved, what needs work.

---

## Key Interaction Patterns

### The Protagonist Web

```
protagonist.md (who Seven is)
    ↓
protagonist-true-history.md (real backstory)
    ↓
vessel-seven-memories.md (what he remembers)
    ↓
sanguine-vessels-registry.md (other Vessels)
    ↓
vampire-figures.md (Velanna, others)
    ↓
vel-thoras.md (where he wakes)
```

### The Conflict Web

```
present-day-crises.md (4 major crises)
    ↓
empires/ (who's fighting)
    ↓
secret-societies/ (hidden agendas)
    ↓
faction-relationship-map.md (alliances/enemies)
    ↓
pov-character-independence.md (personal stakes)
```

### The History Web

```
master-timeline.md (all events)
    ↓
era-breakdowns/ (detailed periods)
    ↓
historical-figures.md (people who shaped eras)
    ↓
contested-histories.md (disagreements)
    ↓
cultural-memory-matrix.md (racial perspectives)
```

### The Power Web

```
artifact-histories.md (what items exist)
    ↓
economic-framework.md (what they're worth)
    ↓
secret-societies/ (who wants them)
    ↓
empires/ (who controls them)
    ↓
magic-disagreements.md (how to use them)
```

---

## How to Use This Map

### When Writing a Scene

1. Check **location-character.md** for sensory details
2. Check **cultural-texture.md** for dialogue flavor
3. Check **character files** for voice and motivation
4. Check **present-day-crises.md** for background tension
5. Check **faction-relationship-map.md** for political context

### When Adding Content

1. Check **premise-constraints.md** - does it fit?
2. Check **master-timeline.md** - when does it happen?
3. Check **consistency-checks.md** - any contradictions?
4. Update **cross-references** in related files

### When Tracking a Character

1. Start with their **major-characters/** file
2. Check **pov-character-independence.md** for personal arc
3. Check **character-relationship-map.md** for connections
4. Check **faction** files for allegiances
5. Check **discoverable-secrets.md** for what they learn when

### When Resolving a Plot Point

1. Check **story-arcs.md** for thread status
2. Check **consequence-chains.md** for ripple effects
3. Check **intersection-points.md** for convergences
4. Update **character-tracker.md** for who knows what

---

## File Count Summary

| Directory | Files | Purpose |
|-----------|-------|---------|
| 00-project-index | 3 | Navigation |
| 01-core-framework | 3 | Foundation |
| 02-timeline | 18 | History |
| 03-cultures | 12 | Peoples |
| 04-factions | 12 | Powers |
| 05-geography | 15 | Places |
| 06-characters | 9 | People |
| 07-artifacts-magic | 6 | Items/Systems |
| 08-secrets | 6 | Hidden info |
| 09-plot-architecture | 6 | Structure |
| 10-style-guide | 4 | Writing |
| 11-validation | 4 | Checking |
| 12-grrm-review | 12 | Review |
| **Total** | **110** | |

---

## Quick Reference: "Where Do I Find...?"

| Topic | Primary File | Secondary Files |
|-------|--------------|-----------------|
| Seven's backstory | protagonist-true-history.md | vessel-seven-memories.md, sanguine-vessels-registry.md |
| Current political crisis | present-day-crises.md | empires/, faction-relationship-map.md |
| Specific artifact | artifact-histories.md | relic-registry.md |
| Race culture | races/ folder | cultural-memory-matrix.md, contested-histories.md |
| Historical event | master-timeline.md | era-breakdowns/, historical-figures.md |
| Secret society | secret-societies/ folder | origin-stories.md |
| Character motivation | major-characters/ folder | pov-character-independence.md |
| Location details | location-character.md | regions/, vampire-ruins/ |
| Magic rules | magic-system.md | magic-disagreements.md |
| What happens when | discoverable-secrets.md | story-arcs.md, consequence-chains.md |

---

*This project is a web, not a list. Everything connects. When you touch one file, you touch twenty. That's what makes the world feel real—no piece stands alone. Use this map to navigate. When lost, start at master-index.md and follow the threads.*
