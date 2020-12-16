# DNDuet Core Rules
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

You can rearrange your starting stat scores once. When leveling up, add 1 point to any one stat with less than 5.

## Action Rolls
Roll `1d20+stat` for actions with uncertain outcomes. The target to beat depends on the GM's action roll and the obstacle's rank. Rolling higher than the target results in a positive outcome and rolling lower results in a negative outcome. Ties result in a mixed outcome.

## Heart Points
With positive outcomes against an obstacle, roll your **damage dice** and subtract the result from the target's **heart points (HP)**. When an obstacle's HP reaches zero it is no longer a threat.

Player characters start with `10+CON` HP at level 1. If a characters's HP reaches zero they suffer a major setback like imprisonment, severe injury, or even death. 

For every two hours of rest in a safe area, roll your damage dice to recover some HP. When you level up, roll your new damage dice and add the result to your max HP. You can reroll `CON` dice when leveling up.

### Damage Dice
<table>
  <tbody>
    <tr>
      <th>L1</th>
      <td><code>1d4</code></td>
      <th>L4</th>
      <td><code>1d10</code></td>
      <th>L7</th>
      <td><code>2d10</code></td>
      <th>L10</th>
      <td><code>3d12</code></td>
    </tr>
    <tr>
      <th>L2</th>
      <td><code>1d6</code></td>
      <th>L5</th>
      <td><code>2d6</code></td>
      <th>L8</th>
      <td><code>2d12</code></td>
      <th>L11</th>
      <td><code>4d10</code></td>
    </tr>
    <tr>
      <th>L3</th>
      <td><code>1d8</code></td>
      <th>L6</th>
      <td><code>2d8</code></td>
      <th>L9</th>
      <td><code>3d10</code></td>
      <th>L12</th>
      <td><code>4d12</code></td>
    </tr>
  </tbody>
</table>

## Powers and Items
Characters can use special powers and items to as bonus points to action rolls or extra damage to damage dice rolls based on their level and the power/item's rank. Characters have 6 powers and can carry up to `10+STR` items at a time.

|  | F | D | C | B | A | S |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Stat** | `+/-1` | `+/-2` | `+/-3` | `+/-4` | `+/-5` | `+/-6` |
| **Max HP** | `4d4` | `6d6` | `8d8` | `10d10` | `12d12` | `10d20` |
| **DMG** | `1d4` | `1d6` | `1d8` | `1d10` | `1d12` | `1d20` |

### Limits and Consequences
Bonuses from powers and items can only be used a limited number of times per long rest (8 hours) based on your level. To find the limit for a rank, divide your level by the stat bonus (rounded down).

If you exceed the limit for an item, roll damage and reduce the item's HP by the result. Items with zero HP break and their bonuses cannot be used until it is repaired by someone qualified.

If you exceed the limit for a power, roll damage as a consumable (see below) and reduce your own HP by the result. Dealing in powers you cannot control can have devastating consequences!

### Consumables and Obstacles
When rolling damage for consumable (one-use) items or obstacles (as a GM), roll one of each lower rank's damage dice and add it to the damage for the rank instead of rolling regular damage. For example, a D-rank potion heals `1d4+1d6` HP regardless of the character's level.