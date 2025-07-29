# DCTLs 

## What are DCTLs
DCTLs are color transformation scripts for DaVinci Resolve, functioning like LUTs but using C-like syntax instead of interpolated lookup tables for direct image transformations. 

## Requirement
- DaVinci Resolve Studio (version 17 or newer is recommended)

## Installation
1. Copy the `.dctl` file to your DaVinci Resolve LUT folder
- Windows:  C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT
- macOS: Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT
- Linux: /home/resolve/LUT

2. Restart Davinci Resolve
   
3. Once DaVinci Resolve starts, go to the Color page and create a serial node by pressing Alt+S.

4. Navigate to Effects > Resolve FX Color > DCTL, drag and drop it onto the node you just created. Then select your DCTL from the dropdown menu.
