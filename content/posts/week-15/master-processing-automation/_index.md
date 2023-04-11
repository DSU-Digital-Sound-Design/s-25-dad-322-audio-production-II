---
title: "Finishing a mix"
---

## Master Bus Processing

We can add effects to the master track to tie all the tracks together. For example, it's common to add bus effects early in the mixing process and change your per track effects as the mix goes on.

> Download Mike Senior's [final mix](https://multitracks.cambridge-mt.com/SwingingSteaks_LostMyWay_MSFTSSWorkflowDemo.zip) so that we have a mixed project to test out master processing on.

We can start with Reaper plugins, then look at some freeware options and see if they're better. First, add ReaEQ to the master track. Next, using a low shelf, then a high shelf, check if the mix could use any more low end or high end.

Next, add a compressor to glue the mix together and make it more dynamic. A freeware option for this that comes with Reaper is the `1175 Compressor`, a recreation of the famous [1176 Peak Limiter](https://en.wikipedia.org/wiki/1176_Peak_Limiter). Keep the ratio at 4. Start bringing down the threshold until you're getting some gain reduction. Add back in some of that reduction with the Gain parameter. Finally, pick a setting that makes the track seem louder and more dynamic. Be careful not to add any unnatural pumping sound.

Right-click on the track and select `Bypass Chain` to hear what it sounds like without your master processing. Doing this can show you if you're doing something positive to the mix.

Next, let's add a multi-band compressor. In Reaper, that's `ReaXComp.` Start with the low end and `Solo current band` so that you only hear that band. Then, adjust that band to compress the sub-bass frequency range, around 160 Hz. Next, change the following three bands to pass the correct parts of the frequency spectrum for this mix. Set the ratio of each compressor to 4:1, a good starting point. Also, turn on `Program dependent release` for each band.

Finally, link each threshold together, so they all move simultaneously. For example, touch the threshold of the second band, go to Param -> Parameter Modulation / MIDI Link -> Link from MIDI or fx parameter, then select the threshold of the first band. Go through and link each other band to the first band. Finally, adjust the threshold to get a slight gain reduction across the bands.

Your master is probably clipping now. To fix this, we'll add a mastering limiter, `ReaLimit.` This will turn down only the peaks, so we don't clip. Then, finally, change the `Brickwall ceiling` to adjust the final mix level. Here a lower threshold will make the mix sound louder, raising the level of the quieter parts to match the louder parts.

We can check the overall perceived loudness of the mix with a loudness meter. Add the `Loudness Meter Peak/RMS/LUFS` JS plugin to the master track. A good target LUFS-I value is -10 LUFS. Click on the meters to make them reset after you've changed other parameters.

> Save this chain of effects as a preset. Next, Right-click, then go to `FX Chains -> Save all FX as chain...`
> We will recreate this FX chain with third-party plugins and compare the results.

Freeware plugin options:

- EQ
  <!-- - bx_console Focusrite SC - is included in the bundle. -->
  - [TDR SlickEQ](https://www.tokyodawn.net/tdr-vos-slickeq/)
  - [TDR Nova](https://www.tokyodawn.net/tdr-nova/)
- Compressor
  - Shadow Hills Mastering Compressor - is included in the bundle.
  - [TDR Kotelnikov (Tokyo Dawn Labs)](https://www.tokyodawn.net/tdr-kotelnikov/) - you may have this from the compressors lesson.
  - [TDR Molotok](https://www.tokyodawn.net/tdr-molotok/) - color compressor
- Multi-band Compressor
  - [OTT](https://xferrecords.com/freeware) - a bit aggressive, very good for electronic music. Just use ReaXComp for acoustic music.
- Limiters
  - [W1 Limiter](http://www.yohng.com/software/w1limit.html) - a clone of, famous, Waves L1.
  - [Limited Z](https://lvcaudio.com/plugins/limited-z/) - many more features.
  - [Frontier](https://d16.pl/frontier)
- Loudness Meter
  - [Youlean Loudness Meter 2](https://youlean.co/youlean-loudness-meter/)
- All in one - these plugins do a bit of all of the above.
  - [PA FREE bx_masterdesk Classic - Plugin Alliance](https://www.plugin-alliance.com/en/products/bx_masterdesk_classic.html)

> Now try to recreate our FX chain but with 3rd party plugins. See your settings from the Reaper plugins and figure out how to get the same effect with the 3rd party plugins. Save each of your chains as a FX chain in Reaper.

## AB

To compare these plugins, we need to AB them. If we want to compare plugins on the same track, they can be toggled on or off using the key command `command + b.`

A straightforward way to do this is to use the SWS Extensions Snapshots feature. You can download these extensions [here](https://www.sws-extension.org/). The snapshots feature allows you to save and load your current track state snapshot. We can save one version with the original plugins and another version with the third-party plugins. We can easily switch between them by clicking `next` or `previous.`

## Reference Mix

Finally we need to set up a reference mix to check this against other popular songs. We can add a song, then take it out of the master parent send, so that it's not getting our master fx added to it. Then we send it directly to our speakers, outputs 1-2.
