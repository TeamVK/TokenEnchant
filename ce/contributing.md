## Contributing
If you developed your own TokenEnchant Custom Enchantment, you can submit your pull request to add your custom enchantment's config file ```NmeOfYourCE_config.yml``` to ```TokenEnchant/ce``` folder.

Please make sure that your ```NameOfYourCE_config.yml``` contain the ```description:``` filed like:
```
Potions:
  EvokerFangs:
    description: "Attack like Evoker!! " ## <---- this line!!
    event_map:
      PlayerInteractEvent: "HIGHEST"
    price: 10
    max: 4
    ...
```

Optionally, you can also add some metadata in you ```NameOfYourCE_config.yml``` file indicating
* Author
* URL
* Link to Image/Demo video
* Sale price

```
#plugin.author:[ThePurpleHoser](https://www.spigotmc.org/members/thepurplehoser.108646/)
#plugin.url:https://www.spigotmc.org/resources/te-evokerfangsenchant.34044/
#plugin.demo:[![demo](https://img.youtube.com/vi/qk7YYzTpE2Q/0.jpg)](https://www.youtube.com/watch?v=qk7YYzTpE2Q)
#plugin.price:US$2.5
```
and the description of your custom enchantment like:


```EvokerFang_config.yml``` should look like:
```
#plugin.author:[ThePurpleHoser](https://www.spigotmc.org/members/thepurplehoser.108646/)
#plugin.url:https://www.spigotmc.org/resources/te-evokerfangsenchant.34044/
#plugin.demo:[![demo](https://img.youtube.com/vi/qk7YYzTpE2Q/0.jpg)](https://www.youtube.com/watch?v=qk7YYzTpE2Q)
#plugin.price:US$2.5
Potions:
  EvokerFangs:
    description: "Attack like Evoker!! Fangs will reach out to your opponent and bite them!" ## <---- this line!!
    event_map:
      PlayerInteractEvent: "HIGHEST"
    price: 10
    max: 4
    distance_multiplier: 2
    need_sneak: false
    need_sneak_message: "&a[TE] You need to sneak (Shift-key) to use this enchant!"
    cooldown: 0
    cooldown_message: "&a[TE] You have to wait for &b%remaining% &aseconds."
    occurrence: always
    allowed_items:
      - DIAMOND_SWORD
```

