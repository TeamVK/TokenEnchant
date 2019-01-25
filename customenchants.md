There are two types of Custom Enchantments (CEs):
* Enchantments : these CEs are created based on Minecraft's Enchantment.
* Potions : these CEs are created more like Minecraft's Potion effects.

In practice, the codings for these two types of CEs are slightly different but the usages are pretty much the same.

### Enchantments:
These effects must be listed under "Enchants:" section.
* Aqua affinity (aka Aquatic) (Bukkit name: WATER_WORKER)
* Baneofarthropods (Bukkit name: DAMAGE_ARTHROPODS)
* Blastprotection (Bukkit name: PROTECTION_EXPLOSIONS)
* Curseofbinding (Bukkit name: BINDING_CURSE)
* Curseofvanishing (Bukkit name: VANISHING_CURSE)
* Depth (Bukkit name: DEPTH_STRIDER) *only available from 1.8.3
* Efficiency (Bukkit name: DIG_SPEED)
* Featherfall (Bukkit name: PROTECTION_FALL)
* Fireaspect (Bukkit name: FIRE_ASPECT)
* Fireprotection (Bukkit name: PROTECTION_FIRE)
* Flame (Bukkit name: ARROW_FIRE)
* Fortune (Bukkit name: LOOT_BONUS_BLOCKS)
* FrostWalker (Bukkit name: FROST_WALKER) *only available from 1.9
* Infinity (Bukkit name: ARROW_INFINITE)
* Knockback (Bukkit name: KNOCKBACK)
* Looting (Bukkit name: LOOT_BONUS_MOBS)
* Luck (Bukkit name: LUCK)
* Lure (Bukkit name: LURE)
* Mending (Bukkit name: MENDING) *only available from 1.9
* Power (Bukkit name: ARROW_DAMAGE)
* Projectileprot (Bukkit name: PROTECTION_PROJECTILE)
* Protection (Bukkit name: PROTECTION_ENVIRONMENTAL)
* Punch (Bukkit name: ARROW_KNOCKBACK)
* Respiration (Bukkit name: OXYGEN)
* Sharpness (Bukkit name: DAMAGE_ALL)
* Silktouch (Bukkit name: SILK_TOUCH)
* Smite (Bukkit name: DAMAGE_UNDEAD)
* Sweepingedge (Bukkit name: SWEEPING_EDGE)
* Thorns (Bukkit name: THORNS)
* Unbreaking (Bukkit name: DURABILITY)

