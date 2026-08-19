# Activity 6 Guide

**Course:** Mastering Semiconductor Key Modules for Enhanced CMOS Process Integration and Device Performance<br>
**Course code:** TGS-2024051248<br>
**Package:** v9.0 · 20 August 2026<br>
**Activity:** 6 — Analyse Yield and Process Capability<br>
**Alignment:** LO2 · K2, A3, A4<br>
**Duration:** 75 minutes


## Goal

Recreate and improve the legacy ProcessCapability exercise using an auditable Excel workbook with dynamic formulas.

## Scenario

A gate module has a target CD of 100 nm with specification limits at 90 and 110 nm. The process owner needs Cp/Cpk evidence and a reasoned yield-risk statement before qualification.

## What You Need

- ProcessCapability.xlsx in this folder
- Legacy Cp/Cpk, sigma, yield and defect-density slides
- Worksheet and evidence template

## Detailed Step-by-Step Procedure

1. Open ProcessCapability.xlsx and read the Instructions sheet before changing any inputs.
2. Go to Data and confirm the 30 hardcoded CD observations are shown in blue text.
3. Review the Analysis formulas for mean, sample standard deviation, Cp and Cpk; do not replace formulas with values.
4. Compare the mean with the 100 nm target and describe accuracy (centering).
5. Compare the standard deviation with the specification width and describe precision (spread).
6. Interpret Cp as potential capability and Cpk as actual capability considering centering.
7. Change one blue input value to 118 nm and observe how the metrics and out-of-spec count recalculate; then restore the value.
8. Use the histogram and capability summary to decide capable, conditionally capable or not capable.
9. Record one containment action and one long-term process action.
10. Export the Analysis sheet to PDF or capture a screenshot named A06-capability-evidence.

## Acceptance Criteria

- [ ] Workbook formulas remain intact and show no Excel errors.
- [ ] The learner distinguishes Cp from Cpk and links both to process evidence.
- [ ] The decision includes containment, corrective action and verification.

## Reflection Questions

1. Why can Cp be acceptable while Cpk is unacceptable?
2. Why does a capability index not prove that the process is statistically stable?

## Evidence to Submit

- Completed worksheet.
- Completed evidence template with file names or screenshots.
- The activity output named with the `A06-` prefix.
- A final release/hold/recommendation statement supported by measurements.

## Troubleshooting

- If a workbook opens in protected view, save a local copy before editing blue input cells.
- If formulas do not update, enable automatic calculation and press **Ctrl+Shift+F9** (Windows) or **Command+=** (macOS Excel).
- If a diagram becomes crowded, separate the process flow from the evidence/control loop; cross-reference them with numbered hand-offs.
- If the conclusion is uncertain, state what is known, what is not known, and the next measurement that can resolve it.
