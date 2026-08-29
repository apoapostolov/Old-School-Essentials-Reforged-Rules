# Combat

## Combat

### Slow Weapons

All weapons with a damage die of `d8` or larger are SLOW. The SLOW property no longer modifies initiative.

When a creature is reduced to 0 hp by a Slow weapon, it does not die immediately. It may take one attack action before the end of the round, but it cannot move or interact. At the end of the combat round, it falls from the damage.

Certain monster attacks with a damage die of `d8` or larger may also be Slow if the monster entry or the DM says so.

> 🎲 __Foundry Tip:__ In Foundry, remove the integrated SLOW property from all weapons to avoid actors acting last in initiative automatically. Treat all weapons with a damage die of `d8` or larger as Slow.

### Draw/Stow Weapon

If a character is not holding the weapon he wants to use, he can drop what is in his hands and draw a weapon (assuming the weapon is in an accessible place, such as on a belt sheath). There's a -2 penalty to hit during the round that this happens. If a two-handed weapon is drawn, or two one-handed weapons, a one-handed weapon and a shield are drawn, the penalty increases to -4.

### Attacking Surprised Enemies

You can strike any surprised or unaware of threat enemy with a bonus of +2 to a melee or ranged attack (only rogues and assassin get a multiplier to their damage). You also benefit from this bonus if you attack an enemy engaged in combat and unaware of your presence, unable to perceive you or your approximate location.

> __MOVEMENT FROM STEALTH__ Unless you end your turn in a location providing a cover, you are detected by all enemies able to perceive you with one or several of their senses. When you move out of cover your turn, you do not become detected to any surprised or unaware enemies that share the same initiative value as you, until you take an action, make an attack, or your turn ends.

### Running in Combat

You may announce that your character will run in combat before initiative is rolled each turn. Running in combat allows your character to use its exploration speed for movement instead of its combat speed. The character cannot do anything else this turn and suffers a -4 penalty to AC against melee attacks until the start of their next turn. The character may not run at its exploration speed through any terrain that would impede or slow down its movement.

### Withdraw

When you are engaged in melee against a single enemy, you may spend your attack action before movement to find an opening and step out of that enemy's weapon range. You are no longer engaged. You may now move out of engagement range.

When you are engaged in melee against more than one enemy, you must also make a Dexterity check, with a -2 penalty for every enemy after the second. On a success, you spend your attack action and withdraw as above. On a failure, you may still withdraw if you also spend your movement for the round, and step away up to 5 feet.

This replaces the published fighting withdrawal. Turning and fleeing is still a retreat: enemies in melee may attack you at +2.

### Subduing Damage

Attacks with the "flat of the blade" for non-lethal damage are made at a -1 attack penalty. No penalty is applied if the melee weapon does bludgeoning damage and its damage die is not larger than d6. Attacks with ranged weapons that aim to disable the enemy by striking non-lethally are made at a -2 attack penalty and cannot be made at a long-range distance. Spells cannot do nonlethal damage.

### Shooting Attacks Past Creatures

When you shoot with a ranged weapon, and your line of attack passes through allies, or your target is already engaged with one or several allies, you risk hitting your allies on a poorly aimed shot. When you roll a very low natural result (1, 2, 3, etc.), your attack hits the first, second, third, etc., ally in order of closest to furthest from you instead of its intended target or randomly if they are all engaged with your initial target. Shooting through hostile creatures to hit one beyond them applies a -1 penalty to attack, plus -1 for each hostile creature that must not be hit to reach your target.

### Defensive Stance, Parry

During your attack phase, you may choose not to attack this round. If you do so, until the start of your next turn, you may prepare to Parry one melee attack that targets you by an enemy you see during your turn.

When an enemy rolls to attack and hits you before damage is rolled, you may Parry if you had prepared to. Make a roll to attack and compare your result with the result of your enemy. If your result is equal or higher, you successfully parry the attack and take no damage from it. If your Parry beat the enemy's attack roll by three or more, you get an opportunity to riposte, and the enemy takes d4 damage (with no modifiers) from your weapon.

### Cover an Ally

While you share the same 5-foot square space as another ally and the ally is prone on the ground by or behind you, you can cover that ally from enemy attacks. At the end of your turn, you take a -1 penalty to your ascending Armor Class (or +1 if descending), and your ally benefits from +2 to their ascending Armor Class (or -2 if not ascending). This effect lasts until the end of your next turn when you can continue or end this effect. Low-intelligence enemies would attack you instead of the ally you cover; high-intelligence enemies may choose to attack through you.

While prone and sharing the same 5-foot square space, your ally may choose to take no movement and no attack action but to improve its cover from you. This must be announced before rolling the initiative for the round. If they do so, the benefit from being covered by you increases to +4 to their ascending Armor Class (or -4 if not ascending).

### Ganging Up

