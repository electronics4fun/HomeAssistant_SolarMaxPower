# HomeAssistant_SolarMaxPower

[![license](https://img.shields.io/github/license/:user/:repo.svg)](LICENSE)


## Abstract
An Automation for HomeAssistant to maximize the power output of a Hoymiles inverter with solar panels setup in East/West direction.
The hoymiles inverter that is used here is limited to 800W output while the inverter itself can handle up to 1.5kW.
With this setting every input (four) is limited to 200W by the inverter.
That means, that in the morning and in the evening the inverter is not delivering the maximum power that is possible.
The script tries to fix that by regulating the output power always to 800W.


## Requirements
- compatible inverter
- OpenDTU running


## Note

The entities are from an [OpenDTU](https://www.opendtu.solar/) (mqtt).
- sensor.gartenhaus_power is the output of the inverter (W)
- number.gartenhaus_limit_nonpersistent_absolute is the nonpersistant output rating of the inverter (W)


## Maintainers

[@electronics4fun](https://github.com/electronics4fun)


## Contributing

Feel free to dive in! [Open an issue](https://github.com/electronics4fun/PartDb-Altium-Connector/issues/new) or submit PRs.


## License

[MIT](LICENSE)
