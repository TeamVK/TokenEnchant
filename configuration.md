
```
# This is a template config file
# define your parameter and its value like:

###########################
# Help Messages used by the plugin
###########################
HelpMessages:
  banner:
    msg: "=== &e[&aTokenEnchant Commands List (%version%)&e] &r==="
  help:
    msg: "/te or /te help : display this help menu."
  reload:
    msg: "/te reload : reloads config file."
    permission: "tokenenchant.reload"
  set:
    msg: "/te set <name> <amount> : sets <name> <amount> tokens."
    permission: "tokenenchant.add"
  add:
    msg: "/te add <name> <amount> : adds <name> <amount> tokens."
    permission: "tokenenchant.add"
  pay:
    msg: "/te pay <name> <amount> : pay <name> <amount> tokens."
    permission: "tokenenchant.pay"
  remove:
    msg: "/te remove <name> <amount> : removes <name> <amount> tokens from <name>."
    permission: "tokenenchant.add"
  balance:
    msg: "/te balance [name] : displays the token balance of yourself or [name]."
    permission: "tokenenchant.balance"
  withdraw:
    msg: "/te withdraw <amount> [drop] : withdraws the specified amount of tokens from your account."
    permission: "tokenenchant.withdraw"
  expexchange:
    msg: "/te expexchange : exchanges the current EXP values to tokens."
    permission: "tokenenchant.expexchange"
  givetokens:
    msg: "/te givetokens <name> <amount> : gives <name> <amount> tokens."
    permission: "tokenenchant.expexchange"
  enchant:
    msg: "/te enchant [name] <enchant> [level] [cost:xxx] : enchants the item <name> is holding with <enchant>."
    permission: "tokenenchant.enchant"
  repair:
    msg: "/te repair [name] [free] : repairs all the enchantments of the item <name> is holding."
    permission: "tokenenchant.repair"
  refund:
    msg: "/te refund [name] <enchant> [level]: refund <name> for the enchantment <enchant>. If [level] is not specified, level = 1."
    permission: "tokenenchant.refund"
  givebp:
    msg: "/te givebp <name> <row> [bpname] cost:xxx : gives <name> a backpacked named [bpname] of size <row> costing xxx."
    permission: "tokenenchant.givebp"
  baltop:
    msg: "/te baltop : list top token balance."
    permission: "tokenenchant.baltop"
  giveall:
    msg: "/te giveall <amount> : give <amount> tokens to all online players."
    permission: "tokenenchant.giveall"
  list:
    msg: "/te list : lists currently registered enchantments."
    permission: "tokenenchant.list"
  tosql:
    msg: "/te tosql [add] : transfer userdata/*.yml to SQL database. If [add] was provided, the data from userdata/*.yml will be added."
    permission: "tokenenchant.tosql"
  news:
    msg: "/te news : display the news associated with the current release."
    permission: "tokenenchant.news"


###########################
# Messages used by the plugin
###########################
Messages:
  ErrorMessage: "&c [TE] : Some error occured."
  SelfBalance: "&a[TE] You currently have &b%token% &atokens."
  NoOthersBalance: "&c[TE] You are not allowed to check other's balance."
  NoTargetPlayer: "&a[TE] A player needs to be specified."
  PlayerOffline: "&a[TE] &e%player% &ais currently offline."
  PlayerNotFound: "&a[TE] &e%player% &awas not found."
  Balance: "&a[TE] &e%player% &acurrently has &b%token% &atokens."
  SetSuccess: "&a[TE] You have set &e%token% &atokens to &e%player%&a."
  AddSuccess: "&a[TE] You have added &e%token% &atokens to &e%player%&a."
  PaySuccess: "&a[TE] You have paid &e%token% &atokens to &e%player%&a." # or %receipient%
  Received: "&a[TE] You have received &e%token% &atokens from &e%sender%&a."
  Deducted: "&a[TE] &e%token% &atokens have been deducted."
  RemoveSuccess: "&a[TE] You have removed &e%token% &atokens from &e%player%&a."
  NotEnoughTokens: "&c[TE] You do not have enough tokens. You need at least %needed% tokens."
  NotEnoughTokenItems: "&c[TE] You do not have enough token items. You need at least %needed% token item(s)."
  NotEnoughExpLevels: "&c[TE] You do not have enough EXP levels. You need at least %exp_needed% EXP level(s)."
  WithdrawSuccess: "&a[TE] You have withdrawn &e%tokens% &atokens."
  InventoryFull: "&a[TE] Inventory is full! &e%tokens% &atokens could not be withdrawn!"
  ExchangeSuccess: "&a[TE] &e+ %token% &atoken(s) has been added to your account."
  NeedToHoldItem: "&c[TE] You need to hold an item to enchant."
  CannotEnchantThis: "&c[TE] You cannot enchant the item you're holding."
  CannotRepairThis: "&c[TE] You cannot repair the item you're holding."
  EnchantSuccess:
    msg: "&a[TE] &e+ %addedlevel% &d%enchant% &aenchantment level. %token% tokens have been deducted."
    sound: LEVEL_UP
  RepairSuccess: "&a[TE] &eThe item repaired. %token% tokens have been deducted."
  MaxedOut: "&c[TE] Your item has already maxed out on &e%enchant% &cenchantment."
  NoPermission: "&c[TE] You don't have a permission for this!"
  NoSuchEnchant: "&c[TE-Admin] That (&e%enchant%&c) is not a valid enchant. Please specify the enchant listed in the config file."
  TokenItemsGiven: "&a[TE] &e%tokenitems% &atoken items were given to &e%player%&a."
  NoPriceSet: "&a[TE] Price is not set for this."
  CommandSuccess: "&a[TE] &e%command%&a was executed, and it cost &e%token% tokens."
  NeedPermission: "&a[TE] You need a permission &etokenenchant.alias.command.%command% &ato use this command &e%command%&a."
  CannotDeEnchantThis: "&c[TE] We cannot de-enchant the item you're holding."
  CannotRefundThis: "&c[TE] We cannot refund the item you're holding."
  RefundSuccess: "&a[TE] &e - %refundlevel% &d%enchant% &aenchantment level. %token% tokens have been refunded."
  BackPackGiven: "&a[TE] %player% has given a backpack and %token% toknes has been deducted."
  VKBackPackNotFound: "&a[TE] VKBackPack plugin was not found."
  TokenBalTopHeader: "&a[TE] Token Balance Top - page:%page%/%total%-"
  TokenBalTopList: "%rank%. %name%, %balance%"
  TokenBalTopTypeMore: "&a[TE] Type &c/te baltop %next% &ato read the next page."
  OnlyOneAtTheTime: "&c[TE] Only one item can be enchanted at the time."
  CannotAddMoreEnchant: "&c[TE] You cannot add anymore than &e%max%&c custom enchantments!"
  CannotUseMoreEnchant:
    msg: "&c[TE] You cannot use an item with enchants more than &e%max%&c."
    sound: ITEM_BREAK
  CEListHeader: "&a[TE] Resistered Custom Enchantments - page:%page%/%total%-"
  CEListList: "%name% (%version%), max:%max%, %description%"
  CEListTypeMore: "&a[TE] Type &c/te list %next% &ato read the next page."
  CannotUseTokenItem: "&c[TE] You cannot use TokenItems for crafting!"



###############################
# Data Storage
###############################
DatabaseConfig:
#  MySQL:
#    host: localhost
#    port: 3306
#    user: root
#    password: yourpassword
#    database: TokenEnchant
#    tokentable: tokens

#
# if UseToken is true, the plugin use its own tokens, if it's false
# it uses economy thorugh Vault
UseToken: true

# if this option is true, the cost of enchant is dynamically calculated
# and displayed at where {ench_cost} is specified on the sign.
UseDynamicSignUpdate: true

Currency: token # token, money, or (exp...not supported atm)


# formating of number
BeautifyNumber: false
MaxCharLength: 4
# the folloiwngs are units of order.
OrderChars:
  - k
  - M
  - B
  - T
  - Q
  - P
  - E
  - Z


EnchantSign: "[&9Enchant&8]"
CostPlaceHolder: "{ench_cost}"
#
ExchangeSign: "[&9Exchange&8]"
ExchangeRate: 1
RatePlaceHolder: "{ex_rate}"
#
ExpExchangeSign: "[&9EXP Exch&8]"
ExpExchangeRate: 20
ExpRatePlaceHolder: "{exp_rate}"
#
WithdrawSign: "[&9Withdraw&8]"
#
RepairSign: "[&9Repair&8]"
RepairBase: 1
RepairDiscount: 0.05
RepairRatePlaceHolder: "{rep_rate}"
#
#
TokenItem: MAGMA_CREAM
TokenItemName: "&aTokenItem"
TokenItemLore: "&bHold it in your hand and\n&bRight-Click to redeem &eTokens"

#
# Enchantment lore prefix
EnchantmentLorePrefix: "&r&7"

#
#
# option to force remove potion effects at the login
ForceRemovePotionAtJoin : true
#

# option to use WorldGuard region
# Use WorldGuard's new block-break flag, otherwise, use canBuild check instead
UseWorldGuardNewFlag: true


# If UseRomanNumeral is true, arabic number will be converted into roman numeral.
UseRomanNumeral: true
# if PureRomanNumeral is true, 1 - 3998 will be converted to RomanNumeral
PureRomanNumeral: false

# if CustomEnchantDisplay is true, TE will use HideFlag option to hide the native enchantment name
# and use custom enchantment name using the lore.
# also it will convert enchantment.level.xxx into xxxx
# default : true
# this option is no longer used.
#CustomEnchantDisplay: true

#
UseEnchantGlowForPotion: true
#
MaxEnchantLevel: 100

#
UseEnchantmentTable: false
DefaultEnchantChance: 0.7
UseTokenEnchantSettingForVanillaEnchant: false


#
TokenFormula:
    # Valid values are: LINEAR and EXPONENTIAL
    # If an invalid value is entered, this will reset to the default setting, which is LINEAR
    # CONSTANT:      price
    # LINEAR:      price + (level * price)
    # EXPONENTIAL: price + price * level ^ exponent
    # EXPONENTIAL2: price * 2 ^ (level - 1)
    Curve: Linear

    Constant:
    Linear:
    Exponential:
        exponent: 1.80


# if this option is true, when you tried to enchant an item, which already has enchantment
# level, the excess enchantment level will be removed and set to the max level.
CapOverEnchant: false

# if this option is true, any enchantment level which is over the configured max level
# will be capped at the max level
RemoveExcessEnchantLevel: true

# Refund related
AllowRefund: false
RefundRate: 0.8

# default values
DefaultPotionDuration: 200
DefaultPotionAmplifier: 2

# option to limit the number of custom enchants on an item.
# The number of max enchants can be specified with permission nodes.
# tokenenchant.multiple_enchants.x
# if the permission node does not exist, the default number will be applied
# tokenenchant.multiple_enchants.x : x should not exceed MaximumMaxNumberOfEnchants
# if AllowOverMaxEnchantUse is true, you can use the item which exceeds custom enchants
# but you will not be able to add more custom enchants.
ApplyMaxNumberOfEnchants: false
MaximumMaxNumberOfEnchants: 10
DefaultMaxNumberOfEnchants: 3
ExcludeVanilla: true
AllowOverMaxEnchantUse: true


# Friendly fire option
# it currently supports Factions plugin and mcMMO's party
# if FriendlyFire is set to "true", you cannot harm your faction members or mcMMO party member.
FriendlyFire_Faction: true
FriendlyFire_McMMO: true

# Prevents self damaging initiating custom effect (default : true)
# if this option is set to true, when you damage yourself effects on your armors/toos won't be activated
# (cases like ender pearling, shooting yourself.... all damages are given but and effects won't be activated)
IgnoreSelfDamage: true


# if this option is true, TE will handle enchant merging via Anvil
AnvilMerge: true

#
# Merge mode: when two items of the same type is merged in anvil, NONE, ADD, MAX, VANILLA
MergeMode: ADD

#
# the mode of permission node for each effect, default=ENCHANT
# ENCHANT : the permission node is considered to determine whether a player can enchant or deenchant
# USE : the permission node is considered to determine whether a player can use the effect or not.
PermissionMode: ENCHANT

#
# Command execution with token
# This format is from a plugin called Aliazes.
# default permission for each command te.command.<cmd>
# If you crate an alias "cmd:" as shown beloe, you need to give a permission
# node "tokenenchant.alias.command.cmd" to a player
#
#cmd:                 <-- The command.
#  price: 20          <-- The amount of toke a player needs to execute this command.
#  permission: <-- Permissions section, if this section is not defined, individual permission system will be used, e.g. "te.command.cmd"
#  - te.command.user    <-- For users, this permission should be added as default.
#  - te.command.mod     <-- For mods, this permission should be added as default. 
#  - te.command.admin   <-- For admins, this permission should be added as default.     
#  alias:               <-- Additional aliases section. 
#  - cmd2              <-- Additional aliases 1, can be as many as you want.
#  default:                   <-- Default meaning anything below will be ran for the player in all worlds.   
#  - "!te_rawmessage %p &aHello" <-- To Print this message.                                                     
#  - "@who"                   <-- Will run /who command as player.                                           
#  - "!give %p 1 32"          <-- Will run command as console to give player 32 stone.                       
#  - ">give %p 1 32"          <-- Will run command as op to give player 32 stone.
#  - if %# = 0 !te_rawmessage %p &aUse '&e/g <name&a' to check user's group.
#  - if %# = 1 >pex user %1 group list
#  world_nether:              <-- The world you wish commands below to be shown in.                          
#  - "!te_rawmessage %p &aHello, you are in the nether." <-- This message will only be seen if player is in the nether.
Commands:
    # example of giving slot 9 chestbackpack to a user (ChestBackpack plugin)
    # backpack9:
    #   permission:
    #    - my.permission.for.backpack9
    #   price: 30
    #   default:
    #     - "!pex user %p add chestbackpack.slots.9"
    # # example of giving slot 18 chestbackpack to a user (ChestBackpack plugin)
    # backpack18:
    #   permission:
    #     - my.permission.for.backpack18
    #   price: 60
    #   default:
    #     - "!pex user %p add chestbackpack.slots.18"
    # # example of allowing a player to set his prefix using PermissionsEx command.
    # setprefix:
    #   permission:
    #     - my.permission.for.setprefix
    #   price: 160
    #   default:
    #     - "!pex user %p prefix %1"
    # letmefly:
    #   permission:
    #     - my.permission.for.letmefly
    #   price: 160
    #   default:
    #     - ">fly"

#
# default is LOW, you can have LOWEST, LOW, NORMAL, HIGH, HIGHEST or MONITOR
# adjust these event priority if those event processes from this plugin
# interfere with other plugins' event processes.
EventPriorityMap:
  PlayerInteractEvent: "NORMAL" # for clicking air/block
  SignChangeEvent: "NORMAL" # make/edit sign
  PlayerRespawnEvent: "MONITOR"
  PlayerJoinEvent: "NORMAL"
  PlayerQuitEvent: "NORMAL"
  PlayerDropItemEvent: "HIGHEST"
  PlayerItemBreakEvent: "HIGHEST"
  PlayerItemHeldEvent: "HIGHEST"
  InventoryClickEvent: "HIGHEST"
  InventoryCloseEvent: "MONITOR"
  PlayerChangedWorldEvent: "HIGHEST"
  EnchantItemEvent: "NORMAL"
  EntityDamageByEntityEvent: "LOWEST"
  PlayerCommandPreprocessEvent: "MONITOR"
  PlayerItemHeldEvent_CheckItem: "MONITOR"
  PlayerJoinEvent_CheckItem: "MONITOR"
  InventoryClickEvent_Anvil: "HIGHEST"
  PrepareAnvilEvent: "MONITOR"
  PlayerMoveEvent: "LOWEST"
  InventoryClickEvent_StopCrafting: "MONITOR"

#
# potion effects included in the default TE:
# Haste (Bukkit name: FAST_DIGGING)
# Speed (Bukkit name: SPEED)
# Nightvision (Bukkit name: NIGHT_VISION)
# Jump (Bukkit name: JUMP)
# Regeneration (Bukkit name: REGENERATION);
# FireResistance (Bukki name: FIRE_RESISTANCE)
# DamageResist (Bukkit name: DAMAGE_RESISTANCE
# Aqua (Bukkit name: WATER_BREATHING)
# Saturation (Bukkit name: SATURATION)
# HealthBoost (Bukkit name: HEALTH_BOOST)
# Strength (Bukkit name: INCREASE_DAMAGE)
# Blindness (Bukkit name: BLINDNESS)
# Confusion (Bukkit name: CONFUSION)
# Harm (aka Instant Damage, Bukkit name: HARM)
# Hunger (Bukkit name: HUNGER)
# Poison (Bukkit name: POISON)
# Slow (Bukkit name: SLOW)
# Weakness (Bukkit name: WEAKNESS)
# Wither (Bukkit name: WITHER)
# Molten (custom : attacker catches fire)
# Fly (custom effect : item holder can fly)
# Explosive : this is a custom effect, which will blow up surrounding blocks. It has an option of auto smelt. This Explosive effect works with MineResetLitePlus's mined block counting as well as Lucky Block feature!
# Excavation : this is a custom effect, It is just like Explosive but it will remove entire cuboid
# Sphered : this is a custom effect, It is just like Explosive but it will remove entire sphere
# BedrockBreaker (custom: allow you to break a bedrock block)
#
# You can set the duration to -1 to give infinite potion effects.
#
# You can set the occurrence
# random: randomly occur based on the level
# always: occur always.
# % : you can set the explicit % number as the maximum occurrence chance at the highest level of enchant.
#
# CustomEnchant (CE) effects listed here do not have corresponding external CE modules.
Potions:
    Haste:
      alias: "SpeedDigging"     #You can use your own name for enchant using alias.
      duration: 200
      amplifier: 2
      price: 10
      max: 10
      # You can set the occurrence
      # random: randomly occur based on the level
      # always: occur always.
      occurrence: random
      enchant_chance: 0.8
      refund_rate: -1
    Speed:
      price: 10
      max: 10
      # You can set the occurrence
      # random: randomly occur based on the level
      # always: occur always.
      occurrence: random
      allowed_items:
        - DIAMOND_BOOTS
        - GOLD_BOOTS
    Nightvision:
      price: 10
      max: 10
      # You can set the occurrence
      # random: randomly occur based on the level
      # always: occur always.
      occurrence: random
    Jump:
      price: 10
      max: 10
      # You can set the occurrence
      # random: randomly occur based on the level
      # always: occur always.
      occurrence: random
    Harm:
      price: 10
      max: 1
      #
      # level_multiplier * the level of potion will be used as
      # the level of Harm potion.
      level_multiplier: 1
      # You can set the occurrence
      # random: randomly occur based on the level
      # always: occur always.
      occurrence: always
    Regeneration:
      price: 10
      max: 2
      duration_multiplier: 1800
      #
      # You can set the occurrence
      # random: randomly occur based on the level
      # always: occur always.
      occurrence: always
    FireProtection:
      price: 10
      max: 1
      duration_multiplier: 1800
      occurrence: always
    Strength:
      price: 10
      max: 3
      duration_multiplier: -1
      occurrence: always
    Aqua:
      price: 10
      max: 1
      duration_multiplier: -1
      occurrence: always
    Saturation:
      price: 10
      max: 3
      duration_multiplier: -1
      occurrence: always
    HealthBoost:
      price: 10
      max: 3
      duration_multiplier: 1200
      occurrence: always


#
# Supported Enchantment:
# Power (ARROW_DAMAGE)
# Flame (ARROW_FIRE)
# Infinity (ARROW_INFINITE)
# Punch (ARROW_KNOCKBACK)
# Sharpness (DAMAGE_ALL)
# BaneOfArthropods (DAMAGE_ARTHROPODS)
# Smite (DAMAGE_UNDEAD)
# Depth / Depthstrider (DEPTH_STRIDER)
# Efficiency (DIG_SPEED)
# Unbreaking (DURABILITY)
# FireAspect (FIRE_ASPECT)
# Frost / FrostWalker (FROST_WALKER)
# Knockback (KNOCKBACK)
# Fortune (LOOT_BONUS_BLOCK)
# Looting (LOOT_BONUS_MOBS)
# Luck (LUCK)
# Lure (LURE)
# Mending / Repair (MENDING)
# Repiration (OXYGEN)
# Protection (PROTECTIOHN_ENVIRONMENTAL)
# BlastProtection (PROTECTION_EXPLOSIONS)
# FeatherFall (PROTECTION_FALL)
# FireProtection (PROTECTION_FIRE)
# ProjectileProt (PROTECTION_PROJECTILE)
# Silktouch (SILK_TOUCH)
# Thorns (THORNS)
# AquaAffinity (WATER_WORKER)
# Sweeping / SweepingEdge (SWEEPING_EDGE)
# Binding / BindingCurse (BINDING_CURSE)
# Vanishing / VanishingCurse (VANISHING_CURSE)
# Loyalty (LOYALTY)
# Impaling (IMPALING)
# Riptide (RIPTIDE)
# Channeling / Channelling (CHANNELING)
#
Enchants:
    Power:
      price: 10
      max: 10
    Flame:
      price: 10
      max: 10
    Infinity:
      price: 10
      max: 10
    Punch:
      price: 10
      max: 10
    Sharpness:
      price: 10
      max: 10
      merge_mode: VANILLA
      max_merge_level: 5 # this will limit the level achivable with merging enchants.
    Baneofarthropods:
      price: 10
      max: 10
    Smite:
      price: 10
      max: 10
    Depth:
      price: 10
      max: 10
    Efficiency:
      price: 10
      max: 10
    Unbreaking:
      price: 10
      max: 10
    Fireaspect:
      price: 10
      max: 10
    Knockback:
      price: 10
      max: 10
    Fortune:
      price: 10
      max: 10
    Looting:
      price: 10
      max: 10
    Luck:
      price: 10
      max: 10
    Mending:
      price: 10
      max: 10
    Respiration:
      price: 10
      max: 10
    Protection:
      price: 10
      max: 10
    Blastprotection:
      price: 10
      max: 10
    Featherfall:
      price: 10
      max: 10
    Fireprotection:
      price: 10
      max: 10
    Projectileprot:
      price: 10
      max: 10
    Silktouch:
      price: 10
      max: 10
    Aquaaffinity:
      price: 10
      max: 10
    Thorns:
      price: 10
      max: 10
    Sweeping:
      price: 10
      max: 10
    Binding:
      price: 10
      max: 10
    Vanishing:
      price: 10
      max: 10
    Loyalty:
      price: 10
      max: 10
    Impaling:
      price: 10
      max: 10
    Riptide:
      price: 10
      max: 10
    Channeling:
      price: 10
      max: 10
    Multishot:
      price: 10
      max: 10
    Piercing:
      price: 10
      max: 10
    QuickCharge:
      price: 10
      max: 10


# this config option is now deprecated.
# you can now specify conflicting enchants under each enchant's setting using 'conflict_with:' option.
Conflicts:
    1:
      - Explosive
      - Excavation
      - Sphered
      - Disk
      - Tile
    2:
      - Silktouch
      - Fortune


# list of items players are allowed to enchant
# if you're not sure which items, you would like to apply which enchant,
# just comment out the following option so that any enchant can be applied to any item.
#
# This config option is now deprecated.
# you can now specify which material type you can apply the custom enchant to using 'allowed_items:' option under
# each enchant's setting.
Items:
    GOLD_PICKAXE:
        - Unbreaking
        - Fortune
        - Efficiency
    IRON_PICKAXE:
        - Unbreaking
        - Fortune
        - Efficiency
    STONE_PICKAXE:
        - Unbreaking
        - Fortune
        - Efficiency
    WOOD_PICKAXE:
        - Unbreaking
        - Fortune
        - Efficiency
```
