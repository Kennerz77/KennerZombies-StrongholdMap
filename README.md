# Dr K's SPZombies Stronghold Map

**Stronghold**, the first map for **Dr K's SPZombies**. Where it all started: a strange rock landed in Customs, Reshala's boys got hold of it and ran, and everyone turned. Hold out in the old factory against the never-ending nightmare: barricaded windows, doors to buy, a basement to fight down into, and an exfil that opens if you last long enough.

Version 0.1.0, for **SPT 4.1.6**. Made by **Kenner**.

## Requirements

| Mod | Version | Why |
|---|---|---|
| SPT | 4.1.x (made on 4.1.6) | |
| [Dr K's SPZombies](https://github.com/Kennerz77/KennerZombiesSPT) (and its requirements) | 0.1.0 or newer | The zombies mode this map is for |
| [Tushonka Mapping SDK](https://sp-mod.com/mod/3193/tushonka-mapping-sdk) by **mizmii** (its CustomMapLoader) | 1.9.3 or newer | Loads the map |

## Installing

1. Close the game and the SPT server.
2. Extract the zip into your SPT folder (the one with the `SPT_Runtime` folder). You should end up with:
   - `BepInEx\plugins\CustomMapLoader\bundles\maps\zm_stronghold*` (the map itself)
   - `SPT_Runtime\user\mods\CustomMapLoader\maps\zm_stronghold\`
   - `BepInEx\plugins\Kennerz_ZM_Stronghold\maps\` (the zombies layout, sounds and pictures)
3. Start the server, then the game. In zombies mode, Stronghold shows up on the map screen and in the lobby's map list.

**Fika headless:** copy the two `BepInEx\plugins` folders onto the headless install as well, or matches it hosts can't load the map.

## Compatibility

- Never changes another mod's files, settings or load order. CustomMapLoader is used as it is.
- Only shows up in zombies mode: the normal map screen doesn't list it.

## Uninstalling

Delete the three places above.

## Credits

- **[Tushonka Mapping SDK](https://sp-mod.com/mod/3193/tushonka-mapping-sdk)** by **mizmii**, with **Manimal1920** (and thanks to **elgreco505**): the map was built with the SDK and is loaded by its CustomMapLoader. Not included.
- Made by Kenner.

## Changelog

- **0.1.0:** first release.
