# Historical Revision Implementation Plan

*Created: 2025-11-22*

## Overview

This plan organizes all historical revisions into a coherent implementation sequence. Changes are ordered to maintain consistency—earlier phases establish foundations that later phases build upon.

**Total Scope**: ~40,000-50,000 words of new/revised content across 15+ documents

---

## Phase 1: Foundation Layer (Do First)

These changes establish the base that all other revisions build upon.

### 1.1 Remove Shadow Truth Certainty

**Files to modify**:
- `08-secrets/shadow-truths.md`
- `02-timeline/collapse-event.md`

**Changes**:
1. Delete or rewrite all "What Actually Happened" sections
2. Replace with "Possible Truths (All Fit Evidence)"
3. Remove specific vampire survivor numbers
4. Change "Shadow Truth" headers to "Unresolved Questions"

**Template for revised events**:
```markdown
## The Collapse

### Possible Truths

**Possibility A: Sabotaged Experiment**
- Evidence for: [list]
- Evidence against: [list]
- Who benefits from this narrative: [faction]

**Possibility B: Multi-Causal Cascade**
- Evidence for: [list]
- Evidence against: [list]
- Who benefits from this narrative: [faction]

**Possibility C: Something Came Through**
- Evidence for: [list]
- Evidence against: [list]
- Who benefits from this narrative: [faction]

### What Cannot Be Known
- [List elements that are genuinely unresolvable]

### Contradictory Evidence
- [Evidence that supports A but contradicts B]
- [Evidence that supports B but contradicts C]
- [Evidence that contradicts ALL versions]
```

**Why first**: All subsequent historical content must fit within this ambiguity framework.

---

### 1.2 Establish Consequence Chain Template

**New file to create**:
- `02-timeline/consequence-tracking.md`

**Content**:
Create a tracking system for major events and their consequences across centuries.

**Template**:
```markdown
## Event: [Name] (Year X)

### Immediate Effects (0-10 years)
- [Effect 1]
- [Effect 2]

### Medium-Term Effects (10-100 years)
- [Effect 1] → leads to [Event Y]
- [Effect 2] → leads to [Event Z]

### Long-Term Effects (100+ years)
- [Effect 1] → still visible in Year 1200 as [manifestation]

### Knowledge/People Lost
- [Specific knowledge that died]
- [Lineages that ended]

### Power Shifts
- [Who gained]
- [Who lost]

### Cultural Memory
- Humans remember as: [version]
- Elves remember as: [version]
- Dwarves remember as: [version]
- Goblins remember as: [version]
```

**Why first**: This template ensures all subsequent historical additions include proper consequence chains.

---

## Phase 2: Pre-Vampire Foundation (Year -1200 to -1000)

Expand the pre-vampire era to support all "ancient tradition" claims.

### 2.1 Pre-Vampire Human Kingdoms

**File to modify**: `02-timeline/era-breakdowns/era-pre-vampire.md`

**Add**:

**Kingdom of Valdris**
- Ruling dynasty: House Aurelian (7 kings)
- Major wars: War of the Silver River (Year -1150), Coastal Conquest (Year -1080)
- Cultural achievements: Aurelian Code of Law, Great Temple of Valdris Prime
- Final king: Aldric III, who negotiated with first vampires

**Merchant Principalities**
- Named princes: Castellan of Portmere, Doge of Seahaven, Lord of the Narrow Strait
- Economic system: Trade leagues, banking houses
- Internal conflicts: The Coin Wars (Year -1100)
- How vampires conquered: Debt manipulation, not military force

**Holy Confederation**
- Religious structure: Council of Seven Flames
- Named High Priests: Solarius the Founder, Mara Lightbringer
- Theological disputes: The Dual Nature Heresy (Year -1120)
- How vampires conquered: Religious conversion of key priests

### 2.2 Pre-Vampire Elven Domains

**Add to same file**:

