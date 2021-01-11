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

Characters, along with many items and obstacles, have a resource called **heart points (HP)** which represents their overall integrity. After a successful action roll against a target, roll your level-specific **heart dice (HD)** and reduce their HP by the result. If an obstacle's HP reaches zero it is no longer a threat. If a character’s HP reaches zero they suffer a major narrative setback.

### Heart Dice by Level

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

Characters start with 10 max HP at L1. Roll your HD to regain lost HP after every 2 hours of rest. When you level up, roll your new HD to increase your max HP.

## Items & Inventory

Players can add bonus dice to specific actions and HD rolls using items such as tools, weapons, wearables, and consumables. Non-consumable items have HP and take HD damage on a negative outcome. If the item's HP reaches zero it breaks and cannot be used until if is repaired by someone qualified.

| Levels | Bonus | Max HP | Value | Rarity |
|:---:|:---:|:---:|:---:|:---:|
| 1-3 | `d4` | `4d4` | x0.01 | Abundant |
| 4, 5 | `d6` | `6d6` | x0.1 | Common |
| 6, 7 | `d8` | `8d8` | x1 | Uncommon |
| 8, 9 | `d10` | `10d10` | x10 | Rare |
| 10, 11 | `d12` | `12d12` | x100 |  Epic |
| 12 | `d20` | `20d20` | x1000 | Legendary |

If a consumable item affects HP, roll the bonus die and one of each lesser dice and add up the total instead of adding your own HD roll. For value, roll percentage dice (`1d00+1d10`, 00 and 0 equals 100) and multiply the result as listed.

## Abilities

Abilities are bonuses to specific rolls based on physical features, experience, study, training, divine gifts, etc. They can sometimes be combined with items in the right circumstances, but if you use an ability with an item and the roll fails you must add the ability bonus when rolling damage for the item.

Characters start with one `d4` ability and unlock abilities specific to their class/job/etc with every even numbered level:

| L1 | L2 | L4 | L6 | L8 | L10 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `d4` | `d4` | `d6` | `d8` | `d10` | `d12` | `d20` |

Sometimes the GM may grant a character temporary or even permanent abilities thanks to specific narrative events.
