Diablo II Palettes for Paint Shop Pro
=====================================

The "d2-act0.pal" is a special palette, designed to make items
that won't have problems. It have cyan for the index 0, and
magenta for the colors that changes from act to act.

Say you have a bitmap of an item you want to convert into a dc6
(either a truecolor or a indexed one).

   1. Take your bitmap and make the background cyan
   2. Make sure you don't have magenta in your bitmap
   3. Now convert it  : load the "d2-act0.pal" with the
      "nearest color matching" option, or even the
      "error diffusion dithering", BUT NOT the "maintain same index"

You have now an item with background properly set to index 0, and
which don't use the colors that change from act to act.

Now, just use dc6con or dc6maker, and your item should be all fine
(with dc6con, don't forget the '-transcol 0' option to have transparent
background, or else your item in the game won't be transparent : it
will have a black background instead)


Use of the Palette in the game :
--------------------------------
d2-act0.pal      : don't exists, special palette for the purpose of creating items
d2-act1.pal      : act 1 stuffs & inventory gfx
d2-act2.pal      : act 2 stuffs & inventory gfx
d2-act3.pal      : act 3 stuffs & inventory gfx
d2-act4.pal      : act 4 stuffs & inventory gfx
d2-act5.pal      : act 5 stuffs & inventory gfx
d2-endgame.pal   : ending screen (Talrasha giving you honorific title)
d2-endgame2.pal  : ending screen (Cain giving you honorific title)
d2-fechar.pal    : character creation screen
d2-loading.pal   : loading screen (the Wanderer in front of the Monastery doors)
d2-menu0.pal     : ?
d2-menu1.pal     : ?
d2-menu2.pal     : ?
d2-menu3.pal     : ?
d2-menu4.pal     : ?
d2-sky.pal       : game selection screen
d2-static.pal    : all GUI (Graphic User Interface) stuff (get some random results)
d2-trademark.pal : trademark screen
d2-units.pal     : all the GUI icons (but in has been succefully used for the
                   trademark screen, game select & Gui stuff, without distorsion)
