
```statblock
name: Ghast
size: Medium
type: undead
alignment: chaotic evil

ac: 13
hp: 36 (8d8)
speed: 30 ft.

stats:
  - 16
  - 17
  - 10
  - 11
  - 10
  - 8

saves:
  - Wis: 2

damage_resistances: Necrotic
damage_immunities: Poison
condition_immunities: Charmed, Exhaustion, Poisoned

senses: Darkvision 60 ft.
languages: Common

cr: 2
pb: 2

traits:
  - name: Stench
    desc: Any creature that starts its turn within 5 feet of the ghast must succeed on a DC 10 Constitution saving throw or be **Poisoned** until the start of its next turn. On a successful save, the creature is immune to this ghast's Stench for 24 hours.

actions:
  - name: Bite
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 9 (2d8) necrotic damage."

  - name: Claw
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage. If the target is a non-Undead creature, it must succeed on a DC 10 Constitution saving throw or be **Paralyzed** until the end of its next turn."
```