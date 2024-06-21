# The Intrepid Control Systems command line tool
Manage and use Intrepid Control Systems devices through the command line.
## Supported modules
- Device settings
- Firmware flashing
- Hardware info retrieval
- User settings

## Supported devices
- RAD-Gigastar
- neoVI-FIRE3
- neovi-RED2
- ValueCAN 4-4
- RAD-A2B

## Getting started
# Linux
To install unzip the release and add the executable located in `ics-cli/bin` to your path. Make sure to set the executable bit on the application located at `ics-cli/bin` by running `chmod +x ics-cli/bin/ics`. Ethernet and USB devices require root permission or additional udev rules for usage. Make sure not to change the directory structure of the release as it could prevent the application from retrieving specific resources. Call `ics --help` to see specific options and subcommands.

# Windows
To install unzip the release and add the executable located in `ics-cli/bin` to your path. The application requires PCAP to be installed on the host computer. Make sure not to change the directory structure of the release as it could prevent the application from retrieving specific resources. Call `ics --help` to see specific options and subcommands.

## Intrepid Control Systems udev rules
You can find the udev rules for our devices [here](https://github.com/intrepidcs/libicsneo/blob/master/99-intrepidcs.rules).

