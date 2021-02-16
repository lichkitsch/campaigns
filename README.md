# DNDuet Core Rules
_DNDuet_ is a simple, flexible system for building and playing custom tabletop RPGs. These rules work with as few as one game master (GM) and one player and have been built around the standard RPG dice set.

## Action Rolls

When the outcome of a character’s action is uncertain, roll `1d20+trait` against the target, set by the GM. If your result is higher the outcome is positive and if not, the outcome is negative. If the result is equal to the target, the positive outcome carries a cost.

When creating a character, roll `1d4-2` for the following:

| Trait | Uses |
|:---:|:--- |
| Strength | Athletics, muscle, melee attacks |
| Dexterity | Acrobatics, stealth, finesse |
| Constitution | Endurance, resistance |
| Intelligence | Memory, logic, investigation |
| Wisdom | Intuition, perception, ranged attacks |
| Charisma | Performance, persuasion, deception |

You can rearrange these rolls once. When you level up add 1 point to any one trait lower than 5.

## Heart Points

Characters, along with many items and obstacles, have a resource called **heart points (HP)** which represents their overall integrity. After a successful action roll against a target, roll your level-specific **damage dice** and reduce their HP by the result. When HP reaches zero items break, obstacles are overcome, and characters suffer a major narrative setback.

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

Characters start with 10 max HP at L1. After every 2 hours of rest roll your damage dice to regain lost HP. When you level up, roll your new damage to increase your max HP.

## Items

Characters collect useful items that provide bonus points to specific rolls. Items that provide a fixed bonus to a specific action or damage roll is called **equipment**. Equipment has max HP and takes damage on a negative outcome, and if a piece of equipment reaches zero HP it breaks and cannot be used until it is repaired by someone qualified. **Consumables** are limited-use items that take up an action and either give a one-time bonus to specific action rolls or deal damage as listed on the table below:

### Item Ratings

| Rating | Bonus | Max HP | Damage | Quality |
|:---:|:---:|:---:|:---:|:---:|
| F | +1 | `4d4` | `1d4` | Poor |  
| D | +2 | `6d6` | `F+1d6` | Fair |
| C | +3 | `8d8` | `D+1d8` | Decent |
| B | +4 | `10d10` | `C+1d10` | Good |
| A | +5 | `12d12` | `B+1d12` |  Great |
| S | +6 | `20d20` | `A+1d20` | Epic |

## Abilities

Abilities are bonuses based on physical features, experience, study, training, divine gifts, etc. They can be combined with equipment in the right circumstances, but if you use an ability with an item for maximum effect, the item may take damage. Characters start with one "reroll" ability at L1, allowing them to reroll a specific action or damage for a chance at a better outcome. The GM may grant a character temporary or even permanent abilities as the result of specific narrative events, but characters also unlock class-based abilities at every even-numbered level:

| L2 | L4 | L6 | L8 | L10 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `1d12` | `1d20` |