- Named councils: The Starlight Conclave, The Roothold Assembly
- Ruling families: House Silvermoon, House Thornweald
- The Elf-Dwarf Wars: Three specific conflicts with causes and outcomes
- Why elves allied with vampires: The Thornweald Betrayal—House Thornweald traded elven service for vampire magic to defeat House Silvermoon

### 2.3 Pre-Vampire Dwarven Holds

**Add**:
- Named holds: Ironpeak Prime, Deepforge, Crystalvein
- Thanes: Specific rulers with accomplishments
- The Succession Crisis of Year -1090: Three thanes claimed High King title
- Why dwarves accepted vampire rule: Vampires resolved succession crisis

### 2.4 Pre-Vampire Goblin Tribes

**Add**:
- Named tribes: Bloodmoon, Ashfang, Stoneclaw
- Shamanic traditions: What existed before vampires
- The Great Gathering (Year -1050): Last free goblin council
- How vampires conquered: Tribe-by-tribe, exploiting inter-tribal wars

**Deliverable**: Expanded `era-pre-vampire.md` from ~2,000 words to ~8,000 words

---

## Phase 3: Vampire Civilization Texture

Add individual stories and cultural content to make vampires feel real.

### 3.1 Named Vampire Figures

**File to modify**: `02-timeline/vampire-factions.md` and era documents

**Create profiles for 10 figures**:

1. **Vykros the Conqueror** (existing, expand)
   - Add 3 theories about his death
   - Name his children and their fates
   - His philosophy: "Unity Through Strength"

2. **Velanna of Mind** (existing, expand)
   - Her rivals within Mind Covenant
   - Her relationship with protagonist
   - Her writings on ethics

3. **Kael Shadowmend** (new)
   - Twilight philosopher, Year -400
   - Wrote "Meditations on Eternity"
   - Argued vampires had lost their purpose
   - Executed for sedition

4. **Serath the Artificer** (new)
   - Created the Crown of Seeing
   - Warned about Bloodweb dependency
   - Disappeared Year -200

5. **Lady Morrigan** (new)
   - Throne military commander
   - Conquered the Northern Marches
   - Loved a human slave—scandal
   - How she died in Final Century

6. **The Twins of Neth'Korath** (new)
   - Mind researchers
   - Created first Sanguine Vessel (failed)
   - Killed each other in argument about methods

7. **High Keeper Solindra** (new)
   - Twilight leader Year -100
   - Ordered sanctuary preparations
   - What she knew about coming collapse

8. **Mordecai the Reformer** (new)
   - Year -50 moderate
   - Proposed Blood Covenant with subject races
   - Assassinated by Throne

9. **Archon Vex** (new)
   - Throne leader in Final Century
   - Pushed for Ascension Experiment
   - His justification

10. **Nalissa the Witness** (new)
    - Survived collapse in minor facility
    - Her account (fragmentary) contradicts all official versions
    - Died Year 3, her testimony disputed

### 3.2 Vampire Cultural Content

**Add to era documents**:

**The Eternal Forms Movement** (Year -275)
- What it depicted: Frozen moments of perfect predation
- Key works: "The Last Heartbeat," "Red Dawn Over Valdris"
- Why controversial: Glorified feeding, criticized as decadent
- How current cultures misinterpret it

**Twilight Meditations**
- Actual content: Contemplation of immortality's burden
- Key concepts: "The Long Silence," "The Weight of Memory"
- How Silverwood elves preserved fragments
- Contradictions within the text

**The Pleasures of Eternity Movement**
- What it was: Pursuit of sensation to combat ennui
- Extremes it reached: Dangerous experiments with subject races
- The Scandal of Year -260: What happened
- Why Mind purged participants

### 3.3 Failed Reform Attempts

**Add to `era-final-century.md`**:

**The Blood Covenant Proposal** (Year -50)
- Proposed by: Mordecai the Reformer
- Terms: Subject races given citizenship, limited Bloodweb access
- Who supported: Mind minority, some Twilight
- Why it failed: Throne assassination + Mind internal coup
- Consequences: Final window for peaceful reform closed

