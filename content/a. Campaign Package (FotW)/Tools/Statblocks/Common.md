```statblock
name: Turak
image: Turak.png
size: Medium
type: humanoid
subtype: half-orc
alignment: unaligned
ac: 16
hp: 55
hit_dice: 10d10
speed: 30 ft.
stats:
  - 18
  - 16
  - 15
  - 10
  - 10
  - 10
skillsaves:
  - deception: 6
  - insight: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: 
condition_immunities: ""
senses: passive Perception 11
languages: Common
cr: "3"
bestiary: true
traits:
  - name: Grappling Strike
    desc: After hitting a creature try to grapple the target as a bonus action, add SD to athletics
  - name: Parry
    desc: Use reaction to reduce damage by one SD + DEX
  - name: Trip Attack
    desc: Add SD to DMG and enemy must succeed DC 16 STR or proned
  - name: Unarmed Fighting Style
    desc: Unarmed Strikes deal 1d6 + STR. 1d8 + STR if no weapons or shield wielded
actions:
  - name: Unarmed Strike
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d8 + 4) bludgeoning damage."
  - name: Greataxe
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d12 + 4) bludgeoning damage."
```

```statblock
name: Brigham Alikir
image: Brigham Alikir.jpg
size: Medium
type: humanoid
subtype: Mark of Shadow Elf
alignment: Chaotic Evil
ac: 14
hp: 42
hit_dice: 7d10 + 4
speed: 30 ft.
stats:
  - 11
  - 14
  - 14
  - 12
  - 16
  - 11
saves:
  - wisdom: 6
  - intelligence: 4
skillsaves:
  - Arcana: 4
  - history: 4
  - nature: 4
  - perception: 6
  - intimidation: 3
  - stealth: +d4
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 10
languages: common, elvish
cr: "2"
bestiary: true
traits:
  - name: Shadow Shape 2/rest
    desc: BA expend a shadow shape to become a shadow. Shadow Swipes impose DC 15 WIS throw, enemy loses 1 STR on failure. Heal for half damage dealt with melee
  - name: War Caster
    desc: ADV on concentration saves; cast spell as opportunity attack
  - name: Shadow Master
    desc: Can cast invisibility 1/day for free
actions:
  - name: Shadow Swipes
    desc: "Melee Attack: +7 to hit, reach 5 ft., one target. Hit: 4 (2d6 + 2) necrotic damage."
  - name: Quarterstaff
    desc: "Melee Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6) bludgeoning damage."
  - name: Shillelagh/1 min
    desc: "BA to activate. Melee Attack: +6 to hit, reach 5 ft., one target. Hit: 4 (1d8 + 3) bludgeoning "
  - name: Defile Ground 1/rest
    desc: BA to activate. Patch of land or water in 10 ft radius within 60ft is corrupted for 1 min. Difficult terrain for enemies. Creature in area that takes damage for the first time, per turn, takes extra 1d4 necrotic. Can move as bonus action
spells:
  - "The mage is a 6th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 14, +6 to hit with spell attacks). The caster has the following artifcier spells prepared:"
  - Cantrips (at will): poison spray, shillelagh, minor illusion
  - 1st level (4 slots): earth tremor
  - 2nd level (3 slots): darkness, invisibility, locate object, shadow blade
  - 3rd level (3 slots): bestow curse, conjure animals, fear, revivify, tidal wave, wall of water
reactions:
  - name: Call Shadowseeds (PROF/day)
    desc: When a non-undead or construct takes damage in defiled ground, summon a Shadow Sapling that obeys your commands
```

```statblock
name: Asura Swiftfoot
image: Asura Swiftfoot.jpg
size: Medium
type: humanoid
subtype: Kitsune
alignment: Chaotic Neutral
ac: 17
hp: 33
hit_dice: 6d10
speed: 40 ft.
stats:
  - 10
  - 14
  - 10
  - 18
  - 10
  - 16
saves:
  - dexterity: 5
  - constitution: 3
  - intelligence: 7
skillsaves:
  - deception: 6
  - acrobatics: 5
  - sleight of hand: 5
  - stealth: 5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 10
languages: any four languages
cr: "2"
bestiary: true
traits:
  - name: Infusions (3)
    desc: Spell slot ring (Timothy), Repulsion Shield (Asura), Homunculus Servant (Grim)
  - name: Elixirs (2)
    desc: Heal (2d4 + 4), Swiftness (MS + 10ft/1hr), Resilience (+1 AC), Flight (Fly speed = 10ft/10 mins), Boldness (add d4 to every atk roll or save/1 min), Transformation (Alter self/10 mins)
  - name: Stored Elixirs
    desc: Heal & Swiftness
  - name: Bomb (1/day)
    desc: Creatures within 5 feet of impact must succeed a DC12 DEX or take 3d6
actions:
  - name: Fire Sling
    desc: "Ranged Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d6 + 2) fire damage."
  - name: Make or Use Elixir
    desc: Consume or feed pre-made elixir. Can create one in empty flask for lvl 1 spell slot or higher
spells:
  - "The mage is a 6th-level half-caster. Its spellcasting ability is Intelligence (spell save DC 15, +7 to hit with spell attacks). The caster has the following artifcier spells prepared:"
  - Cantrips (at will): magic stone, spare the dying
  - 1st level (4 slots): catapult, healing word, ray of sickness
  - 2nd level (3 slots): flaming sphere, melf's acid arrow
reactions:
  - name: Repulsion Shield (4/day)(Infusion)
    desc: After being hit by melee expend 1 charge to push attacker up to 15 ft away
```

