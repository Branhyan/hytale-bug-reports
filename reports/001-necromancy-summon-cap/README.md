# [Pre-Release U2] Necromancy has no summon cap; follow behavior breaks after ~30 minions

**Version:** pre-release/2026.01.22-a60fdd027  
**Severity:** Critical / Exploit / AI  
**Date Reported:** 22/01/2026

## Steps to Reproduce
1. Obtain Necromancy Grimoire
2. Summon skeletons repeatedly using multiple bone piles
3. Reach approximately 30 active minions
4. Summon additional minions

## Expected Result
- Maximum of 5 active minions enforced
- All active minions follow the summoner correctly

## Actual Result
- No summon limit enforced
- Up to ~30 minions follow correctly
- Additional minions spawn but do not follow the summoner

## Notes
- Suggests an internal follower limit (~30) not aligned with summon logic
- Causes uncontrolled entities in the world
- Potential performance and gameplay issues

## Screenshots/Video
<img width="2560" height="1440" alt="Hytale2026-01-22_13-34-41" src="https://github.com/user-attachments/assets/b5cf0686-90d7-446f-8cc7-f948ab99ce2f" />


---
**Reported by:** Krimm/Branhyan
