# DNDuet Core SRD
*DNDuet* (Dramatic Narrative Duet) is a framework for creating custom tabletop RPGs for one player and one narrator. The narrator controls the world and events of the story while the player controls the protagonist.

## Action Rolls
When facing an obstacle, the player makes an **action roll** by describing their intention, rolling `1d20`, and adding their most relevant trait to the result. The narrator rolls `1d20`, adds the obstacle's relevant trait or bonus, and compares both results. If the player's result is higher the outcome is positive and if not, the outcome is negative. Ties result in a positive outcome that comes at a cost. When creating a character, roll `1d4‐2` for the following six traits:

| Trait | Abbr. | Description |
| ---:|:---:|:--- |
| Strength | `STR` | Athletics, muscle, melee |
| Dexterity | `DEX` | Acrobatics, stealth, finesse |
| Constitution | `CON` | Durability, healthiness |
| Intelligence | `INT` | Memory, logic, investigation |
| Wisdom | `WIS` | Intuition, perception, aim |
| Charisma | `CHA` | Performance, persuasion, deceit |

When the player gains a level they add 1 point to any one trait (max +5).

## Heart Points
Characters, along with most obstacles, have a resource called **heart points (HP)** that represents their overall integrity. On a positive outcome against an obstacle with HP, the player rolls their **damage dice** to reduce it. Obstacles with zero HP are no longer a threat. On a negative outcome the player takes damage and if their HP reaches zero they suffer a major narrative setback. Death, however, must be unanimous.

Characters start with 10 max HP at level 1. The player may restore lost HP using their damage dice after 2 hours of rest in a safe place. When the player levels up, they increase their max HP by rolling their new damage dice:

| L1 | L2 | L3 | L4 | L5 | L6 | L7 | L8 | L9 | L10 | L11 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `2d6` | `2d8` | `2d10` | `2d12` | `3d10` | `3d12` | `4d10` | `4d12` |

## Abilities
Combat tactics, professional skills, and magical spells are all placed under a resource called **abilities**. Abilities allow the character to add bonus dice to specific rolls based on the character's training, studies, and gifts. Characters start with one `F`-rank ability at level 1. When leveling up the player can choose to increase the rank of an existing ability or learn a new `F`-rank ability. Abilities can also be temporary, granted through narrative events or items such as magic potions or scrolls.

### Ability Dice by Rank
| F | D | C | B | A | S |
|:---:|:---:|:---:|:---:|:---:|:---:|
| `+1d4` | `+1d6` | `+1d8` | `+1d10` | `+1d12` | `+1d20` |

## Items
Characters collect items during their adventure that they can use to add bonuses to specific rolls, heal/deal damage, or barter for goods and services. Characters start with three `F`-rank items. There are six item categories that define the mechanical effect an item has when used, based on it's rank:

| Category | Usage | F | D | C | B | A | S |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Tools** | Trait bonus | `Roll+1` | `Roll+2` | `Roll+3` | `Roll+4` | `Roll+5` | `Roll+6` |
| **Weapons** | Damage bonus | `DMG+1` | `DMG+2` | `DMG+3` | `DMG+4` | `DMG+5` | `DMG+6` |
| **Armor** | Reduce damage | `DMG-1` | `DMG-2` | `DMG-3` | `DMG-4` | `DMG-5` | `DMG-6` |
| **Food** | Restore HP | `+1d4 HP` | `+2d6 HP` | `+3d8 HP` | `+4d10 HP` | `+5d12 HP` | `+6d20 HP` |
| **Traps** | Inflict damage | `1d4 DMG` | `2d6 DMG` | `3d8 DMG` | `4d10 DMG` | `5d12 DMG` | `6d20 DMG` |
| **Treasure** | Trade value | `4d4` | `6d6` | `8d8` | `10d10` | `12d12` | `20d20` |

As an example, the player might have an iron chain that acts as a `D`-rank tool, giving them a +2 to `STR` rolls when using the chain to restrain something. All items have a value based on their rank (see "Treasure") but the treasure category specifically refers to items that do not provide another advantage; treasure's only intended use is for bartering, trading, and bribing.
