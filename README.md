# Volume Control with Vision of Hand Tracking using OpenCV and MediaPipe
Work on `Ubuntu 20.04`, requirements:

1. Ubuntu package
 
 ```
 sudo apt install libopencv-core-dev libasound2-dev alsa-base
 ```
 
2. Pip package
- `opencv 4.5.3.56`
- `mediapipe 0.8.7.1`
- `pyalsaaudio 0.9.0`
 
## Testing
- Testing module using `testing-htm-module.py` from `HandTrackingModule.py`
- Testing audio of alsa if its work after installation using `testing-audio.py`, over-amplification not included. You can refer to this site [PyAlsaAudio](https://github.com/larsimmisch/pyalsaaudio)
