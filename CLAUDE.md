# Claude Code Worldbuilding Project Prompt

## Project: The Vampire Collapse Epic - Complete Historical Architecture

You are tasked with building the complete historical, cultural, and narrative architecture for a GRRM-style epic fantasy novel using the following core premise:

**Core Premise:**
- Ancient advanced vampire civilization collapsed 1,200 years ago
- Present day: Medieval tech level (GOT equivalent)
- Multiple races (humans, elves, dwarves, goblins) with sub-races, empires, intrigue
- Magic exists but is limited, costly, practical
- Protagonist: Experimental vampire relic with enhanced (but still limited) magic abilities
- Lost vampire cities underground, mostly unknown
- Current world largely unaware of vampire history

---

## CRITICAL: Iterative Process & Context Management

This is a **multi-session project**. You MUST:

1. **Work in phases** - Complete one phase before moving to next
2. **Create reference files** at each phase that can be reloaded in future sessions
3. **Maintain a master index** showing what's been completed
4. **Validate consistency** before moving forward
5. **Build modularly** so any section can be updated without breaking others

---

## File Structure & Documentation System

Create this directory structure in `/home/claude/vampire-world/`:

```
vampire-world/
├── 00-project-index/
│   ├── master-index.md (tracks all completed work)
│   ├── session-log.md (logs what was done each session)
│   └── next-steps.md (what to work on next)
│
├── 01-core-framework/
│   ├── premise-constraints.md (the non-negotiables)
│   ├── core-mysteries.md (the driving questions)
│   └── thematic-pillars.md (the themes)
│
├── 02-timeline/
│   ├── master-timeline.md (chronological event list)
│   ├── era-breakdowns/ (detailed files for each era)
│   ├── collapse-event.md (detailed collapse analysis)
│   └── timeline-validation.md (consistency checks)
│
├── 03-cultures/
│   ├── cultural-memory-matrix.md (how each race remembers history)
│   ├── races/ (folder for each race)
│   │   ├── humans.md
│   │   ├── elves.md
│   │   ├── dwarves.md
│   │   ├── goblins.md
│   │   └── vampires.md
│   └── cultural-conflicts.md (how histories clash)
│
├── 04-factions/
│   ├── empires/ (major political entities)
│   ├── secret-societies/ (hidden knowledge keepers)
│   ├── magic-schools/ (magical traditions)
│   └── faction-relationship-map.md
│
├── 05-geography/
│   ├── world-map-description.md
│   ├── regions/ (detailed regional info)
│   ├── vampire-ruins/ (underground cities and sites)
│   └── relic-distribution.md
│
├── 06-characters/
│   ├── protagonist.md (detailed)
│   ├── major-characters/ (POV characters)
│   ├── supporting-cast/ (secondary characters)
│   ├── character-relationship-map.md
│   └── character-validation.md
│
├── 07-artifacts-magic/
│   ├── relic-registry.md (all vampire artifacts)
│   ├── magic-system.md (how magic works)
│   ├── vampire-technology.md (what they could do)
│   └── artifact-plot-connections.md
│
├── 08-secrets/
│   ├── shadow-truths.md (what really happened vs beliefs)
│   ├── protagonist-true-history.md (his real backstory)
│   ├── discoverable-secrets.md (plot revelations)
│   └── permanent-mysteries.md (what stays unknown)
│
├── 09-plot-architecture/
│   ├── story-arcs.md (major plot threads)
│   ├── character-arcs.md (character journeys)
│   ├── intersection-points.md (where storylines meet)
│   └── consequence-chains.md (cause and effect)
│
├── 10-style-guide/
│   ├── grrm-writing-principles.md
│   ├── narrative-voice.md
│   ├── scene-construction.md
│   └── dialogue-guidelines.md
│
└── 11-validation/
    ├── consistency-checks.md
    ├── timeline-validator.md
    ├── character-tracker.md
    └── integration-tests.md
```

---

## Phase-by-Phase Process

### **Phase 1: Foundation Setup**

