# Fifth-Pass Revision Plan: Storyline Consistency Fixes

## Overview

This plan addresses the critical storyline coherence issues identified in the fifth-pass audit. The issues fall into five categories requiring sequential resolution (later phases depend on earlier fixes).

---

## Phase 1: Geographic & Timeline Repair (CRITICAL)

These fixes must happen first as they affect all other storylines.

### 1.1 Fix Event Order Inversion

**Problem**: Event 3 (Border Clash, Week 2) occurs BEFORE Event 2 (Crown's Vision, Week 3)

**Solution**:
- Move Crown's Vision to Week 2 (Days 8-10)
- Keep Border Clash at Week 2 but specify Days 12-14
- This makes them near-simultaneous rather than inverted

**Files to edit**:
- `09-plot-architecture/intersection-points.md` - Update Event 2 timing
- `09-plot-architecture/story-events/event-02-*.md` - Adjust week reference

### 1.2 Fix Seven's Travel Distances

**Problem**: Seven cannot physically reach Scholar's Haven (Maritime) by Week 6 at night-only travel speeds

**Solution Options** (choose one):
- **Option A**: Add "safe passage" mechanism - Thandril arranges faster transport (elven waypoints, hidden roads)
- **Option B**: Move Blood Archives to closer location (not Maritime)
- **Option C**: Extend timeline - events happen over 16-20 weeks, not 12

**Recommended**: Option A - Thandril's resources enable faster travel after Week 3 alliance

**Files to edit**:
- `06-characters/protagonist.md` - Add travel mechanism after Thandril alliance
- `09-plot-architecture/intersection-points.md` - Note faster travel capability
- `04-factions/empires/silverwood-domain.md` - Document Thandril's access to elven waypoints

### 1.3 Fill Weeks 4-5 Narrative Void

**Problem**: Complete gap between Thandril intervention (Week 3) and Blood Archives (Week 6)

**Solution**: Add content for Weeks 4-5:
- Week 4: Trust negotiation with Inheritors, Seven learns to control abilities
- Week 5: Journey to Scholar's Haven, Seven confronts feeding ethics

**Files to edit**:
- `09-plot-architecture/intersection-points.md` - Add Week 4-5 section
- `06-characters/protagonist.md` - Add skill development timeline

### 1.4 Resolve Border Clash Location

**Problem**: Seven cannot reach Valdrian-Northern border by Week 2

**Solution**: Seven doesn't travel TO the clash - the clash's consequences reach Seven
- Seven is still fleeing (near eastern Valdris)
- Border Clash creates refugee waves that overtake Seven
- Seven learns of clash from refugees, not by witnessing it

**Files to edit**:
- `09-plot-architecture/intersection-points.md` - Reframe Seven's connection to Event 3
- `09-plot-architecture/story-events/event-03-*.md` - Clarify Seven learns indirectly

---

## Phase 2: Economic Consistency Fixes

### 2.1 Order Budget Crisis

**Problem**: 950K budget vs 2.25M campaign cost

**Solution**: Make the budget crisis PART of the story
- Order begins hunt with normal resources
- By Week 4, costs spiral - begin drawing on Sanctified funds
- By Week 8, financial crisis forces tactical retreat
- This CREATES the moment for Seven to gain breathing room

**Files to edit**:
- `04-factions/organizations/order-of-dawn.md` - Document budget crisis timeline
- `09-plot-architecture/present-day-crises.md` - Add Order financial collapse as plot point
- `09-plot-architecture/intersection-points.md` - Note Week 8 Order pullback

### 2.2 Sanctified Funding Conflict

**Problem**: Can't fund both persecution AND Order mobilization

**Solution**: Force a choice - Solarius must pick one
- Weeks 1-4: Tries to fund both, persecution weakens
- Week 5: Must choose - cuts persecution to fund hunt
- This creates opportunity for reform faction

**Files to edit**:
- `04-factions/empires/sanctified-states.md` - Add funding choice
- `06-characters/supporting/high-theocrat-solarius-vii.md` - Add decision point

### 2.3 Northern Grain Problem

**Problem**: 4-month reserves make invasion suicidal

**Solution**: Already partially addressed (Phase 1 raid for granaries), but add:
- Aldric knows the risk - that's why it's a quick raid, not conquest
- Success of raid determines whether full invasion is possible
- Failure means Northern must negotiate or starve

**Files to edit**:
- `04-factions/empires/northern-dominion.md` - Clarify raid stakes
- `06-characters/supporting/warlord-king-aldric-xii.md` - Add awareness of risk

---

## Phase 3: Causation Chain Reconstruction

### 3.1 Restructure Events 2-3-4 Relationship

**Problem**: These are parallel consequences of Event 1, not a causal chain

**Solution**: Acknowledge parallel structure, but add connecting threads:
- Event 1 (Awakening) triggers THREE simultaneous responses
- Event 2 (Crown's Vision) - Valdrian succession crisis
- Event 3 (Border Clash) - Northern opportunism
- Event 4 (Blood Archives) - Seven's quest for answers
- ADD: Each affects the others (Vision distracts from Clash response, Clash creates chaos Seven exploits)

**Files to edit**:
- `09-plot-architecture/intersection-points.md` - Reframe as "parallel consequences" with cross-effects
- Add cross-references between Event 2, 3, 4 showing mutual impact

### 3.2 Add Mechanical Causation Links

**Problem**: No clear HOW explanations between events

**Solution**: Add specific mechanisms:
- Event 4 → 5: Scholar's Haven records mention Ironpeak, Seven travels there
- Event 5 → 6: Dwarven artifact points to Sel'Naroth, Thandril guides
- Event 6 → 7: Sel'Naroth knowledge reveals Scar crisis timing

**Files to edit**:
- `09-plot-architecture/story-events/` - Add "leads to next" section in each event
- `09-plot-architecture/intersection-points.md` - Document causal mechanisms

### 3.3 Resolve Unresolved Setups

**Problem**: Multiple Chekhov's guns that never fire

**Solutions**:
- Year 812 vampire testimony → Payoff: Seven discovers this record, it names the Scar threat
- Crown's madness history → Payoff: Crown breaks during Event 7, fulfilling its pattern
- Thandril feeding intervention → Payoff: Creates bond that enables later trust
- Blood Anvil + vampire blood → Payoff: This combination is key to Scar resolution

**Files to edit**:
- `09-plot-architecture/story-events/event-07-*.md` - Add Crown breakdown
- `08-secrets/` - Connect Year 812 testimony to Event 4 discovery
- `09-plot-architecture/intersection-points.md` - Document payoffs

---

## Phase 4: Faction Pressure Integration

### 4.1 Order Overextension → Persecution Weakens

**Mechanism**: Order draws knights from persecution duty for hunt
- Week 3: Persecution at 100%
- Week 5: Persecution at 60% (knights reassigned)
- Week 8: Persecution at 30% (financial crisis)

**Files to edit**:
- `09-plot-architecture/present-day-crises.md` - Add persecution decline timeline
- `04-factions/empires/sanctified-states.md` - Note enforcement gaps

### 4.2 Northern Invasion → Order Coverage Collapse

**Mechanism**: Order must choose - chase Seven or defend against Northern
- Week 2: Border Clash forces Order response
- Week 3-4: Hunt slows as knights redirected north
- Week 5: Northern raid success means more resources needed

**Files to edit**:
- `09-plot-architecture/present-day-crises.md` - Add Order divided attention
- `09-plot-architecture/intersection-points.md` - Note how this helps Seven

### 4.3 Maritime Chaos → Artifact Verification Breaks

**Mechanism**: Maritime authenticates magical artifacts continent-wide
- Post-coup: Authentication network disrupted
- Week 4+: Factions can't verify artifacts, creating uncertainty
- This affects Order's ability to track magical signatures

**Files to edit**:
- `04-factions/empires/maritime-republic.md` - Add authentication disruption
- `09-plot-architecture/present-day-crises.md` - Note continental impact

### 4.4 Add Dwarven Faction to Timeline

**Problem**: Ironpeak Confederation completely absent from 12-week arc

**Solution**: Add dwarven involvement:
- Week 8: Seven reaches Ironpeak (Event 5)
- Week 8-9: Dwarves debate helping vs neutrality
- High Thane Borin makes decision with consequences

**Files to edit**:
- `09-plot-architecture/intersection-points.md` - Add dwarven section
- `04-factions/empires/ironpeak-confederation.md` - Add current crisis involvement
- `06-characters/supporting/` - Flesh out High Thane Borin

---

## Phase 5: NPC Arc Completion

### 5.1 Complete Missing Arcs

**NPCs needing full arcs**:

**Solarius VII** (resolve contradiction first):
- Beginning: Moderate trying to balance reform and tradition
- Middle: Forced to choose (persecution vs hunt funding)
- End: Choice defines his legacy

**Sister Elena**:
- Beginning: Secret doubter within Order
- Middle: Encounters evidence that breaks her faith
- End: Must choose loyalty or conscience

**Aldric XII**:
- Beginning: Desperate king, starving people
- Middle: Raid succeeds but at cost
- End: Must decide - conquest or consolidation

**High Thane Borin**:
- Beginning: Neutral isolationist
- Middle: Seven arrives seeking help
- End: Must choose - help or exile

**Files to edit**:
- `06-characters/supporting/high-theocrat-solarius-vii.md` - Fix contradiction, add arc
- `06-characters/supporting/sister-elena.md` - Add complete arc
- `06-characters/supporting/warlord-king-aldric-xii.md` - Add decision arc
- Create or update High Thane Borin file

### 5.2 Add NPC Decision Points to Intersection Points

**Problem**: NPCs don't appear in plot architecture

**Solution**: Add NPC decision moments to intersection-points.md:
- Week 2: Aurelius's hunt strategy decision
- Week 4: Helena's intelligence choice
- Week 5: Solarius's funding decision
- Week 6: Elena's crisis of faith moment
- Week 8: Borin's neutrality decision
- Week 10: Kira's loyalty break

**Files to edit**:
- `09-plot-architecture/intersection-points.md` - Add NPC decision sections

### 5.3 Fix Data Inconsistencies

**Aldric XII age**: Standardize to 48 (experienced king makes more sense)
**Solarius VII**: Remove "fundamentalist" from registry, align with moderate characterization

**Files to edit**:
- `06-characters/supporting-cast/character-registry.md` - Fix age and characterization

---

## Phase 6: Information Architecture

### 6.1 Create Knowledge Matrix

**Problem**: Referenced but doesn't exist

**Solution**: Create `05-systems/information-control/knowledge-matrix.md` tracking:
- What each faction knows about Seven (by week)
- What Seven knows about each faction (by week)
- What readers know vs characters know

**Files to create**:
- `05-systems/information-control/knowledge-matrix.md`

### 6.2 Fix Vessel Registry Conflicts

**Problem**: Different people assigned to same Vessel numbers

**Solution**: Audit and standardize:
- `08-secrets/sanguine-vessels-registry.md`
- `08-secrets/vessel-recruitment-process.md`
- Ensure all Vessel assignments consistent

### 6.3 Resolve Seven's Memory Contradiction

**Problem**: Both "missing memories" and "knows everyone who died"

**Solution**: Clarify - Seven has emotional impressions, not clear memories
- Knows they existed and felt connections
- Doesn't have specific memories or names
- Blood Archives revelation fills gaps

**Files to edit**:
- `06-characters/protagonist.md` - Clarify memory nature

---

## Implementation Priority

1. **Phase 1** (Geographic/Timeline) - MUST be first, everything else depends on it
2. **Phase 2** (Economic) - Creates story opportunities
3. **Phase 3** (Causation) - Makes events feel connected
4. **Phase 4** (Faction Pressure) - Makes world feel alive
5. **Phase 5** (NPC Arcs) - Populates the story
6. **Phase 6** (Information) - Tracks complexity

---

## Estimated Scope

- **Files to edit**: ~25-30
- **Files to create**: 1-2 (knowledge matrix, possibly Borin file)
- **Major rewrites**: intersection-points.md, present-day-crises.md
- **Moderate edits**: All faction files, key NPC files
- **Minor edits**: Event files, registry files
