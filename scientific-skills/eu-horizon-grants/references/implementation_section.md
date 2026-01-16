# Implementation Section: Writing Section 3 of Horizon Europe Proposals

## Overview

Section 3 (Quality and Efficiency of Implementation) typically carries the remaining weight in Horizon Europe evaluations (often 20%). This section must demonstrate that your project has a realistic work plan, competent consortium, and effective management structure to deliver the promised results.

**Evaluation Question**: "To what extent is the proposed work plan and consortium composition appropriate and effectively managed?"

**Threshold**: 3 out of 5 (lower than Excellence and Impact, but still critical)

---

## Section Structure

### Standard RIA/IA Part B Section 3 Structure

```
3. QUALITY AND EFFICIENCY OF IMPLEMENTATION
   3.1 Work plan and resources
       - Work package descriptions
       - Deliverables and milestones
       - Critical risks and mitigation
       - Resource allocation
   3.2 Capacity of participants and consortium as a whole
       - Consortium composition
       - Partner descriptions
       - Third parties
```

---

## 3.1 Work Plan and Resources

### Work Package Structure

**Standard WP Organization**:

| WP# | Type | Purpose |
|-----|------|---------|
| WP1 | Management | Project coordination, reporting |
| WP2-n | Technical | Research/innovation activities |
| Final WP | Cross-cutting | Dissemination, exploitation, communication |

**WP Numbering Convention**:
- Sequential numbering (WP1, WP2, WP3...)
- Alternative: Functional grouping (WP1-2 management, WP3-6 research, WP7-8 impact)

### Work Package Description Table

For each work package, provide:

```markdown
## Work package [number]

| Work package number | WP[X] |
|---------------------|-------|
| Work package title | [Title] |
| Lead beneficiary | [Number and short name] |
| Start month | M[X] |
| End month | M[Y] |
| Person-months | [Total PM] |

**Objectives**:
[Clear, measurable objectives for this WP - bullet points recommended]

**Description of work**:

**Task [X.1]: [Task title]** (Lead: [Partner], M[start]-M[end])
[Description of task activities]
Participants: [Partner1] (X PM), [Partner2] (Y PM), [Partner3] (Z PM)

**Task [X.2]: [Task title]** (Lead: [Partner], M[start]-M[end])
[Description of task activities]
Participants: [Partner1] (X PM), [Partner2] (Y PM)

[Repeat for all tasks]
```

### Task Descriptions

**Good Task Description**:
- Clear scope and boundaries
- Specific activities
- Identifiable outputs
- Assigned lead and participants
- Realistic person-month allocation
- Clear timing (start/end months)

**Example**:
```markdown
**Task 3.2: Prototype development and testing** (Lead: PartnerX, M12-M24)
PartnerX will develop a functional prototype integrating the algorithms
from WP2 with the hardware interface from Task 3.1. The prototype will
undergo laboratory testing (M18-21) and field validation (M22-24) with
end-users from the advisory board. Testing protocols will follow ISO
standards where applicable.

Participants: PartnerX (8 PM), PartnerY (4 PM), PartnerZ (2 PM)
```

### Deliverables

**Deliverable Table Format**:

| Del. No. | Deliverable name | WP | Lead | Type | Diss. level | Due |
|----------|------------------|----|------|------|-------------|-----|
| D1.1 | Project Management Plan | WP1 | P1 | R | PU | M3 |
| D1.2 | Data Management Plan | WP1 | P1 | DMP | PU | M6 |
| D2.1 | State of art report | WP2 | P2 | R | PU | M12 |
| D3.1 | Prototype v1.0 | WP3 | P3 | DEM | CO | M18 |

**Deliverable Types**:
| Code | Type | Description |
|------|------|-------------|
| R | Report | Document, publication |
| DEM | Demonstrator | Prototype, pilot |
| DEC | Websites, patent filings, videos, etc. | Communication outputs |
| DATA | Data sets, databases | Research data outputs |
| DMP | Data Management Plan | FAIR data plan |
| ETHICS | Ethics requirement | Ethics approval documentation |
| ORDP | Open Research Data Pilot outputs | FAIR data packages |
| OTHER | Other | Software, technical drawings |

**Dissemination Levels**:
| Code | Level | Description |
|------|-------|-------------|
| PU | Public | Available to all |
| SEN | Sensitive | Limited access |
| EU-RES | EU Restricted | As per Commission decision |
| EU-CON | EU Confidential | As per Commission decision |
| EU-SEC | EU Secret | As per Commission decision |

**Deliverable Timing Guidelines**:
- Spread deliverables across project timeline
- Major deliverables at year ends for periodic reports
- DMP required early (typically M6)
- Ethics deliverables according to ethics review requirements
- Don't cluster all deliverables at project end