**Objective**: Establish the core framework and constraints

**Tasks**:
1. Create directory structure
2. Document premise constraints in `01-core-framework/premise-constraints.md`
3. Develop core mysteries in `01-core-framework/core-mysteries.md`:
   - Why did vampires collapse? (multiple theories)
   - How advanced were they really?
   - What experiments created the protagonist?
   - Where did other races come from?
   - Were vampires evil or misunderstood?
4. Establish thematic pillars in `01-core-framework/thematic-pillars.md`:
   - Price of power
   - Unreliability of history
   - Cycles of rise and fall
   - Burden of legacy
   - Knowledge vs wisdom
5. Update `00-project-index/master-index.md` with completion status

**Output**: Foundation documents that anchor all future work

**Validation**: Can you explain the core mysteries and how they drive the story?

---

### **Phase 2: The Collapse Event (Year 0)**

**Objective**: Define the pivot point of all history in exhaustive detail

**Tasks**:
1. Create `02-timeline/collapse-event.md` with:
   - **What specifically happened**: Multi-causal breakdown
   - **Timeline of collapse**: Was it sudden or gradual?
   - **Who survived and how**: Different factions, different fates
   - **What was lost immediately vs over time**: Knowledge, technology, infrastructure
   - **Regional variations**: Did different areas collapse differently?
   - **The triggering experiment**: What was the protagonist's creation project about?
   - **Evidence that remains**: What proof exists in the present day?

2. Develop **multiple contradictory historical interpretations**:
   - Official version (what most people believe)
   - Scholar interpretation (what evidence suggests)
   - Cultural variations (how each race remembers it)
   - Shadow truth (what actually happened)
   - Unknown elements (what can never be known)

3. Create **consequence cascade**:
   - Immediate aftermath (Year 0-10)
   - Power vacuum effects (Year 10-50)
   - Long-term impacts (to present day)

**Output**: `02-timeline/collapse-event.md` - the most detailed document in the project

**Validation**: Does the collapse explanation feel complex, realistic, and create multiple interpretations?

---

### **Phase 3: Pre-Collapse Vampire History**

**Objective**: Build vampire civilization history working backwards from collapse

**Tasks**:
1. Create `02-timeline/era-breakdowns/` folder with files:
   - `era-final-century.md` (Year -100 to 0)
   - `era-golden-age.md` (Year -500 to -100)
   - `era-rise.md` (Year -1000 to -500)
   - `era-pre-vampire.md` (Year -1200 to -1000)

2. For each era, document:
   - **Major events**: Wars, discoveries, catastrophes
   - **Vampire factions**: Who held power, what did they believe?
   - **Technological/magical developments**: What could they do?
   - **Relationship with other races**: Slaves? Allies? Complicated?
   - **Cultural achievements**: What did they create?
   - **Seeds of collapse**: What problems were brewing?
   - **Physical evidence**: What ruins/artifacts come from this era?

3. Create `02-timeline/vampire-factions.md`:
   - List all major vampire groups/philosophies
   - Which faction created the protagonist? Why?
   - What happened to each faction during collapse?

4. Update `02-timeline/master-timeline.md` with all events chronologically

**Output**: Detailed pre-collapse history with internal consistency

**Validation**: Run consistency check - do events logically lead to collapse?

---

### **Phase 4: Post-Collapse History to Present**

**Objective**: Build the 1,200 years from collapse to story start

**Tasks**:
1. Create era breakdown files:
   - `era-immediate-aftermath.md` (Year 0-50)
   - `era-dark-ages.md` (Year 50-300)
   - `era-warring-kingdoms.md` (Year 300-700)
   - `era-consolidation.md` (Year 700-1100)
   - `era-recent-past.md` (Year 1100-1200)

2. For each era, document:
   - **Power structures**: Who ruled what?
   - **Major wars/conflicts**: Between which races/kingdoms?
   - **Vampire relic discoveries**: What was found when? Impact?
   - **Knowledge recovered/lost**: What did they learn/forget?
   - **Cultural development**: How did races evolve?
   - **Key figures**: Heroes, villains, legends

