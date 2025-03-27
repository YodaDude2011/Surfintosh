# Surfintosh
 Surfintosh is a MacOS 13 EFI made for the Microsoft Surface Laptop Go Model 1943 based on the Dortania OpenCore guide.

 # Getting Started
 Please read this entire guide before continuing!
 
 To install MacOS 13 on your Surface Laptop Go Gen 1, please download the EFI folder. This EFI folder was created using the OpenCore Dortania Guide found here: https://dortania.github.io/OpenCore-Install-Guide/

 Afterwards please follow https://dortania.github.io/OpenCore-Install-Guide/installer-guide/ to download the MacOS 13 recovery images. Once this is complete,
 you will need to generate a uuid and SMBIOS for your device using https://github.com/corpnewt/GenSMBIOS. 
 
 Double check that everything is correct by following https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html#starting-point

 # Recovery Prep
 Please place the EFI folder and the com.apple.recovery.boot folder onto a flash drive that is a minimum of 16GB.

 

 The flash drive should look like this:

 
 ![image](https://github.com/user-attachments/assets/7fbc3ee6-fd76-4896-a98d-ee496c8d56df)

# Installation
Insert your flash drive into your Microsoft Surface Laptop Go (Model 1943). Make sure the flash drive is selected as the primary boot option in the BIOS. 

Once the MacOS recovery screen appears, please follow the installation steps like normal. If there are any issues, please refer to https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/troubleshooting.html#table-of-contents


# Known Issues
As of this time there are several features that are unavailable or issues that are prevalent with this EFI.

Issues:
No bluetooth driver
Airdrop is non-functional
Adjusting screen brightness does not work via keyboard or the control panel (Please install an app like Shade from the App Store as a workaround)
Possible overheat and random restart issue


# Notice
I am NOT responsible for any loss of data, drive corruption, or any other hardware/software issues due to installing MacOS on your device. MAKE SURE YOU BACKUP IMPORTANT DATA BEFORE INSTALLATION, USE THIS EFI AT YOUR OWN RISK.

If there any problems or errors during installation, please refer to the [Hackintosh discord](https://dortania.github.io/OpenCore-Install-Guide/) or [subreddit](https://www.reddit.com/r/hackintosh/). You may create an issue on Github if you would like but there is no promise that I will be able to provide a timely response


