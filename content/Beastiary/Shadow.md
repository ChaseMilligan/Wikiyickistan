
```statblock
name: Shadow
size: Medium
type: undead
alignment: chaotic evil

ac: 12
hp: 27 (5d8 + 5)
speed: 40 ft.

stats:
  - 6
  - 14
  - 13
  - 6
  - 10
  - 8

skillsaves:
  - Stealth: 6

damage_vulnerabilities: Radiant
damage_resistances: Lightning, Thunder, Cold, Fire, Acid
damage_immunities: Poison, Necrotic
condition_immunities: Exhaustion, Frightened, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained, Unconscious

senses: Darkvision 60 ft.
languages: —

cr: 1/2
pb: 2

traits:
  - name: Amorphous
    desc: The shadow can move through a space as narrow as 1 inch without expending extra movement to do so.

  - name: Sunlight Weakness
    desc: While in sunlight, the shadow has disadvantage on d20 Tests.

actions:
  - name: Draining Swipe
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) necrotic damage, and the target's Strength score decreases by 1d4. The target dies if this reduces that score to 0. If a Humanoid is slain by this attack, a Shadow rises from the corpse 1d4 hours later."

bonus_actions:
  - name: Shadow Stealth
    desc: While in dim light or darkness, the shadow takes the Hide action.
```