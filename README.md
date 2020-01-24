# TriNetra, the EyE
A security spy cam built on raspberry pi

## Agenda
 - Plan is to build a security solution on the lines of [motioneyeos](https://github.com/ccrisan/motioneyeos), but as a  utility and not as a complete OS - reason being I would like to continue using RaspberryPI for my other uses.
 
## Features
 - Ability to identify motion using software without hardware sensors.
 - Ability to capture and save the video till motion has stopped.
 - Should also include the frame before motion has been observed into the video. (e.g.: You should be seeing an intruder coming in and not when he has already come in - as part of the recorded video.)
 - Should identify objects in the video - these could be faces, cats and other prebuilt items.
 - Stretch target - Ability to identify if the individual is an intruder or an insider (this would be needing loading of friendly images)
 - Broadcast the video as a telegram message or persue other IFTTT features.
 
## Learnings
 - openCV
 - python
 - playing with hardware
 - Image processing and Machine Learning. yay!

### Useful links
- https://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/
