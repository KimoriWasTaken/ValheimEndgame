# ValheimEndgame
A heavily modded Valheim repo for Clients and Servers running `v0.205.5`. Rediscover Valheim and embark on a new Adventure!
The goal is to preserve the original principle of Valheim and just add more content mods, qol mods and their respective depencies.
After that we try to integrate all the mods into each other and balance them so they work together and feel like one big mod.



## For the best experience we recommend:
- Create a new Character and a new World
- Steam Properties:
   - Disable Steam Overlay
   - Launch Options: `-window-mode exclusive -screen-fullscreen`
   - Press Alt+Enter twice after opening Valheim
- Add `gfx-enable-jobs=1` and `gfx-enable-native-gfx-jobs=1` in valheim_Data\boot.config
- HD Texture [Pack](https://drive.google.com/file/d/15pG3zUpH1Qz9PlsNe3Y6g8U1y0kwsknO/view?usp=sharing) for Clients NOT the Server: https://www.nexusmods.com/valheim/mods/302
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
- If you did everything right you should see `BepInEx`, `doorstop_libs`, `MonoBleedingEdge`, `unstripped_corlib`, `valheim_Data`, `doorstop_config.ini`, `steam_appid.txt`, `UnitiCrashHandler.exe`, `UnityPlayer.dll`, `valheim.exe`, `winhttp.dll` in the same folder



## How to upate:
Every release there will be a `PatchFromLastVersion.rar` that you can download and put into your Valheim folder for those with slower internet speeds.
If there's none, delete your `BepInEx` folder and replace it with the one from latest version.



## How to clean-uninstall:
- Navigate to your Steam Library
- Right click Valheim -> Manage -> Browse Local files and leave the folder open
- Go back to Steam
- Right click Valheim -> Manage -> Uninstall
- Now delete the remaining files in the prior opened Valheim folder
- Re-install Valheim through Steam Library



## To-Do List:
#### High Priority:
⚠️ Fix Desyncs
   - Current Plugin works but Terrain near Spawn-Stones resets itself sometimes

❌ Greatswords Stamina Numbers are higher than expected
   - They're missing a modifier somewhere

✔️ Integrate HugosArmory, JudesEquipment and JotunsBackpacks into BetterTrader
   - Traders sales should scale with your recipe unlocks

✔️ Add Backpacks and `0.205.5` Monsters to the Loot- and Startable
   - Because who doesn't want to fight a 5★ a̷̦͗̆̍̊́b̸̮̯̟͗̈͘ǫ̸̛̖̔̀̑m̶͉͔͒̚͝i̸̥̮̠̗̓.̸̫̦̱̘̹̔̈̀̀.̶̖̓̉.̶̮͕͚̃̿̓.̸̖͕̄

✔️ Serpent isn't scary enough
   - Either Boats get oneshot or they are indestructable...

#### Needs Time:
⚠️ Economy balancing
   - Find the right balance between Drops, Enchant/Augment costs and the Trader

✔️ Valheim Legends balancing
   - Damage seems minimal at first and overpowered once leveled
   - Especially Casters seem to need a lot of attention

✔️ Optimize Boss difficulty
   - They should be a challange at first and when you have to farm them

✔️ EpicLoot is too cheesy
   - Once you got your hands on an iron pickaxe for example you can mine 1 silver ore, smelt it and get thrown into the next Tier with all Silver Equipment drops
   - Will either use "MustHaveCrafted" or make mobs drop only Enchant Materials like [Epic Valheim](https://www.nexusmods.com/valheim/mods/1409?tab=description) does

#### Future Plans:
✔️ Add another Endgame difficulty spike
   - Equipment is there, just need to add more stars
   - Looking into [ForgottenBiomes](https://valheim.thunderstore.io/package/AlreeNicolas/Forgotten_Biomes/) and [DoOrDieMonster](https://valheim.thunderstore.io/package/Horem/DoOrDieMonsters/) right now


## Known Issues:
- Featherfall enchantment causes a heavy performance decrease upon dying
   - You can fix this by re-logging or augmenting and restarting your game
   - This is an error in EpicLoots code
- Terrain near spawn stones gets reset sometimes
   - You can fix this by sending the host (the first person that entered the area near the stones) away through a portal or a re-log
   - This is an error in Valheims code which gets enhanced by us trying to fix desyncs



## Mods Included, configured and balanced:
- [Atos Arrows](https://www.nexusmods.com/valheim/mods/1301) `v1.0.0`
- [BepInEx](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/) `v5.4.16.0`
- [Better Networking](https://www.nexusmods.com/valheim/mods/1570) `1.2.2`
- [Better Trader](https://www.nexusmods.com/valheim/mods/433) `2.1.1`
- [Blacksmith Tools](https://valheim.thunderstore.io/package/GoldenJude/Blacksmiths_tools/) `v2.0.1`
- [Bone Appetit](https://github.com/RockerKitten/BoneAppetit) `3.0.4`
- [ChickenBoo](https://github.com/sbtoonz/chickenboo) `2.0.5`
- [Clutter](https://github.com/plumga/Clutter) `v0.1.0`
- [Creature Level and Loot Control](https://valheim.thunderstore.io/package/Smoothbrain/CreatureLevelAndLootControl/) `v4.4.5`
- [Configuration Manager](https://github.com/aedenthorn/ValheimMods/tree/master/ConfigurationManager) `v0.5.0`
- [Discard Inventory Item](https://www.nexusmods.com/valheim/mods/45) `v0.7.0`
- [Diving Mod](https://www.nexusmods.com/valheim/mods/1271) `v1.2.2`
- [DoOrDieMonsters](https://valheim.thunderstore.io/package/Horem/DoOrDieMonsters/) `0.4.3`
- [Drop That](https://github.com/ASharpPen/Valheim.DropThat) `2.1.1`
- [Easy Translate](https://github.com/MLIMG/Easy-Translate) `v1.0.0`
- [Epic Loot](https://github.com/RandyKnapp/ValheimMods/tree/main/EpicLoot) `v0.8.7`
- [Epic Loot Adventures](https://valheim.thunderstore.io/package/OdinPlus/Digitalroots_EpicLoot_Adventure_Bounties/) `2.1.2`
- [EpicValheimAdditions](https://valheim.thunderstore.io/package/Huntardys/EpicValheimsAdditions/) `1.2.7`
- [Equipment and Quickslots](https://github.com/RandyKnapp/ValheimMods/tree/main/EquipmentAndQuickSlots) `v2.0.14`
- [Extended Item Data Framework](https://github.com/RandyKnapp/ValheimMods/tree/main/ExtendedItemDataFramework) `v1.0.5`
- [Forgotten Biomes](https://valheim.thunderstore.io/package/AlreeNicolas/Forgotten_Biomes/) `0.0.15`
- [HookGenPatcher](https://github.com/harbingerofme/Bepinex.Monomod.HookGenPatcher) `v1.2.0.0`
- [Hugos Armory](https://github.com/Hugo-the-Dwarf/ValheimMoreTwoHanders) `v5.0.1`
- [Jotunn](https://github.com/Valheim-Modding/Jotunn) `v2.4.1`
- [Jotunn Backpacks](https://www.nexusmods.com/valheim/mods/1416) `v2.0.0`
- [Judes Equipment](https://valheim.thunderstore.io/package/GoldenJude/Judes_Equipment/) `v1.4.0`
- [Mass Farming](https://github.com/Xeio/MassFarming) `1.3.0`
- [MonsterLabZ](https://valheim.thunderstore.io/package/MonsterLabZ/MonsterLabZ/) `1.7.0`
- [Plant Everything](https://valheim.thunderstore.io/package/Advize/PlantEverything/) `1.8.6`
- [Potions Plus](https://www.nexusmods.com/valheim/mods/1561) `v3.0.2`
- [RRR](https://valheim.thunderstore.io/package/neurodr0me/) `stable`
- [Sell That](https://www.nexusmods.com/valheim/mods/232) `v1.2.0`
- [Spawn That](https://github.com/ASharpPen/Valheim.SpawnThat) `0.11.6`
- [Speedy Paths](https://github.com/NNaso/ValheimMods/tree/main/SpeedyPaths) `v1.0.5`
- [Use Equipment in Water](https://www.nexusmods.com/valheim/mods/121) `v0.2.2.0`
- [Valheim Legends](https://www.nexusmods.com/valheim/mods/796) `v0.4.2`
- [Valheim Plus](https://valheim.plus/) `v0.9.9`



## Inspired by:
- [Epic Endgame](https://www.nexusmods.com/valheim/mods/1505)
- [Epic Valheim](https://www.nexusmods.com/valheim/mods/1409?tab=description)
- [Journey To Valhalla](https://valheim.thunderstore.io/package/thedefside/Journey_To_Valhalla/)
- [FixItFelix](https://valheim.thunderstore.io/package/FixItFelix/)



## Sponsor the creators, not us:
- [Aedenthorn](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=18901754)
   - Configuration Manager
   - Discard or Recycle Inventory Item
- [ASharpPen123](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=111115963)
   - DropThat
   - SellThat
- [CW_Jesse](https://www.patreon.com/CW_Jesse)
   - Better Networking
- [Digitalroot](https://www.buymeacoffee.com/digitalroot)
   - Atos Arrows JVL
   - Epic Loot Adventures
   - Potions Plus
- [DJAurelius](https://www.nexusmods.com/Core/Libs/Common/Widgets/DonatePopUp?user=887129)
   - HD Valheim
- [ElTheLedge](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=110405878)
   - Use Equipment in Water
- [EmrikNorth](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=121141283)
   - Jotunn Backpacks
- [HugotheDward](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=80461878)
   - Hugo's Armory
- [Menthus15](https://www.patreon.com/Menthus)
   - Better Trader
- [Mlimg](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=111855103)
   - Diving Mod
- [MonsterLabZ](paypal.me/davidfry1988)
   - MonsterLabZ
- [Plumga](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=8865735)
   - Clutter
- [RandyKnapp](https://www.nexusmods.com/Core/Libs/Common/Widgets/PayPalPopUp?user=9322077)
   - Epic Loot
   - Equipment and Quick Slots
   - Extended Item Data Framework
- [ValheimPlus](https://www.patreon.com/valheimPlus)
   - ValheimPlus

Our goal is to make it as easy as possible for others to enjoy the modded version of Valheim but we also don't want to hurt the creators since they are the ones that drive this project.

So if you want us add your donation link or even remove your .dll please contact us and we'll make some sort of skript that will download and intall the respective mods from their original source. Integrating everything and balancing takes priority right now which is why a skript to download everything from their original source comes later on the to-do list.
