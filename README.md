# WIDE Installer
## For Linux & Mac
#### By Craig Childs

Please not this is configured for Mac, if you're using Linux please see [here](#linux-configuration).

## How to use
 - Download the [.zip file from this repository](https://github.com/CraigChilds94/WIDE-Installer/archive/master.zip) and unzip it
 - Open the terminal, change directory to the folder by typing `cd ~/Downloads/WIDE-Installer-master`
 - Make this executable by typing `sudo chmod +x run`
 - Then run it by typing `./run`
 - Once the process has finished you should now be able start the IDE by typing `wide_run`

## Linux Configuration
The folder used to store the IDE on the mac is `~/Applications`, please modify the two scripts in this repository as you require. The variables you'll be needing to change are called `location`. Just change this to a suitable path.

## How it works
This scripts downloads and extracts the .zip file stored on the WIDE site. It then moves it to a location, common for applications. I add my own script to the `bin` folder which allows you to run it from anywhere on your system. Just by typing `wide_run` in the terminal.
