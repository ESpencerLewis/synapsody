# Synapsody

![preview](media/intro_preview.gif)

An interactive experience that lets participants see their own brain activity in real time while interacting with music — watch your synapses fire as you learn to control your brainwaves and explore your innate creativity.

Synapsody is a **1-2 player music game**. Each player wears an EEG headset; consciously relaxing or focusing changes the music in real time and is illuminated live on a 3D brain sculpture/visualization.

<img src="media/brain_viz.jpg" width="70%">

Intro video (compressed): [media/Synapsody_Intro_compressed.mp4](media/Synapsody_Intro_compressed.mp4)

## Why

Synapsody is built on the idea that music is more than cultural experience — as music professor Lee Bartel (University of Toronto) has argued, it's a stimulus with real cognitive and memory effects on the brain. Neurofeedback using EEG monitoring is already an effective form of cognitive therapy; Synapsody's premise is that using music itself as the neurofeedback signal could push that method further. It connects three elements — neurofeedback, music, and health — into a single brain-controlled interface aimed at optimizing cognition and brain health.

## Technology

- EEG headset for real-time brainwave capture
- [Petal Metrics](https://petalmetrics.com/) — bridges Muse EEG data over Bluetooth into OSC
- [TouchDesigner](https://derivative.ca/) — real-time EEG-to-OSC pipeline, visualization, and show control
- [KalmanJS](https://github.com/wouterbulten/kalmanjs) — signal filtering for EEG data
- 3D brain model with real-time synaptic mapping driven by live EEG signal
- Original interactive, nonlinear music composition mapped to brainwave data (relax/focus)

## Credits

- **Elle Spencer Lewis** — interactive design, TouchDesigner programming, audio-reactive signal architecture, music composition, EEG data acquisition and filtering
- **Jeff Smith** (CEO of Eye Vapor) — developed the original brain visualization, visual design and TouchDesigner programming
- **Dr. Adam Gazzaley** (neuroscientist, UCSF) — advised on mapping the brain visualization to each sensor on the specific EEG headset used

## Related

- [pixeldriver/](pixeldriver/) — a prototype exploring a physical exhibit counterpart, mapping live EEG data to an LED bank propagated through fiber-optic cable and 3D-printed synapse structures.
- [two-player/](two-player/) — an iteration built around simultaneous two-player interaction.
- [brain-display/](brain-display/) — the core 3D brain visualization component.

## Status

Synapsody has gone through multiple research iterations, including work conducted through an ASU-affiliated research collaboration. This project is under active development and being evaluated for IP protection, so production source files and implementation-level detail are not published in this repository.

## Requirements

- [TouchDesigner](https://derivative.ca/) (macOS)