### Milestones

**Milestone Table Format**:

| MS No. | Milestone name | WP | Due | Verification means |
|--------|----------------|----|-----|-------------------|
| MS1 | Consortium kick-off | WP1 | M1 | Kick-off meeting held |
| MS2 | Requirements finalized | WP2 | M6 | Requirements document approved |
| MS3 | Prototype validated | WP3 | M24 | Test report showing targets met |
| MS4 | Pilot completed | WP4 | M36 | Pilot evaluation report |

**Good Milestone Criteria**:
- Marks significant achievement or decision point
- Objectively verifiable (not "work completed")
- Go/no-go decision points where applicable
- Evenly distributed through project
- 1-2 milestones per year typically

**Verification Means Examples**:
- Meeting minutes approved
- Document delivered and accepted
- Test results meeting specifications
- Stakeholder sign-off obtained
- Prototype demonstrating functionality

### Gantt Chart

**Required Elements**:
- All work packages with duration bars
- Key deliverables marked
- Milestones indicated
- Logical dependencies shown
- Clear month/year scale

**Example ASCII Gantt**:

```
Work Package         Year 1              Year 2              Year 3
                  Q1  Q2  Q3  Q4    Q1  Q2  Q3  Q4    Q1  Q2  Q3  Q4
WP1: Management   ████████████████████████████████████████████████████
WP2: Research     ████████████████████████
WP3: Development          ████████████████████████████████
WP4: Validation                       ████████████████████████████
WP5: Pilot                                    ████████████████████████
WP6: Impact       ████████████████████████████████████████████████████

▽ M1: Kick-off    ● D2.1           ▽ M2: Prototype    ● D4.1  ▽ M3: Final
```

### PERT Diagram (If Required)

Some calls request PERT charts showing dependencies:

```
          ┌─────────┐
          │  WP2    │
    ┌────→│Research │────┐
    │     └─────────┘    │
┌───┴───┐             ┌──▼──────┐      ┌─────────┐
│ WP1   │             │  WP3    │─────→│  WP4    │
│Mgmt   │             │ Develop │      │ Validate│
└───┬───┘             └─────────┘      └────┬────┘
    │     ┌─────────┐                       │
    └────→│  WP6    │←──────────────────────┘
          │ Impact  │
          └─────────┘
```

### Critical Risks and Mitigation

**Risk Assessment Table**:

| Risk | Description | WP | Likelihood | Impact | Mitigation |
|------|-------------|-----|------------|--------|------------|
| R1 | Technology performance below target | WP3 | Medium | High | Alternative approach in Task 3.4; early testing in M12 |
| R2 | Partner withdrawal | WP1 | Low | High | Consortium Agreement provisions; backup partner identified |
| R3 | Regulatory delay | WP4 | Medium | Medium | Early engagement with authorities; parallel preparation |
| R4 | COVID-19/pandemic impact | All | Low | Medium | Remote working protocols; virtual meetings established |

**Risk Categories**:
- **Technical**: Method/technology performance
- **Resource**: Personnel, equipment, funding
- **External**: Regulatory, market, stakeholder
- **Consortium**: Partner performance, communication
- **Timeline**: Dependencies, parallel activities

**Likelihood/Impact Definitions**:
| Level | Likelihood | Impact |
|-------|------------|--------|
| Low | <20% | Minor adjustments needed |
| Medium | 20-60% | Significant replanning |
| High | >60% | Objectives at risk |

### Resource Allocation

**Person-Months by Partner and WP**:

| Partner | WP1 | WP2 | WP3 | WP4 | WP5 | WP6 | Total |
|---------|-----|-----|-----|-----|-----|-----|-------|
| P1-Coord | 12 | 8 | 6 | 4 | 2 | 6 | 38 |
| P2-Univ | 2 | 24 | 12 | 8 | 4 | 4 | 54 |
| P3-SME | 1 | 4 | 18 | 12 | 6 | 3 | 44 |
| P4-RTO | 1 | 8 | 8 | 16 | 8 | 3 | 44 |
| **Total** | **16** | **44** | **44** | **40** | **20** | **16** | **180** |

**Resource Justification**:
- Explain large allocations
- Justify subcontracting needs
- Explain major equipment purchases
- Address any unusual cost items

---

## 3.2 Capacity of Participants and Consortium

### Consortium Composition

**Required Elements**:
- Why this specific consortium
- Complementary expertise
- Sectoral balance
- Geographical coverage
- No unnecessary duplication

**Consortium Composition Table**:

