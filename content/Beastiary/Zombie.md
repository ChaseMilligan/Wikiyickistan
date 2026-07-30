
```statblock
name: Zombie
size: Medium
type: undead
alignment: neutral evil

ac: 8
hp: 15 (2d8 + 6)
speed: 20 ft.

stats:
  - 13
  - 6
  - 16
  - 3
  - 6
  - 5

saves:
  - Wis: 0

damage_immunities: Poison
condition_immunities: Exhaustion, Poisoned

senses: Darkvision 60 ft.
languages: Understands Common plus one other language but can't speak

cr: 1/4
pb: 2

traits:
  - name: Undead Fortitude
    desc: If damage reduces the zombie to 0 hit points, it makes a Constitution saving throw (DC 5 + the damage taken), unless the damage is radiant or from a critical hit. On a successful save, the zombie drops to 1 hit point instead.

actions:
  - name: Slam
    desc: "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) bludgeoning damage."
```