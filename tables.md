# *DNDuet* Tables

## Damage Dice by Level

| L1 | L2 | L3 | L4 | L5 | L6 | L7 | L8 | L9 | L10 | L11 | L12 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `1d4` | `1d6` | `1d8` | `1d10` | `2d6` | `2d8` | `2d10` | `2d12` | `3d10` | `3d12` | `4d10` | `4d12` |

The player rolls their new damage dice when gaining a level to increase their max HP. Roll your damage dice after every 2 hours of rest to reestore lost HP.

## Item and Ability Ranks

| Rank | Bonus | Damage | Max HP | Ability | Value | Level |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `F` | +1 | `1d4` | `4d4` | `+1d4` | `d100 * 0.1` | 1/2/3 |
| `D` | +2 | `F+1d6` | `6d6` | `+1d6` | `d100` | 4/5 |
| `C` | +3 | `D+1d8` | `8d8` | `+1d8` | `d100 * 10` | 6/7 |
| `B` | +4 | `C+1d10` | `10d10` | `+1d10` | `d100 * 100` | 8/9 |
| `A` | +5 | `B+1d12` | `12d12` | `+1d12` | `d100 * 1000` | 10/11 |
| `S` | +6 | `A+1d20` | `20d20` | `+1d20` | `d100 * 10k` | 12 |

Consumables have their own damage dice, deal damage to themselves equal to the effect they have when used, and run empty when their HP reaches zero. Other items that reach zero HP break, but can usually be repaired by someone qualified. Most obstacles and NPCs are created as items; they roll `1d20+bonus` against the player, deal damage like a consumable item, and are no longer a threat when their HP reaches zero. Some NPCs are created like player characters with damage dice, items, and abilities all their own.

## Damage Types and Conditions

| Type | Source | Condition | Effect |
|:--- |:---:|:---:|:--- |
| 👊 Crushing | Blunt objects, gravity, sound | *Broken* | Take damage when moving until healed |
| ⚔️ Slashing | Blades, whips, saws | *Bleeding* | Take damage each turn until wound is sealed |
| 🏹 Piercing | Arrows, spears, bullets | *Pinned* | Roll `STR > 10` to break free or take damage |
| 🔥 Fire | Flames, explosions | *Burned* | Subsequent blows to burned area deal double damage |
| ❄️ Cold | Frost, water, darkness | *Frozen* | Roll `CON > 10` to move successfully or take damage |
| ⚡️ Shock | Lightning, electricity | *Paralyzed* | Drop held weapons and lose a turn |
| 💉 Poison | Harmful substances | *Poisoned* | Take damage each turn until cured with antidote |
| 💀 Necrotic | Acid, disease, death | *Cursed* | Take damage each turn until curse is removed |
| ☀️ Radiant | Light, divine energy | *Blinded* | Automatically fail actions that require sight |
| ♥️ Psychic | Mental/emotional trauma | *Confused* | Roll `WIS > 10` to make any action until rested |

Conditions are applied to a target when the attacker rolls a natural 20.

## Spellcraft

| School | Description | Components |
|:--- |:--- |:---:|
| 🔴 Destruction | Inflict damage through a magical medium | Fire, Earth |
| 🟠 Conjuration | Summon objects and creatures from elsewhere | Fire, Water |
| 🟡 Abjuration | Protect against damage, bad luck, or ill will | Earth, Air |
| 🟢 Restoration | Restore an object to a past iteration | Earth, Water |
| 🔵 Alteration | Change an object's properties | Fire, Air |
| 🟣 Divination | Reveal hidden information | Water, Air |

| Components | Fire | Earth | Water | Air |
|:---:|:---:|:---:|:---:|:---:|
| Physical | Candles, alcohol, ash, heat, spices, flames, blades, meat | Dirt, sand, stone, gems, crystals, oil, hammers, bones | Water, rain, ice, snow, cups, ink, whips, blood | Feathers, plants, seeds, scrolls, wands, staves, arrows, breath, wind |
| Abstract | Dance, sex, specific movements | Burying, grinding, specific locations | Submerging, drinking, specific times | Breathing, eating, language |

Spells require one physical component, one abstract component, and concentration (`WIS > 10`) to cast. Spells can be cast and contained in potions, scrolls, and other items and used at a later time without needing to spend the components or concentration during the action.

### Spell Elements, Forms, and Creatures