3. Create **discovery timeline**:
   - Track every significant vampire ruin/artifact discovery
   - Who found it? What happened? Political impact?
   - Store in `05-geography/relic-distribution.md`

4. Update master timeline with all post-collapse events

**Output**: Complete 1,200-year history from collapse to present

**Validation**: Does history logically progress? Are there cause-effect chains?

---

### **Phase 5: Cultural Memory Matrix**

**Objective**: Develop how each race/culture remembers and interprets history

**Tasks**:
1. Create `03-cultures/cultural-memory-matrix.md` as a table:
   ```
   | Event | Humans | Elves | Dwarves | Goblins | Scholars | Truth | Unknown |
   ```
   For major events: Collapse, vampire wars, each race's origin, etc.

2. Create detailed race files in `03-cultures/races/`:

   **For each race (humans, elves, dwarves, goblins, vampires):**
   - **Sub-races**: Different ethnicities/cultures within race
   - **Origin story**: What they believe about their origins
   - **Vampire relationship**: How they interacted with vampire civilization
   - **Collapse narrative**: Their version of what happened
   - **Cultural values**: What they prize/despise
   - **Historical heroes/villains**: Their legends
   - **Present-day culture**: Government, religion, social structure
   - **Relationship with vampire ruins**: Fear? Treasure hunt? Sacred? Forbidden?
   - **Internal conflicts**: Factions within the race
   - **Secrets they hide**: What truths they suppress

3. Create `03-cultures/cultural-conflicts.md`:
   - Where do cultural narratives clash?
   - What historical disputes drive present conflicts?
   - Whose version is closest to truth?

**Output**: Rich, contradictory cultural perspectives

**Validation**: Do different cultures have genuinely different, self-serving interpretations?

---

### **Phase 6: Faction & Power Structure Development**

**Objective**: Build present-day political entities and secret societies

**Tasks**:
1. Create empire files in `04-factions/empires/`:
   - For each major kingdom/empire (6-10 total):
     - Name, territory, population
     - Ruling structure (monarchy, council, etc.)
     - Founding history (Year X to present)
     - Current ruler and ruling family
     - Major cities and strongholds
     - Military strength
     - Economic base
     - Cultural character
     - Relationship with other empires
     - View on vampire history/relics
     - Internal conflicts/factions
     - Role in main story

2. Create secret society files in `04-factions/secret-societies/`:
   - For each major secret organization (4-8 total):
     - Name and founding date
     - True purpose vs public face
     - What they know about vampire history
     - What they want (preserve? destroy? recover? use?)
     - Membership (who can join?)
     - Resources and reach
     - Current leader and hierarchy
     - Relationship with protagonist (do they know about him?)
     - Conflicts with other societies
     - Role in main story

3. Create magic school files in `04-factions/magic-schools/`:
   - For each tradition (4-6 schools):
     - Philosophy and approach to magic
     - What they know about vampire magic (accurate? wrong?)
     - Forbidden techniques (are these actually vampire methods?)
     - Notable practitioners
     - Political alignments
     - Role in story

4. Create `04-factions/faction-relationship-map.md`:
   - Who allies with whom?
   - Who competes/conflicts?
   - What treaties exist?
   - What secret connections exist?

**Output**: Complex web of present-day power structures

**Validation**: Do factions have conflicting goals that create organic conflict?

---

### **Phase 7: Geography & Relic Placement**

**Objective**: Map the world and strategically place vampire remnants

**Tasks**:
1. Create `05-geography/world-map-description.md`:
   - Continents and major regions
   - Climate zones
   - Major geographical features
   - Travel times between regions
   - Racial distribution (who lives where?)
   - Empire boundaries

2. Create regional files in `05-geography/regions/`:
   - For each major region (8-12 regions):
     - Physical description
     - Who controls it now?
     - What was here during vampire era?
     - Climate and resources
     - Major settlements
     - Vampire ruins in this region
     - Notable features/mysteries

