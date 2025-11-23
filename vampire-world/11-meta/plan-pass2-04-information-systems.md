# Phase 4: Information Systems

## Overview
Map how information flows, distorts, and creates strategic advantage.

---

## Task 4.1: Communication Infrastructure

**Source**: audit-pass2-05-gaps.md
**File**: Create `09-plot-architecture/communication-infrastructure.md`

**Implementation**:

```markdown
# Communication Infrastructure

## Message Speed by Method

### Fastest to Slowest

| Method | Speed | Cost | Reliability | Secrecy |
|--------|-------|------|-------------|---------|
| Inheritor crystals | Instant | N/A | Perfect | High |
| Veil Keeper crystal (1) | Instant | N/A | Perfect | Very High |
| Mounted courier | 60-80 mi/day | 5 crowns/day | High | Medium |
| Post riders (relay) | 100 mi/day | 10 crowns/message | High | Low |
| Ship (coastal) | 80-120 mi/day | 2 crowns/message | Weather | Low |
| Merchant convoy | 20-30 mi/day | 1 crown/message | High | Very Low |
| Pilgrim route | 15-20 mi/day | Free | Moderate | None |

### Typical Message Times

| Route | Courier | Post | Ship | Merchant |
|-------|---------|------|------|----------|
| Valdris Prime ↔ Port Sovereign | 20 days | 12 days | 8 days | 40 days |
| Valdris Prime ↔ Solarium | 25 days | 15 days | N/A | 50 days |
| Port Sovereign ↔ Northern capital | 30 days | 18 days | 15 days | 60 days |
| Any city ↔ Ironpeak | 35 days | 20 days | N/A | 45 days |

---

## Faction Communication Capabilities

### Tier 1: Instant Communication
**Inheritors of Blood**
- 12 paired message crystals
- Instant text communication between paired crystals
- Limited by: Number of crystals, need for literate operators
- Strategic advantage: Coordinate across continent in hours

**Veil Keepers**
- 1 paired crystal (headquarters to field command)
- Used only for critical messages
- All other communication: Couriers and dead drops
- Vulnerable: Losing the crystal cripples coordination

### Tier 2: Fast Networks
**Order of Dawn**
- Dedicated courier network between chapter houses
- Post rider relays in Sanctified States
- Speed: 80-100 miles/day in friendly territory
- Coverage: Excellent in Sanctified, moderate elsewhere

**Northern Military**
- Military courier corps
- Signal towers along borders (fire/smoke)
- Speed: 60-80 miles/day by rider, instant by signal
- Coverage: Excellent in Northern, poor elsewhere

**Valdrian Imperial**
- Imperial post system (fastest non-magical)
- Diplomatic pouches with foreign powers
- Speed: 100 miles/day on post roads
- Coverage: Excellent in Valdris, diplomatic elsewhere

### Tier 3: Trade Networks
**Maritime Republic**
- Ship message service
- Merchant information exchange
- Speed: Fast by sea, slow by land
- Coverage: Excellent on coasts, poor inland

**Ironpeak Confederation**
- Merchant network carries information
- Slow but reliable
- Speed: 20-30 miles/day
- Coverage: Excellent with trading partners, none with non-partners

### Tier 4: No Formal Network
**Silverwood Domain**
- Completely cut off (closed borders)
- Thandril has unknown communication method
- May use magical sensing for major events

**Broken Lands Goblins**
- Oral messages through raiding parties
- Shaman communication (limited, unreliable)
- Speed: Irregular, sometimes weeks

---

## Message Costs

### Official Channels
- Imperial post (Valdris): 2 crowns/message
- Military courier: 5 crowns/day
- Diplomatic pouch: Free (if you have access)
- Ship message: 2 crowns (coastal)

### Private Channels
- Hired courier: 5-10 crowns/day + danger pay
- Merchant network: 1 crown/message (slow)
- Information broker: 10-50 crowns (verified)

### Secret Channels
- Dead drop establishment: 20-50 crowns
- Coded message service: 10 crowns/message
- Bribed official: 50-200 crowns
- Assassin courier: 100+ crowns

---

## Information Decay and Distortion

### Accuracy by Distance

| Distance | Time | Accuracy | Typical Distortion |
|----------|------|----------|-------------------|
| Local | 1-3 days | 90% | Minor details wrong |
| Regional | 1-2 weeks | 70% | Motivation added |
| Continental | 3-6 weeks | 50% | Narrative formed |
| Cross-border | 4-8 weeks | 30% | Propaganda filtered |

### Distortion Patterns
1. **Simplification**: Complex events become simple stories
2. **Motivation**: Neutral acts gain good/evil framing
3. **Attribution**: Vague actors become specific enemies
4. **Scale**: Numbers grow with retelling
5. **Timing**: Sequence compressed or confused

### Example: Seven's Awakening
- Week 1 (local): "Something awakened at Vel'Thoras"
- Week 3 (regional): "A vampire escaped from the ruins"
- Week 6 (continental): "Demon unleashed by foolish scholars"
- Week 8 (cross-border): "Valdrian experiment threatens all"

---

## Intelligence Networks

### Valdrian Eye
- Coverage: All major Valdrian cities, key foreign cities
- Method: Paid informants, diplomatic staff
- Reporting: Weekly summaries to court
- Blind spots: Northern interior, Silverwood, goblin lands

### Northern Wolves
- Coverage: Border regions, military movements
- Method: Military scouts, merchant debriefing
- Reporting: Daily to command, weekly to court
- Blind spots: Maritime, Sanctified interior, dwarven holds

### Maritime Information Market
- Coverage: All ports, trade routes, banking
- Method: Bought information, merchant gossip
- Reporting: Continuous through trade networks
- Blind spots: Interior regions, non-trading communities

### Church Network
- Coverage: Everywhere the Church operates
- Method: Confession, pilgrimage, wandering priests
- Reporting: Quarterly to hierarchy
- Blind spots: Non-human societies, atheist communities
```

