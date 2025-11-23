# Phase 2: Critical Narrative Fixes

## Overview
Document protagonist constraints and resolve identity issues that affect story feasibility.

---

## Task 2.1: Protagonist Feeding Pattern

**Source**: audit-pass2-04-narrative.md
**File**: `06-characters/protagonists/vessel-seven.md` (or protagonist.md)

**Implementation**:
Add "Feeding Requirements" section:

```markdown
## Feeding Requirements

### Blood Needs
- **Optimal**: 1 pint human blood every 3-4 days
- **Functional**: Can go 2 weeks at reduced capacity
- **Emergency**: 3-4 weeks maximum before incapacitation
- **Animal blood**: 50% effective (requires twice volume)

### Effects of Hunger
- **Days 1-7**: Full capacity
- **Days 8-14**: Strength reduced 25%, healing slowed
- **Days 15-21**: Strength reduced 50%, perception dulled
- **Days 22-28**: Near incapacitation, involuntary hunting instinct
- **Beyond 28**: Feral state, attacks anything with blood

### Feeding Methods During Travel
1. **Enemies**: Preferred—leaves no witnesses, morally acceptable
2. **Willing donors**: Rare—requires trust and secrecy
3. **Animals**: Inefficient but available—deer, livestock
4. **Unwilling humans**: Last resort—creates enemies and witnesses

### Travel Constraints
- Must plan routes through areas with prey availability
- Cannot cross true wilderness (no blood sources) for more than 2 weeks
- Urban areas provide more sources but more risk of discovery
- Each feeding creates potential witness or missing person

### Feeding and Combat
- Full-fed: Combat effective
- Week hungry: Still dangerous but tires faster
- Two weeks hungry: Significant disadvantage
- Beyond: Cannot reliably win fights

### Story Implications
- Every 1-2 weeks, Seven must find blood
- Each feeding is a scene (risk, moral choice, discovery)
- Hunger becomes ticking clock during chase sequences
- Feral state is catastrophic failure mode
```

---

## Task 2.2: Sunlight Travel Method

**Source**: audit-pass2-04-narrative.md
**File**: `06-characters/protagonists/vessel-seven.md`

**Implementation**:
Add "Sunlight and Travel" section:

```markdown
## Sunlight and Travel

### Sunlight Effects
- **Direct sun**: Painful, weakening, eventually fatal (hours)
- **Indirect/overcast**: Uncomfortable but functional
- **Shade**: Full capacity
- **Dawn/dusk**: Safe to move

### Travel Methods

**Primary: Night Travel**
- Speed: ~20 miles/night (vs 50-80 day for humans)
- Advantages: Better senses, predator avoidance
- Disadvantages: Half the travel speed, suspicious schedule

**Secondary: Covered Day Travel**
- Heavy cloak, hood, gloves covering all skin
- Speed: ~30 miles/day (slower than normal due to caution)
- Risk: Inspection, questions about appearance
- Effective in rain/overcast

**Emergency: Underground Routes**
- Vampire ruins often connected by tunnels
- Speed varies by condition
- Risk: Unknown hazards, collapse, getting lost
- Seven's knowledge of tunnel networks: Partial (from Blood Archive)

### Typical Journey Pattern
- Travel dusk to midnight (6 hours)
- Rest/hide midnight to dawn
- Travel dawn to sunrise if covered (2 hours)
- Total: ~20-25 miles/day

### Comparative Travel Times
| Route | Normal Human | Seven |
|-------|--------------|-------|
| Vel'Thoras → Valdris Prime | 25 days | 40-50 days |
| Valdris Prime → Port Sovereign | 20 days | 32-40 days |
| Any mountain crossing | 15 days | 25-35 days |

### Story Implications
- Seven moves at roughly half human speed
- Pursuers can gain ground during daylight
- Must find shelter before dawn (time pressure)
- Overcast days are gifts; clear days are threats
- Underground routes offer speed but unknown dangers
```

---

## Task 2.3: Disguise Methods

**Source**: audit-pass2-04-narrative.md
**File**: `06-characters/protagonists/vessel-seven.md`

