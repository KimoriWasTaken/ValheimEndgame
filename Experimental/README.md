# Experimental ValheimEndgame
This is the experimental branch where we test mod additions/integrations that require much more work.


## Use at your own risk:
Most of the time this branch isn't working properly but you can still see what we're working on.
This way you can even help us out if you're interested.


## To-Do List:
- Fix Desyncs
   - Waiting for Network mod updates
   - Issues seem to only affect Spawn Stone area, further testing in progress
- Optimize Valheim Legends balancing
   - Damage seems minimal at first and overpowered once leveled
   - Mage seems to require the most attention
- Add Backpacks and `0.205.5` Monsters to the Loot- and Spawntable
   - In progress
- Optimize Boss difficulty
   - They should be a challange at first and when you have to farm them
- Serpent isn't scary enough
   - Either boats get oneshot or they are indestructable...
   - Mob damage to boats is enabled right now and in testing
   - When boats hit structures they recieve damage which is problematic when you've built a port and there are a lot of waves
- Add another Endgame difficulty spike
   - Equipment is there, just need to add more stars
   - Looking into [ForgottenBiomes](https://valheim.thunderstore.io/package/AlreeNicolas/Forgotten_Biomes/) and [DoOrDieMonster](https://valheim.thunderstore.io/package/Horem/DoOrDieMonsters/) right now
- ~~Cleanup unedited cfg's so clients/servers generate their own to minimize errors~~


## Known Issues:
- In rare instances dying seems to decrease performance and spams an error that is being investigated
- EpicLoot pushes you into Tier3 (iron) loot seemingly at random
- Some users experience mutliplied stamina costs instead of reduced stamina costs when using abilities of ValheimLegends
   - Example: vl_svr_energyCostMultiplier = 0.7 -> Monks flying kick costs 350 stamina instead of 50
   - Fixed by setting it back to 1


## How to clean-uninstall:
- Navigate to your Steam Library
- Right click Valheim -> Manage -> Browse Local files and leave the folder open
- Go back to Steam
- Right click Valheim -> Manage -> Uninstall
- Now delete the remaining files in the prior opened Valheim folder
- Re-install Valheim through Steam Library