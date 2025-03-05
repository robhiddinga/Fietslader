# Fietslader
domoticz script to detect loading state and  turn off

I have my bike loader on a NAS-WR01ZE
This one has a switch so I can turn it on when parking my bike
The script monitors te loading and turns the NAS-WR01ZE off when battery is full 

The domoticz devices needed are Switch and GeneralCurrent from the NAS-WR01ZE
UsageElectric and GeneralVoltage are optional

Create FietsLader_Amp as user variable type string value 0
