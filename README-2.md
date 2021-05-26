# DNDuet Core SRD
This is a system reference document for *DNDuet*, a framework for creating custom tabletop RPGs for one player and one narrator. The narrator controls the world and events of the story while the player controls the protagonist.

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

## Items & Abilities
Creatures can use learned abilities and collected items to improve specific action or damage rolls. Characters start with one `F`‐rank ability and gain a new ability (or upgrade an existing one) when they level up. Items are ranked by their effectiveness. Some items are spent when used and others break if used on an action roll where the `d20` lands on a natural 1.

|  | F | D | C | B | A | S |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Item** | +1 | +2 | +3 | +4 | +5 | +6 |
| **Ability** | `d4` | `d6` | `d8` | `d10` | `d12` | `d20` |

### Value and Consumables
Items with limited uses are called "consumables" and include things like potions, scrolls, food, and traps. These items are destroyed on use and can come bundled or be found/sold individually. For item value, roll the same amount of dice as the sides of the die listed under **Ability**, which means `F`-rank treasures are worth `4d4` monies. Potions and scrolls give the holder a portable magic spell which can either add a temporary ability or provide specific damage dice (or healing) based on their rank. For a consumable item's damage dice, roll **Item** amount of **Ability** dice (`1d4`, `2d6`, `3d8`, etc.). This also applies to food (which heals) and traps or other consumable damaging items like runes, mines, bombs, etc.
