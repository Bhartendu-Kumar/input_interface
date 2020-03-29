# auto-play-pause-video-using-webcam
A video being played can be paused if you are looking away from the screen and played if you return to it.

## Working

+ Run the file *facerecog.py* and in 15 seconds play the video in a media player. <br />
+ Put the video in the *pause* state. <br />
+ When the program starts running after 15 seconds, then you can observe that the player automatically starts. <br />
+ When you look away from the screen for 1 sec period, then it will be paused and when you return to it, it will play automatically. 

##  Testing

I have tested this code on Ubuntu 18.04 abd it is working properly. <br />
The code has been written for VLC media player where **space** is the button for both play and pause. 

## Reference

The code for face detection is taking from the following repository: https://github.com/shantnu/Webcam-Face-Detect
I thank him for the code. 
