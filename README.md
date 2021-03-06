# MassEffectTextureMapper

**Introduction**

This program is intended to facilitate modding of the Mass Effect trilogy (ME1, ME2, ME3).

Textures in those games are represented by hashes (hexadecimal IDs, ie 0x12345678). Many textures are reused across several games, sometimes identically, sometimes only with a resize or a small color change between one game and the other. This program makes use of a database of such textures made by AlvaroMe and myself, CreeperLava.

**Usage**

1. Input the list of the files you wish to port in the left pane. One file per line. File names can be whatever you like, as long as the hashes are present in them. ie

![](https://i.imgur.com/Ua5I5xC.png)

2. Select the options you need. Hover over each checkbox to view the functionnality they provide in a tooltip.

3. Select the game you wish to port your textures to. The game your hashes come from doesn't matter. You can port textures from several games at once.

3. Click Go. The tool will match your hashes with the database, and create a batch file (.bat) in the directory you ran it from. It will be named ME1.bat, or ME2.bat, or ME3.bat, depending on which game you're porting to.

![](https://i.imgur.com/oAClrhl.png)

4. Copy/paste the .bat file into the directory your textures are in.
Only BMP, PNG, DDS extensions are supported for the copying, though you can easily modify the batch file yourself to change the extension.

![](https://i.imgur.com/5qcXIoe.png)

5. Run the .bat file. The ported textures will be located in a new folder named ME1, ME2 or ME3.

![](https://i.imgur.com/lz5fdjH.png)
