# ktg5's H370 HD3, i7-8700 Hackintosh EFI.
The EFI I use for my H370 HD3 i7-8700 Hackintosh.
*hopefully i didn't fuck over my computer*

[You can easily download the latest version of this EFI folder by looking in the releases section.](https://github.com/ktg5/H370-HD3-i7-8700-Hackintosh/releases)

## Note.
My "custom" EFI is only built for systems running an Gigabyte H370 HD3, an i7-8700 CPU, and an Gigabyte RX 590. The reason why I'm talking about this is because in some of the settings in the config.plist file, those settings may not match your configzation.

Also your SIMBIOS/BoardSerialNumber, /SerialNumber, /SmUUID, and RtVariables/MLB have to be set by you as they are all set to nothing and MAY cause issues when using services like iMessage and other iCloud services to NOT work on your system.

Any other things you want to change is all up to you, just make sure you know what you're doing.

## What does and doesn't work.
### Working
* Networking.
* HDMI, DVI, DisplayPort.
* Sound (USB or not).
* Video editing, and Photoshopping.
### Not working
* Sleep - want to get this fixed even know I don't use it.