| # | Short name | Country | Type | Main expertise | Key personnel |
|---|------------|---------|------|----------------|---------------|
| 1 | COORD | DE | REC | Project management, [expertise] | Dr. X (PM), Prof. Y |
| 2 | UNIV1 | NL | HES | [Discipline expertise] | Prof. A, Dr. B |
| 3 | SME1 | ES | PRC | [Commercial expertise] | Mr. C (CEO), Dr. D |
| 4 | RTO1 | FR | REC | [Technical expertise] | Dr. E, Dr. F |

### Partner Descriptions

For each partner, provide:

```markdown
### Partner [X]: [Full name] ([SHORT NAME])

**Organization profile**: [Brief description of organization, type, size,
main activities]

**Role in project**: [Specific role and responsibilities]

**Key personnel**:
- **[Name]** ([Position]): [Brief CV - relevant experience and
  publications/achievements]
- **[Name]** ([Position]): [Brief CV]

**Relevant experience**: [2-3 most relevant previous projects or
qualifications]

**Infrastructure/facilities**: [Key resources available for the project]
```

**Key Personnel Information**:
- Name and position
- Relevant qualifications
- Track record (key publications, patents, projects)
- Role in this project
- Time commitment (% FTE or person-months)

### Consortium Balance

**Sectoral Distribution**:
```markdown
| Sector | Partners | % Budget |
|--------|----------|----------|
| Academia (HES) | P2, P5 | 35% |
| Research Organizations (REC) | P1, P4 | 30% |
| Industry - Large (PRC) | P6 | 15% |
| Industry - SME (PRC) | P3, P7 | 20% |
```

**Geographical Distribution**:
```markdown
| Region | Partners | Countries |
|--------|----------|-----------|
| Western Europe | P1, P2, P6 | DE, NL, FR |
| Southern Europe | P3, P4 | ES, IT |
| Northern Europe | P5 | SE |
| Eastern Europe | P7 | PL |
```

### Management Structure

**Governance Diagram**:

```
                    ┌─────────────────────┐
                    │   General Assembly  │
                    │ (All Partners, 1x/y)│
                    └──────────┬──────────┘
                               │
                    ┌──────────▼──────────┐
                    │ Steering Committee  │
                    │  (WP Leads, 2x/y)   │
                    └──────────┬──────────┘
                               │
            ┌──────────────────┼──────────────────┐
            │                  │                  │
    ┌───────▼───────┐  ┌───────▼───────┐  ┌───────▼───────┐
    │  Project      │  │   Technical   │  │   Advisory    │
    │  Coordinator  │  │   Manager     │  │   Board       │
    │  (P1)         │  │   (P2)        │  │   (External)  │
    └───────┬───────┘  └───────────────┘  └───────────────┘
            │
    ┌───────┴───────┐
    │ WP Leaders    │
    │ (P1-P6)       │
    └───────────────┘
```

**Management Bodies**:

| Body | Composition | Meetings | Decision scope |
|------|-------------|----------|----------------|
| General Assembly | All partners (1 rep each) | Annual | Strategy, disputes |
| Steering Committee | WP Leaders | Quarterly | Technical decisions |
| Project Coordinator | P1 | Continuous | Day-to-day management |
| Advisory Board | External experts | Semi-annual | Strategic advice |

**Decision-Making Procedures**:
- Routine decisions: Project Coordinator
- Technical decisions: Steering Committee (majority)
- Strategic decisions: General Assembly (qualified majority)
- Disputes: Escalation procedure defined in Consortium Agreement

### Communication and Reporting

**Internal Communication**:
| Type | Frequency | Participants | Tool |
|------|-----------|--------------|------|
| WP meetings | Monthly | WP members | Video call |
| SC meetings | Quarterly | WP leads | Video call |
| GA meetings | Annual | All partners | In-person |
| Day-to-day | Continuous | As needed | Email, chat |

**External Reporting**:
- Periodic reports to EC (typically every 18 months)
- Financial statements
- Deliverable submissions through portal
- Amendment requests as needed

### Third Parties and Subcontracting

**Types of Third Parties**:

| Type | Relationship | Funding | Examples |
|------|-------------|---------|----------|
| Affiliated entity | Linked to beneficiary | Receives funding | Subsidiary, parent |
| Associated partner | Formal agreement | No EC funding | Advisory, in-kind |
| Subcontractor | Commercial contract | Via beneficiary | Specialized services |
| Third party giving in-kind | Contributing resources | No EC funding | Data providers |

**Third Party Declaration**:
```markdown
**Third parties involved in the action**

**[Partner X] involves the following third party:**
- Name: [Third party name]
- Type: [Affiliated entity/Associated partner/etc.]
- Country: [Country]
- Tasks: [Description of their involvement]
- Justification: [Why this third party is needed]
```

---

## Visual Elements for Implementation Section

### Required Figures/Tables

