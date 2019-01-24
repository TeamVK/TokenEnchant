### Convention
* \<xxx\> : indicates the option/argument required for the command,
* [xxx] : indicates the option/argument optional for the command.

## Aliases
* tokenenchant
* te
* token

## Commands
* /te help or /te : displays a help menu
* /te add <name> <token_amount> : adds <token_amount> tokens to the player <name>
* /te remove <name> <token_amount> : remove <token_amount> from the player <name>
* /te set <name> <token_amount> : sets <token_amount> tokens to the player <name>
* /te reload : reloads the config.yml
* /te or /te balance [other] : displays your current token balance of you or [other]
* /te withdraw <token_amount> [drop] : withdraws the specified number of tokens from your account and gives you the token items in your inventory. If [drop] is specified, the excess token items will be dropped on the ground.
* /te expexchange [max_exp_to_be_exchanged] : exchanges the specified amount of EXP or all available EXP to tokens.
* /te givetokens [name] <amount> : gives <amount> token items to yourself (or a player [name])
* /te pay <player> <token_amount> : send <token_amount> to <player>
* /tealiasreload : reloads command aliases.
* /te enchant [player][enchant_name][[+]level] : enchants the item [player] is holding with [enchant_name]. If [level] is provided, the command will apply [enchant_name] with [level] to the item, which [player] is holding. If [+level] is specified, [level] will be "added" to the current enchantment level.
* /te refund [player][enchant_name] : refund [player] for the enchantment [enchant_name]
* /te repair [player] : repair the item in your (or [player]'s) hand.
* /te givebp <name> <row> [bpname] cost:xxx : gives <name> a backpacked named [bpname] of size <row> costing xxx.
* /te baltop : lists ranking of token balance.
