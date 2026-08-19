# Activity 2 Guide

**Course:** Mastering Semiconductor Key Modules for Enhanced CMOS Process Integration and Device Performance  
**Course code:** TGS-2024051248  
**Package:** v8.0 · 20 August 2026  
**Activity:** 2 — Diagnose a Pattern-Transfer Process Window  
**Alignment:** LO1 · K1, A2  
**Duration:** 60 minutes


## Goal

Connect mask/resist/exposure decisions to etch profile and select a stable corrective action without masking the root cause.

## Scenario

A contact layer shows intermittent bridging and open defects. Lithography CD, resist profile and plasma-etch selectivity must be reviewed together rather than as isolated module results.

## What You Need

- Pattern-transfer worksheet and process-window workbook
- Legacy diagrams on resist polarity, Rayleigh resolution, OPC, selectivity and anisotropy
- Calculator or spreadsheet software

## Detailed Step-by-Step Procedure

1. Review the defect images in the worksheet and classify each as bridge, open, incomplete etch, undercut or resist-collapse risk.
2. Open pattern-transfer-window.xlsx and read the focus, exposure dose, post-develop CD and post-etch CD observations.
3. Mark cells that violate the target post-etch CD range of 88-112 nm.
4. Compare the lithography CD bias with the post-etch CD bias to decide whether the dominant shift occurs before or during etch.
5. Check whether edge cells fail more often than centre cells; record the spatial signature.
6. Select one lithography lever (focus, dose, resist thickness or bake) and one etch lever (gas ratio, bias power, pressure or over-etch).
7. Predict the intended effect and one possible side effect for each lever.
8. Write a confirmation plan using CD-SEM before etch, CD-SEM after etch and profile inspection on a cross-section.
9. Record a release decision: accept, conditional release, hold for engineering, or scrap.

## Acceptance Criteria

- [ ] Every defect is linked to a plausible lithography/etch mechanism.
- [ ] The dominant CD-shift stage is supported by before/after evidence.
- [ ] Corrective levers include predicted benefit, risk and verification measurement.

## Reflection Questions

1. Why can improving resolution reduce depth of focus?
2. When does additional over-etch protect yield, and when does it create reliability risk?

## Evidence to Submit

- Completed worksheet.
- Completed evidence template with file names or screenshots.
- The activity output named with the `A02-` prefix.
- A final release/hold/recommendation statement supported by measurements.

## Troubleshooting

- If a workbook opens in protected view, save a local copy before editing blue input cells.
- If formulas do not update, enable automatic calculation and press **Ctrl+Shift+F9** (Windows) or **Command+=** (macOS Excel).
- If a diagram becomes crowded, separate the process flow from the evidence/control loop; cross-reference them with numbered hand-offs.
- If the conclusion is uncertain, state what is known, what is not known, and the next measurement that can resolve it.
