
```statblock
name: Sarbrindar
size: Medium
type: undead (warlock)
alignment: chaotic evil

ac: 12 (15 with mage armor)
hp: 37 (5d8 + 15)
speed: 30 ft.

stats:
  - 11
  - 14
  - 16
  - 12
  - 14
  - 16

saves:
  - Wis: 4

skillsaves:
  - Arcana: 3
  - Perception: 4

damage_resistances: Necrotic; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks
damage_immunities: Poison
condition_immunities: Exhaustion, Poisoned

senses: Darkvision 60 ft.
languages: the languages it knew in life

cr: 3
pb: 2

traits:
  - name: Sunlight Sensitivity
    desc: While in sunlight, Sarbrindar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

  - name: Unusual Nature
    desc: Sarbrindar doesn't require air, food, drink, or sleep.

actions:
  - name: Multiattack
    desc: Sarbrindar makes two **Life Drain** or **Grave Bolt** attacks.

  - name: Life Drain
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 6 (1d8 + 2) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A Humanoid slain by this attack rises 24 hours later as a zombie under Sarbrindar's control unless it is restored to life or its body is destroyed. Sarbrindar can have no more than twelve zombies under its control at one time."

  - name: Grave Bolt
    desc: "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target. *Hit:* 12 (2d8 + 3) necrotic damage."

  - name: Spellcasting
    desc: |
      Sarbrindar casts one of the following spells, using Charisma as its spellcasting ability (spell save **DC 13**).

      **At will:** *detect magic, disguise self, mage armor*

      **1/day each:** *fear, hold person, hallucinatory terrain*
```