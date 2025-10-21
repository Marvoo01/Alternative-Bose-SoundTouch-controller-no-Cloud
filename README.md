# Alternative-Bose-SoundTouch-controller-no-Cloud
Alternative Bose SoundTouch controller without the Bose Cloud.

I have created some html files to control the Bose Soundtouch speakers over their api when the Bose cloud stops. 
It's just a shame that the six preset buttons are almost certainly expected to stop working, as the SoundTouch will 
likely request information from the cloud when you press them. If that's not the case, that's fine, and I have a preset 
editor for the SoundTouch API.

I've created several files. The ones with speaker feedback require you to disable your browser's CORS security if you want 
to test them. This can be done with a simple extension like Access-Control-Allow-Origin.

The files are, of course, based on my speakers. So, if you wantg to tgest on your speakers you need to adjust the IP, Mac, and speaker ID.
You can find that here http://IP of your speaker:8090/info

Look for the lines:

info deviceID=

macAddress

ipAddress


Finally, I created a master SoundTouch with a WiiM mini streamer attached to it. I select presets 1 
through 12 in the HTML and connect one or more SoundTouch slaves via the SoundTouch API. This works very well.

Hope this helps and we can make a perfect controller without their Cloud.
