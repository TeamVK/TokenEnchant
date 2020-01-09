# Custom Enchantment registration request
This pull request is to register your custom enchantment with this site's Custom Enchantment list.  You only need to submit your custom enchantment's ```_config.yml``` file.

## Name of Your Custom Enchantment.
name_of_your_custom_enchantment

## Description
Please include a description of your Custom Enchantment.

## Author
[name_of_author](http://url.to.author's.page) 
NOTE: It is recommended to use spigotmc.org's profile page.

## Link to obtain your Custom Enchantment.
[Link](http://url.to.your.custom.enchantment.site)

## Checklist:
- [ ] Is your submitting config file named like ```NameOfEnchant_config.yml```? (eg. ```Excavation_config.yml```)
- [ ] Does your ```NameOfEnchant_config.yml``` file contain the following header info lines?
```
#plugin.author:[YourName](https://www.spigotmc.org/members/yourname.xxxxx/)
#plugin.url:https://www.spigotmc.org/resources/yourresoruce.xxxx/
#plugin.price:name_your_price
```
- [ ] Does your ```NameOfEnchant_config.yml``` file contains ```description:``` option? (like below?)
```
Potions:
  AntiKnockback:
    description: "Prevents being knocked back."  ## <---- this line!!
    price: 10
    max: 4
    occurrence: random
```
