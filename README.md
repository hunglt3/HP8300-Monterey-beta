# HP8300-Monterey-beta
HP8300 Monterey beta 7
 HP 8300/i3 3225 HD4000/4Gb RAM/SSD 128Gb OpenCore 0.7.4 Bootloader

Tested models:
HP Elite 8300 USDT

What works:
Secure Boot
FileVault
Sleep and Wake
Audio
Power Management
USB Ports
LAN
DisplayPort and DisplayPort Audio

What doesn't work:

SMBIOS: Mac mini7,1
To change the SMBIOS go to EFI/OC/Config.plist > PlatformInfo > Generic > SystemProductName Refer to SMBIOS Choices to pick the correct SMBIOS choice that fits your needs.

Power Management
The included EFI/OC/ACPI/SSDT-EC.aml, SSDT-HPET, SSDT-PLUG Intel Core i3-3225 CPU which is the one that my HP Desktop does have. If you have same CPU model on your HP machine, you are good to go, nothing is needed to be done.
If you have different CPU, make your own
