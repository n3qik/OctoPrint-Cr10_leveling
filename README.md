# Bed Leveling

### Adds bed leveling buttons to the controls tab.

This plugin adds buttons to apply heat to the bed and nozzle, and move the printing head to each of the four corners of the bed, as well as the center of the bed.

The coordinates and temperatures can all be customized in the plugin’s settings.

## Warning

After turning on your printer, you must first home it before you can safely issuing gcode that causes movement.
This is true for this plugin, OctoPrint's default movement controls, and even the LCD control on the printer.

Failing to do so can cause the printer to move out-of-bounds.

## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)- Coming soon. 

Manually using this URL:

    https://github.com/n3qik/OctoPrint-Cr10_leveling/archive/master.zip

## Configuration

Options can be configured from OctoPrint's settings menu under "Plugins"
Available options are:
 - Bed Temp
 - Nozzle Temp
 - Simultaneously heat Bed and Nozzle
 - Feed Rate (Speed of movement)
 - Lower Z coordinate
 - Upper Z coordinate
 - Autolevel Commands
 - Front Left Position
 - Front Center Position
 - Front Right Position
 - Back Left Position
 - Back Center Position
 - Back Right Position
 - Center Position
 
 ## Version Changes
 
 5-3-2020: Added Front Center and Back Center for the newer larger bed printers, by n3qik.
 
