# raid-dell
Setting up my first large RAID storage machine
## Description
I'm using a Dell Poweredge T320 Server to host my hard drives for photo backups.
## Goal 
The goal for this project is to have an actually safe storage for my photos and videos that aren't in the cloud. I'm aiming for the 3-2-1 storage solution motto ultimately.

### Notes 12/4/2022
> So the preivous card (H710P Mini) was not compatible with this server, but might be with some of the servers I own with John. I bought a H710P PCI-E ($67) so the price of this project has increased rip.
> The H710P PCI-E arrived and as I tried to install it I've run into problems. The BIOS doesn't recognize the controller or the LifeCycle controller never boots if the RAID card is plugged in. I'm thinking the issue is either driver problems (finding a working debian x86_64 driver is more difficult than it should be) or I need to change the boot setup options for RAID. If either of these don't work I'm thinking the firmware on the controller might be broken or something (there is a green flashing light) which means I have to flash new firmware. Flashing firmware onto the H710P might not be possible to do.

### Notes 11/20/2022
> For now here is my issue: The server for some reason doesn't have a raid card preinstalled. So do I buy a new raid card? or software raid? I think I'll just spend the $20 since I don't want to take any  chances. Unfortunatly this server doesn't have hot-swap bays so when I need it in the future I need a 2x2tb solution and will have to replace drives instead of just adding more in.
### Notes Previous
> I bought an Intel Xeon E5 2470 V2 LGA1356 CPU for $17! Coming Nov 23-26?
> Specs: 2.4Ghz (Boost 3.2Ghz), 25MB L3Cache, 10 Core, 20 threads, 22nm process, Ivy Bridge EN
