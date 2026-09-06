# Wood to Paldium Crusher

A PalSchema mod for Palworld 1.0.3 that adds Paldium Fragment recipes for all
current wood materials at both the Crusher and Cryogenic Crusher.

## Recipes

| Input | Output | Work |
| --- | --- | --- |
| 10 Wood | 1 Paldium Fragment | 1,000 |
| 5 Hardwood | 1 Paldium Fragment | 1,000 |
| 1 Mythical Wood | 1 Paldium Fragment | 1,000 |

## Requirements

- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS)
- [PalSchema](https://www.nexusmods.com/palworld/mods/2361) 0.6.4 or later

## Install

Extract the `WoodToPaldium` folder into:

`<Palworld>/Pal/Binaries/Win64/ue4ss/Mods/PalSchema/mods/`

Restart Palworld. The recipes appear in the Crusher menu when a suitable Pal is assigned.

## Compatibility

This mod adds three new rows to `DT_ItemRecipeDataTable`; it does not modify vanilla recipes or structures.
