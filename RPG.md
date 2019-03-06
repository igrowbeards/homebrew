# Gameplay Rules

### Attributes

#### Basic Attributes
  There are 4 basic attributes that define your character:

  * `STR` Strength
  * `AGL` Agility
  * `COG` Cognition
  * `CHR` Charisma

  All attributes start at 0, You get 20 points when characters are created to increase these scores,
  however at character creation no single attribute may be higher than 15.
  
  In addition to being used as the basis for checks when a talent is not more
  appropriate your attributes modify the results of other actions your player may take.

  * `STR` modifies the damage dealt when you hit someone with something held in your hand or thrown.
  * `AGL` makes you more difficult to hit (adds to your armor class)
  * `COG` is added to spell casting attempts
  * `CHR` is added to attempts to lie, persuade, or perform

  You gain modifiers to relevant checks based on the following scale:

  score   | modifier
  --------|----------
  20      | +4
  15...19 | +3
  10...14 | +2
  5...9   | +1
  0...4   |  0 
  -1...-4  | -1
  -5...-9 | -2
  <= -10  | disabled
   
  At -10 in any ability score your character is disabled.
  With regards to `AGL` this means they are crippled, paralyzed or otherwise cannot move.
  When at -10 or lower in `COG` your character is unconscious, stunned, or comatose.
  It would be uncommon to be at -10 in `CHR` and so the consequences thereof are left as an exercise for the GM.

  The major outlier in these is `STR`. If you character reaches -10 or lower in `STR`, their body is too weakened
  or damaged to go on. They are unconscious and will die if not tended to soon or if they take any further damage.
   
#### Derived Attributes

  Characters have 2 attributes derived from other factors
  These are:
   * `AC` Armor Class
   * `HP` Hit Points

  `AC` represents how difficult a character is to hurt. This covers both how 
  difficult it is to hit them, as well as how well armored they are.
  The `AC` stat is equal to a base of 8 (for an alert character who is able to move)
  plus their `AGL` modifier, plus their armor bonus.

  Hit Points represent your characters toughness, or their ability to be battered and bruised without lasting damage.
  When receiving damage, points will be taken from this stat until none are left.
  Any subsequent damage is subtracted from the characters `STR`.

  Your characters starting hit points are equal to 5 plus your characters `STR` modifier

---

### Action Checks
  Characters will frequently take actions that may or may not succeed. During the
  course of play players and the GM will make checks to decide the results of actions.

  Checks are rolled on a single d20 + talent modifier versus a target number provided by the GM.

  Target name | Target number
  ------------|---------------
  easy        | 5
  normal      | 10
  hard        | 15
  heroic      | 20

  When instructed to roll a talent or attribute check, you roll a d20 and add
  any relevant talent or attribute modifiers (positive or negative).
  If you're not sure if something should apply a modifier just ask the GM.
  Equal or greater than the target means your character was able to accomplish
  their stated goal.

  When attempting skill checks that your character has no talents in, use the relevant ability score (as determined by the dm)
  instead of the talent bonus, but do so at a -3 penalty.

  A natural one is a catastrophic failure and a natural 20 is a critical success, regardless of modifier.

#### Failing Action Checks

  Under normal circumstances failing a talent or attribute check just means that what you're trying to do doesn't work
  and you suffer any logical ramifications of that.

  However in some circumstances failure on checks can lead to temporary damage to your attributes.

  * A critical failure on a check causes the difference after any modifiers between the target and the result
    after any modifiers in damage to the relevant attribute. If the attribute that should be damaged isn't obvious
    it's left to the GM's discrection.
  * Failure on a casting check _always_ causes temporary `COG` damage.

---