3. Create vampire ruin files in `05-geography/vampire-ruins/`:
   - For each major underground city (3-5):
     - Location (hidden? partially known?)
     - Size and original purpose
     - What era was it built?
     - Current condition
     - What remains functional/dangerous?
     - What secrets does it contain?
     - Who knows about it?
     - How to access it
     - Role in story

   - For minor sites (12-20):
     - Brief description
     - What's there
     - Discovery status

4. Create `05-geography/relic-distribution.md`:
   - Map every significant vampire artifact to location
   - Who currently possesses it?
   - Do they know what it is?
   - What does it do?
   - Role in story potential

**Output**: Fully mapped world with strategic relic placement

**Validation**: Are relics distributed to create conflicts and revelations?

---

### **Phase 8: Character Architecture**

**Objective**: Develop protagonist and major supporting cast

**Tasks**:
1. Create `06-characters/protagonist.md` with exhaustive detail:
   - **True history**: When/why/how he was created
   - **What he remembers**: Accurate and false memories
   - **What he knows**: About himself, vampire history, magic
   - **What he doesn't know**: Gaps and mysteries
   - **Abilities**: Specific powers and limitations
   - **Personality**: Shaped by vampire culture and isolation
   - **Fatal flaw**: What could destroy him?
   - **Want vs Need**: What he thinks he wants vs what he needs
   - **Character arc**: Journey through story
   - **Relationships**: How he connects with other characters
   - **Secrets he keeps**: What he hides from others
   - **Discovery timeline**: What he learns when

2. Create POV character files in `06-characters/major-characters/`:
   - Create 5-8 major POV characters (following GRRM model)
   - Each needs:
     - Full background and history
     - Personal wound/trauma
     - Motivations (want vs need)
     - Fatal flaw
     - Starting position in world
     - Character arc trajectory
     - Relationship to vampire history
     - Relationship to protagonist
     - What they know/don't know
     - Secrets they keep
     - How they could die (no plot armor)

3. Create supporting character files in `06-characters/supporting-cast/`:
   - 20-30 secondary characters
   - Each with their own agenda
   - Not just reactive to main characters

4. Create `06-characters/character-relationship-map.md`:
   - Who knows whom?
   - What relationships exist?
   - What conflicts?
   - What secrets between characters?

**Output**: Fully developed character constellation

**Validation**: Does each character have agency and could carry their own story?

---

### **Phase 9: Magic & Technology Systems**

**Objective**: Define how magic works and what vampire technology could do

