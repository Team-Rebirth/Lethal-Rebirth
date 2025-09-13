# Lethal Rebirth

> v2.0.0

Lethal Company is an efficient operation, but imperfections remain. Bugs, instability, and questionable balance are regrettable liabilities. This package aims to correct those faults, enhancing your tools, and expanding the catalog. All without compromising performance in any significant manner. Efficiency is mandatory. Profit is expected.

- [README on GitHub](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/README.md) (always latest version)
- [Thunderstore Modpack](https://thunderstore.io/c/lethal-company/p/Rebirth/Lethal_Rebirth/)
- [Company Code of Conduct](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/CODE_OF_CONDUCT.md)
- [Contributing to the Company's Effort](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/CONTRIBUTING.md) (WIP)
- [Changelog](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/CHANGELOG.md)

## Operational Summary

### Major features

The directive of Lethal Rebirth is simple: Preserve the integrity of standard Company operations. Core procedures remain familiar, but efficiency has been refined. Alongside improved stability and performance, enhancements include:

- **Bigger Teams, bigger profit**: Studies done by the Company have found that bigger teams make for more efficient work. There is no extension of the provided living space (the Company financed ship).

- **Rebalanced Moons**: No new locations authorized. *Existing environments* have been adjusted for scrap yield, hostile presence, and navigation. Additional exits, traversal structures, and safety measures have been implemented where efficiency demanded.

- **New Interiors**: Generic environments (including The Backrooms), a Slaughter House, Wesley’s extensions, the Lethal Office (inspired by [The Upturned](https://store.steampowered.com/app/1717770/The_Upturned/)), and the Slaughterhouse are accessible.

- **Better Immersion**: Cave variants, new fog, and prettier foliage have been discovered.

- **New Hostiles**: Two additional threats: The Locker (situational hazard) and The Shrimp (from [The Upturned](https://store.steampowered.com/app/1717770/The_Upturned/)). *Infestation variants and the reinstated Kidnapper Fox are also present.*

- **Masked**: In recent events the Company has found that entities, known as the Masked, have found ways to both mimic appearance and voice of any given employee. They seem to be rare yet should be encountered with caution.

- **Lategame Upgrades**: Costs and functions adapted to progression.

  > ⚠️ The Hunter Upgrade is free of charge and replaces SellBodiesFixed. Acquisition must occur **manually** at round start.

- **Utility Slots**: Up to *3 additional equipment slots* may be purchased. Most items are compatible.

- **Quota Rollover**: In the event of total personnel loss, quota rollover will be reduced by 20%.

- **Terminal Improvements**: *Expanded interface functions*, including *purchase packs* and *lobby management systems*.

- **The Casino** An officially sanctioned outlet for risk-oriented employees. Sadly, in recent events the Company found that the assigned worth to a teammates bodies encourages desperate teams to resort to friendly fire. The Company asks you to refrain from such behavior for the benefit of morale, efficiency, and professionalism in this operation.

> ℹ️ For a complete list of all gameplay-relevant mods and what they do in this modpack, [check here](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/docs/Mods.md).

### Ressources

This package includes some major overhauls in your scavenging experience and thus the Company has compiled this list of guides to aid newcomers.

- [Company Terminal Guide](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/docs/Terminal.md) (WIP)
- [Company Equipment Guide](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/docs/Equipment.md) (WIP)
- [LobbyControl Info (Thunderstore)](https://thunderstore.io/c/lethal-company/p/mattymatty/LobbyControl/)

### Hotkeys

> ⚠️ This list is not finished yet

- F: Flashlight control
- Left Alt: Switch to utility slots
- F1: Betterfog configuration menu
- O: Femmployee Customization - ⚠️ Recommended to be changed to a non-letter/-number key due to potential terminal interference.

### Known Issues

- **Please restart the game for CustomSounds to work properly!**: Has been ignored thus far whenever it occured without noticed consequence.

- **Betterfog Preset Desync**: Incorrect fog parameters may apply.
  - **Directive**: Press F1, disable autosync, then revert to vanilla mode or manually select the correct preset. To understand which preset is used when, check out the [BetterFog Configuration Guide](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/docs/BetterFog.md)

- **General Desync**: Terminal purchases or similar functions may become unavailable to an operator.
  - **Directive**: Affected personnel must exit and rejoin the lobby.

- **Messed up screen width**: LCUltrawide_Community most likely is responsible. Occurs more often on linux systems apparently.
  - **Directive**: Disable the mod and restart. Wholly clientside, should not cause desync.

## Installation

Two things are required:

- The game, [Lethal Company](https://store.steampowered.com/app/1966720/Lethal_Company/)
- An approved mod management system ([Gale](https://kesomannen.com/gale) is recommended for efficiency)

Acquisition is simple. [Download the package from Thunderstore](https://thunderstore.io/c/lethal-company/p/Rebirth/Lethal_Rebirth/) as you would any standard modification. Initiation will be immediate.

> ℹ️ All personnel must have the modpack installed when multiple operators are present. Non-compliance is unacceptable.
> ⚠️ You may disable or supplement individual components at your own risk. Such alterations may result in instability or hazardous anomalies. The Company assumes no responsibility.

## Compatibility

This package is made to work best *as is*, meaning the Company did not consider mods outside the scope of it regarding compatibility. Here a list of mod-types that *should not* interfere with the package.

- Suit Mods
- MoreHead Cosmetics
- Model Replacements ([See for exception here](#known-incompatibilities))
- Additional Enemies
- Additional Moons ([More info here](#moons))

If you encounter errors while having installed a type of mod that is not **purely cosmetic**, please make sure that the error is not related to the added mod before reaching out to the Company support.

### Known Incompatibilities

- The [Female_Scavenger_Reskiner by TKronix](https://thunderstore.io/c/lethal-company/p/TKronix/Female_Scavenger_Reskiner/) is considered incompatible because of **severe issues** (game-breaking desync) in the past, probably caused by interaction with [The Femmployee Mod](https://thunderstore.io/c/lethal-company/p/TiltedTomb/The_Femmployee_Mod/) or the [ModelReplacementAPI](https://thunderstore.io/c/lethal-company/p/BunyaPineTree/ModelReplacementAPI/).
- [Diversity by IntegrityChaos](https://thunderstore.io/c/lethal-company/p/IntegrityChaos/Diversity/) sadly is incompatible with some of the interiors added here and has generally been found to not work reliably enough in combination with the other mods to be recommended. Perhaps, if updated in the future, as planned by [IntegrityChaos](https://integritychaos.com/), it will be readded. **He is looking to have a maintainer for their mod.** Consider [joining his discord](https://discord.gg/W8YSVRdv2B) if you are interested.
- [LethalCompanyVR by DaXcess](https://thunderstore.io/c/lethal-company/p/DaXcess/LethalCompanyVR/) is incompatible with [CruiserImproved by DiggC](https://thunderstore.io/c/lethal-company/p/DiggC/CruiserImproved/) currently and has been rather unstable with older pre-release versions of this modpack.
- [HDLCPatch](https://thunderstore.io/c/lethal-company/p/MintyMods/HDLCPatch/) can work but has been shown to work unreliably and cause issues.

### Recommended Mods

If you want to extend your experience in certain ways, here are additional packages we have found that should both be compatible and might appeal to you!

#### Accessibility Mods

- [Subtitles by JustJelly](https://thunderstore.io/c/lethal-company/p/JustJelly/Subtitles/)

#### QoL Mods

- [CrossHair by CTNOriginals](https://thunderstore.io/c/lethal-company/p/CTNOriginals/CrossHair/): Wanna see exactly what you target?
- [DisableHelmetVisor by DeathWrench](https://thunderstore.io/c/lethal-company/p/DeathWrench/DisableHelmetVisor/): Annoyed by the visor? Remove it.
- [SafeSoloScrap by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/SafeSoloScrap/): Solo scavenging too hard? Retain past day's scrap.

#### Fun Mods

- [LethalThings by Evaisa](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalThings/): Random but fun stuff like a rocket launcher, plushies, and a remote radar (which makes the already added remote mapper redundant...)
- [EmergencyDiceUpdated by slayer6409](https://thunderstore.io/c/lethal-company/p/slayer6409/Emergency_Dice_Updated/): Want to gamble for luck or absolute chaos? Your chance lays here.s
- [BetterEmotes by KlutzyBubbles](https://thunderstore.io/c/lethal-company/p/KlutzyBubbles/BetterEmotes/)

### Moons

As of now, the package does not include routes to new moons. Implementing more routes turned out to be a struggle for low-end hardware and increase boot-up time significantly, not to mention the instabilities that can come with them.

But, as the Company considers creating an extended package featuring new routes, there are *few*, mostly [Chameleon-based](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/Chameleon/) minor configurations made for [Wesleys_Moons](https://thunderstore.io/c/lethal-company/p/Magic_Wesley/Wesleys_Moons/), [Aquatis](https://thunderstore.io/c/lethal-company/p/sfDesat/Aquatis/), some of [Rosies_Moons](https://thunderstore.io/c/lethal-company/p/RosiePies/Rosies_Moons/), and [Rockwell](https://thunderstore.io/c/lethal-company/p/DemonMae/Rockwell_moon/) specifically.

## Credits

Primary acknowledgment is directed to [Zeekerss](https://bsky.app/profile/zeekerss.bsky.social), originator of the Lethal Company framework. His product established the foundation for extensive testing, modification, and balance procedures.

Secondary acknowledgment is extended to all registered creators whose modifications were integrated into this package. Their contributions increase operational variety and engagement metrics beyond baseline parameters.

Last acknowledgment is, of course, directed to all the mod creators and their work. To see most of the mods and by whom they were made, [check out our list of mods and what they add to this modpack](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/docs/Mods.md).

### Acknowledged Contributions

**Most of the Configuration & modpack conceptualization done by [Shaydelity](https://github.com/Shaydelity), member of [Team Rebirth](https://github.com/Team-Rebirth).**

**Technical execution of the modpack and its publishing, done by [Nando Lawson](https://github.com/nandolawson), member of [Team Rebirth](https://github.com/Team-Rebirth).**
