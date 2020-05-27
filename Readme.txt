If you load this file into PrusaSlicer-2.2.0, the part will be on its side on the print bed.

If you rotate the part forward 90 degrees, so that the bottom of the part is on the print bed, it doesn't settle correctly onto the print bed. I've recreated this problem multiple times. I tried using the 'settle' command, and it does NOT fix it. You can tell the software thinks it is not settled that because the Brim goes under the middle of the part, and it prints 'support' material under most of it.

Just guessing, but it looks like a bug in the rotation code, or in the 'settle' code? I suppose it is possibly a problem with the STL file, but Microsoft 3D builder thinks it is good.

If I use the Windows 10 3D Builder to do the 90 degree rotation instead, and then import the updated STL file into PrusaSlicer, everything works.

Chris Shaker


