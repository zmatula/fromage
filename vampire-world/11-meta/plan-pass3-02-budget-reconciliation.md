# Phase 2: Budget Reconciliation

## Overview
Resolve budget/capacity mismatches that make claimed operations impossible.

---

## Task 2.1: Order of Dawn Pursuit Capacity

**Source**: audit-pass3-05-cross-system.md
**Files**:
- `04-factions/secret-societies/order-of-dawn.md`
- `09-plot-architecture/economic-framework.md`

**Issue**: Active campaign costs 2.25M but budget is 950k (1.3M deficit)

**Implementation**:
Add "Operational Constraints" section to order-of-dawn.md:

```markdown
## Operational Constraints

### Budget Reality
- Peacetime maintenance: 900,000 crowns/year
- Active campaign cost: 150 crowns/knight × 15,000 = 2,250,000 crowns
- **True budget: 950,000 crowns**
- **Maximum sustainable campaign: 3-4 months before bankruptcy**

### How They Manage Continental Hunt
The Order cannot sustain full mobilization. Instead:

**Rotation System**:
- 5,000 knights active pursuit (750,000 crowns/year)
- 10,000 knights garrison duty (maintains fortresses)
- Rotates quarterly to spread fatigue and cost

**Regional Prioritization**:
- Northern territories: High intensity (Seven's escape route)
- Sanctified States: Medium intensity (home territory)
- Valdrian/Maritime: Low intensity (political complications)

**Hidden Costs**:
- Depleting reserve funds (~100,000 crowns available)
- Accepting noble "donations" with strings attached
- Reducing training and recruitment
- Deferring fortress maintenance

### Strategic Vulnerability
- Extended hunt weakens defenses elsewhere
- Political patrons may demand concessions
- If Seven not found within 6 months, financial crisis
- Success requires early capture or external funding
```

---

## Task 2.2: Veil Keeper Operational Deficit

**Source**: audit-pass3-05-cross-system.md
**File**: `04-factions/secret-societies/veil-keepers.md`

**Issue**: Operations need ~250k but only 165k available (85k deficit)

**Implementation**:
Add "Operational Model" section:

```markdown
## Operational Model

### Why Budget Works

**Volunteer Network**:
- Many agents serve without pay (ideological commitment)
- Only cell leaders and specialists receive stipend
- Reduces personnel cost from 240k to ~100k

**Selective Operations**:
- Continental suppression is myth; actual coverage is regional
- Focus on: Northern (Seven), Maritime (artifact trade), Valdrian (politics)
- Sanctified and Ironpeak largely ignored (lower priority)

**Shared Resources**:
- Use Order of Dawn facilities when aligned
- Piggyback on government intelligence networks
- Barter information rather than pay for it

### Actual Costs
- 12 cells (leadership only): 60,000 crowns
- Specialist agents (30): 45,000 crowns
- Archive and security: 20,000 crowns
- Operations fund: 40,000 crowns
- **Total: 165,000 crowns** (matches budget)

### What This Means
- Cannot pursue Seven AND suppress knowledge simultaneously
- Must choose priorities each quarter
- Failure to find Seven means knowledge spreads
- Success requires allies (Order of Dawn cooperation)
```

---

## Task 2.3: Maritime Information vs Trade

**Source**: audit-pass3-05-cross-system.md
**File**: `04-factions/empires/maritime-republic.md`

**Issue**: "Information reliability damaged" but trade operates normally

**Implementation**:
Add clarifying section:

```markdown
## Post-Coup Recovery (Year 1199-1200)

### What Was Damaged
- **Political intelligence network**: Informants arrested or fled
- **Diplomatic communications**: Ambassadors recalled, couriers suspect
- **Internal security**: Loyalty uncertain, paranoia high

### What Survived Intact
- **Commercial networks**: Trade must continue for revenue
- **Banking operations**: Consortium needs income to survive
- **Shipping routes**: Captains care about cargo, not politics

### Current Status (Year 1200)
- Political intelligence: 40% capacity (rebuilding)
- Commercial intelligence: 90% capacity (never disrupted)
- Overall information reliability: "Moderate" for trade, "Poor" for politics

### Why The Asymmetry
Banking Consortium protected commercial assets but purged political operatives:
- Merchants are loyal to profit, not factions
- Political agents had dangerous knowledge
- Revenue streams take priority over intelligence

This means Maritime knows trade movements but not political intentions.
```

---

## Task 2.4: Propaganda Budget Breakdown

**Source**: audit-pass3-04-information-coherence.md
**File**: `09-plot-architecture/propaganda-campaigns.md`

**Issue**: 30k Church budget claims 70% effectiveness but no breakdown

**Implementation**:
Add detailed budget section:

```markdown
## Church Campaign Budget Breakdown

### Annual Allocation: 30,000 crowns

**Distribution Methods**:

| Method | Cost | Reach | Effectiveness |
|--------|------|-------|---------------|
| Sunday sermons | 5,000 | 80% Sanctified pop | High (weekly) |
| Traveling priests | 12,000 | 40% rural areas | Medium (monthly) |
| Printed pamphlets | 8,000 | 10% literate urban | Low (one-time) |
| Public executions | 5,000 | 30% regional | High (memorable) |

### How 70% Is Achieved
- Sermons reach most Sanctified population weekly
- Traveling priests reinforce message monthly
- Public executions create fear that spreads by word of mouth
- Pamphlets target influential literate minority

### Regional Effectiveness
- Sanctified States (70%): All methods active
- Rural Valdris (40%): Only traveling priests and rumors
- Maritime (20%): Only pamphlets and merchant rumors

### Cost Efficiency
30,000 crowns achieves 70% penetration because:
- Church infrastructure already exists (no new construction)
- Priests are already paid (no additional salary)
- Message is simple ("darkness growing, trust Church")
- Fear spreads faster than information
```

---

## Verification Checklist

After Phase 2:
- [ ] Order pursuit limitations documented with rotation system
- [ ] Veil Keeper volunteer network explains budget
- [ ] Maritime trade vs political intelligence clarified
- [ ] Propaganda budget traced to effectiveness claims

---

## Files to Modify

1. `04-factions/secret-societies/order-of-dawn.md` - Operational constraints
2. `04-factions/secret-societies/veil-keepers.md` - Operational model
3. `04-factions/empires/maritime-republic.md` - Post-coup recovery
4. `09-plot-architecture/propaganda-campaigns.md` - Budget breakdown
