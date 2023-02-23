---
title: "Equalizing for a Reason"
---

{{< toc >}}

# Frequency masking and balance

The primary function of equalization is to make the sound more balanced, not to improve or change the timbre of a sound. Masking naturally takes place when instruments are played together that share frequency ranges. EQ is used to make these parts fit together like a jigsaw puzzle.

Because of this a track might sound terrible soloed, but great in the context of the mix. This is to be expected. Soloing can be useful when first applying EQ, so that you can hear exactly what you're changing more easily, but the track always needs to be compared to the rest of the mix.

Listening in mono will help you make these decisions because the stereo field can lessen the effects of masking. Also, because EQ settings will be specific to your mix, it is not possible to use presets from the EQ to balance your mix.

Let's listen to [some examples](https://cambridge-mt.com/ms/ch11/) from the book to hear what we're talking about.

> Spend some time listening to the tracks with EQ and no EQ. Try to hear the instruments that change tone from one to the other.

Just as we did when we first starting building the balance, we'll start EQing the most important parts of the mix, carving space out of each subsequent instrument so we can still hear the important ones.

# Basic EQ tools and techniques

We'll rebuild the balance again, but keeping these questions in mind:

> - Can I find a fader level for the new track that allows me to hear all of its frequency regions as clearly as I want to?
> - Is the new instrument leaving the perceived frequency balance of the more important tracks essentially unscathed?

If the answer to these questions is yes, then we don't need EQ. The highpass filtering we added before is enough.

## Reaper EQ tricks

A few scripts can help you hear what you're taking out by soloing the band so that you only hear that band. In ReaPack if you install "ReaEQ tools" and "Various function" you'll get some scripts from mpl. That will give you these two scripts:

- mpl_Solo last touched ReaEQ band
  - turns off all other bands so you can hear just the one bands effect on the track
- mpl_Solo last touched ReaEQ band (alter)
  - solos all other bands and inverts the band you touched, so you hear what the EQ is removing from the track

## Shelving filter basics

The default setting is to have a low shelf, high shelf and two bandpass filters in between. We'll start with the shelving filter. These can change the level of a whole part of the frequency spectrum. You can either have a low or high shelf. Reaper's ReaEQ gives you control over the frequency, gain and bandwidth of the shelf. The mousewheel will set the bandwidth of each band. Also, doubleclick on the number to disable the band temporarily.

First choose weather the track needs a high or low shelf. Then move around the gain control to let your ears get used to what effect it's having. Keep bringing the fader up and the shelf down until you feel like the balance between the tracks is good.

I'll start with balancing the drums. Then go on and try to get the bass to not overpower kick.

## Adding in Peaking Filters

If we hear specific frequencies of the sound clash with our other sounds w can use peaking filters to cut out those frequencies.

## EQing live drums

We can also try to EQ Hurray For The Riff Raff since it has a more complex sound with all live recorded instruments.
