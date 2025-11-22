# Consistency Checks

Validation protocols for ensuring internal consistency across all worldbuilding elements.

---

## Purpose

This document establishes protocols for checking that all elements of the Vampire Collapse Epic are internally consistent. Use these checks before writing and periodically during development.

---

## Timeline Consistency

### Protocol

1. **Chronological Order**: All events must follow logical sequence
2. **Cause-Effect**: Every event must have established cause
3. **Duration**: Time between events must be plausible
4. **Character Ages**: Characters must be appropriate age for events

### Key Checks

| Check | Description | Reference |
|-------|-------------|-----------|
| Collapse timing | Year 0 is pivot; negatives before, positives after | master-timeline.md |
| Era boundaries | Events fall in correct eras | era-breakdowns/ |
| Character births | Birth years match current ages | character files |
| Travel times | Movement between locations plausible | world-map-description.md |

### Known Timeline Points

- Year -1200: Pre-vampire era begins
- Year -1000: Vampire rise era begins
- Year -7: Protagonist created
- Year 0: Collapse
- Year 1200: Story begins

---

## Character Consistency

### Protocol

1. **Knowledge Tracking**: Characters know only what they could know
2. **Personality**: Actions match established traits
3. **Motivation**: Goals drive behavior consistently
4. **Relationships**: Connections remain consistent

### Key Checks

| Check | Description | Reference |
|-------|-------------|-----------|
| Knowledge limits | No character knows more than possible | discoverable-secrets.md |
| Fatal flaws | Flaws manifest appropriately | character-arcs.md |
| Faction loyalty | Allegiances consistent | character files |
| Age/experience | Skills match background | character files |

### Character Knowledge Matrix

Track what each character knows about:
- Protagonist's nature
- Collapse cause
- Artifact locations
- Other characters' secrets
- Historical truths

---

## Geographical Consistency

### Protocol

1. **Distance**: Travel times match map
2. **Climate**: Weather matches region
3. **Resources**: Economy matches geography
4. **Borders**: Political boundaries consistent

### Key Checks

| Check | Description | Reference |
|-------|-------------|-----------|
| Travel times | Movement matches distances | world-map-description.md |
| Ruin locations | Sites match historical events | vampire-ruins/ |
| Resource distribution | Trade routes make sense | regions/ |
| Border conflicts | Disputes match terrain | faction-relationship-map.md |

### Distance Reference

- Valdris Prime to Ironhold: ~800 miles (3-4 weeks travel)
- The Scar to Silverwood: ~600 miles
- Vel'Thoras to nearest city: ~200 miles

---

## Cultural Consistency

### Protocol

1. **Memory**: Each culture remembers history according to their narrative
2. **Values**: Actions reflect established cultural values
3. **Conflicts**: Disputes arise from established differences
4. **Language**: Terminology matches culture

### Key Checks

| Check | Description | Reference |
|-------|-------------|-----------|
| Historical memory | Each race tells their version | cultural-memory-matrix.md |
| Value conflicts | Disputes logical | cultural-conflicts.md |
| Religious consistency | Church behavior matches doctrine | humans.md |
| Racial traits | Abilities match established biology | race files |

---

## Magic System Consistency

### Protocol

1. **Costs**: All magic has appropriate cost
2. **Limitations**: No magic exceeds established limits
3. **Traditions**: Each tradition works as described
4. **Artifacts**: Effects match mechanics

### Key Checks

| Check | Description | Reference |
|-------|-------------|-----------|
| Cost payment | Every spell has cost | magic-system.md |
| Absolute limits | Nothing violates impossibilities | magic-system.md |
| Tradition rules | Each tradition follows its approach | magic-system.md |
| Artifact mechanics | Each artifact works as documented | relic-registry.md |

### Magic Limits

Cannot do:
- Create true life
- Resurrect the dead
- Time travel
- Unlimited power
- Complete mind control
- Permanent transformation (without permanent cost)

---

## Political Consistency

### Protocol

1. **Power Balance**: Factions maintain established strengths/weaknesses
2. **Alliances**: Relationships follow logical interests
3. **Conflicts**: Disputes have established causes
4. **Leaders**: Rulers act according to characterization

### Key Checks

| Check | Description | Reference |
|-------|-------------|-----------|
| Faction strength | Military/economic power matches | empire files |
| Alliance logic | Partnerships make sense | faction-relationship-map.md |
| Secret society reach | Infiltration matches resources | secret society files |
| Leader motivations | Rulers act in character | NPC descriptions |

---

## Plot Consistency

### Protocol

1. **Arcs**: Story threads follow established structure
2. **Consequences**: Actions have documented effects
3. **Intersections**: Characters meet as planned
4. **Revelations**: Secrets revealed in order

### Key Checks

| Check | Description | Reference |
|-------|-------------|-----------|
| Arc progression | Stories follow beats | story-arcs.md |
| Consequence chains | Effects cascade properly | consequence-chains.md |
| Meeting points | Characters converge at established events | intersection-points.md |
| Revelation timing | Secrets revealed in sequence | discoverable-secrets.md |

---

## Validation Checklist

### Before Writing Scene

- [ ] What does POV character know at this point?
- [ ] Where is this geographically? Travel time from last location?
- [ ] What artifacts are present? How do they work?
- [ ] What are character motivations in this scene?
- [ ] What will be revealed? Is it time?
- [ ] What consequences will follow?

### Periodic Full Check

- [ ] Timeline validator pass
- [ ] Character knowledge audit
- [ ] Geography verification
- [ ] Magic system compliance
- [ ] Political relationship check
- [ ] Plot arc alignment

---

## Common Inconsistencies to Watch

### Timeline Errors
- Characters knowing about events before they happen
- Travel too fast for distance
- Age doesn't match birth year
- Event in wrong era

### Character Errors
- Knowing information they shouldn't have
- Acting against established motivation
- Skills they weren't trained in
- Wrong faction loyalty

### World Errors
- Magic without cost
- Artifact doing something not in mechanics
- Geography contradicting map
- Culture acting against values

### Plot Errors
- Revelation before setup
- Consequence without cause
- Characters meeting when they shouldn't
- Arc beat out of order

---

## Cross-References

- [Timeline Validator](timeline-validator.md) - Chronological checks
- [Character Tracker](character-tracker.md) - Knowledge tracking
- [Integration Tests](integration-tests.md) - Cross-system validation
- [Master Timeline](../02-timeline/master-timeline.md) - Event sequence

---

*Consistency is the foundation of believability. Every contradiction weakens the world. These checks exist to maintain the illusion that this is a real place with real history and real people.*
