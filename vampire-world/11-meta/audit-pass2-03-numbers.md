# Second-Pass Audit: Numeric Consistency

## Overview
Verifies all numbers work together mathematically.

---

## Numbers That Work

### Order of Dawn Budget (950,000 crowns)
- 15,000 knights × 50 crowns/year = 750,000 ✓
- 30 fortresses × 5,000/year = 150,000 ✓
- Subtotal need: 900,000+ | Budget: 950,000 ✓
- Sources: Church 400k + subsidy 300k + donations 150k + confiscations 100k ✓

### Dwarven Debt Interest
- Valdrian: 500k @ 5% = 25,000 ✓
- Northern: 300k @ 6% = 18,000 ✓
- Maritime: 200k @ 4% = 8,000 ✓
- Sanctified: 150k @ 5% = 7,500 ✓
- Total: 58,500 ≈ 60,000 documented ✓

### Northern Food Import Pricing
- Valdrian: 900,000 bushels ÷ 150,000 crowns = 0.167 crowns/bushel ✓
- Sanctified: 300,000 bushels ÷ 50,000 crowns = 0.167 crowns/bushel ✓
- Consistent pricing across sources ✓

### Iron Gate Pass Revenue
- Trade flow: ~2 million crowns
- Toll rate: 5%
- Revenue: 100,000 crowns ✓

### Maritime Coup Timeline
- Liquid assets: 500,000 crowns
- Burn rate: 50,000/month
- Runway: 10 months ✓

### Travel Time Triangle Inequality
- Port Sovereign → Solarium: 15-20 days
- Solarium → Valdris Prime: 20-25 days
- Direct: 25-30 days
- Triangle satisfied (35-45 via Solarium vs 25-30 direct) ✓

---

## Numeric Problems

### CRITICAL: Valdris River Toll Contradiction

**Locations**:
- economic-framework.md:270 → 80,000 crowns/year
- valdrian-empire.md:194 → 200,000 crowns/year

**Discrepancy**: 150% difference

**Severity**: CRITICAL

**Fix**: Choose one figure based on river economics (800-mile river with 3+ checkpoints suggests higher revenue)

---

### CRITICAL: Northern Grain Consumption Underestimated

**Location**: northern-dominion.md:199-224

**Calculation**:
- Documented: 3 million bushels for 3 million people = 1 bushel/person/year
- Historical reality: 2.5-5 bushels/person/year
- Under-calculation: 250-500%

**Actual Need**: 7.5-15 million bushels (not 3 million)

**Impact**:
- Current 1.8M domestic + 1.2M imports = catastrophically insufficient
- Import requirement should be 5.7-13.2M bushels (76-88% of need)
- War planning becomes logistically impossible

**Severity**: CRITICAL

**Fix**: Recalculate using 2.5-5 bushels/person, adjust all dependencies

---

### HIGH: Northern Military Budget vs Forces

**Location**: northern-dominion.md + economic-framework.md

**Calculation**:
- 80,000 "professional warriors" × 50 crowns = 4 million needed
- Treasury: 1.5 million crowns
- Shortfall: 2.5 million crowns

**Severity**: HIGH

**Fix**: Clarify ~30,000 true professionals (1.5M cost), rest are feudal levies (0 peacetime cost)

---

### HIGH: Sanctified States Economic Data Missing

**Location**: sanctified-states.md

**Issue**: Largest power (5M population, 500K sq miles) has no documented:
- State treasury size
- Agricultural revenue
- State militia costs
- Land value and tithe revenue

**Severity**: HIGH

**Fix**: Add economic data section (30% land ownership should generate 500k+ crowns/year in tithes)

---

### HIGH: Dwarven Economic Data Missing

**Issue**: Dwarves hold 1.15M in debt leverage but:
- No documented mining revenue
- No military budget
- No food import data (mountains can't sustain 1.5M)

**Severity**: HIGH

**Fix**: Add dwarven economic overview explaining how they sustain debt leverage

---

### MEDIUM: Maritime Banking Liquidity

**Calculation**:
- Liquid: 500,000 crowns
- Total assets: ~10 million
- Liquidity ratio: 5% (critical)

**Severity**: Medium (realistic for post-coup desperation but creates vulnerability)

---

### MEDIUM: Population Gap

**Calculation**:
- Documented major powers: ~16.5 million
- Stated continental: ~45 million
- Unaccounted: 28.5 million

**Severity**: Medium (possibly rural populations)

---

## Summary

**Working**: Debt interest, food pricing, pass revenue, coup timeline, travel times

**Critical Issues**:
1. Valdris River tolls (80k vs 200k)
2. Northern grain consumption (1 vs 2.5-5 bushels/person)

**High Issues**:
3. Northern military budget vs forces
4. Sanctified States economic data missing
5. Dwarven economic data missing

The pattern: World is **underfunded** - factions documented but basic revenues unstated, military logistics glossed over
