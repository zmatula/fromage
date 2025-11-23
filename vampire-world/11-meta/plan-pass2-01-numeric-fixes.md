# Phase 1: Critical Numeric Fixes

## Overview
Fix calculation errors that cascade through economic modeling.

---

## Task 1.1: Valdris River Toll Reconciliation

**Source**: audit-pass2-01-verification.md, audit-pass2-03-numbers.md
**Files**:
- `09-plot-architecture/economic-framework.md`
- `04-factions/empires/valdrian-empire.md`

**Issue**: 80,000 vs 200,000 crowns/year

**Implementation**:
Adopt 200,000 crowns/year (higher figure) because:
- 800-mile river with 3+ major checkpoints
- Primary continental trade artery
- More detailed source (faction file)

Update economic-framework.md line ~270:
```markdown
### Valdris River System
- **Length**: 800 miles navigable
- **Control**: Valdrian Empire (complete)
- **Checkpoints**: Valdris Prime, Three Forks, River's End
- **Revenue**: ~200,000 crowns/year in tolls
- **Strategic value**: Blockade = Northern famine within 6 months
```

---

## Task 1.2: Northern Grain Recalculation

**Source**: audit-pass2-03-numbers.md
**File**: `04-factions/empires/northern-dominion.md`

**Issue**: Using 1 bushel/person/year vs realistic 2.5-5

**Implementation**:
Recalculate using 3 bushels/person/year (conservative medieval estimate):

```markdown
## Food Security Crisis

### Consumption Reality
- Population: 3 million
- Per capita need: 3 bushels grain/year (minimum)
- **Total need: 9 million bushels/year**

### Production Capacity
- Domestic production: 5.4 million bushels (60% of need)
- **Import requirement: 3.6 million bushels (40%)**

### Current Sources
- Valdrian Empire: 2.7 million bushels @ 450,000 crowns
- Sanctified States: 900,000 bushels @ 150,000 crowns
- **Total import cost: 600,000 crowns/year**

### Strategic Vulnerability
- Valdrian embargo = 6-month famine window
- Must stockpile 18+ months before any war with Valdris
- Current reserves: ~4 months (critically low)
- War planning requires 2-3 year preparation minimum

### Why This Drives Expansion
- Cannot afford 600,000/year indefinitely
- Must seize farmland or face permanent dependency
- Northern expansion is survival, not ambition
```

Also update economic-framework.md trade dependencies section to match.

---

## Task 1.3: Sanctified States Economic Data

**Source**: audit-pass2-03-numbers.md
**File**: `04-factions/empires/sanctified-states.md`

**Issue**: Largest power has no economic data

**Implementation**:
Add economic section:

```markdown
## Economic Foundation

### Land and Revenue
- Territory: 500,000 square miles (largest)
- Population: 5 million (largest)
- Church land ownership: 30% of arable land
- State land ownership: 40% of arable land
- Private holdings: 30%

### Annual Revenues
- Church tithes (10% of all production): ~800,000 crowns
- State land taxes: ~500,000 crowns
- Trade tariffs: ~200,000 crowns
- **Total state revenue: ~1,500,000 crowns**

### Annual Expenditures
- State militias (100,000 troops @ 30 crowns): 3,000,000 crowns
- **Deficit: 1,500,000 crowns/year**

### How They Manage
- Church subsidizes state military (secret arrangement)
- Confiscations from "heretics" cover ~300,000/year
- Debt to Ironpeak: 150,000 crowns @ 5%
- System is unsustainable without persecution revenue

### Agricultural Surplus
- Production: 20 million bushels/year
- Domestic need: 15 million bushels
- **Export capacity: 5 million bushels**
- Primary customer: Northern Dominion (900,000 bushels)

### Economic Pressure from Persecution
- Scholars fleeing: ~50,000 crowns/year in lost taxes
- Merchants fleeing: ~100,000 crowns/year in lost trade
- Craftspeople fleeing: ~75,000 crowns/year in lost production
- **Total annual loss: ~225,000 crowns (and growing)**
```

