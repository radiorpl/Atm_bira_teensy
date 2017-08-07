# Atm_bira_teensy
this is my code for help on the teensy forum

This code combines the teensy audio and automaton libraries
to create state machines, so that, in this instance, one encoder can
be used to control different parameters.

This code can play back 2 wav files. An encoder and button can change track and 
stop and start the player. Another button switches which wav player the encoder and 
other button control.

Atm_master_vol uses an encoder to change the volume. Right now it works for controlling the
master volume out of the sgtl5000, but when i tried to make it be able to control mixer gains for the
different wav players, it does not seem to work.

I have sgtl5000 and the AudioMixer4 objectes declared the same way, so why does only the sgtl5000 work?
