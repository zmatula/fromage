# Phase 5: Timing Polish

## Overview
Adjust timing details and communication specifics for consistency.

---

## Task 5.1: Border Clash Timing

**Source**: audit-pass3-03-protagonist-constraints.md
**File**: `09-plot-architecture/intersection-points.md`

**Issue**: Event 3 (Border Clash) may fall on Week 3 when Seven is at peak hunger (50% strength)

**Implementation**:
Add timing note to Event 3:

```markdown
## Event 3: Border Clash

### Timing Constraint
**Must occur Week 2 (Days 10-14) or Week 5+ (Days 35+)**

Seven's hunger cycle:
- Days 1-7: Full capacity
- Days 8-14: 25% reduction (acceptable for combat)
- Days 15-21: 50% reduction (significant disadvantage)
- Days 22-28: Near incapacitation

**Recommended**: Week 2 (Days 12-14)
- Seven is still strong enough for combat
- Pursuit pressure is building (regional forces mobilizing)
- Creates urgency to find allies before weakness sets in

**Alternative**: Week 5+ (Days 35+)
- Seven has found allies and fed
- Returns to full strength for major confrontation
- Makes this a climactic battle rather than desperate survival

### Feeding Requirement
If Border Clash is Week 3-4, Seven MUST feed immediately before:
- Hunt successfully (animals or enemies)
- Ally provides blood
- Takes from prisoner/enemy during chaos

Document whichever timing is chosen to ensure constraint is satisfied.
```

---

## Task 5.2: Kira's Communication Method

**Source**: audit-pass3-04-information-coherence.md
**Files**:
- `06-characters/supporting/kira-frost.md`
- `09-plot-architecture/awakening-response-timeline.md`

**Issue**: Veil Keepers have only 1 crystal but Kira reports "within hours"

**Implementation**:
Add communication section to kira-frost.md:

```markdown
## Communication Protocols

### To Northern Military
- Standard military courier dispatch
- Dead drops at predetermined locations
- Signal patterns for emergency extraction
- **Speed**: 1-3 days to Commander Vara

### To Veil Keepers
- Emergency signal: Light pattern at night (visible to watching agents)
- Regular reports: Dead drop system in Northern cities
- Priority messages: Runner to nearest Veil Keeper cell
- **Speed**: 2-5 days to Veil Keeper command

### The Vel'Thoras Report
Kira's assassination attempt and escape created chaos. Her report traveled:
1. Hour 0-6: Escaped ruins, signaled nearest Veil Keeper watcher
2. Day 1-2: Watcher carried message to Northern cell
3. Day 2-3: Cell relayed to Veil Keeper headquarters (they have the crystal)
4. Day 3-4: Headquarters alerted allies (Order of Dawn contacts)

**"Within hours" refers to**: Signal reaching first watcher, not full chain

### Why She Doesn't Have a Crystal
- Crystals are too valuable (only 1 paired set)
- Field operatives use traditional methods
- If captured with crystal, Veil Keepers lose capability
- Her cover would be instantly blown
```

Update awakening-response-timeline.md to clarify:

```markdown
### Week 0 Actions
- **Hour 0-6**: Kira signals nearest Veil Keeper watcher
- **Day 1-3**: Message reaches Veil Keeper headquarters
- **Day 3-4**: Veil Keepers alert Order of Dawn contacts
```

---

## Task 5.3: Signal Tower Coverage

**Source**: audit-pass3-04-information-coherence.md
**File**: `09-plot-architecture/communication-infrastructure.md`

**Issue**: Northern signal towers provide "instant" communication but not used in timeline

**Implementation**:
Add clarification to signal tower section:

```markdown
### Northern Signal Tower Network

**Coverage**:
- Major border fortifications (Northern/Valdrian line)
- Capital approach routes
- Coastal warning stations
- **NOT covered**: Interior wilderness, remote ruins, mountain passes

**Limitations**:
- Line-of-sight only (mountains block)
- Weather dependent (fog, snow, rain obscure)
- Simple signals only (fire = danger, smoke patterns = codes)
- Cannot convey detailed information

**Vel'Thoras Gap**:
Vel'Thoras is in Northern Highland wilderness, NOT on signal tower network:
- Nearest tower: 80 miles south
- Terrain: Forested mountains block line-of-sight
- No military installation to receive signals

This is why Kira used runner/watcher system, not signals.

**What Signals ARE Used For**:
- Border alert (Valdrian forces approaching)
- Coastal raid warning
- Capital emergency
- NOT for field intelligence reports
```

---

## Task 5.4: Dwarven Information Sources

**Source**: audit-pass3-04-information-coherence.md
**File**: `09-plot-architecture/awakening-response-timeline.md`

**Issue**: Dwarves learn Week 4-5 despite being merchant confederation

**Implementation**:
Add explanation to timeline:

```markdown
### Dwarven Information Lag (Week 4-5)

**Why So Slow?**

Despite being merchants, Ironpeak receives information late because:

1. **Geographic Isolation**: Holds are in mountains; trade routes go TO dwarves, not through
2. **Neutrality Policy**: Dwarves avoid human political intelligence; merchants report commerce, not conflict
3. **Vel'Thoras Location**: Northern Highlands have minimal dwarven trade; no direct merchant contact

**How They Learn**:
- Week 3-4: Merchant in Port Sovereign hears rumors
- Week 4: Merchant convoy travels to Ironhold (20-30 mi/day)
- Week 4-5: Report reaches Thane Council through commercial channels

**Information Quality**: Low
- Third-hand rumors from Maritime merchants
- No direct witnesses or intelligence assets
- Mostly speculation about "something in the North"

**Why This Matters**:
Dwarven neutrality depends on information. If they can't learn quickly, they can't act quickly. By Week 5, other factions have already made decisions that affect dwarves—and dwarves are reacting to consequences rather than events.

This is why Borin's patience frustrates younger dwarves. Waiting means arriving late.
```

---

## Verification Checklist

After Phase 5:
- [ ] Border Clash timing avoids Week 3 hunger window
- [ ] Kira's communication chain documented with realistic timing
- [ ] Signal tower coverage map explains Vel'Thoras gap
- [ ] Dwarven information lag explained by geography and policy

---

## Files to Modify

1. `09-plot-architecture/intersection-points.md` - Border Clash timing
2. `06-characters/supporting/kira-frost.md` - Communication protocols
3. `09-plot-architecture/awakening-response-timeline.md` - Kira timing, dwarven lag
4. `09-plot-architecture/communication-infrastructure.md` - Signal tower coverage
