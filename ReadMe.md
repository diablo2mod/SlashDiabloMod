## Testing Branch.
All modifications prior to master branch merge will be performed here.

### Tools and testing.

Lookup table found here: http://diablo2mod.github.io/SlashDiabloMod/

Modify and add runewords/gemwords/jewelwords: http://www.planetdiablo.com/modding/guides/runewords/

Beginner's Guide to Mod Making: http://phrozenkeep.blob.core.windows.net/public/files/resources/BeginnerGuide-v14.pdf

Tools and software: http://d2mods.info/filecenter/dload.php?action=category&cat_id=1

Suggested tools:
  * MPQ Viewer – for viewing and extracting files from the .mpq archives. There is a separate 
datafile for all known contents of the archives, without it MPQ Viewer won’t know what to look 
for. The datafile gets changed with almost every game release. 
  * Tab Delimited Text Editor – for editing the database txt files. D2Excel is designed specifically 
for these files, and is available for download. Microsoft Excel or other spreadsheet programs will 
work, if you import and export as tab delimited text files with nothing for string delimiters. Also, 
MS Excel will corrupt the data table if the rightmost fields are empty. Although the files have .txt 
extensions, they are not ordinary text files, so do not use a word processor or even Notepad as 
they will corrupt the databases. 
  * Baron Darkstorm’s Table Editor – for editing string table files. This is an easy tool to use, but it 
has trouble with PatchString.tbl file (more on this later). Other tbl editors are D2Tbl and Peer 
TBL Editor (v3.38). 
  * DC6Con and DC6Maker – for viewing and converting dc6 type graphics files. 
  * CV5 (v5.2) – for extracting, viewing and converting several types of graphics files. One 
component, CVDCC.DLL (now at v3.0), is required for dcc files but may be a separate 
download. Editing animation files is outside of the scope of this guide. 
  * MPQ2K and MPQ Stormless Editor – for packing your files into an mpq after you have changed 
them. 

These tools are suggested but there are newer (and potentially better) tools out now.  If you find a better tool, please let us know.

Link to unmodified D2LOD patch_d2.mpq: http://bhfiles.com/files/Diablo%20II/1.13c/[original%201.13c]%20patch_d2.mpq
### Proposed modification:

- [ ] firestorm proc being taken off of the Phoenix runeword.
- [ ] Removal of weather.
- [ ] Removal of npc/non-monster animals.
- [ ] %ed/max dmg jewel bug (jewels like this only work in weapons)
- [ ] fend bug (info: http://diablo.incgamers.com/forums/showthread.php?490462-In-Game-Analysis-of-the-Fend-Bug)
- [ ] ladder specific items available in non-ladder
- [ ] Hell difficulty increase.  Across the board or just farms?
- [ ] Build specific tweaking.
- [ ] Enigma teleport cast rate decrease?

### Proposed modding tools

SVR D2 Mod system: http://ladderhall.com/forums/topic/30189-svrs-d2-mod-system/ ? (might be 1.10 only)
PlugY for larger stash? (might be 1.10 only)

.