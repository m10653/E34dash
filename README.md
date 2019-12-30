# E34dash
Simple and dirty tool to edit blue/brown "coding plug" firmware of BMW E32/E34 dashboards

## Allows to edit
* VIN
* Odometer
* Engine type
* Fuel tank type
* Various gauge parameters
* and more!

Building for Ubuntu.
Install qmake

clone this git
inside clusterinfo.h  //#include <stdint.h> un comment this line if you building in Ubuntu with qmake
mkdir build
cd build
qmake ../dashmaster.pro
make

Run program

./dashmaster

NOT for LOW clusters.

All feedback and support was closed because of idiots.

For those, who think that lowering mileage would increase car's value - BURN IN HELL!

Mileage set up wrong by idiots. This tool is designed to set the mileage back to the original. And for repairing broken dashboards!!!! 
