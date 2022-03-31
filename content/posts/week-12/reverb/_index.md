---
title: "Mixing with Reverb"
---

Let's go back to our uses for reverb:

- Blend
- Size
- Tone
- Sustain
- Spread

In our example from a few weeks ago we used reverb to blend the drums together by sending different amounts of them into a reverb, making them sound like they were coming from the same room. But, there are these other uses of reverb that we'll look into today.

In order to find good settings and sounds for each of these uses, it takes a lot of trial and error. Because of that we'll install many different types of free reverb plugins and spend class trying them out on different musical elements. The Reaper reverbs are good starts, but it's always nice to have more options, especially with something like reverb.

Let's download and install the following reverb plugins:

- Basics:
  - [OrilRiver](https://www.kvraudio.com/product/orilriver-by-denis-tihanov)
  - [Sanford](https://www.lesliesanford.com/vst/plugins/) - PC Only
  - [Ambience](http://magnus.smartelectronix.com/#Ambience) - Won't load for me
- Creative plugins for tone and sustain
  - [PSP PianoVerb](https://www.pspaudioware.com/products/psp-pianoverb)
  - [Valhalla Supermassive](https://valhalladsp.com/shop/reverb/valhalla-supermassive/)
  - [KR-Reverb FS R1.5.0](https://www.kresearch.com/Products/Details/17)
    - The UI on this looks strange but it sounds really great. Notice the unique "listener position" setting. You can also set the size of the early reflections and tail separately.
  - [Dragonfly Reverb](https://michaelwillis.github.io/dragonfly-reverb/) - [Manual](https://michaelwillis.github.io/dragonfly-reverb/manuals.html)
  - [Riviera: Hyper-room reverb](https://nuspaceaudio.com/2017/02/07/riviera-fast-hybrid-reverb-plugin-for-modeling-high-dimensional-spaces/)
  - [TAL Reverb 2 + 3](https://tal-software.com/products/tal-reverb)
  - [TAL Reverb 4](https://tal-software.com/products/tal-reverb-4)
  - [Protoverb](https://u-he.com/products/protoverb/)
  - [Xhip Reverb](http://xhip.net/effects/?p=Reverb) - The GUI doesn't load for me
- Convolution
  - [MConvolutionEZ](https://www.meldaproduction.com/MConvolutionEZ)

Let's go to [Mike's page](https://cambridge-mt.com/ms/ch16/) for some advice on choosing reverbs and working with them.

## Size

Let's follow Mike's method for finding a reverb preset for blend/size that sounds good. He uses [this drum sound](https://audio.cambridge-mt.com/MSFTSS/Ch16/MS1601_Preset0Dry.wav) played through different reverbs to compare them. Create a new project and include this sample. Create a reverb bus and send the drum sample through it.

Find an instrument that could have a larger size in the mix. Use the suggestions from the book to find a good preset for the instrument.

> The biggest difference between reverbs designed for blend and size is that where the former is best provided by the earlier reverb reflections, the latter is best created by focusing the effect sound on the remainder of the reverb tail.

I'll try OrilRiver for this. If you could get Sanford or Ambience to work those are also good options. Let's check out the [manual](orilriver-manual.pdf). Lets explore the settings of this reverb.

Try turning off the reverb tail so that you can listen only to the early reflections variations. Adjust the room size parameter to hear the early reflections more. Then do the same with the reverb tail, turning the early reflections off.

Play with the room size parameter. This seems to effect mostly the early reflections.

Try to mimic the first 4 presets that Mike lists on [his site](https://cambridge-mt.com/ms/ch16/).

> - Beware of unnatural-sounding presets, as these will have trouble creating the sound of a larger space convincingly. CPU-light plug-ins will typically sound less natural than more computationally hungry algorithms.
> - Feel free to ignore the preset names with impunity—the main goal is to try to imagine the space implied by each preset and decide whether it’s the right kind of space for your mix to exist within.
> - Don’t be too concerned about tonal imbalances as long as there aren’t nasty metallic resonances.
> - Check that the stereo picture is fairly evenly spread, and assess the mono compatibility.
> - Don’t hurry the selection process, and make sure you ratify your choice properly with your different monitoring systems.
> - When you’ve got a promising patch, mute it, recalibrate your ears to the mix as is, and then fade it up to confirm that it’s actually what you’re looking for.

## Blend

You'll want the most natural sounding reverbs for the blending process. Pay special attention to the predelay settings. Predelay cues us into the size of the room. In a large room the predelay would be longer, because it would take more time for the reflections to reflect and come back to the listener. Generally use a predelay between 10-20ms.

Try to blend like elements. Drums should blend, vocals and back ground vocals, horn sections.

> When working with multiple tracks of the same type, you may want to control the send amounts at the same time. There's no easy way to group these send amounts, but we'll use a different method.
> Create a new track and call it `Drum Verb`. Move your FX over to that track by clicking the FX icon and dragging with the `option` key held down. Rename your original reverb track to `Drum Verb Send`. Take the `Drum Verb Send` track out of the master parent send by clicking on the routing and unchecking the `Parent send` checkbox. Finally route the `Drum Verb Send` track to the `Drum Verb` track. Now you have a master control over the send levels of all of the drum tracks. Now it's really easy to automate this reverb as a group. Let's try this now.

## Tone and sustain

Let's move on to the tone and sustain reverbs. These are more more about creatively enhancing the character of the sound. The goal here is not to make the sounds act like their coming from large spaces, but to change the overall tone of the sound. These do not need to sound natural, unlike the blend and size reverbs. Spend some time looking through your reverbs to find the ones that create unique sounds.