1. **Gantt Chart**: Work package timeline with milestones and deliverables
2. **PERT Diagram**: If dependencies are complex (optional for most calls)
3. **Management Structure**: Governance and decision-making diagram
4. **Consortium Map**: Geographic distribution (optional but helpful)

### Figure Guidelines

- Clear, professional appearance
- Readable at PDF scale
- Consistent style with rest of proposal
- Self-explanatory with caption
- Referenced in text

---

## Implementation Section Checklist

### Work Packages
- [ ] Logical structure covering all objectives
- [ ] Clear WP descriptions with objectives
- [ ] Tasks well-defined with participants
- [ ] Person-months realistic and justified
- [ ] Lead beneficiaries appropriate

### Deliverables
- [ ] All key outputs captured
- [ ] Appropriate types assigned
- [ ] Dissemination levels correct
- [ ] Due dates realistic and spread across project
- [ ] Numbered correctly

### Milestones
- [ ] Key decision points captured
- [ ] Verification means defined
- [ ] Spread across project timeline
- [ ] Go/no-go decisions included

### Gantt Chart
- [ ] All WPs shown
- [ ] Key deliverables marked
- [ ] Milestones indicated
- [ ] Dependencies visible
- [ ] Readable and professional

### Risks
- [ ] Major risks identified
- [ ] All risk categories covered
- [ ] Realistic likelihood/impact assessment
- [ ] Specific mitigation measures
- [ ] Contingency plans included

### Consortium
- [ ] All partners described
- [ ] Complementary expertise demonstrated
- [ ] Key personnel identified
- [ ] Sectoral balance shown
- [ ] Geographical coverage adequate

### Management
- [ ] Governance structure clear
- [ ] Decision-making procedures defined
- [ ] Communication plan included
- [ ] Reporting requirements addressed
- [ ] Third parties declared

### Resources
- [ ] Person-months justified
- [ ] Budget aligned with activities
- [ ] Equipment needs explained
- [ ] Subcontracting justified
- [ ] Balance across consortium

---

## Common Mistakes in Implementation Section

### Work Plan
- **Too many/few WPs**: Should be manageable (typically 5-8 for 3-year project)
- **Overlapping tasks**: Duplication between WPs
- **Missing integration**: No cross-WP coordination
- **Unclear outputs**: Tasks without deliverables
- **Unrealistic timing**: Too compressed or too spread out

### Deliverables and Milestones
- **Too many deliverables**: Quality over quantity
- **Vague milestones**: "Work completed" not verifiable
- **Clustering at end**: All due in final months
- **Missing key outputs**: Main results not captured

### Consortium
- **Missing expertise**: Gaps in required capabilities
- **Partner imbalance**: One partner dominates
- **Geographic clustering**: Missing EU coverage
- **Weak descriptions**: Generic partner profiles
- **Missing key personnel CVs**: No track record shown

### Management
- **Overly complex**: Governance structure larger than project
- **Missing procedures**: No conflict resolution
- **Coordinator overload**: Too many responsibilities on one partner
- **No advisory mechanism**: No external input

### Resources
- **Budget mismatch**: Resources don't match activities
- **PM imbalance**: Some partners over/under-allocated
- **Missing justification**: Large items unexplained
- **Unrealistic estimates**: PM costs don't match market rates

---

## Writing Tips for Implementation

### Work Package Descriptions

**Be Specific About Activities**:
```markdown
❌ "Research will be conducted on topic X"

✓ "Task 2.1 will conduct systematic literature review using PRISMA
methodology, followed by quantitative analysis of identified datasets
using machine learning algorithms (Random Forest, XGBoost)"
```

### Show Dependencies

**Link WPs Together**:
```markdown
"WP3 will receive validated requirements from D2.2 (M12) and commence
prototype development. Intermediate results will be shared with WP4
through joint Task 3.2/4.1 meetings (M18, M24)."
```

### Justify Partner Roles

**Explain Why Each Partner**:
```markdown
"[PARTNER] leads WP3 due to their unique expertise in [specific area],
demonstrated through [previous project/publication]. They bring [X]
years of experience and access to [facility/resource]."
```

### Make PM Allocation Credible

**Show Calculation Basis**:
```markdown
"WP2 allocation (44 PM) based on:
- Task 2.1 literature review: 8 PM (2 researchers × 4 months)
- Task 2.2 data collection: 20 PM (field work × 4 partners)
- Task 2.3 analysis: 16 PM (senior + junior researcher × 8 months)"
```

### Management Proportionate to Project Size

```markdown
Small project (EUR 1-2M, 3-4 partners): Simple structure, monthly calls
Medium project (EUR 3-5M, 5-8 partners): Steering Committee quarterly
Large project (EUR 5M+, 10+ partners): Full governance structure
```

---

**Next**: See `consortium_building.md` for detailed guidance on finding partners and building effective consortia.
