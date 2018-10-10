# Tower Of Hanoi

Animated solution of Tower of Hanoi puzzle

<img src="th.gif" width="400">

This is written in Haskell language.
The solution is wellknown recursive algorithm (https://en.wikipedia.org/wiki/Tower_of_Hanoi)
The animation is using Haskell Bricks library.


# Program Design.

The recursive algoriths produce a list of steps to move the disks.
These steps are then converted to a list of animation commands understand by Bricks Animation.

The bricks animation understands basic commands (CUp, CLeft, CRight, CDown) to move the disks.
The animation command 'CLeft 0' means move the disk 0 towards left one step. 

The commands are send to the animation through Bricks BChan


