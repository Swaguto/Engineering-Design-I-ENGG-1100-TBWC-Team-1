# Teddy Bear Wheelchair — ENGG\*1100 F2026 Design Project

**Course:** Engineering and Design I (ENGG\*1100), University of Guelph — Fall 2026
**Team:** Team 1
**Project:** The Teddy Bear Wheelchair (TBWC) — TBWC Sustainable Mobility Challenge 2026
**Source document:** *ENGG\*1100 F2026 Design Project Description*, version 2026-09-27

---

## 1. Project Summary

Our team is designing, building, testing, documenting, and demonstrating an **autonomous Teddy
Bear Wheelchair** — a powered mobility device that carries a Teddy Bear (TB) around a marked
course, navigates accessibility features autonomously, and delivers a recyclable item into a
recycling bin.

The TB is treated as a **human equivalent**: the design must keep the client secure and
comfortable, must not tip, and must be evaluated for accessibility, eco-friendliness, safety,
and aesthetics — not just speed. The project is a full engineering design cycle: empathize,
define, ideate, prototype, test, and assess, supported by cost analysis, engineering
calculations, drawings, and documented reflection.

Teams are formed of **6 students** from the same lab section. Teams of 6, working as a team,
are assigned by the professors and finalized at the start of the Week 3 Design Lab.

### Design objectives (100 competition points)

| # | Objective | Points | Summary |
|---|-----------|--------|---------|
| 1 | **Accessibility Speed Run** | 30 | Autonomously complete the course **Line A → Line C → Line A**, traversing the ramp end-to-end at least once, as fast as possible |
| 2 | **Recycling Delivery Mission** | 30 | Autonomously carry a recyclable item and validly release/launch it into the recycling bin from between **Line B and Line C** |
| 3 | **Minimize TBWC Mass** | 20 | Lightest functional design; weighed without the TB before the events |
| 4 | **Maximize Aesthetic Appeal** | 20 | Visually appealing to TBs, environmentally conscious, and showcasing accessibility and/or safety features |

> Criteria 1–3 make up the **80-point Challenge Day performance score**, which carries a **10%
> bonus multiplier** if we build our own motor control circuit. Aesthetics (20 pts) is assessed
> separately in the Week 10 Design Lab and is worth **10%** of the course grade.

---

## 2. Scoring Details

### 2.1 Accessibility Speed Run (30 pts)

The TBWC must traverse the full course autonomously. A **raw time** is only recorded if the full
course is completed.

**Case 1 — full course + at least one complete ramp crossing:**

| Raw time | Points |
|----------|--------|
| ≤ 8 s | 30 |
| ≤ 9 s | 28 |
| ≤ 10 s | 26 |
| ≤ 12 s | 24 |
| > 12 s | 22 |

**Case 2 — course not fully completed** (no raw time; scored on furthest valid progress):

| Progress | Points |
|----------|--------|
| Completes A→C→A but no successful full ramp crossing | 18 |
| Reaches Line B and returns to Line A | 16 |
| Reaches Line B, then reverses at least 1 Atrium square | 14 |
| Reaches Line C but < 1 Atrium square on the return | 12 |
| Reaches Line B but < 1 Atrium square on the return | 9 |
| Fully crosses Line A but does not reach Line B | 3 |
| Does not fully cross Line A | 0 |

Progress achieved after leaving the course boundaries — or by bypassing the ramp — does not count.

### 2.2 Recycling Delivery Mission (30 pts)

**Case 1 — valid release (item meets requirements, released between Lines B and C):**

| Outcome | Points |
|---------|--------|
| Item comes to rest **inside the recycling bin** | 30 |
| Item comes to rest inside the Recycling Bay, not in the bin | 24 |
| Item contacts the Recycling Bay but rests outside | 18 |
| Valid release between B and C, does not reach the Recycling Bay | 14 |

**Case 2 — no valid release:**

| Outcome | Points |
|---------|--------|
| Fully crosses Line B carrying the item but no valid release | 9 |
| Releases from beyond Line C | — |
| Releases between B and C but item fails the Recyclable Item Requirements | — |
| Fully crosses Line A but does not fully cross Line B | 3 |
| Does not fully cross Line A | 0 |

