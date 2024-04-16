---
title: "Finishing a mix"
---

Mike senior listening examples: [Chapter 19: Master-buss Processing, Automation, & Endgame](https://cambridge-mt.com/ms/ch19/)

## Master-Buss Processing - General Concepts

It's common to add processing on our master bus to create a more combined sound. This can be a challenging process to take care not to undo your decisions in the mixing process.

### Compression

Compression is one of the most common processors on the master.

Below are some uses for master-buss compression:

- It introduces some level of interaction between different parts in your mix by ducking quiet signals slightly in response to louder ones, and in doing so it gives a feeling that the mix coheres better. It’s common to hear recording engineers talk of master-buss compression “gluing the mix together” on account of this.
- It can create pumping effects that add a subjective sense of loudness and aggression, which suits certain music genres, especially rock music.
- By boosting lower-level signals, it draws more attention to internal mix details and generally makes the music seem more emotionally engaging.
- If a characterful compressor is used, then it may subjectively enhance some
  aspects of the mix—for example, by adding subtle distortion artifacts at certain frequencies.
- Some engineers feel that it reduces the negative side effects of down-the-line
  mastering or transmission compression. Here’s Andy Wallace, for example “A long time ago, I learned that [radio compression] was seriously changing how the low end sounded and the balance . . . That’s when I really started experimenting with a substantial amount of stereo compression. And I found that if I had something compressed ahead of time and was happy with the sound of it, the additional compression from the radio station had less effect.”
- It evens out the dynamics of the entire mix signal, increasing the production’s average levels so that it appears louder at a given metered peak level.

Concepts:

> Master-buss compression simply for the purposes of “mix glue” rarely uses more than about 2 to 3 dB of gain reduction at most. Where you want to keep transient smoothing and pumping artifacts to a minimum, you’ll likely want to rely on a **slow attack time and automatic release time**, whereas **faster release time settings will tend to draw out more of the mix details**. Ratios over 2:1 are unlikely to be useful in these cases, and you may discover that ratios as low as 1.1:1 may be more appropriate, depending on the musical style. If you’re looking for more **aggressive pumping compression**, however, then you might even see **8 dB of gain reduction on peaks, with faster attack/release times and higher ratios.** Lee DeCarlo also recommends one important refinement: “I’ll play with the release and the attack times until I can actually make that limiter pump in time with the music.”

Watch out for these common side effects of compression on the master:

- _Loss of attack on prominent transients, such as kick and snare drums._ Suggested remedies: reduce gain reduction; increase attack time; reduce the ratio; adjust knee softness; switch level-detection mode from peak to average (RMS); select a different compressor design.
- _Excessive gain pumping._ Suggested remedies: reduce gain reduction; adjust release time or switch to automatic mode; apply low-frequency EQ cut in the level-detection side-chain; select a different compressor design.
- _Unwanted distortion._ Suggested remedies: lengthen attack and release times; adjust knee softness; select a different compressor design.
- _Loss of weight on instruments with low-end transients, such as kick drums._ Suggested remedies: reduce gain reduction; lengthen attack time; apply low-frequency EQ cut in the level-detection side-chain; adjust knee softness; select a different compressor design.
- _Undesirable alterations in the subjective mix balance._ Suggested remedies: reduce gain reduction; lengthen attack and/or release times; adjust knee softness; select a different compressor design.
- _Unappealing tonal changes to the mix._ Suggested remedies: use a gain plugin to adjust the signal level feeding the compressor; select a different compressor design.

If you can't hear these side effects follow advice from Andy Wallace:

> “It’s not unusual for me to really make a compressor slam, to hit it pretty hard. I’ll often put it on an extreme setting, to get a sense of what the ballpark is, and then back it off to what sounds right to me.”

### Equalization

Use EQ on the master if you've gotten to the end of the process and decide that the overall tone of your mix needs a bit of tweaking. You should add this after any compression.

Spike Stent explains the rationale here:

> “Basically what I do with every mix is put a GML EQ across the stereo buss of the SSL, and just lift the top end, above 10K, so I won’t have to use as much high end from the SSL. The mid and high end of the SSL is a little harsh and cold. So I turn that down a bit, and then lift the high end with the Massenburg to make the mix sound warmer and add sheen.”

### Stereo Manipulation

- Multi-band MS processing
- Or other techniques we covered in the width lesson

### "Special Sauces"

Coloristic things to try:

- distortion techniques
- analog, tube, classic mix consoles or historical tape machines

### General Considerations for Master-buss Processing

- never try to finalize all your mix settings before getting your choice of master-buss processing involved
- Top-down vs. bottom up

> “Why would you wait till the end?" asks Jaycen Joshua. “You want to hear what it’s doing immediately. If you wait to the end, it’s going to change your mix completely.”

## Referencing and Loudness Processing

### Suggested Processing Strategies

- _Full-band “top-down” squeeze_. This is where you attempt to gently squeeze a large section of a signal’s dynamic range, using very low-ratio compression operating above a low threshold level, such that subtle compression is happening almost all the time. As long as gain reduction is kept within 3 dB or so, it’s usually possible to keep pumping artifacts relatively benign by adjusting attack/release times by ear. Potential side effects include undue emphasis of low-level details such as background sounds, reverb/delay effects, and incidental noises; unwanted overall level increases during sections with sparser arrangement; and reduction in transient definition.
- _Full-band “bottom-up” squeeze_. A similar approach as in the top-down squeeze, except that the dynamic range below the compressor’s threshold is targeted. There are specialist processors for this purpose (called upward compressors or de-expanders), but you can also achieve much the same effect using subtle full-band parallel compression. Potential side effects are akin to those of top-down squeeze—transient definition tends to suffer less, but you get less peak control and an increased likelihood of unwanted overall level increases during sparser arrangement sections.
- _Full-band limiting._ This is usually a much faster-acting gain reduction designed to stop signal peaks dead, while leaving the remainder of the dynamic range comparatively unscathed. In some types of music, an intelligently designed peak limiter can achieve a peak reduction of several decibels before audible problems start arising. Potential side effects include pumping, bass distortion, softening of transients, and reduction of apparent drum levels.
- _Multiband compression/limiting._ Using a multiband configuration for any of the three dynamics processes I’ve just described gives you additional scope for dynamic-range reduction before pumping artifacts impinge on your enjoyment of the music. However, pumping is only one of the potential side effects of compression-based loudness enhancement, and if you use multi-band processing to increase the amount of gain reduction, then you can easily end up with greater side effects in terms of mix-balance alteration and transient softening. Any multiband approach also adds further problems of its own: because the amount of gain-reduction in each frequency band will depend on the overall level of frequencies within it, changes in the spectral content of the mix (perhaps as a result of alterations in the instrumentation) can trigger unwanted changes in the overall mix tonality as the compression/limiting adjusts its gain-reduction—it can be almost as if some maniac were randomly tweaking an EQ over your whole mix in real time. There are also engineers who feel that multiband gain reduction drains the life out of a production by ironing out the tonal contrasts between its musical sections.
- _Subtle distortion_. By adding distortion harmonics to a mixed signal, you can increase its harmonic density and apparent loudness with very little increase in its peak signal levels. Subtle valve, tape, and transformer distortions are all options here, and if you need greater control over the exact nature of the harmonics additions, then parallel or frequency-selective configurations may be appropriate. Potential side effects include fatiguing tonal harshness, emphasized vocal sibilance, increase in the apparent level of treble percussion instruments in the balance, veiling of midrange details, and unwanted overall changes to the mix tonality.
- _Clipping._ Yes, clipping—whether it’s straight digital-style flat topping of the waveform peaks or some kind of modeled analog saturation that rounds them off more smoothly. You can find any number of textbooks that threaten hellfire and brimstone should you dare abuse your full mix in this way, but such admonitions are at odds with widespread commercial practice—examine the waveforms of the top 40 singles any week of the year and you’ll see clipping in abundance. The advantage of clipping as I see it is that it doesn’t seem to affect the subjective attack or balance of prominent drum parts as much as peak limiting, so it tends to suit styles with hard-hitting rhythm parts. Potential side effects include subjective tonal change of clipped peaks and unwanted distortion on more steady-state signal waveforms, although this may be disguised to some extent by distorted instruments, such as electric guitars, within the music itself. (For a particularly striking example of this tactic, check out the Imagine Dragons single “Radioactive.”)

## Referencing checklist

- _How does the overall mix tonality compare?_
- How does the balance compare?
- How does each instrument’s tone compare?
- How does the use of reverb and delay effects compare?
- How does the stereo image compare?

## Reaper Master Buss techniques

We can add effects to the master track to tie all the tracks together. For example, it's common to add bus effects early in the mixing process and change your per track effects as the mix goes on.

> Download Mike Senior's [final mix](https://multitracks.cambridge-mt.com/SwingingSteaks_LostMyWay_MSFTSSWorkflowDemo.zip) so that we have a mixed project to test out master processing on.

We can start with Reaper plugins, then look at some freeware options and see if they're better. First, add ReaEQ to the master track. Next, using a low shelf, then a high shelf, check if the mix could use any more low end or high end.

Next, add a compressor to glue the mix together and make it more dynamic. A freeware option for this that comes with Reaper is the `1175 Compressor`, a recreation of the famous [1176 Peak Limiter](https://en.wikipedia.org/wiki/1176_Peak_Limiter). Keep the ratio at 4. Start bringing down the threshold until you're getting some gain reduction. Add back in some of that reduction with the Gain parameter. Finally, pick a setting that makes the track seem louder and more dynamic. Be careful not to add any unnatural pumping sound.

Right-click on the track and select `Bypass Chain` to hear what it sounds like without your master processing. Doing this can show you if you're doing something positive to the mix.

Next, let's add a multi-band compressor. In Reaper, that's `ReaXComp.` Start with the low-end and `Solo current band` so that you only hear that band. Then, adjust that band to compress the sub-bass frequency range, around 160 Hz. Next, change the following three bands to pass the correct parts of the frequency spectrum for this mix. Set the ratio of each compressor to 4:1, a good starting point. Also, turn on `Program dependent release` for each band.

Finally, link each threshold together, so they all move simultaneously. For example, touch the threshold of the second band, go to Param -> Parameter Modulation / MIDI Link -> Link from MIDI or fx parameter, then select the threshold of the first band. Go through and link each other band to the first band. Finally, adjust the threshold to get a slight gain reduction across the bands.

Your master is probably clipping now. To fix this, we'll add a mastering limiter. `ReaLimit.` This will turn down only the peaks, so we don't clip. Then, finally, change the `Brickwall ceiling` to adjust the final mix level. Here a lower threshold will make the mix sound louder, raising the level of the quieter parts to match the louder parts.

We can check the overall perceived loudness of the mix with a loudness meter. Add the `Loudness Meter Peak/RMS/LUFS` JS plugin to the master track. A good target LUFS-I value is -10 LUFS. Click on the meters to make them reset after you've changed other parameters.

> Save this chain of effects as a preset. Next, Right-click, then go to `FX Chains -> Save all FX as chain...`
> We will recreate this FX chain with third-party plugins and compare the results.

Freeware plugin options:

- Compressor
  - Shadow Hills Mastering Compressor - is included in the bundle.
  - [TDR Kotelnikov (Tokyo Dawn Labs)](https://www.tokyodawn.net/tdr-kotelnikov/) - you may have this from the compressors lesson.
  - [TDR Molotok](https://www.tokyodawn.net/tdr-molotok/) - color compressor
- Multi-band Compressor
  - [OTT](https://xferrecords.com/freeware) - a bit aggressive, very good for electronic music. Just use ReaXComp for acoustic music.
- EQ
  <!-- - bx_console Focusrite SC - is included in the bundle. -->
  - [TDR SlickEQ](https://www.tokyodawn.net/tdr-vos-slickeq/)
  - [TDR Nova](https://www.tokyodawn.net/tdr-nova/)
- Imaging
  - [MONSTR | White Elephant Audio](https://whiteelephantaudio.com/plugins/monstr) - multiband stereo imaging
  - [Ozone Imager](https://www.izotope.com/en/products/ozone-imager.html)
- Special Sauce
  - [Klanghelm IVGI](https://www.audiopluginsforfree.com/klanghelm/)
  - [Wave Arts | Tube Saturator Vintage](https://wavearts.com/products/plugins/tube-saturator-vintage)
  - [GSatPlus | TBProAudio](https://www.tbproaudio.de/products/gsatplus)
  - [Vinyl](https://www.izotope.com/en/products/downloads/vinyl.html)
  - [Codec](https://www.audiopluginsforfree.com/codec/) - sounds amazing..very experimental
  - Others from the distortion section?
- Limiters
  - [Frontier](https://d16.pl/frontier)
  - [W1 Limiter](http://www.yohng.com/software/w1limit.html) - a clone of, famous, Waves L1.
  - [Limited Z](https://lvcaudio.com/plugins/limited-z/) - many more features.
- Loudness Meter
  - [Youlean Loudness Meter 2](https://youlean.co/youlean-loudness-meter/)
- All in one - these plugins do a bit of all of the above.
  - [bx_masterdesk Classic](https://www.plugin-alliance.com/en/products/bx_masterdesk_classic.html)

> Now try to recreate our FX chain but with 3rd party plugins. See your settings from the Reaper plugins and figure out how to get the same effect with the 3rd party plugins. Save each of your chains as a FX chain in Reaper.

## Automation for long-term mix dynamics

- Look at Mike Senior's finished mix for all of his automation rides.

## Mastering

### Why Do You Need Mastering?

### Choosing a Mastering Service

### Evaluating the Master

## AB

To compare these plugins, we need to AB them. If we want to compare plugins on the same track, they can be toggled on or off using the key command `command + b.`

A straightforward way to do this is to use the SWS Extensions Snapshots feature. You can download these extensions [here](https://www.sws-extension.org/). The snapshots feature allows you to save and load your current track state snapshot. We can save one version with the original plugins and another version with the third-party plugins. We can easily switch between them by clicking `next` or `previous.`

## Reference Mix

Finally, we need to set up a reference mix to check this against other popular songs. We can add a song, then take it out of the master parent send, so that it's not getting our master fx added to it. Then we send it directly to our speakers, outputs 1-2.
