# GoProStream

Tools for handling/displaying GoPro HTTP/UDP stream. Available in Python.

### Dependencies:

Python:

* FFMPEG
* urllib

Linux(Added by BratCat):

* sudo apt install linuxbrew-wrapper 
(Install brew for Linux and add the classpaths to your .bashrc)
* brew install ffmpeg

## Screenshots:

![](http://i.imgur.com/5wlh8yS.png) 


## Compatible with:

- HERO3 
- HERO3+
- HERO4
- HERO Session
- HERO+ (incl. LCD)
- HERO5 

## Flags:

    VERBOSE=False

Verbose flag for FFmpeg

    RECORD=False

Sends a record command to the camera, camera must be in video mode!

    STREAM=False

Creates a local stream via FFMPEG with minimized lag for use in OBS, camera must be in video mode!

    SAVE=False

Save the gopro live feed to your machine

    SAVE_FILENAME="goprofeed2"

The filename of the saved video feed

    SAVE_FORMAT="mp4"

File format for saved video feed

    SAVE_LOCATION="/home/konrad/Videos/"

Location for saved video feed (needs to be changed to your username and directory)

### Further instructions:


https://medium.com/@konrad_it/how-to-stream-from-a-gopro-camera-f4a164150797


### Extra Links to refer to:
https://www.youtube.com/watch?v=zjDX7o-TseM

https://www.reddit.com/r/gopro/comments/2md8hm/how_to_livestream_from_a_gopro_hero4/

https://github.com/KonradIT/GoProStream

https://www.kaggle.com/veeralakrishna/200-bird-species-with-11788-images/data

### Credit


- @SonOf8Bits --> He is the original contributor for the GoPro streaming python script. 
