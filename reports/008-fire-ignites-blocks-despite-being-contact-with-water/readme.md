# Fire ignites blocks despite being in contact with water

## Environment
- **Version:** pre-release/2026.02.06-0baf7c5aa
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
High — Fire Propagation / Fluids / World Interaction

## Description
When using the flamethrower on blocks that are in contact with water, the blocks still ignite despite being submerged. In some cases, the fire also spreads to adjacent blocks.

## Steps to Reproduce
1. Create a platform that can hold water  
2. Fill the entire platform with water  
3. Use the flamethrower on the blocks  
4. Observe the result  

## Expected Result
Blocks that are in contact with water should not be able to ignite.

## Actual Result
Fire ignites and propagates despite the blocks being underwater.

## Reproduction Rate
Always

## QA Notes
- Tested with multiple flammable block types  
- Reproduced in both Creative and Adventure modes  
- Blocks may require a state such as “in contact with water” to prevent fire interaction  

## Evidence
<img width="2560" height="1440" alt="Hytale2026-02-09_15-57-57" src="https://github.com/user-attachments/assets/3e82cdcd-8de0-4b00-b956-29f0a913b6af" />
<img width="2560" height="1440" alt="Hytale2026-02-09_15-58-14" src="https://github.com/user-attachments/assets/3a1e7733-fefd-4c43-91ce-7f5cfe45d322" />


---

**Reported by:** Krimm (`@Krimm_QA`) / Branhyan
