# CMDR Herbrand's SmartPipsManagement
A Thrustmaster T.A.R.G.E.T. Script to control Elite Dangerous Power Distributor more efficiently

Setup:
In order to use the script, you must first configure the variables in the file HerbrandPipsManagementVariables.tmh; I am using the first Hat of the Thrustmaster Warthog joystick, and the DX23 through DX26 keys for it, but feel free to rebind them at your leisure.

After that, ensure that both files are in the same folder of your TARGET Script profile and add the following line to the top:

    include "HerbrandPipsManagement.tmh"

Finally, add

    InitSmartPipsManagement();

at any point in your script. If everything compiles, after running you should receive the "SmartPipsManagement: Initialization complete" message at the bottom of the Script Editor.
The behavior of the script is described in the image PowerManagementDiagram.jpg.
