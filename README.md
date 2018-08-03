# libEntitiesControl
A Datapack for Minecraft to Select Entities via Raycast


## How to Use:
### Select-Default

    /give @p minecraft:carrot_on_a_stick{Damage:3,Unbreakable:1b,display:{Name:"{\"text\":\"EntitiesControl\"}"}}
    
### Select-Manually

    /function lucsoft:entitiescontrol.select
    
#### Execute as Targets
    
    /execute as @e[scores={lsselectec=1}] at @s run
