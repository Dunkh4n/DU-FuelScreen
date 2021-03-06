![display of multiple fuel tank configurations](https://rostw.com/i/urmwr.gif)
## Features

Supports any configuration of atmospheric, rocket, and space tanks up to 8 total tanks

Automatic detection, simply connect any amount of screens, and the tanks, and it will automatically adjust to the configuration

Easy configuration of all colors and text

## Installation

[Installation Tutorial / Feature Showcase](https://youtu.be/woB6tSPFkqw)

Click on FuelManagement1.4 above, on the top right click the Raw Button, and copy all text(Ctrl+C)

Right click on a programming board, Advanced, Paste Lua Configuration from clipboard

From there use the link tool(build mode tool 6 by default), to connect a minimum of one screen and one tank, before activating the programming board.

**Note: Due to the way dual universe handles the unloading of elements, when you get more than 250m from the programming board, the script will error and will not be able to work correctly until the programming board is deactivated and reactivated. However, this can easily be avoided by creating a link from a detection zone to the programming board. This will cause the board to be turned off whenever the player as out of range, and turned on whenever in range, solving the problem.**

## Planned Features

 - ~~Support for any combination of 8 tanks, for non-hybrid ships~~ | Added in 1.3
 - ~~Rocket Tank Support~~ | Added in 1.4
 - Support to display the percentage filled as a text value on top of the bar
 - Support to display the size of the tank on the bar
 - Further customization options
 - Support to split the list across more than one screen, rather than mirroring

## Customization

~~The script can be customized within the Advanced -> Edit Lua Paramaters menu, though due to the length of the strings, this can both look and feel clunky.~~ | Temporarily disabled

For an easier to read configuration, Go to Advanced -> Edit Lua Script, click unit under slots, and start() under filters. This will display a section of the code where the variables can more easily be read.

## Troubleshooting

 - Restart your game
 - Verify that the names of the tanks does not contain symbols, as this can conflict with the lua code
 - Verify that you are not attempting to link more than 8 of a single tank to the programming board
 

## Use on Payed Constructs

The script is free to use on payed and personal ships, however I would appreciate to be notified if it's being used on a sold construct/blueprint, as well as a link to this github provided to the buyer, so buyers can update their script at a later date.

## Support

Any issues or suggestions? You can contact me at either of these locations:

- Discord: Rost#6764
- Ingame: RostNerd

## Changelog

**v1.4** - 9/28/2020

- Features: Added Support for Rocket Tanks
- Features: Temporarily removed support for configuration via lua paramaters
- Backend: Added new arrays containing the list of rocketTanks and rocketTankNames
- Readme: Updated Gif to show rocket tank support

**v1.3** - 9/25/2020
- Features: Added Support for any configuration of 8 tanks, rather than a limit of 4 atmospheric, and 4 space tanks
- Backend: Reworked the way the tankName Array's are generated
- Backend: Added comments to some portions of the code

**v1.2** - 9/22/2020
- Initial Public Release
- Added autoconfiguration based on the class of the link, rather than requiring the connected slot to be named

**v1.1** - 9/20/2020

## Credits

Thanks to the great folks in the #lua-scripting channel in the Dual Universe discord, for assisting me in figuring out the more difficult sections of this script. Notably: Lithum3, D.Mentia, and NoPantsMcDance

