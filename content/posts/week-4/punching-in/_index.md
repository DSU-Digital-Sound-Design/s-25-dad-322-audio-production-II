---
title: "Record modes"
---

### Step-by-Step Instructions for Punch In/Punch Out in Reaper DAW

#### Punch In / Punch Out
Punching in and out is a technique used during recording to replace a specific section of an already recorded track without affecting the rest of the track.

#### Time Selection Auto Punch
Time Selection Auto Punch is a feature in Reaper that allows you to define a specific section of your track for re-recording, providing a more flexible and automatic way of punching in and out.

**Setting Time Selection:**

- Highlight the section of the track that you want to replace by making a time selection.
- This can be done by clicking and dragging on the timeline over the area you wish to re-record.

**Configuring Recording Mode:**

- Right-click the record button located at the bottom of your toolbar.
- Select "Record mode: Time Selection Auto Punch".
- This sets Reaper to automatically start and stop recording at the boundaries of your selected time.

**Unlinking Looping and Time Selection (Optional):**
   
- If you want to loop a specific section separately from the time selection, go to "Options".
- Select "Toggle loop points linked to time selection". This separates the loop points from the time selection.

**Setting Up Pre-roll:**
- Access the metronome/pre-roll settings in Reaper.
- Activate "pre-roll before recording". This feature allows for a few seconds of playback before the actual recording starts, helping the performer to get in sync.
- The recording will start automatically at the beginning of the time selection, but the pre-roll ensures that the performer is already in the flow.

#### Selected Item Auto-Punch
Selected Item Auto-Punch is useful when you have multiple sections across the track that need re-recording.

**Slicing and Selecting Items:**
- Use the split tool to slice the track at the beginning and end of each section you wish to re-record.
- Select these individual items. These are the sections that Reaper will focus on during the recording.

 **Configuring Record Mode:**
- Set the record mode to "Selected Item Auto-Punch".
- Reaper will now only record over the selected items, ignoring the unselected parts of the track.

 **Recording:**
- Hit the record button. Reaper will automatically punch in and out of the selected items, allowing you to focus on your performance.

**Pre-roll Consideration:**

- Similar to the Time Selection Auto Punch, you might want to use the pre-roll feature for a smooth start into the sections that are being re-recorded.

**Comping and Finalizing:**
- After recording, you can comp the takes to choose the best parts of each recording.
- This method allows for a more organized approach when dealing with multiple sections needing re-recordings.

Remember, the choice between Time Selection Auto Punch and Selected Item Auto-Punch largely depends on the specific requirements of your project and your workflow preference. Experiment with both to find what works best for you.
<!-- 
## Punch in / punch out

Using takes and comping is one way of getting a good performance while recording. But, sometimes you just want to re-record a specific section of a track that you messed up. The easiest way to punch in is to record only the part you want to replace. Reaper will create a take for the part you recorded, allowing you to easily replace it with takes.

## Time selection auto punch

We can re-record specific sections with the _time selection auto punch_ recording mode. It provides a more flexible way to re-record than the simple method listed above without having to manually stop the recording when you want to punch out.

Make a time selection on the part that you want to record over. Go to the record button on the bottom of your toolbar and right click -> Record Mode: time selection auto punch.

If you would like to loop a specific section you can unlink looping and time selection by selecting _Options: Toggle loop points linked to time selection_.

In the metronome settings select _pre-roll before recording_. This allows you to start playing before the section that you want to record over. Reaper will record when you click the record button, but you will only see the material that is in the time selection. The pre-roll helps the performer be ready to play when the selected portion appears. It also makes it easier to edit between the new recording and what's before and after it.

## Selected item auto-punch

If there are multiple places you would like to re-record you can set the record mode to selected item auto-punch. Create splits in items that you want to re-record and select them. Now Reaper will only punch in for the items you have selected. This is a pretty helpful way to get a good performance.

This method is similar to pre-roll. Choose whatever method works best for your and your project. -->
