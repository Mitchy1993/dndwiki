```statblock
name: Plague-Changed Thralls
image: Plague Changed Thralls.jpg
size: Medium
type: Aberration
subtype: "Mega Minion"
alignment: chaotic evil (Can't speak)(1 hit = -1 hp)
ac: 12
hp: 2
hit_dice: 1d4
speed: 30 ft.
stats:
  - 13
  - 15
  - 10
  - 7
  - 10
  - 6
damage_vulnerabilities: ""
damage_resistances: "Fire"
damage_immunities: ""
condition_immunities: Burning
senses: darkvision 60 ft., passive Perception 10
languages: Common
cr: "1"
bestiary: true
actions:
  - name: Spellblast
    desc: "Spell Attack: +6 to hit, reach 10 ft., one creature. Hit: 9 (2d6 + 2) force damage. If target is size medium or smaller it must succeed on a DC 12 Strength saving throw or be pushed back 10 feet"
    attack_bonus: 2
    damage_dice: 2d6
    damage_bonus: 2
  - name: Claws
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (2d4 + 2) slashing damage. If the target is a creature other than a plague-changed, it must succeed on a DC 10 Dexterity saving throw or be burned for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
    attack_bonus: 4
  - name: Shortbow
    desc: "Ranged Weapon Attack: +6 to hit, ranged 5 ft., one creature. Hit: 5 (1d6 + 2) piercing damage."
    attack_bonus: 4
```

```statblock
name: Grunt(Grunthar)
image: Mountain Ogre.jpg
size: Large
type: Plaguechanged
subtype: "Mountain Ogre"
alignment: neutral evil (Dumb, 1-2 word sentences)
ac: 8
hp: 200
hit_dice: 36d10 + 2
speed: 30 ft.
stats:
  - 19
  - 6
  - 18
  - 3
  - 6
  - 5
saves:
  - wisdom: 0
damage_vulnerabilities: ""
damage_resistances: "Fire"
damage_immunities: poison
condition_immunities: poisoned, burning
senses: darkvision 60 ft., passive Perception 8
languages: understands Common and Giant but can't speak
cr: "2"
bestiary: true
traits:
  - name: Terrifying Roar
    desc: Grunthar can unleash a bone-chilling roar that instills fear in all enemies within a 30-fot radius. Each creature that can hear Grunthar must make a Wisdom saving throw (DC 15) or become frightened for 10 turns. They can repeat the saving throw at the end of each of their turns to end the effect.
    attack_bonus: 0
actions:
  - name: Devastating Slam
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 22 (4d8 + 4) bludgeoning damage. On hit the target must suceed on a Strength saving throw or be knocked prone"
    attack_bonus: 6
    damage_dice: 4d8
    damage_bonus: 4
    
```

```statblock
name: Thrak
image: Nothic.jpg
size: Tiny
type: Plaguechanged
subtype: "Nothic"
alignment: chaotic evil (Speaks in abrupt screechy/breathy rhythem. Refers to self as we)
ac: 18
hp: 78
hit_dice: 13d10 + 7
speed: 45 ft.
stats:
  - 1
  - 28
  - 10
  - 13
  - 14
  - 11
damage_vulnerabilities: ""
damage_resistances: 
damage_immunities: 
condition_immunities: Grappled, Burning
senses: darkvision 120 ft., passive Perception 12
languages: Common, abyssal
cr: "2"
bestiary: true
traits:
  - name: Corrupting Gaze
    desc: (Can make one attempt on each target per battle) Thrak can fix his gaze upon a creature within 30 feet. The target must succed on a Wisdom saving throw or suffer hallucinations. (Disadvantage on next attack)
    attack_bonus: 0
  - name: Ephemeral
    desc: Thrak can't wear or carry anything.
    attack_bonus: 0
  - name: Incorporeal Movement
    desc: Thrak can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.
    attack_bonus: 0
actions:
  - name: Ephemeral Claws
    desc: "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 9 (3d8) lightning damage."
    attack_bonus: 4
    damage_dice: 3d8

```


