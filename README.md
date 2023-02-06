# dell-optiplex-7010-efi
Opencore 0.8.8 efi files for running Macos Monterey
On a Dell optiplex 7010 and a gt730

# whats working
- Gpu acceleration work though opencore legacy patcher 
- Usb tethering 
# whats not working
- Usb map are not completely working
- Sharing screen results in pink screen


# install guide
1. Copy efi folder to a fat32 usb drive
2. Copy Macos recovery files to usb (https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)
3. Bolt into recovery and install to a formatted drive
4. Mount efi (https://github.com/corpnewt/MountEFI)