**Tasks**:
1. Create `07-artifacts-magic/magic-system.md`:
   - How magic works in this world (rules)
   - What magic can/cannot do
   - Costs of using magic (why it's limited)
   - Different magical traditions
   - How protagonist's abilities differ
   - How vampire magic differs from current magic

2. Create `07-artifacts-magic/vampire-technology.md`:
   - What could vampires do at their peak?
   - How did it work? (blend of tech and magic)
   - What required infrastructure that no longer exists?
   - What could theoretically still work?
   - What's dangerous to activate?

3. Create `07-artifacts-magic/relic-registry.md`:
   - Comprehensive list of all vampire artifacts
   - For each artifact:
     - Name and description
     - What it does (specific mechanics)
     - Current location
     - Who has it/knows about it
     - How it relates to plot
     - Historical context (when created, why)

4. Create `07-artifacts-magic/artifact-plot-connections.md`:
   - Which artifacts drive which plot threads?
   - How do characters discover/compete for them?

**Output**: Coherent magic/technology system with specific artifacts

**Validation**: Are limitations and costs clearly defined? Does it avoid "magic solves everything"?

---

### **Phase 10: Shadow Truths & Secrets**

**Objective**: Document what really happened vs what people believe

**Tasks**:
1. Create `08-secrets/shadow-truths.md`:
   - For each major historical "fact":
     - What people believe
     - What scholars think
     - What actually happened
     - Why the truth is hidden/forgotten
     - Who knows the truth
     - Evidence that exists
     - How truth could be discovered

2. Create `08-secrets/protagonist-true-history.md`:
   - Complete accurate backstory
   - Why he was created
   - What the experiment was supposed to do
   - What went wrong/right
   - How he survived
   - What happened to others like him
   - Why his memories are fragmented/false

3. Create `08-secrets/discoverable-secrets.md`:
   - Plot revelations organized by story progression
   - What gets revealed when?
   - How is it discovered?
   - What's the impact?

4. Create `08-secrets/permanent-mysteries.md`:
   - What will NEVER be fully explained
   - Mysteries that maintain sense of depth
   - Questions without definitive answers

**Output**: Complete truth layer beneath public history

**Validation**: Do secrets create dramatic irony? Are revelations well-timed?

---

### **Phase 11: Plot Architecture**

**Objective**: Structure the actual story threads and character arcs

**Tasks**:
1. Create `09-plot-architecture/story-arcs.md`:
   - 5-10 major plot threads
   - For each thread:
     - Initial situation
     - Key turning points
     - Major characters involved
     - How it connects to other threads
     - Resolution trajectory

2. Create `09-plot-architecture/character-arcs.md`:
   - For each POV character:
     - Starting position
     - Character journey beats
     - Transformation trajectory
     - Potential ending states (multiple options)

3. Create `09-plot-architecture/intersection-points.md`:
   - Where do separate storylines converge?
   - What events affect multiple characters?
   - How do character paths cross?
   - Timeline of intersections

4. Create `09-plot-architecture/consequence-chains.md`:
   - Track cause and effect across storylines
   - How does action in thread A affect thread B?
   - Build consequence cascade for major events

**Output**: Story architecture with interwoven threads

**Validation**: Do storylines organically intersect? Are there consequence chains?

---

### **Phase 12: GRRM Style Guide**

**Objective**: Create writing guidelines to maintain consistent GRRM tone/style

**Tasks**:
Create `10-style-guide/grrm-writing-principles.md`:

**Core Principles**:
1. **No Pure Heroes or Villains**
   - Every character is hero of their own story
   - Justified in their own minds
   - Complex motivations
   - Capability for both good and evil

2. **Actions Have Consequences**
   - Choices matter and echo forward
   - No consequence-free decisions
   - Small choices can have huge impacts
   - Mercy can lead to disaster; cruelty can save lives

3. **Anyone Can Die**
   - No plot armor
   - Death is permanent and meaningful
   - Major characters can die if story demands it
   - But death must serve story, not shock value

4. **Deep POV Technique**
   - Write from inside character's head
   - Character's biases color everything
   - They only know what they know
   - Unreliable narrators are normal

5. **Historical Ambiguity**
   - No single true version of history
   - Multiple interpretations coexist
   - Characters argue about past
   - Reader must judge for themselves

6. **Political Complexity**
   - No simple solutions
   - Competing legitimate interests
   - Moral gray areas
   - Power struggles are personal AND institutional

7. **Sensory Detail**
   - Describe food, smells, textures
   - Make world feel lived-in
   - Details create immersion
   - But avoid info dumps

8. **Dialogue Reveals Character**
   - Each character has distinct voice
   - Speech patterns reflect background
   - What's NOT said matters
   - Subtext is critical

9. **Chapter Structure**
   - One POV per chapter
   - End on hooks/cliffhangers
   - Cut away at crucial moments
   - Rotate between storylines to build tension

10. **Earned Moments**
    - No deus ex machina
    - Plant seeds early
    - Payoffs must be set up
    - Reader should feel "of course" not "what?"

**Narrative Voice**:
- Present tense or past tense? (Choose one)
- Third person limited (deep POV)
- Voice adapts to POV character
- Vocabulary reflects character's background
- Internal monologue vs external observation balance

**Scene Construction**:
- Start late, end early
- Every scene has conflict
- Scenes must advance plot OR character (preferably both)
- Scene-sequel structure (action-reaction)
- Layer multiple conflicts in single scene

**Dialogue Guidelines**:
- Subtext over exposition
- Characters rarely say exactly what they mean
- Power dynamics in every conversation
- Interruptions, trailing off, body language
- Distinct vocabulary per character

**Description Techniques**:
- Show through character's perspective
- Avoid neutral camera-view descriptions
- Use specific details, not generic
- Description serves mood/theme
- Compare to things character would know

**Worldbuilding Integration**:
- History through character knowledge
- No "as you know, Bob" exposition
- Reveal world through action and dialogue
- Create sense of iceberg (more beneath surface)
- Contradictions in accounts are features not bugs

**Handling Magic/Fantasy Elements**:
- Magic has costs and limitations
- Treat fantastical as normal to characters
- Technology of another era feels like magic
- No explaining what characters take for granted
- Wonder AND practicality

**Pacing**:
- Mix action and character moments
- Political intrigue scenes as tense as battles
- Quiet moments before storms
- Multiple storylines create natural rhythm
- Don't rush to climaxes

**Common Pitfalls to Avoid**:
- ❌ Over-explaining world or magic
- ❌ Making protagonist always right
- ❌ Convenient solutions
- ❌ One-dimensional antagonists
- ❌ Protecting favorite characters
- ❌ Rushed consequences
- ❌ Anachronistic language/attitudes
- ❌ Forgetting what characters know/don't know

---

### **Phase 13: Consistency Validation**

**Objective**: Check all work for internal consistency and integration

**Tasks**:
1. Create `11-validation/consistency-checks.md`:
   - Timeline validation protocol
   - Character knowledge tracking
   - Geographical consistency
   - Cultural consistency
   - Power level consistency
   - Technology consistency

2. Create `11-validation/timeline-validator.md`:
   - Chronological check of all events
   - Look for contradictions
   - Verify cause-effect chains
   - Check character ages/lifespans
   - Ensure travel times make sense

3. Create `11-validation/character-tracker.md`:
   - What does each character know at each point?
   - Track secrets and revelations
   - Verify relationship consistency
   - Check character arc logic
   - Ensure no one knows things they shouldn't

4. Create `11-validation/integration-tests.md`:
   - Do cultures' histories logically conflict?
   - Do artifact placements create intended conflicts?
   - Are consequence chains complete?
   - Do character motivations drive plot organically?
   - Are themes woven through all layers?

5. Run specific validation checks:
   - **Historical Consistency**: Do events in master timeline contradict cultural memories in logical ways?
   - **Character Knowledge**: Does protagonist know things that contradict what scholars know?
   - **Geographical Logic**: Are ruin placements consistent with historical events?
   - **Power Scaling**: Is magic/technology power consistent throughout?
   - **Cultural Behavior**: Do races act consistently with their values?

**Output**: Validation report with any inconsistencies flagged

**Action**: Fix inconsistencies before proceeding

---

## Iteration & Session Management

### At Start of Each Session:

1. **Load context**:
   ```bash
   cat /home/claude/vampire-world/00-project-index/master-index.md
   cat /home/claude/vampire-world/00-project-index/next-steps.md
   ```

2. **Review previous session**:
   ```bash
   tail -50 /home/claude/vampire-world/00-project-index/session-log.md
   ```

3. **Load relevant reference files** for current phase

### During Each Session:

1. **Work on specified phase** from next-steps.md
2. **Create/update files** in appropriate directories
3. **Cross-reference** with existing documents
4. **Note dependencies** and connections
5. **Document decisions** and reasoning

### At End of Each Session:

1. **Update master-index.md** with completion status:
   ```markdown
   ## Completion Status
   - [x] Phase 1: Foundation Setup
   - [x] Phase 2: Collapse Event
   - [ ] Phase 3: Pre-Collapse History (in progress)
   - [ ] Phase 4: Post-Collapse History
   ...
   ```

2. **Update session-log.md**:
   ```markdown
   ## Session [Date/Number]
   ### Completed:
   - Created collapse-event.md with multi-causal analysis
   - Documented 5 contradictory interpretations
   - Established consequence cascade

   ### Decisions Made:
   - Collapse was triggered by dimensional breach experiment
   - Protagonist was part of soldier enhancement program
   - Three vampire factions survived underground

   ### Next Session Focus:
   - Begin Pre-Collapse vampire faction development
   - Create Golden Age era documentation
   ```

3. **Update next-steps.md**:
   ```markdown
   ## Next Steps
   1. Continue Phase 3: Pre-Collapse History
      - Create era-golden-age.md
      - Document vampire factions
      - Establish protagonist's creation context
   2. Cross-reference with collapse event
   3. Validate timeline consistency
   ```

---

## Quality Standards

Every document must meet these standards:

### **Depth Over Breadth**
- Don't list generically - be specific
- "Vampire Council of Immortals" NOT "vampire government"
- "The Sundering War (Year -234)" NOT "a war happened"

### **Internal Logic**
- Every event has causes
- Every choice has consequences
- No contradictions unless intentional (and flagged)

### **Multiple Perspectives**
- Show how different groups interpret events
- Create legitimate disagreements
- No single "correct" version unless that's the point

### **Story Service**
- Every element must serve the story
- Pass the "So what?" test
- Cut elements that don't generate conflict or depth

### **GRRM Authenticity**
- Moral complexity
- Political realism
- Historical ambiguity
- Earned moments
- Consequences matter

### **Documentation Clarity**
- Use markdown headers and formatting
- Cross-reference other documents
- Include dates and specifics
- Make it easy to reload context

---

## Consistency Enforcement Mechanisms

### **Naming Conventions**
Create `naming-registry.md`:
- All character names
- All place names
- All artifact names
- All faction names
- Check for duplicates or confusion

### **Date Tracking**
In every document with events, include:
- Absolute dates (Year X)
- Relative dates (Y years before collapse)
- Duration (lasted X years)

### **Knowledge Matrices**
Track "who knows what" for:
- Major secrets
- Historical truths
- Artifact locations
- Character backgrounds

### **Reference Linking**
In documents, link to related files:
```markdown
This event connects to:
- [The Collapse Event](../02-timeline/collapse-event.md#dimensional-breach)
- [Human Cultural Memory](../03-cultures/races/humans.md#collapse-narrative)
- [Protagonist Creation](../06-characters/protagonist.md#true-history)
```

### **Version Control**
- Commit work after each major document
- Tag completion of each phase
- Enable rollback if needed

---

## Critical Success Factors

✅ **Modularity**: Any file can be updated without breaking others
✅ **Traceability**: Every element connects to specific story purposes
✅ **Consistency**: No contradictions except intentional ones
✅ **Depth**: 10x more detail than will appear on page
✅ **Accessibility**: Easy to reload context in any session
✅ **Flexibility**: Can expand or modify as story develops
✅ **GRRM Authenticity**: Captures style and approach

---

## First Session Directive

**Begin with Phase 1: Foundation Setup**

1. Create the directory structure
2. Create `00-project-index/master-index.md`
3. Create `01-core-framework/premise-constraints.md` (document the given premise)
4. Create `01-core-framework/core-mysteries.md` (develop the driving questions)
5. Create `01-core-framework/thematic-pillars.md` (establish themes)
6. Update master index with completion
7. Log session and set next steps

**Then await further direction on Phase 2 or ask clarifying questions about the premise.**

---

## Key Principles to Remember

1. **This is iterative** - Perfection comes through revision
2. **Context limits are real** - Document thoroughly for future sessions
3. **Consistency is paramount** - Check and cross-reference constantly
4. **GRRM style is essential** - Complexity, ambiguity, consequences
5. **Story drives everything** - If it doesn't serve story, cut it
6. **Interwoven is key** - Everything connects to everything else

**This is not just worldbuilding - this is creating the architecture for an epic that feels as real, complex, and morally ambiguous as Game of Thrones.**
