# Railcarts do not move without a player on 45° slopes

## Environment
- **Version:** pre-release/2026.01.29-301e13929
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
Medium — Gameplay / Transport / Physics

## Description
Railcarts never move unless a player is riding them.  
This prevents their use for automation or creative systems and contradicts expected world logic, where gravity should cause movement on slopes.

## Steps to Reproduce
1. Place rails on a downward staircase (45° slope)
2. Place a railcart on the rails
3. Attempt to push it in any way
4. Observe that it does not move

## Expected Result
Railcarts should move downhill when placed on a 45° slope, even without a player.

## Actual Result
Railcarts remain completely static as long as no player is riding them.

## Reproduction Rate
100% — Always

## QA Notes
- Railcarts do not move even when pushed
- When a player rides the railcart, it behaves as expected
- The railcart appears to have no collision when unoccupied

## Evidence
<img width="2560" height="1440" alt="Hytale2026-02-02_18-37-46" src="https://github.com/user-attachments/assets/4fd0b24c-3b94-4cb4-828c-aa1b72b98d2f" />


---

**Reported by:** Krimm (`@Krimm_QA`)
