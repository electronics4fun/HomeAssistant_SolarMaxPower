# HomeAssistant_SolarMaxPower
An Automation for HomeAssistant to maximize the power output of a Hoymiles inverter with solar panels setup in East/West direction.
The hoymiles inverter that is used here is limited to 800W output while the inverter itself can handle up to 1.5kW.
With this setting every input (four) is limited to 200W by the inverter.
That means, that in the morning and in the evening the inverter is not delivering the maximum power that is possible.
The script tries to fix that by regulating the output power always to 800W.
