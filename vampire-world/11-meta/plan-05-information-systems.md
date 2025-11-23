# Phase 5: Information Systems

## Overview
These additions create the information economy—how secrets are kept, how rumors spread, who knows what, and what it costs to maintain or obtain information.

---

## Task 5.1: Information Broker Character

**Source**: audit-08-information.md
**File**: Create `06-characters/supporting/lysander-vex.md`

**Implementation**:

```markdown
# Lysander Vex ("The Cartographer")

## Basic Information
- **Role**: Information broker
- **Location**: Port Sovereign, Maritime Republic
- **Age**: 47
- **Background**: Former Inheritor operative, left after ethical disagreement

## Appearance
Nondescript by design—medium height, brown hair graying at temples, forgettable face. Dresses as middle merchant. Only distinguishing feature: never sits with back to door.

## Operation

### Network
- Runs information trading network from rotating tavern locations
- Contacts include: sailors, merchants, thieves, scholars, minor spies
- Buys information, verifies through multiple sources, sells to highest bidder
- Never sells to only one buyer (maintains multiple revenue streams)

### Methodology
- Pays for information in kind (trades secrets, not gold)
- Verifies before selling (reputation depends on accuracy)
- Never reveals sources (would destroy network)
- Maintains "neutral" reputation (sells to all factions)
- Disappears when things get too hot

### Pricing (Information Trades)
- Rumor for rumor (lowest tier)
- Verified fact for verified fact (mid tier)
- Secret for secret (high tier)
- Exclusive for exclusive (highest—something no one else has)

## Knowledge

### What He Knows
- Who is looking for what (demand tracking)
- What each faction actually knows vs believes
- Which secrets are actually secret
- Who has been asking about protagonist
- Where money is flowing (follows funding)

### What He Trades
- Artifact locations and expedition outcomes
- Political intelligence (who's allying, who's betraying)
- Academic discoveries before publication
- Military movements and supply purchases
- Personal secrets of powerful people

### What He Won't Trade
- Information that would cause mass death (has limits)
- His sources (would end his business)
- His own past (Inheritor connection stays hidden)

## Relationships

### Factions
- **Inheritors**: Former member; they want him back or silenced
- **Veil Keepers**: They know he exists; constant surveillance
- **Maritime Council**: Tolerated because useful; would arrest if convenient
- **Order of Dawn**: Would execute him if they knew extent of knowledge

### Potential Protagonist Interaction
- Recognizes Seven as vampire (knows the signs)
- Calculates value: enormous but dangerous
- Possible trades: Information about pursuing factions for Seven's story
- Risk: Everyone wants what he knows about Seven's location

## Cultural DNA

### Speech Patterns
- Never direct answers ("That depends on what you're offering")
- Questions wrapped in questions
- Maritime merchant cadence
- Reveals nothing personal

### Knowledge Limitations
- Doesn't know Silverwood (no contacts inside)
- Doesn't know deep dwarven politics (holds too sealed)
- Doesn't know true Veil Keeper leadership structure
- Doesn't know his own Inheritor file (what they have on him)

## Story Function
- Demonstrates how information actually circulates
- Provides protagonist access to faction knowledge
- Shows rumor economy in action
- Morally ambiguous (profits from everyone's problems)
- Potential ally or threat depending on protagonist choices
```

---

## Task 5.2: Secret-Keeping Costs

**Source**: audit-08-information.md
**File**: Add sections to relevant faction/character files

**Implementation**:

### Vera's Three-Family Surveillance
Add to Vera's file or true-origins.md:

```markdown
## Surveillance of Founder Families

### Current Operations
- **Ashford family**: 2 watchers, monthly reports
- **Thornwood family**: 1 watcher, quarterly reports
- **Vane family**: 2 watchers, monthly reports (most suspicious activity)

### Annual Cost
- Watcher salaries: 300 crowns/year
- Travel and expenses: 150 crowns/year
- Emergency funds: 100 crowns/year
- **Total: ~550 crowns/year** (significant portion of Vera's budget)

### Risk Assessment
- Watchers might be turned (each is potential leak)
- Families might notice surveillance (would trigger investigation)
- Evidence of surveillance would confirm something worth hiding
- Vera must personally review reports (time cost)

### Current Status
- Helena Ashford now investigating organization origins (convergence imminent)
- Thornwood family expanding scholarly interests (getting closer)
- Vane family has hired genealogist (direct threat)
- Estimated time until discovery: 6-18 months

### Decision Point
When truth emerges, Vera must choose:
- Confess and reshape organization
- Eliminate discoverers (become what ancestors were)
- Flee and abandon position
```

### Goblin Sanctuary Memory Shamans
Add to goblin culture file or secret documentation:

