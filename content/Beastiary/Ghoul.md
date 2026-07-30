
```statblock
name: Ghoul
size: Medium
type: undead
alignment: chaotic evil

ac: 12
hp: 22 (5d8)
speed: 30 ft.

stats:
  - 13
  - 15
  - 10
  - 7
  - 10
  - 6

damage_immunities: Poison
condition_immunities: Charmed, Exhaustion, Poisoned

senses: Darkvision 60 ft.
languages: Common

cr: 1
pb: 2

actions:
  - name: Multiattack
    desc: The ghoul makes two **Bite** attacks.

  - name: Bite
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 3 (1d6) necrotic damage."

  - name: Claw
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage. If the target is a creature that isn't an Undead or an elf, it must succeed on a DC 10 Constitution saving throw or be **Paralyzed** until the end of its next turn."
```