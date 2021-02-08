# DNDuet Core Rules
_DNDuet_ is a simple, flexible system for building and playing custom tabletop RPGs. These rules work with as few as one game master (GM) and one player and have been built around the standard RPG dice set.

## Action Rolls

When the outcome of a character’s action is uncertain, roll `1d20+trait` against the target, set by the GM. If your result is higher the outcome is positive and if not, the outcome is negative. If the result is equal to the target, the positive outcome carries a cost.

When creating a character, roll `1d4-2` for the following:

| Trait | Uses |
|:---:|:--- |
| Strength | Athletics, muscle, melee attacks |
| Dexterity | Acrobatics, stealth, finesse |
| Constitution | Durability, physical resistance |
| Intelligence | Memory, logic, investigation |
| Wisdom | Intuition, perception, ranged attacks |
| Charisma | Performance, persuasion, deception |

You can rearrange your starting trait scores once. When you level up, add 1 point to any one trait with a score lower than 5.

## Heart Points

Characters, along with many items and obstacles, have a resource called **heart points (HP)** which represents their overall integrity. After a successful action roll against a target, roll your level-specific **damage dice** and reduce their HP by the result. When HP reaches zero equipment breaks, obstacles are overcome, and characters suffer a major narrative setback.

### Damage Dice by Level

<table>
  <tbody>
    <tr>
      <th>L1</th>
      <td><code>1d4</code></td>
      <th>L2</th>
      <td><code>1d6</code></td>
      <th>L3</th>
      <td><code>1d8</code></td>
      <th>L4</th>
      <td><code>1d10</code></td>
    </tr>
    <tr>
      <th>L5</th>
      <td><code>2d6</code></td>
      <th>L6</th>
      <td><code>2d8</code></td>
      <th>L7</th>
      <td><code>2d10</code></td>
      <th>L8</th>
      <td><code>2d12</code></td>
    </tr>
    <tr>
      <th>L9</th>
      <td><code>3d10</code></td>
      <th>L10</th>
      <td><code>3d12</code></td>
      <th>L11</th>
      <td><code>4d10</code></td>
      <th>L12</th>
      <td><code>4d12</code></td>
    </tr>
  </tbody>
</table>

Characters start with 10 max HP at L1. Roll your damage to regain lost HP after every 2 hours of rest. When you level up, roll your new damage to increase your max HP.

## Items

During the game, characters will collect useful items that provide either a fixed bonus to a specific action or damage roll or independent damage dice (not added to a damage roll) when used on a target. Some items have their own HP and take damage on a negative outcome or when added to an ability bonus, and if a piece of equipment reaches zero HP it breaks and cannot be used until it is repaired by someone qualified. Items take up an action; if you use an item to deal or heal damage it counts as your turn.

### Item Ratings

| Rating | Bonus | Max HP | DMG | Value | Quality |
|:---:|:---:|:---:|:---:|:---:|:---:|
| F | +1 | `4d4` | `1d4` | x0.01 | Poor |  
| D | +2 | `6d6` | `F+1d6` | x0.1 | Fair |
| C | +3 | `8d8` | `D+1d8` | x1 | Decent |
| B | +4 | `10d10` | `C+1d10` | x10 | Good |
| A | +5 | `12d12` | `B+1d12` | x100 |  Great |
| S | +6 | `20d20` | `A+1d20` | x1000 | Epic |

For value, roll percentage dice (`1d00+1d10`, 00 and 0 equals 100) and multiply the result as listed.

## Abilities

Abilities are bonuses based on physical features, experience, study, training, divine gifts, etc. The GM may grant a character temporary or even permanent abilities thanks to specific narrative events, but characters also unlock new abilities at every even-numbered level. Characters start with one `1d4` ability at L1 and gain the following bonus dice to specific action or damage rolls:

| L2 | L4 | L6 | L8 | L10 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `1d12` | `1d20` |

For example, at L1 characters with dragon ancestry could start with a breath weapon that deals `DMG+1d4` when used. Players can also decide to improve an existing ability, such as the dragonborn upgrading their breath weapon to `DMG+1d6` at L4. In this case, the GM should allow the player to take a new `d4` ability in its place.
