---
layout: post
title: "Neural DSP Archeytpe Gojira Overview"
categories: music neuraldsp
---

## Contents

This article is an overview of the Archtype Gojira plugin by Neural DSP. 

## Opening the Plugin

![Default screen](\assets\img\gojira\default.jpg)

If this is your first time opening the plugin, you'll be greeted by this screen. If you've opened the plugin before, it will open to the screen it was on when you closed it last. 

## Interface Overview

![Top icons](\assets\img\gojira\top-icons.jpg)

The first row of icons are the navigation icons. Clicking each will take you to another section of the plugin. From left to right they are:
- [Pitch shift effects](#pitch-shift-effects) (Whammy, Octaver)
- [Pre effects](#pre-effects) (Overdrive, Distortion, Phaser, Chorus)
- [Amp](#amp-selection) (main screen) 
- [EQ](#eq)
- [Cab and mics](#cab-and-mics)
- [Post effects](#post-effects) (Delay, Reverb)

![Gain controls](\assets\img\gojira\gain-controls-and-presets.jpg)

Next are the gain controls as well as the preset selection. From left to right they are:
1. Input gain
2. Noise gate
3. Input mode
4. Preset selection
5. Output gain

The preset selection icons from left to right are:
1. Save the current preset. 
2. Delete the current preset.
3. Import a preset. 
4. Open the presets folder.

![Amp and cab](\assets\img\gojira\amp-and-cab.jpg)

Next is the amp and cab selection. The amp/cab icons at the bottom from left to right are:
1. [Cln](#cln)
2. [Rust](#rust)
3. [Hot](#hot)

The white icon is the currently selected one.

The chain icon above them will let you mix and match the different heads and cabs. See the [Amp Selection](#amp-selection) section for more information. 

![Settings](\assets\img\gojira\bottom-icons.jpg)

The bottom row of icons from left to right are:
1. Audio settings
2. Midi mappings
3. Tuner
4. Metronome

The metronome isn't really a metronome, but it acts as a tap tempo for the delay pedal. See the [Post Effects](#post-effects) section for more information.

Then in the far bottom right is the window size selection. Clicking that will bring up the option to resize the window to small, medium, or large. 

## Amp Selection

There are three types of amps in the Archetype Gojira plugin. They're called Cln, Rust, and Hot. They each have their own independant parameters, and you can switch between the amps without losing those settings. 

### Cln

This is the clean amp. 

![Clean amp](\assets\img\gojira\amp-clean.jpg)

The settings from left to right are:
1. Bright switch. This enhances the sparkle of the signal.
2. Gain. This controls the amount of gain in the preamp section.
3. Bass/Mid/Treble. These control the EQ of the amp.
4. Level. This controls the output level of the amp.
5. Power switch. This will disable the amp. 

### Rust

This is the crunch amp.

![Crunch amp](\assets\img\gojira\amp-crunch.jpg)

The settings from left to right are:
1. Gain. This controls the amount of gain in the preamp section.
2. Low/Mid/High. These control the EQ of the amp.
3. Master. This controls the overall volume of the amp. 
4. Presence. This boosts the higher frequencies of the amp.
5. Depth. This boosts the lower frequencies of the amp.
6. Level. This controls the output level of the amp.
7. Power switch. This will disable the amp.

### Hot

This is the high gain amp. 

![High gain amp](\assets\img\gojira\default.jpg)

It has all the same knobs as the Rust amp. However, they're still independant of one another. Switching amps will not carry the settings over. 

## Pitch Shift Effects

![Pitch shift effects](\assets\img\gojira\pitch-shift.jpg)

The Archetype Gojira comes with two ptich shifting effects. From left to right they are:
1. Wow
2. Oct

### Wow

The Wow pedal is a whammy pedal, much like the Digitech Whammy. It can tune your signal up, down, or act as a harmonizer depending on the mode. 

The effect is engaged with the toggle switch, and the amount of pitch shifting is controlled with the expression pedal.

The **Fatso Dry/Wet** knob controls how much of the fatso effect is blended into your dry signal. Turning the knob all the way to the left will give you a completely dry signal. Turning the knob all the way to the right will give you a completely wet signal.

The pedal has three modes:

1. Fatso. This adds an extra layer to the signal. It goes from one octave down (expression pedal toe up) to one octave up (expression pedal toe down). Depending on the Dry/Wet mix, Fatso can act as a detune pedal or a harmonizer.

    Setting the Dry/Wet knob to noon will let you use the pedal as a harmonizer.  

    Setting the Dry/Wet to fully wet will make the pedal act as a detuner. 

    To find the unison setting, set the expression pedal toe up then go 22 clicks towards toe down. Every two clicks towards toe down will raise the pitch one half step. Every two clicks towards toe up will lower the pitch one half step. 

2. Blade 1. This will shift the signal from unison (toe up) to one octave up (toe down). 

3. Blade 2. This will shift the signal from unison (toe up) to two octaves up (toe down.

The Dry/Wet knob is disabled when using Blade 1 and Blade 2.

You can disable or enable this entire section by right clicking on the icon at the top of the plugin.

### Oct

The Oct pedal is an octaver. It blends two layers, one octave down and two octaves down, into your dry signal.

The effect is engaged with the toggle switch.

The signal blending is controlled by the three knobs.

1. Oct1. This controls the amount of the one octave down layer.

2. Oct2. This controls the amount of the two octaves down layer.

3. Level. This controls the amount of dry signal.

To achieve a completely dry signal, turn the Oct1 and Oct2 knobs all the way to the left, and the level knob all the way to the right.

Turning the Level knob all the way to the left will remove the dry signal. 

## Pre Effects

![Pre Effects](/assets/img/gojira/pre-effects.jpg)

There are four pre effects pedals. They are OD, DST, PHSR, and CHR. 

1. OD. This is an overdrive pedal.

    The effect is engaged with the toggle switch.

    The **Dist** knob controls the amount of distortion.

    The **Level** knob controls the overall volume of the pedal.

    The **Tone** knob controls the treble frequencies. Turning it all the way to the right will let all of the high frequencies through. Turning it all the way to the left will cut a fair amount of the high frequencies, and some of the high-mids. 

2. DST. This is a distortion pedal.

    The effect is engaged with the toggle switch.

    The **Dist** knob controls the amount of distortion.

    The **Vol** knob controls the overall volume of the pedal.

    The **Filter** knob is a high pass filter and controls the tone of the pedal. Turn it all the way to the right to decrease the high frequencies. Turning it all the way to the left will allow the high frequencies to come through.

3. PHSR. This is a phaser pedal.

    The effect is engaged with the toggle switch.

    The **Rate** knob controls the overall rate of the phasing effect. 

4. CHR. This is a chorus pedal.

    The effect is engaged with the toggle switch.

    The **Rate** knob controls the speed of the chorus effect.

    The **Depth** knob controls how extreme the chorus sound is by changing the amount of pitch-shifting and delay created.

    The **Feedback** knob controls how strong the effect is.

    The **Mix** knob controls the blend amount of the wet and dry signals. All the way to the right is fully wet. All the way to the left is fully dry.

You can disable or enable this entire section by right clicking the icon at the top of the plugin.

## EQ

![EQ](/assets\img\gojira\eq.jpg)

This is the EQ section, which features a 9-band graphic EQ used to further sculpt your tone. It lets you boost or cut frequencies from 65 Hz up to 16 kHz. 

Note that each of the three amps have their own separate EQ, so changing the EQ on one amp will not affect the other. 

The EQ can be disabled or enabled by using the **on/off** switch or by right clicking the icon at the top of the plugin. However, disabling by right clicking **will** disable it for all three amps. Disabling it by using the on/off switch will only disable it for the current amp.

## Cab and Mics

![Cab and mics](/assets\img\gojira\mics.jpg)

This is the cab section, where you can choose from 6 different mics, a single or dual mic setup, or load your own cab IRs. 

The mics available to choose from are:

1. Dynamic 57
2. Dynamic 421
3. Condensor 414
4. Condensor 184
5. Ribbon 160
6. Ribbon 121

You're able to mix and match these however you like to achieve your desired sound. You can also disable either of the mics using the **active** switch at the bottom for a single mic setup. 

The **Position** knob controls the position of the mic in relatin to the speaker cone. A higher number will move the mic towards the outer edge. A lower number will move it closer to the center.

The **Distance** knob controls the distance of the mic from the speaker. A higher number will move it farther away from the speaker. A lower number will move it closer. 

The **Level** knob controls the overall volume of the mic, which lets you blend the sounds of the mics together. 

The **Pan** knob controls the stereo panning of the mic signal. 

The **Phase** switch located below pan will invert the phase of the mic signal.

You can also click and drag each mic into the position you want. Dragging left/right will change the position, while dragging up/down will change the distance.

## Post Effects

![Post effects](/assets\img\gojira\post-effects.jpg)

The post effects section has two pedals: DLY and REV.

1. DLY. This is a delay pedal.

    The effect is engaged with the **Engage** toggle switch.

    The **Dry/Wet** knob controls the volume of the effect added to the dry signal.

    The **Feedback** knob controls the amount of delay repeats added to the dry signal. 

    The **Tape Sat** knob adds a subtle drive to the delay repeats.

    The **Tempo** knob adjusts the BPM of the delay.

    The **Time** knob changes the delay subdivision ranging from 1/64T to 1/1D. You have the option of triplet, dotted, or straight notes. 

    The **Tone** controls the frequency range of the low pass filter applied to the delay. 

    The **Sync** switch will sync the delay time to your DAW when enabled. When disabled you can set the time manually by adjusting the **Time** knob, using the **Tap Tempo** switch, or by using the metronome located at the bottom of the plugin. 

    The **Ping Pong** switch will enable the ping pong delay effect, which bounces the repeats from left/right across the stereo image. 

    The **Mod** switch adds a pitch modulation effect to the delay repeats. 

2. REV. This is a reverb pedal.

    The effect is engaged with the toggle switch.

    The **Dry/Wet** knob controls the volume of the effect added to the dry signal.

    The **Time** knob controls the duration of the reverb decay envelope. 

    The **High Pass Filter** knob controls the frequency range of the high pass filter applied to the recerb.

    The **Low Pass Filter** knob controls the frequency range of the low pass filter applied to the reverb.

    The **Shimmer** switch enables the shimmer effect, which layers a tail of reverb pitched up an octave on top of the dry signal.

