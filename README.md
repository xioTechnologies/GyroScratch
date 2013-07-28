GyroScratch
===========

GyroScratch is an open source application that uses [x-OSC](http://www.x-io.co.uk/x-osc/) to play and scratch audio files on a computer using a real record. It also acts as a neat example application demonstrating how to interface to [x-OSC](http://www.x-io.co.uk/x-osc/) using the standard [Max/MSP](http://cycling74.com/products/max/) objects. 

The patch controls the playback rate of an audio file using an [IMU 6DOF Razor](https://www.sparkfun.com/products/retired/9431) from [sparkfun](https://www.sparkfun.com). The high-pass filters on the gyroscope outputs were bypassed to prevent the output from returning to zero for continuous rotations.

The the current audio level is indicated on a [VU meter](http://en.wikipedia.org/wiki/VU_meter) made from 16 [1206 surface-mount yellow LEDs](http://uk.rs-online.com/web/p/visible-leds/4975122/). 

To run the application: 

1.  open GyroScratch.maxpat in Max/MSP
2.  activate audio by pressing the loudspeaker button
3.  when the record is stationary click the 0RPM button
4.  set the record playing and click 33RMP
5.  behold, you are Grandmaster Flash

The scratch.wav file is edited from [Killa Tactics](http://www.killatactics.com/) [Belt Drive Breaks](http://tablist.net/album/killa-tactics-belt-drive-breaks-free). The application is inspired by [Nicholas J. Bryan's](https://ccrma.stanford.edu/~njb/) [MOPHODJ](http://www.youtube.com/watch?v=PAHhJQQw7dI)

<!---
The demo video shows GyroScratch being used to play and scratch some beats with LEDs indicating the current audio level. Additionally the play position is controlled membrane potentiometer and a second x-OSC connects with a button to control the audio level. You can also play frisbee with it. 

All audio samples in this video are edited from Killa Tactics Belt Drive Breaks. Inspired by Nicholas J. Bryan's MOPHODJ -->
