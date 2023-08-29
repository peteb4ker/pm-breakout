# Overview

An expander module for the WMD performance mixer that outputs channels 1-10 and main pre-fader outs on a separate 6hp breakout module.

Module output jacks:

- Mono channels 1-6
- Stereo channels 7-8
- PM Channels 9-10 (Optional - disconnected if PM channels is not present)
- Stereo out (effectively active multing the stereo outs on the Performance Mixer)

This module is a community-created, creative commons licensed module that is not designed, affiliated or endorsed by WMD.

This module was designed by Pete Baker in Oakland, California.  Thanks to WMD and the Modwiggler community for tips that led to the design of this module.

## **Use cases**

Connect pre-fader outs from any PM channel to other modules, 

- e.g. a sound card such as ES-9 to record mixed channels
- bus channels for bus FX
- +other creative uses

### Output phase

Channels 1-8 have inverted phase.  This is a constraing of the underlying 
WMD Performance mixer hardware, and cannot be readily fixed in hardware without making the design 
much more complex.  

The intention is that the phase of these channels is inverted by an effect on a downstream 
soundcard, or in software.

Channels 9-10 and Main outs (L&R) do not have inverted phase.

## **Technical specifications**

### Outputs

- Mono channels 1-6
- Stereo channels 7-10 (9 and 10 require PM channels)
- Main stereo out

### **Output impedance**

- 510R - all channels

### Inputs

- None

### Controls

- None

### Power consumption

- None - module is passive

### Dimensions

- 6HP
- TBDmm deep

### Rear connectors

- 20-pin PM pre-outs connector (mono 1-6, stereo 7-8)
- 10-pin PM channels pre-outs connector (stereo 9-10)
- 6-pin main connector (main L & R)
