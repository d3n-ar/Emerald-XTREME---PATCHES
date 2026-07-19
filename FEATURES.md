# What features are included?
## Table of Contents
- [What features are included?](#what-features-are-included)
  - [Table of Contents](#table-of-contents)
  - [Configuration files](#configuration-files)
  - [Upgraded Battle Engine](#upgraded-battle-engine)
  - [Full Trainer customization](#full-trainer-customization)
  - [Pokémon data](#pokémon-data)
  - [Interface improvements](#interface-improvements)
  - [Engine improvements](#engine-improvements)
  - [Overworld improvements](#overworld-improvements)
  - [Developer tools](#developer-tools)

## Configuration files
A lot of features listed below can be turned off as desired. Check which ones in these files
- [AI config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/ai.h)
- [Battle config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/battle.h)
- [Caps config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/caps.h)
- [Debug config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/debug.h)
- [DexNav config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/dexnav.h)
- [General config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/general.h)
- [HGSS Pokédex config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/pokedex_plus_hgss.h)
- [Item config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/item.h)
- [NPC Follower config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/follower_npc.h)
- [Overworld config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/overworld.h)
- [Pokémon config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/pokemon.h)
- [Save config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/save.h)
- [Species enabled](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/species_enabled.h)
- [Summary screen config](https://github.com/rh-hideout/pokeemerald-expansion/blob/master/include/config/summary_screen.h)

## Upgraded Battle Engine
- ***Battle gimmicks:*** Mega Evolution, Primal Reversion, Ultra Burst, Z-Moves, and Terastallization.
- ***Newer game battle types:*** Double Wild Battles, Inverse Battles, 1v2/2v1 battles, Sky Battles (not fully implemented yet).
- ***Updated battle mechanics:*** Critical capture, Frostbite support, Poké Ball quick menu, Move description menu, Gen 4 Fog, obedience, Affection, Party swap upon catch, FRLG/Gen4+ whiteout money calculation, Gen 4-style shadows.
- ***Updated move data***: Fairy/Stellar types, Physical/Special split, flags.
- ***Updated calculations:*** Damage, experience, mid-turn speed, end-battle stats and EVs, Level 100 EVs.
- ***Every item, ability and move effect up to Gen IX:*** Includes contest data up to SwSh ([source](https://pokemonurpg.com/info/contests/rse-move-list/)) [except for a few Pokemons].
- ***Initial battle conditions:*** Stat stages, battle terrain, Wild AI flags.
- ***Faster battles:*** Simultaneous HP reduction, shortcut to "Run" option, faster battle intro, faster HP drain, faster AI calculations.
- ***Improved AI:*** Faster and considers new effects added by Expansion.
- ***Popular features:*** Type Indicators.

## Interface improvements
- ***Pokémon Summary:*** Move relearner, EV/IV checks, Nature colors ([feature branch](https://github.com/DizzyEggg/pokeemerald/tree/nature_color) by @DizzyEggg).
- ***Party Menu:*** "Move Item" option.
- ***Pokémon Storage System:*** Move option as default, access from Box Link item.
- ***HGSS-style Pokédex*** ([original feature branch](https://github.com/TheXaman/pokeemerald/tree/tx_pokedexPlus_hgss) by @TheXaman): Detailed in-game information accessible to players.

## Engine improvements
- ***All base pokeemerald bugfixes implemented by default:*** Anything under the `BUGFIX` define.
- ***Improved sprite and palette compression:*** Assets use less space than vanilla compression.
- ***Modern compiler support:*** Detect potential errors in your code more easily.
- ***Dynamic Multichoice*** ([original branch](https://github.com/SBird1337/pokeemerald/tree/feature/dynmulti) by @SBird1337): Easier way to add multiple-choice menus for scripting.
- ***High-Quality RNG:*** No more broken vanilla RNG.

## Overworld improvements
- ***Modern Mechanics***: Defog field move, B2W2+ Repel system, Running indoors, Removed field poison, Chain fishing, VS. Seeker, FRLG+ whiteout message.
- ***Overworld and Follower Pokémon*** ([feature branch](https://github.com/aarant/pokeemerald/tree/followers-expanded-id) by @aarant)
    - *Includes Dynamic overworld palettes (DOWP) and Overworld Expansion for event IDs beyond 255.*
    - *Includes Pokémon sprites up to Generation IX.*
- ***Day/Night System:*** ([feature branch](https://github.com/aarant/pokeemerald/tree/lighting-expanded-id) by @aarant)
    - *Includes support for non-real time clock*.
- ***NPC Followers***: ([feature branch](https://github.com/ghoulslash/pokeemerald/tree/follow_me) by @ghoulslash) This is unused currently.
- ***BW Map Pop-ups*** ([feature branch](https://github.com/ravepossum/pokeemerald/tree/bsbob_map_popups) by @BSBob).
- ***Obtained Item descriptions*** (feature branch by @ghoulslash).

## Special tools
- ***Pokémon Sprite Visualizer:*** Test every Pokémon sprite and animation.
- ***Overworld debug menu** ([original feature branch](https://github.com/TheXaman/pokeemerald/tree/tx_debug_system) by @TheXaman)*: Support menu with an assortment of features to facilitate debugging, including warping, flag and var toggling, Pokémon and item generation and more.
- ***Battle Debug Menu:*** Modify data on the fly in the middle of a battle.
- ***Learnset Helper:*** Autogenerate movesets from your custom TM and Tutor data based on official compatibility data.
- ***Configurable script flags:*** Disabling Wild encounters, Disabling Trainer battles, Forcing/Disabling Shinies.
- ***Saveblock Cleansing*** ([feature branch](https://github.com/ghoulslash/pokeemerald/tree/saveblock) by @ghoulslash)

## Pokemons
- Upto gen 7.

## Post Game Expansion
- **No spoilers**
