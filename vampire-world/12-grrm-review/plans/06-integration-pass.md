# Phase 6: Integration & Cross-References

## Overview
Final pass to ensure all changes ripple appropriately and cross-references work.

---

## Task 6.1: Consistency Verification

### Numbers Must Match

Check these values are consistent across all files:

| Value | Correct Amount | Files to Check |
|-------|----------------|----------------|
| Valdrian population | 4M total, 3.5M heartlands | valdrian-empire.md, valdrian-heartlands.md |
| Northern population | 3M | northern-dominion.md, northern-highlands.md |
| Valdrian debt to dwarves | 500,000 crowns | economic-framework.md, valdrian-empire.md |
| Northern food imports | 40% / 200,000 crowns | northern-dominion.md, economic-framework.md |
| Veil Keeper budget | ~180,000 crowns | veil-keepers.md, economic-framework.md |

### Travel Times Must Triangulate

Verify all route times work geometrically:
- Use world-map-description.md as canonical source
- Check any character movements in plot files
- Ensure no one teleports

### Character Names Must Be Consistent

After Helena Ashford split:
- Helena Ashford: Veil Keeper archivist, Ashford descendant
- Maren Thorne: Senior Veil Keeper investigating true origins
- Update all references

---

## Task 6.2: Cross-Reference Updates

### Files That Need New Cross-References

**After adding Scar effects to regional files**:
- valdrian-heartlands.md → the-scar.md
- northern-highlands.md → the-scar.md
- economic-framework.md → the-scar.md

**After creating communication systems**:
- All faction files should reference it
- character files should note communication access
- plot files should account for information lag

**After creating contamination matrix**:
- Each culture file should link to it
- cultural-texture.md should reference it
- Each empire file should link to it

**After adding character cultural DNA**:
- Each character should cross-reference their faction file
- cultural-texture.md should reference character examples

---

## Task 6.3: Ripple Effect Verification

### Economic Changes Should Affect

When we add debt matrix:
- Political tension files should reference debt pressure
- Character motivations should include economic factors
- Faction relationship map should note economic leverage

When we add food dependency:
- Northern military strategy must account for it
- Valdrian political leverage must reference it
- War planning documents must address it

### Cultural Changes Should Affect

When we add contamination matrix:
- Characters should show cultural markers from their faction
- Conflicts should reference cultural misunderstandings
- History files should show contamination developing

When we add religious syncretism:
- Church internal conflicts should reference it
- Character religious expressions should match
- Church-faction relationships should acknowledge it

### Information Changes Should Affect

When we add communication systems:
- Plot timelines must be realistic
- Character "knowledge" must match access
- Crisis escalation must account for lag

When we add propaganda:
- Character beliefs should show propaganda effects
- Faction conflicts should include information warfare
- Regional differences should reflect propaganda reach

---

## Task 6.4: Dangling Thread Resolution

### Threads That Need Tying

**Starweave Silk**:
- Mentioned as critical but never used
- Add: What rituals require it? Who's desperate for it?
- Connect to plot tension

**Elven-Dwarven Communication**:
- Hinted but never developed
- Add: What do they discuss? Shared concerns?
- Connect to why dwarves stay neutral

**Living Artifact Seizure**:
- Timeline unclear
- Add: Full timeline from Year 1118 to present
- Connect to Northern-Veil Keeper conflict

**Princess Helena's Network**:
- Setup but not used
- Add: Her ladies-in-waiting, her goals, her communications
- Connect to succession crisis

---

## Task 6.5: Missing Link Creation

### Links That Don't Exist But Should

**Demographic consequences → Character backstories**:
- Which characters come from depopulated regions?
- Whose families rose during labor shortages?
- Who lost ancestors in Collapse/aftermath?

**Trade routes → Political conflicts**:
- Which routes are contested?
- Who controls which chokepoints?
- How does Scar disruption affect which factions?

**Secret society funding → Faction relationships**:
- Who funds the Inheritors? (Name specific patrons)
- Why do states secretly fund Veil Keepers?
- How does Order of Dawn funding affect Sanctified politics?

---

## Task 6.6: Final Consistency Check

### Read-Through Checklist

After all phases complete, do a full read of:

1. **Timeline files**: Does causation flow properly?
2. **Geographic files**: Do locations match descriptions?
3. **Faction files**: Do resources match capabilities?
4. **Character files**: Do backgrounds match cultural DNA?
5. **Secret files**: Is information distribution realistic?
6. **Plot files**: Do timelines work with communication lag?

### The Spider Web Test

For each major element, verify you can trace connections to at least 5 other elements:

Example - Northern Food Dependency:
1. → Geographic (short growing season)
2. → Economic (import costs)
3. → Political (constrains war planning)
4. → Faction (Valdrian leverage)
5. → Character (King Aldric's strategy)
6. → Plot (why they haven't invaded yet)

If any element has fewer than 3 connections, it needs integration work.

---

## Task 6.7: Documentation Updates

### Update CLAUDE.md

After implementation, update CLAUDE.md to reflect:
- New file structure
- New cross-reference patterns
- Consistency standards established
- Integration requirements for future additions

### Create Implementation Log

Document what was changed:
- Files modified (with dates)
- New files created
- Major decisions made
- Remaining issues for future work

---

## Final Verification Checklist

- [ ] All numbers consistent across files
- [ ] All travel times geometrically possible
- [ ] Character names consistent after splits
- [ ] Cross-references updated for all new files
- [ ] Economic changes ripple to political files
- [ ] Cultural changes ripple to character files
- [ ] Information changes ripple to plot files
- [ ] Dangling threads resolved or documented
- [ ] Missing links created
- [ ] Full read-through completed
- [ ] Spider web test passed for major elements
- [ ] CLAUDE.md updated
- [ ] Implementation log created

---

## Success Criteria

The integration is complete when:

1. **Any fact appears the same in all files that mention it**
2. **Any change to one file would require changes to connected files**
3. **Any character's knowledge matches their information access**
4. **Any plot development respects travel/communication times**
5. **Any conflict has economic, political, AND cultural dimensions**

*Touch one strand and the entire web vibrates.*