| ID | Element | Form | Creature |
|:---:|:---:|:---:|:---:|
| 1 | Acid |	Arc |	Ant |
| 2 | Aether |	Assassin | Ape |
| 3 | Air | Aura |	Badger |
| 4 | Alabaster | Bastion | Bat |
| 5 | Amber | Beacon | Bear |
| 6 | Ash | Beam | Beaver |
| 7 | Bat | Beast | Bee |
| 8 | Battle |	Blade | Beetle |
| 9 | Beetle |	Blast | Boar |
| 10 | Bile |	Blob | Bulldog |
| 11 | Blight |	Bolt | Butterfly |
| 12 | Blood | Bubble | Camel |
| 13 | Bone |	Burst | Cat |
| 14 | Brimstone | Call | Centipede |
| 15 | Brine | Cascade | Chameleon |
| 16 | Bronze |	Circle | Cobra |
| 17 | Chaos | Cloud | Cockroach |
| 18 | Clay |	Coil | Constrictor |
| 19 | Copper |	Colossus | Cougar |
| 20 | Crow |	Column | Cow |
| 21 | Crystal | Cone | Coyote |
| 22 | Death | Crystal | Crab |
| 23 | Doom |	Cube | Crane |
| 24 | Dream | Disk | Cricket |
| 25 | Dust |	Elemental |	Crocodile |
| 26 | Earth | Emanation |	Crow |
| 27 | Echo |	Enclosure |	Donkey |
| 28 | Energy |	Explosion |	Dragonfly |
| 29 | Fire |	Eye	| Duck |
| 30 | Flame | Face |	Eagle |
| 31 | Flesh | Field | Eel |
| 32 | Fog | Fist | Elephant |
| 33 | Fungus |	Fountain | Elk |
| 34 | Ghost | Gate | Falcon |
| 35 | Glass | Gaze |	Ferret |
| 36 | Gold |	Grip | Firefly |
| 37 | Heat |	Gush | Fox |
| 38 | Honey | Halo | Frog |
| 39 | Ice | Hand |	Goat |
| 40 | Ichor | Heart | Goose |
| 41 | Insect |	Helix | Hare |
| 42 | Iron |	Image | Hart |
| 43 | Ivory | Laugh | Hawk |
| 44 | Jade |	Lock | Hedgehog |
| 45 | Lava |	Loop | Hornet |
| 46 | Light | Maze | Horse |
| 47 | Lightning | Moment |	Hound |
| 48 | Loam |	Monolith | Hummingbird |
| 49 | Marmalade | Mount | Jackal |
| 50 | Miasma |	Mouth | Jellyfish |
| 51 | Milk |	Nexus | Leech |
| 52 | Mist |	Oracle | Lion |
| 53 | Moss |	Path | Locust |
| 54 | Mud | Pattern | Lynx |
| 55 | Mutation |	Plane | Mantis |
| 56 | Nectar | Portal | Mastodon |
| 57 | Night | Prism | Mockingbird |
| 58 | Nightmare | Pulse | Mole |
| 59 | Obsidian |	Puppet | Monkey |
| 60 | Oil | Pyramid | Moose |
| 61 | Plague |	Ray |	Moth |
| 62 | Poison |	Rift | Mouse |
| 63 | Power | Road | Mule |
| 64 | Psyche |	Scream | Octopus |
| 65 | Quicksilver | Seal | Otter |
| 66 | Rain |	Sentinel | Owl |
| 67 | Rat | Servant | Ox |
| 68 | Rose |	Shard |	Panther |
| 69 | Rot |	Shield | Pig |
| 70 | Rust |	Shroud | Pony |
| 71 | Salt |	Sigil | Porcupine |
| 72 | Sand |	Song | Possum |
| 73 | Sap | Sphere | Rabbit |
| 74 | Serpent | Spiral |	Raccoon |
| 75 | Shadow |	Splinter | Rat |
| 76 | Silver |	Spray | Reindeer |
| 77 | Skin |	Storm | Rooster |
| 78 | Slime | Stream |	Salamander |
| 79 | Smoke | Strike | Scorpion |
| 80 | Snow |	Swarm |	Seal |
| 81 | Souls | Tendril | Shark |
| 82 | Spirit |	Tentacle | Sheep |
| 83 | Star |	Throne | Slug |
| 84 | Steam | Tongue | Snail |
| 85 | Stench |	Torrent | Sparrow |
| 86 | Stone | Touch | Spider |
| 87 | Sun | Tower | Squid |
| 88 | Tar | Trap | Squirrel |
| 89 | Thorn | Tree |	Tiger |
| 90 | Thunder | Tunnel |	Toad |
| 91 | Treasure |	Veil | Turtle |
| 92 | Venom | Voice |	Viper |
| 93 | Vine |	Vortex | Vulture |
| 94 | Void |	Wall | Walrus |
| 95 | Water | Ward | Weasel |
| 96 | Wind |	Wave | Whale |
| 97 | Wine |	Web | Wolf |
| 98 | Winter |	Whisper | Wolverine |
| 99 | Wood |	Word | Worm |
| 100 | Worm |	Zone | Zebra |

