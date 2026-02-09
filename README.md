# X68000-remote-codes
A collective of remote control codes for the Sharp X68000 series monitors to be used with M5Stick C Plus 2 and [Bruce Firmware](https://bruce.computer/). 

Derived from information available at [NFG Games](https://gamesx.com/wiki/doku.php?id=x68000:go555sa_monitor_remote). Much thanks to that authors of that document, and to the creators of Bruce Firmware for the M5Stick C Plus 2. Without these efforts, this would not have been possible. 

All remote functions in this code were tested as working on a Sharp CZ-613D monitor. I can't guarantee they will work with other monitor models in the CZ-6XX series, nor can I gaurantee they'll even work with another CZ-613D. 

Also of note: Input switching buttons such as TV/Computer and TV/Video seem to require an active signal for the button to have an effect. I've noticed a pattern where if I'm not actively sending a composite video signal to the RCA input, for example, the TV/Computer will not switch from the RGB input to composite. Make sure you are sending appropriate signals to the monitor before determining a remote code isn't working. 

Finally, I've also made the working buttons available on SofaBaton universal remotes. If you have one of their remotes, search for the Sharp CZ-613D under TVs, and you'll find my user-created remote codes uploaded there. The list of working buttons for SofaBaton are the same as listed below. 

### Working buttons
- Power (電源)
- TV/Computer (テレビ・ビデオ/ コンピュータ)
- Volume Down (量 - 小); note that the OSD may not visible in Computer/RGB15 mode but button still lowers volume
- Volume Up (音量 – 大); note that the OSD may not visible in Computer/RGB15 mode but button still raises volume
- Mute (消音)
- TV/Video (テレビ/ビデオ); note that this button does nothing when Computer/RGB15 input is selected
- Channel Display (chコール); note that this button has no effect when Computer/RGB15 input is selected
- Channel 1
- Channel 2
- Channel 3
- Channel 4
- Channel 5
- Channel 6
- Channel 7
- Channel 8
- Channel 9
- Channel 10
- Channel 11
- Channel 12
- Hidden 1 (test in Computer/RGB15 mode; input should switch to Composite/RCA, then back on 2nd press)
- Hidden 2 (test in Computer/RGB15 mode; monitor should black out briefly then resume picture)

### Troubleshooting

If you find these codes are not working for your monitor, here are some things you can experiment with:

1. If nothing works, vary the carrier frequency and/or duty cycle. Start at 38khz with a base and vary up or down within 1khz. Start with a duty cycle of 25% and vary plus or minus 20-33%. And of course, confirm your monitor has an IR receiver. Not every monitor in the CZ-6XX series does.
2. Change the gap between Frame A and Frame B,  and/or the gap following frame B. Keep gaps consistent between frames.
3. Make sure you are in the correct mode for buttons that have mode-specific functions, and that appropriate inputs are being sent to the monitor for the given modes and button functions. Known mode-specific buttons/states are listed above. 
