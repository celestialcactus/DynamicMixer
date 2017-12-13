# DynamicTouchMixer
This patch is the framework for a dynamic track mixer. The purpose is to be able to use touch devices through max to mix and fade multiple tracks for a live performance. The system uses nodes to pull position data, and interperet preset data. This in turn manipulates sliders controlling track volume. 
(THIS IS ONLY A PROTOTYPE) This mixer is in a working conceptual stage, as the finalized concept would require a much more rugged device pairing capability. The ideal would be to have a dynamic mixer controlled with any kind of XY reading device and audio pulled from mixer tracks in ableton. As of now the audio is sourced from premade audio files.

*Application* 
Live dynamic mixing done on the fly. I originally thought that having a live dynamic mixer would be cool for stage performances as well as for background music in a Dungeons and Dragons game. All of the mixing could be fluidly controlled with one device, allowing to build dynamic sound tracks on the fly. It can also be used to test how your soundtrack would sound in a video game when different inputs are active. 

*User Review* 
Device works as should and is simple to use in terms of functionality. However, more work needs to be done in terms of content as listening to the same 16 bar loops can get boring rather quickly. The device used (Wacom tablet) needs to have a direct link to the patch.

*Development*
Development was harsh, as initially the plan was to have a direct link to the Wacom tablet to be able to draw data. This would have given a user the ability to draw and visualize audio on a spectrum, while having the waveform play from that data. However, the Wacom device has had virtually no support or documentation. I decided to revert to a simpler idea (Dynamic Mixer). 

*HOW DO I USE THIS THING?*
1. Click the open buttons that are located below the three sliders/mixers. Load any of the Wav files located within the WavsInteractive folder into each mixer.
2. Hit the Bang button located above "Bangbang". This will arm and start the playback of each file at the same time. 
3. Use your wacom device (or mouse really) to navigate the cursor in the nodes window to the bottom left of the patch (the one with the color circles). (Or for those of you who are color blind... the square window with the numbers).
*By clicking/pressing and dragging, you can drag the cursor to raise the audio levels of certain tracks. Dragging to number 9 will have all of the audio tracks level.
Once you get bored, you can insert your own audio files if you would like. 