```markdown
## Memory Shaman Protocol

### Structure
- Only 7 shamans know sanctuary locations at any time
- Knowledge passed through ritual transfer (one-to-one)
- Transfer takes 3 years of preparation
- Failed transfer = lost knowledge forever

### Selection Process
- Candidates identified in childhood
- 20 years of testing and observation
- Final 3 candidates chosen at age 50
- Ritual selects one; others' memories blocked

### Historical Losses
- Year 412: Shaman Keth captured, tortured, died without revealing (successful)
- Year 687: Shaman Vros died before transfer; knowledge gap
- Year 891: Shaman Malk went mad; had to be eliminated
- Year 1195: Shaman Keth'la died unexpectedly; emergency transfer to unprepared successor

### Current Vulnerability
- Successor from Year 1195 transfer is undertrained
- One shaman is elderly (may die before proper transfer)
- If vampire returns, bounty for location will be enormous
- Three shamans have never been tested under torture

### Why It Works
- Vampire-hating cultures expect torture; goblins trained to resist
- Cultural narrative: sanctuaries are myth (fewer seekers)
- Memory transfer includes psychological conditioning
- Death before revelation is religious requirement
```

### Veil Keeper Living Artifact Containment
Add to Veil Keeper documentation:

```markdown
## Living Artifact Containment Protocol

### Physical Requirements
- Sealed chamber in secure location
- Blood feeding: 1 pint/week (from volunteers)
- Temperature and humidity control
- Constant observation (3 shifts)

### Annual Cost
- Facility maintenance: 500 crowns/year
- Personnel (9 observers, 3 shifts): 900 crowns/year
- Blood acquisition: 200 crowns/year
- Security systems: 300 crowns/year
- **Total: ~1,900 crowns/year** (major budget line)

### Research Value
- Artifact shows awareness, responds to questions sometimes
- Provides glimpses into vampire psychology
- May know stasis chamber locations
- Refuses to cooperate fully; gives partial information

### Current Conflict
- King Aldric XII demands return
- Veil Keepers believe he'd use it as weapon
- Artifact itself seems to want to go to Northern (suspicious)
- Stalemate: Aldric won't admit what it is publicly; Veil Keepers won't admit they have it

### Risk Assessment
- If containment fails, artifact escapes (consequence unknown)
- If Northern attacks Veil Keeper holdings, artifact is vulnerable
- Artifact may be manipulating its keepers (can't rule out)
```

---

## Task 5.3: Information Distortion Examples

**Source**: audit-08-information.md
**File**: Create `03-cultures/information-distortion.md` or add to cultural-memory-matrix.md

**Implementation**:

```markdown
# Information Distortion: Case Studies

## Year 812 Incident - Four Cultural Versions

### The Event (Approximate Truth)
- Mining operation discovered stasis vampire
- Vampire partially awakened
- Church-Veil Keeper operation contained it
- All witnesses eliminated
- Cover story: mine collapse

### Human Version (Church-Influenced)
**Narrative**: "A demon awakened in the dark places. The righteous warriors of the Church destroyed it with divine aid. The creature's evil corruption threatened the world, but faith protected us."

**How It Spreads**: Church sermons, pilgrim routes, folk memory
**Who Believes It**: Rural populations, religious communities
**Function**: Reinforces Church authority, divine protection narrative

### Elf Version (Academic-Influenced)
**Narrative**: "An ancient vampire experiment failed catastrophically. The Church contained the damage but lost many warriors. The incident demonstrates the danger of vampire artifacts in the world."

**How It Spreads**: Academic correspondence, scholarly discussion
**Who Believes It**: Educated populations, scholars
**Function**: Historical analysis, caution about artifacts

### Dwarven Version (Practical)
**Narrative**: "Another vampire incident underground. The humans handled it their way. We were not involved. This demonstrates why we sealed our holds and stayed out of surface politics."

**How It Spreads**: Merchant gossip, dwarf-to-dwarf storytelling
**Who Believes It**: Dwarves and their trading partners
**Function**: Justifies dwarven isolation and neutrality

### Goblin Version (Anger-Inflected)
**Narrative**: "The humans found one of our captors hiding in the dark. They fought it, but many humans died—why should we care? The vampire was one of those who enslaved us. Better to let them kill each other."

**How It Spreads**: Oral storytelling, goblin communities
**Who Believes It**: Goblins
**Function**: Maintains human-as-oppressor narrative, vampire-as-enemy narrative

### By Year 850 (40 Years Later)
All four cultures remember "Year 812" but describe events so differently they might be discussing different incidents.

---

## The Liberation - Four Cultural Versions

### Human Version
"We rose up and threw off our chains. Sister Mercy led us to the light."

### Elf Version
"We preserved knowledge while others destroyed. When the moment came, we emerged to guide."

### Dwarven Version
"We sealed our holds and survived. When the chaos ended, we emerged to trade."

### Goblin Version
"We fought and died while others hid. The liberation is our blood price."

### Truth
All four happened. All four are incomplete. None acknowledge the others' contributions.

---

## Protagonist's Future - Predicted Distortions

When Seven awakens, predict how story will distort:

**Week 1-2**: "Strange occurrence at Vel'Thoras" (factual, incomplete)
**Week 3-4**: "Monster awakens in the north" (dramatic, partly wrong)
**Month 2**: "Vampire returns—the end times come" (prophetic, fear-driven)
**Month 3**: "Demon sent to test the faithful" (Church narrative)
**Month 6**: Multiple contradictory legends, none accurate

Each culture will fit Seven into their existing narratives.
```

---

