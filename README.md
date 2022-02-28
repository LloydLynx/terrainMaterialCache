# terrainMaterialCache
BeamNG.drive on Linux doesn't generate PBR texture cache correctly, resulting in black textures everywhere on maps that use PBR textures. The solution is to use PBR texture cache generated on a Windows computer. This is a repository of correctly generated PBR cache so Linux BeamNG players can fix their game. 

## How to install PBR texture cache into your game
* Go into the terrainMaterialCache directory in this github and find the zip file for the map you want fix. There are two directories; "Vanilla" and "Mods". Pretty self explanatory. Click on the zip file and download it. 
* The zip will contain lots of .dds files; these are the cache. 
* Extract and put the .dds files into **_BeamNG.drive/0.24/temp/art/terrainMaterialCache/_** on your computer. Make sure to replace any duplicate files with the new ones from the zip. 

### Location of the BeamNG.drive directory
* If you installed Steam as a native package (apt, AUR, etc...), you will find your **BeamNG.drive** directory at exactly **_~/.local/share/Steam/steamapps/compatdata/284160/pfx/drive_c/users/steamuser/AppData/Local/BeamNG.drive_**
* If Steam is installed as a flatpak, look in **_~/.var/app/_** for the Steam directory. I don't know the exact path.
* If snap, good luck. I know even less about that. 

## How to generate cache so you can contribute
* You need a Windows computer with BeamNG.
* Delete all the .dds files inside **_C:\Users\James\AppData\Local\BeamNG.drive\0.24\temp\art\terrainMaterialCache\\_**
* Open the game and load up the map that you want to contribute for. 
* When the map is done loading, there will be new .dds files for it in **_C:\\Users\James\AppData\Local\BeamNG.drive\0.24\temp\art\terrainMaterialCache\\_**
* Add those .dds files to an archive in .zip format. Make sure the .dds files are in the root of the zip file. Name the zip file "terrainMaterialCache" followed by the map name without spaces and the version number. Example: Yellowsand Island version 0.91 would be **terrainMaterialCacheYellowsandIsland0.91.zip**
* Either create an issue with a URL link to the map and a download link to your zip file, or create a pull request. 
