MysteryHack (Ray Dunn's hack)
-----------------------------

Someone, who came across my own port of hack, sent this to me many years ago,
retrieved from an old floppy disk.

To play the game you'll need to unzip the following files into a single folder on
your DOS machine:
   replacement files.zip    <--- Needed for the help and scoring system
   old hack.zip             <--- The unmodified file I received

Inside the .exe I found the following message (also stored in saved games):
   Sunday 22-MAR-1987 - Ray Dunn, Montreal.

Nethack was first released by Mike Stephenson on July 28, 1987.

There are five (5) missing help files (see below), that were deleted to make room
for two saved games. The RECORD file was also missing (it must exist for scores
to be kept).

I have included replacement files taken from PC Hack 3.60.

I have seen no mention of this game anywhere on the internet or in old newsgroup
posts, even though Mr. Dunn apparently posted in the latter frequently in the
late 1980s about DOS and C programming.

I believe this is likely the author's facebook page, the connections being that
he worked for Phillips Electronics in Canada, and that he was a DOS and C
programmer--both facts noted in his usenet posts:
   https://www.facebook.com/raymondunn

Comparing what I call this "MysteryHack" with Hack 1.0.3 (the last version before
NetHack) I made a list of changes (see below).

Donnie Russell II
https://sites.google.com/site/donnierussellii/

----------------------------------------------------------------------------------

This version of Hack features animation, a real-time play option (at variable
speeds) and PC speaker sound effects and music

Uses a Microsoft C Library from 1986

A new "Down-And-Out" class was added, and a Witch as the female complement
of a Wizard (a Cave-woman was already present in Hack 1.0.3)

Doors and keys are present in the game

You can play another game without exiting and re-executing the .exe
(very interesting, since this seems like a very difficult thing to implement
based on what I've seen of hack's source code).

Game messages are loaded from the encrypted file:
   HACKMSGS
I don't know the encryption

Bones and saved games have filenames in the format:
   BONES_{LevelNumber}
   S_{PlayerName}
Two saved files are included

The following files were missing from the archive I was sent:
(they were deleted from the floppy disk to save space;
I have tried to recreate them from PC Hack 3.60 of 1986)
   CHELP
   DATA
   HELP
   NHELP
   OHELP
   RECORD

No new monsters

Some monsters can unlock and open doors

In addition to monsters being invisible they can be:
   mutant
   Siamese twin

Added food items:
   dead parrot
   talking slug
   chocolate coin

Tins can contain SPAM, accompanied by song and animation

Added weapons:
   blow-pipe
   stick of dynamite
   lit stick of dynamite

Added tools:
   match
   crystal ball
   heavy ball of glass
   key

Added armor:
   pointed hat
   shiny pair of boots
   life-jacket

Added potions:
   deafness
   intuition
   sensory deprivation
   x-ray vision
   sloth
   stability
   deodorant

Added potion colors:
   pale
   mauve
   fluorescent

Added scrolls:
   intuition
   anger
   remembrance
   trap detection

Missing scroll title:
   KIRJE

Added scroll title:
   TO WHOM IT MAY CONCERN

Added wands:
   charging
   attraction
   repulsion
   probing

Added wand descriptions:
   golden
   striped

No added rings or ring descriptions

Gems with modified names (brackets indicate added text):
   [sparkling] diamond		
   [glowing] ruby			

Added gem descriptions:
   crystal					
   plastic					
   mineral salt			

Added gem colors:
   clear
   translucent