**The Twilight Withdrawal** (Year -30)
- Proposed by: Twilight majority
- Terms: Twilight retreats to sanctuaries, leaves others to fate
- Who opposed: Twilight's own young members
- Outcome: Partial implementation—explains sanctuary preparations

**The Subject Race Rebellion Alliance** (Year -15)
- Proposed by: Underground leaders from all races
- Terms: Coordinated uprising on single day
- Why it failed: Infiltration by Mind agents
- Consequences: Mass executions, increased security

**Deliverable**: ~10,000 words of new vampire civilization content

---

## Phase 4: Dark Ages Expansion (Year 50-300)

The most critical expansion—triple this era's content.

### 4.1 Failed Kingdoms

**Add to `era-dark-ages.md`**:

**The Realm of Solace** (Year 60-180)
- Founded by: High Priestess Solara's successors
- Territory: Central plains
- Achievements: First post-collapse legal code
- Fall: Great Plague killed ruling family; civil war

**The Northern Confederation** (Year 80-220)
- Founded by: Alliance of warlords
- Territory: Northern Marches
- Achievements: First organized vampire ruin expeditions
- Fall: Internal betrayal; three-way succession war

**The Maritime League** (Year 100-280)
- Founded by: Merchant families
- Territory: Coastal cities
- Achievements: Restored trade routes
- Fall: Elven withdrawal from trade; economic collapse

**The Sanctified Realm** (Year 120-260)
- Founded by: Orthodox Church faction
- Territory: Holy Confederation lands
- Achievements: Preserved pre-vampire religious texts
- Fall: Church Schism; pragmatists seized capital

**The Goblin Resurgence** (Year 90-210)
- Founded by: United tribes under Shaman-King Vrok
- Territory: Broken Lands + border regions
- Achievements: Recovered blood magic traditions
- Fall: Vrok's death; tribal fragmentation + human counterattack

### 4.2 Great Plague Consequence Chain

**Add detailed section**:

**The Plague** (Year 168-175)
- Origin: Unknown—possibly vampire facility contamination
- Spread: Trade routes from Maritime League
- Death toll: 20-25% of human population, 15% of dwarves, 5% of elves, 30% of goblins

**Immediate Consequences** (Year 168-180)
- Realm of Solace: Royal family dies; three claimants
- Maritime League: Quarantine destroys trade; cities riot
- Northern Confederation: Blame falls on "vampire curse"; anti-relic faction rises
- Church: "Divine punishment" narrative takes hold
- Goblins: Lose most shamans; knowledge crisis

**Medium-Term Consequences** (Year 180-250)
- Power vacuum in central plains → warlord period
- Trade routes shift northward → Northern Confederation gains power
- Church's plague narrative → Orthodox faction gains ground
- Goblin shamanic loss → dependency on human-held territories for food

**Long-Term Consequences** (to Year 1200)
- Central plains never reunified → explains Valdrian expansion opportunity
- Northern distrust of relics → explains current caution
- Church's plague authority → foundation of Sanctified States
- Goblin population never recovered → explains current demographics

### 4.3 Named Rulers (Year 52-278)

**Fill the 226-year gap**:

- Year 52-89: High Priestess Solara → King Aldric of Solace
- Year 89-120: King Aldric → Queen Mara → King Varen
- Year 120-168: King Varen → Prince-Regent Cassius (never crowned—plague)
- Year 168-200: Interregnum—Three Claimants War
- Year 200-250: Warlord period—name 5 major warlords
- Year 250-278: Consolidation under Duke Valdris → first Valdrian Emperor

### 4.4 Secret Society Founding Stories

**Expand for each**:

**Veil Keepers** (founded Year 45)
- Founder: Commander Aldric Veilguard (not the king)
- Original purpose: Destroy ALL vampire knowledge
- First crisis: Year 80—discovered some knowledge was essential
- Schism: Destroyers vs. Guardians; Guardians won
- First major operation: Sealed three ruins (Year 90-100)

