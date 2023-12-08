# Lenovo Thinkpad L14 Gen3(amd) Opencore Hackintosh

## Notes
1. Work in progress. Boots, but some important things are broken

## Hardware
| Item | Brand | Model | Driver | Comment |
|-----|-----|-----|-----|-----|
| Motherboard | Lenovo | L14 Gen3 | - | - |
| CPU | AMD | r7-5875U | [SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor) | - |
| RAM | - | 2x32GB DDR4 3200 | - | - |
| APU | AMD | Vega | [NootedRed](https://github.com/ChefKissInc/NootedRed) | - |
| SSD1 | Lenovo | 512 Gb | - | Main SSD Mac OS |
| SSD2 | - | - | - | will buy later |
| Wifi | Intel | - | [AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | Default module replacement |
| Bluetooth | Intel | - | [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Default module replacement |
| Ethernet | RTL8111 | - | [RealtechRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X) | - |
| Audio | - | - | [AppleALC](https://github.com/acidanthera/AppleALC) | Layout in DeviceProps |
| Touchpad | - | ELAN via HID | [VoodooI@C](https://github.com/VoodooI2C/VoodooI2C) | latest buld from master with -vi2c-force-polling |


## BIOS Setup
| Name | Option | Comment |
| --- | --- | --- |
| UMA Frame buffer Size | 4G | needed 2G or above |
| Sleep State | Linux S3 | - |
| CPU Power Management | Enabled | - |

## What's working?
- wifi
- bluetooth
- trackpoint
- touchpad
- gpu acceleration
- buttons near touchpad
- brightness buttons
- type-c docking

## What's broken?
- sleep
- firefox

## To test
- virtualization
- rendering(Final cut)
- firefox with flags to disable gpu acceleration

## Acknowledgement
Apple for macOS

acidanthera for OpenCore etc.

headkaze for Hackintool
