# Lethal Rebirth

[![GitHub Wiki](https://img.shields.io/badge/Wiki-%20-FFFFFF?style=for-the-badge)](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki)
[![GitHub](https://img.shields.io/badge/GitHub-%20-FFFFFF?style=for-the-badge)](https://github.com/Team-Rebirth/Lethal-Rebirth)
[![Thunderstore](https://img.shields.io/badge/Thunderstore-%20-229EC6?style=for-the-badge)](https://thunderstore.io/c/lethal-company/p/Rebirth/Lethal_Rebirth/)

> ## Promotion Announcement
>
> Congratulations, Contractor.
>
> Effective immediately, you are promoted to Elite Recovery Operative - Operation Rebirth. This promotion is not a courtesy. It is a metric-driven adjustment based on sustained profitability and demonstrated tolerance for hazardous assignment environments.
>
> As an Elite Recovery Operative you will be deployed to newly commissioned Company assets. These locations contain high-yield proprietary material and unverified hazards. Your role is to extract value, and return usable assets to Company custody.
> Previous recovery operations produced significant anomalous data. Including personnel apparent duplications. These phenomena are non-compensable and non-billable. If you encounter expired staff, doppelgängers, or other anomalous entities:
>
> - Do not engage outside of mission parameters.
> - Neutralize or bypass as required to preserve mission integrity.
> - Mark any recovered biological material as “non-standard” and route to containment.
>
> Noncompliance will affect promotional standing and future assignment eligibility.

## Operational Summary

### Major features

The concept of Lethal Rebirth is simple: optimize some of the game's mechanics, increase performance, and expand the experience without losing the vanilla feel. This includes:

- **Bigger Teams**: Lobbies with up to 32 players (4-8 recommended) are now possible! To keep the ship from getting too crowded, a larger ship is available right away.
  - **Latejoin**: Per `Lobby open` you can re-open the lobby in orbit and allow players to late join!
- **Rebalanced Moons**: Existing moons have been adjusted in terms of scrap yield, enemy presence, and much more. Additional fire exits, better access to different locations, and cruiser friendliness are also included.
- **New Interiors**: Various interiors (including the Backrooms), Wesley's Interiors, the Lethal Office (inspired by [The Upturned](https://store.steampowered.com/app/1717770/The_Upturned/)), Deepcore Mines & some vanilla-style interiors are accessible.
  - **Expanded Interiors**: The Facility and Mineshaft interiors have been **replaced** by Wesley's expanded variants, featuring new rooms that expand the experience in an immersive way. There is also a Manor alternative.
- **Better Immersion**: Cave variants & new fog styles
- **New enemies**: Two additional threats: The Locker & The Cabinet. *Infestation variants are also present.*
- **Mirages**: Masked individuals have found ways to imitate both the appearance and voice of an employee. They appear to be rare, but should be approached with caution.
  - Cautious with the body of fallen crewmates as well...
- **Lategame Upgrades**: Various ship and equipment upgrades
- **Additional Slots**: *1 additional equipment-only slot* can be purchased.
- **Quota Rollover**: Rollover for superceeded quotas. In the event that all crew members die, the quota rollover will be reduced by 50%.
- **Terminal Improvements**: New commands & formatting.

> For a proper guide to these changes, [check here](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki).
>
> ℹ️ For a complete list of all gameplay-relevant mods and what they do in this modpack, [check here](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Mods-&-Features).

We recommend installing [LethalCasino](https://thunderstore.io/c/lethal-company/p/mrgrm7/LethalCasino/) if you aim for a more casual, relaxed experience when meeting your quota!

→ Further recommendations can be found here: [Recommended Mods](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Recommended-Mods)

### Hotkeys

**General:**

- `F`: Flashlight control
- `M`: Toggle Mute
- `Left Alt`: Switch to utility slots
- `Right + Alt`: Toggle swap utility slots
- `F1`: Betterfog configuration menu
- `F2`: Toggle HUD

**Special:**

- `O`: Femmployee Customization - ⚠️ Recommended to be changed to a non-letter/-number key due to potential terminal interferences.
- `CTRL + SHIFT + ALT + Q`: Quit to Menu, no matter what.
- `Left + Alt`: Toggle Night Vision Goggles *(have to be bought & equipped first)*
- `Middle Mouse Button`: Wholly empty wheelbarrow/shopping cart.

**Spray Paint:**

- `T`: Change spray paint color.
- `+`/`-`: Adjust spray size.
- `E + LMB`: Erase when using spray paint.

**Terminal:**

- `↑`: Get prior command in command history
- `←`/`→`: Switch `view monitor` target
- `Left + Shift`: Display alternative currency (PC from LGU)

**Spectator:**

- `Q`: Switch to poltergeist spectator mode
- `LMB` in poltergeist: Enable night vision
- `H`: Show poltergeist keybinds

### Known Issues

Updating the mods after installing the modpack can cause new issues! Please let us know if you updated your mods when reporting them.

Issues can easily be reported per [GitHub Issue](https://github.com/Team-Rebirth/Lethal-Rebirth/issues) or in [our Discord Thread on the Official LC Modding Discord Server](https://discord.com/channels/1168655651455639582/1433832543060496404).

- **Monster Samples disappearing on lobby reload**: Might be fixed soon, is an error caused by the v73 update that has yet to be fixed.
- **Game Crash when hosting after having been a client**: Restart the game whenever you have been a client and want to host a lobby afterwards. Seems to be caused by LLL & LeathalNetworkAPI, will address it sometime.
- **Betterfog Preset Desync**: Betterfog might use the incorrect preset, which can be noticed by unfittig color or higher fog density than your peers.
  - **How to deal with it**: Press F1, disable autosync, then revert to vanilla mode or manually select the correct preset. To understand which preset is used when, check out the [BetterFog Configuration Guide](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/BetterFog).
- **General Desync**: Terminal purchases or similar functions may become unavailable to one or more players.
  - **How to deal with it**: All affected players must exit and rejoin the lobby.
- **Messed up screen width**: LCUltrawide_Community most likely is responsible. Occurs more often on linux systems apparently.
  - **How to deal with it**: Disable the mod and restart. As the mod is wholly clientside, it should be save to disable.
- **Wheelbarrow / Shopping Cart glitch**: You can not place items into it again despite it being empty.
  - **How to deal with it**: Use the `Middle Mouse Button` to wholly empty the wheelbarrow/shopping cart to remove it.
- **Invisible Maneater**: Sometimes a man eater that ate scrap is invisible before pick up. Cause is unknown (maybe Cullfactory?).
- **0 value Anvil**: Sometimes the anvil from Immersive Scrap does not have any value. Cause is unknown.
- **Airborn Mines/Hazards**: Some hazards, mostly (prison) mines might float above the floor or cliffs. Cause is unknown.
- **Unable to enter PW for lobby**: Had it occur once that no PW could be entered. Pressing space might have fixed it. Cause is unknown.

### Future Plans

Here an overview over our future plans and priorities. **Everything on here is not guaranteed to be implemented but simply plans we have made thus far for the development of this modpack.**

#### Update Roadmap

- [X] Release Lethal Rebirth v2.0.0 pre-Halloween
- [X] Re-add BetterSpraypaint: Once updated to v73
- [X] Re-add [FixCharWarn by chuxiaaaa](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/FixCharWarn/): Once updated to be compatible with LGU
- [X] Re-enable EnhancedLockPicker/RadarBooster Enhancements: Once updated for v73
- [X] LGU Pricing & Upgrade distribution Overhaul
- [X] LunarConfigMoons: Vanilla-like Interior Weights
- [X] LoadingTips for most mods.
- [X] Better Solo Balancing
- [ ] LunarConfig: Implement [ButteRyBalance](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/ButteRyBalance/wiki/)'s changes for moon balancing & enemy weights manually & tweak it.
- [ ] Weather Overhaul with [Combined Weathers Toolkit](https://thunderstore.io/c/lethal-company/p/Zigzag/Combined_Weathers_Toolkit/) & [LethalElementsTheta](https://thunderstore.io/c/lethal-company/p/pacoito/LethalElementsTheta/) + [Weather_Probe](https://thunderstore.io/c/lethal-company/p/WhiteSpike/Weather_Probe/)
- [ ] Custom Logs (Lore, Info, Modpack Intro)
- [ ] Skin Registry integration & configuration
- [ ] Wesley's Moons Compatibility per Configuration

#### Sometime

Everything in this category especially is less set in stone.

- [X] BetterFog Enhancement: Custom presets for Embrion & Eclipsed Artifice - *Already implemented, dependent on betterfog patch to work*
- [ ] More Vanilla-like Interior Mods (Maybe Castellum Carnis, PlayZone, [Cabin](https://thunderstore.io/c/lethal-company/p/Sniper1_1/CabIn/), and/or Sector0(Beta)?)
- [ ] More Vanilla-like Moon Mods (Maybe Tunere, Oxyde, Lua, Seichi, and/or Wither?)
- [ ] Mirage Spawn Chance overhaul: Currently every moon has the same spawn chances for Mirages. In the future, they should become very rare on Experimentation, Assurance, and Vow, stay about as common on the 2nd Tier, and become more common above it.
- [X] Testing - [FairAI by TheFluff](https://thunderstore.io/c/lethal-company/p/TheFluff/FairAI/changelog/): Integration when compatible
- [ ] Testing - [FacilityMeltdown by loaforc](https://thunderstore.io/c/lethal-company/p/loaforc/FacilityMeltdownExperimental/) (+chance): Re-implementation when functional again
- [ ] Testing - [CodeRebirth by XuXiaolan](https://thunderstore.io/c/lethal-company/p/XuXiaolan/CodeRebirth/): Either integration or compatibility
- [ ] Testing - [DawnLib by TeamXiaolan](https://thunderstore.io/c/lethal-company/p/TeamXiaolan/DawnLib/): Integration (+ Company_Globes!)
- [ ] Testing - [Biodiversity by super_fucking_cool_and_basass_team](https://thunderstore.io/c/lethal-company/p/super_fucking_cool_and_badass_team/Biodiversity/): Integration when fitting
- [ ] Testing - [FacelessStalker by Sparble](https://thunderstore.io/c/lethal-company/p/Sparble/FacelessStalker/): Integration when fitting
- [ ] Testing - [InsanityRemastered by BudgetAirpods](https://thunderstore.io/c/lethal-company/p/BudgetAirpods/InsanityRemastered/): When updated for v73 and deemed fitting
- [ ] Testing - [MapImprovements by SpookyBuddy](https://thunderstore.io/c/lethal-company/p/SpookyBuddy/MapImprovements/): When compatible with RebalancedMoons or as an alternative.
- [ ] Testing - [LCGoldScrapMod by SimonTendo](https://thunderstore.io/c/lethal-company/p/SimonTendo/LCGoldScrapMod/): Needs proper adjustment
- [ ] Testing - [Diversity](https://thunderstore.io/c/lethal-company/p/IntegrityChaos/Diversity/): Needs proper adjustment for compatibility & balancing.
- [ ] Testing - [LethalThings by Evaisa](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalThings/): Either integration or compatibility
- [ ] Testing - [Piggys_Variety_Mod by Piggy](https://thunderstore.io/c/lethal-company/p/Piggy/Piggys_Variety_Mod/): Either integration or compatibility
- [ ] Testing - [Company Hauler by Glojam](https://thunderstore.io/c/lethal-company/p/Glojam/Company_Hauler/): Integration when compatible with v73, CruiserImproved & LC_VR
- [ ] Testing - [GhostCodes by darmuh](https://thunderstore.io/c/lethal-company/p/darmuh/ghostCodes/): Integration when compatible with v73

## Installation

Two things are required:

- The game [Lethal Company](https://store.steampowered.com/app/1966720/Lethal_Company/)
- An approved mod manager:
  - [Gale](https://kesomannen.com/gale) is recommended.
  - [r2modman](https://r2modman.com) is a valid alternative.

Installing this modpack is simple. [Download the package from Thunderstore](https://thunderstore.io/c/lethal-company/p/Rebirth/Lethal_Rebirth/) as you would any other mod and you're ready to go!

> ℹ️ All players must have the modpack installed when playing in multiplayer.

Updating the game or individual mods may cause bugs. If this happens, please create an issue.

> ⚠️ Install other mods at your own risk. Any further modifications may result in instability or bugs.

## Credits

Big thanks to [Zeekerss](https://bsky.app/profile/zeekerss.bsky.social), the creator of Lethal Company. His work laid the foundation for all our testing, adjustments, and balancing efforts.

We’d also like to thank all the mod creators whose work is included in this pack. Their contributions add variety and make the experience a lot more engaging. [Check out our list of mods and what they add to this modpack](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Mods-&-Features).

Additional thanks go out to other fellow modpack creators, like [ZetaArcade](https://github.com/Zeta-Arcade), [Moroxide](https://thunderstore.io/c/lethal-company/p/Megalophobia/MEGALOPHOBIA/) and [ProfoundlyPurple](https://www.youtube.com/channel/UCegCZVxrWaOay_0sKO4TOAw), who through their own perspectives and ideas also inspire the development of this modpack. Their stuff is worth checking out!

Also consider joining the [Lethal Company Modding Community Server](https://discord.gg/ffCEu5KC5D)!

### Acknowledged Contributions

**Most of the Configuration & modpack conceptualization done by [Shaydelity](https://github.com/Shaydelity), member of [Team Rebirth](https://github.com/Team-Rebirth).**

**Technical execution of the modpack and its publishing, done by [Nando Lawson](https://github.com/nandolawson), member of [Team Rebirth](https://github.com/Team-Rebirth).**

**Thanks to [ThecheeseXD](https://github.com/thecheesexd) for providing feedback on the Wiki and Mod choice!**

**Thanks to [Jovius](https://github.com/Jovyus), who helped us with the promotional material.**

**Thanks to [Zeta](https://thunderstore.io/c/lethal-company/p/ZetaArcade/?section=modpacks) (aka. ZetaArcade), creator of the [Testudination Modpacks](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Testudination) for providing feedback and inspiring Lethal Rebirth's development.**

**Huge thanks to [Purple](https://thunderstore.io/c/lethal-company/p/purpletheproto/?section=modpacks), creator of the [Arduous Modpacks](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Arduous-Hardships-&-Journeys), for inspiring this modpack, offering feedback on the mods included, and inspiring the direction of Lethal Rebirth.**
