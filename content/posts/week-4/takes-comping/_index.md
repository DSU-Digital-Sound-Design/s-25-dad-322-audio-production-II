---
title: "Takes and Comping"
---

> Adapted from [#shorts - REAPER 7 - Convert Take Lanes to Fixed Item Lanes - YouTube](https://www.youtube.com/watch?v=Cs70Wle-BPM) and [Track Lanes & Comping in REAPER 7 - YouTube](https://www.youtube.com/watch?v=QKql5MD-dCA)

### Converting Takes to Fixed Item Lanes 

We recorded with traditional take lanes in the previous class, but now we want to convert them to fixed item lanes. This conversion will allow us to take advantage of the new features in Reaper 7.

#### Step 1: Access the Action List

1. **Go to Actions**: Start by navigating to the 'Actions' menu within your project.
2. **Open Action List**: Select 'Action List' to view the available actions that can be performed.

#### Step 2: Find and Execute the Conversion Action

1. **Search for 'Take Explode'**: In the Action List, use the search bar and type in "take explode" to find the specific action needed for conversion.
2. **Execute the Action**: If you have multiple tracks to convert, ensure they are selected. Then, run the action named `Take: explode takes on selected tracks to fixed lanes.`

After executing the action, your traditional take lanes will be converted into the new fixed item lanes. This conversion simplifies take management and aligns your older projects with the new features offered in Reaper 7.

### Introducing Track Lanes

Track lanes are a new feature in Reaper 7, offering an alternative to the traditional stacking of takes. If we want to start off our recordings using track lanes we can do so by enabling them in the Track menu.

1. **Accessing Track Lanes**: Navigate to the options menu and find the 'New recording that overlaps existing media items' section.
2. **Enable Track Lanes**: Choose the 'Add Lanes' option. Now, when you record new takes, Reaper will create separate lanes for each, instead of stacking them on top of each other.
3. **Recording with Track Lanes**: Record additional takes. You'll notice that each new take creates a new lane, rather than stacking on the previous takes.

### Basics of Comping

Comping is a process that allows you to compile the best parts of different takes into a single, seamless track.

1. **Enable Comping**: Right-click on one of the yellow item lanes buttons and choose 'Comping' and then 'Comp into new empty lane'.
2. **Create a Comp Lane**: Reaper will add a new lane, designated for your compiled track.
3. **Selecting the Best Parts**: Play through your takes and use the comping tool to drag and select the best parts from each lane. These selections will appear in your comp lane.
4. **Refining Your Comp**: As you make selections, you can listen to the comp track in real-time, ensuring that the transitions between selections are smooth.
5. **Finalizing Your Comp**: Once you're happy with your comp, you can choose to delete the other lanes or keep them for reference.

### Advanced Comping Techniques


Reaper 7 offers a range of tools and shortcuts to streamline the comping process.

1. **Comp Areas and Choosing Takes**: Define specific areas for comping and easily switch between different takes using keyboard shortcuts or the mouse.
2. **Comp Editing**: Adjust, move, or delete comp areas as needed to refine your track.
3. **Collapsing and Expanding Lanes**: Manage your workspace by collapsing or expanding track lanes.
4. **Final Comp**: Ensure your final comp is exactly how you want it, with the ability to revert to previous states or make last-minute changes.


<!-- 
> see: [Comping Takes in REAPER - YouTube](https://www.youtube.com/watch?v=9zyld5BicWQ)

If you record on top of an media item, Reaper automatically creates takes. This allows you to choose which performance you like better, or compile parts from each performance into a new and better take.

Click on the take to choose which take you hear during playback. Or, use keyboard shortcut _T_ to select next take or _shift + t_ for the previous take.

To comp takes, create splits between phrases. You can then select parts of each performance. If we like the combination of takes we selected, we can select the takes and "crop to active take" (right click -> take -> crop to active take OR shift + command + t).

If we want to be able to compare different comps, we can save the comps instead of cropping to active take (right click -> comp -> save as new comp). Make sure to select all of the items you want in your comp first. Saving a comp allows us to choose a comped take without making our choices permanent. You can switch between comps using _Comp takes: Activate next comp_. You can also rename the active comp, remove it, crop list to active comp, or _move active comp to top lane._ This last option moves your selected comp to the top lane so you can see it more easily. See the other actions for comping takes for other useful actions.

When you decide on the take you want you should lock your takes so that you don't accidentally chose the wrong take. Do this with _Item properties: Lock to active take (mouse click will not change active take)_.

We can now use these techniques to comp together different takes from our percussion recording.

If we're happy with the take or comp we can collapse the take lanes by selecting _Options: Show all takes in lanes (when room)_ and turning it off. -->
