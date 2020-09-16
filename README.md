# dnduet Core System
dnduet is a system for building and playing custom tabletop RPGs. A game master (GM) controls the world in which the player character (PC) exists. The player makes decisions for their character and rolls dice to determine outcomes of uncertain actions and move the narrative forward.

## Character Creation
Roll `1d4-2` for each of the stats below. You may rearrange the results.

| Stat | Abbr. | Uses |
|:---:|:---:|:--- |
| Strength | `STR` | Athletics, power, melee attacks |
| Dexterity | `DEX` | Acrobatics, stealth, finesse |
| Constitution | `CON` | Endurance, stamina, health |
| Intelligence | `INT` | Memory, logic, strategy |
| Wisdom | `WIS` | Intuition, perception, ranged attacks |
| Charisma | `CHA` | Personality, persuasion, deceit |

Once you have 6 starting stats come up with a personality, background, and desire, then briefly describe your character's appearance.

## Actions
If the outcome of a character’s action is uncertain, make an **action roll** by rolling `1d20`, adding a relevant stat modifier, and checking the result against the _Air of Fate_. The _Air of Fate_ is a number that represents the current level of challenge. Outcomes of action rolls are as follows:

| Result | Outcome |
|:---:|:---:|
| Result > AoF | Positive Outcome |
| Result = AoF | Mixed Outcome |
| Result < AoF | Negative Outcome |

Many targets can roll an opposing action (dodge, counter, etc.), and replace the _Air of Fate_ with their own roll. This is called a **contest**.

## Heart Points
Your character starts out with `10+CON` **heart points (HP)** at level 1. Creatures, objects, and tasks can all have HP which represents the effort required to overcome them. On a successful action roll against a target with HP, roll your level-specific **damage dice** and reduce the target's HP by the result. Damage dice are also used to replenish HP during a short rest (<8 hours). A long rest (8+ hours) restores your HP fully.

If the player's HP reaches zero, they suffer a major narrative setback such as imprisonment, dismemberment, or even death.

## Moves
Creatures and characters start with 1 **move** and can have up to 4 at a time. Moves are special actions that your character can make using their specific talents, abilities, or physical features. Moves may also be based on your character's background or profession. Each move has a limited number of uses (per long rest) based on your level.

Moves can do extra damage, add 1 or 2 points to a stat for a turn, impose advantage or disadvantage to a roll, or result in a progression of the narrative. If you're having trouble coming up with moves for your character, use the following base classes as a guide:

| Class | LV/1 uses | LV/2 uses | LV/3 uses | LV/4 uses |
|:---:|:---:|:---:|:---:|:---:|
| Warrior | `1.5x Damage` to target | Redirect Damage | `+1 STR/CON` to self | `+2 STR/CON` to self |
| Rogue | Perform Skill | `1.5x Damage` to target | `+1 DEX/CHA` to self | `+2 DEX/CHA` to self |
| Cleric | Heal `1.5x Damage` to self or target | `+1 stat` to self or target | `+2 stat` to self or target | Give `advantage` to self or target |
| Wizard | `-1 stat` to target | `1.5x Damage` to target | `-2 stat` to target | Impose `disadvantage` on target |

## Items and Inventory
**Items** work in a similar way to moves; they might be required for certain moves or only have a limited number of uses. They might also come with downsides, such as curses, side effects, or bounties. Characters can carry `10+STR` items at one time.

Items range from rank F to rank S and can have an effect on stats, action rolls, HP, and other areas of the game world. The ranks are explained below:

| Rank | Type | Effect |
|:---:|:---:|:--- |
| S | Blessed | Advantage on some rolls |
| A | Legendary | +3 to certain action rolls |
| B | Very Rare | +2 to certain action rolls |
| C | Rare | +1 to certain action rolls |
| D | Mundane | No special effect |
| F | Cursed | Disadvantage on some rolls |

## Leveling Up
After reaching significant milestones, The GM can grant players a level up to improve their character by increasing their max HP, upgrading their damage dice, adding a point to a stat (no more than 5 points per stat), and either learning new moves or swapping old moves for new ones. When increasing HP you can choose to reroll `CON` dice.

| LV | Max HP | Damage |
|:---:|:---:|:---:|
| 1 | `10+CON` | `1d4` |
| 2 | +`2d4` | `1d6` |
| 3 | +`2d4` | `1d8` |
| 4 | +`2d4` | `1d10` |
| 5 | +`3d6` | `2d6` |
| 6 | +`3d6` | `2d8` |
| 7 | +`3d6` | `2d10` |
| 8 | +`3d6` | `2d12` |
| 9 | +`3d12` | `3d10` |
| 10 | +`3d12` | `3d12` |
| 11 | +`3d12` | `4d10` |
| 12 | +`5d10` | `4d12` |

Get creative with character creation, systems for magic or other special skills, setting, themes, etc. This system was built for maximum flexibility.

Check out dnduet.com for more!

# Game Master Guide
The game master is responsible for all of the non-player characters (NPCs) in the campaign and giving the player options to move the story forward. They design and populate the world in which the characters live and act, throwing obstacles between the player and their goals.

## Setting the Air of Fate
The Air of Fate signifies the level of challenge the characters are facing. Typically 10 is a neutral and effective challenge, but the Air of Fate can change (8, 12, etc.) depending on the situation. Keep the level of challenge reasonable and remember that you can also make some actions easy (AoF-3) or  hard (AoF+3) to keep the game from becoming unfair.

## Enemy Generator
| LV | Max HP | Damage |
|:---:|:---:|:---:|
| 1 | `2d4` | `1d4` |
| 2 | `3d6` | `1d6` |
| 3 | `3d10` | `1d8` |
| 4 | `6d6` | `1d10` |
| 5 | `5d10` | `2d6` |
| 6 | `8d8` | `2d8` |
| 7 | `7d12` | `2d10` |
| 8 | `10d10` | `2d12` |
| 9 | `10d12` | `3d10` |
| 10 | `15d10` | `3d12` |
| 11 | `15d12` | `4d10` |
| 12 | `20d12` | `4d12` |
