## Basic Permissions
* tokenenchant.sign.create : allows you to create a TokenEnchant sign.
* tokenenchant.reload : allows you to use /te reload
* tokenenchant.add : allows you to use /te add command
* tokenenchant.remove : allows you to use /te remove command
* tokenenchant.balance : allows you to use /te balance command
* tokenenchant.balance.other : allows you to use /te balance <other> command
* tokenenchant.withdraw: allows you to use /te withdraw command
* tokenenchant.expexchange: allows you to use /te expexchange command
* tokenenchant.alias.reload : allows you to use /tealiasreload command.
* tokenenchant.enchant : allows you to use /te enchant command.
* tokenenchant.refund : allows you to use /te refund <enchant_name>
* tokenenchant.refund.other : allows you to use /te refund <player> < enchant_name>

You can specify "permission: xxxx.xxxx" node for each enchantment/potion in the config.yml. If you specify a permission node, only the player with the permission node can "apply" the enchantment/potion to an item. If "PermissionMode" is set to "USE" (default "ENCHANT"), this permission is used to determine whether a player can "use" the effect or not.
