# Kerbal Stellar Frontiers
## A planet pack with unique and potentially interesting worlds across 2 stars
## Work in progress! The release under releases is extremely outdated!

## Novus System
* Novus, a large blue-white star that's the result of a stellar merger, wreaking chaos in the system
* Ardor, a large hot super-joolian world that orbits Novus at an extremely short distance
    * Adaris, a shattered lava moon scarily close to Ardor, bombarded by Novus's light and tidally wrecked by Ardor.
* Ferrum, an iron and copper rich world that was once like Duna. But it lost its atmosphere and water long before Novus's existence.
* Helia, a sterile, hot and humid dried-up hycean world, massive flats mixed with extreme mountains and volcanism, hazy and misty with a perpetual rain
* Mirage, habitable paradise turned desert world. Sorta breathable, though the temperature would kill a Kerbal under the sun. Unstable climate and weather.
* Khion, a lonely cold white-blue ice giant which is heating up slightly
    * Boreas, a Vall clone with an atmosphere and strange weather. A slick melting ice ball with polar snow storms and sparse lakes.
    * Cairn, a foggy cold moon containing jagged highlands with odd eroded valleys and flats. Can provide gravity assists/capture for Khion.
    * The wormhole is here, linking from Moho.
* Nimis, a highly elliptical gilly-sized comet with an immense tail.

## PDS70 System -- Very unfinished!
* PDS70, roughly inspired by real life. A young orange dwarf with an immense protoplanetary disk
* Cinis, a newly born lava and ash ridden world. Exceptionally hot and unstable surface. Contains its own smaller disk just like its star.
* Zero work done yet: Furen, essentially a newly born brown dwarf with 1-2 protomoons. An extremely hot and large gas giant

## Todo
* Helia Homeswitch
* Helia volcano visuals
* Wet surface configs
* Parallax scatter configs for the following: Helia, Cairn, Nimis(maybe)
* Fix polar "keyhole" anomalies on some worlds. Byproduct of heightmap process :/ (I may not do for a while! Would require redoing height, and normal and parallax min/max)
* Mirage rings?
* Re-Do nimis's tail
* Fix Boreas's ocean node missing reflections

## Implemented at a later date
* Optimization:
    * Downscaling some textures
    * EVE tweaks
    * Other stuff I cant think of
    * Not a priority
* Misc stuff
* * Better lava on Helia, or lava texture at all
* * Fix killzone for lava on Helia weirdly not working
* * Science Definitions
* * Nicer displacement + AO maps
* Pretty readme/perhaps wiki with screenshots
* **Release**

## Requirements
* Kopernicus obviously
* Parallax Continued. Yes, this is a hard dependency!
* For wormholes if theyre enabled:
* * Kopernicus Expansion
* * Singularity
* VertexColormapEmissive and VertexMitchellNetravaliHeightMap
* V5 scatterer and volumetrics
    * In the far future I might add 2D cloud support for EVE-Redux and make parallax continued optional. V3 scatterer **may** be compatible, though I never tested it

## Optional
* BurstPQS: __This pack uses a lot of complicated PQS/terrain setups that are very costly on low-end hardware, I would *highly* recommend this__

## Supported mods
* Scaled Decorator, Nimis's tail and PDS70 disk(s)
* TiltEm Continued
* Blueshift configs for the system
* Kronometer so day/year time is right for homeswitch
* Star systems
* * Not tested right now, really just KSS2 is known not to conflict
* * System-replacers are incompatible with homeswitch
* * Kcalbeloh compatible(?)

`This project is licensed under GPLv3, with some exceptions. See LICENSE.md and LICENSEINFO.md`