---

## Task 4.2: Information Broker Network

**Source**: audit-pass2-05-gaps.md
**File**: Add section to `communication-infrastructure.md`

**Implementation**:

```markdown
## Information Broker Network

### Major Brokers

**Lysander Vex (Port Sovereign)**
- Specialty: Artifact expeditions, faction movements
- Network: Sailors, merchants, scholars
- Method: Trade information for information
- Reputation: Accurate but expensive

**The Whisper (Valdris Prime)**
- Specialty: Court politics, succession intelligence
- Network: Servants, minor nobles, courtesans
- Method: Gold for secrets
- Reputation: Fast but sometimes wrong

**Brother Silence (Solarium)**
- Specialty: Religious movements, Order activities
- Network: Disaffected priests, pilgrim routes
- Method: Sanctuary for secrets
- Reputation: Slow but very reliable

**Merchant-Prince's Ear (Port Sovereign)**
- Specialty: Banking, trade routes, shipping
- Network: Clerks, captains, warehouse workers
- Method: Commercial arrangements
- Reputation: Narrow focus but deep

### Pricing (Information Trade)

| Information Type | Trade Value | Gold Equivalent |
|-----------------|-------------|-----------------|
| Rumor | Rumor | 1-5 crowns |
| Verified fact | Verified fact | 10-20 crowns |
| Political secret | Secret | 50-100 crowns |
| Military intelligence | Exclusive | 200-500 crowns |
| Faction operation | Dangerous | 500-1000 crowns |
| Assassination contract | Life-changing | 2000+ crowns |

### Risks
- Information sold to multiple buyers (no exclusivity)
- Deliberate misinformation (verify before acting)
- Broker loyalty bought (they can be turned)
- Reputation damage (clients tracked)
```

---

## Task 4.3: Faction Knowledge Gaps

**Source**: audit-pass2-05-gaps.md
**File**: Add section to `knowledge-matrix.md`

**Implementation**:

