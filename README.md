# AppleBrainBoard
Use the BrainBoard to load DOS 3.3 on Apple II power up or control+B Reset. 
Additionally a Control+C Reset will load DOS and then catalog a disk in disk drive #1.
The code expects to be loaded into a 27C256 EPROM (or a EEPROM). Currently the code resides in the bank 0 of the Brain Board.
I found the Brain Board for sale on Ebay. I since have located websites about the board.
https://www.willegal.net/appleii/brainboard.htm
Back in the 80's I converted an Apple ROM card to be a DOS HOSS from Jim Sather's book Understanding the Apple IIe.
I took the ROMs I created from that project and extracted Apple DOS from those ROMs, as well as the F8 monitor code.
I then packed this into a new EPROM. I then figured out a way to transfer the DOS into the Apple, doing it a bit different
than the way Jim did it. Seems to work. Future project will be to add Integer Basic load using the upper bank of ROM in the
Brain Board.
I plan to expand this readme as time permits. There are notes in my assembly source code that will be helpful.
