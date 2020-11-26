# DNDuet Core Rulebook
_DNDuet_ is a simple, flexible system for building and playing custom tabletop RPGs.

## Stats
Roll `1d4-2` for your starting stats.

| Stat | Abbr. | Use |
|:---:|:---:|:--- |
| Strength | `STR` | Athletics, muscle, melee |
| Dexterity | `DEX` | Acrobatics, stealth, precision |
| Constitution | `CON` | Health, endurance, stamina |
| Intelligence | `INT` | Memory, logic, tactics |
| Wisdom | `WIS` | Intuition, perception, ranged |
| Charisma | `CHA` | Performance, persuasion, deceit |

## Action Rolls
Roll `1d20+stat` for actions with uncertain outcomes. The target to beat depends on the GM's action roll and the obstacle's rank.

| Result | Outcome |
|:---:|:---:|
| > Target | Positive |
| = Target | Mixed |
| < Target | Negative |

## HP and Damage
On successful action rolls against an obstacle roll your **damage dice** and subtract the result from the obstacle's remaining **heart points (HP)**. When the obstacle's HP reaches zero it is no longer a threat.

Player characters start with `10+CON` HP at level 1. If a PC's HP falls to zero, they suffer a dire consequence. While resting with food and sleep, roll damage dice to heal HP. When you level up, roll your new damage dice and add the result to your max HP. You can reroll `CON` dice when increasing your max HP.

### Damage Dice
| L1 | L2 | L3 | L4 | L5 | L6 | L7 | L8 | L9 | L10 | L11 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `2d6` | `2d8` | `2d10` | `2d12` | `3d10` | `3d12` | `4d10` | `4d12` |

## Ranks
There are six ranks which describe obstacles, special moves, and item categories in _DNDuet_. Characters have six special moves based on their physical features, training, or background and can carry `10+STR` items in their inventory at a time.

|  | F | D | C | B | A | S |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Uses** | L/1 | L/2 | L/3 | L/4 | L/5 | L/6 |
| **Max HP** | `4d4` | `6d6` | `8d8` | `10d10` | `12d12` | `10d20` |
| **Damage** | `1d4` | `F+1d6` | `D+1d8` | `C+1d10` | `B+1d12` | `A+1d20` |
| **Buff** | `+/- 0` | `+/- 1` | `+/- 2` | `+/- 3` | `+/- 4` | `+/- 5` |
| **Value** | `%cp` | `%sp` | `%gp` | `%pp` | `%pp*10` | `%pp*100` |
