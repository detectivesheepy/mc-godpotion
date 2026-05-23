# Minecraft God Potion
God potion for vannila Minecraft
## Get the item
In a command block, paste this code (or the code inside `command.mcfunction`) and run the command block. Make sure it is not repeating. <br>
````give @a potion[potion_contents={custom_color:16711680,custom_effects:[{id:regeneration,duration:99999,amplifier:225,show_particles:0b},{id:health_boost,duration:99999,amplifier:225,show_particles:0b},{id:luck,duration:99999,amplifier:225,show_particles:0b},{id:hero_of_the_village,duration:99999,amplifier:225,show_particles:0b}]},custom_name=[{"text":"𓎼𓅱𓂧","italic":false}],lore=[[{"text":"This potion can only be summoned by gods. Just make sure not to die, or the world will turn against you.","italic":false}]],item_name=[{"text":"𓎼𓅱𓂧","italic":false}],rarity=epic,equippable={slot:mainhand},death_protection={death_effects:[{type:apply_effects,probability:1,effects:[{id:bad_omen,duration:100,amplifier:255,ShowParticles:0b}]}]}]````
