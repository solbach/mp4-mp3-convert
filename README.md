# mp4 to mp3 converter

This little script converts .mp4 files to .mp3 audio files. 

## usage
    $ tomp3 <input-file>
or
    
    $ tomp3 <input-file> <bitrate>

## requires
* ffmpeg
* bash

## tested on
* Ubuntu 14.04
* ffmpeg 2.4.3
* bash 4.3.11

## install ffmpeg on Ubuntu 14.04

``` 
$ sudo add-apt-repository ppa:kirillshkrogalev/ffmpeg-next
$ sudo apt-get update
$ sudo apt-get install ffmpeg
```