---

## Task 1.4: Dwarven Economic Overview

**Source**: audit-pass2-03-numbers.md
**File**: `04-factions/empires/ironpeak-confederation.md`

**Issue**: Hold 1.15M in debt but own economy undocumented

**Implementation**:
Add economic section:

```markdown
## Economic Foundation

### Revenue Sources
- Iron mining and export: ~400,000 crowns/year
- Bloodstone monopoly: ~200,000 crowns/year
- Banking interest (1.15M principal): ~60,000 crowns/year
- Certification services (artifact verification): ~50,000 crowns/year
- **Total revenue: ~710,000 crowns/year**

### Annual Expenditures
- Hold maintenance (7 major holds): ~200,000 crowns
- Military (standing forces): ~150,000 crowns
- Food imports (mountains cannot sustain population): ~250,000 crowns
- **Total expenditure: ~600,000 crowns/year**

### Treasury Position
- Current reserves: ~2,000,000 crowns (estimated)
- Annual surplus: ~110,000 crowns
- Debt holdings: 1,150,000 crowns in loans to surface powers

### Strategic Vulnerability
- **Food dependency**: Must import 80% of grain
- Primary suppliers: Valdrian (60%), Sanctified (40%)
- Cannot sustain blockade longer than 3 months
- Neutrality depends on continued trade access

### Why Debt Weapon Is Limited
- Calling all debts would trigger coordinated retaliation
- Surface powers could embargo food in response
- 3-month food reserve vs years of war
- Leverage works through threat, not execution

### Economic Power Without Military Risk
- Control verification market (is this artifact real?)
- Control currency standards (dwarven coins most trusted)
- Control precision manufacturing (human smiths can't match)
- Control deep earth resources (no competition)
```

---

## Task 1.5: Northern Military Composition Clarification

**Source**: audit-pass2-03-numbers.md
**File**: `04-factions/empires/northern-dominion.md`

**Issue**: 80,000 "professional warriors" exceeds 1.5M treasury

**Implementation**:
Clarify military composition:

```markdown
## Military Forces

### Standing Army (Professional)
- **Core professionals**: 30,000 warriors
- Cost: 50 crowns/year each = 1,500,000 crowns
- Funded by: Royal treasury (1,500,000 crowns)
- Status: Full-time soldiers, highest training

### Feudal Levies (Semi-Professional)
- **Levy obligation**: 50,000 warriors
- Cost: 0 crowns peacetime (lords maintain)
- Wartime cost: 30 crowns/month each (food, equipment)
- Status: Train 2 months/year, available on call

### Reserve Militia
- **Available fighters**: 150,000 able-bodied
- Cost: 0 crowns until mobilized
- Wartime cost: 20 crowns/month each
- Status: Minimal training, last resort

### Total Military Potential
- Peacetime standing: 30,000
- Rapid mobilization (1 month): 80,000
- Full mobilization (3 months): 230,000

### Why "80,000 Warriors" Is Claimed
- Propaganda includes feudal levies as "standing"
- Intimidation factor
- Actual deployable force without levies: 30,000
- With full levy call: 80,000 within 30 days
```

---

## Verification Checklist

After Phase 1 implementation, verify:

- [ ] Valdris River toll is 200,000 everywhere
- [ ] Northern grain need is 9 million bushels
- [ ] Northern import cost is 600,000 crowns
- [ ] Sanctified has complete economic profile
- [ ] Dwarven economy explains debt leverage limits
- [ ] Northern military clearly distinguishes professionals from levies
- [ ] All numbers cascade correctly through dependent calculations

---

## Files to Modify

1. `09-plot-architecture/economic-framework.md` - Valdris toll, trade dependencies
2. `04-factions/empires/northern-dominion.md` - Grain, military composition
3. `04-factions/empires/sanctified-states.md` - Full economic section
4. `04-factions/empires/ironpeak-confederation.md` - Full economic section
5. `09-plot-architecture/present-day-crises.md` - Update Northern crisis numbers
