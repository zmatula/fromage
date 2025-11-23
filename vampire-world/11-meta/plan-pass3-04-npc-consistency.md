# Phase 4: NPC Consistency

## Overview
Resolve NPC contradictions and knowledge inconsistencies.

---

## Task 4.1: Aldric XII Economics and Logistics

**Source**: audit-pass3-02-npc-integration.md
**File**: `06-characters/supporting/warlord-king-aldric-xii.md`

**Issues**:
- Personal treasury 80k doesn't match 1.5M military authority
- "Doesn't know logistics fragility" contradicts grain crisis motivation

**Implementation**:
Update Economic Position section:

```markdown
## Economic Position

### Personal vs State Wealth
- **Personal treasury**: ~80,000 crowns (royal estates, hunting rights)
- **State treasury access**: ~300,000 crowns reserves (as king)
- **Annual state revenue**: ~1,700,000 crowns (controls allocation)

### The Distinction
Aldric's personal wealth is modest for a king—he's a warrior, not a merchant. But he controls the Northern treasury and can direct its spending. The 80,000 crowns are HIS; the 1,700,000 crowns are the KINGDOM's that he commands.

### Stakes
- Personal: Legacy, dynasty, honor
- State: 600,000 crowns/year grain dependency, military dominance
```

Update Knowledge section:

```markdown
## Knowledge

### Knows
- Grain crisis is severe (that's why he's acting)
- Must invade before war, not after (stockpile first)
- Valdrian succession creates opportunity
- His military can defeat Valdrian forces in field

### Believes
- Northern strength will compensate for supply weakness
- Quick victory will solve logistics before they break
- Honor demands action over caution

### Doesn't Know
- **How quickly logistics collapse under extended campaign** (expects 6 months, reality is 3)
- That Helena still reports to Valdrian intelligence (suspects contact but not scope)
- That dwarves might abandon neutrality if he wins too decisively
- That Sanctified surplus could solve grain crisis without war
```

---

## Task 4.2: Aurelius Institutional Crisis Awareness

**Source**: audit-pass3-02-npc-integration.md
**File**: `06-characters/supporting/grand-master-aurelius.md`

**Issue**: Doesn't emphasize that persecution revenue funds Sanctified state

**Implementation**:
Update Motivations section:

```markdown
## Motivations

### Primary Drive
Destroy all vampire remnants and those who would use them

### Secondary Concerns
- Maintain Order's military readiness
- Expand Order influence in other realms
- **Justify Order's existence to secular authorities**

### The Institutional Pressure
Aurelius knows—though he doesn't dwell on it—that Sanctified States depend on confiscation revenue to cover their budget deficit. The Order's hunts produce that revenue. If darkness disappeared, the Order would lose purpose AND the state would lose funding.

This creates unconscious incentive to always find threats. Aurelius isn't corrupt—he genuinely believes darkness is everywhere. But his belief conveniently justifies the Order's existence and the state's solvency.

### What He Tells Himself
"The darkness is real. We hunt because we must, not because we profit. That our success also funds the state is Divine providence, not corruption."

### Fears
- That he might be wrong (unbearable)
- That the Order might become unnecessary
- That doubt would spread among knights
```

---

## Task 4.3: Helena/Aldric Knowledge Standardization

**Source**: audit-pass3-02-npc-integration.md
**Files**:
- `06-characters/supporting/warlord-king-aldric-xii.md`
- `06-characters/supporting/princess-helena-valorian.md`

**Issue**: Conflicting accounts of what Aldric knows about Helena's intelligence work

**Implementation**:
Standardize across both files:

In warlord-king-aldric-xii.md:
```markdown
### Doesn't Know
- The full extent of Helena's intelligence reports (knows she contacts family, doesn't realize it's operational intelligence)
```

In princess-helena-valorian.md:
```markdown
## The Intelligence Question

### What Aldric Knows
- Helena maintains contact with Valdrian relatives (expected)
- Some of her correspondence is coded (suspicious but not confronted)
- She receives visitors from Valdris occasionally (noted but tolerated)

### What Aldric Doesn't Know
- Contact is systematic intelligence reporting
- She has dead drops and courier protocols
- Her reports include military positioning and supply information

### What Helena Doesn't Know
- Aldric has noticed more than he lets on
- Commander Vara suspects and is watching
- She's being allowed to operate as potential double agent

### The Unspoken Agreement
Both know something is happening. Neither confronts it directly. Aldric because he loves her and needs the alliance. Helena because she fears the consequences. This fragile ignorance cannot last.
```

---

## Task 4.4: Helena Linguistic Code-Switching

**Source**: audit-pass3-02-npc-integration.md
**File**: `06-characters/supporting/princess-helena-valorian.md`

**Issue**: After 10 years in North, should show more Northern patterns in speech

**Implementation**:
Expand Speech Patterns section:

```markdown
## Speech Patterns

### The Two Voices

**In Valdrian Context** (with relatives, ambassadors, in correspondence):
- Formal structure with embedded clauses
- Wine and seasonal metaphors
- Elaborate courtesies before substance
- "One might observe that the vintage of this alliance requires careful decanting..."

**In Northern Context** (with Aldric, military, at court):
- Direct statements, minimal elaboration
- Hunting and weather metaphors
- Substance before courtesy
- "The alliance holds. Winter's coming. We prepare."

**In Mixed Context** (stress, surprise, private):
- Hesitation between patterns
- Starts formal, shifts direct mid-sentence
- Self-aware about the performance
- "One might—no. The truth is simple. I don't know what I am anymore."

### Sample Lines

**To Valdrian envoy**: "The hospitality of my husband's court reflects well on Northern civilization. You'll find the arrangements... adequate to your station. The wine cellar is, I confess, less refined than I would prefer."

**To King Aldric**: "The envoy arrived. He's watching everything. I'll handle him."

**To herself**: "Ten years. Half my adult life. Am I still Valdrian? Was I ever really Northern? The children are both. I am neither."

### The Tell
When genuinely stressed, Helena loses control of code-switching. She'll use Valdrian formality to create distance, then snap to Northern directness when she needs to act. People who know both patterns can read her emotional state.
```

---

## Verification Checklist

After Phase 4:
- [ ] Aldric XII personal vs state wealth clarified
- [ ] Aldric XII logistics knowledge is specific, not general
- [ ] Aurelius shows awareness of institutional funding pressure
- [ ] Helena/Aldric knowledge aligned across both files
- [ ] Helena shows genuine linguistic code-switching with examples

---

## Files to Modify

1. `06-characters/supporting/warlord-king-aldric-xii.md` - Economics, knowledge
2. `06-characters/supporting/grand-master-aurelius.md` - Institutional pressure
3. `06-characters/supporting/princess-helena-valorian.md` - Knowledge, speech
