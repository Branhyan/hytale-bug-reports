# Water passes through closed trapdoors

## Environment
- **Version:** pre-release/2026.01.29-301e13929
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
Medium — World Interaction / Fluids / Building

## Description
When placing a trapdoor in a closed state, it is not recognized as a solid block for water. As a result, water passes through it as if no block were present.

This creates an inconsistency with doors, which correctly block water when closed, and limits creative gameplay possibilities such as controllable water sources, fluid-based builds, or potential future mechanisms.

## Steps to Reproduce
1. Create a structure that allows water to be held at an elevated level
2. Place a trapdoor underneath in a closed state
3. Observe whether the water passes through the trapdoor

## Expected Result
As with doors, water should not pass through the block when the trapdoor is closed.

## Actual Result
Water passes through the closed trapdoor as if there were no block present.

## Reproduction Rate
100% — Always

## QA Notes
- All trapdoor variants were tested and reproduce the issue
- Doors correctly block water when closed, indicating inconsistent behavior

## Evidence
Screenshot showing water passing through closed trapdoor
<img width="2560" height="1440" alt="Hytale2026-02-04_12-45-59" src="https://github.com/user-attachments/assets/dbee8823-e5ac-46d5-a463-2838ea4be245" />

---

**Reported by:** Krimm (`@Krimm_QA`)/Branhyan
