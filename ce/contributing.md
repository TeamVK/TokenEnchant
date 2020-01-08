## Contributing
If you developed your own TokenEnchant Custom Enchantment, you can submit your pull request to add your custom enchantment's config file ```NmeOfYourCE_config.yml``` to ```TokenEnchant/ce``` folder.
Please make sure that your ```NameOfYourCE_config.yml``` contain following lines:

```
#plugin.author:[vk2gpz](https://www.spigotmc.org/members/vk2gpz.617/)
#plugin.url:https://www.spigotmc.org/resources/te-antiknockbackenchant.12751/
#plugin.price:free
```
and the description of your custom enchantment like:
```
Potions:
  AntiKnockback:
    description: "Prevents being knocked back."  ## <---- this line!!
    price: 10
    max: 4
    occurrence: random

```

