# Flawedspirit's BR Control

## Description

This program lets you monitor and actively control a Big Reactors reactor and turbines with an OpenComputers computer.

This program was tested on and designed to work with the mod versions and configurations installed on Flawedspirit's Mental Instability Pack, though as the pack uses default settings for both Big Reactors and OpenComputers, there should be no issues using a different modpack, or even a modpack that makes changes to how BR works.

* http://technicpack.net/modpack/mi-reloaded.604813
* https://flawedspirit.com/minecraft/#pack

## Computer Design

Please note that to keep the code (relatively) simple, the program makes a few assumptions; those being:

* A Tier 3 Computer
* A Tier 2 or better Graphics Card
* An Internet Card
* One Tier 2 screen OR one Tier 3 screen (for best results)
* One reactor
* Any number of (or zero) turbines

## Notes

* Only one reactor has been tested with this program (additional reactors added AT OWN RISK)
* Data for only 6 turbines will display onscreen
* Data for up to 28 turbines will display onscreen if using a Tier 3 screen
* Data for ALL turbines will still be tallied in the 'totals' row
* By default, the program updates once every 2 seconds, though the rate is adjustable

## Features

* Dynamic tracking of reactor information, like temperature, fuel/waste levels, coolant levels`*`, steam output`*`, or RF storage`*`
* Dynamic tracking of up to 6 turbines, including speed, steam input, RF generation, and RF storage
* In-program control of reactor power and control rod settings
* Real-time warning if certain parameters indicate abnormal or non-optimal operation of reactors/turbines
* NEW! Turbine auto mode! Set it to either 900 or 1800 RPM by pressing T and the program will toggle your turbines' induction coils or active state to keep it at the right speed`**`

`*` If applicable
`**` Note: the author takes no responsibility if you bankrupt your base's energy stores because your turbines are all disengaged. Please use responsibly.

## Usage

* Press the left and right arrow keys to toggle between page 1 (turbine/RF storage information) or 2 (control rod configuration)
* Press L or , to lower/raise control rods by 1%
* Press ; or . to lower/raise control rods by 5%
* Press ' or / to lower/raise control rods by 10%
* Press P to toggle reactor power
* Press Q to exit the program and return to your computer's terminal prompt
* Press T to toggle 'Auto Mode' on all turbines. This will engage the induction coil when your preferred rotational speed (900 or 1800 RPM) is reached

## Resources

* This script is available from:
  * http://pastebin.com/zWju7H0z
  * https://github.com/Flawedspirit/FlawedspiritOC/tree/master/OpenComputers-Reactor-Control
* Official OpenComputers Site: http://ocdoc.cil.li/
* Official Big Reactors Site: http://www.big-reactors.com/#/
* Big Reactors API: http://wiki.technicpack.net/Reactor_Computer_Port

## Changelog

* 0.1.4
  * First release to Github! :D
* 0.1.5
  * Addition of turbine auto mode
  * Changes to make the program take better advantage of larger screen sizes
  * Bug fixes

## TODO
* See https://github.com/Flawedspirit/FlawedspiritOC/issues for any outstanding issues.
* Fix screen flickering issue on Page 1 (may not be possible at the moment)