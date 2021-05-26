# *DNDuet* Core
*DNDuet* (Dramatic Narrative Duet) is a framework for building tabletop RPGs for one narrator and one player. The narrator describes the world and events of the story while the player controls the protagonist.

When a player's action involves a chance of failure and risk, the narrator will ask them to make an **action roll** using `1d20` and adding their most relevant **trait** score to the result. The narrator rolls `1d20` and adds the obstacle's bonus or relevant trait score and looks for the higher result. If the player wins the outcome is positive and if not the outcome is negative. Ties result in a positive outcome that comes at a cost. When creating a level 1 character, the player rolls `1d4-2` to set their six starting trait scores:

| Trait | Abbr. | Description |
| ---:|:---:|:--- |
| Strength | `STR` | Athletics, muscle, melee |
| Dexterity | `DEX` | Acrobatics, stealth, finesse |
| Constitution | `CON` | Durability, healthiness |
| Intelligence | `INT` | Memory, logic, investigation |
| Wisdom | `WIS` | Intuition, perception, aim |
| Charisma | `CHA` | Performance, persuasion, deceit |

Characters gain +1 to one trait score when they gain a level.

If the obstacle has heart points (HP) and the outcome is positive, the player may roll damage dice to reduce the obstacle's HP. Obstacles with zero HP are no longer a threat. On a negative outcome the narrator might roll damage dice to reduce the character's HP. Characters with zero HP suffer a major narrative setback such as permanent injuries, lost or broken equipment, or even death (if allowed by the player). Characters start with 10 max HP at level 1 and increase their limit by rolling their new damage dice when they gain a level:

| L1 | L2 | L3 | L4 | L5 | L6 | L7 | L8 | L9 | L10 | L11 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `2d6` | `2d8` | `2d10` | `2d12` | `3d10` | `3d12` | `4d10` | `4d12` |


| Rank | Ability | Item Bonus | Item Damage | Value |
|:---:|:---:|:---:|:---:|:---:|
| `F` | Roll+`1d4` | Roll+1 | `1d4 HP` | `4d4` |
| `D` | Roll+`1d6` | Roll+2 | `2d6 HP` | `6d6` |
| `C` | Roll+`1d8` | Roll+3 | `3d8 HP` | `8d8` |
| `B` | Roll+`1d10` | Roll+4 | `4d10 HP` | `10d10` |
| `A` | Roll+`1d12` | Roll+5 | `5d12 HP` | `12d12` |
| `S` | Roll+`1d20` | Roll+6 | `6d20 HP` | `20d20` |
