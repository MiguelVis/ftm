Find That Mine!
===============

A MineSweeper clon game for the CP/M operating system and the Z80 cpu
with supported CRTs.

v2.0 - 07 April 2020.

Copyright (c) 2012-2020 Miguel Garcia / FloppySoftware, Spain.
www.floppysoftware.es
floppysoftware@gmail.com


Introduction
------------

This is a clon (yes, one more!) of MineSweeper for CP/M with supported CRTs,
derived from the plain CP/M version (and itself from the Amstrad PCW
& Samaruc GUI version).

It should run in any version of the CP/M operating system, running in any
computer with a supported CRT, and a Z80 CPU.


Running the game
----------------

To start the game, type at the CP/M prompt the following:

```
ftm TTY_NAME
```

where `TTY_NAME` is one of the supported TTY names,
and follow the instructions.

To know the supported TTYs, just type `ftm` at the CP/M prompt - ie:

```
A>ftm
Usage: ftm tty_name

Supported TTY names:
        VT52
        VT100
        PCW
        CPC
        SPECTRUM
        KAYPRO
```

The game
--------

The aim of the game is to find all the mines on the board, putting a flag on
them and uncovering the other squares.

If you uncover a mine, you lose the game.

There are three different levels:
- Level 1 : 08 x 08 squares, 08 mines
- Level 2 : 08 x 12 squares, 12 mines
- Level 3 : 08 x 16 squares, 16 mines


How to play
-----------

In the board, a number on a square means the quantity of mines around it.

To uncover a square, you must enter a command telling its position as row and column - ie:
```
1C
```

To put or remove a flag on a square, you must append a F character to the command - ie:
```
3DF
```


Technical notes
---------------

This program was developed using MESCC (Mike's Enhanced Small C Compiler - my
own version of Small C) and my KS (Keyboard & Screen) libraries for CP/M.


License
-------

This software is copyright of Miguel Garcia / FloppySoftware, Spain. All rights
reserved.

This program is freeware, and it's licensed under the GNU General Public License.

See the license file for more details.

