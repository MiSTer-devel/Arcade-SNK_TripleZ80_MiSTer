# SNK Triple Z80 Arcade Core (WIP)
Follow any core updates and news on my Twitter acount [@RndMnkIII](https://twitter.com/RndMnkIII). this project is a hobby but it requires investing in arcade game boards and specific tools, so any donation is welcome: [https://ko-fi.com/rndmnkiii](https://ko-fi.com/rndmnkiii).

## About
This core originated from the core project for __SNK's__ __Alpha__ __Mission__ arcade game. In the end, it has become a multigame project where new games will be added, encompassed in the so-called __"SNK Triple Z80"__ platform, this groups together several games that were developed by SNK around the mid-1980s using a similar hardware architecture. For a complete reference of the list of games consult
[https://github.com/mamedev/mame/blob/master/src/mame/drivers/snk.cpp](https://github.com/mamedev/mame/blob/master/src/mame/drivers/snk.cpp). 

I am currently making the core of other of these games, as I develop them I will incorporate modular features to use certain hardware parts depending on the game that is loaded in the core. The idea is to use a single core for all these games or try to modularize it as much as possible.

While it is in this development process, it will be appreciated that parallel developments of these games are not made to those of the author based on the code of this project, although I think it is good that it is ported to other platforms apart from MiSTer. Respecting that if I would like to receive suggestions or advice from other developers or users about this core.

## Third party cores
* Daniel Wallner T80 core [jesus@opencores.org](https://opencores.org/projects/t80).
* JTOPL FPGA Clone of Yamaha OPL hardware by Jose Tejada, @topapate [(https://github.com/jotego/jtopl)](https://github.com/jotego/jtopl).
* Based on Tim Rudy 7400 TTL library [https://github.com/TimRudy/ice-chips-verilog](https://github.com/TimRudy/ice-chips-verilog).
## Instructions ASO/Alpha Mission/Arian Mission:
In a game of two players who play in alternating turns. 
You use a 8-way joystick control with three buttons: Fire, Missile, Armor, Start1,Start2, Coin and Service mode. In MiSTer you have an additional button to pause the game (not implemented yet).
For enter in service mode you must hold pressed the service mode button while you reset the core. Not keyboard controls implemented yet.

## Manual installation
Rename the .rbf file to SNK_TripleZ80_20220509.rbf and copy to the SD Card to the folder  /media/fat/_Arcade/cores and the .MRA files to /media/fat/_Arcade.

The required ROM files follow the MAME naming conventions (check inside MRA for this). Is the user responsability to be installed in the following folder:
/_Arcade/mame/<mame rom>.zip

## Acknowledgments
* __@caiusarcade__ for their assistance in using files and converting PLD files.
* __@topapate__ for general advice with the JTOPL core.
* __@FCochise__ for helping with the rom settings of MRA files.
* __@alanswx__ for helping me with some technical aspects related to the use of the MiSTer framework.
* And all those who with their comments and shows of support have encouraged me to continue with this project.