## Buying Items

| Category | Merchant | Goods |
|:---:| ---:|:--- |
| Food | Hunter | Game meat (squirrel, venison, etc.), game fish, wild poultry (quail, pheasant, pigeon, turkey), mushrooms |
|  | Grocer | Canned goods, boxed goods, frozen goods, candy, honey, maple syrup, dry ingredients (beans, rice, oats, coffee, tea, sugar, dried fruit) |
|  | Fishmonger | Fresh fish, game fish, salted fish, smoked fish, shellfish, crustaceans, shells, coral, pearls |
|  | Farmer | Fresh fruit, fresh vegetables, jams, jellies, pickles, eggs, milk, cheese, butter, honey, livestock |
|  | Baker | Bread loaves, bread rolls, cakes, pies, prepared mixes |
|  | Brewer | Tonic, mead, ale, rum, wine, moonshine, etc. |
|  | Butcher | Beef, lamb, mutton, goat, raised poultry (chicken, turkey), sausages |
|  | Street Vendor | Roasted meats, fried bread, sweet treats, etc. |
|  | Innkeep | Tavern meal (bread, cheese, meat, fruit/veggie), live music, rumors, accomodations |
| Clothing | Tailor | Hats, tops, bottoms, dresses, coats, cloaks, capes, robes, undergarments, socks, shoes, furs, etc. |
|  | Jeweler | Clips, rings, pins, cuffs, necklaces, bracelets, anklets, etc. |
|  | Armorer | Helms, plates, pauldrons, greaves, gauntlets, etc. |
| Tools | Blacksmith | Metal-forged weapons (daggers, swords, axes, spears, mauls, maces, flails, etc.) and tools (traps, hammers, nails, screws, etc.) |
|  | Bower/Atilliator | Bows, arrows, crossbows, bolts |
|  | General Store | Climbing gear, camping gear, cookware, writing tools, containers, personal effects (canes, pipes, hygiene, makeup, etc.) |
|  | Toy Store | Cards, dice, puzzles, puppets, dolls, marbles, whistles, magic kits, costumes, etc. |
|  | Luthier | Instrument cases, string instruments (lute, lyre, violin, etc.), wind instruments (flutes, pipes, horns, etc.), percussion instruments (bells, drums, etc.) |
|  | Alchemist | Balms, baths, compresses, creams, decoctions, drops, elixirs, extracts, infusions, lotions, oils, perfumes, phials, philtres, pills, potions, poultices, powders, salves, soaks, soap, spices, sprays, syrups, tablets, teas, tinctures, satchets |
|  | Herbalist/Apothecary | Drugs, chemicals, potions, herb satchets, pills, tablets, powders |
|  | Thief | Glasscutter, prybar, grappling hook, lockpicks, disguises, etc. |
|  | Artificer | Mechanical weapons (guns, cannons, lasers), traps, sensors, constructs, etc. |
| Raw Material | Gemcutter | Amber, amethyst, aquamarine, azurite, banded agate, bloodstone, carnelian, coral, yellow diamond, pink diamond, blue diamond, white diamond, emerald, garnet, hematite, iolite, jade, jasper, jet, lapis lazuli, malachite, moonstone, obsidian, onyx, opal, freshwater pearl, pearl, black pearl, peridot, quartz, rose quartz, ruby, sapphire, sardonyx, spinel, tiger's eye, topaz, tourmaline, turqouise, zircon |
|  | Miner | Stone, gravel, ore (iron, copper, silver, gold) |
|  | Witch | Plants, herbs, flowers, leaves, crystals, potions, satchets, scrolls |

## 
