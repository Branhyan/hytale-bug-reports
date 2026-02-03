# Doors close despite being blocked by an entity

## Environment
- **Version:** pre-release/2026.01.29-301e13929
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
Medium — Gameplay / World Interaction

## Description
All door types currently close even when an entity or player is blocking them.  
According to the pre-release patch notes, this behavior should no longer occur.

Patch notes state:  
"Doors no longer close when blocked by entities or players."

## Steps to Reproduce
1. Place a door
2. Place an entity or a player in the door's closing path
3. Attempt to close the door
4. Observe the result

## Expected Result
Doors should remain open when blocked by an entity or player, as stated in the patch notes.

## Actual Result
Doors close while phasing through the blocking entity.  
If the blocking entity is a player, the door pushes the player back by one block.

## Reproduction Rate
100% — Always

## QA Notes
- All door types and sizes were tested
- Test dummies react to collision but still do not block the door from closing

## Evidence
Open
<img width="2560" height="1440" alt="Hytale2026-02-03_11-19-57" src="https://github.com/user-attachments/assets/8dd608ce-3bbd-4dde-ae6c-f4d09e814e78" />
Close
<img width="2560" height="1440" alt="Hytale2026-02-03_11-22-26" src="https://github.com/user-attachments/assets/d18be448-1252-40d8-ba4c-7532d94cf9f8" />
---

**Reported by:** Krimm (`@Krimm_QA`)
