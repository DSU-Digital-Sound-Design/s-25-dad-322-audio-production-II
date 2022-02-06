---
title: "Introduction to Compression"
---

Why do we use compression?

We want to try to reduce the dynamic range for certain instruments. The dynamic range is the difference between the loudest and quietest sounds. The louder parts will get quieter and the quieter parts will get louder.

If tracks have too much dynamic range they can stick out of a mix in an unpleasant way. If a track has too little dynamic range overall it can sound boring and lifeless.

- Basic parameters - threshold, makeup gain
- different types of compressors
- start to bring in tracks one by one from our mix, adding compression where necessary. We'll look for tracks that we can't find stable fader settings for because they vary too much in volume. Do certain sections poke out too much or get lost because their too quiet?

First let's look at [some compression examples](https://cambridge-mt.com/ms/ch9/) from the book.

## Compression in Broken man

Steps:

1. Before I start, I'm going to offset all of the fader values to the clip gain so that my faders are all at 0 dB. I'm using a script called "X-Raym_Offset selected items volume by their track fader value", which you can get from ReaPack. See [this video](https://youtu.be/gVbMbqGSB7E?t=369) for a description of how to install extensions for Reaper.
2. Pick a compressor, i'll use ReaComp or MCompressor.
3. Set the threshold and makeup gain
4. Listen for how the track sounds in the mix. Does it sound better or worse? In context of the song, we'll try to back off of the compression to see if we can use less.
5. Do we need to change the level of any of the media items before they get to the compressor for more consistent inputs?

## Class Lab

Let's get some hands on experimenting with balance and compression in your own mixes

- Install a few types of compressors and experiment with them
- [MCompressor](https://www.meldaproduction.com/MCompressor), [RoughRider 3](https://www.audiodamage.com/pages/free-downloads), [TDR Kotelnikov](https://www.tokyodawn.net/tdr-kotelnikov/)

Instructions:

Open the drum editing project we did a few weeks ago. Add ReaComp to the kick drum track. Turn on auto-makeup gain. Set the ratio to 4:1. For every dB that the signal goes above the threshold it's reduced by this ratio. It is 4thing the dB increase. So a 4 dB increase becomes just a 1 dB increase.

The attack setting determine how long the compressor takes to respond to a change in volume. The release setting determines how long the compressor takes to recover from a change in volume.

Now do the same to the other kicks and snares, then the hi-hats.

As you add plugins, check the "Project Media Bay/FX" view to bypass all compressors at once. Use this to hear the cumulative difference.

Now compress your room microphones, but this time with the 1175 Compressor that comes with Reaper. Set the ratio to 4. Adjust the threshold to your liking. with this plugin you have to adjust teh gain manually. Try to get it back to the input level.

Finally, group all of the drums in a folder and apply a 1175 compressor to the folder. Notice how extreme parameter settings can have a drastic effect on the timbre of the track.

Try this whole process again with at least one other compressor. AB the results and decide which one you prefer.

## Voice Compression

Now add the vocal sample to the project and try to compress it.
