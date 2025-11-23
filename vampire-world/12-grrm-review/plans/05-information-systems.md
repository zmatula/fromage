# Phase 5: Information & Knowledge Systems

## Overview
Define how information actually travels, what it costs to keep secrets, and add the propaganda/rumor layer.

---

## Task 5.1: Define Communication Methods

**New File**: `/vampire-world/09-plot-architecture/communication-systems.md`

```markdown
# Communication Systems

How information actually travels in Year 1200.

---

## Mundane Communication

### Travel Speeds
- **Mounted courier**: 50-80 miles/day (relay system)
- **Ship (coastal)**: 100-150 miles/day
- **Ship (open sea)**: 50-100 miles/day
- **Walking messenger**: 20-30 miles/day
- **Caravan**: 15-20 miles/day

### Typical Message Times

| Route | Method | Days | Notes |
|-------|--------|------|-------|
| Valdris Prime → Port Sovereign | Courier | 12-15 | Established route |
| Ironhold → Valdris Prime | Courier | 25-30 | Mountain passes |
| Solarius → Port Sovereign | Ship | 8-10 | Coastal |
| Any capital → Silverwood | None | - | Borders closed |
| Any capital → Ironpeak | Courier | 10-20 | Depends on depth |

### What This Means
- News from Port Sovereign reaches Valdris Prime in 2 weeks
- A crisis in Ironhold won't be known in Solarius for a month
- Orders to distant commanders are always outdated
- Rumors travel faster than official messages

---

## Magical Communication

### Message Crystals
**Type**: Paired crystals that transmit voice
**Range**: 50-100 miles (degraded with distance)
**Availability**: Extremely rare (maybe 50 pairs worldwide)
**Who Has Them**:
- Imperial family (3 pairs)
- Inheritors (5 pairs)
- Banking Houses (4 pairs)
- Order of Dawn (2 pairs)
- Veil Keepers (1 pair)

**Limitation**: Both parties must have their crystal active. Can't call someone; can only speak when both are listening.

### Scrying
Can view distant locations but:
- Requires knowing the location
- Can be warded against
- Exhausting for the scryer
- Cannot transmit messages, only observe

### The Gap
No reliable long-distance instant communication exists. This shapes everything:
- Commanders must be trusted to act independently
- Crises escalate before responses arrive
- Information asymmetry is normal
- Rumors fill gaps

---

## Information Networks

### Merchant Networks
Fastest informal news:
- Travels with trade caravans
- Accurate for prices, politics
- Distorts for sensation
- Maritime merchants have best network

### Pilgrim Routes
Slower but widespread:
- Church news travels this way
- Sanctified propaganda spreads here
- Rural areas hear news via pilgrims
- 2-4 weeks behind merchant news

### Military Couriers
Fastest official system:
- Relay stations every 30 miles
- Only for military/state business
- Can be intercepted

### Academic Correspondence
Slow but detailed:
- Scholars exchange letters
- Months between exchanges
- Most accurate for technical information
- Inheritors monitor this network

---

## Who Knows What When

### Breaking News Travel Time
A major event (assassination, battle, discovery):
- **Same city**: Hours
- **Same region**: 1-3 days
- **Same empire**: 1-2 weeks
- **Continental**: 3-6 weeks
- **Accurate details**: Add 1-2 weeks

### Implication
When Seven awakens, it will be weeks before anyone outside Vel'Thoras knows. The Inheritors might know in 2-3 weeks (they're watching). The Order of Dawn might not know for a month. Elves might never find out through normal channels.
```

---

## Task 5.2: Show Secret-Keeping Costs

### Vera's Surveillance Operations

**File**: `/vampire-world/06-characters/major-characters/vera-nighthollow.md`

**Add to "The Founder's Secret" section**:
```markdown
### The Cost of Keeping It

Vera maintains active surveillance on three families:

**Helena Ashford** (Veil Keeper descendant):
- Inheritor mole in Veil Keeper cells reports her movements
- Cost: 500 crowns/year in bribes
- Risk: Mole could be discovered or turned

**Marcus Thornwood** (Valdrian historian):
- Academic colleague reports his research
- Cost: 200 crowns/year stipend
- Risk: Colleague might grow conscience

**Cassandra Vane** (Maritime noble):
- Maritime contact tracks her legal movements
- Cost: 300 crowns/year
- Risk: She's getting too close; may need to act

**Total Annual Cost**: ~1,000 crowns
**Years Maintained**: Since she became Conclave member (12 years)
**Total Investment**: ~12,000 crowns in keeping one secret

**The Pressure**:
- Every year they get closer to truth
- Every year the cost grows
- She must decide: silence them or confess
- The Crown whispers: silence is strength
```

### Goblin Sanctuary Protection

**File**: `/vampire-world/03-cultures/races/goblins.md`

**Add section**:
```markdown
## The Cost of the Great Secret

### Sanctuary Knowledge Protection

The goblins' greatest secret—Twilight sanctuary locations—has been protected for 1,200 years through brutal methods:

**The Memory Shamans**: Only 7 shamans at any time know all locations. They never travel together. They never write it down. Knowledge passes through blood ritual only.

**The Tortured Protocol**: When goblins are captured, the tribe assumes the worst. Any goblin held more than a day is... questioned... upon return. Not because they're traitors—because they might have broken.

**The Price Paid**: Over twelve centuries, dozens of goblins who might have revealed the secret under torture have been killed by their own people. Some were probably innocent. The shamans bear this weight.

**Why It Works**: Other races assume goblins know nothing worth knowing. This prejudice is their greatest protection.

**Why It Might Fail**: Seven's awakening makes sanctuaries relevant again. If someone realizes goblins know, the torture will begin in earnest. How many will die to keep the secret this time?
```

