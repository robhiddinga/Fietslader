# Fietslader / Bicycle loader
domoticz script to detect loading state and turns unit off when finished.
To prevend fire in your shed from overheated units.

I have my bike loader on a NAS-WR01ZE.
This one has a switch so I can turn it on when parking my bike.
The script monitors te loading and turns the NAS-WR01ZE off when battery is full. 
Same can be accomplished with any switch that monitors Ampere usage.

The domoticz devices needed are Switch and GeneralCurrent (=Ampere)from the NAS-WR01ZE.
UsageElectric and GeneralVoltage are optional.

Create FietsLader_Amp as user variable type string value 0.

The three most important variables that you need to check and set in the script are:
amp_aan   - the Ampere used when unit is plugged in, but not attached to a bike
amp_laden - the maximum Ampere used while loading
amp_vol   - the Ampere used when battery is at 100% 

Do not forget to change the device numbers to your own values

Tested on two bikes and these values differ per bike/loading unit
Above values are for a Batavus unit (2nd generation)
