# DNDuet Core SRD
This is a system reference document for DNDuet, a simple framework for building and playing custom tabletop RPGs with 1 player and 1 narrator. The narrator describes the world and events of the story while the player controls the protagonist.

When the player faces an obstacle, they make an action roll by describing their intention, rolling 1d20, and adding their most relevant trait to the result. The narrator rolls 1d20, adds the obstacle's bonus, and compares both results. If the player's result is higher the outcome is positive and if not the outcome is negative. Ties result in a positive outcome that comes at a cost. When creating a character, roll 1d4‐2 for the following six traits:

| Trait | Abbr. | Description |
| ---:|:---:|:--- |
| Strength | `STR` | Athletics, muscle, melee |
| Dexterity | `DEX` | Acrobatics, stealth, finesse |
| Constitution | `CON` | Durability, healthiness |
| Intelligence | `INT` | Memory, logic, investigation |
| Wisdom | `WIS` | Intuition, perception, aim |
| Charisma | `CHA` | Performance, persuasion, deceit |

When the player levels up they add 1 point to any one trait (max +5).

## Heart Points
Characters, along with most obstacles, have a resource called heart points (HP) that represents their overall integrity. On a positive outcome against an obstacle with HP the player rolls their damage dice to reduce it. Obstacles with zero HP are no longer a threat. On a negative outcome the player takes damage and if their HP reaches zero they suffer a major narrative setback. Death must be unanimous.

Characters start with 10 max HP at level 1. The player may restore lost HP using their damage dice after 2 hours of rest in a safe place. When the player levels up, they increase their max HP by rolling their new damage dice:

| L1 | L2 | L3 | L4 | L5 | L6 | L7 | L8 | L9 | L10 | L11 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `2d6` | `2d8` | `2d10` | `2d12` | `3d10` | `3d12` | `4d10` | `4d12` |

## Items & Abilities
The player can use learned abilities and collected items to improve specific action or damage rolls. Characters start with one F‐rank ability and gain a new ability (or upgrade an existing one) when they level up. Items are ranked by their effectiveness. Some items are spent when used and others break if used on an action roll where the d20 lands on a natural 1. The narrator creates obstacles as items with HP.

| Rank | Bonus | Damage | Max HP | Value |
|:---:|:---:|:---:|:---:|:---:|
| F | +1 | `1d4` | `4d4` | 0.01 |
| D | +2 | `F+1d6` | `6d6` | 0.1 |
| C | +3 | `D+1d8` | `8d8` | 1 |
| B | +4 | `C+1d10` | `10d10` | 10 |
| A | +5 | `B+1d12` | `12d12` | 100 |
| S | +6 | `A+1d20` | `20d20` | 1000 |

&#42;For value, roll `1d00` and multiply by the listed value
