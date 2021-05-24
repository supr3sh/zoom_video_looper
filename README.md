# Zoom video looper

It is a cool trick to loop a video of yourself in a zoom meeting by exploiting the virtual background feature provided by it.

## Requirements
Python3

## Setup
* First record a video of yourself which you want to play in the zoom meeting.
* Then go to [this](https://ezgif.com/video-to-jpg) website and convert this video to jpg. Upload the video and download jpg in zip.
* Now disable all the cameras of your laptop.
* Extract all the jpg images in a folder.
* Now open zoom and in settings select background settings.
* Click + icon and add all extracted jpg images one by one.
* Now clone this repository and go to zoom_video_looper directory.
```
git clone https://github.com/supr3sh/zoom_video_looper.git
cd zoom_video_looper
```
* Edit the python code and in place of i<11, write the total number of images uploaded.
* Join a zoom meeting and select join with video.
* In video settings select virtual background and select the first jpg image.
* Now run the python file in a terminal and within 5 seconds, select the first jpg image again.
* This will start exactly after 5 seconds that all of your uploaded images will start showing in the meeting. It seems like a video.
* This process will repeat itself until you stop the script it press Ctrl+C.