**Implementation**:
Add "Concealment and Disguise" section:

```markdown
## Concealment and Disguise

### Physical Tells to Hide
1. **Eye reflectivity**: Unusual gleam in low light
2. **Predatory grace**: Movement too smooth, too quiet
3. **Unusual stillness**: Doesn't fidget, breathe visibly
4. **Skin pallor**: Pale even by Northern standards
5. **Vampire script tattoos**: Located on forearms and chest

### Concealment Methods

**Basic Disguise**:
- Heavy travel cloak (hides movement, pallor, tattoos)
- Gloves (hides hand pallor, forearm tattoos)
- Hood in sun (expected for fair-skinned)
- Deliberate fidgeting (learned behavior to seem human)

**Advanced Measures**:
- Theatrical makeup for skin tone (expensive, limited availability)
- Tinted glasses for eye gleam (rare, suspicious)
- Deliberate clumsiness (harder than it sounds)
- Speaking with pauses (hides too-smooth delivery)

**What Can't Be Hidden**:
- Response to direct sunlight
- Lack of body heat (close contact reveals)
- Healing too fast from visible wounds
- Not eating food (can fake but can't digest)
- Reflection oddities in some mirrors (inconsistent)

### Cover Stories
- **Northern scholar**: Explains pallor, formality, travel
- **Plague survivor**: Explains avoiding touch, staying covered
- **Religious penitent**: Explains hood, silence, avoiding eye contact
- **Merchant's agent**: Explains odd hours, carrying valuables

### Discovery Risk by Situation
- **Casual encounter**: Low (cloak and hood sufficient)
- **Conversation**: Medium (speech patterns may confuse)
- **Physical contact**: High (no body heat)
- **Combat**: Very high (healing, speed, strength obvious)
- **Extended stay**: Very high (feeding needed, no eating)

### Story Implications
- Seven can pass casual inspection
- Extended interaction is risky
- Any combat may blow cover
- Must avoid intimacy and prolonged contact
- Each settlement is infiltration challenge
```

---

## Task 2.4: Lysander/Vex Shadowhand Resolution

**Source**: audit-pass2-02-crossref.md
**Files**:
- `06-characters/supporting/lysander-vex.md`
- `04-factions/secret-societies/inheritors.md`

**Implementation**:
Make them the same person with clear timeline:

Update lysander-vex.md:
```markdown
# Lysander Vex (formerly "Vex Shadowhand")

## Basic Information
- **Current Role**: Independent information broker
- **Former Role**: Master of Acquisition, Inheritor Council of Light
- **Location**: Port Sovereign, Maritime Republic
- **Age**: 47

## Background

### Inheritor Career (Years 1175-1195)
- Recruited age 22 for linguistic talents
- Rose to Master of Acquisition by age 35
- Council of Light member for 5 years
- Known as "Vex Shadowhand" (operational name)
- Specialized in artifact procurement and verification

### The Break (Year 1195)
- Discovered Inheritors planning to use Seven as weapon
- Ethical disagreement with Council over "preservation vs exploitation"
- Argued for study without control; Council wanted leverage
- Left organization under threat of silencing
- Took operational knowledge, left artifacts behind

### Current Status
- Inheritors want him back or dead (knows too much)
- Uses "Lysander Vex" to distance from Shadowhand identity
- Maintains some Inheritor contacts (for information, not loyalty)
- Council has not yet replaced Master of Acquisition position
```

Update inheritors.md Council section:
```markdown
### Master of Acquisition: VACANT (formerly Vex Shadowhand)
- Position empty since Year 1195
- Vex Shadowhand departed after ethical disagreement
- Now operates independently as "Lysander Vex" in Port Sovereign
- Council considers him security risk but hasn't moved against him
- Temporary duties split between other Council members
```

---

## Task 2.5: Faction Learning Timeline

**Source**: audit-pass2-04-narrative.md
**File**: Create `09-plot-architecture/awakening-response-timeline.md`

**Implementation**:

