# Lava does not ignite or destroy adjacent flammable blocks

## Environment
- **Version:** pre-release/2026.02.06-0baf7c5aa
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
🟡 Medium — Gameplay / Fire Mechanics / World Interaction

## Description
When lava is placed in contact with flammable blocks, there is no reaction. Lava also does not interact with vegetation such as trees.

## Steps to Reproduce
1. Place flammable blocks in a configuration that can support lava
2. Place lava on top of or adjacent to the flammable blocks
3. Observe the result

## Expected Result
Flammable blocks in contact with lava should be ignited or destroyed when exposed to lava.

## Actual Result
Blocks do not react to lava in any way. Lava behaves like a denser version of water with no fire properties.

## Reproduction Rate
100% — Always

## QA Notes
- Tested with multiple flammable block types in both Adventure and Creative modes
- Tested with trees and observed the same lack of reaction
- Ideally, lava should ignite blocks similar to how the flamethrower works — applying fire damage on contact, as it does with entities

## Evidence
<img width="2560" height="1440" alt="Hytale2026-02-09_16-20-15" src="https://github.com/user-attachments/assets/[YOUR-ASSET-ID-HERE]" />


---

**Reported by:** Krimm (`@Krimm_QA`)
