# Third-Pass Audit: NPC Integration

## Overview
Verifies 10 new NPCs integrate properly with existing faction dynamics.

---

## Well-Integrated NPCs

### Emperor Cassius VIII ✓
- Economic position matches Valdrian profile
- Speech patterns align with imperial cultural DNA
- Relationships reference all succession players correctly
- Knowledge gaps match faction intelligence blind spots

### Duke Aldric Varen ✓
- Economic position consistent with traditionalist noble faction
- Clear desperation creates authentic motivation
- Speech patterns match agricultural cultural DNA

### Duchess Margret ✓
- Highest personal wealth matches merchant faction leadership
- Motivations create succession driver
- Speech patterns consistent with merchant cultural DNA

### High Thane Borin ✓
- 15M reserves correctly represents dwarven leverage
- Speech patterns authentically reflect dwarven cultural DNA
- Motivations create constraint on all powers

### Sister Elena ✓
- Economically dependent creates authentic stakes
- Relationships within Order create realistic conflict
- Motivations drive character arc

---

## Integration Issues

### CRITICAL: Order of Dawn Leadership Contradiction

**NPCs**: Grand Master Aurelius

**Issue**: present-day-crises.md (line 361) identifies "High Confessor Brennan" as supreme leader, but Aurelius's file identifies him as "Grand Master...supreme commander"

**Files**:
- grand-master-aurelius.md (Aurelius as supreme)
- present-day-crises.md:361-362 (Brennan as supreme)
- order-of-dawn.md (confirms Aurelius as Grand Master since 1189)

**Severity**: CRITICAL

**Fix**: Either clarify Brennan and Aurelius are different people with different roles (religious vs military), or consolidate into one character

---

### HIGH: Warlord-King Aldric XII Economic Scale

**Issue**: Personal treasury ~80,000 crowns but military costs 1,500,000/year

**Files**:
- warlord-king-aldric-xii.md:47-53
- northern-dominion.md:140

**Severity**: HIGH

**Fix**: Clarify 80k is personal wealth only with separate state treasury control, or increase to match military authority

---

### HIGH: Aldric XII Logistics Knowledge

**Issue**: "Doesn't know how fragile Northern logistics actually are" but primary motivation IS the grain crisis

**Files**: warlord-king-aldric-xii.md:92

**Severity**: HIGH

**Fix**: Either modify to specific gaps ("doesn't know dwarven alternative") or show he recently discovered fragility

---

### HIGH: Aurelius Economics Don't Reflect Crisis

**Issue**: Order treasury 950k but Sanctified runs 1.5M deficit relying on confiscation revenue—Aurelius should show awareness of perverse incentive

**Files**:
- grand-master-aurelius.md:56-57
- sanctified-states.md:218-227

**Severity**: HIGH

**Fix**: Expand perverse incentive section or add to "Doesn't Know" that persecution funds the state

---

### MEDIUM: Helena/Aldric Knowledge Contradiction

**Issue**: Conflicting accounts of what Aldric XII knows about Helena's intelligence work

**Files**:
- warlord-king-aldric-xii.md:93 (doesn't know)
- princess-helena-valorian.md:94 (he knows some)

**Severity**: MEDIUM

**Fix**: Standardize—he suspects some contact but doesn't understand extent

---

### MEDIUM: Aurelius/Elena Awareness

**Issue**: Elena's file says Aurelius hasn't noticed her wavering, but Aurelius's file notes she's "showing weakness"

**Files**:
- sister-elena.md:95
- grand-master-aurelius.md:74

**Severity**: MEDIUM

**Fix**: Clarify he notices but hasn't decided whether to mentor or eliminate her

---

### MEDIUM: Helena Linguistic Code-Switching

**Issue**: After 10 years in North, should show more Northern patterns bleeding into Valdrian speech

**Severity**: MEDIUM

**Fix**: Expand sample lines to show cultural contamination

---

### MEDIUM: Solarius Economic Pessimism

**Issue**: Believes "can maintain balance indefinitely" but data shows 225k/year growing losses

**Severity**: MEDIUM

**Fix**: Add to "Doesn't Know" that persecution cost is unsustainable, or modify belief

---

## Summary

**Well-Integrated**: 5/10 NPCs fully consistent
**Critical Issues**: 1 (Brennan vs Aurelius leadership)
**High Issues**: 3 (Aldric economics, logistics, Aurelius crisis)
**Medium Issues**: 4 (knowledge contradictions, speech patterns)

**Overall**: NPCs integrate well with faction framework. Critical ordering issue needs immediate clarification.
