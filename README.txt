Added a UCI implementation of sargon.lua: sargon_uci.lua
UCI is still not fully implemented because of restrictions of the original Sargon code, especially the "position FEN" commands.
But for a straight forward game without taking back any moves more than 2 half moves it should work fine.
No opening books should be used! 
Tested with picochess on a DGT PI and in Shredder GUI.


This is a small sample of Lua based chess to run from command line.

1. GarboChess.bat - good port of chess engine to Lua
 (ported from javascript)

2. fruit21chess.bat - good port of Fruit chess engine to Lua
 (ported from C++)

3. EmulatedOliThink.bat - kind of scientific port of a 64bit chess engine.
  NOT a useful Lua chess AI. Anyway, interesting to see checkmate at the end:)

4. c0_chess.bat - a lua library for chess

5. sargon.bat - Sargon assembler code of 80s ported to lua
   history at http://chessprogramming.wikispaces.com/Dan+Spracklen
   Just fast and simply positional. Not strong, improvable.

6. LuaJester.bat - Very good chess program for 32-bits, and fast. Almost best what lua can perform.

7. OwlChess.bat - a port of an old '92-95 Owl Chess program
 in Borland Turbo C (from javascript port). Good and well documented.
 It was written when no 64 bits seemed useful. :)
 This version sometimes crashes on LuaJIT.

Other:
---------

1. polybase.bat - a polyglot book reader sample

2. abkbase.bat - an Arena book reader sample



Also lua to loadfile:
---------------------
i64.lua - emulated 64bit variables to get working (1<<63)

noBitOp.lua -  can be used instead of BitOp (but slower)

c0_chess_subroutine.lua - chess logic, not a fastest code


Updated 2017.feb.