```statblock
name: Eldrin
image: Eldrin.jpg
size: Medium
type: Plaguechanged
subtype: Gnome
alignment: Lawful evil
ac: 12
hp: 41
hit_dice: 27d10 + 2
speed: 30 ft.
stats:
  - 10
  - 14
  - 12
  - 16
  - 12
  - 18
saves:
  - charisma: 8
  - intelligence: 7
skillsaves:
  - arcana: 7
  - investigation: 7
  - perception: 3
damage_vulnerabilities: ""
damage_resistances: "Fire"
damage_immunities: ""
condition_immunities: "Burning"
senses: passive Perception 13
languages: common, elvish
cr: "3"
bestiary: true
traits: []
actions:
  - name: Open Portal
    desc: "A portal opens back to and from the Plague Wrought Lands."
  - name: Dagger 
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5ft. or range 20/60 ft., one target. Hit: 4(1d4 + 2) piercing damage."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 2
  - name: Karsite Grasp
    desc: "Eldrin can channel the Karsite Weave into another creature by touching them thereby devouring their connection to Mystra's Weave, DC 30"
spells:
  - "The mage is a 10th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 16, +8 to hit with spell attacks). The mage has the following wizard spells prepared:"
  - Cantrips (at will): fire bolt, mage hand, ray of frost
  - 1st level (2 slots): ray of sickness, shield
  - 2nd level (2 slots): misty step, blindness/deafness
  - 3rd level (2 slots): fireball, lightning bolt, counterspell, Spellplague
  - 4th level (2 slots): dimension door, ice storm
  - 5rd level (2 slots): teleportation circle, cone of cold
  - Spellplague: A 20-foot-radius sphere of blue flame appears, centered on a point within range and lasting for 10 turns (Concentration). Any creature that starts its turn in the area takes 2d6 fire damage. Any creature that ends its turn in the area must succeed on a Dexterity saving throw or take 1d6 and begin burning
legendary_description: Legendary Resistance 1/day
reactions:
  - name: Counterspell
    desc: "If the creature is casting a spell of 3rd level or lower, its spell fails and has no effect. If it is casting a spell of 4th level or higher, make an ability check using your spellcasting ability. The DC equals 10 + the spell's level. On a success, the creature's spell fails and has no effect. At Higher Levels: When you cast this spell using a spell slot of 4th level or higher, the interrupted spell has no effect if its level is less than or equal to the level of the spell slot you used."
```


```statblock
name: Arandur
image: Arandur.jpg
size: Medium
type: Plaguechanged
subtype: Human
alignment: Lawful Evil
ac: 18(20 w/Shield of Faith)
hp: 150
hit_dice: 27d10 + 2
speed: 30 ft.
stats:
  - 14
  - 10
  - 12
  - 18
  - 18
  - 16
saves:
  - charisma: 6
  - wisdom: 7
skillsaves:
  - medicine: 6
  - religion: 4
damage_vulnerabilities: ""
damage_resistances: "Fire"
damage_immunities: ""
condition_immunities: "Burning"
senses: passive Perception 14
languages: Common
cr: "3"
bestiary: true
traits: []
actions:
  - name: Channel Divinity
    desc: "1 Charge/Short rest"
  - name: Channel Divinity - Unravel Weave
    desc: "As an action, Arandur can attempt to consume the Weave in a localized area, causing magical disturbances and unraveling the fabric of reality. All of Mystra's Weave within 350 ft is consumed incapacitating creatures, unless they can sustain themselves on the Karsite Weave. Spellcaster's must make a DC 20, of their spellcasting ability, saving throw or permanently lose their connection to Mystra's Weave. Additionally, any concentration spells active within the area of effect that do not rely on the Karsite Weave have a chance to be immediately dispelled, with the caster needing to make a Constitution saving throw against a DC equal to 10, to maintain concentration"
  - name: Channel Divinity - Weave of Shadows
    desc: "Arandur calls upon the shadows to cloak himself and his allies, granting them advantage on Dexterity (Stealth) checks for 1 minute. Additionally, any enemy within 10 feet of Arandur or his allies that targets them with an attack or a harmful spell must succeed on a Wisdom saving throw against Arandur's spell save DC or have disadvantage on the attack roll or spell attack roll."
  - name: Mace
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) bludgeoning damage."
  - name: Karsite Grasp
    desc: "Arandur can channel the Karsite Weave into another creature by touching them"
reactions:
  - name: Tactical Insight
    desc: "Arandur can use his reaction to grant one ally within range tactical insight, allowing them to add his wisdom modifier to their next attack roll, ability check, or saving throw."
legendary_description: Legendary Resistance 1/day
spells:
  - "Arandur is a 10th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 15, +7 to hit with spell attacks). The caster has the following wizard & cleric spells prepared:"
  - Cantrips (at will): Fire bolt, Thaumaturgy 
  - 1st level (4 slots): Shield, Shield of Faith, Bless, Cure Wounds
  - 2nd level (3 slots): Blur, Hold Person
  - 3rd level (3 slots): Counterspell, Haste
  - 4th level (3 slots): Death Ward
  - 5th level (2 slot): Mass Cure Wounds

```



