# X68000-remote-codes
A collective of remote control codes for the Sharp X68000 series monitors to be used with M5Stick C Plus 2 and [Bruce Firmware](https://bruce.computer/). 

Derived from information available at [NFG Games](https://gamesx.com/wiki/doku.php?id=x68000:go555sa_monitor_remote). Much thanks to that authors of that document, and to the creators of Bruce Firmware for the M5Stick C Plus 2. Without these efforts, this would not have been possible. 

All essential remote functions for operations in this code were tested as working on a Sharp CZ-613D monitor, though some are a little hit or miss and may need to be pressed several times before they work. Determining raw timing for some buttons was easy, while others were stubborn, and yet others refused to work at all. I can't gaurantee they will work with other monitor models in the CZ-6XX series, nor can I gaurantee they'll even work with another CZ-613D. 

Also of note: Input switching buttons such as TV/Computer and TV/Video seem to require an active signal for the button to have an effect. I've noticed a pattern where if I'm not actively sending a composite video signal to the RCA input, for example, the TV/Computer will not switch from the RGB input to composite. Make sure you are sending appropriate signals to the monitor before determining a remote code isn't working. 

Finally, I've also made the working buttons available on SofaBaton universal remotes. If you have one of their remotes, search for the Sharp CZ-613D under TVs, and you'll find my user-created remote codes uploaded there. The list of working buttons for SofaBaton are the same as listed below. 

### Working buttons
- Power (電源)
- TV/Computer (テレビ・ビデオ/ コンピュータ)
- Volume Down (量 - 小)
- Volume Up (音量 – 大)
- Mute (消音)
- TV/Video (テレビ/ビデオ)
- Channel Display (chコール)
- Channel 1
- Channel 3
- Channel 11

### Not working/not available
- Channel 2
- Channel 4
- Channel 5
- Channel 6
- Channel 7
- Channel 8
- Channel 9
- Channel 10
- Channel 12
- Hidden 1
- Hidden 2
