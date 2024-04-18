---
title: "Envelopes & Automation"
---

## Automation and Envelope Basics 

### Automating Parameters
- To access the track envelopes click the `Trim` button on the track control panel. Here you can set the automation mode, view and edit envelopes for parameters such as volume, pan, pre-effects parameters, and mute. If your track has sends and effects, those envelopes will show up here as well. 

### Working with Volume Envelopes
- You can select the volume envelope by clicking on the `Trim` button, or by typing `V` on your keyboard. By default, all automation envelopes use the `Trim/Read` mode. 
  - **Trim/Read mode:** The volume fader acts as a "trim" control, adjusting the volume up or down from the existing volume automation. This allows you to make global volume changes while preserving the shape of the automation.
- Techniques for creating and editing volume envelopes:
  - Draw automation freehand using the pen tool `(Ctrl/Cmd)`.
  - Create single points with the `shift` key then click to create points. 
  - Delete points one by one by clicking them while holding `Alt/Option`.
  - Copy and paste points to return to previous automation levels in different sections. This also works when you select multiple points.
  - Adjusting envelope segments between points with Alt+Shift/Option+Shift.
    - First, create two points at the beginning and end of the segment you want to adjust.
    - This is known as a `four-point envelope` and is useful for automating changes for different song sections more easily.
    - You can also do this by creating a time selection and then adjusting the envelope fader on the left in the track control panel. 
  - Using a time selection to automatically create and adjust envelope segments.
    - Do this using `Shift+Control/Command`.

### Real-Time Automation Writing
- Change the automation mode to "Write" for real-time automation writing.
- Be sure to switch back to `Trim/Read` mode after writing automation to prevent unintentional changes.
- If you want to see the fader move while playing the track back, switch to `Read` mode. You can't adjust the fader in this mode, but you can see the automation move the fader.

### Writing Pan Automation
- Try the same procedure to write pan automation. Open the envelope by clicking the `P` key.
- When writing to a second envelope, make sure that only one envelope is armed for writing at a time.

### Managing Envelopes
- You can bypass and hide envelopes during playback from the `Envelopes` dialogue.
- Move envelopes to the Media Lane for easier manipulation and visibility.


### Additional Automation Modes
- Introduction to "Touch" and "Latch" automation modes.
  - "Touch" mode: Automation is written only while the fader is touched; it reverts upon release.
  - "Latch" mode: Once touched, the fader continues to write automation until playback stops, regardless of whether it is still being held.

## Automation Items

- Automation items are a separate type of item in Reaper that can be used to automate various parameters like volume, panning, effects, etc. Automation items are more flexible than just using track automation, as they can be moved, duplicated, and edited independently of the audio items.

- **Creating the Automation Item**
  - Create an `Automation Item` by clicking `Alt`, then dragging along the envelope on the timeline.
  - Double-click the item to open the automation item editor.

- **Configuring Automation Settings**
  - Adjust the automation item properties to set the LFO to a square wave.
  - Tune the cycles of the square wave to achieve the desired stutter speed (8 cycles for slower, 16 for faster).
  - You can also stretch or shrink the automation item the same way as you would an audio item.

- **Manipulating and Replicating Automation Items**
  - Copying automation items to reuse the effect at different parts of the song.
  - Using pooled automation items to ensure simultaneous adjustments across copies.
    - To copy and pool an automation item, hold `Ctrl/Cmd + Alt` while dragging the item.

- **Advanced Automation Techniques**
  - Copy automation items to other parameters like panning.


.