### Talents

  You define your characters skills via a list of talents 
  Talents give your character bonuses to related checks.
  Unless your GM tell you otherwise your character starts with 3 talents.

  Talents are defined and recorded in the form of

  > "My character is [_talent level_] at [_talent_] ([_modifier_])"

  Example talent levels are:

  level name    | bonus
  --------------|--------
  good          | +1
  very good     | +2
  above average | +3
  great         | +4
  amazing       | +5
  world class   | +6
  legendendary  | +7

  For example:

  > "Arthur is good at fighting with medium weapons (+1)"
  >
  >  "Leroy Jenkins is very good at maneuvering in heavy armor (+2)"
  >
  >  "Robin Hood is amazing at firing bows (+5)"
  >
  >  "Rocky is great at unarmed fighting (+4)"
  >
  >  "Dumbledore is legendary at evocation spells (+7)"
    
  All magical talents are special talents that can usually only be taken during character creation
  (unless your GM says otherwise). Usually a character that is skilled at one school of
  magic _can_ take a magical talent in another school after creation, but as always
  ultimate say lies with your GM.
  
  Magical talents should usually be fairly focused. Some good examples would be:

  * life or death magic
  * a specific element (fire, ice, air, etc) magic
  * illusion 
    
---

### Weaknesses
  
  Your characters weaknesses are things that your character has trouble doing,
  situations that cause him to perform poorly, or personal or situational traits
  that make life more difficult for them.

  The standard form of these are defined and recorded something like:

  > "My character is [_weakness level_] at [_skill_] ([_modifier_])"

  or

  > "My character is [_weakness level_] when confronted with [_situation_] ([_modifier_])"
  
  where possible talent levels are:
  
  weakness level            | modifier
  --------------------------|----------
  below average / uneasy    | -1
  bad / anxious             | -2
  awful / scared            | -3
  hopeless / petrified      | -4
  atrocious / scared stiff  | -5

  During character creation you _must_ take at least one weakness, but may optionally take 5 more levels.
  You may increase a skill by one level for each of the optional weakness levels you take.

  The above are just examples. Players or GMs may come up with other forms of
  weaknesses, and that is encouraged.

  Some example of less traditional weaknesses that characters may have are:

  * difficulty resisting temptation or vices (lust, greed, etc)
  * A powerful enemy that foils the players plans
  * Some sort of health condition (bad eyesight, maimed limbs, addictions)
  * etc

  When assigning modifiers and extra advancement points for these less standard
  weaknesses the GM should consider how often the scenario or situation is
  likely to come up how disadvantageous it will be when it happens.

  Be aware that weaknesses are not just numbers on the page, but should be used
  when role-playing your character as well as by the GM when crafting adventures.

---

### Casting Spells

  Characters who took magical skills at character creation can cast spells
  relevant to their magical talents at will, and without having predefined "spells"
  To cast a spell tell the GM what you are trying to do (preferably with a flashy name and description)
  Your GM will then tell you the target difficulty for your spell casting check.
  When successful the spell works and the GM will describe the effects of your successful casting.
  
---

### Combat

  Attempts to harm a character or NPC/monster are a modified skill check versus the armor class `AC`
  of the target. Attack rolls use _both_ the ability and skill bonus (str for melee, agl for ranged).
  A failed attack check may miss entirely, or not hit hard enough to cause harm.
  It's up to the GM to describe it as they see fit.

  If successful roll damage for your weapon and add your `STR` bonus (if applicable) to the attack. 

  Damage is dealt first to hit points `HP` and then to `STR`.  
  "Cannon fodder" enemies usually do not take `STR` damage, and are simply 
  slain when their hit points are exhausted.

#### Initiative
  At the beginning of any other scenario where timing and the order of actions is important
  the characters and NPCs involved can roll an initiative check to determine the order of their actions.
  Scenarios such as combat where the action continues for more than one round of actions
  just repeat the process. 
  An initiative check is an `AGL` check, with the entities with the highest results going first.

  In cases where one side or another in a situation is caught by surprise the GM will usually
  rule that the surprised character, NPC, or group automatically goes last. In certain more extreme
  cases the surprised group may not get a turn at all. 

  Optionally If the group desires faster gameplay the initial initiative results can just be
  used throughout the encounter, without re-rolling each round.

