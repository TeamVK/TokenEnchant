All Custom Enchantment (CE) in TokenEnchant can have the following config options.  If they are not listed in CE's config, the default value will be used.

- enabled: (default = true)
    If this option is set to 'false', TE won't register this CE.

- cooldown: (default = 0)
    The cooldown value in second.

- cooldown_message: (default = "")
    The message displayed to warn the cooldown.

- conflict_with:
    The list of enchantments which conflict with this enchantment.

- allowed_items: (default = "*")
    The list of item types, which can have this enchantment.

- event_map: (no default)
    If the enchantment is activated based on events, you can specify the event listener's level

- permission: (default = null)
    If this is specified, this permission node is used to either enchantment or use of this enchantment.

- permission_mode: (default = "ENCHANT")
    This flag indicates how the permission node is used (either for enchanting or for using the enchantment).

- enchant_chance: (default = "DefaultEnchantChance: 1.0" from TE's config.yml)
    The chance of a successful enchantment process.

- description: (default = the name of the enchantment)
    The brief description of this enchantment.

- occurrence: (default = "random")
    The chance of this enchantment being executed at the "max" enchantment level.  "always", "random" or a number between 0.0 and 1.0 are premitted.

- occurrence_min: (default = 0.0)
    This value is used in computing the chance of execution in the occurrence formula.

- max: (default = 100)
    The maximum enchantment level. The default is the value specified in "MaxEnchantLevel:" option in TE's config.yml.

- merge_mode: 

- max_merge_level: (default = 'max')
    The maximum enchantment level you can achieve through the merging process with the anvil.

- price: (default = Double.MAX_VALUE)
    The base price/cost of the enchantment. (from the level 0 to level 1).

- invalid_in_world: The list of worlds where you cannot use the enchantment

- enabled_world: The list of worlds where you can use the enchantment

- invalid_in_region: The list of WorldGuard regions where you cannot use the enchantment

- enabled_region: The list of WorldGuard regions where you can use the enchantment

- alias: The alternative name. It supports color codes

- old_aliases: if you change the alias, you should list the previous aliases here so that old lore entries can be fixed.

- item_target: (default = "ALL")
    The target of the enchantment (inherited from Bukkit's Enchantment class)

- duration: (default = "DefaultEnchantDuration:" from TE's config.yml)
    If the enchantment effect uses a potion effect, this defines the duration of the potion effect.

- duration_multiplier: (default = 1)
    The multiplier factor to adjust the duration of the potion effect.

- refund_rate: (default = "RefundRate: 1" from TE's config.yml)
    The rate being applied to the refunding.  If this value is -1, the refund is not permitted.

- cost_formula: (defualt = "DefaultFormula: linear_diff" from TE's config.yml)
    The name of the javascript function from Costformulae.js

- cooldown_formula: (default = "DefaultCooldownFormula: constant" from TE's config.yml)
    The name of the javascript function from CooldownFormulae.js

- occurrence_formula: (default = "DefaultOccurrenceFormula: linear" from TE's config.yml)
    The name of the javascript function from OccurrenceFormulae.js

- availabilities:
    availabilities of this enchant (NONE, TREASURE, ENCHANTMENT_TABLE, LOOT, VILLAGER, FISHING, ENTITY_DEATH)
  
- is_treasure: (default = false) (deprecated: replaced by "availabilities" option)
    If this flag is "true", the enchantment is treated as a treasure enchantment.
    
- is_enchanttabled: (default = !is_treasure) (deprecated: replaced by "availabilities" option)
    If this flag is "true", the enchantment can be selected by the Enchantment Table.
    
- is_loot: (default = !is_treasure) (deprecated: replaced by "availabilities" option)

- rarity: (default = "COMMON")
    The flag indicating the rarity of the enchantment.  Inherited from Bukkit API.
    
- enchantment_slot_type: (default = "ALL")

- enum_item_slots: (default = a list of "MAINHAND", "OFFHAND", "HEAD", "CHEST", "LEGS", "FEET")

- use_action_bar: (default = false)
    The flag indicating the use of the action bar for messaging.
    
- apply_offhand_potion: (default = false)
    The flag indicating whether the potion-based enchantment effect is applied or not when the item is in the off-hand.
    
- hidden: (default = false)
    If this flag is 'true' the name of enchant will not be displayed on the item's lore.

- toggle: (default = true)
    If this flag is 'true' you can disable/enable this enchatnment using EnchantToggle addon (https://te.polymart.org/resource/597)

- levels.commands:
    a list of commands to be executed for specified levels.  commands are executed when the enchantment effect is activated

- full_armor: (default = false)
    if this option is "true", you need to have this enchant on all armor items you're wearing.
    
