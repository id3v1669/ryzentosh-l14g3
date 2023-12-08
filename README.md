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
| Ethernet | - | - | - | - |
| Audio | - | - | [AppleALC](https://github.com/acidanthera/AppleALC) | Layout in DeviceProps |


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
- gpu acceleration
- buttons near touchpad
- brightness buttons
- type-c docking

## What's broken?
- elan touchpad(waiting for VoodooI2C 2.9)
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