**Recyclable item requirements:** clean, dry, empty, lightweight, safe to handle, recognizable
as a household recyclable, larger than a ping-pong ball, and **not** a ball or other spherical
object. Non-compliant items cap the attempt at 9 points. No electronics, hardware, sharp
objects, food waste, Styrofoam, or plastic bags.

### 2.3 TBWC Mass (20 pts)

| Mass | Points |
|------|--------|
| < 1200 g | 20 |
| < 1300 g | 18 |
| < 1400 g | 16 |
| < 1500 g | 14 |
| < 1600 g | 12 |
| < 1700 g | 10 |
| ≥ 1700 g | 8 |

Mass and physical configuration **cannot change between events**.

### 2.4 Aesthetics (20 pts)

Judged on visual appeal to Teddy Bears, environmental responsibility, and demonstrated
accessibility/safety features. The TBWC must clearly display our **section and team number**
(e.g. `S05-08`).

Submission is a **2-slide PowerPoint**: one slide with a photo highlighting aesthetic,
eco-friendly and safety details; one slide with an embedded **360° video**. Each slide may carry
a 30-second voice-over narration.

### 2.5 Penalties and score caps

| Condition | Effect |
|-----------|--------|
| TB falls out **or** TBWC tips over during an attempt | That attempt capped at **10 pts** |
| Fails any required **Safety and Comfort Code** test | Speed Run capped at **15 pts** |
| Fails the required **Static Tipping Code** | Recycling Delivery capped at **15 pts** |
| TBWC contacts the Recycling Bay wall or the bin | **4-pt** penalty, applied at most once per attempt |
| Kit not fully disassembled and inventoried on return | **50%** penalty on the TBWC project mark |

**Attempts:** one initial attempt per challenge, plus **two additional attempts total** at our
discretion (either or both events). The highest valid score in each event is used. Configuration
must remain unchanged between events.

All TBWCs undergo a Static Tipping Test and a TBWC Code (202609a) compliance check.

---

## 3. Compliance: TBWC Code 202609a

These are not optional — they cap our scores if violated.

### 3.1 Static Stability
- Must **not tip over** at rest on a **30° slope**, with the TB seated and competition batteries
  installed. The recyclable payload is excluded from the static test.
- Tested in **four directions** (forward, backward, and two lateral) using a wooden ramp with a
  small block of wood to prevent rolling.
- **Calculated** tipping angle must **exceed 35° in all four directions** for a margin of safety
  (TB seated, competition batteries installed, payload excluded).
- Physical test failure caps the Recycling Delivery Mission at 15 pts before the bonus multiplier.

### 3.2 Teddy Bear Security and Comfort
- The TB must not fall out under normal operations (including the whole challenge).
- **Seat belts and harnesses are NOT an acceptable means** of satisfying this. The TBWC is gently
  turned upside down (no shaking) with the TB in place; if the TB stays in, Code 2b is
  satisfied — provided no belt or harness moves out of the way during the test.
- **Field of view:** minimum continuous **240° horizontal** visual view at TB eye level looking
  straight forward (120° either side of centre) and a minimum **40° vertical** view (20° either
  side of centre).
- The TB's **head must sit higher than the rest of its torso** when seated in the TBWC.
- Failure of any required test caps **both** the Speed Run and the Recycling Delivery at 15 pts.

---

## 4. Supplies and Constraints

### 4.1 Kit provided

**Mechanical**
- One Meccano Super Set (exact pieces may vary)

**Electronics and control**
- **1 microcontroller** — Arduino Mega 2560, Arduino UNO R3, or an ATmega328P-based UNO
  R3-compatible board
- **Motors** — 1 DC motor + 1 SG90 micro servo. Maximum **1 microcontroller and 2 motors** in
  the final design; the servo may be exchanged for a second DC motor via Project Office Hours.
- **1 breadboard** — **must** be used for all wiring. No soldering. No tape.
- USB cable, AA battery holders, L298N integrated motor driver module, on/off switch, 2 LEDs

### 4.2 Optional supplies

- **Sensors** — Ultrasonic (HC-SR04) or Infrared. Limited to **1 sensor** in the final design;
  request the specific type at Project Office Hours.
- **Custom motor control circuit** — optional. Build one and we earn a **10% bonus multiplier**
  on the 80-point Challenge Day score (e.g. 60 × 1.1 = 66). Requires the **L6205 Motor Driver
  IC**, 2× 1N4148 diodes, resistors (100 Ω, 2× 100 kΩ), and capacitors (2× 5600 pF, 10 nF,
  100 nF, 100 µF) — acquired from the Project Support TAs.