```markdown
## Critical Knowledge Gaps by Faction

### What Valdrian Empire Doesn't Know
- Northern is more desperate than they appear (grain crisis severe)
- Ironpeak is considering abandoning neutrality (succession debate)
- Order of Dawn operates in Valdris (hidden chapter)
- Maritime coup may resolve soon (banking faction winning)
- Seven exists and what he represents

### What Northern Dominion Doesn't Know
- Their grain dependency is known to everyone
- Valdrian succession will affect food supply
- Inheritors have been at Vel'Thoras for months
- Dwarven succession may end neutrality
- Their princess Helena still reports to Valdris

### What Sanctified States Doesn't Know
- Persecution is destroying their economic base
- Order of Dawn true funding level and hidden operations
- Scholars fleeing are being recruited by rivals
- Maritime and Valdris are considering intervention
- Their agricultural surplus gives them power they're not using

### What Maritime Republic Doesn't Know
- Coup has damaged their information reliability
- Banking faction and merchant faction both plan betrayal
- Lysander Vex knows their financial secrets
- Dwarven debt position is more leveraged than reported
- Inheritors have infiltrated their university

### What Ironpeak Doesn't Know
- Their neutrality is more resented than respected
- Surface powers discuss coordinated response to debt calls
- Their food dependency is their true weakness
- Succession debate is known outside (spies in holds)
- Humans consider attacking if dwarves choose sides

### What Silverwood Doesn't Know
(Intentionally mysterious)
- Modern political alignments
- Current faction capabilities
- How much has been lost since closure
- Whether their preparations will be sufficient

### What Goblins Don't Know
- They're being manipulated by multiple factions
- Blood magic may be harming them from inside
- Some humans might ally with them against common enemies
- Their sanctuaries may be compromised
- Seven may not be what they expect
```

---

## Task 4.4: Message Interception and Security

**Source**: audit-pass2-05-gaps.md
**File**: Add section to `communication-infrastructure.md`

**Implementation**:

```markdown
## Message Security

### Interception Methods

**Physical**:
- Courier ambush (common in contested territory)
- Port inspection (routine for ships)
- Bribed relay station (expensive but effective)
- Stolen diplomatic pouch (act of war)

**Cryptographic**:
- Code-breaking (most faction codes breakable)
- Stolen cipher keys (espionage priority)
- Turned agents (inside access)

**Social**:
- Informants in receiving office
- Seduction of messengers
- Blackmail of officials

### Security Measures

**Inheritor Crystals**:
- Cannot be intercepted (magical)
- Limited by crystal availability
- Messages can be overheard if crystal stolen

**Diplomatic Pouches**:
- Theoretically inviolate
- Actually opened when possible
- Best protection: multiple copies by different routes

**Code Systems**:
- All major factions use codes
- Most are breakable within weeks
- Best codes change monthly (expensive)

**Oral Messages**:
- Memorized, never written
- Courier assassination loses message
- Torture usually works

### Cost of Security

| Level | Method | Cost | Protection |
|-------|--------|------|------------|
| None | Open message | 1-5 crowns | None |
| Basic | Sealed letter | 5-10 crowns | Casual reading |
| Coded | Cipher | 20-50 crowns | Days to break |
| Secure | Multiple routes | 100+ crowns | Partial delivery |
| Maximum | Memorized + suicide | 500+ crowns | Capture doesn't help |

### Known Compromises

- Valdrian codes broken by Northern (suspected)
- Maritime banking codes broken by Inheritors (confirmed)
- Order of Dawn codes broken by Veil Keepers (confirmed)
- Pilgrim route infiltrated by all sides (known)
- Dwarven commercial codes unbroken (so far)
```

---

## Verification Checklist

After Phase 4 implementation, verify:

- [ ] Every faction has documented communication speed
- [ ] Message costs are quantified
- [ ] Information distortion patterns are clear
- [ ] Broker network provides information access paths
- [ ] Each faction has documented knowledge gaps
- [ ] Security costs and risks are specified

---

## Files to Create/Modify

1. Create `09-plot-architecture/communication-infrastructure.md`
2. Update `09-plot-architecture/knowledge-matrix.md` - Knowledge gaps
