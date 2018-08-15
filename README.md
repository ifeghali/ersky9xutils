# Ersky9x Utils for Mac OS X

Ersky9X is an open source radio firmware avaivalable [here](http://www.er9x.com).

This repository holds general utilities intended to be run in a Mac OS X environment to perform specific tasks for the above firmware.

The first utility available here is vagen, a voice alert generator.

# Configuration

Write to your ~/.vagen

```sh
VOICE=Luciana # Mac OS X voice
WPM=200       # Words per minute
OUTPATH=      # Output path for generated wav file 
```

# Usage

Make a model name for a Learjet and save it in the output path configured in ~/.vagen:
```sh
vagen learjet
```

Make a flaps up alert and save in a custom location:
```sh
vagen "flaps up" /Volumes/9XR/voice/user/flapsup.wav
```
