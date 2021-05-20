# Markov-Step-Sequencer-for-Live (Senior Independent Study Comp Sci Project)
This application is a sequencer made in Max, that uses Markov chains in order to “improvise” new sequences based off of what the user originally inputted. Users play notes in Ableton Live. These notes are then quantized and fed into the Markov model.
The GUI of the patch allows user to change the tempo and the quantization parameters for the model. This improvising sequencer is intended for live use as an accompaniment or as a creative recording tool.

## Instructions (Step 1-4 are only necessary for primary installation)
1. First download and open the folder (inside of which are two Max Patches)
2. One patch is labeled Untitled Device, and the other Metronomo_2 (Adapted from Rodolfo Cangiotti https://cycling74.com/author/568d412cd78f77af5a3d0f80)
3. Find and open the file within the Ableton User Library, and copy both Patches into the folder (...\User Library\Presets\MIDI Effects\Max MIDI Effect)
4. Now, opening Ableton Live, navigate to Max for Live, and then open the Max Midi Effect folder, and drag Untitled Device.amxd into that folder
5. Open an instrument midi track, and then drag Untitled Device onto any instrument you wish to play
6. In the bottom window in Ableton, where the device's GUI is now displayed, match your tempo with that of Ableton, pick your quantization, and you are now ready to play (See image below)
https://github.com/DamonHollenbeck/Markov-Step-Sequencer-for-Live/blob/main/Images/GUI.png
7. If you wish to stop the sequencer and reset the model, simply click the button next to the tempo and quantization adjuster
