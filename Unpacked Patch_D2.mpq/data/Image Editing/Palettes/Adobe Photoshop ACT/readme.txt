==================================
= Photoshop ACT palette file for =
=    Diablo2 DC6 Modding         =
==================================

Since the palettes for each act uses a 31 out of the 256 
colors of an index palette for each act's tile theme. Using 
all 256 colors for D2modding will often result in warping
from act to act. This ACT file will help Photoshop users
solve the problem. Other ACT files will enable Photoshop
users to edit the various screens in D2 efficiently.

--------------------------------------
 The Zip file includes five (5) files:
--------------------------------------
readme.txt (this file)
D2PAL.act
D2CharSelect_Trademark_GameSelect.act
D2EndGame2.act
D2Loading.act

--------
 Usage:
--------
NOTE: This readme is meant for intermediate Photoshop users. It is
assumed that you've mastered the basics of Photoshop when reading this:
you should at least know where the menus, tools are. If you're a
beginner in Photoshop, you might want to practice and pick up some
basics tutorials first.

Palettes:
D2PAL
- for use with inventory dc6's.
D2CharSelect_Trademark_GameSelect
- for use with CharSelection Screen, Trademark, Gameselect Screen,
Ctrlpnl7, 800Ctrlpnl7 and more I believe. Basically everything that
concerns the interface of the game uses this palette.
D2EndGame2
- for use with the Ending screen for cLOD, endgame2.dc6
D2Loading
- for use with loading sequence, loading.dc6

* Unzip the ACT's into a convenient working directory
* Work on your image in RGB, while making sure you have your
  desired background transparency as pure black (0,0,0)
* Once satisfied with your work and ready for conversion into
  index colors...
* Image ->
  Mode ->
  Indexed Color...
* Under Palette dropdown option select "Custom...", followed
  by "Load..."
* Select an appropriate palette from where you unzipped it
* Click OK all the way until you return to your work
* You should realised some of your colors may change but not
  drastically
* Replace parts which turned into 0,0,0 but not meant to be   transparent to 4,4,4
* Save as bmp and you're ready to convert to dc6

---------------
 Known Issues:
---------------
Some images might require darkening by about -20 brightness for it to
look proper, since D2 has a way of brightening images.

D2pal: You can't use bright, hot pink with this palette, not that a
lot of people will use bright, hot pink in a medieval themed
game. This is because bright pink is used as placeholders to
screen out those index used for act tilesets.

--------------
 Extra Tools:
--------------
CV5
- http://user.cs.tu-berlin.de/~mickyk/cv.html
DC6Maker 2.0 + 2.1 Upgrade
- http://dynamic2.gamespy.com/~phrozenkeep/site/filecenter/filecenter-1-tools-3-0002.php
- http://dynamic2.gamespy.com/~phrozenkeep/site/filecenter/filecenter-1-tools-3-0003.php
DC6Maker 3.0
-http://dynamic2.gamespy.com/~phrozenkeep/site/filecenter/filecenter-1-tools-3-0004.php

------- 
 Tips:
-------
*When in doubt, load up the original bmp's converted from the dc6's and
apply the ACT files. Any distortion will mean that it is the wrong ACT.
*CV5 may crash when trying to browse images with palettes that it
doesn't have, in this situation, use MPQview to extract the dc6's you
want.


Last updated: 11 Jun '02

File exclusive distributed at Phrozen Keep:
http://dynamic2.gamespy.com/~phrozenkeep/site/

Contact for bugs or problems:
SubSanity
j0e737@hotmail.com
