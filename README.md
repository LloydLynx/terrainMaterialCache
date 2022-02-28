# terrainMaterialCache
BeamNG.drive on Linux doesn't generate PBR texture cache correctly, resulting in black textures everywhere on maps that use PBR textures. The solution is to give BeamNG PBR cache generated on a Windows computer. This is a repository of correctly generated PBR cache so Linux BeamNG players can fix their game. 

## How to install PBR texture cache into your game:
* Go into the terrainMaterialCache directory in this github and find the zip file for the map you want fix. There are two directories; "Vanilla" and "Mods". Pretty self explanatory. 
* The zip will contain lots of .dds files; these are the cache. 
* Extract and put the .dds files into **_BeamNG.drive/0.24/temp/art/terrainMaterialCache/_**. Make sure to replace any duplicate files with the new ones from the zip. 

### Location of the BeamNG.drive directory
* If you installed Steam as a native package (apt, AUR, etc...), you will find your **BeamNG.drive** directory at exactly **_~/.local/share/Steam/steamapps/compatdata/284160/pfx/drive_c/users/steamuser/AppData/Local/BeamNG.drive_**. 
* If Steam is installed as a flatpak, look in **_~/.var/app/_** for the Steam directory. I don't know the exact path.
* If snap, good luck. I know even less about that. 
