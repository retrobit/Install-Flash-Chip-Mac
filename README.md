# UNDER CONTRUCTION - I will be cleaning this up and correcting the spelling/grammar mistakes that were inherited

# Install-Flash-Chip-Mac

# Unsupported on Mac OS 1.13+ 
![Sucessful Flashed](https://scontent-frt3-1.xx.fbcdn.net/v/t1.0-0/p320x320/56119926_418247262055853_7781281606957793280_n.jpg?_nc_cat=109&_nc_ht=scontent-frt3-1.xx&oh=1382283de4082b42c9e2094abc502944&oe=5D3DFDF0)


## Ready to use environment to Flash your C.H.I.P Single Board Computer on MacOS 
 Simplyfies the Flashing Process for the C.H.I.P and PocketC.H.I.P Computer.
 
 
 ## Special Thanks to Nerten 
 
 https://github.com/Nerten 
 
 I dont know if i would finished this Work without him. 

## Instructions
1. Remove the C.H.I.P from its case (in case you have a Pocket C.H.I.P).
2. Connect the FEL and a GROUND pin of the C.H.I.P (for example, with a paperclip).
3. Connect the C.H.I.P its micro USB port to a USB port of your Linux machine.
4. On the Mac:
    - run ` git clone https://github.com/Thore-Krug/Install-Flash-Chip-Mac` to clone this repository. ( Or use Github Desktop ) 
    - `cd` into the location where you stored this repository.
    - run `sudo chmod +x Flasher.sh`
    - `./Flasher.sh help` will give out the help 
    - `./Flasher.sh install-all` install all the things you need to Flash your C.H.I.P 
    - `./Flasher.sh flash` Will Flash your C.H.I.P
    - Select the version you want to install.
    - Wait until the installation finishes.
    - Enjoy!

## Troubleshooting 

1. Kill the Script with ctrl + C 
2. Read the output if something is not installed or Permissions are missing 
3. Just restart the Script (fixes most of the Problem with FEL and Fastboot ) 
4. If this does not help reboot, retry
5. Open an Issue on this Git Repo. 

## Support my work by Donating 

https://www.paypal.me/a13tech
