# PacMan Lives
MITxPro project writing a program demonstrating PacMan bouncing from one edge of the screen to the other looking for something (***anything!***) to eat.
### Details 
The program makes use of four images depending on the direction of movement on the screen (with mouth open and closed). It uses a two element array within an array indexed at the direction (number indicating way it's facing) and focus (number indicating mouth opened or closed) of the image. The direction changes based on when the image reaches the border of the page (based on both the page's width and image's width). The focus alternates from 0 to 1 each time an interation takes place -- showing a very hungry PacMan indeed.
