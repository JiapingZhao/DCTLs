# DCTLs 

## What is DCTL?
DCTL stands for Davinci Color Transform Language. It is a computer language/transformation scripts that works with Davinci Resolve. 

## What do I need?
- You will need the paid version of DaVinci Resolve to run this tool.

## How do I install DCTL on my PC
Here is a step-by-step tutorial for DCTL installation:

1. Copy the `.dctl` file to your DaVinci Resolve LUT folder
- Windows:  `C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT`
- macOS: `Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT`
- Linux: `/home/resolve/LUT`

2. Restart Davinci Resolve
   
3. Once DaVinci Resolve starts, go to the Color page and create a serial node by pressing Alt+S.

4. Navigate to Effects > Resolve FX Color > DCTL, drag and drop it onto the node you just created. Then select your DCTL from the dropdown menu.
