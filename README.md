# chvd-scripted-verision
This is repository for saving old CHVD View Distance Script (Arma 3) Scripted verision. I'm not own this script.

https://steamcommunity.com/sharedfiles/filedetails/?id=837729515

https://forums.bohemia.net/forums/topic/175757-ch-view-distance-addon/

1. Place "CHVD" folder in your mission folder.

2. Add this code to description.ext file in your mission folder:


#include "CHVD\dialog.hpp"
class CfgFunctions
{
#include "CHVD\CfgFunctions.hpp"
};
3. (Optional) If you want localization copy "stringtable.xml" to your mission folder.
4. (Optional) Add these commands to init.sqf file in your mission folder if you wish to limit some functionality:


CHVD_allowNoGrass = true; // Set 'false' if you want to disable "Low" option for terrain (default: true)
CHVD_maxView = 2500; // Set maximum view distance (default: 12000)
CHVD_maxObj = 2500; // Set maximimum object view distance (default: 12000)
