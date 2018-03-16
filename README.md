# Lefthand cursors files

This repository contains Windows 10's AERO style cursor. All of them are edited by ArtCursors. It's very easy to use ArtCursors.

## Step 1:

Install [ArtCursors](http://www.artcursors.com/artcur.htm) or from [here](artcurs.exe).

## Step 2:

Open a cursor file from system folder. In Win10, it is C:\Windows\Cursors.

## Step 3:

In the working area, **menu click -> Flip -> Horizontally** to flip the cursor to point to the right rather to the left.

Menu click: for the left-handed it's Left click while for the right-handed it's Right click.

## Step 4: [This is the KEY process!]

**Menu -> Cursor -> Hot Spot** to set the trigger point.

For the default 32x32 pixel cur cursor, ArtCursors regards the upper left coordinate as (0, 0) and the lower right coordinate as (31, 31). Since we have horizontally flipped the cursor, we should change the Hot Spot Horizontal coordinate to **31-X**, where X is the original coordinate, and maintain the Vertical one.

Take "aero_arrow.cur" for an example, its hot spot should be change from (2, 4) (left) to (29, 4) (right).

For the default 64x64 pixel ani cursor, it is of course to be **63-X**

## Step 5:

**Menu -> File -> Save as** to save the cursor to a new folder.

## Step 6:

Change the cursor scheme in the Control Panel.

## PS

Although the unregistered ArtCursors can be only used for 30 days but it's enough for us to change flip many cursors.

But ArtCursors is not MS systems which can recognize your motherboard, so you may uninstall it if you do not want to use and install it if you want to use. ArtCursors would count from the 1st day.