```statblock
name: Twig Blight
size: small
type: plant
subtype: ""
alignment: neutral evil
ac: 13 (natural armor)
hp: 4
hit_dice: 1d6 + 1
speed: 20 ft.
stats:
  - 6
  - 13
  - 12
  - 4
  - 8
  - 3
damage_vulnerabilities: "fire"
damage_resistances: 
damage_immunities: 
condition_immunities: blinded, deafened
senses: blindsight 60 ft. (blind beyond this radius), passive perception 9
languages: Undertands common but can't speak
cr: "1/8"
bestiary: true
traits:
  - name: False Appearance
    desc: While the blight remains motionless, it is indistinguishable from a dead shrub
    attack_bonus: 0
actions:
  - name: Claws
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4 + 1) bludgeoning damage."
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
```

```statblock
name: Vine Blight
size: small
type: plant
subtype: ""
alignment: neutral evil
ac: 12 (natural armor)
hp: 26
hit_dice: 4d8 + 4
speed: 10 ft.
stats:
  - 15
  - 8
  - 14
  - 5
  - 10
  - 3
damage_vulnerabilities: "fire"
damage_resistances: 
damage_immunities: 
condition_immunities: blinded, deafened
senses: blindsight 60 ft. (blind beyond this radius), passive perception 10
languages: Undertands common but can't speak
cr: "1/2"
bestiary: true
traits:
  - name: False Appearance
    desc: While the blight remains motionless, it is indistinguishable from a dead shrub
    attack_bonus: 0
actions:
  - name: Constrict
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6 + 2) bludgeoning damage."
    attack_bonus: 4
    damage_dice: 2d6
    damage_bonus: 2
  - name: Entangling Plants (Recharge 5)
    desc: "Grasping roots and vines sprout in a 15-foot radius centered on the blight, withering away after 1 minute. For the duration, that area is difficult terrain for nonplant creatures. In addition, each creature of the blight's choice in that area when the plants appear must succeed on a DC: 12 Strength saving throw or become restrained. A creature can use its action to make a DC: 12 Strength check, freeing it self or another entangled creature within reach on a success."
```


```statblock
name: Shambling Mound
size: Large
type: plant
subtype: ""
alignment: unaligned
ac: 15 (natural armor)
hp: 60
hit_dice: 11d10 + 5
speed: 20 ft., swim 20 ft.
stats:
  - 18
  - 8
  - 16
  - 5
  - 10
  - 5
damage_vulnerabilities: "fire"
damage_resistances: 
damage_immunities: 
condition_immunities: blinded, deafened
senses: blindsight 60 ft. (blind beyond this radius), passive perception 10
languages: Undertands common but can't speak
cr: "1/2"
bestiary: true
traits:
  - name: False Appearance
    desc: While the blight remains motionless, it is indistinguishable from a dead shrub
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The shambling mound makes two slam attacks. If both atttacks hit a medium or smaller target, the target is grappled (escape DC 14), and the shambling mound uses its Engulf on it."
  - name: Slam
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) bludgeoning damage."
    attack_bonus: 7
    damage_dice: 2d8
    damage_bonus: 4
  - name: Engulf
    desc: "The shambling mound engulfs a medium or smaller creature grappled by it. The engulfed target is blinded, resstratined, and unable to breathe, and it must suceed on a DC 14 Con saving throw at the start of each of the mound's turns or take 13"
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
```

