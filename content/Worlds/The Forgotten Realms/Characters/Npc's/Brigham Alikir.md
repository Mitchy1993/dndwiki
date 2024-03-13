An enigmatic shadow druid, is a member of the secretive Purification Society, dedicated to eradicating what they see as impurities in nature. With a fanatical devotion to their cause, Brigham believes that only by purging the world of lesser races can nature truly thrive. Joining Timothy's rival party, Brigham sees an opportunity to further the goals of the Purification Society and cleanse the land of those he deems unworthy.
![[Brigham Alikir.jpg]]
![[Shadow Sapling.jpg]]
# Statblock
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
actions:
  - name: Shadow Swipes
    desc: "Melee Attack: +7 to hit, reach 5 ft., one target. Hit: 4 (2d6 + 2) necrotic damage."
  - name: Quarterstaff
    desc: "Melee Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6) bludgeoning damage."
  - name: Shillelagh/1 min
    desc: "BA to activate. Melee Attack: +6 to hit, reach 5 ft., one target. Hit: 4 (1d8 + 3) bludgeoning "
  - name: Defile Ground 1/rest
    desc: "BA to activate. Patch of land or water in 10 ft radius within 60ft is corrupted for 1 min. Difficult terrain for enemies. Creature in area that takes damage for the first time, per turn, takes extra 1d4 necrotic. Can move as bonus action"
spells:
  - "The mage is a 6th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 14, +6 to hit with spell attacks). The caster has the following artifcier spells prepared:"
  - Cantrips (at will): poison spray, shillelagh, minor illusion
  - 1st level (4 slots): Earth tremor
  - 2nd level (3 slots): darkness, invisibility(free 1/day), locate object, shadow blade
  - 3rd level (3 slots): bestow curse, conjure animals, fear, revivify, tidal wave, wall of water
reactions:
  - name: Call Shadowseeds (PROF/day)
    desc: When a non-undead or construct takes damage in defiled ground, summon a Shadow Sapling that obeys your commands
```

```statblock
name: Shadow Sapling
image: Shadow Sapling.jpg
size: tiny
type: plant
subtype: sapling
alignment: Chaotic Evil
ac: 10 + PB
hp: 2*Druid Lvl
hit_dice: 3d6 + 2
speed: 30 ft.
stats:
  - 8
  - 13
  - 12
  - 4
  - 8
  - 3
saves:
skillsaves:
damage_vulnerabilities: "fire"
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 9, blindsight 60 ft.
languages: common, elvish
cr: ""
bestiary: true
traits:
actions:
  - name: Multiattack
    desc: "2 attacks When you reach 14th lvl"
  - name: Claws
    desc: "Melee Attack: +6 to hit, reach 5 ft., one target. Hit: 4 (2d4) + PB piercing damage."
```
# Circle of Shadow's Druid
Circle of Shadows

Those in this circle live where the canopy is thick. The crossroads where travlers lose their way in the forest and jungles. They see it as their sacred duty to be the necessary evil. Not a darkness born of necromancy or the nine hells but the cruel hand of nature herself.

**2nd Level**

Bonus Cantrip

Upon joining this Circle you learn your the _Minor illusion_ or _Chill Touch_ Cantrip.

_This is the optional ability, simply to get the theme across, though I’m happy to remove it_

Strength of the Shadows

Your familiarity with the shadows and dark places has caused you to become resistant to necrotic damage, in addition you gain darkvision to 60ft, if you already have darkvision its range is instead increased by 30ft.

_I find this Thematic, and reasonably strong, though I’m keen to hear your thoughts_

Shadow Form

When you join this Circle at second level you learn the art of becoming a shadow. You may expend one use of your wild shape to become a _Shadow_ (MM.269) with the following changes.

- the _Strength Drain_ Attack is replaced with the following attack. **Life Drain.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: (2d6 + 2) necrotic damage. On a hit your shadow form regains a number of hitpoints equal to half the damage dealt.
    
- it gains a number of additional hit die equal to half your Druid level rounded down.
    

The same rules apply as your regular Beast shapes and once you’ve used this ability, you cannot do so again until you’ve finished a long or short rest. At 10th level you may use your wildshape to assume this form as often as you wish.

_before you panic, CR wise this is weaker than a moon druid, that said I know the potency of Shadows so until 10th level it’s limited to once per short rest, and from then till 20th it’s twice, in addition this form has a low AC and quite low health so I think it’s reasonable, though again criticisms are welcomed_

---

**3rd Level**

Bonus spells

At 3rd, 5th, 7th, and 9th level you gain access to the following circle spells whispered to you by the archdruid ghosts of the Circle of Shadows. Once you gain access a circle spell. You always have it prepared, and it doesn't count against the number of spells you can prepare each day. If you gain access to a spell that doesn't appear on the druid spelllist, the spell is nonetheless a druid spell for you,

|Druid Level|Circle Spells|
|---|---|
|3rd|Shadow Blade, Darkness|
|5th|Bestow Curse, Fear|
|7th|Shadow of Moil, Evards Black Tentacles|
|9th|Mislead, Negative Energy Flood|

---

**6th Level**

Call of the Shadowseeds

At level 6, your Defile Ground starts to foster new life. As a reaction when your Defile Ground does Necrotic damage to an enemy – who is not an Undead or Construct – you can summon a Blighted Sapling. This little fella can immediately attack and then obeys your commands. These last until you summon a new one, until you take a long rest, or until it reaches 0 hit points. You can only use this ability a number of times per day equal to your Proficiency modifier.

The Sapling itself is _exceptionally_ weak defensively, sporting a mere 2 * Druid Level hitpoints. A Fireball will _decimate_ this thing, as it is Vulnerable to Fire. It has okay AC with 10 + Proficiency Bonus. It is an awful scout, though it does have Blindsight 60 feet. 

Offensively, it has your spell attack modifier and 2d4 + PB piercing damage for a melee attack. That’s pretty solid! It’ll keep up with your accuracy and doesn’t do abysmal damage. At level 14, it gains Multiattack, getting two attacks.

The limitation on daily uses should very rarely come up. 6 of these fellas should be plenty for a day. Try to time your reaction so this guy gets to attack _right_ before your turn, maximizing the number of times it can attack.

---

**10th level**

Boogieman

At 10th level your ties with the Shadows have grown stronger, enhancing your abilities in the following ways,

- You may Hide as a bonus action on each of your turns.
    
- You become proficient in the Stealth skill if you aren’t already and may add your wisdom modifier to any stealth checks you make in dim light or darkness.
    
- When in darkness or dim light you have resistance to piercing, bludgeoning and slashing damage.
    
- When you use your Shadow Form ability to become a shadow, you gain temporary hitpoints equal to your Druid level + your Wisdom Modifier, in addition that form loses its Sunlight Sensitivity and vulnerability to Radiant Damage.
    

_This is the level where it all comes together, where you truly become the boogie man, I think it accomplishes that without being overly powerful_

---

**14th Level**

Fear the Dark

At 14th level the darkness brings you potency, if you hit a creature with a spell attack whilst either you or your target are in dim light or darkness, that spell deals additional necrotic damage equal to your Wisdom Modifier.

In addition you may force the target to make a Wisdom saving throw against your Spell Save DC. On a failed save they become frightened of you until the end of its next turn. You may use this ability a number of times equal to your Wisdom modifier, regaining all uses after a short or long rest.

_i think this fits the theme, but may be too powerful, please let me know, also tell me if this adds too many rolls_