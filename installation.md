## Installation Process
1. Shutdown your server.
2. Place TokenEnchant.jar in the plugins folder (plugins/). 
3. Restart the server, and this should create plugin's folder called TokenEnchant with the default config.yml and other folders (such as enchants/)
4. If you found the custom enchants you wish to install, place .jar file of the custom enchants (CEs) (which should look like TE-XXXEnchant.jar, where XXX is the general name of enchant) in plugins/TokenEnchant/enchants folder.
5. Add installed CEs configuration(s) to your config.yml file.
6. Restart the server.

## Dependency
There is no hard dependency to any other plugin.

* Vault: if this is installed, you can use its economy as currency,
* WorldGuard: if this is installed, you can use WG regions to block certain custom enchants in the specific region.

## Work with
* VKBackPack
* EZBlock
* DeluxeChat
* AutoSell (make sure to set "pickup: false" in Explosive)
* VKAutoPickup (all TokenEnchant features will work with this plugin)
* MineResetLite
* FeatherBoard
* Faction (MassiveCore's official 2.x version)
* mcMMO
* PrisonMines