```statblock
name: Ice Climber
image: Ice Climber.jpg
size: Medium
type: monstrosity
subtype: shapechanger
alignment: unaligned
ac: 18
hp: 70
hit_dice: 13d12 + 16
speed: 30 ft.
stats:
  - 11
  - 18
  - 14
  - 11
  - 12
  - 14
skillsaves:
  - deception: 6
  - insight: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: charmed
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 11
languages: Common
cr: "3"
bestiary: true
traits:
  - name: Shapechanger
    desc: The doppelganger can use its action to polymorph into a Small or Medium humanoid it has seen, or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
    attack_bonus: 0
  - name: Ambusher
    desc: The doppelganger has advantage on attack rolls against any creature it has surprised.
    attack_bonus: 0
  - name: Surprise Attack
    desc: If the doppelganger surprises a creature and hits it with an attack during the first round of combat, the target takes an extra 10 (3d6) damage from the attack.
    attack_bonus: 0
    damage_dice: 3d6
  - name: Belay
    desc: If Popo and Nana start their turn within 10 feet of each other they can toss a rope and propel the other at an enemy within 20 feet or use other means to attack with advantage
actions:
  - name: Multiattack
    desc: The doppelganger makes two pickaxe attacks.
    attack_bonus: 0
  - name: Pickaxe
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (2d6 + 4) bludgeoning damage."
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 4
  - name: Axe Spin
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11 (3d6) piercing damage. Popo and Nana use Slam attack on everyone in reach"
  - name: Ray of Frost
    desc: "Ranged Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 11 (3d6) cold damage. A frigid beam of blue-white light streaks toward a creature within range and its speed is reduced by 10 feet until the start of your next turn."
  - name: Decanter of Endless Water
    desc: "Verbal activation. Hit: 11 (1d8) bludgeoning damage. 'Geyser' produces 30 gallons of water that gushes forth in a geyser 30 feet long and 1 foot wide. As a bonus action aim the geyser at a creature you can see within 30 feet of you. The target must succeed on a DC 13 Strength saving throw or take 1d8 bludgeoning damage and fall prone. Target an object that isn't being worn or carried and that weighs no more than 200 pounds. The object is either knocked over or pushed up to 15 feet away from you."
  - name: Read Thoughts
    desc: The doppelganger magically reads the surface thoughts of one creature within 60 ft. of it. The effect can penetrate barriers, but 3 ft. of wood or dirt, 2 ft. of stone, 2 inches of metal, or a thin sheet of lead blocks it. While the target is in range, the doppelganger can continue reading its thoughts, as long as the doppelganger's concentration isn't broken (as if concentrating on a spell). While reading the target's mind, the doppelganger has advantage on Wisdom (Insight) and Charisma (Deception, Intimidation, and Persuasion) checks against the target.
```

```statblock
name: Giant Rat
size: Small
type: beast
subtype: ""
alignment: unaligned
ac: 12
hp: 7
hit_dice: 1d2 + 0
speed: 30 ft.
stats:
  - 7
  - 15
  - 11
  - 2
  - 10
  - 4
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 10
languages: ""
cr: 1/8
bestiary: true
traits:
  - name: Keen Smell
    desc: The rat has advantage on Wisdom (Perception) checks that rely on smell.
    attack_bonus: 0
  - name: Pack Tactics
    desc: The rat has advantage on an attack roll against a creature if at least one of the rat's allies is within 5 ft. of the creature and the ally isn't incapacitated.
  - name: Skittish
    desc: When recieving damage the swarm must succeed on a Consitution saving throw DC 15 or scatter and flee
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4 + 2) piercing damage."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 2
```

```statblock
name: Swarm of Rats
size: Medium swarm of tiny beasts
type: beast
subtype: rodent
alignment: unaligned
ac: 10
hp: 20
hit_dice: 2d12 + 7
speed: 30 ft.
stats:
  - 9
  - 11
  - 9
  - 2
  - 10
  - 3
skillsaves:
damage_vulnerabilities: ""
damage_resistances: "poison"
damage_immunities: ""
condition_immunities: "Charmed, Frightened, Grappled, paralyzed, Petrified, Poisoned Prone, Restrained, Stunned"
senses: darkvision 30 ft., passive Perception 10
languages: 
cr: 1/4
bestiary: true
traits:
  - name: Keen Smell
    desc: The swarm has advantage on WIsdom (perception) checks that rely on smell.
  - name: Swarm
    desc: The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny rat. the swarm can't regain hit points or gain temporary hit points.
  - name: Skittish
    desc: When recieving damage the swarm must succeed on a Consitution saving throw DC 15 or scatter and flee
actions:
  - name: Bites (swarm has more than half HP)
    desc: "Melee Weapon Attack: +2 to hit, reach 0 ft., one target in the swarms space. Hit: 13 (3d6 + 3) piercing damage."
    attack_bonus: 2
    damage_dice: 3d6
    damage_bonus: 0
  - name: Bites (swarm has half HP or less)
    desc: "Melee Weapon Attack: +2 to hit, reach 0ft., one target in the swarm's space. Hit: 10 (2d6 + 3) piercing damage."
    attack_bonus: 2
    damage_dice: 2d6
    damage_bonus: 0
```

