# Activity 3 Guide

**Course:** Mastering Semiconductor Key Modules for Enhanced CMOS Process Integration and Device Performance  
**Course code:** TGS-2024051248  
**Package:** v8.0 · 20 August 2026  
**Activity:** 3 — Balance Implantation and Thermal Budget  
**Alignment:** LO1 · K1, A2, A3  
**Duration:** 60 minutes


## Goal

Create an implant-to-anneal decision trail that balances activation, junction depth, damage recovery and channeling risk.

## Scenario

After a source/drain extension implant, sheet resistance is above target and short-channel control is drifting. The team must distinguish dose/energy error from activation and diffusion effects.

## What You Need

- Implant and RTP data cards in the worksheet
- Legacy diagrams for beam scanning, channeling, damage and RTP
- Evidence template

## Detailed Step-by-Step Procedure

1. Read the target dose, implant energy, tilt/twist, sheet resistance and junction-depth specifications.
2. Compare actual dose and energy with the target and note whether the deviation can explain the electrical signature.
3. Inspect the channeling indicator and decide whether tilt/twist or an amorphising layer should be reviewed.
4. Use the damage/activation card to separate as-implanted lattice damage from electrically active dopant.
5. Compare the furnace and RTP thermal cycles by peak temperature, dwell time and ramp rate.
6. Predict how each thermal cycle affects activation, lateral diffusion and junction depth.
7. Choose a containment action for the current lot and a recipe action for the next engineering split.
8. Define the minimum verification set: sheet resistance map, SIMS profile or junction-depth proxy, and electrical monitor.
9. Complete the risk statement: action, expected benefit, possible adverse effect and stop condition.

## Acceptance Criteria

- [ ] The recommendation distinguishes implant dose/energy, damage and activation mechanisms.
- [ ] Thermal-budget effects on activation and diffusion are explicit.
- [ ] Follow-up measurements can confirm or reject the proposed cause.

## Reflection Questions

1. Why does a shorter high-temperature RTP cycle often protect shallow junctions?
2. How can a sheet-resistance improvement still hide a device-performance problem?

## Evidence to Submit

- Completed worksheet.
- Completed evidence template with file names or screenshots.
- The activity output named with the `A03-` prefix.
- A final release/hold/recommendation statement supported by measurements.

## Troubleshooting

- If a workbook opens in protected view, save a local copy before editing blue input cells.
- If formulas do not update, enable automatic calculation and press **Ctrl+Shift+F9** (Windows) or **Command+=** (macOS Excel).
- If a diagram becomes crowded, separate the process flow from the evidence/control loop; cross-reference them with numbered hand-offs.
- If the conclusion is uncertain, state what is known, what is not known, and the next measurement that can resolve it.
