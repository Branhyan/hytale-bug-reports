# Railcart has no physics when unoccupied and remains floating in mid-air

## Environment
- **Version:** pre-release/2026.01.29-301e13929
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
Medium — Gameplay / Physics / Entities

## Description
Railcarts appear to have no active physics when they are unoccupied.  
If a player dismounts from a railcart while it is in mid-air or not properly grounded, the railcart remains suspended in the air without reacting to gravity, collisions, or rail logic.

The railcart only reacts again when it is destroyed.  
This behavior affects general gameplay, automation systems, and interactions with other mechanics such as teleports.

## Steps to Reproduce
1. Place rails leading into a gap or elevated section
2. Place a railcart and mount it
3. Move into the elevated section
4. Dismount from the railcart while it is in mid-air
5. Observe the railcart state after dismounting

## Expected Result
An unoccupied railcart should react to gravity, collisions, or rail logic, falling or moving naturally according to physics.

## Actual Result
The railcart remains floating in mid-air with no physical reaction or movement.

## Reproduction Rate
100% — Always

## QA Notes
- This issue appears to be the root cause of other railcart-related bugs
- Possibly related to railcart behavior when passing through teleports
- Prevents automation and creative rail-based systems

## Evidence
https://x.com/Krimm_QA/status/2018565116057538730?s=20


---

**Reported by:** Krimm (`@Krimm_QA`)
