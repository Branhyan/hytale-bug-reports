# Picking up a filled Watering Can returns an Empty Watering Can

## Environment
- **Version:** pre-release/2026.02.26-89796e57b
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
🟡 Medium — Gameplay / Items / Quality of Life

## Description
When a Watering Can is filled with water and placed as a block, breaking it returns an Empty Watering Can instead of preserving its filled state. This undermines a quality-of-life feature intended to allow players to store pre-filled Watering Cans for later use.

## Steps to Reproduce
1. Fill a Watering Can with water
2. Place it in the world as a block using Crouch + Right Click
3. Observe that it appears as a filled Watering Can
4. Break the placed block
5. Check the returned item

## Expected Result
Picking up a filled Watering Can should return the same filled item that was placed in the world.

## Actual Result
Picking up the Watering Can returns an Empty Watering Can regardless of its filled state.

## Reproduction Rate
100% — Always

## QA Notes
- Fixing this issue would restore the intended quality-of-life feature of being able to store pre-filled Watering Cans for convenient use
- The Watering Can should have different drop behaviors depending on its state — one for Empty Watering Can and another for filled Watering Can. These distinct block states should not share the same drop table.

## Evidence
Before
<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/c020c041-f940-4ae4-9a89-371cbc8a1217" />
After
<img width="2554" height="1430" alt="image" src="https://github.com/user-attachments/assets/38ab5e6e-8882-4135-8974-7525a6984294" />


---

**Reported by:** Branhyan