#### Dual Wielding

  Any character can dual wield weapons, although doing so causes a penalty to attacks.
  Talents in dual wielding can be taken to offset the penalties.
  A dual wielding character may make an attack with each hand during their round, once 
  on their regular turn, and the second at the end of the round. A character that takes and damage
  during the round after their first attack loses their second.

  All dual wielding characters use the penalties below.
  Medium weapons and larger add an additional penalty of -1 per size, per hand.

  Dual Wield Talent Level   | Dominant Hand Penalty   | Off Hand Penalty  
  --------------------------|-------------------------|-------------------
  none                      | -3                      | -7
  good                      | -3                      | -6
  very good                 | -2                      | -5
  above average             | -2                      | -4
  great                     | -1                      | -3
  amazing                   | -1                      | -2
  world class               |  0                      | -1
  legendary                 |  0                      |  0


  ```
  example:

  Retion uses a short sword (a medium weapon) in his dominant hand and a dagger (a medium weapon) and 
  in his off hand. He has no talent levels in dual wielding so his attack rolls are at
  -4 for his dominant hand (-3 for dual wielding and -1 for using a medium weapon while dual wielding)
  Attacks with his off hand are at -7 (all from the dual wielding penalty as there is no additional penalty for
  regular sized welcomes)
  ```

---

### Weapons

  Weapons are classified into the following broad damage categories.
  If your character uses a weapon that doesn't easily fit into one of the
  categories talk to your GM to determine it's stats.

  Melee Weapons:

  Type     | Example Weapons                                                         | Damage
  ---------|-------------------------------------------------------------------------|--------
  Unarmed  | an average unarmed person, without extensive or formal combat training  | d2
  Light    | small or pocket knives, improvised weapons, highly trained unarmed      | d4
  Regular  | hunting knives, hatchets, small clubs, hammers, or cudgels              | d6
  Medium   | swords, axes, large one handed clubs or maces, staves or spears         | d8
  Heavy    | Pole Arms, two handed axes or swords, two handed large clubs or maces   | d10

  In general some medium and almost all heavy weapons require 2 hands to wield properly.

---

### Armor & Shields

  Armor and shields add to a characters armor class. Armor has a min and max modifier.
  The minimum represents the bare protection it provides just by being worn (or held in the case of shields).
  The maximum is the max protection it can provide a skilled user.
  Taking talents in armor/shield usage increases the effectiveness up to a cap of the max.

  armor type   |  examples                    | base  | max | penalty
  -------------|------------------------------|-------|-----|---------
  light        | cloth or padded, thick robes | +1    | +1  |  0
  medium       | leather                      | +1    | +2  | -2
  heavy        | ring or chain mail           | +2    | +3  | -3
  extra heavy  | plate                        | +2    | +5  | -5
    
  Similar to armor shields provide a bonus to a character's armor class.
    
  type   | base  | max | penalty
  -------|-------|-----|---------
  small  | +1    | +2  | -3
  medium | +2    | +3  | -4
  large  | +3    | +4  | -5
    
  Caveats: Wearing light or heavier armor causes a `penalty` to attempts to move
  quietly, cast spells, as well as any difficult non-combat athletic maneuvers 
  such as tumbling, swimming, climbing, etc.
  
  Holding any shield causes similar penalties as armor but at an increased rate of max protection +1.
  
---

### Healing and Recovery  

  Hit points are recovered fully after combat ends and characters have a chance to rest for 10-15 minutes.
  All damaged attributes regain points at the rate of 1-d4 a day if the characters are able to eat and rest safely for at
  least 4-6 hours.

  Characters with talents in medicine or first aid can treat physically injured characters to give them a bonus of up to their
  skill level on their daily healing roll.

---

### Character Advancement

  At the logical end of each adventure each player will gain a new skill or increase an existing skill
  one level, as well as gaining 1 + their `STR` bonus in hit points.

  On even levels the character also gains 1 point to add to one of their 4 core attributes.

### Tips

  1) The primary goal is to have fun. All other principles are secondary to this first principle.
  2) RPGs are an exercise in collaborative storytelling. Make sure you're telling a story you want to hear.
  3) The "rules" are really more guidelines.
  4) Any rule that does not add to the fun or even worse takes away from the fun should be replaced or removed.
  5) Any situation that is repeatedly causing problems should have a rule added to help resolve or avoid the problems.
  5) Feel free to change, add, or remove rules, but try to make changes outside of game time.
  6) During gameplay the GM's word is law.
  7) Outside of active game time all participants are equal. Taking some time outside of gameplay to talk about 
     what has and hasn't been fun is encouraged.
  8) The GM's responsibilities are to have fun, to create the world the players act in, and to manage the game, in that order.
  9) A players' responsibility is first to have fun, and second to work with the GM and other players to tell an interesting story.
  10) Communication is key.
  11) You will get out of the game what you put into it.
