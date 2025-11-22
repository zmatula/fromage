# Timeline Validator

Chronological checks to ensure all events are properly sequenced and causally connected.

---

## Timeline Structure

### Era Boundaries

| Era | Years | Key Events |
|-----|-------|------------|
| Pre-Vampire | -1200 to -1000 | Other races' kingdoms, vampire near-extinction |
| Rise | -1000 to -500 | Conquest, covenant formation, Bloodweb creation |
| Golden Age | -500 to -100 | Peak civilization, slow rot begins |
| Final Century | -100 to 0 | Decline, rebellions, Sanguine Vessels, collapse |
| Immediate Aftermath | 0 to 50 | Liberation chaos, kingdom formation |
| Dark Ages | 50 to 300 | Knowledge loss, recovery |
| Warring Kingdoms | 300 to 700 | Wars, artifact discoveries |
| Consolidation | 700 to 1100 | Empire formation, secret societies |
| Recent Past | 1100 to 1200 | Current tensions, protagonist awakening |

---

## Critical Event Sequence

### Pre-Collapse (must be in order)

1. Year -1160: Vampire near-extinction (only ~30,000)
2. Year -1000: Vykros unifies clans
3. Year -900: Conquest complete
4. Year -810: Covenant of Eternal Mind founded
5. Year -808: Covenant of Crimson Throne founded
6. Year -805: Covenant of Silver Twilight founded
7. Year -800: Bloodweb created
8. Year -600: Bloodweb ambient energy enhancement
9. Year -400: Blood potency enhancement
10. Year -200: Dependency nearly universal
11. Year -50: Human rebellion
12. Year -30: Elven strike
13. Year -20: Dwarven sabotage
14. Year -12: Sanguine Vessels Initiative begins
15. Year -7: Vessel Seven (protagonist) created
16. Year 0: Ascension Experiment, collapse

### Post-Collapse (must be in order)

1. Year 0: Collapse begins
2. Year 1-50: Liberation, chaos, early kingdoms
3. Year 160: Vampires become pure legend
4. Year 312: Crown of Seeing discovered
5. Year 350: Church schisms
6. Year 358: Forge of Souls discovered (secret)
7. Year 478: Healer's Stone discovered
8. Year 534: Gate Fragment discovered
9. Year 612: Blood Archives discovered
10. Year 667: Mind Codex discovered
11. Year 745: Vel'Krath Cache discovered
12. Year 812: First confirmed vampire survivor (destroyed)
13. Year 900: Four-empire system stable
14. Year 950-1000: Secret society Shadow Wars
15. Year 1050: Twilight War (elven isolation)
16. Year 1112: Vel'Thoras inner sanctum approached
17. Year 1118: Living Artifact discovered
18. Year 1121: Veil Keeper scholar purge
19. Year 1172: Vel'Thoras sanctum located
20. Year 1175: Twilight sanctuary entrance found
21. Year 1178: Dimensional readings begin increasing
22. Year 1180: Awakening protocols discovered
23. Year 1198: Maritime coup
24. Year 1200: Story begins, protagonist awakens

---

## Character Age Validation

### Current Ages (Year 1200)

| Character | Birth Year | Age | Valid? |
|-----------|------------|-----|--------|
| Vessel Seven | Year -7 (created) | N/A (1207 in stasis) | ✓ |
| Emperor Cassius VIII | ~1140 | ~60 | ✓ |
| King Aldric XII | ~1166 | ~34 | ✓ |
| Elara Goldstone | ~1172 | ~28 | ✓ |
| Marcus Ashford | ~1165 | ~35 | ✓ |
| Vera Nighthollow | ~1168 | ~32 | ✓ |
| Kira Frost | 1169 | 31 | ✓ |
| Gritha Bloodsinger | 1111 | 89 | ✓ (old for goblin) |
| Thandril Shadowleaf | ~1050 | ~150 | ✓ (young for elf) |
| High Thane Borin | ~888 | ~312 | ✓ (old dwarf) |

### Age Logic

- Humans: 70-80 years typical lifespan
- Elves: 500+ years
- Dwarves: 300-400 years
- Goblins: 60-70 years (Gritha is very old)
- Vampires: Indefinite (but can be killed)

---

## Cause-Effect Chains

### Must Follow

**Bloodweb → Dependency → Vulnerability → Collapse**
- Year -800: Bloodweb created
- Year -200: Dependency universal
- Year 0: Inversion kills all connected

**Sanguine Vessels → Protagonist → Story**
- Year -12: Initiative begins (knowing risk)
- Year -7: Protagonist created
- Year 0: He survives (not connected)
- Year 1200: He awakens

**Collapse → Liberation → Empires → Present**
- Year 0: Collapse
- Year 0-50: Chaos and formation
- Year 900: Empires stable
- Year 1200: Current situation

**Secret Societies → Artifact Control → Conflict**
- Various founding dates
- Ongoing competition
- Current tensions at peak

---

## Travel Time Validation

### Reference Distances

All travel times assume standard conditions (roads, weather, no pursuit).

| Route | Distance | Time |
|-------|----------|------|
| Valdris Prime ↔ Ironhold | ~800 miles | 3-4 weeks |
| Valdris Prime ↔ Goldport | ~500 miles | 2-3 weeks |
| Ironhold ↔ The Scar | ~400 miles | 2 weeks |
| Vel'Thoras ↔ Valdris Prime | ~300 miles | 1.5-2 weeks |
| Silverwood ↔ The Scar | ~600 miles | 3 weeks |

### Modifiers

- Forced march: -30% time
- Bad weather: +50% time
- Difficult terrain: +50% time
- Sea travel: 2x speed
- Pursuit: varies

---

## Validation Queries

### Run These Checks

**Timeline Sequence**
1. Are all events in master-timeline.md in chronological order?
2. Do era breakdowns match master timeline?
3. Do character birth dates allow their documented actions?

**Cause-Effect**
1. Does every major event have established cause?
2. Do consequences follow from causes logically?
3. Are there unexplained gaps?

**Travel Logic**
1. Can characters get from A to B in stated time?
2. Do chase sequences allow for geography?
3. Do simultaneous events allow for communication delay?

**Historical Memory**
1. Do cultures remember events they could have witnessed?
2. Are "lost" facts actually lost at the right time?
3. Do discoveries happen when stated?

---

## Known Timeline Issues

### Resolved

All major timeline issues resolved during worldbuilding phases.

### Watch For

- Character ages not matching stated experience
- Events happening before their causes
- Travel too fast for distances
- Information known before it could spread
- Artifacts used before discovered

---

## Validation Report Template

When running validation, document:

```markdown
## Timeline Validation Report

**Date**: [date]
**Scope**: [what was checked]

### Issues Found

1. **Issue**: [description]
   **Location**: [file and line]
   **Severity**: [critical/moderate/minor]
   **Fix**: [proposed solution]

### Verification

- [ ] All events in chronological order
- [ ] All cause-effect chains valid
- [ ] All character ages correct
- [ ] All travel times plausible
- [ ] All discoveries in order
```

---

## Cross-References

- [Master Timeline](../02-timeline/master-timeline.md) - Event sequence
- [Era Breakdowns](../02-timeline/era-breakdowns/) - Detailed periods
- [World Map](../05-geography/world-map-description.md) - Distances
- [Consistency Checks](consistency-checks.md) - General validation

---

*Time is the skeleton of history. If the timeline is wrong, everything built on it is wrong. Validate early, validate often.*