## Task 5.4: Propaganda Campaigns

**Source**: audit-08-information.md
**File**: Add to faction files or create `09-plot-architecture/propaganda-campaigns.md`

**Implementation**:

```markdown
# Active Propaganda Campaigns (Year 1200)

## Church Campaign: "The Growing Corruption"

### Created
Year 1198 (response to dimensional readings)

### Funded By
Church budget (~30,000 crowns/year)

### Method
- Sunday sermons (standard messaging)
- Traveling priests (reach rural areas)
- Printed pamphlets (expensive, limited distribution)
- Public executions with religious framing

### Message
"Dark forces stir. The corruption grows. Only faith and vigilance protect us. Report suspicious activity. Trust the Church."

### Target Audience
Rural populations who fear magic, urban poor seeking meaning

### Effectiveness
- High in Sanctified States (believed by 70%)
- Medium in rural Valdris (40%)
- Low in Maritime (20%)
- Creates fear but also resistance to "fearmongering"

### Cost
Equivalent to training 30 priests for year; competes with other Church priorities

---

## Northern Campaign: "Weakness of Weak Kingdoms"

### Created
Year 1195 (King Aldric's strategic communication)

### Funded By
Royal military communications budget (~15,000 crowns/year)

### Method
- Military dispatches to allies
- Diplomatic letters to neutral powers
- Merchant rumors (subsidized)
- Bard songs celebrating Northern strength

### Message
"Valdrian succession shows weakness. Maritime coup shows instability. Sanctified persecution shows madness. Only the Northern Dominion stands strong."

### Target Audience
Neutral powers, potential allies, Northern population (morale)

### Effectiveness
- Rallies Northern population (believed by 80%)
- Persuades some neutrals (30%)
- Offends targets (counterproductive with Valdris, Maritime, Sanctified)

---

## Counter-Propaganda: "The Order Grows Radical"

### Created
Year 1199 (Valdrian/Maritime scholarly response)

### Funded By
University networks, some merchant backing (~10,000 crowns/year)

### Method
- Academic publications
- Theological debates
- Refugee testimonials
- Scholarly correspondence

### Message
"The Order of Dawn has abandoned reason. Their persecution targets innocents. This extremism threatens all of us."

### Target Audience
Educated populations, religious moderates

### Effectiveness
- High among scholars (70%)
- Medium among urban educated (40%)
- Low among general population (15%—they don't read academic papers)

### Challenge
Reaches only literate minority; most people never see it
```

---

## Task 5.5: "Who Knows What" Matrix

**Source**: audit-08-information.md
**File**: Create `09-plot-architecture/knowledge-matrix.md`

**Implementation**:

```markdown
# Knowledge Matrix: Major Secrets

## Secret: Protagonist's Location (Vel'Thoras)

| Faction | Knows For Certain | Believes | Suspects | Wrong About |
|---------|-------------------|----------|----------|-------------|
| Inheritors | Location, approaching awakening | Can be controlled | Veil Keepers will try to kill | His willingness to cooperate |
| Veil Keepers | Location, danger level | Must be destroyed | Inheritors will get there first | That he might cooperate |
| Order of Dawn | Vampire exists | Located in north | Awakening imminent | What he actually is |
| Northern Military | Activity at Vel'Thoras | Something valuable | Inheritors involved | Why it matters |
| Valdrian Court | Nothing | Nothing | Nothing | Everything |
| Silverwood | Unknown (closed borders) | Unknown | Unknown | Unknown |

## Secret: Inheritor Founding Murders

| Faction | Knows | Suspects | Wrong About |
|---------|-------|----------|-------------|
| Vera | Complete truth | Nothing (she knows) | How to handle it |
| Helena Ashford | Her ancestor died suspiciously | Organization hiding something | Scope of the crime |
| Thornwood family | Nothing | Their ancestor was important | That he was murdered |
| Vane family | Genealogist hired | Family has secrets | What the secrets are |
| General Inheritors | Nothing | Nothing | That origins are honorable |

## Secret: Silverwood's Purpose

| Faction | Knows | Suspects | Wrong About |
|---------|-------|----------|-------------|
| All outside powers | Nothing | Isolation is defensive | Why they closed |
| Silverwood elders | Complete truth | Nothing | How outsiders will react |
| Silverwood young | Nothing | Elders hiding something | Whether it matters |
```

---

## Verification Checklist

After Phase 5 implementation, verify:

- [ ] Information broker character created with full details
- [ ] Secret-keeping costs are specific and visible
- [ ] Information distortion shows same event as four stories
- [ ] Propaganda campaigns have funding, method, effectiveness
- [ ] Knowledge matrix tracks who knows what about major secrets

---

## Files to Create/Modify

1. Create `06-characters/supporting/lysander-vex.md`
2. Modify `04-factions/secret-societies/true-origins.md` - Vera's surveillance
3. Modify `03-cultures/races/goblins.md` - Memory shaman protocol
4. Modify Veil Keeper documentation - Artifact containment
5. Create `03-cultures/information-distortion.md`
6. Create `09-plot-architecture/propaganda-campaigns.md`
7. Create `09-plot-architecture/knowledge-matrix.md`
