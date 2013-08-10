GyroScratch
===========

GyroScratch is an open source application that uses [x-OSC](http://www.x-io.co.uk/x-osc/) attached to a 7" record to play and scratch audio files. It also shows how to interface to [x-OSC](http://www.x-io.co.uk/x-osc/) using [Max/MSP](http://cycling74.com/products/max/).

The patch controls the playback rate of an audio file using an [IMU 6DOF Razor](https://www.sparkfun.com/products/retired/9431) from [sparkfun](https://www.sparkfun.com). The high-pass filters on the gyroscope outputs were bypassed to prevent the output from returning to zero for continuous rotations.

The the current audio level is indicated on a [VU meter](http://en.wikipedia.org/wiki/VU_meter) made from 16 [1206 surface-mount yellow LEDs](http://uk.rs-online.com/web/p/visible-leds/4975122/).

The gyroscope, x-OSC and battery are secured to the record with [sugru](https://sugru.com/). Demo video available on [YouTube](), see [original post]() for more info.

=========

**x-OSC settings**

* analogue sample rate: 100 Hz
* input 1 to analogue
* outputs 1 - 16 to digital.

**Wiring**

<img src="https://raw.github.com/xioTechnologies/GyroScratch/master/Wiring%20Diagram.png" alt="GyroScratch Wiring" style="width: 600px;"/>

**Instructions** 

1.  open GyroScratch.maxpat in Max/MSP
2.  activate audio by pressing the loudspeaker button
3.  when the record is stationary click the 0 RPM button
4.  set the record playing and click 33 RMP
5.  behold, you are Grandmaster Flash

The scratch.wav file is edited from [Killa Tactics](http://www.killatactics.com/) [Belt Drive Breaks](http://tablist.net/album/killa-tactics-belt-drive-breaks-free). The application is inspired by [Nicholas J. Bryan's](https://ccrma.stanford.edu/~njb/) [MOPHODJ](http://www.youtube.com/watch?v=PAHhJQQw7dI)

<!---
The demo video shows GyroScratch being used to play and scratch some beats with LEDs indicating the current audio level. Additionally the play position is controlled membrane potentiometer and a second x-OSC connects with a button to control the audio level. You can also play frisbee with it. 

All audio samples in this video are edited from Killa Tactics Belt Drive Breaks. Inspired by Nicholas J. Bryan's MOPHODJ -->
