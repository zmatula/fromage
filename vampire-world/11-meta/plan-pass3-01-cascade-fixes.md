# Phase 1: Cascade Fixes

## Overview
Backpropagate numbers from faction files to coordinating documents.

---

## Task 1.1: Northern Military Force Size

**Source**: audit-pass3-01-numeric-cascade.md
**File**: `09-plot-architecture/present-day-crises.md`

**Issue**: Line 277 says "40,000 professional soldiers" but northern-dominion.md says 30,000

**Implementation**:
Find and replace in present-day-crises.md:

```markdown
## Northern Expansion
...
**Military Strength**: 30,000 professional soldiers with 50,000 feudal levies available within 30 days (80,000 total rapid deployment)
```

Add clarifying note that "80,000" includes levies, not all professionals.

---

## Task 1.2: Northern Military Budget

**Source**: audit-pass3-01-numeric-cascade.md
**File**: `09-plot-architecture/economic-framework.md`

**Issue**: Line 14 says "Northern military budget: 800,000 crowns" but northern-dominion.md says 1,500,000

**Implementation**:
Update economic-framework.md "For Comparison" section:

```markdown
## For Comparison (Annual Scales)
- Valdrian Imperial budget: ~2,000,000 crowns
- Northern military budget: ~1,500,000 crowns
- Total artifact trade: ~500,000 crowns
- Order of Dawn (true): ~950,000 crowns
```

---

## Task 1.3: Resolve Aurelius vs Brennan

**Source**: audit-pass3-02-npc-integration.md
**Files**:
- `09-plot-architecture/present-day-crises.md`
- `06-characters/supporting/grand-master-aurelius.md`

**Issue**: Brennan identified as supreme leader in present-day-crises, Aurelius in faction/NPC files

**Implementation**:
Option A (Consolidate): Replace all Brennan references with Aurelius

In present-day-crises.md, find "High Confessor Brennan" and replace:

```markdown
**Order of Dawn**: Grand Master Aurelius Dawnbringer commands the Order's military forces from Dawnhaven. His certainty that darkness is rising drives aggressive hunting operations.
```

Remove any other Brennan references.

---

## Task 1.4: Northern Revenue Clarity

**Source**: audit-pass3-01-numeric-cascade.md
**File**: `04-factions/empires/northern-dominion.md`

**Issue**: 1.5M appears as both treasury and military cost—impossible if no other spending

**Implementation**:
Add revenue breakdown to northern-dominion.md economic section:

```markdown
## Economic Foundation

### Annual Revenue
- Land taxes: ~800,000 crowns
- Trade tariffs: ~400,000 crowns
- Royal holdings: ~300,000 crowns
- Tribute/fees: ~200,000 crowns
- **Total revenue: ~1,700,000 crowns**

### Annual Expenditure
- Military (30,000 professionals): 1,500,000 crowns
- Administration: ~100,000 crowns
- Infrastructure: ~50,000 crowns
- Reserves: ~50,000 crowns
- **Total: ~1,700,000 crowns**

### Treasury Position
- Current reserves: ~300,000 crowns
- Strategic grain stockpile: 4 months (critically low)
- War chest: Insufficient for extended campaign
```

---

## Verification Checklist

After Phase 1:
- [ ] 30,000 professionals appears in present-day-crises.md
- [ ] 1,500,000 budget appears in economic-framework.md
- [ ] No Brennan references remain (only Aurelius)
- [ ] Northern revenue total documented (~1.7M)

---

## Files to Modify

1. `09-plot-architecture/present-day-crises.md` - Military size, Aurelius
2. `09-plot-architecture/economic-framework.md` - Northern budget
3. `04-factions/empires/northern-dominion.md` - Revenue breakdown
