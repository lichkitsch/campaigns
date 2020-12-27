# DNDuet Core Rules
_DNDuet_ is a simple, flexible system for building and playing custom tabletop RPGs. These rules work with as few as one game master (GM) and one player and have been built around the standard RPG dice set.

## Action Rolls

When the outcome of a character’s action is uncertain, roll `1d20+stat` against the obstacle. If your result is higher the outcome is positive and if not, the outcome is negative. Ties result in a mixed outcome. When creating a character, roll `1d4-2` for the following stats:

| Stat | Abbr. | Use |
|:---:|:---:|:--- |
| Strength | `STR` | Athletics, muscle, melee attacks |
| Dexterity | `DEX` | Acrobatics, stealth, finesse |
| Constitution | `CON` | Health, endurance, stamina |
| Intelligence | `INT` | Memory, logic, investigation |
| Wisdom | `WIS` | Intuition, perception, ranged attacks |
| Charisma | `CHA` | Performance, persuasion, deception |

You can rearrange stats once. When you level up, you can spend 1 point on any one stat lower than 5.

## Heart Points

Characters, along with many items and obstacles, have a stat called **heart points (HP)** which represents their overall integrity. After a successful action roll against a target, roll your level-specific **heart dice** and reduce their HP by the result. If a character’s HP reaches zero they suffer a major setback like imprisonment, severe injury, or even death.

### Heart Dice by Level

<table>
  <tbody>
    <tr>
      <th>L1</th>
      <td><code>1d4</code></td>
      <th>L5</th>
      <td><code>2d6</code></td>
      <th>L9</th>
      <td><code>3d10</code></td>
    </tr>
    <tr>
      <th>L2</th>
      <td><code>1d6</code></td>
      <th>L6</th>
      <td><code>2d8</code></td>
      <th>L10</th>
      <td><code>3d12</code></td>
    </tr>
    <tr>
      <th>L3</th>
      <td><code>1d8</code></td>
      <th>L7</th>
      <td><code>2d10</code></td>
      <th>L11</th>
      <td><code>4d10</code></td>
    </tr>
    <tr>
      <th>L4</th>
      <td><code>1d10</code></td>
      <th>L8</th>
      <td><code>2d12</code></td>
      <th>L12</th>
      <td><code>4d12</code></td>
    </tr>
  </tbody>
</table>

Characters start with 10 max HP at level 1. When you level up, roll your new heart dice and add the result to your max HP.

## Items & Abilities

Characters can carry `10+STR` items and have limited ability slots per rank based on their level. Items and abilities use the following ranks:

|  | Stat Buff | Heart Dice | Item HP | Value |
|:---:|:---:|:---:|:---:|:---:|
| **F** | `+/- 1` | `1d4` | `4d4` | `1d10` cp |
| **D** | `+/- 2` | `1d6` | `6d6` | `1d10` sp |
| **C** | `+/- 3` | `1d8` | `8d8` | `1d10` gp |
| **B** | `+/- 4` | `1d10` | `10d10` | `1d10` pp |
| **A** | `+/- 5` | `1d12` | `12d12` | `1d10` gems |
| **S** | `+/- 6` | `1d20` | `20d20` | `1d10` jewels |

Items take damage on failed rolls, break when they reach zero HP, and can only be repaired by someone qualified. Consumable items add each lower rank’s heart dice rather than adding your own roll. Abilities require specific stats, use slots (`Level / Stat Buff`), and are gained through experience, study, training, etc.
