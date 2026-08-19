# Activity 1 Guide

**Course:** Mastering Semiconductor Key Modules for Enhanced CMOS Process Integration and Device Performance<br>
**Course code:** TGS-2024051248<br>
**Package:** v9.0 · 20 August 2026<br>
**Activity:** 1 — Build a CMOS Process Module Map<br>
**Alignment:** LO1 · K1, A1, A2<br>
**Duration:** 45 minutes


## Goal

Organise the legacy module coverage into a defensible FEOL-to-BEOL flow and expose the interfaces that can propagate variation.

## Scenario

A new 300 mm logic product is moving from process development into a pilot manufacturing line. The integration team needs one agreed process map before module owners set recipes and control plans.

## What You Need

- Activity worksheet and evidence template in this folder
- Learner slides covering wafer fab, photolithography, etch, implant, thermal, film, CMP and integrated flows
- A3 paper or a digital drawing tool

## Detailed Step-by-Step Procedure

1. Open the worksheet and write the target product assumptions: substrate type, logic technology family and the intended final device outcome.
2. Create seven module lanes: photolithography, etch/clean, ion implantation, diffusion/RTP, film deposition, CMP and metrology/control.
3. Place the major FEOL stages in order: wafer preparation, isolation, well formation, gate stack, source/drain formation and contacts.
4. Add the BEOL stages: dielectric deposition, via/trench patterning, barrier/seed, metal fill, CMP, passivation and wafer sort.
5. For each hand-off, identify the incoming measurable characteristic, such as CD, overlay, film thickness, dose, sheet resistance or surface planarity.
6. Mark at least three feedback loops where metrology can cause hold, rework, recipe correction or engineering disposition.
7. Circle two interactions where a change in one module can create a downstream electrical or yield effect.
8. Check the map against the provided process-flow slides and correct missing or duplicated stages.
9. Export or photograph the final map and name the evidence file A01-process-map.

## Acceptance Criteria

- [ ] The map contains all seven key process modules and distinguishes FEOL from BEOL.
- [ ] At least eight process hand-offs have a measurable characteristic.
- [ ] At least three control/feedback loops and two cross-module interactions are justified.

## Reflection Questions

1. Which module has the greatest ability to propagate a hidden defect downstream, and why?
2. What evidence would allow the integration owner to release the lot to the next module?

## Evidence to Submit

- Completed worksheet.
- Completed evidence template with file names or screenshots.
- The activity output named with the `A01-` prefix.
- A final release/hold/recommendation statement supported by measurements.

## Troubleshooting

- If a workbook opens in protected view, save a local copy before editing blue input cells.
- If formulas do not update, enable automatic calculation and press **Ctrl+Shift+F9** (Windows) or **Command+=** (macOS Excel).
- If a diagram becomes crowded, separate the process flow from the evidence/control loop; cross-reference them with numbered hand-offs.
- If the conclusion is uncertain, state what is known, what is not known, and the next measurement that can resolve it.
