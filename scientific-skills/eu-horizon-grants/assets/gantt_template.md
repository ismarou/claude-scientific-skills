# Gantt Chart Templates for Horizon Europe Proposals

## Overview

Gantt charts are required in most Horizon Europe proposals to visualize the project timeline, work package duration, deliverables, and milestones. This document provides templates and guidance for creating effective Gantt charts.

---

## Basic ASCII Gantt Template

### 36-Month Project (3 Years)

```
Work Package              Year 1              Year 2              Year 3
                     Q1  Q2  Q3  Q4    Q1  Q2  Q3  Q4    Q1  Q2  Q3  Q4
                    M1-3 M4-6 M7-9 M10-12 M13-15 M16-18 M19-21 M22-24 M25-27 M28-30 M31-33 M34-36

WP1: Management     ████████████████████████████████████████████████████████████████████████
WP2: Requirements   ████████████████████
WP3: Development              ████████████████████████████████████████
WP4: Validation                                   ████████████████████████████████
WP5: Piloting                                                   ████████████████████████
WP6: Dissemination  ████████████████████████████████████████████████████████████████████████

Milestones          ▽           ▽               ▽                   ▽               ▽
                   MS1         MS2             MS3                 MS4             MS5

Deliverables       ●D1.1      ●D2.1  ●D2.2           ●D3.1    ●D3.2  ●D4.1  ●D5.1  ●Final
```

**Legend:**
- █ = Work package active
- ▽ = Milestone
- ● = Deliverable

---

### 48-Month Project (4 Years)

```
Work Package                Year 1              Year 2              Year 3              Year 4
                        M1-12               M13-24              M25-36              M37-48
                     Q1 Q2 Q3 Q4       Q1 Q2 Q3 Q4       Q1 Q2 Q3 Q4       Q1 Q2 Q3 Q4

WP1: Management      ██████████████████████████████████████████████████████████████████████████
WP2: Research        ██████████████████████████████████
WP3: Development              ██████████████████████████████████████████████
WP4: Integration                              ██████████████████████████████████████
WP5: Validation                                       ██████████████████████████████████
WP6: Piloting                                                   ██████████████████████████
WP7: Exploitation    ██████████████████████████████████████████████████████████████████████████

▽ MS1     ▽ MS2          ▽ MS3       ▽ MS4          ▽ MS5       ▽ MS6          ▽ MS7
●D1.1    ●D2.1 ●D2.2    ●D3.1 ●D3.2    ●D4.1 ●D4.2    ●D5.1 ●D5.2    ●D6.1 ●D6.2    ●Final
```

---

## Detailed Monthly Gantt Template

### 36-Month Project with Monthly Detail

```
                    Year 1                          Year 2                          Year 3
WP   1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36

WP1  ██████████████████████████████████████████████████████████████████████████████████████████████████████████
WP2  ████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
WP3  ░░░░░░████████████████████████████████████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
WP4  ░░░░░░░░░░░░░░░░░░░░░░████████████████████████████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
WP5  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░██████████████████████████████████████████████████████░░░░░░░░░░
WP6  ██████████████████████████████████████████████████████████████████████████████████████████████████████████

MS   ▽        ▽              ▽              ▽              ▽              ▽              ▽           ▽
     1        2              3              4              5              6              7           8

D    ●        ●  ●           ●    ●         ●    ●         ●    ●         ●    ●         ●           ●
    1.1      2.1 2.2        3.1  3.2       4.1  4.2       5.1  5.2       6.1  6.2       6.3         F
```

**Legend:**
- █ = Active period
- ░ = Inactive period
- ▽ = Milestone (numbered)
- ● = Deliverable

---

## Gantt Chart with Dependencies

```
              M1-6    M7-12   M13-18  M19-24  M25-30  M31-36

WP1: Mgmt    ████████████████████████████████████████████████
              │
              ▼
WP2: Specs   ████████████
              │        │
              │        └─────────┐
              ▼                  ▼
WP3: Dev          ████████████████████████████
                       │             │
                       │             └─────────┐
                       ▼                       ▼
WP4: Integ              ████████████████████████████
                                  │        │
                                  ▼        │
WP5: Valid                    ████████████████████████
                                           │
                                           ▼
WP6: Pilot                            ████████████████████
                                                    │
                                                    ▼
WP7: Dissem  ████████████████████████████████████████████████
```

---

## Summary Tables to Accompany Gantt

### Work Package Summary Table

