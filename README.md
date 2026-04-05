# Hytale Early Access — Bug Reports & QA Documentation

Independent QA testing of Hytale during Early Access, focused on pre-release builds.  
Each report includes reproduction steps, expected vs actual behavior, severity assessment, and visual evidence.

## Focus Areas
- Physics & entity behavior
- Fire propagation & fluid interactions
- World interaction & edge cases
- UI & gameplay consistency

## Approach
Exploratory testing on new pre-release features, prioritizing what the development team needs validated rather than reporting known issues.  
Bugs are tested in vanilla environments to isolate mod interference.

## Reports

| # | Bug | Severity |
|---|-----|----------|
| 001 | [Necromancy has no summon cap; follow behavior breaks after ~30 minions](reports/001-necromancy-summon-cap/) | 🔴 Critical - ✅ Solved |
| 002 | [Darkwood Planks – Decorative drops Darkwood Fence](reports/002-Darkwood-Planks-Decorative-drops-Darkwood-Fence/) | 🟢 Low — ✅ Solved |
| 003 | [Railcarts do not move without a player on 45° slopes](reports/003-Railcarts-do-not-move-without-a-player-on-45°-slopes/) | 🟡 Medium |
| 004 | [Railcart remains floating after passing through a teleport](reports/004-Railcart-remains-floating-and-unresponsive-after-passing-through-a-teleport/) | 🟡 Medium |
| 005 | [Railcart has no physics when unoccupied](reports/005-railcart-has-no-physics-when-unoccupied-amd-remains-floating-in-mid-air/) | 🟡 Medium |
| 006 | [Doors close despite being blocked by an entity](reports/006-doors-close-despite-being-blocked-by-an-entity/) | 🟡 Medium |
| 007 | [Water passes through closed trapdoors](reports/007-water-passes-through-closed-trapdoors/) | 🟡 Medium |
| 008 | [Fire ignites blocks despite being in contact with water](reports/008-fire-ignites-blocks-despite-being-contact-with-water/) | 🔴 High |
| 009 | [Lava does not ignite adjacent flammable blocks](reports/009-lava-does-not-ignite-or-destroy-adjacent-flammable-blocks/) | 🟡 Medium |
| 010 | [Tar does not react to fire propagation](reports/010-tar-does-not-react-to-fire-propagation/) | 🟡 Medium |

**10 bugs documented** — some resolved by the development team ✅

---

Reported by: Krimm/Branhyan ([@Krimm_QA](https://x.com/Krimm_QA))