**Inheritors** (founded Year 52)
- Founder: Scholar Vera Lighttouch (ironic name given Vera Nighthollow)
- Original purpose: Preserve vampire knowledge for humanity
- First crisis: Year 100—accused of heresy; fled to Maritime League
- Evolution: Scholarly society → secret political network
- First major acquisition: Mind Codex fragments (Year 85)

**Order of Dawn** (founded Year 8)
- Founder: Saint Aurelius the Purifier
- Original purpose: Hunt vampire survivors
- First crisis: Year 50—no survivors found; purpose questioned
- Evolution: Vampire hunters → general "darkness" hunters
- The Seraphina Question: Did Aurelius preserve vampire knowledge?

**Deliverable**: Expanded `era-dark-ages.md` from ~3,000 words to ~12,000 words

---

## Phase 5: Consequence Chains for Major Events

Implement the tracking system from Phase 1.

### 5.1 Church Schism Chain

**Event**: Great Schism (Year 350)

**Cause**: Dispute over how to interpret plague—divine punishment (Orthodox) vs. natural disaster (Pragmatic)

**Immediate Effects**:
- Orthodox control central territories
- Pragmatists control coastal cities
- Violence: Massacre of Thornhaven (Year 355)

**Medium-Term Effects**:
- Year 400: Pragmatists ally with Maritime merchants
- Year 450: Orthodox ally with Northern military
- Year 500: First reconciliation attempt fails

**Long-Term Effects** (to Year 1200):
- Orthodox faction became Sanctified States establishment
- Pragmatic remnants became Reform movement Elara supports
- The massacre's descendants still seek justice
- Theological arguments map onto current political divisions

**Current Status**: Orthodox "won" but Pragmatic ideas persist in Maritime Republic and reformist nobles

### 5.2 Year 812 Vampire Chain

**Event**: Stasis vampire discovered in minor ruin

**Discovery**:
- Who: Valdrian expedition seeking artifacts
- Where: Collapsed facility in Border Marches
- Condition: Alive, disoriented, speaking old language

**Immediate Effects**:
- Destroyed within 6 hours—by whom?
- Three versions: Expedition leader (official), Veil Keeper team (rumored), the vampire itself (conspiracy)
- Panic in expedition; half desert

**What It Said** (contested):
- Version A: Nothing coherent—brain-damaged
- Version B: Warned about "others sleeping"
- Version C: Named locations of other survivors
- Version D: It said nothing; it was killed on sight

**Medium-Term Effects**:
- Inheritors realize survivors exist—intensify search
- Veil Keepers realize survivors exist—intensify sealing
- Order of Dawn realizes prey exists—intensify hunting
- All three become more secretive and competitive

**Long-Term Effects**:
- Secret society cold war escalates
- Border Marches become contested exploration zone
- "Year 812" becomes code phrase among relic hunters
- Conspiracy theories persist—"what did it really say?"

### 5.3 Silverwood Closure Chain

**Event**: Elves close borders (Year 1050)

**Create multiple theories**:

**Theory A: The Prophecy**
- Elven seers foresaw the protagonist's awakening
- Closure is preparation for "the Reawakening"
- Evidence: Timing matches Twilight calendar cycles

**Theory B: Internal Coup**
- Isolationist faction seized power
- Closure hides internal civil war
- Evidence: No elven diplomats seen since; all communications through intermediaries

**Theory C: They Found Something**
- Expedition to Sel'Naroth found something terrifying
- Closure protects the world from elven knowledge
- Evidence: The expedition leader's family was "honored" with isolation

**Theory D: External Threat**
- Elves detected dimensional instability
- Closure is defensive measure
- Evidence: Increased Twilight-style magic detected at borders

**Consequences**:
- Silverwood knowledge isolated—other races can't access elven scholarship
- Elven agents outside become cut off; Thandril's 150-year exile
- Trade in elven goods collapses—economic effects
- Year 1200: No one knows which theory is correct

### 5.4 Artifact Provenance Chains

**Track 3 major artifacts**:

