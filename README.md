# BusMousOMatic

Update 1 changelog: Improved Silkscreen (part descriptions wherever connections go, correction of the DB9 connector gender), added STL and FreeCAD for a basic 3D-printed base plate (a fully enclosed case does not make sense for this project, but at least the solder joints don't touch a potentially conductive surface it is placed on), added BOM for TME (tme.eu) for 5 boards (the minimum amount of PCBs you can order at PCBWay, JLCPCB and similar), separately uploaded Excel Sheet for connector pinouts instead of including it in the main RAR archive

Passive PCB (KiCAD Project) that let's you adapt any Bus Mouse type to anything
BusMousOMatic is a passive PCB that converts various Bus Mouse types to others. A Bus Mouse is a mouse that uses quadrature coding (X/XQ, Y/YQ) directly on the mouse connector.

My assumption is that anybody from the retro scene owns something like a Amiga Tank Mouse which is still quite common, or some adapter like the Rys Mk II, MouSTer or my USB RetroARDUInput, also available here on Github. So an Amiga or Atari Mouse or Mouse Emulation should be available for anybody.

For this reason, I assumed that Amiga or Atari Mouse is the input, however, you also could use one of the Mini-DIN or an Amstrad or Apple Lisa Mouse as Input, but require a Gender Changer for the other DB9 Mouse Types.

Just pull wires 1:1 between the pin headers to select your connector and pinout you want to convert from or to.

Supported types are:

- CN1: Mouse Input for Commodore or Atari (D9M on the board, D9F on the mouse)

- CN2: Mouse Output (can also be used as Input with a gender changer) (D9F on the board/mouse, D9M on the host):
  - Position Amiga: Commodore Amiga Series, PC1, PC10-III, PC20-III, Colt
  - Position Atari: Atari ST Series, Atari PC with Atari Bus Mouse Port
  - Position Amstrad: Amstrad/Schneider PC1512, PC1640, Sinclair PC-200
  
- CN3: Mouse Output (can also be used as Input with a gender changer) (D9M on the board/mouse, D9F on the host):
  - Position Lisa: Apple Lisa
  - Position PC98: NEC PC-98
  
- CN4: Mouse Output (can also be used as Input) Mini-DIN 9:
  - Position InPort: Microsoft InPort
  - Position Archimedes: Acorn Archimedes
  - Position Headstart: Headstart Computers (e.g. Headstart Explorer)
  
- CN5: Mouse Output (can also be used as Input) Mini-DIN 8:
  - Position NeXT: NeXT Cube (Non-ADB Version)
