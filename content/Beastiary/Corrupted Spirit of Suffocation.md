
```statblock
name: Corrupted Spirit of Suffocation
size: Medium
type: undead
alignment: chaotic evil

ac: 15 (Angry Defiance)
hp: 54 (12d8)
speed: 0 ft., fly 60 ft.

stats:
  - 7
  - 13
  - 11
  - 10
  - 10
  - 19

saves:
  - Wis: 2
  - Cha: 6

damage_resistances: Lightning, Thunder, Fire, Acid; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks
damage_immunities: Poison, Cold, Necrotic
condition_immunities: Charmed, Exhaustion, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained

senses: Darkvision 60 ft.
languages: the languages it knew in life

cr: 4
pb: 2

traits:
  - name: Angry Defiance
    desc: The corrupted spirit adds its Charisma modifier to its AC (included above).

  - name: Incorporeal Movement
    desc: The corrupted spirit can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.

  - name: Undead Nature
    desc: The corrupted spirit doesn't require air, food, drink, or sleep.

actions:
  - name: Essence of Rage
    desc: "*Melee or Ranged Spell Attack:* +6 to hit, reach 5 ft. or range 30 ft., one creature. *Hit:* 22 (4d8 + 4) psychic damage, and the target must succeed on a DC 14 Charisma saving throw or be enraged until the end of its next turn. While enraged, the target has advantage on melee attack rolls and must move to and attack the nearest creature other than the spirit. In addition, attack rolls against the enraged target have advantage."

  - name: Asphyxiation (1/Day)
    desc: The corrupted spirit targets one creature it can see within 30 feet that needs to breathe. The target must make a DC 14 Constitution saving throw, taking 28 (8d6) bludgeoning damage on a failed save, or half as much on a successful one. A target that fails the saving throw experiences the effects of suffocation until the spirit dies or until the effect is ended by **remove curse** or **dispel magic** (DC 13).
```