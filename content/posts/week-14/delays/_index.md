---
title: "Mixing with delays"
---

## Track Manger

The track manager in Reaper can make working with large projects much more manageable. So let's set it up and use it for this project.

## Delays in Reaper

Delays are a very close cousin to reverb. Where reverb is many repeats of a sound happening very close together, delay has repeats that are happening more spaced apart.

Open the Reaper starter project [here](https://dakotastateuniversity-my.sharepoint.com/:f:/g/personal/tate_carson_dsu_edu/Eu21oE1GkClLoqCG_joBRawB_Z6nDF-dYYNT-rOoMzAStg?e=epotLO). Then, add a `ReaDelay` plugin to the `Flute` track. The delay time is set using the `Length (musical)` parameter by default. Find that parameter and adjust it to taste, preferably a whole number. You might hear that the delays are not in time. To fix this, set the correct project tempo.

Next, increase the `Feedback` parameter to hear the delays repeated for longer. Finally, adjust the filter section to add color to the delayed repeats.

Let's create a stereo multi-tap delay. Pan your first delay tap to the left. Then create another tap and pan that to the right. You can create complex rhythms by adjusting the delay times of the taps.

We can also set the delay time in milliseconds instead of the tempo. For example, setting the delay time at about 100 ms will create a slapback echo delay.

> Do your own delay experiments on the spoken word vocal. Try to create something interesting with multiple delay taps. Try experimenting with more ReaDelays in series to get more complex effects.

## Dynamic delay

This technique is very similar to the dynamic reverb technique we learned a few weeks ago. The delay will come in and out based on the dynamics of the signal.

Create a delay send track and send your vocal track to it. Then, add a `ReaDelay` plugin to the `Delay` track. Turn off the dry sound because it's coming from the vocal track.

Set the musical length to 2, increase the feedback, and filter the repeats to make them thinner.

Try to automate the delay using the same method we learned in the dynamic reverb lesson.

Now, try the same technique but use a compressor after the delay effect. Drag the routing icon of the vocal track onto the compressor to connect track channels 1/2 to auxiliary channels 3/4. Then set the detector input to `Auxillary inputs.` Next, turn the attack and release to 0 and the ratio to inf. Now, set the threshold so only the delayed signal is heard when the vocals are paused. Finally, adjust the release time for a more subtle effect.

> Create your own dynamic delay on a synth track with spaces in it. Then, program the delay only to turn on when the synth is paused. You can use whatever synth you want; if you don't have one, try [Vital Synth](https://vital.audio/).

## Automated delay

We can do a similar technique to dynamic delay but only have the delay turn on for specific notes or syllables, giving us more control. We'll do this by automating the delay mute. Then, set up a delay send track the same as before, and send your vocal track to it.

Open the envelopes window of the vocal track and find the send envelopes section, then select the delay send mute. Set the envelope so that the mute is only off for the word "then". Pay special attention to the rhythm of both times the delay is heard. Try to match them.

> An alternative way of creating a delay throw is to automate the delay volume instead. Now that you can do it with muting try to create the same effect by automating the delay volume. This method gives you much more control over how the delay sounds. We'll get into automation more deeply in the next lesson.

## Coloristic and more extreme delays

If we have extra time, let's check out these delay effects.

- [Chow Matrix](https://chowdsp.com/products.html)
- [Valhalla Freq Echo](https://valhalladsp.com/shop/delay/valhalla-freq-echo/)
- [Full Bucket Brigade Delay](https://www.fullbucket.de/music/fbdelay.html)