**Crown of Seeing**
- Created: Year -350 by Serath the Artificer
- Collapse: Hidden in Vel'Krath vault
- Year 200: Discovered by Northern warlord; goes mad
- Year 350: Captured by Valdrian forces; studied
- Year 500: "Lost" in palace fire (actually stolen by Veil Keepers)
- Year 800: Veil Keepers give to Valdrian Emperor as "gift" (to monitor him)
- Year 1200: Emperor Cassius VIII has it; it's destroying him

**The Living Artifact** (Vessel 11)
- Created: Year -5
- Collapse: Stasis failed; escaped facility
- Year 0-300: Unknown
- Year 350: Rumors of "the walking dead" in Broken Lands
- Year 600: Goblin shamans report contact
- Year 900: Veil Keepers confirm existence; cannot locate
- Year 1200: Still active; hunting or being hunted?

**The Mind Codex**
- Created: Mind Covenant central records
- Collapse: Fragmented across multiple facilities
- Year 85: Inheritors acquire first fragments
- Year 300: Major fragment found in Maritime Republic
- Year 667: Compiled; "revolutionizes magical education"
- Year 900: Inheritors realize it's incomplete—critical sections missing
- Year 1200: Missing sections may explain protagonist's creation

**Deliverable**: New `02-timeline/consequence-tracking.md` file, ~8,000 words

---

## Phase 6: Cultural Memory Revision

Ensure each race has genuine internal debates.

### 6.1 Human Internal Debates

**Add to `03-cultures/races/humans.md`**:

**The Collaborator Question**
- Orthodox view: All collaborators were traitors
- Revisionist view: Some saved human lives through cooperation
- Current politics: Reformists support revisionism; traditionalists oppose
- Evidence both sides cite

**The Plague Interpretation**
- Orthodox view: Divine punishment for insufficient faith
- Pragmatic view: Natural disaster; Church exploited it
- Maritime view: Plague came from Church territories; they're responsible
- Current politics: Underlies Church-merchant tensions

**Were Vampires Entirely Evil?**
- Mainstream: Yes, demons
- Scholar minority: They built functional civilization; we've lost knowledge
- Radical fringe: We should study vampire governance models
- Why this is dangerous to say publicly

### 6.2 Elven Internal Debates

**Add to `03-cultures/races/elves.md`**:

**Should We Have Helped Vampires Reform?**
- Silverwood establishment: No—vampires were irredeemable
- Urban elves: Yes—we had influence and didn't use it
- Wild elves: We DID help—that's why Silverwood is corrupt
- What this means for current elven policy

**The Servant Question**
- Establishment: We preserved knowledge; service was resistance
- Critics: We were comfortable; we didn't resist until it was easy
- Evidence: Elven casualties in collapse were lowest of all races

**What Do We Actually Know?**
- Establishment: Our archives are complete and accurate
- Scholars: Archives have gaps; sections are sealed
- Radicals: Leadership is hiding the truth about Twilight
- The sealed sections of Year 1050

### 6.3 Dwarven Internal Debates

**Add to `03-cultures/races/dwarves.md`**:

**Did We Gain or Lose?**
- Traditionalists: We lost honor; our crafts served evil
- Pragmatists: We gained knowledge; vampire tech improved our lives
- Evidence: Deep holds still use vampire-derived techniques

**The Neutrality Question**
- Establishment: Neutrality preserved us
- Critics: Neutrality was cowardice; we could have helped others
- Radicals: We should be neutral now too—let humans fight humans

**What's in the Sealed Holds?**
- Leadership: Dangerous knowledge best forgotten
- Young dwarves: Our heritage being hidden from us
- Rumors: Active vampire technology still running

### 6.4 Goblin Internal Debates

**Add to `03-cultures/races/goblins.md`**:

**Blood Magic: Heritage or Curse?**
- Traditionalists: Sacred inheritance; our only power
- Moderates: Useful but dangerous; needs controls
- Assimilationists: It marks us as monsters; abandon it

**Should We Seek Revenge or Peace?**
- War faction: Humans will never accept us; strength is only option
- Peace faction: Revenge destroyed us before; integration is survival
- Gritha's position: Justified rage, but is it wise?

