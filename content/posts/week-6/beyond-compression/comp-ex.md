---
title: "Beyond Compression"
---

<!-- {{<toc>}} -->

<!-- TODO: mix back in some of the suggestions from before -->

### Gating

Gating is a technique used to reduce the volume of unwanted, quiet sounds in a recording, effectively the opposite of compression. This section outlines steps to clean up a recording by applying gating and dynamic split, with a special focus on a track by Hurray For the Riff Raff.

#### Key Steps and Tips:

- **Dynamic Split for Noise Reduction**: Utilize dynamic split to clean up tracks with significant noise or spill from other mics.
  - EX: Tom track 
- **ReaGate for Leakage Prevention**: Apply ReaGate on tracks where leakage from other instruments is an issue, like preventing snare sounds from bleeding into the kick mic track.
  - EX: Snare 
- **Plugin Order**: Place the gate before any compression or EQ plugins to ensure the noise is reduced before further processing.
- **Attack and Release Settings**: Opt for a fast attack to preserve the transient of the sound but adjust to avoid clicks. Set the release as long as possible without reintroducing unwanted noise.
- **Hysteresis and Filter Use**: Adjust hysteresis settings for a more natural sound and use filtering to limit the gate's focus, enhancing noise removal efficiency.

### Parallel Processed Gated Snare

This section explores the application of parallel processing with gating to emphasize drum transients, creating a sharper attack on drum hits by mixing a highly gated "blip" of each hit with the unprocessed track.

#### Technique Highlights:

- **High Threshold and Fast Attack/Release**: Isolate the initial transient of drum hits for a pronounced impact.
- **Parallel Mixing**: Blend the gated transients with the original, unprocessed sound for enhanced drum presence.

### Transient Enhancement

Transient enhancement allows for independent manipulation of the attack and sustain phases of sounds. Using Reaper's "Transient Control" plugin, this approach can make drum kicks more pronounced or smooth out harsh transients on other instruments.

#### Application Methods:

- **Adjusting Attack and Sustain**: Modify these parameters to increase or decrease the prominence of transients and the body of the sound.
- **Parallel Processing Strategy**: Employ parallel processing with varied transient and sustain settings to achieve a balanced and dynamic sound texture.
- **Room Mics and Other Instruments**: Apply transient design on room mics for added sustain or to smooth out specific sounds like the picking noise on acoustic guitars.


<!-- 
# Gating

We can use gating to do the opposite of compression. We can turn down the quiet sounds that we might not want in our recording. I'll look at the Hurray For the Riff Raff recording and use Gating and dynamic split to clean up the recording.

> Instead of Gating we can try to use an Expander, which is like a Gate but has a ratio control.

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

> Also try to gate the snare tracks.

## Parallel Processed Gated Snare

> Another useful application of this parallel expansion is emphasizing drum transients. Set the expander/gate with a high threshold and fast attack and release times to isolate just a tiny “blip” at the start of each hit, and then mix that back in with the unprocessed sound.

# Transient Enhancement

Transient design allows us to control the transient and sustain of our sounds independently. In Reaper we can use the "Transient Control" plugin to control transients in our tracks.

We can start with our kick to try to make it more attacking. If you want more attack, you can turn up the attack percentage, or lower it if there is too much transient.

You can also try transient design with parallel processing. One track can have a very short attack and a long sustain, then you can mix that in with another track with a longer attack and a short sustain.

We can try this parallel trick on our snare track as well.

Then let's try it on the room mics. You may want this mic to get more sustain.

> Can we use transient enhancement on our other mix? I tried smoothing out the picking noise on the solo acoustic guitars and that worked well.

After we add our gating and transient processing where necessary let's rebuild the balance to see if things feel more stable. -->