- **3D-printed components** — **conditional approval only.** Must be custom-designed for a
  specific function; standard/off-the-shelf parts may not be reproduced. Max **2 parts** and
  **2 cubic inches** of printed material. Requires prior approval from the 3D Printing Support
  TAs plus a **decision matrix** justifying 3D printing over alternatives, with **3D CAD
  drawings**. Missing approval evidence in the final report costs a **10% deduction**.

### 4.3 Additional materials

Team-purchased materials must be inexpensive, must **not** replace structural or mechanical
functions already covered by the Meccano components, and must be documented in the Bill of
Materials and Cost Analysis.

**Permitted:** cardboard and similar (no wood), popsicle sticks / tongue depressors / toothpicks,
nuts/bolts/screws, additional Meccano brackets/plates/rods, individual gears and pulleys,
elastics and springs, string and thread, twist ties, common waste materials (fabric, plastic,
paper).

**Prohibited:** adhesives, sealants, solder, **tape and glue**; zip ties or equivalents; LEGO,
K'nex or equivalent construction systems; ready-made components repurposed for the same function
(e.g. a toy car wheel); Raspberry Pi boards; wood (except popsicle sticks, tongue depressors,
toothpicks); Styrofoam; bulk materials that can be shaped into custom parts (wood, aluminum, sheet
metal); pressurized air; **mousetraps (new restriction for 2026)**.

> If unsure whether a material is acceptable, email **engg1100@uoguelph.ca**. Attempting to find
> a loophole may result in disqualification on Challenge Day.

### 4.4 Other equipment notes
- A scale reading to the nearest gram is required to measure component and assembled mass. A small
  kitchen scale is suitable, and **its cost may be excluded from the supply budget**.
- Keeping the kit clean, organized, and inventoried matters — see the kit return penalty above.

---

## 5. Cost Analysis

Three tracked categories:

1. **Development Cost — COE Supplied Material:** anything supplied by the College of Engineering
   and used in the final design, **plus any replacement parts** (destroy a sensor, replace it,
   and both count).
2. **Development Cost — Team Purchased or Sourced Material:** anything the team bought (e.g.
   batteries) or that wasn't in the supplied kit (e.g. recycled material). Keep these minimal.
3. **TBWC Final Design Material Production Cost:** the cost of one complete TBWC as configured for
   Challenge Day — i.e. what a single unit would cost to manufacture.

**Rules**
- Cost based on the **minimum purchasable unit** (report a full package even if partly unused).
- For reused/recyclable material not directly purchased: **$10/kg**. If it *was* purchased for
  the project, use the actual purchase cost and cite the source.
- For materials on hand, estimate using the cost of an equivalent new item.
- **Provide references for all costs.**

---

## 6. Engineering Analysis Deliverables

All of the following must be professionally documented — neat, well organized, and retraceable
by the reader. Handwritten work may be scanned and embedded into a Word or PDF.

| Deliverable | Method / notes |
|-------------|----------------|
| **Centre of mass** | Hand calculation. Origin at the **back, bottom and left** of the design = (0, 0, 0). Include **all** parts including non-starter-kit components; estimate each component's CoM. Spacers, nuts, wire, etc. may be excluded for the hand calc — **but justify each exclusion**. |
| **Tipping analysis** | Theoretical tipping angle in **all four directions** (left, right, front, back), built on the CoM results. Completed in a **professionally documented Excel spreadsheet** and **verified by hand** using the major components. Demonstrated in lecture (not in the notes). Regardless of the numbers, the TBWC must not tip during the challenge. |
| **Life cycle impact** | Estimate **CO₂ and CH₄** emissions using the supplied Life Cycle Inventory Data table. Also quantify and comment on **total consumable battery use** across the project and compare it against the design components' impact. Done in a professionally documented **Excel spreadsheet**, with **unit-conversion examples included to validate the spreadsheet**. |
| **Arduino code** | One submission per major subsystem (forward motion, stopping, reversing, sensor detection, projectile launch/release, …). Each segment **commented on** for effectiveness and possible future improvements. |
| **Assembly sketching** | Orthographic projection **hand sketch**: isometric view **with shading**, plus top, front and side. All major components included so the TBWC is recognizable. 2D graphic elements (paint, decals) and Meccano part holes need not be drawn. |
| **Electrical drawings** | Detailed **AutoCAD** drawing of the electrical circuit configuration. |

