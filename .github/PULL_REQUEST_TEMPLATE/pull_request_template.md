# Custom Enchantment registration request
This pull request is to register your custom enchantment with this site's Custom Enchantment list by adding your custom enchantment's config file (```NameOfEnchant_config.yml```) file to [```ce``` folder](https://github.com/TeamVK/TokenEnchant/tree/master/ce).

If you haven't read the information on what sort of pieces of information are needed for your ```_config.yml``` file, please read [Contributing](https://github.com/TeamVK/TokenEnchant/blob/master/ce/contributing.md). 

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
