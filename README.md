# Lenovo Thinkpad L14 Gen3(amd) Opencore Hackintosh

## Notes
1. Work in progress. Boots, but mostly broken

## Hardware
| Item | Brand | Model | Driver | Comment |
|-----|-----|-----|-----|-----|
| Motherboard | Lenovo | L14 Gen3 | - | - |
| CPU | AMD | r7-5875U | | |
| RAM | - | 2x32GB DDR4 3200 | - | - |
| APU | AMD | Vega | NootedRed | - |
| SSD1 | Lenovo | 512 Gb | - | Main SSD Mac OS |
| SSD2 | - | - | - | will buy later |
| Wireless | Intel | - | - | Default module replacement |
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

## What's broken?
- touchpad
- brightness buttons
- sleep
- ...other to check

## Acknowledgement
Apple for macOS

acidanthera for OpenCore etc.

headkaze for Hackintool