**Tip from the course:** complete the engineering analysis early — it is largely independent of
the build, and end-of-semester deadlines collide with every other course's finals. Track
components as you go in your logbook (mass of each part, how close to tipping, environmental
footprint); relying on memory loses you the justifications you will need later.

---

## 7. The Teddy Bear (Our Client)

| Property | Value |
|----------|-------|
| Height | ~17 cm standing, 12 cm sitting |
| Width (hips) | ~8 cm |
| Depth (belly to tail) | ~6 cm |
| Mass | 86.0 g ± 2.0 g |

The TB and its nearly identical twin are available for testing during design labs later in the
term.

---

## 8. Field of Play Dimensions

One Atrium floor tile = **60 cm × 60 cm**.

**Ramp**
| Dimension | Value |
|-----------|-------|
| Total length | 1.2 m |
| Ascending slope | 0.3 m |
| Flat platform | 0.6 m |
| Descending slope | 0.3 m |
| Platform height | 5 cm |
| Width | 1.2 m |

**Recycling Bay**
| Dimension | Value |
|-----------|-------|
| Bay width | 1.8 m |
| Bay depth | 1.2 m |
| Gate width | 0.6 m |
| Side / front wall height | 30 cm |
| Rear wall height | 45 cm |

**Recycling Bin**
| Dimension | Value |
|-----------|-------|
| Inner width | 18 in (46 cm) |
| Inner depth | 14 in (36 cm) |
| Height | 12.5 in (32 cm) |
| Front cutout height (from top) | 4 in (10 cm) |
| Front cutout width (at top) | 16 in (41 cm) |
| Front cutout width (4 in from top) | 14 in (36 cm) |

**Speed Bump**
| Dimension | Value |
|-----------|-------|
| Length | 120 cm |
| Width | 15 cm |
| Height | 2 cm |

**Lines.** Line A is the start/finish. Line B is the intermediate reference and the ramp location
for the Speed Run, and sits **two Atrium tiles beyond Line A** as the minimum release line for
the Recycling Mission. Line C is the required turnaround point and the maximum release line. A
backboard beyond Line C defines the rear end of the course; left and right sidelines define the
course boundaries.

> The 3D layout and top-view course drawings are images in Appendix A of the project description
> and are not reproduced here — consult the source PDF for exact course dimensions.

---

## 9. Schedule and Deliverables

Design labs run in **ACE Studio THRN 2420**. All deadlines are **11:59:00 PM Eastern** and all
submissions go to the appropriate **CourseLink Dropbox**.

| Week | Lab dates | Deliverable | Due | Weight |
|------|-----------|-------------|-----|--------|
| 3 | Sep 28 – Oct 02 | Teams finalized | — | — |
| 4 | Oct 05 – 09 | **Initial Team Contract** | 11:59 pm, 1 day before Design Lab | N/A |
| 7 | Oct 26 – 30 | **Prototype Demonstration** | In Design Lab | N/A |
| 7 | — | **Prototype Report (Team)** + Updated Team Contract | 11:59 pm, 2 days after Design Lab | 4% |
| 7 | — | **Prototype Report (Individual)** | 11:59 pm, 4 days after Design Lab | 4% |
| 7 | — | **Self & Peer Evaluation I** (Feedback Fruits) | 11:59 pm, 4 days after Design Lab | 2% |
| 9 | — | **Aesthetics Submission** (2-slide PPT) | 11:59 pm, Sat Nov 14, 2026 | 10% |
| 10 | Nov 16 – 20 | **Aesthetics Evaluation** | In Design Lab | — |
| 11 | Nov 23 – 27 | **Final Performance Demonstration Challenge** | In Design Lab | 10% |
| 11 | — | **Final Design Report (Team)** + Final Team Contract | 11:59 pm, 2 days after Design Lab | 11% |
| 11 | — | **Final Design Report (Individual)** | 11:59 pm, 4 days after Design Lab | 4% |
| 11 | — | **Self & Peer Evaluation II** (Feedback Fruits) | 11:59 pm, 4 days after Design Lab | 2% |

Team + Individual Final Design Reports combined are worth **15%**. **Late submissions receive a
grade of zero** — submit drafts to CourseLink as you go; multiple submissions are saved and only
the most recent is graded.

