# Changelog

Every change to the modpack itself will be noted in this file.

The format of the changelog is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

We adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html):
> Given a version number MAJOR.MINOR.PATCH, increment the:
>
> MAJOR version when you make changes that disrupt backwards compatibility.
> MINOR version when you add functionality in a backward compatible manner.
> PATCH version when you make backward compatible bug fixes.
> Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

## [unreleased/v2.?.?] - 2025-??-?? | ??? (v73)

### Noted [unreleased]

- Updated Dependencies.

## [v2.3.0] - 2025-11-21 | Solo Balance & Info (v73)

### Added [v2.3.0]

- [SafeSoloScrap by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/SafeSoloScrap/): Safes all the scrap from the days before you died when you are playing solo. 
- [AnnounceMoonAndWeatherChange by TestAccount666](https://thunderstore.io/c/lethal-company/p/TestAccount666/AnnounceMoonAndWeatherChange/): Announces when routing to another moon.
- [BetterPaycheck by Swaggies](https://thunderstore.io/c/lethal-company/p/Swaggies/BetterPaycheck/): Improves the paycheck's format and readability.
- [Interior_Title_Cards by lethal_coder](https://thunderstore.io/c/lethal-company/p/lethal_coder/Interior_Title_Cards/): When entering the interior you shall be greeted with its name.

### Changed [v2.3.0]

- LGU (moreshipupgrades.cfg): Increased price for Scrap Keeper, temporarily deactivated lightning rod as distance config does not work.

### Noted [v2.3.0]

- Updated Dependencies.

## [v2.2.1] - 2025-11-21 | Loading Tips (v73)

### Changed [v2.2.1]

- LoadingTips: Added many more, refined some, added category marking tips.

### Noted [v2.2.1]

- Updated Dependencies.
- Updated the [Wiki's Modlist](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Mods-&-Features).
- Updated Roadmap in README.

## [v2.2.0] - 2025-11-21 | Rebalancing (v73)

### Added [v2.2.0]

- [DimmingFlashlights by blink9803](https://thunderstore.io/c/lethal-company/p/blink9803/DimmingFlashlights/): Makes the flashligh dimmer with lower battery.
- [FriendPatches by Lauriichan](https://thunderstore.io/c/lethal-company/p/Lauriichan/FriendPatches/): Fixes an error that makes another player's name display as "Unknown" and adds players to steam's recently played list.
- [DoNotEatItems by mattymatty](https://thunderstore.io/c/lethal-company/p/mattymatty/DoNotEatItems/): Items are always dropped upon death.
- [EasterEggFixes by SpookyBuddy](https://thunderstore.io/c/lethal-company/p/SpookyBuddy/EasterEggFixes/): Easter eggs can now only explode when thrown.

### Changed [v.2.2.0]

- ImmersiveScrap: Disabled the Brick from spawning due to RPC errors when throwing it.
- LGU (moreshipupgrades.cfg): Rebalanced Hunter Sample prices to be less overpowered.
- ExtendDeadline: Increased cost for additional day, made cost primarily quota dependent allowing early game players to afford day extensions while not making it OP for high quotas.
- GeneralImprovements: Increased Quota Rollover Penalty for Squad-wipe from 25 to 50%
- LunarConfigMoons: Integrated Deep Sewers & Decrepit Store into interior weights (and corrected weights misaligned with the [Wiki](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Interiors)'s entries).

### Noted [v.2.2.0]

- Updated Dependencies.
- Some of the new mod additions have been inspired by [Testudination](https://thunderstore.io/c/lethal-company/p/ZetaArcade/Testudination/). 
  - That excellent modpack exists thanks to Zeta (ZetaArcade) & their community and [also features a (WIP) wiki](https://github.com/Zeta-Arcade/ZetasPack/wiki)!

## [v2.1.2] - 2025-11-19 | Hotfix (v73)

### Changed [v2.1.2]

- LoadingScreen: Window type set to FakeGame instead of FixedWindow
- Actually implemented the changes that were supposed to be present in v2.1.0!
  - Specifically, the butterybalance interior adjustments have been disabled, the transitional weathers are gone from gordion.

### Noted [v2.1.2]

- Updated Dependencies.
- Updated README.md
- Cleaned up wiki pages ^-^
- LLL config removed.

## [v2.1.1] - 2025-11-19 | Hotfix (v73)

### Changed [v2.1.1]

- LethalLevelLoader: Config reset to avoid conflicts with the lunarconfig (config removal next update)

### Noted [v2.1.1]

- Updated Dependencies.
- Corrected minor inconsistencies in the v2.1.0 changelog.

## [v2.1.0] - 2025-11-18 | Interior & Lategame Overhaul (v73)

This update features primarily a complete overhaul of Interior weights and Lategame Upgrade pricing & balancing, aiming for a more vanilla-like and fair experience.

This update has had massive delay due to multiple irl interventions and minor technical diffculties, but at last finally found its way to release. At least gave us the opportunity to feature Generic's Cosmetics as well!

### Added [v2.1.0]

- [Generic_Cosmetics by Generic_GMD](https://thunderstore.io/c/lethal-company/p/Generic_GMD/Generic_Cosmetics/)
- [ChuxiaFixes by chuxiaaaa](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/ChuxiaFixes/): Quite a few network optimizing fixes/patches.
- [LunarConfig by Crafty](https://thunderstore.io/c/lethal-company/p/Crafty/LunarConfig/): Used for all configuration beyond single mods in the future. Used to rebalance interior chances thus far.
- [FairAI by TheFluff](https://thunderstore.io/c/lethal-company/p/TheFluff/FairAI/): Allows mines and spiketraps to kill enemies and quicksand to slow them, and kill some.
- [LateGameUpgrades_GUI by slayer6409](https://thunderstore.io/c/lethal-company/p/slayer6409/LateGameUpgrades_Gui/): A GUI to use your Player Credits in.

### Removed [v2.1.0]

- v73ncfix now in ChuxiaFixes
- FixPlayerName now in ChuxiaFixes
- FixCharWarn now in ChuxiaFixes
- NetworkMetricsFix now in ChuxiaFixes
- [PoisonPuffer](https://thunderstore.io/c/lethal-company/p/TestAccount666/PoisonPuffer/)
- [NutcrackerDontKickWhenNotAggrod](https://thunderstore.io/c/lethal-company/p/qwcan/NutcrackerDontKickWhenNotAggrod/)
- [LessPopups](https://thunderstore.io/c/lethal-company/p/Venture/LessPopups/)

### Changed [v2.1.0]

- LunarConfigMoons: Rebalanced Interior weights according to the Wiki's [Moons](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Moons) and [Interiors](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Interiors) page.
- Lategame_Upgrades: Reworked the entire price & currency system. Increased range and intensity of Night Vision Goggles.
- BetterFog: Added Eclipsed Experimentation & Artifice Presets.
- WeatherRegistry: **FIXED PROGRESSIVE WEATHERS ON GORDION**. Integrated Earthquakes into weather weights & added level filter for the Company everywhere.
- ButteRyBalance: Does all the moon balancing again (besides interiors).
- GeneralImprovements: Disabled "FixItemsFallingThrough" as it is incompatible with Matty's fix for it and disabled item falling instead.
- RebalancedMoonsBeta: No interior adjustments.
- Loadstone: Put Art Gallery (MuseumInteriorFlow) on blacklist due to lighting errors caused otherwise.
- LethalSponge: Reduced ship cam framerates for better performance.

### Noted [v2.1.0]

- Updated Dependencies.
- Updated LoadingTips.
- Switched back from BetterSprayPaintFIXED to BetterSprayPaint as it has been updated.
- Switched from Experimental [LobbyControl](https://thunderstore.io/c/lethal-company/p/mattymatty/LobbyControl/) & [AsyncLoggers](https://thunderstore.io/c/lethal-company/p/mattymatty/AsyncLoggers/) to stable
- The standard settings when you make WeatherTweaks Weathers configurable for some reason set the blacklist to be a whitelist per default, which led to progressive weathers on Gordion...

## [v2.0.1] - 2025-10-31 | Dependency Fix & Branding Update (v73)

### Changed [v2.0.1]

- LoadingScreen: Updated configuration & replaced original image with the modpack logo
- Updated dependencies

#### Fixes [v2.0.1]

- Upload workflow: Fixed disabling the console when launching the game.
- Upload workflow: Fixed version string in the main menu.
- Put YesFox on DiFFoZTweaks blacklist as it was not meant to be installed (but can not prevented).

#### Removed [v2.0.1]

- Removed LogNeuter

### Noted [v2.0.1]

- Updated dependencies & removed all that will already be automatically installed due to other mods having them as dependencies.

## [v2.0.0] - 2025-10-31 | The Rebirth (v73)

This update was initially planned as the "Ship & Weather Update". As we engaged with the weather aspect we found lots of balancing work to be done and thus focused on overhauling the modpack's difficulty and experience.
Just as we had the first release candidate for this update, the V73 update for Lethal Company came around. Thus the modpack developed A LOT more, with V73 compatibility now in mind.

The current update certainly is more of a general overhaul, including loads of new features, reconfigured and adjusted features, new fixes, and much much more.

### Added [v2.0.0]

#### Ship [v2.0.0]

- Added [BiggerShip by mrov](https://thunderstore.io/c/lethal-company/p/mrov/BiggerShip/): Makes the ship bigger in a vanilla-ish way.
- Added [ShipAudioTweaks by toosday](https://thunderstore.io/c/lethal-company/p/toosday/ShipAudioTweaks/): Tweaks and replaces some ship noises.
- Added [AudibleHydraulics by dragonmcmx](https://thunderstore.io/c/lethal-company/p/dragonmcmx/AudibleHydraulics/): Makes Enemies capable of hearing the ship door open and close.
- Added [MoreCupboards by ScienceBird](https://thunderstore.io/c/lethal-company/p/ScienceBird/MoreCupboards/): Adds purchasable additional cupboards in different colors.
- Added [Lethal_Doors_Fixed by Entity378](https://thunderstore.io/c/lethal-company/p/Entity378/Lethal_Doors_Fixed/): Makes the ship doors lethal to both players and enemies.
- Added [FunitureLock](https://thunderstore.io/c/lethal-company/p/mattymatty/FurnitureLock/): Allows pre-defined spawn locations and auto unlocking of furniture.

##### Terminal [v2.0.0]

- Added [suitsTerminal by darmuh](https://thunderstore.io/c/lethal-company/p/darmuh/suitsTerminal/): Lets you select suits per terminal with a webcam-like preview.
- Added [TwoRadarMaps by Zaggy1024](https://thunderstore.io/c/lethal-company/p/Zaggy1024/TwoRadarMaps/): Makes switching the radar target in the terminal independent of the radar monitor.
- Added [TransmitPunctuation by Unyucord](https://thunderstore.io/c/lethal-company/p/Unyucord/TransmitPunctuation/): Allows the signal translator to transmit letters like `!`, `?`, and `.`.

#### Moons [v2.0.0]

- Added [NoCompanyPenalties by mrov](https://thunderstore.io/c/lethal-company/p/mrov/NoCompanyPenalties/).
- Added [Atlas by dopadream](https://thunderstore.io/c/lethal-company/p/dopadream/Atlas/): Adds new, and better, HDRI skyboxes to moons.
- Added [BetterLaddersFixed by Lunxara](https://thunderstore.io/c/lethal-company/p/Lunxara/BetterLaddersFixed/): Disables the retraction of the extension ladder, enables ladder sprint.

##### Weathers [v2.0.0]

- Added [MrovWeathers by mrov](https://thunderstore.io/c/lethal-company/p/mrov/MrovWeathers/): Adds cloudy & blackout weather conditions.
- Added [WeatherTweaks by mrov](https://thunderstore.io/c/lethal-company/p/mrov/WeatherTweaks/): Adds combined weathers and inaccurate weather designations like `Foggy?` and `[UNKNOWN]`.

##### Interiors [v2.0.0]

- Added [Fairer_Fire_Exits by MikuOreo](https://thunderstore.io/c/lethal-company/p/MikuOreo/Fairer_Fire_Exits/): Makes Fire Exits generate farther away from the main entrance.
- Added [Deepcore_Mines by Beaniebe](https://thunderstore.io/c/lethal-company/p/Beaniebe/Deepcore_Mines/): Adds the deepcore mines which serve as an alternative to the vanilla mines.
- Added [WaterAssetRestorer](https://thunderstore.io/c/lethal-company/p/Sniper1_1/WaterAssetRestorer/)

##### Enemies [v2.0.0]

- Added [Wesleys_Ememy_Variants by Magic_Wesley](https://thunderstore.io/c/lethal-company/p/Magic_Wesley/Wesleys_Ememy_Variants/).
- Added [PoisonPuffer by TestAccount666](https://thunderstore.io/c/lethal-company/p/TestAccount666/PoisonPuffer/): Makes the spore lizard's spores poisonous.
- Added [CoilHeadStare by TwinDimensionalProductions](https://thunderstore.io/c/lethal-company/p/TwinDimensionalProductions/CoilHeadStare/): Makes the Coil-Head stare back.
- Added [TheCabinet](https://thunderstore.io/c/lethal-company/p/Cabinet_crew/TheCabinet/): Adds a shy, clingy, and potentially helpful creature.
- Added [SmartEnemyPathfinding by Zaggy1024](https://thunderstore.io/c/lethal-company/p/Zaggy1024/SmartEnemyPathfinding/): Allows Masked enemies to use elevators in modded interiors and search for players more naturally.
- Added [DynamicJesterCrank by Piggy](https://thunderstore.io/c/lethal-company/p/Piggy/DynamicJesterCrank/): Makes the jester crank faster and faster...
- Added [LooseJesterSpring by TestAccount666](https://thunderstore.io/c/lethal-company/p/TestAccount666/LooseJesterSpring/): Makes the jester pop when hit too much.
- Added [NutCrackerDontKickWhenNotAggrod by qwcan](https://thunderstore.io/c/lethal-company/p/qwcan/NutcrackerDontKickWhenNotAggrod/): Makes the Nutcracker aggro onto a player it ran into instead of kicking them when not aggroed.

##### Hazards [v2.0.0]

- Added [DoorBreach by TestAccount666](https://thunderstore.io/c/lethal-company/p/TestAccount666/DoorBreach/): Landmines and Turrets can now destroy doors.

#### Quality of Life [v2.0.0]

- Added [Extend_Deadline by WhiteSpike](https://thunderstore.io/c/lethal-company/p/WhiteSpike/Extend_Deadline/): Adds the option to extend the days until the deadline using credits.
- Added [NaturalHealthRegen by Swaggies](https://thunderstore.io/c/lethal-company/p/Swaggies/NaturalHealthRegen/): Makes health regen situational and better.
- Added [ProperOxygen](https://thunderstore.io/c/lethal-company/p/FiligraniCringeGang/ProperOxygen/): Adds gradual damage after the suit's oxygen tanks have been depleted, instead of instant death. The damage recovers once the water is left, Super Mario 64 style.
- Added [LethalHUD](https://thunderstore.io/c/lethal-company/p/s1ckboy/LethalHUD/): Overhauls the HUD. Configured bootstrap.cfg to make you use the local, the modpack's, configuration; Reverse this incase you have made your own (global) config.
- Added [BetterEXP by Swaggies](https://thunderstore.io/c/lethal-company/p/Swaggies/BetterEXP/): A better EXP system that acknowleges statistics like how far you walked, how much scrap you gathered, and how much time you spent where.
- Added [LethalHUD by s1ckboy](https://thunderstore.io/c/lethal-company/p/s1ckboy/LethalHUD/): Allows for customization of the HUD.
- Added [BetterScanVision by DBJ](https://thunderstore.io/c/lethal-company/p/DBJ/BetterScanVision/): Adds a light night vision effect on every scan; Wholly compatible with [LethalHUD by s1ckboy](https://thunderstore.io/c/lethal-company/p/s1ckboy/LethalHUD/).
- Added [MelaniesVoice by Zehs](https://thunderstore.io/c/lethal-company/p/Zehs/MelaniesVoice/): Adds text-to-speech.
- Added [Emblem by Darkbrewery](https://thunderstore.io/c/lethal-company/p/Darkbrewery/Emblem/) & [Lunxaras_Menu_Theme](https://thunderstore.io/c/lethal-company/p/Lunxara/Lunxaras_Menu_Theme/).
- Added [QuickQuitToMenu by taffyko](https://thunderstore.io/c/lethal-company/p/taffyko/QuickQuitToMenu/).
- Added [NameplateTweaks by taffyko](https://thunderstore.io/c/lethal-company/p/taffyko/NameplateTweaks/).
- Added [LoadingScreen by Bertogim](https://thunderstore.io/c/lethal-company/p/Bertogim/LoadingScreen/).
- Added [Poltergeist by coderCleric](https://thunderstore.io/c/lethal-company/p/coderCleric/Poltergeist/): Adds a free-cam-like spectator mode which allows limited interaction with environment and some entities.
- Added [LethalRichPresenceExperimental by mrov](https://thunderstore.io/c/lethal-company/p/mrov/LethalRichPresenceExperimental/): Makes the discord rich presence more detailed, displaying the current moon, wether you are playing online or LAN, how many players of how many possible players are in your lobby, as well as how much scrap currently is on your ship and which quota you are on.
- Added [ToggleMute by quackandcheese](https://thunderstore.io/c/lethal-company/p/quackandcheese/ToggleMute/): Allows to press `M` to mute oneself.
- Added [LobbyCompatibility by BMX](https://thunderstore.io/c/lethal-company/p/BMX/LobbyCompatibility/): Lets you check a lobbies compatibility and let's you know what was incompatible.
- Added [Left_and_Right_Map_Indicator by AtomicStudio](https://thunderstore.io/c/lethal-company/p/AtomicStudio/Left_and_Right_Map_Indicator/): Adds an `L` and `R` indicator to a player's radar icon.
- Added [KickWithoutBan by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/KickWithoutBan/): Allows for kicking someone without them being banned. Changed [LobbyControl](https://thunderstore.io/c/lethal-company/p/mattymatty/LobbyControl/)'s config to **not auto re-open the lobby.** Manually re-opening per `lobby open` or `open` commands is now required for late- and rejoin.
- Added [NiceChat by taffyko](https://thunderstore.io/c/lethal-company/p/taffyko/NiceChat/): Makes the chat scrollable and less disruptive when unused.
- Added [LoadingInfo by chuxiaaaa](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/LoadingInfo/): Displays how many players have loaded the moon while loading the moon.
- Added [LoadingTips by Enova](https://thunderstore.io/c/lethal-company/p/Enova/LoadingTips/): Displays custom loading tips during loading a moon.
- Added [LessPopups by Venture](https://thunderstore.io/c/lethal-company/p/Venture/LessPopups/): Suppresses the scrap collected HUD element, making it more ambigious if crew members survived.
- Added [CoronerIntegrations by TurkeySteak](https://thunderstore.io/c/lethal-company/p/Turkeysteaks/CoronerIntegrations/): Add support for other modded entities.
- Added [DiFFoZTweaks](https://thunderstore.io/c/lethal-company/p/DiFFoZ/DiFFoZTweaks/): Limits MoreCompanyCosmetics, makes taskbar flash when game awaits input, fixes Soft Mask Incompatibility, allows BepInEx blacklist.
- Added [DissonanceVoiceSettings](https://thunderstore.io/c/lethal-company/p/lukeprime/DissonanceVoiceSettings/): Improves management of voice chat data packages & similar.
- Added [LobbyControl_Experimental by mattymatty](https://thunderstore.io/c/lethal-company/p/mattymatty/LobbyControl_Experimental/): Allows re-opening the lobby per terminal in orbit (**late joining**) as well as changing other lobby settings + lobby fixes.
- Added [SuitSaver](https://thunderstore.io/c/lethal-company/p/Hexnet111/SuitSaver/): Saves last used suit.
- Added [UniqueItemSounds by debit_card_debit](https://thunderstore.io/c/lethal-company/p/debit_card_debit/UniqueItemSounds/): Add custom sounds for different items, both vanilla and modded.

##### Equipment [v2.0.0]

- Added [HexiBetterShotgunFixed by Entity378](https://thunderstore.io/c/lethal-company/p/Entity378/HexiBetterShotgunFixed/) & [HexiShotgunTweaks by dopadream](https://thunderstore.io/c/lethal-company/p/dopadream/HexiShotgunTweaks/).
- Added [Shopping_Cart by WhiteSpike](https://thunderstore.io/c/lethal-company/p/WhiteSpike/Shopping_Cart/)s are now allowed to be used for scrap transportation thanks to WhiteSpike's update to the company code.
- Added [Diving_Kit by WhiteSpike](https://thunderstore.io/c/lethal-company/p/WhiteSpike/Diving_Kit/): Two handed items that allows you to breathe underwater.
- Added [BetterSprayPaintFIXED](https://thunderstore.io/c/lethal-company/p/ddd278/BetterSprayPaintFIXED/): Makes Spray Paint work more reliably, makes shake more effective, reduces volume, makes cruiser paintable, makes capacity infinite, and adds erase functionality.

##### Scraps [v2.0.0]

- Added [TestAccountVariety](https://thunderstore.io/c/lethal-company/p/TestAccount666/TestAccountVariety/): Adds items in reference to the modding community and its creators, and some new hazards.
- Added [LaserPointerDetonator by Kittenji](https://thunderstore.io/c/lethal-company/p/Kittenji/LaserPointerDetonator/): The laserpointer can detonate landmines now.
- Added [ToiletPaperNormalizer](https://thunderstore.io/c/lethal-company/p/giosuel/ToiletPaperNormalizer/): Toilet paper won't cover your entire screen anylonger.

##### Cosmetics [v.2.0.0]

- Added [WaluigiSuitLite by Mattomo](https://thunderstore.io/c/lethal-company/p/Mattomo/WaluigiSuitLite/): For the true WAH-Weegie Fans.
- Added [Gradient_Suits by Endoxicom](https://thunderstore.io/c/lethal-company/p/Endoxicom/Gradient_Suits/)
- Added [StarTrekSuitsCore by Nikki](https://thunderstore.io/c/lethal-company/p/Nikki/StarTrekSuitsCore/)
- Added [SuitsPlus by FREAKS](https://thunderstore.io/c/lethal-company/p/Nikki/StarTrekSuitsCore/)
- Added [Colorful_1000_Quota_Stare by TronMan63304](https://thunderstore.io/c/lethal-company/p/TronMan63304/Colorful_1000_Quota_Stare/): Adds suits.
- Added [NikkisCosmeticKingdom by Nikki](https://thunderstore.io/c/lethal-company/p/Nikki/NikkisCosmeticKingdom/): Adds quite a few neat cosmetics.
- Added [VisorColorsCosmetics by crump_laude](https://thunderstore.io/c/lethal-company/p/crump_laude/VisorColorsCosmetics/).
- Added [EquipmentCompany by companyeomployee](https://thunderstore.io/c/lethal-company/p/companyemployee/EquipmentCompany/): MoreCompany cosmetics.
- Added [Lunxaras_Addons by Lunxara](https://thunderstore.io/c/lethal-company/p/Lunxara/Lunxaras_Addons/): Suits & MoreCompany cosmetics.
- Added [SimpleCompany by Smxrez](https://thunderstore.io/c/lethal-company/p/Smxrez/SimpleCompany/): MoreCompany cosmetics.

##### Performance [v2.0.0]

- Added [BepInEx_MonoMod_Debug_Patcher by DiFFoZ](https://thunderstore.io/c/lethal-company/p/DiFFoZ/BepInEx_MonoMod_Debug_Patcher/).
- Added [LethalSponge by Scoops](https://thunderstore.io/c/lethal-company/p/Scoops/LethalSponge/): Decreases RAM & VRAM usage in exchange for longer inital loading time, optimizes general performance greatly.
- Added [ReXuvination by XuXiaolan](https://thunderstore.io/c/lethal-company/p/XuXiaolan/ReXuvination/) for optimization to collision performance.
- Added [EntranceTeleportOptimizations by mattymatty](https://thunderstore.io/c/lethal-company/p/mattymatty/EntranceTeleportOptimizations/): The enemy activity hint is now also displayed for going outdoors as well, the teleport mechanic is optimized for better performance.
- Added [LightsOut by mrov](https://thunderstore.io/c/lethal-company/p/mrov/LightsOut/): Makes items that emit light stop emitting light when placed in the ship, improving framerate.

#### Fixes [v2.0.0]

- Added [InventoryFixPlugin by DOkge](https://thunderstore.io/c/lethal-company/p/DOkge/InventoryFixPlugin/).
- Added [LethalError by chuxiaaaa](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/LethalError/): Tries to fix `An error occured!` on the client side.
- Added [RagdollDesyncFix by Zaggy1024](https://thunderstore.io/c/lethal-company/p/Zaggy1024/RagdollDesyncFix/).
- Added [TestAccountFixes by TestAccount666](https://thunderstore.io/c/lethal-company/p/TestAccount666/TestAccountFixes/).
- Added [FixCharWarn by huxiaaaa](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/FixCharWarn/) & [FixPlayerName by huxiaaaa](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/FixPlayerName/).
- Added [TypeLoadExceptionFixer by Hamunii](https://thunderstore.io/c/lethal-company/p/Hamunii/TypeLoadExceptionFixer/)
- Added [V73dcfix by hu_luo_bo_ya](https://thunderstore.io/c/lethal-company/p/hu_luo_bo_ya/V73dcfix/): Fixes an issue where clients do not disconnect after the host exits the game.
- Added [v73ncfic by chuxiaaaa](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/v73ncfix/): Fix issues related to late joining.
- Added [ApparatusFix](https://thunderstore.io/c/lethal-company/p/mrov/ApparatusFix/): Fixes Apparatus desync.
- Added [NetworkMetricsFix](https://thunderstore.io/c/lethal-company/p/chuxiaaaa/NetworkMetricsFix/): Optimize network analyzer
- Added [ReviveDesyncPatch by DaanSmoki](https://thunderstore.io/c/lethal-company/p/DaanSmoki/ReviveDesyncPatch/): Fix an issue where players would not respawn in lobbys greater than 4.

#### Libraries & APIs [v2.0.0]

- Added [LethalLevelLoaderUpdated by pacoito](https://thunderstore.io/c/lethal-company/p/pacoito/LethalLevelLoaderUpdated/): Makes LLL compatible with V73.

### Changed [v2.0.0]

#### Major Changes [v2.0.0]

- Reworked the weather weights for [WeatherRegistry by mrov](https://thunderstore.io/c/lethal-company/p/mrov/WeatherRegistry/), making it less crazed and more vanilla-like, as well as properly integrating the new weathers added, [as detailed here](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Weather-Registry-&-Tweaks).
- Reworked the weather scrap value and quantity multipliers to incentivise visiting moons with weather conditions while not making it absurdly over powered, [as detailed here](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Weather-Registry-&-Tweaks).
- Reworked [Lategame_Upgrades](https://thunderstore.io/c/lethal-company/p/malco/Lategame_Upgrades/):
  - Set Drop Ship Thrusters Upgrade & Sick Beats to auto enable.
  - Buffed Night Vision Goggles.
  - It now uses alternative currency, Player Credits (PC), [as explained here](https://github.com/Team-Rebirth/Lethal-Rebirth/wiki/Lategame-Upgrades).
  - The configuration for the item progression has also been adjusted to properly consider every apparatus for unlocking the next cheapest upgrade.
  - There have been price rebalances across the board to make most initial increments cost less for less effect, which is then balanced out with additional or more costly increments after, encouraging upgrade variety.
  - The Deep Pockets upgrade has been disabled.
  - The Medical Nanobots & Effective Bandaids have been disabled in favor of [NaturalHealthRegen by swaggies](https://thunderstore.io/c/lethal-company/p/Swaggies/NaturalHealthRegen/).
- Reduced the number of [ReservedUtilitySlot by FlipMods](https://thunderstore.io/c/lethal-company/p/FlipMods/ReservedUtilitySlot/) to one, lowered the price for the inital slot, and increased the price distance between the intial and second slot.
- Enabled [ScienceBird_Tweaks'](https://thunderstore.io/c/lethal-company/p/ScienceBird/ScienceBird_Tweaks/) Zap Gun rework, which allows it to disable hazards and open shelter doors in addition to configured increased battery. Also enhanced the ship's floodlights and enabled the experimental scanned item highlight.

#### Minor Changes [v2.0.0]

- Configured [HostFixes by CharlesE2](https://thunderstore.io/c/lethal-company/p/CharlesE2/HostFixes/) to disallow PvP inside the ship.
- Adjusted spawn weights for [ImmersiveScrap by XuXiaolan](https://thunderstore.io/c/lethal-company/p/XuXiaolan/ImmersiveScrap/).
- Adjusted [RestoreMapper by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/RestoreMapper/) to have a lower quality (for performance) and display the path back out.
- Rebalanced the [Wheelbarrow by WhiteSpike](https://thunderstore.io/c/lethal-company/p/WhiteSpike/Wheelbarrow/).
- Adjusted [OpenBodyCams by Zaggy1024](https://thunderstore.io/c/lethal-company/p/Zaggy1024/OpenBodyCams/) to have better night vision.
- [EliteFlashlight by MissileMann](https://thunderstore.io/c/lethal-company/p/MissileMann/EliteFlashlight/) now only costs 35c.
- Adjusted the [Locker by zealsprince](https://thunderstore.io/c/lethal-company/p/zealsprince/Locker/) to go for a second dash less often and re-distributed spawn chances.
- Buffed the Weed Killer configuration using [WeedKillerAdjuster by OniroDev](https://thunderstore.io/c/lethal-company/p/OniroDev/WeedKillerAdjuster/) & [WeedKillerTweaks by Furiante](https://thunderstore.io/c/lethal-company/p/Furiante/WeedKillerTweaks/).
- Made the Kidnapper Fox unable to spawn on Embrion, using [YesFox by Dev1A3](https://thunderstore.io/c/lethal-company/p/Dev1A3/YesFox/).
- Adjusted chances for [HalloweenAction](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/HalloweenAction/), [HalloweenElevator](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/HalloweenElevator/), and [SnowyHolidayDropship by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/SnowyHolidayDropship/).
- Adjusted [KidnapperFoxSettings by Zehs](https://thunderstore.io/c/lethal-company/p/Zehs/KidnapperFoxSettings/) to make the Fox Squishy.
- Configured [More_Suits by x753](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/) to not squish the suits on the rack.
- Added probabilities for [Chameleon](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/Chameleon/)'s new cave/rock types.
- Adjusted [ButteryFixes by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/ButteryFixes/) to not add indoor power for Mask Hornets.
- Adjusted [ButteRyBalance](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/ButteRyBalance/): Enabled Kidnapper Squishy setting, reduce radar booster cost to 50c, nerf price of stun grenades to 40c, enabled nerf foggy weather (in case one switches to vanilla mode), enabled masks spawning rarely on lower tier moons and allows masked infestations IN CASE Mirage is deactivated, enabled all interior spawn adjustments, enabled the kill switch for all moon settings to prevent any potential spawn weight-related problems.
- Adjusted invulnerability settings in [CruiserImprovements by DiggC](https://thunderstore.io/c/lethal-company/p/DiggC/CruiserImproved/) and enabled the booster seat syncronization.
- Configured the Toy Store interior from [WesleysInteriors by Magic_Wesley](https://thunderstore.io/c/lethal-company/p/Magic_Wesley/WesleysInteriors/) to be more spooky.
- Adjusted the interior weights in [LethalLevelLoader by IAmBatby](https://thunderstore.io/c/lethal-company/p/IAmBatby/LethalLevelLoader/) to make all of Wesley's & Generic's Interiors appear a little more regularly on the vanilla moons, except for the Rubber Rooms which has it chances more equalized and the Grand Amory which had its chances for specific moons increased and decreased outside of that.
- Adjusted [MaskFixes by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/MaskFixes/) to have an increased chance for masks to spawn with tragedy masks (in case Mirage is disabled).
- Changed [JetpackFixes by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/JetpackFixes/) to change the jetpacks behavior to explode when going too fast.

### Removed [v2.0.0]

- Removed [Slaughterhouse](https://thunderstore.io/c/lethal-company/p/Nikki/Slaughterhouse/) (& [SlaughterhouseScraps](https://thunderstore.io/c/lethal-company/p/Nikki/SlaughterhouseScraps/)) due to lockpicker incompatible doors.
- Removed [TakeThatMaskOff](https://thunderstore.io/c/lethal-company/p/SillySquad/TakeThatMaskOff/) due to multiple mods offering that functionality as an option and Mirages (Masked) not visually displaying masks to begin with.
- Removed [LethalCasino](https://thunderstore.io/c/lethal-company/p/mrgrm7/LethalCasino/) due to balancing concerns, instead now dearly recommended.
- Removed [LethalCasinoTweaks](https://thunderstore.io/c/lethal-company/p/confusingus/LethalCasinoTweaks/) due to observed errors in Black Jack.
- Removed [MirrorDecor](https://thunderstore.io/c/lethal-company/p/quackandcheese/MirrorDecor/) due to significant performance hits. Now among recommended Mods.
- Removed [AstolfoPlushie](https://thunderstore.io/c/lethal-company/p/Lugom/AstolfoPlushie/) due to disruptive, non-vanilla conforming, sound design. Now among recommended mods.
- Removed [SpikeTrapFixes](https://thunderstore.io/c/lethal-company/p/SpookyBuddy/SpikeTrapFixes/) for breaking the Spike Trap Cooldown Animation (as implemented by ScienceBirdTweaks) & making the spike trap remain deactivated indefinitively.
- Removed [No_Console_Spam](https://thunderstore.io/c/lethal-company/p/4902/No_Console_Spam/) for breaking the Zap Gun Rework (as implemented by ScienceBirdTweaks).
- Removed [Moved_Magnet_Switch](https://thunderstore.io/c/lethal-company/p/AtomicStudio/Moved_Magnet_Switch/) due to the magnet switch hitbox being misplaced.
- Removed [Atomics_Suits](https://thunderstore.io/c/lethal-company/p/AtomicStudio/Atomics_Suits/) due to Suit Desync.
- Removed [WalkieRevamped](https://thunderstore.io/c/lethal-company/p/swny/WalkieRevamped/).
- Removed [Symbiosis](https://thunderstore.io/c/lethal-company/p/NiceHairs/Symbiosis/) due to inactive dev and too little gameplay influence.
- Removed [Lethal_Missions](https://thunderstore.io/c/lethal-company/p/Nozz/Lethal_Missions/) due to errors.
- Removed [ManiaBania's 1K Quota Stare](https://thunderstore.io/c/lethal-company/p/ManiaBania/1000_Quota_Stare/) in favor for the extended selection provided by [Colorful_1000_Quota_Stare by TronMan63304](https://thunderstore.io/c/lethal-company/p/TronMan63304/Colorful_1000_Quota_Stare/).
- Removed [MaskTheDead](https://thunderstore.io/c/lethal-company/p/F4ilS4fe/MaskTheDead/) in favor of [MirageRevive by qwbarch](https://thunderstore.io/c/lethal-company/p/qwbarch/MirageRevive/).
- Removed [Hold_Scan_Button](https://thunderstore.io/c/lethal-company/p/FutureSavior/Hold_Scan_Button/) in favor of the implementation from [LethalHUD by s1ckboy](https://thunderstore.io/c/lethal-company/p/s1ckboy/LethalHUD/).
- Removed [SpectateEnemies](https://thunderstore.io/c/lethal-company/p/AllToasters/SpectateEnemies/) in favor of [Poltergeist by coderCleric](https://thunderstore.io/c/lethal-company/p/coderCleric/Poltergeist/).
- Removed [Arachnophilia](https://thunderstore.io/c/lethal-company/p/SillySquad/Arachnophilia/).
- Removed [NoMoreCompanyLogo](https://thunderstore.io/c/lethal-company/p/DaXcess/NoMoreCompanyLogo/)
- Removed [FacilityMeltdown](https://thunderstore.io/c/lethal-company/p/loaforc/FacilityMeltdown/)
- Removed [Malfunctions](https://thunderstore.io/c/lethal-company/p/zealsprince/Malfunctions/)
- Removed [BetterSprayPaint](https://thunderstore.io/c/lethal-company/p/taffyko/BetterSprayPaint/)
- Removed [KidnapperFoxSettings](https://thunderstore.io/c/lethal-company/p/Zehs/KidnapperFoxSettings/)
- Removed [YesFox](https://thunderstore.io/c/lethal-company/p/Dev1A3/YesFox/)

### Fixed [v2.0.0]

- Extended the cookie2D Atlas from [LethalPerformance by DiFFoZ](https://thunderstore.io/c/lethal-company/p/DiFFoZ/LethalPerformance/).
- Configured [FontUpdate by rectorado](https://thunderstore.io/c/lethal-company/p/rectorado/FontUpdate/) to no longer replace the credit symbol with a dollar.

### Noted [v2.0.0]

- Updated dependencies.
- Added missing crediting in the mod list.
- Overhauled the past Changelog to be uniformely dry and to the point.
- Died typing out the masses of documentation for this modpack, not to mention structuring it to be accessible and non-overwhelming.
  - Oh boy way it fun to rewrite 2 weeks work because I 1. did not push it, 2. accidentally used git restore :p
  - Also, **we have a Wiki now!**
- Will refer to "Masked" entities as "Mirages" from now.
- Settled for [ButteryFixes by ButteryStancakes](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/ButteryFixes/) instead of [GeneralImprovments by ShaosilGaming](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/GeneralImprovements/) to handle the fire exit rotation fix, which makes you face the interior instead of the fire exit upon entry, disabled Mask Hornet Indoor Power.
- Added all new mods to the [Mod list](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/docs/Mods.md). Also added missing crediting in said list.

## [v1.1.0] - 2025-08-28 | The Initiation Update (v72)

Delayed arrival due to minor technical difficulties. A collection of mods we stumbled upon and found worth including.

### Added [v1.1.0]

#### Quality of Life

- Added [CoronerMimics by EliteMasterEric](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/CoronerMimics/): Adds custom and new performance/death reports specifically for the [Mimics by x753](https://thunderstore.io/c/lethal-company/p/x753/Mimics/).
- Added [TooManySuits by Verity](https://thunderstore.io/c/lethal-company/p/Verity/TooManySuits/): Adds pages to the suit racket.
- Added [ScienceBird_Tweaks by ScienceBird](https://thunderstore.io/c/lethal-company/p/ScienceBird/ScienceBird_Tweaks/): Adds Better Shotgun tooltips, specific scrap or scrap with a value of 0c being retained (like beloved plushies to collect), minor ship clean-up (removing tubes & wires, helmet, stray batteries) & collision fixes regarding teleporter placement, proper blackouts on Apparatus removal, and proper hazard deactivation signals.
- Added [LessLogs by facodxb](https://thunderstore.io/c/lethal-company/p/falcodxb/LessLogs/)
- Added [No_Console_Spam by 4902](https://thunderstore.io/c/lethal-company/p/4902/No_Console_Spam/)
- Added [NoMoreCompanyLogo by DaXcess](https://thunderstore.io/c/lethal-company/p/DaXcess/NoMoreCompanyLogo/)

##### Scraps [v1.1.0]

- Added [Polished_Plushies_and_Silly_Scrap by ScienceBird](https://thunderstore.io/c/lethal-company/p/ScienceBird/Polished_Plushies_and_Silly_Scrap/): Miku, Teto, Frieren and more!
- Added [AstolfoPlushie by Lugom](https://thunderstore.io/c/lethal-company/p/Lugom/AstolfoPlushie/) for a friend: It's cuddly.

##### Cosmetics [v.1.1.0]

- Added [Atomics_Suits by AtomicStudio](https://thunderstore.io/c/lethal-company/p/AtomicStudio/Atomics_Suits/)
- Added [PigeonsCosmeticsAddon by BigBadPigeon](https://thunderstore.io/c/lethal-company/p/BigBadPigeon/PigeonsCosmeticsAddon/)
- Added [Atomics_Cosmetics by AtomicStudio](https://thunderstore.io/c/lethal-company/p/AtomicStudio/Atomics_Cosmetics/)
- Added [1000_Quota_Stare by ManiaBania](https://thunderstore.io/c/lethal-company/p/ManiaBania/1000_Quota_Stare/): A Suit.
- Added [SCP_Foundation_Suit](https://thunderstore.io/c/lethal-company/p/TeamClark/SCP_Foundation_Suit/)

#### Fixes [v1.1.0]

- Added [SlimeTamingFix by EliteMasterEric](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/SlimeTamingFix/): Slimes can now be tamed per Boombox.
- Added [BoomboxSyncFix by FutureSavior](https://thunderstore.io/c/lethal-company/p/FutureSavior/Boombox_Sync_Fix/)
- Added [ScanforItemsFix by ThePotato](https://thunderstore.io/c/lethal-company/p/ThePotato/scanForItemsFix/)

### Fixed [v1.1.0]

- Changed [BetterFog](https://thunderstore.io/c/lethal-company/p/ironthumb/BetterFog/) foggy presets to be a bit more tolerable (foggy weather is slightly more comfortable/playable than in vanilla this way).
- Fixed minor error (using a dot instead of a comma) in the [Chameleon](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/Chameleon/) configuration regarding snowy windows.

### Noted [v1.1.0]

- Updated dependencies & removed unneeded configs.
- Proper ReadMe & Documentation on the mods included and specific configurations on our [GitHub Repository](https://github.com/Team-Rebirth/Lethal-Rebirth/tree/main)!
- Removed [AtomicStudio's Better Shotgun Tooltips](https://thunderstore.io/c/lethal-company/p/AtomicStudio/Better_Shotgun_Tooltip/) in favor of its implementation in [ScienceBird_Tweaks by ScienceBird](https://thunderstore.io/c/lethal-company/p/ScienceBird/ScienceBird_Tweaks/).
- We now have a changelog.

## [v1.0.0] - 2025-08-25 | Initial Release (v72)

The initial upload of the modpack. We hope to provide you with the best Lethal Company experience thus far! Let us know if you have feedback per Issue or other in the [README](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/README.md) outlined ways in the future :3

- - -
