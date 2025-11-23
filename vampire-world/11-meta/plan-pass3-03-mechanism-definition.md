# Phase 3: Mechanism Definition

## Overview
Define undefined systems and show economic consequences.

---

## Task 3.1: Silverwood Response Mechanism

**Source**: audit-pass3-05-cross-system.md
**File**: `04-factions/empires/silverwood-domain.md`

**Issue**: How Silverwood learns and responds to Seven's awakening is undefined

**Implementation**:
Add "Response Mechanism" section:

```markdown
## Response Mechanism

### How Silverwood Learns

**Primary Method: Thandril's Report**
- Thandril has hidden communication channel (magical sending stone)
- Can send brief message once per month (costly, draining)
- Message takes 3 days to reach Silverwood Council
- **Timeline**: Thandril learns Week 0-1, reports Week 1-2, Council receives Week 2-3

**Secondary Method: Dimensional Sensing**
- Eldest elves can sense major dimensional disturbances
- Seven's awakening creates detectable ripple
- Provides general awareness but not location/details
- **Timeline**: Sensed within hours of awakening

### Silverwood Knows
- Week 0: Something awakened (dimensional sensing)
- Week 2-3: Thandril's report with details arrives
- Week 3-4: Council deliberates response
- Week 4-5: Decision made, action initiated

### Why They Don't Act Immediately
Despite 150 years of preparation:
- Must verify Thandril's report (trust but verify)
- Must consult with Eldest (protocol requires consensus)
- Must prepare chosen response (logistics take time)
- Must maintain secrecy (no premature revelation)

### Possible Actions (Council Will Choose One)
1. **Send Observers**: More elves outside to watch and report
2. **Contact Seven Directly**: Through Thandril as intermediary
3. **Reveal Themselves**: Open borders, declare intentions
4. **Wait Longer**: Continue observing, act only if necessary

### Story Implication
Silverwood will act in Week 5-6 at earliest. Their 150-year preparation means they're ready, but protocol means they're not fast. When they move, it will be decisive but not instant.
```

---

## Task 3.2: Sanctified Economic Decline

**Source**: audit-pass3-05-cross-system.md
**Files**:
- `04-factions/empires/sanctified-states.md`
- `09-plot-architecture/present-day-crises.md`

**Issue**: Persecution "destroying economic base" but Sanctified remains "largest grain producer"

**Implementation**:
Add "Persecution Economic Impact" to sanctified-states.md:

```markdown
## Persecution Economic Impact

### Documented Losses (Year 1195-1200)
- Scholars fled: ~200 (with knowledge and connections)
- Merchants fled: ~150 (with trade networks)
- Craftspeople fled: ~100 (with skills)
- Farmers displaced: ~500 (agricultural disruption)

### Annual Revenue Loss
- Lost taxes from fled population: ~50,000 crowns
- Lost trade from merchant exodus: ~100,000 crowns
- Lost production from craftspeople: ~75,000 crowns
- **Total annual loss: ~225,000 crowns** (and growing)

### Agricultural Impact
- Year 1195 grain output: 21 million bushels
- Year 1200 grain output: 18 million bushels
- **Decline: 14%** (3 million bushels lost)
- Export capacity reduced from 6M to 3M bushels

### Why They're Still Largest Producer
- Started with massive surplus (geographical advantage)
- Decline not yet catastrophic (14% is survivable)
- Other regions haven't increased production
- But trend is clear: continued persecution = collapse

### Strategic Consequence
Northern could break Valdrian dependency by buying from Sanctified:
- Sanctified has 3M bushel surplus (matches Northern's 3.6M need)
- But Sanctified persecution makes trade politically toxic
- Northern would rather invade than deal with theocrats
- Ironic: Sanctified's religious purity destroys their leverage
```

Also update present-day-crises.md to reference this decline.

---

## Task 3.3: Information Barrier Explanations

**Source**: audit-pass3-04-information-coherence.md
**File**: `09-plot-architecture/knowledge-matrix.md`

**Issue**: Matrix lists gaps but not WHY factions don't know things

**Implementation**:
Add "Information Barriers" section:

```markdown
## Information Barriers

### Why Valdrian Doesn't Know
- **Northern grain crisis severity**: Spy network in North is underfunded; military information prioritized over economic
- **Dwarven succession pressure**: Holds are sealed; dwarven informants rare and expensive
- **Order operations in Valdris**: Order operates through Church channels, not state; deliberate compartmentalization

### Why Northern Doesn't Know
- **Sanctified surplus alternative**: Religious hostility prevents diplomatic contact; wouldn't consider dealing with theocrats
- **Helena's intelligence extent**: Trusts her as wife; doesn't want to know; willful blindness
- **Own logistics fragility**: Military culture doesn't examine weaknesses; admitting fragility is shameful

### Why Sanctified Doesn't Know
- **Persecution's economic cost**: Church controls information; dissent is heresy; no one will report bad news
- **Their leverage is declining**: See above; also, leadership believes Divine will provides
- **Rivals recruiting their refugees**: Refugees are traitors; their success elsewhere is denied

### Why Maritime Doesn't Know
- **Coup damaged intelligence permanently**: Best political agents were purged; network hasn't recovered
- **Banking faction plans**: Consortium is paranoid; information compartmentalized even from allies
- **Lysander's knowledge depth**: He's former Inheritor; they don't trust him enough to buy from him

### Why Information Barriers Matter
Factions act on incomplete information, making "rational" decisions that are collectively disastrous. The Northern invasion, Sanctified persecution, and Maritime coup all make sense from inside—but create catastrophe when combined.
```

---

## Task 3.4: Protagonist Journey Season

**Source**: audit-pass3-03-protagonist-constraints.md
**File**: `06-characters/protagonists/vessel-seven.md` (or protagonist.md)

**Issue**: Season not specified; affects travel times significantly

**Implementation**:
Add "Journey Context" section:

```markdown
## Journey Context

### Season: Late Spring (Month 4-5, Year 1200)

**Why Late Spring**:
- North Pass opens Month 5 (allows Northern invasion timing)
- Nights are ~9 hours (moderate darkness for travel)
- Weather is mild (less survival pressure)
- Forests are leafed (better concealment)

### Daylight Constraints
- Darkness: ~9 hours (dusk to dawn)
- Travel window: 8 hours actual movement
- Distance per day: 20-25 miles (night travel)
- With covered day travel: 30-35 miles (risky)

### Seasonal Progression
- Month 4-5 (Awakening): Mild, moderate darkness
- Month 6-7 (Hunt arc): Summer, shortest nights (6-7 hours)
- Month 8-9 (Alliance arc): Late summer, nights lengthening
- Month 10+ (Convergence): Autumn, long nights favor Seven

### Story Implication
Seven's escape happens in favorable season, but summer makes mid-story harder (shortest nights = most vulnerable). By late story, lengthening nights give him advantage—if he survives summer.
```

---

## Verification Checklist

After Phase 3:
- [ ] Silverwood response mechanism defined with timeline
- [ ] Sanctified economic decline quantified (14% grain loss)
- [ ] Knowledge gaps have information barrier explanations
- [ ] Season specified as late spring with progression

---

## Files to Modify

1. `04-factions/empires/silverwood-domain.md` - Response mechanism
2. `04-factions/empires/sanctified-states.md` - Economic decline
3. `09-plot-architecture/present-day-crises.md` - Reference decline
4. `09-plot-architecture/knowledge-matrix.md` - Information barriers
5. `06-characters/protagonists/vessel-seven.md` - Season context
