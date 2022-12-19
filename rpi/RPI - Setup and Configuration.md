## Installation of OS 
Prerequisites:
- Raspberry pi
- micro SD card
- Memory card reader

1. Using [Raspberry Pi Imager](https://www.raspberrypi.com/software/) format the memory card to the correct OS you want on the imager
2. Wait untill the verification of the software is done and slot it into the Raspberry Pi 
3. Connect power to the raspberry pi
4. You should now be logged in and you can start configuring your raspberry pi

## Setting up SSH
### Headless: 

1. Ensure the RPI is turned off and remove the microSD card from the device
2. Put the microSD card in the card reader (of your computer) and wait untill the card mounts
3. Navigate to the **boot** folder
	- `cd /Volumes/boot`
	- Via Explorer

4. place a file called **ssh** (note that no extension is added to the file) in the boot folder

