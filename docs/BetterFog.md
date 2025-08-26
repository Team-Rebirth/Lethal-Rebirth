# BetterFog Configuration Guide

We completely reworked the better fog configuration file as we found that, in its common configuration, it was generally too lenient in comparison to vanilla, especially on the snowy moons. Additionally, we wanted to use the fog coloration to make the environments more atmospheric and immersive.

## Our Approach

We took an approach of almost completely neglecting the weather multipliers, only having them factor in very subtly for rainy, flooded, and stormy. For foggy and eclipsed we use custom presets.

Moon scaling is also less relevant here but the primary distinction for moons using the same preset. Thus, for example, Assurance and Offense (which share the "Dust" preset with Embrion) have different moon scales, which leads to offense being quite a bit less foggy in comparison.

### Presets

For all non-eclipse presets there exists a foggy alternative.

Dust -> Foggy Dust

It also has to be acknowledged that on the snowy moons, like Rend & Dine, there is a blizzard-like fog, which thus demands special treatment.

- (Foggy) Experimentation: It is the beginner moon and thus has more lenient fog. Its hue is also adapted to fit Experimentation more.
- (Foggy) Dust: For Assurance, Offense, and Embrion.
- (Foggy) Forest: For Vow & March.
- (Foggy) Adamance: For adamance only due to the special foliage.
- (Foggy) Snow: For Rend & Dine.
- (Foggy) Titan: For Titan.
- (Foggy) Artifice: Thanks to being able to both be a non-blizzard or blizzard planet, thanks to [ArtificeBlizzard](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/ArtificeBlizzard/), it required special attention.
- Eclipsed: Used for eclipsed weather on all **non-blizzard moons.**
- Eclipsed Blizzard: Used for eclipsed weather on all **blizzard moons.**
- Eclipsed Artifice: Thanks to being able to both be a non-blizzard or blizzard planet, thanks to [ArtificeBlizzard](https://thunderstore.io/c/lethal-company/p/ButteryStancakes/ArtificeBlizzard/), it required special attention for eclipsed weather as well.
