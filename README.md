# mp3edit

Commands to work with ffmpeg and Audio files:

1. Cut first n hh:mm:ss.sss (Hour, Mins Seconds) from an audio/video file
ffmpeg -i copyMMU.mp3 -ss 00:00:28.500 -acodec copy newcopyMMU.mp3 -loglevel fatal
