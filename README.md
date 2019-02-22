# mixer4nonokontrol2

Plug & play linkage to Korg nanoKontrol 2 mini mixer.


version 1.0 2/12/19 by Rich Rath

Pan, solo, and mute work for all channels with the following exception: On channel 7, labeled "Bass", the pan control manages the master volume.  This is because (a) Bass is usually centered, and (b) there is no Master Volume slider on the nanoKontrol 2 (apparently there was on the first version).

"r" buttons are not connected, and there are a bunch of unused buttons on the left as well.  If you want to connect them, use the midi monitor to find out what the nano is sending and then find the equivalent in "CC to Param_1".  To save some frustration, remember that the nano sends channel 14, not channel 1 by default!

In addition, I have put a transport link connected to the play button to start and stop the transport. The "stop" button to the left of the play button on the nano is a momentary switch that will either stop the playback, or if it is already stopped, will turn playback on only for how long the button is pressed.  On resuming the regular "latched" play buttoin, you might have to hit it twice to resync it after using the momentary "stop" button. It is less complicated to just hit the buttons and see what they do to the mixer!  

On the master channel of the group interface, "UI" opens the underlying plogue 8-track stereo mixer.  "Metro" opens the metronome and transport group, and "Meter" opens a master bus level meter.

enjoy! I hope someone else finds this useful.  

Issues, etc, can be registered at https://github.com/rcrath/mixer4nanokontrol2
~Rich
