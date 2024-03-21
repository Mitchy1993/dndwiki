
```ad-warning
Hag want's to enslave one party member and collect the blood of the rest for her Red Caps
```
A "merchant," with some "horses," stumbles across the party and asks if they need any help or supplies

<small> One horse is jittery and very restless <big>
<small> - Red cap on his 3rd day without soaking his cap in blood <big>

- Asks what kind of quest they're on
- Offer's a fix-it-all mcguffin that they have to ingest
	- Actually a disguised piece of hag hair that mind controls them
		- Player remains in control of their character, but their character has to attack, cast a negative spell on, or otherwise impede their party
		- They may try to beat a DC 18 after each action to break free
#### Loot
- Iron Boots
	- As an action, move up to your speed and kick a target with iron boots. The target must succeed on a DC 14 DEX save or take 3d10 + STR Bludgeoning DMG & Prone
```statblock
name: Forest hag
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

```statblock
name: Redcap
size: small
type: fey
subtype: ""
alignment: chaotic evil
ac: 13
hp: 45
hit_dice: 6d6 + 24
speed: 25 ft.
stats:
  - 18
  - 13
  - 18
  - 10
  - 12
  - 9
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 13
languages: Common, Sylvan
cr: "3"
bestiary: true
skillsaves:
  - athletics: 6
  - perception: 3
traits:
  - name: Iron Boots
    desc: While moving, the redcap has disadvantage on DEX(stealth) checks
  - name: Steeped in Slaughter
    desc: To sustain its unnatural existence, a redcap has to soak its hat in the fresh blood of its victims. When a redcap is born, its hat is coated with wet blood, and it knows that if the blood isn't replenished at least once every three days, the redcap vanishes as if it had never been. A redcap's desire to slay is rooted in its will to survive.  
actions:
  - name: Multiattack
    desc: "Makes three attacks with its wicked sickle"
  - name: Wicked Sickle
    desc: "Melee weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d4 + 4) slashing damage"
  - name: Ironbound Pursuit
    desc: "The redcap moves up to its speed to a creature it can see and kicks with its iron boots. The target must succeed on a DC 14 DEX save or take 20(3d10 + 4) bludgeoning DMG & Prone"
```