```statblock
name: Bust Barrington
image: Bust Barrington.jpg
size: Medium
type: humanoid
subtype: Human
alignment: Chaotic Good
ac: 17
hp: 45
hit_dice: 8d8 + 12
speed: 40 ft.
stats:
  - 8
  - 14
  - 14
  - 12
  - 10
  - 18
saves:
  - dexterity: 5
  - charisma: 7
skillsaves:
  - deception: 7
  - insight: 3
  - performance: 7
  - persuasion: 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 11
languages: any four languages
cr: "2"
bestiary: true
traits:
  - name: Song of Rest
    desc: Regain extra 1d6 HP for party on short rest
  - name: Bardic Inspiration 4/day
    desc: Bonus action give another creature 1d8 to next attack roll, check, or save
  - name: Jack of All Trades
    desc: Half proficiency for non-proficiencies
actions:
  - name: Rapier
    desc: "Melee Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d8 + 2) piercing damage."
  - name: Countercharm
    desc: play a tune that gives creatures advantage to saving throws from fright or charm until you stop playing.
spells:
  - "The mage is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 14, +6 to hit with spell attacks). The mage has the following wizard spells prepared:"
  - Cantrips (at will): vicious mockery, blade ward, minor illusion
  - 1st level (4 slots): detect magic, healing word, tasha's hideous laughter, thunderwave
  - 2nd level (3 slots): cloud of daggers, hold person, invisibility, mirror image, zone of truth
  - 3rd level (3 slots): mass healing word, hunger of hadar, dispel magic
```

```statblock
name: Roaming Bull
image: Roaming Bull.jpg
size: Medium
type: humanoid
subtype: Human
alignment: Lawful Neutral
ac: 15
hp: 66
hit_dice: 12d10
speed: 40 ft.
stats:
  - 20
  - 14
  - 16
  - 8
  - 8
  - 10
saves:
  - strength: 8
  - constitution: 6
skillsaves:
  - athletics: 8
  - insight: 2
  - intimidation: 8
  - religion: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 9
languages: common
cr: "2"
bestiary: true
traits:
  - name: Reckless Attack
    desc: On firts attack of turn, decide to attack recklessly. Gives ADV on melee attacks, also grants advantage on attacks made at Roaming Bull until is next turn.
  - name: Danger Sense
    desc: ADV on DEX throws he can see while not blind, deaf, or incapacitated
  - name: Ancestral Protectors
    desc: While raging, the first creature Bull hits each turn has disadvantage on any attack other than Bull. Any attacks they land on another target are halved
actions:
  - name: Punch (Raging)
    desc: "Melee Attack: +8 to hit, reach 5 ft., one target. Hit: 4 (1 + 7) bludgeoning damage."
  - name: Greatsword
    desc: "Melee Attack: +8 to hit, reach 5 ft., one target. Hit: 4 (2d6 + 5) slashing damage."
  - name: Charge
    desc: When Bull takes dash action and travels 10> ft, he can use a bonus action to make one melee weapon attack = +5 attack roll or push target 10 feet away on successful shove attempt.
reactions:
  - name: Spirit Shield
    desc: Creature, when hit, within 30 feet reduces incoming damage by 2d6
```

```statblock
name: Timothy Thimbleton
image: Timothy Thimbleton.jpg
size: Medium
type: humanoid
subtype: Wood Elf
alignment: True neutral
ac: 15
hp: 38
hit_dice: 7d10
speed: 35 ft.
stats:
  - 10
  - 12
  - 15
  - 18
  - 10
  - 13
saves:
  - intelligence: 7
  - wisdom: 3
  - perception: 3
  - sleight of hand: 4
  - stealth: 4
skillsaves:
  - arcana: 7
  - history: 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 13
languages: any four languages
cr: "2"
bestiary: true
traits:
  - name: City Secrets
    desc: When not in combat, move through two locations in the city twice as fast
actions:
  - name: Dagger
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 4 (1d4 + 1) piercing damage."
  - name: Mask of the Wild
    desc: You can attempt to hide even when only lightly obscured by foilage, heavy rain, falling snow, mist and other natural phenomena
  - name: Spell slot ring (1/day)(Infusion)
    desc: Recover 3rd level or lower slot
spells:
  - "The mage is a 6th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 15, +7 to hit with spell attacks). The mage has the following wizard spells prepared:"
  - Cantrips (at will): fire bolt, blade ward, mind sliver, message
  - 1st level (4 slots): burning hands, mage armor, color spray, shield, silvery barbs
  - 2nd level (3 slots): dragon's breath, shatter
  - 3rd level (3 slots): counterspell, fireball, thunder step, ashardalon's stride
```


![[Seraphon Hybrid.png]]

![[Gorthul.png]]

![[Pasted image 20240320105617.png]]

![[Pasted image 20240320105653.png]]

![[Seraphon (RAtC).png]]

![[Pasted image 20240320110219.png]]

![[Pasted image 20240320110256.png]]

![[Ruby.png]]