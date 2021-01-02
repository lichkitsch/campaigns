# DNDuet Core Rules
_DNDuet_ is a simple, flexible system for building and playing custom tabletop RPGs. These rules work with as few as one game master (GM) and one player and have been built around the standard RPG dice set.

## Action Rolls

When the outcome of a character’s action is uncertain, roll `1d20+stat` against the GM. If your result is higher the outcome is positive and if not, the outcome is negative. Ties result in a mixed outcome. When creating a character, roll `1d4-2` for the following stats:

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

Characters, along with many items and obstacles, have a stat called **heart points (HP)** which represents their overall integrity. After a successful action roll against a target, roll your level-specific **heart dice (HD)** and reduce their HP by the result. If an obstacle's HP reaches zero it is no longer a threat. If a character’s HP reaches zero they suffer a major narrative setback.

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

Characters start with 10 max HP at L1. Roll HD to regain HP every 2 hours of rest. When you level up, roll your new HD and add the result to your max HP.

## Items & Inventory

Players can add bonus dice to specific actions and HD rolls using items such as tools, weapons, wearables, and consumables. Characters can carry `10+STR` items at a time, though smaller items can sometimes stack. Non-consumable items have HP and take HD damage when used on a failed action. If the item's HP reaches zero it breaks and cannot be used until repaired by someone qualified (based on it's rating).

|  | `d4` | `d6` | `d8` | `d10` | `d12` | `d20` |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Max HP** | `4d4` | `6d6` | `8d8` | `10d10` | `12d12` | `20d20` |
| **Cost** | x0.1 | x1 | x10 | x100 | x1000 | x10000 |

If a consumable item affects HP, roll the bonus die and one of each lesser dice and add up the total instead of adding your own HD roll. For cost, roll percentage dice (`1d10` and `1d00`) and multiply the result as listed.

## Abilities

Abilities are based on physical features, experience, study, training, divine gifts, etc. They have a similar effect as items, and can sometimes be combined with items in the right circumstances, but if you use an ability with an item and the roll fails you mist add the ability bonus when rolling damage for the item.

Abilities are equipped by spending **ability points (AP)**. Characters start with 5 AP and one `d4` ability at L1 and gain 3 AP with every level up. Some abilities are gifted by the GM based on events in the story, but characters also unlock abilities specific to their class/job/etc on every even-numbered level:

| L1 | L2 | L4 | L6 | L8 | L10 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `d4` | `d4` | `d6` | `d8` | `d10` | `d12` | `d20` |

Abilities cost the same amount of AP to equip as the number of sides on their bonus die. At L2 you can equip both of your `d4` abilities, but at higher levels you'll have to be more strategic. You can switch around your abilities during times of rest.
