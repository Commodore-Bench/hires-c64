#Hi-Res BASIC Extensions for Commodore 64 and Documentation Demo Program

I added some commands to Commodore 64 BASIC via software extensions
written in 6502 Assembly.

Notable features
* Multiple hi-res screen support (up to 5) and swap between them
* Two hi-res screens and color tables using 18K RAM under ROM and I/O
* Doesn't take away any BASIC RAM, only uses $C000-D423 extra RAM
* Copy shapes of any size between screen and memory
* HIRES, COLOR, PLOT, RECT, PATTERN, SHAPE commands
* Machine language interface included if BASIC isn't your thing
* Scrolling BASIC Editor support (scroll with F1/F7)

The introduction to this software is documented on my blog
[http://hires.davevw.com/](http://hires.davevw.com/)

[C64 disk image (binaries only)](https://github.com/davervw/hires-c64/raw/master/build/hires.d64)