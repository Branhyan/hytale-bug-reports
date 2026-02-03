# Railcart remains floating and unresponsive after passing through a teleport

## Environment
- **Version:** pre-release/YYYY.MM.DD-hash
- **Mode:** All modes
- **Platform:** Windows 11

## Severity
Medium — Gameplay / Entities / Portals

## Description
When passing through a teleport while riding a railcart, the player is teleported correctly, but the railcart remains suspended in mid-air and becomes unresponsive.

After this occurs, the railcart no longer reacts to physics, gravity, or interaction. The only possible interaction is damaging it until it is destroyed.

## Steps to Reproduce
1. Place rails leading into a teleport portal
2. Place a railcart on the rails and mount it
3. Move forward into the portal
4. Observe the railcart state after teleportation

## Expected Result
Both the player and the railcart should be teleported together, maintaining correct physics and interaction behavior.

## Actual Result
The player is teleported, but the railcart remains floating in mid-air with no physical reaction.

## Reproduction Rate
100% — Always

## QA Notes
- A general railcart issue was identified where the cart remains floating in the air when the player dismounts
- This behavior appears related and will be reported separately

## Evidence
<img width="2560" height="1440" alt="Hytale2026-02-02_18-34-17" src="https://github.com/user-attachments/assets/6ebcabd9-6ad0-4f8c-9877-36532d4f2733" />


---

**Reported by:** Krimm (`@Krimm_QA`)
