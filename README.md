# Watcher
Send parameter automation values and clip info from Ableton Live to any application that is OSC ready.
Receive OSC from any application to map on parameters for real-time control.

# Files Description:
General_Configuration: An easy way to setup multiple instances of Watcher in a project.

Clip_Watcher: Sends track and slot number, normalized length and length in seconds.
If loop is enabled it sends the message every time the loop starts.

Parameter_Watcher: Send any parameter automation data.

Paramater_WatcherIN: Receives OSC data to map on any parameter. MinOut and MaxOut are by default the min and max values of the device selected.


All data is saved with the Ableton Live project.



Tested on OSX 10.11.4
Ableton Live 9.6