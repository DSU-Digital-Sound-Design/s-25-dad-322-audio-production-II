+++
title = "Supplemental Monitoring"
outputs = ["Reveal"]
[reveal_hugo]
custom_theme = "reveal-hugo/themes/sunblind.css"
margin = 0.2
+++

<!-- show_notes = "separate-page" -->

## Real-world playback systems

- Monitors don't sound like what we listen to music on for fun
- they're good at:
  - for investigating what’s going on across the whole frequency spectrum, especially at the frequency extremes;
  - for judging the impact of mix processing on the sheer quality of your sounds;
  - for evaluating and adjusting the stereo image;
  - for understanding how your mix will sound on more high-fidelity listening
    systems;
  - for impressing the pants off the artist, client, or anyone else in the room
    with you!

{{< note >}}
Because of this other monitoring solutions can be better than nearfield monitors. We still need the nearfields to create a baseline but its equally as important to check mixes in real-world situations.
{{</ note>}}

---

## Auratone 5C Super Sound Cube

![](auratone.jpg)

{{% note %}}

- Used on Adele’s 21, Dire Straits’s Brothers In Arms, and Michael Jackson’s Thriller,
- The problem is that they're not manufactured anymore, so how can we use their qualities?

{{% /note %}}

---

## Quotes

> “I love Auratones!” enthuses Jackson’s long time producer and engineer Bruce Swedien. “You know what Quincy [Jones] calls them? The Truth Speakers! There’s no hype with an Auratone. . . . Probably 80 percent of the mix is done on Auratones, and then I’ll have a final listen or two on the big speakers.”

---

Tom Elmhirst on working with Adele:

> “When I mix I’ll be jumping around for the first couple of hours playing the track loudly via my [nearfields], and once I know the bottom end is rocking, I’ll mix with low volume on the Auratones for the rest of the day. If I can make a mix work on the Auratones, I know I’m flying.

---

## Midrange focus

- portless
- single, small driver focuses us to the midrange

> “The real perspective lives in that range,” says Jack Joseph Puig. “It doesn’t live in the highs, it doesn’t live in the lows. That’s what really speaks to the heart.”

{{% note %}}

- This is the range that is most likely to reach your listeners ears
- This is the most common range to the most common listening devices
- if you list all the devices most of them are only producing midrange
- mobile devices, clock radios, and a lot of TVs, music-player docking stations, and portable wireless speakers

{{% /note %}}

---

![](auratone_frequency_response.png)

---

## Mono compatibility

- we can listen to just one to check how it would sound without stereo imaging
- most listening environments won't have sweet spots that people sit in regularly
- or acoustic treatment etc
- headphones are the best place to experience stereo

{{% note %}}
Many other systems don’t even make a token stab at stereo! Things such as telephone hold systems, band/ club PAs, and shopping-center announcement systems all typically sum their inputs to mono before feeding any speakers. FM radio receivers also often automatically sum the audio to mono in order to improve reception in the presence of a weak transmitted signal.

So, we should always check mixes in real-world situations, with speakers that produce the range of frequencies and without stereo imaging.

{{% /note %}}

---

## Auratone substitutes??

- We have the [Behritone](https://www.behringer.com/product.html;jsessionid=EE0AAD9D1FF08794D2BD596CF6DB6EBA?modelCode=P0A9N)
- It's speaker C, you need to sum to mono first before listening
- lets do some comparisons to the farfields

---

## Headphones

- perhaps the most common listening device currently
- The stereo image will sound different on headphones than on speakers
- they also block out background noise so can be useful for doing detailed listening
- also easier to hear bad edits, clipping, pops etc
- its good to have a pair that you are familiar with the sound of

{{% note %}}
What’s more important about headphones is that almost all of them transmit each side of your mix exclusively to one ear, whereas with speakers the two stereo channels are always heard to some extent by both ears. For this reason the stereo image is much wider on headphones (the image encompass- ing an angle of 180 degrees, where speakers only cover around 60 degrees), and any sound at the stereo extremes feels disconnected from the rest of the mix as a result.

{{% /note %}}

---

## Grotboxes

- It may also be useful to listen on computer speakers
- or in a car
- or any random place you can find

---

## Low end damage limitation

### Mixing the low end - averaging the room

{{% note %}}
Although one of the problems with room resonances is that they vary as you move your monitoring position, this is also the key to one useful workaround: if you make a point of listening to the bass response from several different locations, then it’s actually possible to average your impressions mentally to some extent. In a room with resonance problems, you’ll find that all aspects of the bass balance will vary as you move around. If a particular bass note, for example, appears to be too loud in some places but too quiet in others, then you can hazard a guess that the overall level may be in the right ballpark, whereas a note that remains too loud all around the room probably needs reining in.

Let's try this with some music, write down your reactions to the bass instruments: kickdrum, bass guitar ect.
{{% /note %}}

---

## Spectrum Analysis and Metering

> “I put [a spectrum analyzer] across my stereo buss that lets me know when the bottom end is right,” says Chiccarelli. “I’m mainly looking at the balance of the octaves on the bottom end, like if there’s too much 30Hz but not enough 50Hz or 80Hz. When you go to a lot of rooms, that’s where the problem areas of the control room are.”

- [Voxengo Span](https://www.voxengo.com/product/span/), [MAnalyzer](https://www.meldaproduction.com/MAnalyzer)

{{% note %}}

- We can get some important information about our low end from a spectrum analyzer
- Remember also that spectrum analyzers can evaluate individual tracks as well as whole mixes, and they’re particularly handy for highlighting if the internal frequency components of a bass part are shifting from note to note—a problem that all too often scup- pers small-studio balances.

{{% /note %}}

---

## Using span

- Hide statistics
- cmd + click: solos specific frequency ranges - creates a band pass filter
- option + scroll: changes the Q
- hold will freeze the graph in place to analyze a certain part of the song
- settings:
  - block size: average out the spectrum. Play with different block sizes then put it at 8192. Now raise the average to smooth out the peaks.
  - smoothing: further tame the peaks with smoothing. Try different settings then put it at 1/4 octave.
- right click to copy frequency to clipboard
- You can now use this to compare the general harmonic content of this track to other reference tracks.

---

## More display settings

- freq lo
- freq high
- range lo
- range hi
- mid/side balance - see the spectral content on the sides of your mix

---

## Preemptive fixes for the low end

- high pass every track, this will clean up the mix and make everything sound much more clear
- take out as much as you can without changing the timbre of the sound, this will take some experimenting
- see how the mix looks different in your analyzer now
