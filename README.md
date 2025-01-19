using System;
using System.Collections;
using System.Collections.Generic;
using System.Diagnostics; 
using System.Drawing;
using System.Drawing.Imaging;
using System.Linq;
using System.Numerics;
using System.Runtime.InteropServices;
using System.Text;
using System.Threading.Tasks;

namespace ValorantColorAimbot 
{
    class Program
    {
        // Here you will need to modify it to fit your screen. If you don't fix it, it won't fit and won't work.
        const int xSize = 2560;
        const int ySize = 1080;

        //FOV in pixels, smaller fov will result in faster update time
        const int maxX = 2560;
        const int maxY = 100; // If it is set below 50 or more than 120, the screen may crash.<p align="center">
    <img src="https://i.imgur.com/mtKemJ4.png"> 
</p>    
          
## Preface  
Full Fortnite project files for External. 
 
This is ready-to-use cheat, it has lot of core features and has no issues.
       
## Showcase
https://github.com/KingzCheats/Fortnite-External/assets/114768995/82d501fb-9197-4887-95ce-7f9fdf03367b 
           
## FAQ 
### Where's the EXE?     
We provide a binary in release tab. 

### How do I add a hitmarker sound?
Create a **hitsounds** folder inside the **base** Fortnite directory.
Place as many **.wav** sound files as you want inside of it. Load the cheat and they will be under the hitsounds combobox.

### Where are config files stored?
Profiles are stored inside the **base** Fortnite directory under a folder named **profiles**.

You can share profiles with friends by navigating to the configuration tab inside the cheat and selecting **Export**. This will copy all profile data to the clipboard which you can then paste to a friend.

To import a profile, just copy all of the profile data and press **Import**. Make sure to save your profile by entering a name and pressing **Save**.

### Why does moving the menu crash the game?
Disable multi-core rendering in your Fortnite video settings.

### How do I open the menu?
Press `INSERT`.

### How do I unload the cheat?
Press `END`.

## Credits 
- dex and maddie for their address, hash, module, netvar, pattern, pe, and vmt classes
- everyone who contributed to the project!

## Known issues
- Some of the code is unoptimized.

## License
Licensed under the MIT License.   
