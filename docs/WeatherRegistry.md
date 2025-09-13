# WeatherRegistry

> Describes V1.2.0.

WeatherRegistry uses a weight based system to determine weather probabilities. To make it easier to overview and maintain we have decided to make sure that the maximum total weight when all weathers are weighted should be 1000, allowing us to work with percents with one decimal. A weight of 505 is equal to 50.5%.

Relational Weather Weights (weather-to-weather, moon-based weather weights) are also determined with this in mind.

Due to our [BetterFog Configuration](https://github.com/Team-Rebirth/Lethal-Rebirth/blob/main/docs/BetterFog.md), which features seperate presets for eclipsed and foggy weathers, we have deactivated all weathers that either combine or transition in/out of these conditions to prevent errors in BetterFog's autosync option.

## WeatherTweaks

We also have WeatherTweaks installed, which adds weather uncertainty mechanics. `Foggy?` for example has a 67% chance to be foggy and a 33% chance to be something else. `Foggy/Blackout` would be a 50/50 change for either weather but we have disabled this uncertainty mechanic due to it being rather unintuitive. Lastly, it can display `[UNKNOWN]` which simply withhelds the chosen weather from you.

WeatherTweaks also adds some kind of difficulty multiplier, which we do not yet understand and (presumably) disabled.

## Weather Weights

- 1000 for all Weathers in Total

- 375 for Neutral Weathers | 37.5% chance for neutral weather conditions to occur on any moon.

- 175 for Transitional Weathers | 15.5. chance for transitional weathers to occur on any moon.

- 325 for Bad Weather | 35% of the available moons will have bad weather on average

- 125 for Combined Weathers | 12.5% of the available moons will have multiple bad weathers

### Neutral Weathers

- None: 200
- Cloudy: 100
- DustClouds: 75

### Bad Weathers

- Foggy: 50
- Rainy: 75
- Flooded: 50
- Stormy: 50
- Eclipsed: 25
- Blackout: 75

### Transitional Weathers

- None > Stormy: 75
- Stormy > Rainy: 50
- None > Blackout: 50
- ~~None > Foggy~~
- ~~Foggy > None~~
- ~~Eclipsed > Foggy~~
- ~~Eclipsed > None~~
- ~~Rainy > Eclipsed~~

### Combined Weathers

- Foggy + Rainy: 15
- Foggy + Flooded: 15
- Foggy + Blackout: 7
- Rainy + Flooded: 15
- Rainy + Blackout: 7
- Stormy + Rainy: 21
- Stormy + Flooded: 7
- Stormy + Rainy + Eclipsed: 6
- Stormy + Rainy + Flooded: 10
- Stormy + Rainy + Flooded + Eclipsed: 5
- Eclipsed + Rainy: 6
- Eclipsed + Flooded: 6
- Eclipsed + Blackout: 5
- ~~Foggy + Eclipsed~~

### Weather Type Overview

- Any Foggy: 87
- Any Rainy: 213
- Any Flooded: 108
- Any Stormy: 149
- Any Eclipsed: 54
- Any Blackout: 144

## Relational Weather Weights

DustClouds can not appear on Dine, Rend, Titan, and Artifice, as those are blizzard planets, and have been substituted with Cloudy for these moons.

Aside from that, only eclipsed weather conditions have weather-to-weather weights making it impossible for eclipsed conditions to be followed by another eclipsed condition. More configuration is planned.

### Ideas

- DustClouds could be more often followed by foggy and blackout, perhaps. Could work as a harmless indicator for badness brewing
- Cloudy should have a high chance to become rainy, stormy, flooded or multiple. Could work as yet another harmless indicator for badness brewing
- March will have the any rainy weather weight increased, replacing dustclouds partially, and none decreased.
- Vow & Adamance will have a slight any rainy chance and cloudy chance increase, replacing dustclouds.
- Offense & Assurance will have a lower any rainy chance.
- Reduce Cloudy substitution for Rend, Dine, Titan, and Artifice in exchange for a slight increase in any stormy/flooded/blackout.

- - -
