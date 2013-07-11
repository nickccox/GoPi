# GoPi

Attempting to provide GoPro like functionality, but using a Raspberry Pi some web cams and some Python scripts.

## Version 2:

Items I'm looking to add:
 - [] Add hardware _button_ to start/stop recording
 - [] Modify main capture loop to continue from last image written to storage path 

## Version 1:
Proof of concept. Almost everything is hardcoded. I know nothing about Python. What could go wrong!

### Library requirements:

* SimpleCV - Image processing libraries that enable simple image capture from a camera
* FFmpeg - Used in this version as a command line tool to build videos from the captured jpg frames. SimpleCV VideoStream is a possible alternative however I faced issues with performance, codecs etc.

### Hardware:
* Raspberry Pi
* USB webcam

### Executing the code:

    python GoPi.py