**The Collaboration Question**
- Mainstream: We were slaves; we had no choice
- Heresy: Some shamans collaborated willingly for power
- Dangerous truth: Blood magic came from vampire teaching

**Deliverable**: Expanded race files, ~4,000 words additional each

---

## Phase 7: Long-Delayed Consequences

Plant seeds in early eras that bloom centuries later.

### 7.1 Rise Era Seed → Consolidation Bloom

**Seed** (Year -800): Mind Covenant establishes "emergency protocols" for Bloodweb failure—including the Sanguine Vessel program concept.

**Growth**: Protocols forgotten by most; preserved in sealed archives.

**Bloom** (Year 900): Inheritors translate fragment mentioning "emergency protocols." They don't know what it means but it drives their search for Mind facilities.

**Year 1200**: This fragment is why they knew to look for Vel'Thoras.

### 7.2 Goblin War Seed → Year 1200 Bloom

**Seed** (Year 467): Blackmarsh Massacre—humans kill 3,000 goblins, but also destroy a shamanic academy.

**Growth**: The academy held the only copy of certain blood rituals.

**Bloom** (Year 1100): Gritha's teacher was trying to reconstruct these rituals; she failed and died.

**Year 1200**: Gritha's quest for vampire knowledge is partly to recover what humans destroyed at Blackmarsh. This is personal, not just political.

### 7.3 Church Schism Seed → Year 1200 Bloom

**Seed** (Year 355): Massacre of Thornhaven—Orthodox forces kill Pragmatic congregation.

**Growth**: Survivor families flee to Maritime Republic; become merchant class.

**Bloom** (Year 1000): Descendant family becomes primary Inheritor funder.

**Year 1200**: The family funding Vera's research are descendants of massacre survivors. Their support for "forbidden knowledge" is revenge on the Orthodox Church.

### 7.4 Year 812 Seed → Year 1200 Bloom

**Seed** (Year 812): What the vampire actually said before being killed.

**Growth**: One expedition member recorded it; journal passed through families.

**Bloom** (Year 1180): Journal acquired by Veil Keepers; contents classified highest level.

**Year 1200**: Kira Frost has clearance but hasn't accessed it. The journal contains location of Vel'Thoras. This is why Veil Keepers knew to send her there.

**Deliverable**: Seeds planted in era documents; blooms documented in `consequence-tracking.md`

---

## Phase 8: Parallel Events and Cycles

Add historical rhymes that create thematic meaning.

### 8.1 Vykros Parallel

**Original** (Year -890): Vykros the Conqueror unifies vampires; assassinated before consolidation; factions form.

**Parallel** (Year 620): King Aldric the Bold unifies Northern humans; killed in battle before consolidation; region fragments.

**Parallel** (Year 1180): Emperor Cassius VIII tries to unify Valdrian response to visions; failing health prevents consolidation; factions form.

**Thematic meaning**: Unity requires a unifier; their death/failure means fragmentation. The protagonist cannot be that unifier—he's not trusted.

### 8.2 Bloodweb Dependency Parallel

**Original**: Vampires became dependent on Bloodweb; ignored warnings; collapse.

**Parallel** (Year 600-1200): Humans become dependent on vampire artifacts for military/political power; warnings ignored.

**Year 1200**: Emperor's Crown of Seeing dependency mirrors vampire Bloodweb dependency. The cycle is repeating.

### 8.3 Subject Race Rebellion Parallel

**Original** (Year -50 to 0): Subject races rebel against vampire rule; succeed only because vampires collapsed.

**Parallel** (Year 400-500): Goblins rebel against human rule; fail because humans are stronger.

**Year 1200**: Will the dimensional threat be the "collapse" that lets goblins succeed this time?

**Deliverable**: Parallels noted in era documents and `consequence-tracking.md`

---

## Phase 9: Final Integration and Validation

### 9.1 Timeline Consistency Check