```markdown
# Faction Learning Timeline: Protagonist Awakening

## Week 0: Awakening at Vel'Thoras

### Immediate Knowledge
- **Inheritors**: Present at site, know immediately
- **Veil Keepers**: Operative at site (Kira), know within hours

### Week 0 Actions
- Inheritors attempt containment/study
- Veil Keepers attempt elimination
- Conflict at site; Seven escapes in chaos

---

## Week 1: First Wave

### Day 1-3
- **Order of Dawn**: Veil Keeper courier reaches nearest chapter
- **Northern Military**: Kira's handler reports to Veil Keeper command, who alert Northern contacts

### Day 4-7
- **Northern Court**: Military intelligence reaches King Aldric
- **Order of Dawn Command**: Chapter reports reach headquarters in Sanctified

### Week 1 Response
- Order dispatches hunting parties north
- Northern sends scouts to Vel'Thoras
- Inheritors begin damage control (deny everything)

---

## Week 2-3: Second Wave

### Day 8-14
- **Valdrian Intelligence**: Spy networks report "unusual activity in north"
- **Maritime Merchants**: Trade rumors reach Port Sovereign
- **Church Hierarchy**: Order of Dawn reports to Cardinal level

### Day 15-21
- **Valdrian Court**: Emperor briefed on possible vampire sighting
- **Maritime Council**: Official awareness (dismissive initially)
- **Sanctified Theocracy**: High Theocrat informed

### Week 2-3 Response
- Valdrian sends investigators (skeptical)
- Maritime increases information buying
- Sanctified begins "corruption spreading" propaganda

---

## Week 4-6: Full Awareness

### Day 22-35
- **All major factions**: Confirmed awareness of vampire awakening
- **Dwarven Confederation**: Merchant network reports reach Thane Council
- **Goblin Tribes**: Raiding parties encounter fleeing refugees with stories

### Day 36-42
- **Silverwood Domain**: Unknown mechanism—either Thandril reports or magical sensing
- **General Population**: Rumors spreading through pilgrim routes

---

## Information Quality by Faction

| Faction | Week Known | Quality | Source |
|---------|------------|---------|--------|
| Inheritors | 0 | Perfect | Present |
| Veil Keepers | 0 | Perfect | Operative |
| Order of Dawn | 1 | Good | Veil Keeper contact |
| Northern | 1 | Good | Intelligence network |
| Valdrian | 2-3 | Moderate | Spy network |
| Maritime | 2-3 | Moderate | Trade rumors |
| Sanctified | 2-3 | Good | Order of Dawn |
| Ironpeak | 4-5 | Low | Merchant gossip |
| Goblins | 4-6 | Very Low | Refugee stories |
| Silverwood | ? | Unknown | Unknown method |

---

## Pursuit Timeline

### Week 1-2: Local Response
- Seven has 1-2 week head start
- Only Inheritor and Veil Keeper agents in immediate pursuit
- Can cover ~150-200 miles before organized hunt

### Week 3-4: Regional Response
- Order of Dawn hunting parties deployed
- Northern scouts searching
- Net closing; must stay ahead or go to ground

### Week 5+: Continental Response
- All factions have agents searching
- Borders being watched
- Any sighting reported within days
- Seven must have allies or shelter by now

---

## Silverwood Response (Unknown)

Possible scenarios:
1. **Immediate magical sensing**: Know from moment of awakening
2. **Thandril reports**: Takes 2-3 weeks through hidden channel
3. **Wait and observe**: Don't act until Seven approaches
4. **Already knew**: 150-year preparation was for this moment

Their response when they act will surprise everyone.
```

---

## Verification Checklist

After Phase 2 implementation, verify:

- [ ] Feeding requirements create regular story beats
- [ ] Travel times account for night movement
- [ ] Disguise limitations create tension
- [ ] Lysander/Vex timeline is coherent
- [ ] Each faction's learning time is documented
- [ ] Pursuit spacing creates escape windows

---

## Files to Create/Modify

1. `06-characters/protagonists/vessel-seven.md` - Feeding, sunlight, disguise sections
2. `06-characters/supporting/lysander-vex.md` - Background clarification
3. `04-factions/secret-societies/inheritors.md` - Council vacancy note
4. Create `09-plot-architecture/awakening-response-timeline.md`
