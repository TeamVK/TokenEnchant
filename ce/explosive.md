This plugin contains a custom enchantment effect that allows you to use 5 different types of explosive effects:

* Explosive
* Excavation
* Sphered
* Disk
* Tile

This was originally included in TokenEnchant plugin.  However, it has been removed from TE itself so that this effect can be used in the different version of TE.

Demo Video:
coming...

### Installation:
Just install TE-ExplosiveEnchant.jar in TokenEnchant/enchants folder. Then you can either "restart the server" or "reload the plugin (not /te reload)". ExplosiveEnchantment will automatically be loaded into TokenEnchant framework.

### Configuration:
You need to add new entry for "Explosive, Excavation, Sphered, Disk, and Tile" enchant under the "Potions:" section in your config.yml.

#### NOTE:
* Make sure to configure your WorldGuard (block-break : allow) or if your server uses any region management plugins, make sure they allow users to break blocks in the region where you wish to use this effect.


```
# if this option is true, TEBlockExplodeEvent will be handled by TokenEnchant
# if you want other plugin to handle TEBlockExplodeEvent, set it to false;
PickupTEExplodedBlocks: true
SmeltTEExplodedBlocks: true

Potions:
    Explosive:
      event_map:
        BlockBreakEvent: "HIGHEST"
        TEBlockExplodeEvent: "MONITOR"
      price: 10
      max: 10  # the level of Explosive will be used as the radius of explosion.
      radius: 3  # radius
      # you can set the multiplier to calculate the total amount of blocks to be exploded
      # level 150 and multipler 2 = 150 x 2 blocks within the radius 3 will be exploded
      multiplier: 2
      # you can nominate the world, which prevents explosive
      invalid_in_world:
        - plotworld
      # you can turn on automatic pickup.
      pickup: true
      # you can turn on automatic smelting
      smelt: true
      # you can turn on/off explostion sound/visual effects
      effect: true
      # you can turn on/off explostion sound effects
      sound: true
      # You can set the occurrence of explosion.
      # random: randomly occur based on the level
      # always: explosion occur always.
      occurrence: random
      use_explode_event: true # use efficient explode event.
      block_break_event_priority: MONITOR
    Excavation:
      event_map:
        BlockBreakEvent: "HIGHEST"
        TEBlockExplodeEvent: "MONITOR"
      radius: 2
      use_explode_event: true
      alias: "&4&lOP Excavation"
      price: 3
      max: 7
      # you can nominate the world, which prevents explosive
      invalid_in_world:
        - plotworld
      # you can turn on automatic pickup.
      pickup: false
      # you can turn on automatic smelting
      smelt: false
      # you can turn on/off explostion sound/visual effects
      effect: true
      # you can turn on/off explostion sound effects
      sound: true
      # You can set the occurrence of explosion.
      # random: randomly occur based on the level
      # always: explosion occur always.
      occurrence: always
      exemptions:
        - ENDER_CHEST
        - GLOWSTONE
        - LADDER
        - "STAINED_GLASS:11"
      invalid_in_region:
        - noexcavation
    Tile:
      event_map:
        BlockBreakEvent: "HIGHEST"
        TEBlockExplodeEvent: "MONITOR"
      use_explode_event: true
      permission: tokenenchant.tile
      price: 10
      max: 3
      invalid_in_world:
        - plotworld
      pickup: false
      smelt: false
      effect: true
      sound: true
      multiplier: 0.5
      occurrence: always
      exemptions:
        - ENDER_CHEST
        - GLOWSTONE
        - LADDER
    Disk:
      event_map:
        BlockBreakEvent: "HIGHEST"
        TEBlockExplodeEvent: "MONITOR"
      use_explode_event: true
      price: 10
      max: 3
      radius : -1 # if radius is set to -1, enchantment level will be used as a radius. if you do not have radius: option it is set to -1
      invalid_in_world:
        - plotworld
      pickup: false
      smelt: false
      effect: true
      sound: true
      multiplier: 0.5
      occurrence: always
      exemptions:
        - ENDER_CHEST
        - GLOWSTONE
        - LADDER
    Sphered:
      event_map:
        BlockBreakEvent: "HIGHEST"
        TEBlockExplodeEvent: "MONITOR"
      use_explode_event: true
      alias: Circle
      price: 10
      max: 3
      # you can nominate the world, which prevents explosive
      invalid_in_world:
    - plotworld
      # you can turn on automatic pickup.
      pickup: false
      # you can turn on automatic smelting
      smelt: false
      # you can turn on/off explostion sound/visual effects
      effect: true
      # you can turn on/off explostion sound effects
      sound: true
      # You can set the occurrence of explosion.
      # random: randomly occur based on the level
      # always: explosion occur always.
      occurrence: always
      exemptions:
        - ENDER_CHEST
        - GLOWSTONE
        - LADDER
```