| WP | Title | Lead | Start | End | Person-Months |
|----|-------|------|-------|-----|---------------|
| WP1 | Project Management | P1 | M1 | M36 | 18 |
| WP2 | Requirements & Design | P2 | M1 | M12 | 36 |
| WP3 | Development | P3 | M6 | M24 | 72 |
| WP4 | Integration | P3 | M18 | M30 | 48 |
| WP5 | Validation | P4 | M24 | M36 | 36 |
| WP6 | Dissemination | P1 | M1 | M36 | 24 |
| **Total** | | | | | **234** |

### Milestone Summary

| MS | Title | Month | WP | Verification |
|----|-------|-------|-----|--------------|
| MS1 | Kick-off | M1 | WP1 | Meeting held |
| MS2 | Specs complete | M9 | WP2 | D2.2 approved |
| MS3 | Development complete | M24 | WP3 | Prototype ready |
| MS4 | Integration complete | M30 | WP4 | System tests passed |
| MS5 | Project end | M36 | WP1 | Final review |

### Deliverable Summary

| Del. | Title | WP | Month | Type | Lead |
|------|-------|----|-------|------|------|
| D1.1 | Project Management Plan | WP1 | M3 | R | P1 |
| D1.2 | Data Management Plan | WP1 | M6 | DMP | P1 |
| D2.1 | State of Art Report | WP2 | M6 | R | P2 |
| D2.2 | Requirements Specification | WP2 | M9 | R | P2 |
| D3.1 | Prototype v1.0 | WP3 | M18 | DEM | P3 |
| D3.2 | Prototype v2.0 | WP3 | M24 | DEM | P3 |
| D4.1 | Integration Report | WP4 | M27 | R | P3 |
| D5.1 | Validation Report | WP5 | M33 | R | P4 |
| D6.1 | Final Report | WP6 | M36 | R | P1 |

---

## Best Practices for Gantt Charts

### Visual Design

**Do:**
- Use clear, readable fonts (minimum 10pt)
- Use consistent colors/shading for each WP
- Clearly mark milestones and deliverables
- Include a legend
- Show dependencies if complex

**Don't:**
- Overcrowd with too much detail
- Use colors that don't print well in B&W
- Forget to label months/years
- Make it so small it's unreadable

### Content Guidelines

**Include:**
- All work packages
- Start and end months for each WP
- Key milestones
- Major deliverables (or all if space permits)
- Project duration clearly marked

**Consider:**
- Task-level detail (if space permits)
- Dependencies between WPs
- Critical path highlighting
- Review/reporting periods

### Alignment Tips

- Ensure Gantt aligns with WP descriptions
- Check that all deliverables appear at correct months
- Verify milestones are at appropriate decision points
- Confirm person-month allocations make sense given timing

---

## Tools for Creating Gantt Charts

### Free Options
- **Mermaid** (markdown-based diagrams)
- **PlantUML** (text-based diagrams)
- **Google Sheets** (with formatting)
- **LibreOffice Calc** (with conditional formatting)
- **GanttProject** (open source software)

### Commercial Options
- **Microsoft Project**
- **MS Excel** (with templates)
- **Smartsheet**
- **TeamGantt**
- **Monday.com**

### Tips for MS Word/PDF
- Create as image in dedicated tool
- Ensure resolution sufficient for print
- Test readability at actual print size
- Consider landscape orientation if needed

---

## Example: Complete Gantt for 48-Month Project

```
[ACRONYM] Project Timeline

                        2025                2026                2027                2028
                    Q1 Q2 Q3 Q4      Q1 Q2 Q3 Q4      Q1 Q2 Q3 Q4      Q1 Q2 Q3 Q4
                    M1-3 M4-6 M7-9 M10-12 M13-15 M16-18 M19-21 M22-24 M25-27 M28-30 M31-33 M34-36 M37-39 M40-42 M43-45 M46-48

WP1 Management       ████████████████████████████████████████████████████████████████████████████████████████████████
WP2 State of Art     ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
WP3 Methodology            ████████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
WP4 Development                  ████████████████████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
WP5 Integration                              ████████████████████████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░
WP6 Validation                                           ████████████████████████████████████████░░░░░░░░░░░░░░░░
WP7 Piloting                                                       ████████████████████████████████████████████████
WP8 Dissemination    ████████████████████████████████████████████████████████████████████████████████████████████████

Milestones   ▽       ▽       ▽              ▽              ▽              ▽              ▽              ▽
             KO     R1      R2             R3             R4             R5             R6            Final

Deliverables ●      ●  ●   ●   ●          ●   ●          ●   ●          ●   ●          ●   ●          ●
            1.1   2.1 3.1 2.2 3.2        4.1 4.2        5.1 5.2        6.1 6.2        7.1 7.2        8.1

Legend: ████ Active  ░░░░ Inactive  ▽ Milestone  ● Deliverable

KO=Kick-off, R1-R6=Review points, Final=Project completion
```
