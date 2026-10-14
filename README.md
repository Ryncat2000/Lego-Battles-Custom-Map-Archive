# Lego-Battles-Custom-Map-Archive
A Folder that contains all of the custom free play maps alongside the difficulty patch for Lego battles so that players can enjoy a fresh and new experience with an old game

All Maps were made using: https://github.com/LiruJ/LegoBattlesMapTool (Special thanks to them for making this even possible)

(Requires: [Crystal Tile 2](https://www.romhacking.net/utilities/818/))
Video tutorial: https://youtu.be/Bebn7aVaufQ
=
Each map file will have:
=
- .png (Reference image)
- .map (actual map file REQUIRED to replace)
- .tmx (used in the map maker so that users can edit the level)
- .txt (Name of file that has the size being either 64x64 or 96x96 so users dont have to guess what file size it is)

=
Additionally, each file may also have:
=
- .tbp (the Detail tiles each map uses, if this is included in the file, you MUST replace it or else the map will look buggy)
- 4 files with the names: "mini.NCBR", "mini.NCGR", "miniNT.NCBR", "miniNT.NCGR" (minimap files, used for the top screen and preview. you MUST replace these files in order to have the map screen to work correctly) if the minimap files are not included, then this may be a "map fix" file that only changes a vanilla map, make sure you replace the correct one if you wish to replace it.

=
IMPORTANT NOTE: you will have to replace a free play Level in order to play on these maps.
When modifying your ROM always keep a backup as there is a likelihood for your ROM size to get too large and become unplayable.
=
you will know if the ROM is Broken when loading the game shows a grey screen or simply does not load at all

Use this Page for reference: [!LB map sheet - Public.pdf](https://github.com/user-attachments/files/33410398/LB.map.sheet.-.Public.pdf)
every map file is listed as "mp_.map" with a number associated as the underscore. the maps in the game files are listed as mp1.map to mp30.map. Keep this in mind and refer back to the above sheet so that you don't accidentally replace the wrong map file

A good rule of thumb is to ONLY replace 96x96 (large) tile sized maps with other 96x96 (large) tile sized maps to prevent your ROM size from getting to big. The smaller maps use less space in the ROM.
only the 64x64 (small) tile sized maps should be replaced by other 64x64 (small) tile sized maps. Though users can replace 64x64 tile sized maps with 96x96 with minimal issues.

If you are planning on using the difficulty patch, keep in mind that you have to replace every single ".map" file one at a time, There is no quick way to load multiple maps at once currently.
