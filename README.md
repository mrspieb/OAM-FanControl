# OpenKNX FanControl

## Description

The OpenKNX FanControl is a KNX-compatible device designed for controlling fans in building automation systems. It integrates seamlessly with the KNX bus to provide reliable and efficient fan control functionality.

## Features

- Sensor driven automatic control or manual control
- Different ventilation modes (heat recovery, supply air and exhaust air)
- Optionally stops ventilation if the absolute humidity outside is higher than inside
- Built on the OpenKNX framework for extensibility.

## Hardware Specifications

The hardware is stored in a separate [repository](https://github.com/mrspieb/HW-FanController). It contains the base PCB, a front panel PCB and the case, which can be mounted on a DIN rail. It supports any combination of fan given in this [table](https://www.maico-ventilatoren.com/cms-live/media/AnleitungenHTML5/PP%20Installation/en-GB/index.html#167198475) (the software may need to be adapted slightly, I only tested 2x PPB30).

## Contributing

Contributions are welcome

## License

This project is licensed under GNU General Public License v3.0. See LICENSE file for details
