---
title: 'Seasons'
layout: single
permalink: /seasons
---

VerdantAges uses [Fabric Seasons](https://modrinth.com/mod/fabric-seasons) to implement the concept of Spring, Summer, Fall and Winter. In the top-right corner, you will see the current season, followed by the current day out of the total days for that season (provided by [SeasonHUD](https://modrinth.com/mod/seasonhud-fabric)).

We have configured the duration of the seasons to be:

- Spring: 28 days
- Summer: 56 days
- Fall: 28 days
- Winter: 14 days

Keep in mind that the seasons affect the overall temperature, what plants will grow best, and some biomes will even experience different weather (i.e snow or rain). The winter will be the hardest to survive, so we highly recommend you have warm armour and a good base by this point. This is why we increased the duration of the other seasons and decreased the duration of winter.

Biomes have different temperatures depending on the current season:

 - Cold Biomes will have rain in the summer
 - Temperate Biomes will have snow in the winter
 - Tropical Biomes will have a steady season all year round
 - Hot Biomes will have a rainy season in the winter

There is a tooltip displayed when hovering over any seeds that indicates how well it will grow in the current season as well as it's preferred season.

VerdantAges also includes [Fabric Season Extras](https://modrinth.com/mod/fabric-seasons-extras) which adds specialty blocks to help you deal with the seasonal impact on crop growth by building greenhouses. Specifically,


 - Greenhouse Glass: Passive block that creates a warmer microclimate
 - Tinted Greenhouse Glass: Passive block that creates a colder microclimate
 - Crop Heater: Active machine that can create a warmer microclimate with up to 3 levels
 - Crop Chiller: Active machine that can create a colder microclimate with up to 3 levels

Additionally, if you are a redstone builder, there is a "season detector" component that outputs a redstone signal based on the current season and the block's configuration.
