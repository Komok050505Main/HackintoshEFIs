# Hackintosh EFI's
Hackintosh EFI's for some laptops and PC's.

## Acer Aspire A315-41
OpenCore EFI for Acer Aspire A315-41 with AMD Ryzen 3 2200U and AMD Radeon Vega 3.  

macOS Version: Monterey  

AMD Radeon Vega 3 - Works (NootedRed kext)  
AMD AHCI Controller - Works  
Bluetooth - Works  
WLAN (Qualcomm Atheros QCA 9377) - Don't work (requires replace)  
Keyboard - Works  
Touchpad (Synaptics) - Works  
Realtek Audio (ALC 255) - Works  
Realtek LAN - Works  


To get the touchpad and keyboard work:  
1. Go to BIOS settings and press Ctrl+S in the Main tab.  
2. Switch the touchpad mode to Basic.  
3. Save and exit.  

Also I recommend using layout id 80 instead of 15 for Apple ALC to make the speakers work and fix the headphones issue.  

## ASUS K52JT
