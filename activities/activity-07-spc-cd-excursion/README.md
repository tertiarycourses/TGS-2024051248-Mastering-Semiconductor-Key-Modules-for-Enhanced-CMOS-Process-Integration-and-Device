# Activity 7 Guide

**Course:** Mastering Semiconductor Key Modules for Enhanced CMOS Process Integration and Device Performance<br>
**Course code:** TGS-2024051248<br>
**Package:** v9.0 · 20 August 2026<br>
**Activity:** 7 — Respond to an SPC CD Excursion<br>
**Alignment:** LO2 · K2, A3, A4, A5<br>
**Duration:** 90 minutes


## Goal

Recreate the legacy P-chart/SPC exercises and generate the corrective-action chain used in Practical Performance Task 2.

## Scenario

STI active-area CD is drifting across production lots. A point crosses the upper control limit and a seven-point upward run appears before the alarm. The team must contain risk and restore control.

## What You Need

- SPCdata.xlsx and p_Chart.xlsx in this folder
- Legacy control-limit, Xbar/R, p/c/u-chart and out-of-control rule slides
- Corrective-action worksheet and evidence template

## Detailed Step-by-Step Procedure

1. Open SPCdata.xlsx and review the raw subgroup CD data, timestamps, tool IDs and lot IDs.
2. Check that subgroup means and ranges use formulas and that the chart updates when a blue input changes.
3. Identify the first out-of-control point and the earlier non-random run signal.
4. Separate control limits from product specification limits in the worksheet.
5. Write the immediate containment actions: stop/hold affected lots, preserve evidence, notify ownership and prevent automatic release.
6. Stratify the data by tool/chamber, wafer position, product and time to narrow the source.
7. Review lithography focus/dose, etch endpoint/profile and metrology calibration as candidate causes.
8. Define confirmation measurements using pre-etch CD, post-etch CD and cross-section profile evidence.
9. Select a corrective action and a controlled engineering split; state the rollback trigger.
10. Verify recovery using consecutive stable subgroups and an updated capability check.
11. Open p_Chart.xlsx and repeat the logic for variable sample sizes using defect proportion rather than CD measurements.
12. Export the SPC evidence and complete the follow-up action record.

## Acceptance Criteria

- [ ] The response identifies both limit violation and non-random pattern.
- [ ] Containment precedes root-cause adjustment and protects affected lots.
- [ ] Corrective action, verification criteria and follow-up owner are explicit.

## Reflection Questions

1. Why must the team investigate a non-random run even when all points remain inside control limits?
2. Which chart is appropriate for CD measurements, and which is appropriate for defect proportions?

## Evidence to Submit

- Completed worksheet.
- Completed evidence template with file names or screenshots.
- The activity output named with the `A07-` prefix.
- A final release/hold/recommendation statement supported by measurements.

## Troubleshooting

- If a workbook opens in protected view, save a local copy before editing blue input cells.
- If formulas do not update, enable automatic calculation and press **Ctrl+Shift+F9** (Windows) or **Command+=** (macOS Excel).
- If a diagram becomes crowded, separate the process flow from the evidence/control loop; cross-reference them with numbered hand-offs.
- If the conclusion is uncertain, state what is known, what is not known, and the next measurement that can resolve it.
