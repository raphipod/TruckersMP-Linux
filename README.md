# TruckersMP-Linux

Two automation shell scripts for ETS2 & ATS that work with truckersmp-cli

The release version number is always bound to the one used in [truckersmp-cli](https://github.com/lhark/truckersmp-cli).

## How to use?

1. Download ETS2/ATS in Linux native Steam client with Proton (not the native Linux version of ETS2/ATS2!!)
2. Run the game once to create necessary files for the next steps.
3. Download [truckersmp-cli](https://github.com/lhark/truckersmp-cli).
4. Open the game directory of ETS2/ATS, and create a new folder called "mp"
5. Unpack truckersmp-cli, and put the contained files into the newly created "mp"-folder (-> */Euro Truck Simulator 2/mp/files*, not /Euro Truck Simulator 2/mp/truckersmp-cli/files)
6. Clone **this** repository or download the script according to your game, and put the file accordingly to your game into the "mp"-folder 
7. Edit ETS2MP or ATSMP accordingly to your game location, and don't forget to change your steam username. Make it executable.
8. Start the script, and enjoy your game!

### Why won't the script start?
It seems that these scripts use DOS file endings, which Unix-based OS'ses can't recognize. Download 'dos2unix' for your distribution, issue 'dos2unix ETS2MP' or 'dos2unix ATSMP' in the terminal to get rid of the bad file endings. Now, the script should execute properly!
