# Dr K's SPZombies Stronghold Map

**Stronghold**, the first map for **Dr K's SPZombies**. Where it all started: a strange rock landed in Customs, Reshala's boys got hold of it and ran, and everyone turned. Hold out in the old factory against the never-ending nightmare: barricaded windows, doors to buy, a basement to fight down into, and an exfil that opens if you last long enough.

Version 0.2.0, for **SPT 4.1.6**. Made by **Kenner**.

## Requirements

| Mod | Version | Why |
|---|---|---|
| SPT | 4.1.x (made on 4.1.6) | |
| [Dr K's SPZombies](https://github.com/Kennerz77/KennerZombiesSPT) (and its requirements) | 0.2.0 or newer | The zombies mode this map is for |

## Installing

1. Close the game and the SPT server.
2. Extract the zip into your SPT folder (the one with the `SPT_Runtime` folder). You should end up with:
   - `BepInEx\plugins\Kennerz_ZM_Stronghold\` with `bundles` (the map itself), `server` (its server settings) and `maps` (the zombies layout, sounds and pictures)
3. Start the server, then the game. In zombies mode, Stronghold shows up on the map screen and in the lobby's map list.

**Fika headless:** copy `BepInEx\plugins\Kennerz_ZM_Stronghold` onto the headless install as well, or matches it hosts can't load the map.

**Updating from 0.1.0:** 0.1.0 also put files in other places. Delete `BepInEx\plugins\CustomMapLoader\bundles\maps\zm_stronghold*` and `SPT_Runtime\user\mods\CustomMapLoader\maps\zm_stronghold`, and both `CustomMapLoader` folders if nothing else is left in them. That also stops the server's "No Assemblies found in path: ...\user\mods\CustomMapLoader" error.

## Compatibility

- Never changes another mod's files, settings or load order.
- Only shows up in zombies mode: the normal map screen doesn't list it.

## Uninstalling

Delete `BepInEx\plugins\Kennerz_ZM_Stronghold`.

## Credits

- Made by Kenner.

## Changelog

- **0.2.0:** more barricaded windows and new openings in the factory, with more zombie spawns. Zombies now drop down from the upper walkways to follow you instead of getting stuck on the stairs. The stray blue cube is gone. Every wall piece you can see is now solid. No other mod needed any more: SPZombies 0.2.0 loads the map itself, and everything is in one folder.
- **0.1.0:** first release.
