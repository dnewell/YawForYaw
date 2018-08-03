# YawForYaw
Live rotation options for YawCam streams.  Adds image Yaw to YawCam where it was needed most. Super Yawmy. Love it or your money back.

Less absurdly said: this repo contains drop-in replacement templates adding a 'Rotation' menu to the streaming interface served by YawCam.
The templates for both Javascript and MJPEG stream formats have been modded.
All other functionality has been maintained, and a few small (non-critical) bugs have been fixed.

![alt text](https://github.com/dnewell/YawForYaw/blob/master/screenshots/newMenu_highlight.png "Screenshot of new 'Rotation' menu")

## Installation:

To install, simply replace the two YawCam `/stream/` template pages with the lovingly modded ones from this repository,
`Shift-F5` (refresh) any open streams, and enter a new and sexy rotation-option filled world.

By default, on Windows 10, these templates are located at: ```C:\Users\_yourAwesomeUsername_\.yawcam\stream\```



### Tested and Working on:
* Chrome 68.0.3440.84
* Chrome Canary 70.0.3511.0
* Firefox Quantum 61.0.1
* Opera 54.0.2952.64
* Microsoft Edge 42.17134.1.0

_Completely broken on Internet Explorer. The fix is trivial and obvious - get a better browser. Seriously, though: if anyone cares, pull requests are welcome._



