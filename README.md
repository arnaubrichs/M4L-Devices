# M4L-Devices
Repository for my custom-made Max for Live Devices.

## Installation

Download the folder and drag and drop the .amxd files into your Ableton Live session. 

The folder contains the following devices, orgnanized by categories:

### Processing

- [HarmPercSeparation 1.0](https://maxforlive.com/library/device/7920/harmpercseparation): Performs harmonic/percussive separation using Flucoma's [HPSS algorithm](https://learn.flucoma.org/reference/hpss/).
- [Audio Transport 1.0](https://maxforlive.com/library/device.php?id=8281): Enables morphing and hybridisation between two sounds.

### Dynamics

- [MIDI Gain](https://maxforlive.com/library/device/8221/midi-enveloper): Gate a sound using a MIDI input.
- Onset Detector: Using Flucoma's [Onset detection](https://learn.flucoma.org/reference/onsetslice/) algorithm, send a bang to a custom-named reciever. 

### Panning

- MC Stereo Panner: Takes up to 32 channels in (using MC recievers), and pans them to a stereo field.

### Utility

- [MultiMap Receiver 1.0](https://maxforlive.com/library/device/8060/multimap-receiver): Map any parameter in Live to anything sent from a global send object in Live or Max.
- [Note Toggle Map 1.0](https://maxforlive.com/library/device/8074/note-toggle-map): Allows you to toggle a mapped parameter or button with incoming MIDI note ons/offs.
- Note Trigger Map v.2: Modified version of the classic [Note Trigger Map](https://maxforlive.com/library/device/7056/note-trigger-map	), but implementing a "sample-and-hold" upon being triggered.

### MIDI
- NoteSwap4L: Use the device in combination with "OnsetPitch Detector". The notes sent from that device are swapped with the incoming MIDI note data.
