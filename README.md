# ValheimEndgame
A heavily modded Valheim repo for Clients and Servers running `v0.205.5`. Rediscover Valheim and embark on a new Adventure!

## For the best experience we recommend:
- Create a new Character and a new World for the whole experience
- Add steam launch options: `-window-mode exclusive -screen-fullscreen`
- Add `gfx-enable-jobs=1` and `gfx-enable-native-gfx-jobs=1` in valheim_Data\boot.config
- HD Texture Pack for Clients NOT the Server: https://www.nexusmods.com/valheim/mods/302
- Do NOT use VulcanAPI

It's also recommended to disable auto-update on your server and clients because if an update releases we want check for compatibility first and wait for possible mod updates.



## To suit your taste:
Have a lot of trolls on the server and want to save your own items:
- ValheimDedicatedServer\BepInEx\config\valheim_plus.cfg
   - Disable Ward section

Feel like it's too hard:
- ValheimDedicatedServer\BepInEx\config\org.bepinex.plugins.creaturelevelcontrol.cfg
   - Adjust Difficulty and/or DMG and HP per Star



## How to install:
- Navigate to your Steam Library
- Right click Valheim -> Manage -> Browse Local files and leave the folder open
- Grab the latest version for your Client or your Server here: https://github.com/KimoriWasTaken/ValheimEndgame/releases/latest
- Download, save and extract it with [winrar](https://www.win-rar.com/download.html)
- Open the extracted folder
- Now copy all the contents of that folder into the prior opened Valheim folder
- Close the windows we opened and double check that we did it right
- Right click Valheim -> Manage -> Browse Local files
- If you did everything right you should see `BepInEx`, `doorstop_libs`, `MonoBleedingEdge`, `unstripped_corlib`, `valheim_Data`, `doorstop_config.ini`, `steam_appid.txt`, `UnitiCrashHandler.exe`, `UnityPlayer.dll`, `valheim.exe`, `winhttp.dll` in the same folder.



## How to upate:
Every release there will be a `PatchFromLastVersion.rar` that you can download and put into your Valheim folder for those with slower internet speeds.



## To-Do List:
- Fix Desyncs
   - Waiting for Network mod updates
- Optimize Valheim Legends balancing
   - Damage seems minimal at first and overpowered once leveled
- Add Backpacks to the loottable
   - They deserve it
- Optimize Boss difficulty
   - They should be a challange at first and when you have to farm them
- Serpent isn't scary enough
   - Either boats get oneshot or they are indestructable...
- Add another Endgame difficulty spike
   - Equipment is there, just need to add more stars
   - Looking into [ForgottenBiomes](https://valheim.thunderstore.io/package/AlreeNicolas/Forgotten_Biomes/) and [DoOrDieMonster](https://valheim.thunderstore.io/package/Horem/DoOrDieMonsters/) right now
- ~~Cleanup unedited cfg's so clients/servers generate their own to minimize errors~~



## Known Issues:
- In rare instances dying seems to decrease performance and spams an error that is being investigated
- EpicLoot pushes you into Tier3 (iron) loot seemingly at random
- Monk needs 400 stamina for his flying kick sometimes



## Mods Included, configured and balanced:
- [Atos Arrows](https://www.nexusmods.com/valheim/mods/1301) `v1.0.0`
- [BepInEx](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/) `v5.4.16.0`
- [Blacksmith Tools](https://valheim.thunderstore.io/package/GoldenJude/Blacksmiths_tools/) `v2.0.1`
- [Clutter](https://www.nexusmods.com/valheim/mods/1350) `v0.1.0`
- [Creature Level and Loot Control](https://valheim.thunderstore.io/package/Smoothbrain/CreatureLevelAndLootControl/) `v4.4.5`
- [Configuration Manager](https://github.com/aedenthorn/ValheimMods/tree/master/ConfigurationManager) `v0.5.0`
- [Discard Inventory Item](https://www.nexusmods.com/valheim/mods/45) `v0.7.0`
- [Diving Mod](https://www.nexusmods.com/valheim/mods/1271) `v1.2.2`
- [Easy Translate](https://github.com/MLIMG/Easy-Translate) `v1.0.0`
- [Epic Endgame](https://www.nexusmods.com/valheim/mods/1505) `v1.0`
- [Epic Loot](https://github.com/RandyKnapp/ValheimMods/tree/main/EpicLoot) `v0.8.7`
- [Equipment and Quickslots](https://github.com/RandyKnapp/ValheimMods/tree/main/EquipmentAndQuickSlots) `v2.0.14`
- [Extended Item Data Framework](https://github.com/RandyKnapp/ValheimMods/tree/main/ExtendedItemDataFramework) `v1.0.5`
- [HookGenPatcher](https://github.com/harbingerofme/Bepinex.Monomod.HookGenPatcher) `v1.2.0.0`
- [Hugos Armory](https://github.com/Hugo-the-Dwarf/ValheimMoreTwoHanders) `v5.0.1`
- [Jotunn](https://github.com/Valheim-Modding/Jotunn) `v2.4.1`
- [Jotunn Backpacks](https://www.nexusmods.com/valheim/mods/1416) `v2.0.0`
- [Judes Equipment](https://valheim.thunderstore.io/package/GoldenJude/Judes_Equipment/) `v1.4.0`
- [Potions Plus](https://www.nexusmods.com/valheim/mods/1561) `v3.0.2`
- [Sell That](https://www.nexusmods.com/valheim/mods/232) `v1.2.0`
- [Speedy Paths](https://www.nexusmods.com/valheim/mods/452) `v1.0.5`
- [Use Equipment in Water](https://www.nexusmods.com/valheim/mods/121) `v0.2.2.0`
- [Valheim Legends](https://www.nexusmods.com/valheim/mods/796) `v0.4.2`
- [Valheim Plus](https://valheim.plus/) `v0.9.9`
