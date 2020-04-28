## AY-Players ##

- collection of pretty formated and most versatile Zilog Z80 players of well know music tracker file formats for AY-3-8910/2
- all players has integrated setup variable which controls looping or fadeout effect:
	- `bit.0` - if you want to play without looping
	- `bit.1` - if you play looped but fadeout after few seconds
	- `bit.7` - is set each time when loop or fadeout was passed
	- ...or simplified:
		+ `2` - fadeout after loop
		+ `1` - no loop
		+ `0` - loop forever

+ [**`PTx.a80`**](PTx.a80) - **ProTracker 2.x**..**3.7** © 1995-2007 Golden Disc & S.V.Bulba
  - universal player with autodetection of format, tone-table and volume-table
+ [**`SQT.a80`**](SQT.a80) - **SQ-Tracker 1.xx** © 1993 George K./Proxima Software
+ [**`STC.a80`**](STC.a80) - **Sound Tracker 1.x** © 1990 Bzyk/Pentagram
+ [**`STP.a80`**](STP.a80) - **Sound Tracker Pro** © 1997 KSA software


**Conditional compilation**

- `define PUREPLAYER`
  if you want to include player in your project
  (without looper and demo song included)

- `define SINGLESETUP`
  if you want just single setup byte through all players
