## Parts Install Speedup for PC Building Simulator
Quadruples your current part install/uninstall and cable plug speed. Also increases screw speed. For lightning fast builds. 

Now fully compatible with my customer stats mod, just make sure you use this patch AFTER installing the customer stats mod or any other mods that fully replace the Assembly-CSharp-firstpass.dll.

Update: After I got some feedback that the manual screw speed wasn't affected by this mod I fixed that, so that should be faster now as well!

## Install
1. Extract all files in the archive to the main directory of PC Building Simulator
2. Run PartsInstallSpeedupInstall.cmd
3. If the patching has been successful you can start the game (should say "1 change(s) applied to file" 11 times)

## Notes
Tested on PC Building Simulator version 0.8.2.1/0.8.3.2. Might work with newer versions, but this is a binary patch - albeit a partial one - meaning if the moving code of the game changes in a future version chances are this patch will not work anymore. If you're unsure just make a backup copy of /PCBS_Data/Managed/Assembly-CSharp-firstpass.dll and then run the patch. If it says something like "no changes made" it is either already patched or not compatible with that version of the DLL.
This mod should be compatible with all other mods that only partially change the Assembly-CSharp-firstpass.dll.

## Credits
Uses hexpatcher ( https://sourceforge.net/projects/hexpatcher/ ) for the binary patch.