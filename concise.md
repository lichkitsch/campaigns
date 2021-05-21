# *DNDuet* Tables

## Damage Dice by Level

| L1 | L2 | L3 | L4 | L5 | L6 | L7 | L8 | L9 | L10 | L11 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `2d6` | `2d8` | `2d10` | `2d12` | `3d10` | `3d12` | `4d10` | `4d12` |

## Item and Ability Ranks
Obstacles are created as items. Consumables deal damage to themselves equal to the effect they have and run empty when their HP reaches zero. Other items that reach zero HP break but can usually be repaired by someone qualified.

| Rank | Bonus | Damage | Max HP | Ability | Value | Level |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `F` | +1 | `1d4` | `4d4` | `+1d4` | `d100 * 0.1` | 1/2/3 |
| `D` | +2 | `F+1d6` | `6d6` | `+1d6` | `d100` | 4/5 |
| `C` | +3 | `D+1d8` | `8d8` | `+1d8` | `d100 * 10` | 6/7 |
| `B` | +4 | `C+1d10` | `10d10` | `+1d10` | `d100 * 100` | 8/9 |
| `A` | +5 | `B+1d12` | `12d12` | `+1d12` | `d100 * 1000` | 10/11 |
| `S` | +6 | `A+1d20` | `20d20` | `+1d20` | `d100 * 10k` | 12 |

## Damage Types and Conditions
Conditions are applied to a target when the attacker rolls a natural 20.

| Type | Source | Condition | Effect |
|:---:|:---:|:---:|:--- |
| 👊 Crushing | Blunt objects, gravity, sound | *Broken* | Take damage when moving until healed |
| ⚔️ Slashing | Bladed weapons | *Bleeding* | Take damage each turn until wound is sealed |
| 🏹 Piercing | Arrows, spears, bullets | *Pinned* | Roll `STR > 10` to break free or take damage |
| 🔥 Fire | Flames, explosions | *Burned* | Subsequent blows to burned area deal double damage |
| ❄️ Cold | Frost, water, darkness | *Frozen* | Roll `CON > 10` to move successfully or take damage |
| ⚡️ Shock | Lightning, electricity | *Paralyzed* | Drop held weapons and lose a turn |
| 💉 Poison | Harmful substances | *Poisoned* | Take damage each turn until cured with antidote |
| 💀 Necrotic | Acid, disease, death | *Cursed* | Take damage each turn until curse is removed |
| ☀️ Radiant | Light, divine energy | *Blinded* | Automatically fail actions that require sight |
| ♥️ Psychic | Mental/emotional trauma | *Confused* | Roll `WIS > 10` to make any action until rested |
