![](https://c10.patreonusercontent.com/4/patreon-media/p/post/134957469/d8822becd1f54f7fbec91c896a6c05ee/eyJ3IjoxMDgwfQ%3D%3D/1.png?token-hash=jamo9IP7Vzg0obSP2mguUlQkfHkcsYQ8ehjpXmCQc5M%3D&token-time=1786665600)

# Description

Everyone loves a mystical weapon with strange powers beyond mortal comprehension, but using them always carries an inherent risk. Leave them “sheathed” in the wrong monster overnight, and you end up with a brain-twisting nightmare. This is why we clean our blades, people!

**_Bizarre Fusion._** Formed when an aberrant blade binds itself to a wyvern corpse, the draconic body becomes a puppet for the sentient distortion within it. The dark pool of energy at its centre bends the air around it, consuming any light that enters. Between the strange anatomy and the visual warping of reality, many adventurers get disoriented and die trying to sever a head that was really more of an accessory anyway.

**_Odd Armour._** Using the gravity well at the core of its body, a bicephal wyrmhole pulls in chips of minerals and metals, slowly replacing the rotting flesh of its host with a durable outer shell. The process, akin to a rapid fossilization, leaves a vaguely metallic and crystalline exterior, which shimmers in odd patterns under the bent light of the Aberration’s gravitational field.

**_Distortion Zone._** At a distance, a bicephal wyrmhole can be easily mistaken for a mirage or trick of the light, making them hard to discern, but there are several sure signs to indicate one’s presence in the area. Barely perceptible shifts in the colouration of nearby objects, making them appear blurry or oversaturated, can be used to confirm a bicephal wyrmhole is nearby. That, and the occasional stand of floating cabbages.

# Graviturgic Warp-hilt

*Wondrous Item, Uncommon (Socketable, Requires Attunement)*

**Component:** Pouch of Aberration (Bicephal Wyrmhole) Claws

> *"Running around from foe to foe, hunting them like prey, is such a waste of energy. Being a truly formidable opponent, one with gravitas, means bringing your enemies to you. Let them waste their strength running towards their own slaughter."*

This distorted, unnatural sword hilt can be socketed onto any magical melee weapon, adapting its bizarre geometry to the hilt or handle of its host.

## Properties

### Gravity Well
Once on each of your turns when you make an attack roll using the socketed weapon, you can attack a creature **5 feet farther** than your normal reach with the weapon. On a hit, the creature is pulled **5 feet directly toward you**.

### Consuming Force
As a **Bonus Action**, you can flourish the socketed weapon and create a minuscule black hole at a point you can see within **20 feet** of you.

Each creature within **15 feet** of that point must succeed on a **DC 13 Strength saving throw** or be pulled to the unoccupied space nearest the point.

When this property is used, roll **1d4**. On a **1**, the black hole consumes the magic of the socketed weapon; both the hilt and weapon lose their magical properties until the next dawn.

## Higher-Rarity Variants

### Rare Variant
- Increase the saving throw **DC to 15**.
- Creatures that fail their saving throw against **Consuming Force** are also **knocked Prone**.

### Very Rare Variant
- Increase the saving throw **DC to 16**.
- Increase the reach and pull distance of **Gravity Well** to **10 feet** each.
- Creatures that fail their saving throw against **Consuming Force** are also **knocked Prone**.
# Stat Block

```statblock
layout: Basic 5e Layout
image: 
name: Bicephal Wyrmhole
size: Large
type: aberration
subtype: 
alignment: chaotic evil
ac: 13
armor_class: 18 with Distortion Armour
hp: 76
hit_dice: 9d10 + 27
speed: 0 ft., fly 30 ft.
stats: [11, 17, 17, 13, 19, 11]
saves:
  - constitution: 6
  - wisdom: 7
skillsaves:
  - stealth: 6
damage_resistances: force, psychic
damage_immunities: radiant
condition_immunities: charmed, frightened, prone
senses: blindsight 60 ft., passive Perception 14
languages: Deep Speech; telepathy 60 ft.
cr: 7
traits:
  - name: Consume Chroma.
    desc: Whenever the bicephal wyrmhole is subjected to radiant damage, it regains hit points equal to the radiant damage dealt.
  - name: Distortion Armour.
    desc: The bicephal wyrmhole bends light around it in strange ways, making it difficult to track visually. While in bright light, the bicephal wyrmhole has three-quarters cover. A blinded creature, or one that closes its eyes or does not rely on sight, ignores this cover.
  - name: Gravity Well.
    desc: The area within 10 feet of the bicephal wyrmhole is difficult terrain for creatures other than bicephal wyrmholes.
actions:
  - name: Multiattack.
    desc: The bicephal wyrmhole makes one Stinger attack and one Warping Blade attack.
  - name: Stinger.
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 5 (1d4 + 3) piercing damage plus 18 (4d8) psychic damage. The target must succeed on a DC 15 Wisdom saving throw or become disoriented and immediately use its reaction to move a distance equal to its speed in a random direction."
  - name: Warping Blade.
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10 (2d6 + 3) force damage, and each creature of the bicephal wyrmhole’s choice within 5 feet of the target takes 4 (1d8) force damage."
bonus_actions:
  - name: Gravity Suspension (Recharge 5-6).
    desc: The bicephal wyrmhole disables gravity around it. Creatures and objects within 60 feet of it come under the effects of the levitate spell and rise 15 feet into the air if not tethered to the ground. At the start of the bicephal wyrmhole’s next turn, gravity rapidly intensifies, and creatures without a fly speed or that otherwise aren’t held aloft fall to the ground. Double the fall distance when calculating damage from falling in this way.
```
