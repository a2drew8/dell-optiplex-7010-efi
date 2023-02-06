# dell-optiplex-7010-efi
Opencore 0.8.8 efi files for running Macos Monterey
On a Dell optiplex 7010 and a gt730


![Screen Shot 2023-02-06 at 14 38 41](https://user-images.githubusercontent.com/82539917/217002950-1af17a5c-9f85-4214-883b-5bdbdfbcdf13.png)



# whats working
- Gpu acceleration work though opencore legacy patcher 
- Usb tethering 
- usb wifi adapters https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter
- usb bluetooth using BlueToolFixup https://github.com/acidanthera/BrcmPatchRAM/releases
- 
- 
# whats not working
- Usb map are not completely working
- Sharing screen results in pink screen


# install guide
1. Copy efi folder to a fat32 usb drive
2. Copy Macos recovery files to usb (https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)
3. Bolt into recovery and install to a formatted drive
4. Mount efi (https://github.com/corpnewt/MountEFI)
