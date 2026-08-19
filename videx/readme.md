# ROMs for VIDEX VideoTerm cards and clones

Fat N and Fat I are a "phat" C64 like font for the Videx cards. Requires two 2716 chips installed into each of hte Font rom locations

VIDEX FW 2.1 1981 2708.bin - an earlier Videx program ROM. It does not support the soft-switch module and works in any slot.

VIDEX ROM Fixed registers.bin is a modified version of the Videx 2.1 firmware with improved registers with 8 scanlines per character. This results in an image that nearly matches the stock Apple II/Apple II+ display. (No problems with text going off the top and bottom of your monitor.)

Videx Clone: These are ROMs (3 of them, one program and two fonts) from a Clone card I bought off eBay. It has a normal and inverse font in the ROMs. Does _NOT_ support the auto switcher module.

videx firmware 600 1982 - bottom - 2708 - FIXED.bin - this is the latest VIDEX program ROM that properly supports the auto switch module.

Config Register Differences.png - this file shows the CRTC 6845 registers in the ROMs. Both the stock ROM and the clone ROM, and then my "fixed" values to fix the centering and size issues. You can modify your own ROM with these values.
