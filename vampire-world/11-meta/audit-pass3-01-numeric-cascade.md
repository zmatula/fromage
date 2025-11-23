# Third-Pass Audit: Numeric Cascade

## Overview
Verifies second-pass numbers cascade correctly through all references.

---

## Verified Cascades (Working)

### Valdris River Toll 200k ✓
- Source: economic-framework.md:269, valdrian-empire.md:194
- Both use consistent 200,000 crowns/year

### Northern Grain 9M Bushels ✓
- Source: northern-dominion.md:221
- Cascades to economic-framework.md:317-318 (3.6M imports at 40%)
- Math: 3 bushels × 3M population = 9M ✓

### Northern Import Cost 600k ✓
- Source: northern-dominion.md:230
- Matches economic-framework.md:318
- Breakdown: 450k Valdrian + 150k Sanctified = 600k ✓

### Sanctified Revenue 1.5M ✓
- Source: sanctified-states.md:216
- Internal calculation: 800k + 500k + 200k = 1.5M ✓

### Dwarven Food 80% Import ✓
- Source: ironpeak-confederation.md:192
- Strategic impact documented (3-month blockade limit)

---

## Cascade Failures

### CRITICAL: Northern Military Force Size Discrepancy

**Number**: 30,000 vs 40,000 professionals

**Source**: northern-dominion.md:139 = "Core professionals: 30,000 warriors"

**Missing from**: present-day-crises.md:277 = "40,000 professional soldiers"

**Severity**: CRITICAL

**Impact**:
- Overstates Northern deployment by 33%
- War planning uses wrong force ratios
- Battle scenarios miscalculate tactical advantage

**Fix**: Update present-day-crises.md:277 to "30,000 professional soldiers" with note that 40k includes rapid levy mobilization

**Note**: plan-pass2-01-numeric-fixes.md line 246 identified this but fix was not implemented

---

### HIGH: Northern Military Budget Mismatch

**Number**: 800,000 vs 1,500,000 crowns

**Source**: northern-dominion.md:140-141 = "1,500,000 crowns" for 30,000 professionals

**Missing from**: economic-framework.md:14 = "Northern military budget: 800,000 crowns"

**Severity**: HIGH

**Impact**:
- Misrepresents Valdrian/Northern spending ratio (2:0.8 vs actual 2:1.5)
- Affects strategic vulnerability assessments

**Fix**: Update economic-framework.md:14 to "1,500,000 crowns"

---

### MEDIUM: Northern Treasury Clarity

**Issue**: 1.5M appears as both treasury assets AND military budget

**Sources**:
- economic-framework.md:393 = "Treasury: ~1.5 million crowns"
- northern-dominion.md:140 = "Funded by: Royal treasury (1,500,000 crowns)"

**Problem**: If treasury = 1.5M and military = 1.5M, then 0 for other spending

**Fix**: Clarify Northern total revenue (should be 2-3M to fund state + military)

---

## Missing Cascades

### Sanctified 1.5M Not in Economic Framework

**Where defined**: sanctified-states.md:216
**Should appear**: economic-framework.md Church Treasury section
**Fix**: Add cross-reference to sanctified-states.md for complete picture

### Dwarven 80% Food Not in Trade Dependencies

**Where defined**: ironpeak-confederation.md:192
**Should appear**: economic-framework.md:329-333 (Dwarven Metal Monopoly)
**Fix**: Add note that dwarves are vulnerable to same food leverage they hold over others

---

## Summary

**Working**: 5/6 numbers cascade correctly in primary documents

**Pattern**: Phase 1 fixes implemented in faction files but NOT backpropagated to economic-framework.md, creating inconsistency for comparative analysis

**Priority Fixes**:
1. Northern military 30k vs 40k (CRITICAL)
2. Northern budget 800k vs 1.5M (HIGH)
3. Northern treasury clarity (MEDIUM)
