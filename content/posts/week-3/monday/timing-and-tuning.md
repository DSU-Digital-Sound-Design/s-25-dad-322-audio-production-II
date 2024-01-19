---
title: "Tempo mapping in Reaper"
---

## Setup

### 1. Download Practice Materials

We'll use the `Living in the City` recording from the previous exercise. These will serve as your base for practicing tempo mapping.

### 2. Check Recording Tempo

Determine whether the song was recorded to a click:
- **If it was:** Editing will be more straightforward.
- **If it wasn't:** You'll need to manually adjust the Reaper tempo to match the recording, enabling precise timing editing later.

## Implementing Tempo Mapping

Tempo mapping is essential for aligning your tracks, especially when working with recordings not made to a click. It ensures that your edits and additions synchronize perfectly with the existing tempo. The goal is to be able to play a metronome along with the track and have it match the tempo of the song.

### 1. Prepare Your Tools and Environment

- **Install Necessary Extensions**: Ensure you have the [SWS / S&M Extension](https://www.sws-extension.org/) package installed in Reaper.
- **Configure Timebases**: Set your timebases to match the image provided.
  
![Timebase Configuration](../timbe-base.png)

- **Adjust Grid Settings**: In Reaper's _Snap/Grid_ settings, set the grid divisions to quarter notes (1/4).
- **Set Tempo** - set the tempo so that the downbeat of the song matches the second measure on the Reaper grid.

### 2. Clean Your Timeline

- **Delete Empty Time**: Remove any silence or space at the beginning of your timeline. This ensures that your timeline starts precisely at the beginning of the stick count-off.

### 3. Create a Flexible Tempo Map

- **Access the Tempo Map**: Navigate to 'View' in your Reaper, and select 'Tempo Envelope' to visualize the current tempo.
- **Align With a Steady Instrument**: Use an instrument track that plays a constant rhythm throughout the song as a reference for your tempo map. I'll use the snare drum in this example.

### 4. Use SWS Extension Actions for Precision

- **Mark the Beats**: While listening to the track, add a marker at the start of each bar.
- **Convert Markers to Tempo Markers**: Utilize the SWS extension action "Convert project markers to tempo markers". This will transform your markers into tempo changes.
- **Organize Your Markers**: Perform this step before adding any organizational markers.
- **Clear Stretch Markers**: Remove any stretch markers, as they won't be needed in this session.

### 5. Verify Your Tempo Map

- **Review Marker Placement**: Ensure that all tempo markers are correctly positioned, aligning accurately with the beat of the track.

## Label Song Sections with Markers

Now that we're done using markers to tempo map the song we can use them to distinguish different sections of the song. Insert markers with the `M` shortcut. You can oversee all markers effortlessly in the _Region/Marker Manager_.
