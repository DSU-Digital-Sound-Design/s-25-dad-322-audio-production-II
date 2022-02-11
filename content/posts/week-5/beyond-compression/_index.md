---
title: "Beyond Compression"
---

{{<toc>}}

# Expansion and Gating

We can use gating to do the opposite of compression. We can turn down the quiet sounds that we might not want in our recording. I'll look at the Hurray For the Riff Raff recording and use Gating and dynamic split to clean up the recording.

> Useful Reaper hint:
>
> - Marquee zoom: cmd + option + right drag. Zooms in on the selected area.

We can look at the tom track. It is mostly spill from the other mics. Because there is more noise than not we can use dynamic split to clean up the tom track. This is similar to gating, but actually removes the items from the track.

Next we can look for other tracks that have more musical information that we want to keep. Gating is a good candidate to fix this. If we listen to the kick track, we can hear that the snare leaks into the kick mic. We can use ReaGate to fix this.

If you're compressing or equalizing a track be sure to add the gate before these plugins. As we raise the threshold we'll start to cut out more and more sound from the track. We want to try to get as much gain reduction from the noise as possible, without effecting the level of our target sound.

We want to try to use a fast attack so that we're not messing with our signals transient. But, if it's too fast we may hear a click on some hits inserted. If we're effecting the transient to negatively we can set a lookahead with the pre-open setting.

Try and set the release as long as possible without hearing the sound you're trying to remove. Hysteresis controls the level of the gate. It's default is at 0 dB, which can sound unnatural. Try setting this lower, without introducing the unwanted noise.

We can invert the gate to only hear what is being filtered out. This is a good way of telling if you've done too much with the gate.

Also, turn the gate off and listen to the timbre of the sound. Make sure you are not effecting the timbre negatively.

If we need to we can use the filter section to limit what the gate is hearing. We can click the "preview filter output" check box to hear what we're filtering out.

# Transient Enhancement

Transient design allows us to control the transient and sustain of our sounds independently. In Reaper we can use the "Transient Control" plugin to control transients in our tracks.

We can start with our kick to try to make it more attacking. If you want more attack, you can turn up the attack percentage, or lower it if there is too much transient.

You can also try transient design with parallel processing. One track can have a very short attack and a long sustain, then you can mix that in with another track with a longer attack and a short sustain.

We can try this parallel trick on our snare track as well.

Then let's try it on the room mics. You may want this mic to get more sustain.

Maybe this will help our electronic drum track? What other tracks from the Broken Man mix did we loose transients on when compressing?

After we add our gating and transient processing where necessary let's rebuild the balance to see if things feel more stable.