---

## Task 5.3: Add Propaganda Campaigns

**File**: `/vampire-world/04-factions/empires/sanctified-states.md`

**Add section**:
```markdown
## Current Propaganda Campaigns

### "The Corruption Grows" (Year 1198-present)

**Purpose**: Justify expanded persecution
**Message**: Magic users increasing, non-humans infiltrating, danger rising
**Method**: Sermons, pamphlets, market-square preachers, traveling shows

**Who Creates It**:
- Cardinal Blackfire's office controls messaging
- Order of Dawn contributes "evidence"
- Local clergy adapt to regional concerns

**Who Believes It**:
- Faithful peasantry: Completely
- Urban merchants: Skeptically (hurts trade)
- Educated clergy: Selectively
- Other nations: See it as excuse for aggression

### "Northern Threat" (Year 1195-present)

**Purpose**: Prepare population for potential conflict
**Message**: Northern Kingdom worships vampire artifacts, plans invasion
**Method**: Military displays, border incident reports (exaggerated)

**The Irony**: The Sanctified States have more vampire artifacts than the Northern Kingdom. But the faithful don't know that.

### Effects
- Refugee families torn apart
- Innocent scholars executed
- Trade with other nations suffering
- But Church authority strengthened
```

---

## Task 5.4: Add "Who Knows What" to Major Characters

**Example for Marcus Ashford**:

**File**: `/vampire-world/06-characters/major-characters/marcus-ashford.md`

**Add section**:
```markdown
## Information Profile

### Knows For Certain
- Order of Dawn doctrine on vampires
- His training and combat techniques
- The Inheritors are enemies
- The Order uses "purified" artifacts

### Believes But Unverified
- Vampires were literally demonic
- Divine Light is a conscious deity
- The Collapse was divine punishment
- All Inheritors are evil

### Suspects
- Order leadership knows things they don't share
- Some doctrine may be simplified for faithful
- His Year 1190 raid killed scholars, not cultists

### Completely Wrong About
- The nature of Divine Light (it's not what he thinks)
- Whether all vampires were evil
- Whether Seven is irredeemable
- What his own Order hides

### Information Sources
- Grand Master Aurelius (filtered)
- Order archives (incomplete)
- Confessions from prisoners (biased/coerced)
- His own observations (colored by training)
```

---

## Task 5.5: Create Information Distortion Examples

**File**: `/vampire-world/03-cultures/cultural-memory-matrix.md`

**Add section**:
```markdown
## How Information Distorts

### Case Study: Year 812 Discovery

**At the Mine** (Year 812):
"Something was found in deep tunnels. Church came. Everyone disappeared."

**In Northern Towns** (Year 815):
"Miners found vampire gold. Church stole it and killed them."

**In Valdrian Courts** (Year 830):
"The Northern Kingdom found a vampire artifact. Church properly confiscated it."

**In Maritime Universities** (Year 900):
"The Iron Ridge Incident may have involved a stasis chamber."

**In Veil Keeper Records** (Year 1000):
"Living vampire confirmed in Northern stasis chamber. Church cover-up verified."

Each version serves different interests. None are entirely accurate.

### Case Study: The Twilight War

**Human Version**: Elves attacked unprovoked; heroic defense pushed them back
**Elven Version**: Humans broke treaty; elves defended homeland
**Dwarven Version**: Both sides were fools; dwarves stayed out of it
**Goblin Version**: Both races weakened themselves; briefly good for goblins

### Pattern
Information distorts through:
- Distance (further = more distortion)
- Time (longer = more mythologized)
- Interest (serves teller's agenda)
- Retelling (details become dramatic)
```

---

## Task 5.6: Add Information Lag Consequences

**File**: `/vampire-world/09-plot-architecture/year-1200-political-tensions.md`

**Add section**:
```markdown
## Information Lag Consequences

### Why Crises Escalate

**Valdrian Succession**:
- Provincial governors make independent decisions
- By the time central command knows, actions are taken
- Contradictory orders cross in transit
- Each faction claims to act with authority

**Example**: Duke Varen mobilizes troops. Message takes 10 days to reach Valdris Prime. Countermand takes 10 days back. By then, troops have engaged locals. Too late to recall.

### Why Rumors Matter

When official news takes 2 weeks, rumors taking 1 week become "truth":
- Markets react to rumors, not facts
- Military repositions on rumors
- Political decisions made on incomplete information
- By time truth arrives, decisions are locked

### Implication for Seven

When Seven awakens:
- Inheritors might know in 2 weeks (agents near Vel'Thoras)
- Veil Keepers might know in 3 weeks (fewer resources)
- Order of Dawn might know in 4 weeks (further away)
- Church hierarchy might know in 5 weeks

Each faction will act on partial information. Mistakes will be made. Seven has a window where no one knows—or everyone "knows" different things.
```

---

## Verification Checklist

After completing Phase 5:

- [ ] Communication systems file created with travel times and methods
- [ ] Vera's surveillance costs detailed
- [ ] Goblin sanctuary protection costs shown
- [ ] Sanctified propaganda campaigns added
- [ ] At least 3 characters have "who knows what" profiles
- [ ] Information distortion examples added to cultural memory
- [ ] Information lag consequences in political tensions
