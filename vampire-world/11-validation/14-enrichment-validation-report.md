# Validation Report: Pre-Awakening Enrichment

Cross-checking 9 new documents against existing content.

---

## Critical Inconsistencies

### Issue 1: Vessel Names and Details (CRITICAL)

**Files**: `sanguine-vessels-lab.md` vs `sanguine-vessels-registry.md`

**Problem**: New lab document uses informal nicknames that conflict with established registry names and survival times.

| Vessel | Lab Doc Name | Registry Name | Lab Survival | Registry Survival |
|--------|-------------|---------------|--------------|-------------------|
| 1 | "First" | Arren Thorne | 3 hours | 12 days |
| 2 | "Persister" | (unknown elf) | 3 months | 6 days |
| 3 | "Dreamer" | Mira Coldwell | 2 years | 21 days |
| 4 | "Stillborn" | Theron Ashward | 0 (never woke) | 3 months |
| 5 | "Feral" | Sera | 6 months | 6 weeks |
| 6 | "Whisper" | Corvin Marsh | 8 months | 6 months |
| 8-10 | "Bright/Edge/Quiet" | Brennan/Lyssa/Marcus | (survived to collapse) | (matches) |

**Recommendation**: Revise `sanguine-vessels-lab.md` to use registry names and correct survival times. The nicknames can be used as informal names alongside official designations.

---

### Issue 2: Dorian's Age (MODERATE)

**Files**: `sanguine-vessels-lab.md` vs `vampire-figures.md`

**Problem**:
- Lab doc: "Dorian was 900 years old"
- Vampire figures: "Dorian val'Kess... Age at Collapse: 203 years"

**Recommendation**: Revise lab doc to 203 years, or explain Dorian Kesh (lab) vs Dorian val'Kess (figures) are different people.

---

### Issue 3: Velanna's Age (MODERATE)

**Files**: `vampire-factions.md` vs `vampire-figures.md`

**Problem**:
- Factions: "Velanna of Mind (Year -850 to Year 0)" = 850 years old
- Figures: "Age at Collapse: 324 years"

**Recommendation**: Reconcile to 850 years (matches the "one of the oldest" description and the Year -850 founding date).

---

### Issue 4: Kael vs Krath Names (MINOR)

**Files**: `council-final-sessions.md`, `collapse-days-2-7.md`, `sanguine-vessels-lab.md`

**Problem**: Similar names may cause confusion:
- General Kael (Throne) - Council attendee, military strategist
- Security Chief Krath - Vel'Thoras security, trainer

**Status**: These are correctly different people, but the similar names may confuse readers.

**Recommendation**: Consider if name differentiation is sufficient or if one should be renamed.

---

## Minor Inconsistencies

### Issue 5: Councillor Lyris Timeline

**Files**: `council-final-sessions.md`, `twilight-sanctuary-selection.md`

**Check**: Lyris warns Council in Year -95, recalled to Twilight, then appears in collapse-days-2-7.md during sanctuary selection.

**Status**: Timeline is consistent—she returned to Twilight after Year -95 and was there during collapse.

---

### Issue 6: Researcher Team Names

**Files**: `sanguine-vessels-lab.md` vs `vampire-figures.md`

**Lab doc researchers**:
- Dorian Kesh (senior researcher, 900yo)
- Krath Velorn (security chief)
- Mira Vex (medical specialist)
- Sevik Thorn (junior researcher)
- Lira Ashward (archive keeper)

**Vampire figures researchers**:
- Velanna val'Thoras (lead)
- Dorian val'Kess (assistant, 203yo)
- Security Chief Krath val'Krath (512yo)

**Problem**: Different last names and ages for same roles.

**Recommendation**: Standardize—either update lab doc to use val'Kess/val'Krath names, or treat as different naming conventions (nickname vs formal).

---

## Timeline Verification

### Council Sessions Timeline ✓

| Year | Event | Consistent? |
|------|-------|-------------|
| -95 | Bloodweb dependency proposal | ✓ Matches pre-collapse decline |
| -85 | Sanctuary disclosure debate | ✓ Matches Twilight preparation |
| -82 | Border incident | ✓ Matches master-timeline |
| -80 | Twilight withdrawal | ✓ Matches master-timeline |
| -70 | Assassination aftermath | ✓ Matches master-timeline |
| -68 | Council suspension | ✓ Matches master-timeline |

### Collapse Days Timeline ✓

| Day | Events | Consistent? |
|-----|--------|-------------|
| 2 | Cassius mobilizes, Selene seals | ✓ Matches factions |
| 3-4 | Decisions and breakdowns | ✓ Logical sequence |
| 5 | Fourth Sanctuary seals | ✓ Matches sanctuary doc |
| 6-7 | Scattering and silence | ✓ Matches collapse-event.md |

### Unification Wars Timeline ✓

All dates consistent with master-timeline.md era-pre-vampire entries.

---

## Cross-Reference Verification

### Artifact Mentions ✓

- Crown of Seeing journey aligns with artifact-histories.md
- Blood Anvil and Forge of Souls locations match
- Speaking Stones distribution consistent

### Historical Figures ✓

- House lineages connect properly across documents
- Ideological successions track correctly
- No orphaned references

---

## Recommended Fixes

### High Priority

1. **Update sanguine-vessels-lab.md**:
   - Use registry names (Arren, Theron, Sera, Corvin, Brennan, Lyssa, Marcus)
   - Correct survival times to match registry
   - Can keep nicknames as additional informal names

2. **Reconcile Dorian's age**:
   - Change lab doc to 203 years
   - Or clarify these are different Dorians

3. **Reconcile Velanna's age**:
   - Should be 850 years (born Year -850)
   - Update vampire-figures.md age field

### Medium Priority

4. **Standardize researcher names**:
   - Use consistent naming convention (val'X formal names)

5. **Add clarifying notes**:
   - Distinguish Kael (General) from Krath (Security Chief)

---

## Validation Summary

| Category | Issues Found | Critical | Moderate | Minor |
|----------|-------------|----------|----------|-------|
| Names/Ages | 4 | 1 | 2 | 1 |
| Timeline | 0 | 0 | 0 | 0 |
| Cross-refs | 0 | 0 | 0 | 0 |
| **Total** | **4** | **1** | **2** | **1** |

**Overall Assessment**: Core content is consistent. Primary issue is Vessel naming/timing in lab document that needs reconciliation with existing registry.

---

## Next Steps

1. Fix critical Vessel inconsistency in sanguine-vessels-lab.md
2. Update age discrepancies
3. Proceed with cross-reference updates

---

*Validation complete. Issues identified are reconcilable and don't affect core narrative consistency.*