### Potions:
These effects must be listed under "Potions:" section. (Note: anything under this section would require separate .jar file, which contain those custom effects.  Effects in yellow are privately released ones.)
* Haste (Bukkit name: FAST_DIGGING)
* Speed (aka Gears) (Bukkit name: SPEED) :
* Nightvision (aka Glowing) (Bukkit name: NIGHT_VISION) :
* Jump (aka Springs , Anti Gravity) (Bukkit name: JUMP) :
* Regeneration  (Bukkit name: REGENERATION);
* FireResistance (aka Obsidian Shield with duration: -1) (Bukki name: FIRE_RESISTANCE) :
* DamageResist (Bukkit name: DAMAGE_RESISTANCE
* Aqua (Bukkit name: WATER_BREATHING)
* Saturation (Bukkit name: SATURATION)
* HealthBoost (Bukkit name: HEALTH_BOOST)
* ====
* MiningFatigue (Bukkit name: SLOW_DIGGING)
* Strength (Bukkit name: INCREASE_DAMAGE)
* Blindness (Bukkit name: BLINDNESS)
* Confusion (Bukkit name: Confusion)
* Harm (aka Instant Damage, Bukkit name: HARM)
* Hunger (Bukkit name: HUNGER)
* Poison (aka Poisoned) (Bukkit name: POISON)
* Slow (Bukkit name: SLOW)
* Weakness (aka Voodoo) (Bukkit name: WEAKNESS)
* Wither (Bukkit name: WITHER)
* ====
* Molten (custom :  attacker catches fire)
* Fly (custom effect : item holder can fly)
* [Explosive](explosive.md) : this is a custom effect, which will blow up surrounding blocks. It has an option of auto smelt. This Explosive effect works with MineResetLitePlus's mined block counting as well as Lucky Block feature!
* Excavation : this is a custom effect, It is just like Explosive but it will remove entire cuboid
* Sphered : this is a custom effect, It is just like Explosive but it will remove entire sphere
* BedrockBreaker (custom: allow you to break a bedrock block)
* Disk : this is a custom effect, which will blow up surrounding blocks in circular form with 1 block deep.
* Tile: this is a custom effect, which will blow up surrounding blocks in square form with 1 block deep.
* GrapplingBow : this is a custom effect, which allow a player to shoot an arrow for grappling.
* Universal : this is a custom effect, which allow your tool to automatically morph into an appropriate tool depending on what you're doing.
* ====
* Hook : this is a custom effect, which allow a player to use fishing rod to grapple or fish living entities.
* MobDrops : this is a custom effect.  With this effect, when you kill a mob, the mob will drop some extra goodies!
* MineBuddy : this custom effect allow you to have a mining buddy. All you mined will automatically sent to your mining buddy's inventory.
* Throw : if you enchant your item with this effect, you can throw it to give a damage! Be like Ninja!
* AttackDeflector : This custom effect will allow you to deflect attacks including arrow!
* SoulBound : If you enchant your item with this effect, the item will stay in your inventory when you die.  Also other people cannot pick it up.
* Teleport : You can mark the destination of teleportation, and flick of your enchanted tool, you can teleport back to the defined location or to the top of the mine.
* Expelliarmus : Disarm your opponent!
* LuckyMining : If you enchant your tool with this effect, you might get lucky and get some prizes!
* SquirtleWaterGun : Shoot water gun like Squirtle!
* =====
* PikachuThunder : Electric damage like Pikachu!
* GroundPound : Are you ungry? Pound the ground!
* Freedom : Fireworks for Freedom!
* Flame : lit the fire after you mined.
* Inquisitive : get more EXP orbs upon mob killing.
* AutoSell : automatically sell all items in your inventory and VKBackPack.
* Guardian : upon taking damage, it will spawn your guardian mob (like PigZombie, IronGolem) to fight for your and protect you!
* Lumberjack : just break one block of a tree and connected tree blocks and leave blocks get cut down too!
* TNT : you can cause TNT-like explosion with Bow/Arrow or simply breaking a block. (you can mine those exploded block if you have auto pick up plugin!)
* Lightning (aka Thundering Blow): You strike Lightning and cause TNT-like explosion! You can also use it for mining as well.
* ====
* Drill : You can drill vertically or horizontally.  The size of drilling hole can be controlled by the level of enchantment.
* RetainEXP : Retain your exp upon your death. You simply carry an item which was enchanted with RetainEXP enchant in your inventory or armours/tools.
* ItemFishing : fish/steal an item your opponent/mob is currently holding!!
* AntiKnockback : Prevents being knocked back.
* Vampire : Suck your opponent's health when you attack him/her
* FakeLag : cause your opponent to lag like crazy!
* Repel : repels your opponents and hostile mobs.
* Piercing : pierce through opponent's armour!
* Ramming : charge towards your opponent when you attack to increase the damage!
* Blast (aka Shockwave) : blast off nearby players and hostile mobs!
* ====
* ShotGun : shoot multiple arrows in one go!
* AutoBlocking : automatically turn dust/ore into blocks when your inventory/backpack is full.
* Invisibility : make you invisible. (vanilla invisibility effect)
* Ninja : disappear like a Ninja!!
* QuickTrap : quickly trap your opponent with cob webs!
* HealingBow : heal your friend by shooting with this enchant bow.
* Camouflage : allows you to blend into the environment as long as you sneak and don't move!
* Frozen : apply slowness to the attacker.
* MolotovCocktail : enchant a Bow with this and get the petrol bomb  effect.
* SkillSwipe : take your opponent's exp when you attack!
* ====
* Rage : ComboAttack (consecutive attack without being damaged) will increase your attack damage!
* MoreHearts (aka Overload) : higher level of enchant will give you more hearts (you can go over 10 hearts!)
* HeadBlow : 1 hit kill with direct hit to the head!
* Toxic : give poison effect to your attacker!
* Trickstar : quickly teleport to the behind your opponent!
* Hardened : decrease durability loss on your armour!
* Death bringer (aka Double Strike) (by [USER=108646]@ThePurpleHoser[/USER]) : double your attack damage!
* Enlightened (by [USER=108646]@ThePurpleHoser[/USER]) : Opposite to Deathbringer Enchant! You can reverse the damage into gaining health!
* Implants (by [USER=108646]@ThePurpleHoser[/USER]) : Recover health and hunger overtime you take a step with this enchant!
* PlungerClimber (by [USER=108646]@ThePurpleHoser[/USER]) : You can climb up the wall with plunger climber enchanted tool!
* ====
* SecureLoot (by [USER=108646]@ThePurpleHoser[/USER]) : You can secure loot (from breaking chests/containers and killing mobs/players) with this enchant so that other cannot pick up your loot!
* Curse (by [USER=108646]@ThePurpleHoser[/USER]) : Curse your attacker with this enchant! It will give them mining fatigue!
* Decapitate (aka Headless) : Decapitate players and mobs' heads!
* KillReward : receive rewards by killing!
* NoPushing : prevent from being pushed around!
* AutoSmelt : automatically smelt mined ore.
* AutoCook : automatically cook caught fish and killed animals.
* PickPocket : steal money/item from other player! it also includes "anti" pickpocket enchant!
* Tame : instantly tame a tameable animal!
* MobSpawnerEgg : Mine a mob spawner and get it as a MobSpawnerEgg!!
* ====
* Voodoo : Use ArmorStand +Voodoo head to give another player damage!
* FrostWalker (by [USER=108646]@ThePurpleHoser[/USER]) : Creates frost blocks when walking over water
* Slicing (aka JackHammer, by [USER=108646]@ThePurpleHoser[/USER]) : Explode entire layer(s)!!
* SkullDigger (aka LuckyBlock digger, by [USER=108646]@ThePurpleHoser[/USER]) : Dig out skull/player head blocks instantly!!
* McMMOExp : Multiply McMMO Experience gain! Higher level = more gain!
* Elytra : Elytra like feature for 1.7, 1.8 server! (you can use it on 1.9 server too!)
* LuckyExcavation (aka Concentrate excavation, by [USER=108646]@ThePurpleHoser[/USER]) : You can get random rewards from Spade-Excavation! Higher level = more drops!!
* Boomerang : Throw your weapon to attack and your weapon will return to you when its job is done!
* Blunt : Give extra durability damage to your attacker's weapon!
* SlipperyHand : Make your opponent's hands slippery and make him lose his item from his hand!
* ====
* PumpkinHead (by [USER=108646]@ThePurpleHoser[/USER]) : Being un-noticed by Endermen with this enchantment!
* MagmaWalker (by [USER=108646]@ThePurpleHoser[/USER]) : Creates obsidian blocks when walking over lava
* StomperBoots : Break/mine a block by stomping on it!
* EvokerFangs (by [USER=108646]@ThePurpleHoser[/USER]) : Attack like Evoker!! Fangs will reach out to your opponent and bite them!
* OreSeeker (aka Vein Mining) : Let this enchant to seek other similar ores around you!
* Laser (by [USER=108646]@ThePurpleHoser[/USER]) : Swing of tool will cast laser of an item (such as Pumpkin), which will cause explosion!
* Slaughter (by [USER=108646]@ThePurpleHoser[/USER]) : Kill multiple mobs in the merged/stacked mobs!! Higher enchant, more kills!
* Unbreakable : Simply making an item unbreakable
* Melee : Sneak up from behind and kill! in HALO style!
* CrossExplosion (by [USER=108646]@ThePurpleHoser[/USER]) : Explode blocks in a cross pattern.
* ===============
* Barbarian (by [USER=108646]@ThePurpleHoser[/USER]) : You can throw an item to give damage to your oponent.
* BodyBreaker (by [USER=108646]@ThePurpleHoser[/USER]) : Give durability damage twice the rate.
* BoneBreaker (by [USER=108646]@ThePurpleHoser[/USER]) : Knocks back the enemy!
* BoostingBoots (by [USER=108646]@ThePurpleHoser[/USER]) : when running this enchant has a chance to get speed effect.
* BrothersGuard (by [USER=108646]@ThePurpleHoser[/USER]) : allows you to get absorption hearts when you wear full armor set with this enchantment.
* BurnBabyBurn (by [USER=108646]@ThePurpleHoser[/USER]) : When an arrow hit an enemy, it will remove enemy's FireResistance.
* Burner (by [USER=108646]@ThePurpleHoser[/USER]) : Smelts the ores as you mine them.
* ChainDrag (by [USER=108646]@ThePurpleHoser[/USER]) : Pulls your enemy close to you.
* Chainmail (by [USER=108646]@ThePurpleHoser[/USER]) : A chance of taking less damage when you get attacked
* Chiseled (by [USER=108646]@ThePurpleHoser[/USER]) : gives you mroe loot upon mining.
* ===============
* ChocolateVision (by [USER=108646]@ThePurpleHoser[/USER]) : See the names of anyone using invis pots
* CloudWaking (by [USER=108646]@ThePurpleHoser[/USER]) : Neglects all fall damage.
* Collector (by [USER=108646]@ThePurpleHoser[/USER]) : Gives you a better looting effect
* Concentrate (by [USER=108646]@ThePurpleHoser[/USER]) : Gives you a high chance of recovering diamonds from excavation. 
* DarkenedDiamond (by [USER=108646]@ThePurpleHoser[/USER]) : Gives a chance of wither 1 effect to an enemy.
* DawnOfDarkness (by [USER=108646]@ThePurpleHoser[/USER]) : Gives a chance to mildly blind someone
* DeathGrinder (by [USER=108646]@ThePurpleHoser[/USER]) : Gives you double the EXP for swords MCMMO than usual
* Decay (by [USER=108646]@ThePurpleHoser[/USER]) : Sickens your enemy with the wither effect as well a poison
* Desecrate (by [USER=108646]@ThePurpleHoser[/USER]) : Destroying your enemies armor very fast but weapon breaks once your enemies armor does
* Desolation (by [USER=108646]@ThePurpleHoser[/USER]) : Protect you but also destroys the attacker's weapon!
* ===============
* DevilsKiss (by [USER=108646]@ThePurpleHoser[/USER]) : Gives a chance of taking away your hearts
* Dexterity (by [USER=108646]@ThePurpleHoser[/USER]) : Once in combat with the weapon you get small speed boost.
* DialsDia (by [USER=108646]@ThePurpleHoser[/USER]) : This enchant allows you to right click your pickaxe and it faces you in the direction of the closest diamonds.
* DiamondTip (by [USER=108646]@ThePurpleHoser[/USER]) : Does more durability damage to armor than regular shots
* DiggingBoots (by [USER=108646]@ThePurpleHoser[/USER]) : When jumping, you mine the block down one when you land on top of it.
* Disarmed (by [USER=108646]@ThePurpleHoser[/USER]) : Gives a chance when shooting an enemy to drop whatever they're holding at the time.
* ElderBow (by [USER=108646]@ThePurpleHoser[/USER]) : Use your wisdom to fire multiple arrows at your struggling target!.
* ElderPowers (by [USER=108646]@ThePurpleHoser[/USER]) : The use of your knowledge has given you the ability to craft these powerful pant to increase your armors durability when being hit by an axe.
* EnderScape (by [USER=108646]@ThePurpleHoser[/USER]) : Gives a small chance of teleporting to escape when about to die .
* Enragement (by [USER=108646]@ThePurpleHoser[/USER]) : if you drop below 3 hearts you have a chance of gaining str 4 for 5 seconds activated on use.
* ===============
* ExplosiveDeath (by [USER=108646]@ThePurpleHoser[/USER]) : Gives the sound and effect of TNT and deals the damage and knockback of TNT as well
* ExplosiveTip (by [USER=108646]@ThePurpleHoser[/USER]) :
* FearInFire (by [USER=108646]@ThePurpleHoser[/USER]) : These boots when in use release a fierce fire effect scarring off enemies while giving you regen!.
* FedTooLittle (by [USER=108646]@ThePurpleHoser[/USER]) : This decrease the hunger of the enemy at an alarming rate.
* FlakJacket (by [USER=108646]@ThePurpleHoser[/USER]) : Neglects all TNT damage and knockback effects when hit with TNT or exploded near you.
* FrozenBlade (by [USER=108646]@ThePurpleHoser[/USER]) :
* Gluttony (by [USER=108646]@ThePurpleHoser[/USER]) : Gives you full hunger bars so there is no need to eat.
* GodlyGuard (by [USER=108646]@ThePurpleHoser[/USER]) : Gives you a chance to only take half the damage normally when using block hitting.
* GrapplingRod (by [USER=108646]@ThePurpleHoser[/USER]) : this enchant when cast out drags you to where the bobber on the fishing rod lands.
* GravityDefiance (by [USER=108646]@ThePurpleHoser[/USER]) : Once you're in combat, it has a chance to throw your enemy into the air making them take fall damage.
* =====
* Grinder (by [USER=108646]@ThePurpleHoser[/USER]) : Gives a chance to double the efficiency of the pickaxe.
* HandyHearts (by [USER=108646]@ThePurpleHoser[/USER]) : This enchant will give you a chance to get an absorption heart when you hit by an enemy.
* HeadButt (by [USER=108646]@ThePurpleHoser[/USER]) : This enchant can stun your opponent.
* HelpingBlade (by [USER=108646]@ThePurpleHoser[/USER]) : When you attack your enemy with this enchant, it can heal non-enemy player.
* KittyCannon (by [USER=108646]@ThePurpleHoser[/USER]) : Swinging your weapon to send a cat out of of your tool! When the cat hits a player, s/he will get damage.
* KnowledgeOfElder (by [USER=108646]@ThePurpleHoser[/USER]) : Gives you extra hearts (depending on the level)
* Laceration (by [USER=108646]@ThePurpleHoser[/USER]) : Cuts deep into your enemies armor giving a chance of dealing more damage.
* LegDay (by [USER=108646]@ThePurpleHoser[/USER]) : Gives you more speed.
* LuckyDrop (by [USER=108646]@ThePurpleHoser[/USER]) : Increases the number of drops according the level.
* Mace (by [USER=108646]@ThePurpleHoser[/USER]) : When using this against an enemy player, it can do up to 1 heart of damage no matter what the gear is.
* ===
* Martyrdom
* MobSwatter
* MoneyBlade
* Mooncrest
* MysticalBlade
* Neglect
* NightWalker
* Over9000
* PiercingSpeed
* PoisonAura
* ===
* PutridDeath
* QuakeTip
* Reconstruct
* RedSkyAtNight
* RegenAura
* Rejuvenate
* Ricochet
* SandSmelter
* Savage
* SecondChance
* ===
* SharpenedIce
* Sharpen
* ShotsFired
* SirenShot
* SpeedTheory
* Springs
* StarvingEdge
* StrengthAura
* Summoner
* Suncrest
* ===
* SwiftAura
* Tank
* TightLine
* Titanium (by [USER=108646]@ThePurpleHoser[/USER]) :
* Trample
* TribpleDrop
* TripleHook
* TrueStrength (by [USER=108646]@ThePurpleHoser[/USER]) :
* Voltage
* WhisperOfWind (by [USER=108646]@ThePurpleHoser[/USER]) :
* ===
* WinOrLose
* ArmoredTank :
* Sentimental (by [USER=108646]@ThePurpleHoser[/USER]) : like SoulBound but not bounded to a player, whoever holds the item with enchant can claim its sentimental value.
* HalloweeenBats (by [USER=108646]@ThePurpleHoser[/USER]): If you have an item/armor with this enchantment, it will spawn bats around you when you attack or get attacked.  Spawned bats will automatically be despawned.
* HalloweenMagmaTrail (by [USER=108646]@ThePurpleHoser[/USER]): This enchant will leave a trail of magma blocks on the floor.  The trail will automatically be put back to the original blocks.  A player will not get damaged from the magma blocks as long as the trail belongs to the player.
* HalloweenFlameEffect (by [USER=108646]@ThePurpleHoser[/USER]): If you have an item/armor with this enchantment, it will repeatedly spawn the mobspawner flames around you.
* HalloweenWitherBow (by [USER=108646]@ThePurpleHoser[/USER]): If you shoot with a bow with this enchantment, it will shoot a witherskull instead of an arrow, and the witherskull will give damage only to a living entity and leave surrounding blocks without any damages.
* MultipleCatch (by [USER=108646]@ThePurpleHoser[/USER]) : When you fish, the number of caught fish multiplies based on your enchantment level.
* AutoSellMultiplier (by [USER=477275]@TheGuildsPlugin[/USER]) : Custom Enchant for increasing AutoSell Multiplier!
* Antidote (by [USER=108646]@ThePurpleHoser[/USER]) : This enchant will protect you from bad splash/lingering potions!
* ====
* LightningTip (by [USER=477275]@TheGuildsPlugin[/USER]) : This plugin contains a custom enchantment effect that allows you to cause an lightning upon attack using a projectile (arrow) with this enchant.
