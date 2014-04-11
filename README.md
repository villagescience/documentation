# VS-Pi: Installation and Development

For any issues or updates to this page, please visit [our discussion forums](http://discuss.villagescience.org/latest) or [contact us](http://villagescience.wpengine.com/contact/).

## Required Hardware
For full details, please visit the [Technology page](http://villagescience.wpengine.com/technology/).

* Raspberry Pi Model B
* 32GB SD card
* USB WiFi adapter
* Keyboard/mouse/display
* Ethernet cable

## Installation Steps
Once you have the required hardware, follow the instructions below to set up a fresh installation on the Raspberry Pi. *Please note that this installation does not include any of the educational content that is intended for use as part of the [iQuEST pilot project](http://villagescience.wpengine.com/iquest-pilot-project/).*

1. Install Raspberry Pi’s New Out Of Box Software (NOOBS) to SD card following [these instructions](http://www.raspberrypi.org/downloads).  
2. Boot Raspberry Pi with the ethernet cable connected.
3. Run this command to install and configure VS-Pi (which will reboot Raspberry Pi):
	* `git clone https://github.com/villagescience/vspi.git && sudo bash ./vspi/setup.sh`
	* You can see what the Setup script is doing at the bottom of this script.
4. Try connecting a laptop (client) to the open ‘VS-Pi Connect’ Wi-Fi hotspot (server):
5. After connecting, try navigating to [http://vspi.local/](http://vspi.local/).
6. You can also connect to Raspberry Pi through SSH:
	* `ssh -l pi 10.0.10.1` (the VSPi installation codes a static IP address for the WiFi adapter).
	* username=pi
	* password=raspberry

## Development Steps
All of our development is done under our [Git Repository](https://github.com/villagescience). You’ll need an account with [GitHub](http://github.com/) in order to contribute. You will *not* need an account if you only want to install and play around with VS-Pi!

1. Create a GitHub account and [set up Git](https://help.github.com/articles/set-up-git)! This is where all the magic happens.
2. Follow the ‘Fork a Repo’ instructions for the Village Science ‘vspi‘ and ‘wordpress‘ repositories.
	* The VSPi repository is used for initial installation and pushing updates.
	* The WordPress repository is used to house the latest free educational content.

## How To Get Involved
Village Science is always looking for ways to improve!

1. Discuss VS-Pi with our online community.
	* General VS-Pi discussion can be found on our [discussion forums](http://discuss.villagescience.org/latest). Please note, you will need to register to *post* on the Village Science message boards. You do not need an account to simply *view* the forums.
2. Find issues that you can help fix.
	Individual bugs or desired improvements are tracked in each ‘Issues’ section of the Git repository (e.g. [VSPI issues](https://github.com/villagescience/vspi/issues) and [WordPress issues](https://github.com/villagescience/wordpress/issues)).
	
Our [Get Involved](http://villagescience.wpengine.com/get-involved/) page shows the developer skills Village Science currently needs.

And as always, please feel free to [contact us](http://villagescience.wpengine.com/contact/)!
