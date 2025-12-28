# PD2 rafineria mod single player

#### This mod fixes a few stupid PD2 balance decisions and makes the single-player gameplay more fun (not balanced).

## Install
Put `data` folder and `default.filter` in `C:\Program Files (x86)\Diablo II\ProjectD2\` directory. Create shortcut of `C:\Program Files (x86)\Diablo II\ProjectD2\Diablo II.exe` and start with `-direct -txt -3dfx`.

Loot filter is vanilla friendly. It's for people who don't like to use it but also they don't want to swim in garbage.

## General changes
- Higher chance of dropping high runes (not very noticeable, but finding a Zod should be slightly less painful)
- All skills can be used in town
- Experience gain is easier after level 90
- Mercenary inventory: 1 ring and 1 amulet
- Charms can be rare
- Sockets are possible in belts, boots, gloves, rings, and amulets
    - Sockets in rings and amulets work like in weapons (e.g., a ruby socket grants fire damage)
- The Countess rune drop chance is slightly increased and can drop up to:
    - **Normal:** Thul (Ral in vanilla)
    - **Nightmare:** Lem (Io in vanilla)
    - **Hell:** Ber (Ist in vanilla)

## Skills
- **Revive**
    - Changed max number of revives. Now it's like in vanilla so max number of revives is the number of Revive skill soft points.
    - Changed HP from [100%] to [200% + (hard point * 20)]
    - Changed duration/level from [10s/level] to [20s/level]

- **Jab**
    - **Fend:** +18% Damage per Level <span style="color:red;">>></span> +20% Damage per Level  
    - **Damage start:** 30% <span style="color:red;">>></span> 50%  
    - **Damage per level:** 20% <span style="color:red;">>></span> 30%  

- **Javelin and Spear Mastery**
    - **Damage start:** 40% <span style="color:red;">>></span> 50%  
    - **Damage per level:** 15% <span style="color:red;">>></span> 20%

- **Raven**
    - Attacks per level: 0 <span style="color:red;">>></span>  Attacks per level: 1

- **Inferno**
    - **Blaze:** +20% Fire Damage per Level <span style="color:red;">>></span> +30% Fire Damage per Level
    - **Fire Wall:** +20% Fire Damage per Level <span style="color:red;">>></span> +30% Fire Damage per Level

- **Meteor**
    - 1.13c

- **Fire Ball**
    - Combustion: +15% Fire Damage per Level <span style="color:red;">>></span> Meteor: +15% Fire Damage per Level

- **Combustion**
    - Cooldown: 2.5 sec <span style="color:red;">>></span> 1.2 sec

- **Fire Mastery**
    - 4% Damage bonus per level <span style="color:red;">>></span> 8% Damage bonus per level
    - Fire pierce changed (`min((29*(lvl-1))/19 + 1, 40)`):

    | Level | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 | 33 | 34 | 35 |
    |-------------|---|---|---|---|---|---|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
    | Fire pierce | 1 | 3 | 4 | 6 | 7 | 9 | 10 | 12 | 13 | 15 | 16 | 18 | 19 | 21 | 22 | 24 | 25 | 27 | 28 | 30 | 32 | 33 | 35 | 36 | 38 | 39 | 40 | 40 | 40 | 40 | 40 | 40 | 40 | 40 | 40 |

- **Cold Mastery**
    - lower resist per level: 1 <span style="color:red;">>></span> 2
    - max lower resist: 45 <span style="color:red;">>></span> 80


## Armor:
- Increased armor rating of elite belts, boots and gloves
- Rebalanced str req of elite belts, boots and gloves
- Increased armor of paladin shields and barb helms
- Increased damage of paladin elite shields
- Decreased str req of several items that had it too high (but increased few that had it too low)
- Increased armor of few items that had it too low (especially elite armors to match missing ETH bug)


## Recipes:
Please use socket recipes after corrupting the item

- rare jewel + any weapon + [1-6] Perfect Amethyst => [1-6] socketed same weapon
- rare jewel + any armor  + [1-4] Perfect Topaz    => [1-4] socketed same armor
- rare jewel + any helm   + [1-4] Perfect Sapphire => [1-4] socketed same helm
- rare jewel + any shield + [1-4] Perfect Ruby     => [1-4] socketed same shield
- rare jewel + any boots  + [1-4] Perfect Emerald  => [1-4] socketed same boots
- rare jewel + any gloves + [1-4] Perfect Diamond  => [1-4] socketed same gloves
- rare jewel + any belt   + [1-2] Perfect Skull    => [1-2] socketed same belt
- rare jewel + any ring   + 1 rare jewel           => 1     socketed same ring
- rare jewel + any amulet + 1 rare jewel           => 1     socketed same amulet
- any socketed item + Ist Rune                     => the same item without runes (runes are lost)
- 10 magic jewel                                   => 1 rare jewel
- 3 rare jewel                                     => 1 rare jewel
- 3 rare ring                                      => 1 rare ring
- 3 rare amulet                                    => 1 rare amulet
- 10 small charms                                  => 1 rare small charm
- 8 medium charms                                  => 1 rare medium charm
- 3 rare big charms                                => 1 rare big charm

## Runewords (weapons):
#### Edge:
- Reduces All Vendor Prices 15% > added
#### Spirit:
- +[25-35]% Faster Cast Rate > +[30-35]% Faster Cast Rate
#### Obedience:
- +[280-320]% Enhanced Damage > +[320-370]% Enhanced Damage
#### Passion: 
- +25% Increased Attack Speed > +30% Increased Attack Speed
- +[160-210]% Enhanced Damage > +[200-230]% Enhanced Damage
#### Voice of Reason: (even after the buff it is still very garbage, but not completely useless)
- +[240-300]% Damage to Demons > +[300-350]% Damage to Demons
- +[280-325]% Damage to Undead > +[300-350]% Damage to Undead
- Adds 200-320 Cold Damage > Adds 500-800 Cold Damage
- 15% Chance to Cast Level 16 Frozen Orb on Striking > 33% Chance to Cast Level 16 Frozen Orb on Striking
- 18% Chance to Cast Level 20 Ice Blast on Striking > 33% Chance to Cast Level 20 Ice Blast on Striking
#### Lawbringer:
- +[150-200]% Enhanced Damage > +200% Enhanced Damage
#### Crescent Moon:
- -[10-15]% to Enemy Lightning Resistance > -35% to Enemy Lightning Resistance
#### Rift:
- Adds 160-250 Magic Damage > Adds 200-250 Magic Damage
- Adds 60-180 Fire Damage > Adds 200-250 Fire Damage
- 26% Chance to Cast Level 30 Tornado on Striking > 33% Chance to Cast Level 30 Tornado on Striking
- 24% Chance to Cast Level 25 Frozen Orb on Striking > 33% Chance to Cast Level 25 Frozen Orb on Striking
#### Heart of the Oak:
- +30% Faster Cast Rate > +40% Faster Cast Rate
#### Death:
- +[275-320]% Enhanced Damage > +[300-385]% Enhanced Damage
#### Chaos:
- 20% Chance to Cast Level 30 Frozen Orb on Striking > 33% Chance to Cast Level 30 Frozen Orb on Striking
- 18% Chance to Cast Level 40 Charged Bolt on Striking > 33% Chance to Cast Level 40 Charged Bolt on Striking
- +[200-250]% Enhanced Damage > +[300-350]% Enhanced Damage
#### Grief: (it is still not even close to the original Grief but as least now it deals decent damage)
- Adds 280 to [320-360] Damage > Adds 400 to 550 Damage
- Ignore Target's Defense > added
#### Eternity:
- +[260-310]% Enhanced Damage > +[300-400]% Enhanced Damage
#### Fury:
- +[239-299]% Enhanced Damage > +[300-350]% Enhanced Damage
#### Brand:
- 65% Chance to Cast Level 31 Amplify Damage when Struck > 75% Chance to Cast Level 50 Amplify Damage when Struck
#### Last Wish:
- 10% Chance to Cast Level 11 Life Tap on Striking > 	25% Chance to Cast Level 11 Life Tap on Striking
- 6% Chance to Cast Level 11 Fade when Struck > 15% Chance to Cast Level 11 Fade when Struck
- Level 19 Might Aura when Equipped > Level 29 Might Aura when Equipped
#### Plague:
- +[1-2] to All Skills > +2 to All Skills
- 25% Chance to Cast Level 35 Poison Nova on Striking > 50% Chance to Cast Level 35 Poison Nova on Striking
- 30% Chance to Cast Level 35 Lower Resist when Struck > 50% Chance to Cast Level 35 Lower Resist when Struck
- +20% Faster Cast Rate > +30% Faster Cast Rate
- -20% to Enemy Poison Resistance > -30% to Enemy Poison Resistance
#### Hand of Justice:
- +33% Increased Attack Speed > +40% Increased Attack Speed
- +[280-330]% Enhanced Damage > +[350-380]% Enhanced Damage
- -[10-20]% to Enemy Fire Resistance > -20% to Enemy Fire Resistance
- Level 12 Holy Fire Aura when Equipped > Level 25 Holy Fire Aura when Equipped
#### Asylum:
- +[285-335]% Enhanced Damage > +[340-380]% Enhanced Damage
#### Obsession:
- +15% Faster Cast Rate > +65% Faster Cast Rate
#### Zenith:
- +[225-300]% Enhanced Damage > +[400-500]% Enhanced Damage


## Runewords (helmets):
Nadir:
    +10 Defense > +40 Defense
Delirium:
    +261 Defense > +350 Defense
    11% Chance to Cast Level 18 Confuse on Striking > 25% Chance to Cast Level 18 Confuse on Striking
Flickering Flame:
    +2 to Fire Skills > +3 to Fire Skills
    -[5-10]% to Enemy Fire Resistance > -15% to Enemy Fire Resistance
Dream:
    Level 14 Holy Shock Aura when Equipped > Level 20 Holy Shock Aura when Equipped
Ferocity:
    [10-12]% Life Stolen per Hit > 15% Life Stolen per Hit
    12% Chance to Cast Level 10 Taunt on Striking > 20% Chance to Cast Level 10 Taunt on Striking
    +[150-200]% Enhanced Defense > +[250-300]% Enhanced Defense


## Runewords (armor):
#### Fortitude:
- 20% Chance to Cast Level 15 Chilling Armor when Struck > added
- +[250-300]% Enhanced Damage > +300% Enhanced Damage
#### Stealth:
- +10% Faster Run/Walk > +25% Faster Run/Walk	
- +20% Faster Cast Rate > +25% Faster Cast Rate
- +20% Faster Hit Recovery > +25% Faster Hit Recovery
#### Myth:
- +30 Defense vs. Missile > +100 Defense vs. Missile
- +50 to Attack Rating > added
#### Hustle:
- +20% Increased Attack Speed > +25% Increased Attack Speed
- Level 6 Burst of Speed When Equipped > Level 14 Burst of Speed When Equipped
#### Treachery:
- 15% Chance to Cast Level 21 Mind Blast when Struck > 15% Chance to Cast Level 11 Fade when Struck
#### Duress:
- +15% Chance of Crushing Blow > +25% Chance of Crushing Blow
#### Bone:
- +2 to Necromancer Skills > +3 to Necromancer Skills
- 30% Chance to Cast Level 25 Bone Spear on Striking > 50% Chance to Cast Level 30 Bone Spear on Striking
- +30% Increased Attack Speed > added
#### Rain:
- +30% Increased Attack Speed > added
#### Principle:
- +50% Enhanced Defense > added
#### Bramble:
- +300 Defense > +1000 Defense
#### Chains of Honor:
- +70% Enhanced Defense > +120% Enhanced Defense
- All Resistances +[50-60] > All Resistances +65
#### Enigma:
- +25% Faster Run/Walk > +45% Faster Run/Walk
- +[500-775] Defense > +800 Defense
- +14 Life after each Kill > added
- [0-74]% Better Chance of Getting Magic Items ([0.5-0.75]% per Character Level) (retarded description) > [0-74]% Better Chance of Getting Magic Items (0.75% per Character Level)
- +[0-74] to Strength (+[0.5-0.75] per Character Level) (retarded description) > +[0-74] to Strength (+0.75 per Character Level)
- Blink > Teleport
**NOTE**: They added Blink not because teleport was OP but because Sorceress got nerfed in every possible way. If they kept the Teleport in Enigma, Sorceress would be pretty much removed from the game. Because of their late game changes, Sorceress is so called "S tier" mapper but nothing else, she sucks in every other possible way. This mod changes that so Sorceress is playable and she is still OP in the late game as PD2 devs intended. Teleport is already nerfed so there is no super late game tele stomping with Enigma (only this is enough to justify Blink > Teleprot change). Also Sorceress is buffed in this mod regardless of Enigma changes.

## Runewords (shields):
#### Spirit:
- +[25-35]% Faster Cast Rate > +[30-35]% Faster Cast Rate
#### Dream:
- Level 14 Holy Shock Aura when Equipped > Level 20 Holy Shock Aura when Equipped
#### Phoenix:
- +[250-300]% Enhanced Damage > +[300-350]% Enhanced Damage
#### Shattered Wall:
- Adds 200-250 Cold Damage > Adds 300-500 Cold Damage
- All Resistances +30 > added
