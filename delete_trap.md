## Layout:

(R1)(C1)(C2)(C3)(C4)

## Commands:

**(R1, Delay: 2)**: execute @e[type=item, name="Trap Jammer"] ~ ~ ~ tag @e[type=armor_stand, name=sTrap, r=15] add deltrap

**(C1)**: execute @e[type=armor_stand, tag=deltrap] ~ ~ ~ particle minecraft:rising_border_dust_particle ~ ~1 ~

**(C2)**: execute @e[type=item, name="Trap Jammer"] ~ ~ ~ title @p actionbar §eFound And Jammed All Nearby Traps

**(C3)**: kill @e[type=armor_stand, tag=deltrap]

**(C4)**: kill @e[type=item, name="Trap Jammer"]
