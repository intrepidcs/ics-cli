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

## Installation directions
The application is installed by simply unzipping the directory while maintaining its contents and adding the unzipped folder to your desired workspace, or adding the executable to your path.

# Linux
1. Download the `ics-cli` zip for Linux
2. Unzip the downloaded file
3. Add executable permissions to the application located in `ics-cli/bin/ics` by running `chmod +x ics-cli/bin/ics`
4. Move the `ics-cli` folder to your desired location and add the `ics-cli/bin` directory to your `PATH` if you'd like

# Windows
1. Download the `ics-cli` zip for Windows
2. Unzip the downloaded file
3. Move the `ics-cli` folder to your desired location, add the `ics-cli/bin` directory to your `PATH` if you'd like

## Requirements
# Linux
On linux this application requires root permissions to access device network interfaces or you can add the required ICS udev rules linked below.
# Windows
On windows this application requires a valid PCAP installation to access ICS devices using ethernet. 

## Intrepid Control Systems udev rules
You can find the udev rules for our devices [here](https://github.com/intrepidcs/libicsneo/blob/master/99-intrepidcs.rules).

