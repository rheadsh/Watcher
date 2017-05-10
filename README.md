# Watcher
Send parameter automation values and clip info from Ableton Live to any application that is OSC ready.
Receive OSC from any application to map on parameters for real-time control.

# Files Description:

### General_Configuration: 
An easy way to setup multiple instances of Watcher in a project.

### Clip_Watcher: 
Sends track and slot number, normalized length and length in seconds. If loop is enabled in the M4L device it sends the message every time the loop starts. 
Choose between the following modes for the info you need:

**Clip Only:** [Track Number, Clip slot number]

**Clip Only + Time:** [Track Number, Clip slot number, Normalized length, Length in seconds]

### Parameter_Watcher: 
Click Select and choose any parameter to send automation data.

### Paramater_WatcherIN: 
Receives OSC data to map on any parameter. MinOut and MaxOut are by default the min and max values of the device selected.


All configuration data is saved with the Ableton Live project.



Tested on:
OSX 10.11.6
Ableton Live 9.7 64 bits
Max 7