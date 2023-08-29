---
layout: default
title: Pre-outs Eurorack Expander for the WMD performance mixer
---

# Overview

An expander module for the WMD performance mixer that outputs channels 1-10 and main pre-fader outs on a separate 6hp breakout module.

## Module output jacks:

- Mono channels 1-6
- Stereo channels 7-8
- PM Channels 9-10 (Optional - disconnected if PM channels is not present)
- Stereo out (effectively active multing the stereo outs on the Performance Mixer)

## Contents

  * [Use cases](#use-cases)
  * [A note on output phase](#output-phase)
  * [Installation](installation.md)
  * [Technical specifications](specs.md)
  * [License](#license)

## Use cases

Connect pre-fader outs from any PM channel to other modules,

- e.g. a sound card such as ES-8, ES-9 or external USB mixer to record mixed channels
- bus channels for bus FX
- +other creative uses

## A note on output phase

Channels 1-8 have inverted phase.  This is a constraint of the underlying
WMD Performance mixer hardware, and cannot be readily fixed in hardware without making the design
much more complex.

The intention is that the phase of these channels should be inverted either in software
or by an effect such as the "invert phase" filter available on the Expert Sleepers ES-9.

Channels 9-10 and Main outs (L&R) do not have inverted phase.

## Hardware

Hardware designs are available for [EasyEDA](https://easyeda.com/) on [Open Source Hardware Lab](https://oshwlab.com/peteb4ker/pm-es9-breakout).

## License

This work is licensed under a Creative Commons Attribution 4.0 International License.

This module is a community-created module that is not designed, affiliated or endorsed by WMD.

This module was designed by Pete Baker in Oakland, California.  Thanks to [WMDevices](https://wmdevices.com/) and the [Modwiggler community](https://www.modwiggler.com/forum/viewtopic.php?t=274484) for tips that led to the design of this module.