**Verify**:
- All dates consistent across documents
- No event contradicts another unintentionally
- Character ages work (elves live centuries; humans don't)
- Travel times make sense

### 9.2 Consequence Chain Completion

**For each major event, confirm**:
- [ ] Immediate effects documented
- [ ] Medium-term effects documented
- [ ] Long-term effects documented
- [ ] Current-day manifestation identified

### 9.3 Ambiguity Verification

**For each major historical question, confirm**:
- [ ] Multiple interpretations exist
- [ ] Each interpretation has supporting evidence
- [ ] No interpretation is marked as "correct"
- [ ] Contradictory evidence is documented

### 9.4 Cultural Memory Cross-Check

**For each event, confirm**:
- [ ] Each race has distinct version
- [ ] Versions are self-serving
- [ ] Internal debates exist within races
- [ ] No race has "the truth"

---

## Implementation Schedule

### Week 1: Foundation
- Phase 1 (Remove certainty, create templates)
- Begin Phase 2 (Pre-vampire expansion)

### Week 2: Vampire Civilization
- Complete Phase 2
- Phase 3 (Vampire texture)

### Week 3: Dark Ages
- Phase 4 (Dark Ages expansion—largest phase)

### Week 4: Consequence Chains
- Phase 5 (Major event chains)
- Phase 6 (Cultural memory revision)

### Week 5: Integration
- Phase 7 (Long-delayed consequences)
- Phase 8 (Parallels and cycles)
- Phase 9 (Validation)

---

## Files Modified/Created

### Modified (existing files):
- `02-timeline/collapse-event.md`
- `02-timeline/era-breakdowns/era-pre-vampire.md`
- `02-timeline/era-breakdowns/era-rise.md`
- `02-timeline/era-breakdowns/era-golden-age.md`
- `02-timeline/era-breakdowns/era-final-century.md`
- `02-timeline/era-breakdowns/era-dark-ages.md`
- `02-timeline/era-breakdowns/era-warring-kingdoms.md`
- `02-timeline/era-breakdowns/era-consolidation.md`
- `02-timeline/vampire-factions.md`
- `03-cultures/races/humans.md`
- `03-cultures/races/elves.md`
- `03-cultures/races/dwarves.md`
- `03-cultures/races/goblins.md`
- `08-secrets/shadow-truths.md`

### Created (new files):
- `02-timeline/consequence-tracking.md`
- `02-timeline/named-figures-registry.md` (optional—index of all named historical figures)

---

## Success Criteria

The revision succeeds when:

- [ ] Dark Ages has 20+ dated events (currently ~15)
- [ ] 5 failed kingdoms documented with rise/fall
- [ ] Great Plague has full consequence chain
- [ ] 10 named vampire figures with profiles
- [ ] No historical event has single "correct" version
- [ ] Each race has internal debates about their history
- [ ] 3+ artifact provenance chains documented
- [ ] Long-delayed consequences (500+ years) implemented
- [ ] Historical parallels create thematic meaning

---

## Congruence Notes

### Ensure Consistency Across Changes

**When expanding pre-vampire era**:
- Kingdoms must fall in ways that let vampires conquer them
- Pre-vampire cultures must be sources for "ancient tradition" claims
- Conflicts must create grudges that persist

**When adding failed kingdoms**:
- Their territories must explain current empire boundaries
- Their falls must benefit current powers
- Their remnants must exist as minority populations

**When revising cultural memory**:
- Internal debates must map onto current political factions
- Historical grievances must drive current conflicts
- No race can "win" the historical narrative

**When implementing consequence chains**:
- Earlier consequences must enable later consequences
- No effect without cause; no cause without effect
- Current politics must be traceable to historical events

---

## Priority Summary

If time is limited, do in this order:

1. **Phase 1**: Remove Shadow Truth certainty (enables everything else)
2. **Phase 4**: Expand Dark Ages (biggest gap)
3. **Phase 5.1-5.2**: Church Schism + Year 812 chains (highest impact)
4. **Phase 3.1**: Named vampire figures (adds texture)
5. **Phase 6**: Cultural internal debates (adds ambiguity)

The remaining phases are valuable but less critical than these five priorities.
