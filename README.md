# AbletonMinilabExtras
Just trying to get more of the rig

I love Arturia MiniLab MkII with Ableton Live, but was wondering why the pickle buttons on encoders 1 and 9 did not have any use in Shift-Pad8 mode. After some research, I decompiled the scripts and found some information about Control Surface programming. So now the button on encoder 1 arms the selected track, and you can push encoder 9 to mute it. Just replace MiniLab/Minilab.pyc and _Arturia/MixerComponent.pyc, both found under LiveFolder/Resources/Midi Remote Scripts, with the ones found here and put those buttons to use. I believe you should delete both .pyc files too, that's what I did. Hope you enjoy the extra controls!

The trick is documented on code.
