# The Intrepid Control Systems command line tool
Manage and use Intrepid Control Systems devices through the command line.
## Supported modules
- Device settings
- Firmware flashing
- Hardware info retrieval
- User settings
- Web based firmware binary retrieval

## Supported devices
- RAD-Gigastar
- neoVI-FIRE3
- neovi-RED2
- ValueCAN 4-4
- RAD-A2B

## Installation directions
The application is installed by simply unzipping the directory while maintaining its contents and adding the unzipped folder to your desired workspace, or adding the executable to your path.

# Linux
1. Download the `ics-cli.zip` file for Linux
2. Unzip the downloaded file
3. Add executable permissions to the application located in `ics-cli/bin` by running `chmod +x ics-cli/bin/ics`
4. Move the `ics-cli` folder to your desired location. Optionally add the `ics-cli/bin` absolute path to your `PATH` var.

# Windows
1. Download the `ics-cli.zip` file for Windows
2. Unzip the downloaded file
3. Move the `ics-cli` folder to your desired location.  Optionally add the `ics-cli/bin` absolute path to your `PATH` var.

# Additional notes
The resources for the application such as the device setting configuration files and the user settings file are found by the application by assuming there location from the location of the
executable file. Therefore, do not change the structure of the directory when it is unzipped, for example do not move the device setting configuration files outside of the unzipped folder. The
structure of the application folder must be maintained to ensure that resources can be found by the application.

## Requirements
# Linux
On linux this application requires root permissions to access device network interfaces or you can add the ICS udev rules linked below.
# Windows
On windows this application requires a valid PCAP installation to access ICS devices using ethernet. 

## Intrepid Control Systems udev rules
You can find the udev rules for our devices [here](https://github.com/intrepidcs/libicsneo/blob/master/99-intrepidcs.rules).

