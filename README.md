# Trim+

A trim plugin with optional input saturation for Reaper/JSFX.

## Features

At its core this is a volume trim plugin. If you only use the output trim control, it will raise or lower the volume of your channel, with no other processing.

If you'd like to add something extra to the signal, the Input Gain control will push the input into a saturation stage adapted from Reaper's Saturation plugin (but less subtle). When Input Gain is used, the signal will be boosted, fed into a saturation algorithm, and then corrected with an auto-gain function to keep the overall level (nearly) the same.

The character control allows you to select between Gentle and Push modes. Push introduces more saturation.


## Installation

1. [Download a zip file of this repository](https://github.com/scottnelle/gainstepper/archive/refs/heads/master.zip) and unzip it.

2. Find the Reaper Resources directory. Under the Options menu click "Show REAPER’s resource path in explorer/finder…" to have Reaper find this folder for you.

3. Open the Effects directory within the Reaper Resources directory and copy the `Trim+` file to that directory (or a subdirectory within.)

4. In Reaper, scan for new plugins.

[A video demonstration of how to install JS FX plugins can be seen at the Reaper Blog](https://reaperblog.net/2015/06/quick-tip-how-to-install-js-plugins/).