```statblock
name: Rat King
size: Large monstrosity
type: beast
subtype: rodent
alignment: chaotic evil
ac: 12
hp: 76
hit_dice: 9d10 + 27
speed: 30 ft., burrow 20ft.
stats:
  - 6
  - 16
  - 18
  - 11
  - 15
  - 16
skillsaves:
  - stealth: 6
saves:
  - constitution: 5
damage_vulnerabilities: ""
damage_resistances: acid, poison
damage_immunities: ""
condition_immunities: Charmed, Frightened, Paralyzed, Petrified, poisoned, Prone, Stunned
senses: darkvision 90 ft., passive Perception 10
languages: Common, Theives' Cant
cr: 5
bestiary: true
traits:
  - name: Keen Smell
    desc: The swarm has advantage on WIsdom (perception) checks that rely on smell.  ​
actions:
  - name: Multiattack
    desc: "- The rat king makes two Bite attacks."
  - name: Bite
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target Hit: 10 (4d6 + 3) piercing damage."
    attack_bonus: 6
    damage_dice: 4d6
    damage_bonus: 3
  - name: Call Rats/1day
    desc: "- The rat king magically calls 2d4 rats, 1d4 giant rats, or 1 swarm of rats. The rates arrive in 1d4 rounds, acting as allies of the rat king and obeying its spoken commands. The rats remain for 1 hour, until the rat king dies, or until the rat king dismisses them as a bonus action."
reactions:
  - name: Absorbtion
    desc: When a friendly rat, giant rat, or swarm starts it's turns within 5 feet of the rat king, he can absorb it. The target dies, and the rat king gains temp hp equal to the target's remaining hp
```

```statblock
name: Forest Hag
size: Medium
type: fey
subtype: ""
alignment: chaotic evil
ac: 14
hp: 52
hit_dice: 7d8 + 20
speed: 30 ft., swim 40 ft.
stats:
  - 16
  - 13
  - 16
  - 12
  - 12
  - 13
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 11
languages: Aquan, Common, Giant
cr: "2"
bestiary: true
traits:
  - name: Amphibious
    desc: The hag can breathe air and water.
    attack_bonus: 0
  - name: Horrific Appearance
    desc: |-
      Any humanoid that starts its turn within 30 feet of the hag and can see the hag's true form must make a DC 11 Wisdom saving throw. On a failed save, the creature is frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, with disadvantage if the hag is within line of sight, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the hag's Horrific Appearance for the next 24 hours.
      Unless the target is surprised or the revelation of the hag's true form is sudden, the target can avert its eyes and avoid making the initial saving throw. Until the start of its next turn, a creature that averts its eyes has disadvantage on attack rolls against the hag.
    attack_bonus: 0

actions:
  - name: Claws
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6 + 3) slashing damage."
    attack_bonus: 5
    damage_dice: 2d6
    damage_bonus: 3
  - name: Death Glare
    desc: The hag targets one frightened creature she can see within 30 ft. of her. If the target can see the hag, it must succeed on a DC 11 Wisdom saving throw against this magic or drop to 0 hit points.
    attack_bonus: 0
  - name: Illusory Appearance
    desc: |-
      The hag covers herself and anything she is wearing or carrying with a magical illusion that makes her look like an ugly creature of her general size and humanoid shape. The effect ends if the hag takes a bonus action to end it or if she dies.
      The changes wrought by this effect fail to hold up to physical inspection. For example, the hag could appear to have no claws, but someone touching her hand might feel the claws. Otherwise, a creature must take an action to visually inspect the illusion and succeed on a DC 16 Intelligence (Investigation) check to discern that the hag is disguised.
    attack_bonus: 0
```