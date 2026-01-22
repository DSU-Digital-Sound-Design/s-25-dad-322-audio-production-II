---
title: "Importing and Organizing Audio Projects in Reaper"
---

Download the [Living in the City](https://cambridge-mt.com/ms/mtk/#HurrayForTheRiffRaff) mix from Cambridge Multi-tracks. After downloading your project, create a new Reaper project. Configure your project settings to mirror the following:

![](../project-settings.png)

Begin by reviewing the notes accompanying the tracks to determine the correct BPM (Beats Per Minute). Next, import your tracks into the project, ensuring they are sequentially ordered and color-coded based on the type of track.

Group similar tracks into dedicated folders. For instance, consolidate all drum tracks into a 'Drums' folder, and all guitar tracks into a 'Guitars' folder, and so on. Employ the track manager for efficient organization of projects with an extensive number of tracks.


## Trimming Silence

The next phase involves refining each track by eliminating silences and areas where sound from other instruments spill into a given mic. Trimming unnecessary audio cleans up the tracks and deepens your familiarity with the mix. Pay close attention to any flaws in the recording, addressing them before starting the mixing process.

This procedure is called "strip silence" in various Digital Audio Workstations (DAWs).

In Reaper, this can be accomplished using the "Dynamic Split" feature. To begin, enlarge the track using "shift + !" and then press "D" to launch the dynamic split dialogue. Opt for "when gate opens" and "when gate closes". Adjust the gate threshold until you achieve a satisfactory result. Exercise caution to avoid over-trimming, as excessive cutting can yield an unnaturally abrupt sound. Initially, apply this technique on a vocal track for practice.

This action helps automate the process:

> "Item: Auto trim/split items (remove silence)..."

Use these settings:

![](../auto-trim.png)

Finish the process by listening to each of the tracks soloed and ensuring that no audio has been inadvertently removed.



## Color-Coding and Track Renaming

Color-coding and renaming tracks are essential for maintaining a clear overview of your project. This practice enhances your workflow and helps you quickly identify specific tracks. For instance, you might color-code all drum tracks in blue, guitar tracks in green, and vocal tracks in red. This visual organization simplifies the mixing process and streamlines your workflow. You can also rename tracks to reflect the instrument or part they represent, such as "Kick Drum" or "Lead Guitar." 

## Regions and Markers

Regions and markers are indispensable tools for navigating your project. Regions are used to define sections of your project, such as verses, choruses, and bridges. Markers, on the other hand, are used to highlight specific points in your project, such as key changes or significant events. By utilizing regions and markers effectively, you can easily navigate your project and make precise edits and adjustments.

Use the following shortcuts to create regions and markers:
- To create a region: make a time selection and type `shift + R`
- To create a marker: `m`

## Utilizing a Reference Mix

1. Create a folder containing all your project tracks.
2. Place your reference mix track outside this folder. Ensure that this track does not route through your master channel if you're using any master effects.
3. Calibrate the loudness of your reference mix using a LUFS Meter, balancing between the readings of the meter and your auditory judgment.
4. Facilitate comparison (A/B testing) between your mix and the reference mix. In Reaper, you can solo tracks exclusively using option + command.
5. Consider adding additional reference tracks as needed.