### 9.1 Week 7 — Prototype Demonstration

The TBWC is **not** expected to be complete. We must show that two major subsystems work:

1. **Rolling Chassis** — a functional rolling chassis with motors attached, producing controlled
   powered motion in both travel directions using the Arduino and motor controller.
2. **Recycling Delivery Mechanism** — a functional mechanism that can carry or retain a
   recyclable item and perform a controlled release or launch action.

Final-challenge performance (speed, accessibility, delivery distance, accuracy, autonomous
release timing) is **not** required yet, and the delivery mechanism need not be integrated with
the rolling chassis or Arduino-controlled. The point is to prove the operating principle works
and that we are making real progress toward an integrated design.

**Team Prototype Report** sections: cover page (title, authors with names/login IDs/signatures,
date, responsibility statement, **Generative AI disclosure**), table of contents, TBWC design
summary (intro paragraph, prototype photo, **≥3 idea-generation sketches each** for chassis and
delivery mechanism, concept-selection rationale with a **decision matrix**, orthographic draft
sketches, Arduino code for Subsystem 1, BOM and cost analysis), prototype performance summary,
project management (**WBS, Gantt chart, risk identification and mitigation**), and reflection
using the **What / So What / Now What** model — including accessibility, eco-friendliness and
aesthetics features and the team contract review.

**Individual Prototype Report** documents your role across the design process phases (empathize,
define, ideate, prototype, test, assess) with **logbook entries as evidence**. The course
explicitly discourages splitting tasks and working in isolation.

### 9.2 Week 11 — Final Performance & Reporting

Report to **THRN 1435** at the start of your scheduled session for roll call, instructions and
mass measurement, then proceed to the Atrium for the challenge events. Full participation is
required — a student who is late, absent, or does not participate **will not receive the team
performance score**.

**Final Design Report** sections: cover page, table of contents, TBWC design summary (photo of
each view — top, side, front, isometric — plus BOM and cost analysis, with COE-supplied vs.
team-added items separated and matching the exploded view), engineering analysis, project
management, **one-page performance table** (ramp speed run, recycling delivery, measured mass,
aesthetics, safety, plus calculated values: calculated mass, CoM in (x, y, z) cm, CO₂ and CH₄
emissions, total battery consumption), and reflection — project (What/So What/Now What on ramp
speed run, delivery mission, mass, cost, aesthetics, safety) and team.

**Appendices:** centre of mass and tipping analysis, life cycle impact estimation, Arduino code,
isometric drawing, orthographic projection sketches, and AutoCAD electrical drawings.

**Individual Final Report:** introduction (your roles, how the team organized meetings and
assigned work), contribution elements tied to design-process phases, logbook evidence, and a
fair and professional assessment of each team member's contributions.

---

## 10. Team Contract

The **Initial Team Contract** is due at 11:59 pm the day before the Week 4 Design Lab. It is
reviewed and updated after the Week 7 Prototype Demonstration, and again for the Week 11 final
team reflection.

> The team contract will be added to this repository in a follow-up commit.

Each team member must maintain an **individual logbook** documenting activities and
contributions. An inadequate logbook can affect the assessment of individual contribution and
may lead to an adjustment to the individual grade for the team portion of the project. The
individual reports must reference specific logbook entries as evidence.

---

## 11. Repository Layout

```
.
├── README.md          # This file — project summary and requirements digest
└── TEAM_CONTRACT.md   # Team Contract (to be added)
```

Additional working material — Arduino source, CAD drawings, spreadsheets (tipping, cost,
life cycle), sketches, and logbook references — will be organized here as the project progresses.

---

## 12. References

- *ENGG\*1100 F2026 Design Project Description*, version 2026-09-27 (primary source)
- Course Outline — ENGG\*1100 F26
- Assessment Summary — ENGG\*1100 F26
- Team Contract Template — ENGG\*1100 F26
- [National Building Code](https://www.nationalcodes.nrc.gc.ca/eng/nbc/index.html)
- [Ontario Electrical Safety Code](https://www.esasafe.com/contractors/the-ontario-electrical-safety-code)
- Material acceptability queries: **engg1100@uoguelph.ca**

*Course materials are subject to change; instructors reserve the right to make corrections,
alterations and additions. The Project Description will be updated on CourseLink throughout the
term.*