When ganging on an enemy, the number of creatures that can attack at in melee is limited without crowding into each other's swings. One size step is the difference between a Halfling and a Human, or a Human and an Ogre.
| Attackers relative to the target      | Close engagement maximum |
| ------------------------------------- | ------------------------ |
| Same size                             | 3                        |
| Same size, plus one size step smaller | 3, plus 2 more (5 total) |
| One size step larger                  | 2                        |
Any additional creature that announce to attacks the same enemy in melee in the same turn apply a cumulative -2 penalty for each extra attacker (-2 for the first extra, -4 for the second, and so on) to all attackers engaged with that enemy.

Attackers with long weapons (spears, polearms, and other reach weapons; see Weapon Mastery) that attack a target already at or above its close engagement maximum count as extra attackers and take this penalty.

## Masterwork Weapons and Armor

Finely crafted weapons and armor (denoted +1 masterwork in statblocks) are often just superior items of expert workmanship, often status symbols for nobility, knights, and officials. These are not magical unless they exhibit additional magical effects (e.g., glow under detect magic, special abilities). True magical weapons/armor (+1 or higher) add their full bonus to both to-hit and damage/AC, and increase their chances to withstand damaging effects. New characters cannot start with masterwork weapons and armor, unless the DM has a good reason to allow it.

| Item Type               | Benefit                     | Durability                 | Cost Mod        |
| ----------------------- | --------------------------- | -------------------------- | --------------- |
| __Weapon (Masterwork)__ | +1 to hit __only__          | +1 SV vs. sunder/rust/acid | ×3              |
| __Armor (Masterwork)__  | +1 AC __only__              | -                          | ×5              |
| __Weapon (Magical +X)__ | +X to hit __and__ +X damage | +1 SV vs. sunder/rust/acid | Per magic rules |
| __Armor (Magical +X)__  | +X AC                       | +X SV vs. sunder/rust/acid | Per magic rules |

## Damage and Healing

### Dropping to 0

- When you take damage and your hp becomes 0 or less, you drop unconscious and start dying, and the excess damage is deducted from your Constitution score, point for point. Record your modified Constitution score separately, but do not change your hit points modifier yet.

> 🎲 __Foundry Tip:__ In Foundry, create a character ability in your character sheet and use its name to record your unmodified Constitution so you are quickly reminded of its maximum value later on.

- When your Constitution score is reduced as a result of taking damage and your hit points are 0, anytime you receive first aid, magical healing or healing potion, or natural healing (such as a salve), make a d20-roll-under Constitution check. If you make the save, you were still hanging on your dear life even if your hit points are 0, and the healing effect is applied. If you fail the save, you died before you could have been healed and are pronounced dead.
- Once combat is over, within one minute of starting dying any player character that is unconscious and starts receiving first aid lasting at least one turn makes the same Constitution save, and on success recovers 1 hp at the end of the turn receiving first aid. Retainers and henchmen have a 2-in-6 chance to regain 1 hp if they receive first aid, and the chance is modified by their Constitution bonus to hit points (minimum 0 in 6, maximum 5-in-6). Any other creature left without first aid will die.
- At the end of combat, recalculate your hit points using your changed Constitution score. If your modified Constitution score is 7 or below, the negative modifier to hit dice is also applied as a penalty to attack rolls and all saving throws. This doesn’t happen mid-combat but only after combat, when the adrenaline wears off.
- Also at the end of combat, you gain an injury that is for roleplaying purposes only and will remind you of the unfortunate events of this combat. Work with your DM on the specifics of the injury. If you lost 3 or fewer Constitution points this combat, the injury is minor and will fully heal once your Constitution score returns to normal. If you lost 4 or more Constitution points in this combat, the injury is severe and will never fully heal, although once your Constitution score returns to normal you will learn how to deal with it for the rest of your life.
- If your Constitution score reaches 0, you are decapitated. Spells that would prevent death or bring you back to life (or unlife, unless it doesn’t require a capable body) consider your body unusable.
- You recover 1 point of Constitution per week if your modified Constitution is 7 or less, and 1d3 points of Constitution per week if your modified Constitution is 8 or more. If you do not benefit from medical care, you do not recover anything if your Constitution is 7 or less, or 1 point if your Constitution is 8 or more. Your modified Constitution cannot increase above your normal Constitution.

### Fire Damage

Burning Oil Flasks do 1 point of damage when they break after a successful hit and set a creature on fire. At the start of its turn, a burning creature takes 1d6 points of fire damage. If the damage taken from that die is 1-3, the die rolled on the next turn decreases in size (to 1d4, and if 1d4 decreases in size the creature is no longer Burning). The Burning creature can also choose to not attack on its turn but attempt to stop the burning; it drops what it is carrying or must drop prone, and this causes the die rolled on the next turn to decrease in size. Using multiple oil flasks to put a creature on fire has no cumulative effect on the creature's burning condition but each following flask resets the die size to d6.

Improved or Magical Burning Oil can start for a die higher than d6 and take more turns to stop, or have fewer or specific conditions to decrease its die size.

### Bleeding Damage

Weapons with the Bleeding quality cause the Bleeding condition on a critical roll of natural 20 on attack rolls, and when they roll maximum damage. A Bleeding creature takes 1 damage at the end of their turn and makes a Constitution check; on success, they stop Bleeding.
