# ExhaustFanSpeedControlforMacfanctld
Very badly written script to set the Exhaust Fan Speed via the macfanctld config file
First things first: You need to have MacfanCtlD installed.
Second things after: My little script only reads and writes into the config file of MFCd and gives *some* outpu
while not trying to blow up the fan.
###Step 1###
Install MacFanCtlD
./rpm_script [argument] ( low / mid / high)
###THATS IT###
The script will write the new rpm into the config file and restart the process to read the new rpm.
thats why i consider this script to be written badly: shooting with a bazooka to kill a bird.

If you feel like a million dollars you also can use 'set' and change the rpm to a specific number
but i limited max. rpm to 6500, just in case the fan cannot take such an amount of rpms.

enjoy.
