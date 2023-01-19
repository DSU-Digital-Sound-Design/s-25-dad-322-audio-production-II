---
title: "Timing and tuning"
---

Download the [Living in the City](https://cambridge-mt.com/ms/mtk/#HurrayForTheRiffRaff) recordings to use for practicing tempo mapping.

If your track was recorded to a click editing will be much easier. If it wasn't you'll need to adjust the tempo of your DAW to match the recording so that you can do timing editing later.

## Tempo Mapping

To do this we'll need the [SWS / S&M Extension](https://www.sws-extension.org/) package installed.

Set the timebases as shown below:

![](../timbe-base.png)

Set the grid divisions to quarter notes (1/4) in the _Snap/Grid_ settings.

Next, delete the empty time so that your timeline starts with the start of the stick count off.

Make a tempo map to align things to your drums without having it be a strict grid. Click view and tempo map to see the tempo. Use an instrument that plays on the 1 of a measure to make a tempo map. Now you can use the tempo map to align your tracks to the drums.

To create the sample map, we'll use a few SWS extension actions. Open the actions list and search for _sws grid line_. Find the _SWS/BR: Move closest grid line to play cursor_ action and add a shortcut. Close the actions list and experiment with how this works for a minute. Next, add another short cut to the _SWS/BR: Move closest tempo marker to mouse cursor (perform until shortcut released)_ action. You will use the first action to set your tempo markers, and the second action to edit them if needed.

After you make the tempo map you can now edit the drums and other parts to match the real tempo of the song. Group (G) your drum tracks together so you can edit them at the same time. Make sure when you select one item it doesn't select every other item in the group. Next, make sure these options are selected in the options menu:

- Auto-crossfade media items when editing
- Trim content behind media items when editing

Now pick a drum sound that you feel has the most importance. The edits will be in relation to this part. It should probably be the kick or snare. Split it by its transients using "Dynamic split items". Deselect "when get opens" and "when gate closes". Set the transient sensitivity so it selects all of the kicks. Then, set the action to "Split selected and grouped items". Notice how all of your drums are split at the same place as the kick.

If you "split selected and grouped items" then all of your drums will be split based on the snare, or whichever drum you picked. Now do the same process to the other drum, i'll do the kick now. Now quantize your drum group to the grid.

Use the following quanitze settings:

![](../quantize.png)

Go through and check that your crossfades aren't covering up the transients of your kick or snare. Move to each crossfade with "command + ]". If you find a crossfade that's out of place you can move it with the shift key.

Continue this process of quantization to the other instruments in the mix until you can get it to sound as natural as possible, but more metronomic in time.
