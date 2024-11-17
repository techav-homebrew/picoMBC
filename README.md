# picoMBC

picoMBC is a generic Pi Pico expansion card for the Sanyo MBC-1000 computer. The primary goal is to add an SD card interface for mass storage, but with some available I/O for future or alternate use.

The MBC-1000 expansion interface is a buffered breakout of the Z80 I/O interface. It does not provide the upper 8 bits of the Z80 address bus or signals required for memory space addressing or DMA. To save I/O, picoMBC multiplexes the 8-bit data and address busses. 