# libEntitysControl
A Datapack for Minecraft to Control a Entitys


## How to Use:
### Select-Default

    /give @p minecraft:carrot_on_a_stick{Damage:3,Unbreakable:1b,display:{Name:"{\"text\":\"EntitysControl\"}"}}
    
### Select-Manuel

    /function lucsoft:entityscontrol.select
    
#### Execute as Targets
    
    /execute as @e[scores={lsselectec=1}] at @s run
